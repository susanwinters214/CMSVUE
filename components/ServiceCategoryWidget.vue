<template>
  <div class="widget" data-aos="fade-up" data-aos-duration="1000">
    <h3 class="widget-title">Service Category</h3>
    <div class="separator-line">
      <img class="me-1" src="/images/shape/line-s2.png" alt="Image-HasTech" />
      <img src="/images/shape/line-s1.png" alt="Image-HasTech" />
    </div>
    <div class="widget-category">
      <NuxtLink
        to="/service"
        v-for="(category, index) in categories"
        :key="index"
      >
        <i class="icofont-double-right"></i>
        {{ category }}
      </NuxtLink>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      categories: [
        "Web Development",
        "Search Engine Optimization",
        "Digital Marketing",
      ],
    };
  },
};
</script>
