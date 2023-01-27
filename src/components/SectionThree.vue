<template>
  <section class="section-three py-5">
    <div class="p-md-5 px-3 text-white">
      <div class="row">
        <div class="col-md-6">
          <div class="section-three__video">
            <div class="video__play p-4">
              <font-awesome-icon icon="fa-solid fa-play" />
            </div>
          </div>
        </div>
        <div
          class="col-md-6 text-center d-flex flex-column justify-content-between"
        >
          <div class="row">
            <div class="col-md-12">
              <h2 class="fs-4">Lorem ipsum dolor sit amet.</h2>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Distinctio eaque dignissimos sunt cupiditate, quisquam cumque
                illo recusandae dolorum vel laboriosam aspernatur id sit iste
                reprehenderit delectus error officiis! Ullam, sequi!
              </p>
            </div>
          </div>
          <div class="row">
            <div class="col-md-6">
              <div class="minicard">
                <p>Lorem, ipsum.</p>
              </div>
            </div>
            <div class="col-md-6">
              <div class="minicard">
                <p>Lorem, ipsum.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="row text-center mt-4">
        <div class="col-md-3">
          <div class="minicard">
            <p>Lorem, ipsum.</p>
          </div>
        </div>
        <div class="col-md-3">
          <div class="minicard">
            <p>Lorem, ipsum.</p>
          </div>
        </div>
        <div class="col-md-3">
          <div class="minicard">
            <p>Lorem, ipsum.</p>
          </div>
        </div>
        <div class="col-md-3">
          <div class="minicard">
            <p>Lorem, ipsum.</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import { library } from "@fortawesome/fontawesome-svg-core";
import { faPlay } from "@fortawesome/free-solid-svg-icons";
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";

library.add(faPlay);

export default {
  components: {
    FontAwesomeIcon,
  },
};
</script>
