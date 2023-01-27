<template>
  <nav class="headroom headroom--fixed">
    <font-awesome-icon icon="fa-solid fa-bars" />
    <div
      class="w-100 text-center d-flex align-items-center justify-content-center"
    >
      <font-awesome-icon class="me-2" icon="fa-solid fa-image" />
      <h1 class="fs-6 m-0">Lorem, ipsum dolor.</h1>
    </div>
  </nav>
</template>

<script>
import { library } from "@fortawesome/fontawesome-svg-core";
import { faBars, faImage } from "@fortawesome/free-solid-svg-icons";
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";
import Headroom from "headroom.js";

library.add(faBars, faImage);

export default {
  components: {
    FontAwesomeIcon,
  },
  mounted() {
    this.mountNavigation();
  },
  methods: {
    mountNavigation() {
      const nav = document.querySelector("nav");

      const headroom = new Headroom(nav);

      headroom.init();
    },
  },
};
</script>
