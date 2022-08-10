<script setup></script>

<template>
  <div class="banner pt-10 w-4/5 flex justify-between items-center mx-auto">
    <div class="text-white leading-4 animate__animated animate__backInLeft">
      <h1 class="text-3xl">Hello</h1>
      <h1
        class="text-5xl font-bold my-5 animate__animated animate__delay-2s animate__fadeInUp"
      >
        This Is Roman
      </h1>
      <p class="w-3/4 text-base text-justify">
        A passionate and dedicated Web Developer. Quick learner to new
        technology and Expert to understand documentation and handle errors.
      </p>
      <span class="banner-btn"
        >Scroll For More
        <a href="#about">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            className="h-6 w-6"
            fill="none"
            viewBox="0 0 24 24"
            stroke="#fff"
            strokeWidth="{2}"
          >
            <path
              strokeLinecap="round"
              strokeLinejoin="round"
              d="M19 14l-7 7m0 0l-7-7m7 7V3"
            />
          </svg> </a
      ></span>
    </div>
    <div
      class="animate__animated animate__delay-2s animate__repeat-2 animate__tada"
    >
      <img src="../assets/img/a.png" alt="" />
    </div>
  </div>
</template>


<style scoped>
.banner img {
  max-width: 120%;
}

.banner-btn{
  display: flex;
  align-items: center;
  margin: 20px 0px;
}

.banner-btn a{
  background: hsla(160, 100%, 37%, 1);
  width: 28px;
  display: inline-block;
  padding: 6px;
  border-radius: 50%;
  margin-left: 5px;
}
</style>