<template>
  <section class="section-five">
    <div class="text-white position-relative overflow-hidden">
      <div class="section-five__text-1">
        <div class="text-1__content">
          <h4>Lorem ipsum dolor sit.</h4>
          <p>
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ea earum
            qui eveniet atque excepturi, culpa quos voluptate, consequuntur
            quod, natus necessitatibus quaerat? Exercitationem, repellendus
            assumenda. Quibusdam porro laborum fugiat consectetur.
          </p>
        </div>
      </div>
      <div class="section-five__text-2">
        <p class="text-2__content">
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eum dolorem
          fugit repellendus commodi modi hic reprehenderit, veniam doloremque
          sint officiis adipisci accusamus! Quia, in quos pariatur facilis iusto
          natus rem perspiciatis fuga a, at magnam.
        </p>
      </div>
      <div class="cellphone p-4 rounded-5 position-absolute">
        <div
          :class="`screen ${cellphone_on} w-100 h-100 rounded-4 position-relative overflow-hidden`"
          @click="handleClick"
        >
          <div
            class="bg-secondary-1 m-auto rounded-pill position-absolute start-0 end-0 z-3"
            style="width: 200px; height: 30px; top: -12px"
          >
            <div
              class="bg-white w-25 m-auto rounded-pill position-absolute top-0 start-0 end-0 bottom-0"
              style="height: 6px"
            ></div>
          </div>
          <div class="screen__off w-100 h-100 position-absolute"></div>
          <div
            class="screen__content bg-white px-3 pt-4 text-black w-100 h-100 position-absolute overflow-y-auto"
          >
            <h2 class="fs-4">Lorem, ipsum dolor.</h2>
            <p>
              Lorem ipsum dolor, sit amet consectetur adipisicing elit.
              Distinctio nobis doloribus provident maiores ullam iusto.
            </p>
            <strong>Lorem, ipsum dolor.</strong>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Voluptatum ex omnis esse quisquam aperiam sint, impedit ut fugit,
              nulla, consequuntur voluptatem voluptate ad hic voluptatibus
              deserunt officiis doloribus. Rem, earum.
            </p>
            <strong>Lorem, ipsum.</strong>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Optio
              dolor a, voluptatibus ducimus obcaecati velit tempora
              reprehenderit consequuntur repellendus in unde ratione sint
              officiis molestiae ea laboriosam perspiciatis dolores perferendis
              ipsam quo.
            </p>
            <ul>
              <li>Lorem, ipsum dolor.</li>
              <li>Lorem ipsum dolor sit amet consectetur.</li>
              <li>Lorem ipsum dolor sit.</li>
              <li>Lorem, ipsum dolor.</li>
            </ul>
          </div>
        </div>
        <div class="bg-secondary-1 cellphone__btn-one rounded-pill"></div>
        <div class="bg-secondary-1 cellphone__btn-two rounded-pill"></div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      cellphone_on: "",
    };
  },
  methods: {
    handleClick() {
      this.cellphone_on == "screen--active"
        ? (this.cellphone_on = "")
        : (this.cellphone_on = "screen--active");
    },
  },
};
</script>
