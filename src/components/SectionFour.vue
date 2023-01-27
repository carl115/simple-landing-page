<template>
  <section class="section-four p-5">
    <div class="mb-4 text-center">
      <h2>Lorem ipsum dolor sit.</h2>
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Illum labore
        rerum corporis distinctio id fugiat suscipit optio quam dolorum! Nam!
      </p>
    </div>
    <div class="row">
      <div
        class="bg-secondary-1 p-3 col-md-6 d-flex flex-column justify-content-between"
      >
        <div>
          <font-awesome-icon class="fs-1" icon="fa-solid fa-image" />
        </div>
        <p>Lorem, ipsum dolor.</p>
        <h3>Lorem ipsum dolor sit amet.</h3>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam
          ducimus voluptatem enim fugiat quam. Placeat voluptatum sapiente,
          dolorum deleniti perferendis reprehenderit nihil provident molestias
          fuga repellat minus accusamus voluptate, hic iste quo illo corporis
          quis voluptatem excepturi? Beatae, voluptas labore.
        </p>
        <div>
          <button class="section-four__button">Lorem, ipsum.</button>
        </div>
      </div>
      <div class="col-md-6 d-flex flex-column justify-content-between">
        <div class="my-4">
          <p>Lorem ipsum dolor sit.</p>
          <strong>Lorem ipsum dolor sit amet consectetur.</strong>
          <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Error
            deserunt quisquam dolor aliquid neque culpa veniam officiis aliquam,
            quae, recusandae voluptas ullam fugit minima numquam tempore
            mollitia sit blanditiis. Aperiam.
          </p>
        </div>
        <div class="my-4">
          <p>Lorem ipsum dolor sit.</p>
          <strong>Lorem ipsum dolor sit amet consectetur.</strong>
          <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Error
            deserunt quisquam dolor aliquid neque culpa veniam officiis aliquam,
            quae, recusandae voluptas ullam fugit minima numquam tempore
            mollitia sit blanditiis. Aperiam.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import { library } from "@fortawesome/fontawesome-svg-core";
import { faImage } from "@fortawesome/free-solid-svg-icons";
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";

library.add(faImage);

export default {
  components: {
    FontAwesomeIcon,
  },
};
</script>
