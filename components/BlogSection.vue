<template>
  <section class="blog-area blog-default-area">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 m-auto">
          <div
            class="section-title text-center"
            data-aos="fade-up"
            data-aos-duration="1000"
          >
            <h2 class="title">News Of Company</h2>
            <div class="separator-line mt-14">
              <img class="me-1" src="/images/shape/line-s2.png" alt="image" />
              <img src="/images/shape/line-s1.png" alt="image" />
            </div>
            <div class="desc">
              <p class="mt-21">
                Lorem Ipsum is simply dummy text of the printing and typesetting
                industry has been the industry's standard dummy text ever since
                the printer took
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="row" data-aos="fade-up" data-aos-duration="1100">
        <div
          class="col-md-6 col-lg-4"
          v-for="(blog, index) in blogs"
          :key="index"
        >
          <div class="post-item mb-md-50">
            <div class="thumb">
              <NuxtLink to="/blog-details">
                <img :src="blog.imgSrc" :alt="blog.title" />
              </NuxtLink>
              <div class="meta">
                <NuxtLink to="/blog" class="post-date">{{
                  blog.date
                }}</NuxtLink>
                <button class="post-comment">
                  <i class="icofont-speech-comments"></i> {{ blog.comment }}
                </button>
                <button class="post-like">
                  <i class="icofont-heart"></i>{{ blog.like }}
                </button>
              </div>
            </div>
            <div class="content">
              <div class="category-inner">
                <img src="/images/shape/line-s1.png" alt="image" />
                <NuxtLink to="/blog" class="category">{{
                  blog.category
                }}</NuxtLink>
              </div>
              <h4 class="title">
                <NuxtLink to="/blog-details">{{ blog.title }}</NuxtLink>
              </h4>
              <p>{{ blog.excerpt }}</p>
              <NuxtLink
                to="/blog-details"
                class="btn btn-theme btn-border btn-gray"
              >
                Read More <i class="icon icofont-long-arrow-right"></i>
              </NuxtLink>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      blogs: [
        {
          id: 101,
          imgSrc: "/images/blog/01.jpg",
          title: "We work in the fields of UI/UX design and art direction.",
          excerpt:
            "Lorem Ipsum is simply dummy text the printing and typesetting industry. Lorem Ipsum has been the industry's standard printer.",
          date: "21 March, 2021",
          comment: 2566,
          like: 750,
          category: "Business/Marketing",
        },
        {
          id: 102,
          imgSrc: "/images/blog/02.jpg",
          title: "printing and type setting industry has been printer.",
          excerpt:
            "Lorem Ipsum is simply dummy text the printing and typesetting industry. Lorem Ipsum has been the industry's standard printer.",
          date: "17 June, 2021",
          comment: 3345,
          like: 980,
          category: "Development/Design",
        },
        {
          id: 103,
          imgSrc: "/images/blog/03.jpg",
          title: "We work in the fields of UI/UX design and art direction.",
          excerpt:
            "Lorem Ipsum is simply dummy text the printing and typesetting industry. Lorem Ipsum has been the industry's standard printer.",
          date: "28 May, 2021",
          comment: 1450,
          like: 380,
          category: "Fashion/Style",
        },
      ],
    };
  },
};
</script>
