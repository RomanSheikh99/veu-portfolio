<script setup>
import SocialIcons from "./SocialIcons.vue";
</script>


<template>
  <div id="about" class="pt-10 mt-20 w-4/5 flex justify-between items-center mx-auto">
    <div
      class="w-2/5 animate__animated animate__delay-2s animate__slower animate__infinite animate__swing"
    >
      <img src="../assets/img/bannerImg.png" alt="" />
    </div>
    <div class="w-3/5 text-white leading-4">
      <h1 class="text-5xl font-bold my-5 animate__animated animate__fadeInUp">
        About Me
      </h1>
      <p
        class="w-3/4 text-base text-justify mb-6 animate__animated animate__fadeInUp"
      >
        I would like to introduce myself to you as I believe I am a passionate
        and dedicated person. I am always eager to learn different and new
        technologies related to web development and ICT. Expert to understand
        documentation and handle errors. Also, I have good communication skills.
        I can organize any team and event. I am always ready to prove myself
        through my dedication, sincerity, and the highest level of
        professionalism.
        <br /><br />
        I am studying for a diploma in engineering in the Department of computer
        technology. Recently I finished a full-stack web development course with
        the highest marks. A proud member of Bangladesh Rover Scout. I am
        passionate about coding.
      </p>
      <a
        class="px-4 py-1 text-2xl rounded-lg animate__animated animate__fadeInUp"
        href=""
      >
        My Resume
      </a>
      <SocialIcons />
    </div>
  </div>
</template>

<style scoped>
#about a {
  background-color: hsla(160, 100%, 37%, 1);
}
#about img {
  max-width: 100%;
}
</style>
