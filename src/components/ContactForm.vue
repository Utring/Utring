<template>
  <div class="contact-form-section section-space--ptb_120" id="contact">
    <div class="container">
      <div class="row">
        <div class="col-lg-7 order-2 order-lg-1">
          <div class="section-title text-left section-space--mb_60">
            <h2 class="font-weight--bold mb-15 wow move-up">¡Cooperemos!</h2>
            <span class="section-text_left wow move-up"
              >Seamos socios para construir un mejor futuro.</span
            >
          </div>
          <div class="contact-from-wrapper wow move-up">
            <form @submit.prevent="submitForm">
              <div class="contact-page-form">
                <div class="contact-input">
                  <div class="contact-inner">
                    <input v-model="name" type="text" placeholder="Nombre *" />
                  </div>
                  <div class="contact-inner">
                    <input v-model="email" type="email" placeholder="Email *" />
                  </div>
                </div>
                <div class="contact-inner">
                  <input v-model="subject" type="text" placeholder="Asunto *" />
                </div>
                <div class="contact-inner contact-message">
                  <textarea v-model="text" placeholder="Mensaje *"></textarea>
                </div>
                <div class="contact-submit-btn">
                  <button class="ht-btn ht-btn-md" type="submit">
                    Enviar mensaje
                  </button>
                  <p class="form-messege"></p>
                </div>
              </div>
            </form>
          </div>
        </div>
        <div class="col-lg-5 order-1 order-lg-2">
          <div class="peatures_image-wrap section-space--mb_40">
            <div class="image text-center wow move-up">
              <img
                class="img-fluid"
                src="../assets/img/features/aeroland-contact-form-image-01.png"
                alt="contact thumb"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
    <loading
      :active.sync="isLoading"
      :can-cancel="true"
      :on-cancel="onCancel"
      :is-full-page="fullPage"
    ></loading>
  </div>
</template>

<script>
import Loading from "vue-loading-overlay";
import axios from "axios";
import "vue-loading-overlay/dist/vue-loading.css";

export default {
  name: "ContactForm",
  data() {
    return {
      name: null,
      email: null,
      subject: null,
      text: null,
      isLoading: false,
      fullPage: true,
    };
  },
  components: {
    Loading,
  },
  methods: {
    onCancel() {
      console.log("User cancelled the loader.");
    },
    submitForm() {
      let data = {
        name: this.name,
        email: this.email,
        subject: this.subject,
        text: this.text,
      };
      console.log(data);
      this.isLoading = true;
      axios
        .post("https://utring.herokuapp.com/api/send-email", data)
        .then((response) => {
          console.log(response);
          this.isLoading = false;
        })
        .catch((error) => {
          console.error(error);
          this.isLoading = false;
        });
      this.name = "";
      this.email = "";
      this.firstSon = "";
    },
  },
};
</script>