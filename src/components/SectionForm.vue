<template>
  <section class="section-form p-5">
    <div class="row">
      <div class="col-md-6">
        <h3>Lorem, ipsum dolor.</h3>
        <div class="section-form__image-profile mt-5">
          <div class="image-profile__photo fs-4">
            <font-awesome-icon icon="fa-solid fa-camera" />
          </div>
          <div>
            <strong>Lorem ipsum dolor sit.</strong>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ut sint
              consequatur harum nisi, modi hic.
            </p>
          </div>
        </div>
      </div>
      <div class="col-md-6">
        <h5>Lorem, ipsum</h5>
        <form class="mt-5">
          <div class="mb-3">
            <input type="email" class="form-control" placeholder="Email" />
          </div>
          <div class="mb-3">
            <input
              type="number"
              class="form-control"
              placeholder="Phone number"
            />
          </div>
          <div class="mb-3">
            <textarea
              class="form-control"
              placeholder="Message"
              style="height: 100px; resize: none"
            ></textarea>
          </div>
        </form>
        <button class="section-form__submit">Submit</button>
      </div>
    </div>
  </section>
</template>

<script>
import { library } from "@fortawesome/fontawesome-svg-core";
import { faCamera } from "@fortawesome/free-solid-svg-icons";
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";

library.add(faCamera);

export default {
  components: {
    FontAwesomeIcon,
  },
};
</script>
