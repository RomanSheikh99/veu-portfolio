<template>
  <div class="w-3/4 mx-auto mt-32">
    <h1 class="text-6xl my-4 w-700 text-white">Some Project I Do!</h1>
    <div>
      <!-- product for odd number  -->
      <div
        data-aos="fade-up-right"
        style="grid-template-columns: 2fr 1fr"
        class="project grid gap-8 justify-center items-center rounded-lg my-8 shadow-md shadow-gray-600"
      >
        <div class="text-white px-4">
          <h1 class="text-4xl mb-4">Sunglass Hut</h1>
          <p class="text-base text-justify mb-4">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Vero
            doloremque voluptate quaerat ad fugiat, accusantium aliquid minus,
            cumque architecto beatae ratione facere. Lorem ipsum dolor, sit amet
            consectetur adipisicing. Obcaecati ex dolorum!
          </p>
          <a class="text-lg dtls-btn" href="">See Details</a>
        </div>
        <div class="">
          <img
            class="max-w-full rounded-r-lg"
            src="../assets/img/product.jpeg"
            alt=""
          />
        </div>
      </div>
      <!-- product for odd number  end  -->
      <!-- product for even number  -->
      <div
        data-aos="fade-up-left"
        style="grid-template-columns: 1fr 2fr"
        class="project grid gap-8 justify-center items-center rounded-lg my-8 shadow-md shadow-gray-600"
      >
        <div class="">
          <img
            class="max-w-full rounded-l-lg"
            src="../assets/img/product.jpeg"
            alt=""
          />
        </div>
        <div class="text-white px-4">
          <h1 class="text-4xl mb-4">Sunglass Hut</h1>
          <p class="text-base text-justify mb-4">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Vero
            doloremque voluptate quaerat ad fugiat, accusantium aliquid minus,
            cumque architecto beatae ratione facere. Lorem ipsum dolor, sit amet
            consectetur adipisicing. Obcaecati ex dolorum!
          </p>
          <a class="text-lg dtls-btn" href="">See Details</a>
        </div>
      </div>
      <!-- product for even number  end  -->
    </div>
  </div>
</template>


<style scoped>
.project a {
  color: hsla(160, 100%, 37%, 1);
}
</style>