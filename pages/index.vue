<template>
  <!-- <Tutorial/> -->
  <div>
    <h1>Welcome to my site !!</h1>
    <p>
    {{'werwerew'}}</p>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
  data() {
    return {
      title: "Welcome to my site",
      description:
        "Bu yerdan seo haqida o'zbekcha ma'lumotlar topishingiz mumkin, nafaqat seo va boshqa generativ tizimlar haqida ham",
    };
  },
  mounted() {
},
  head() {
    return {
      title: this.title,
      description: this.description,
      meta: [
        {
          hid: "og:title",
          name: "og:title",
          content: this.title,
        },
        {
          hid: "og:description",
          name: "og:description",
          content: this.description,
        },
        {
          hid: "og:url",
          name: "og:url",
          // content: `${window.location.host}${this.$route.path}`,
        },
        { hid: "og:type", name: "og:type", content: "shopping" },
        {
          hid: "og:keywords",
          name: "og:keywords",
          content:
            "nuxtjs, seo, javascript,seo haqida, development, software,uzbekcha seo ,malumot homepage,khasan,meta tag,meta teg,teg,mega,robots",
        },
      ],
    };
  },
};
</script>
