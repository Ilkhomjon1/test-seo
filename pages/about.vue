<template lang="html">
  <div>
    <!-- <p>
      Nuxt gives you 3 different ways to add meta data to your application:
      Globally using the nuxt.config.js Locally using the head as an object
      Locally using the head as a function so that you have access to data and
      computed properties. Global Settings Nuxt lets you define all default tags
      for your application inside the nuxt.config.js file using the head
      property. This is very useful for adding a default title and description
      tag for SEO purposes or for setting the viewport or adding the favicon.
      This will give you the same title and description on every page Local
      Settings You can also add titles and meta for each page by setting the
      head property inside your script tag on every page: This example will use
      head as an object to set a title and description only for the home page
      pages/index.vue This example will use head as a function to set a title
      and description only for the home page. By using a function you have
      access to data and computed properties Nuxt uses vue-meta to update the
      document head and meta attributes of your application. To avoid any
      duplication when used in child components, please give a unique identifier
      with the hid key to the meta description. This way vue-meta will know that
      it has to overwrite the default tag. Learn more about the options
      available for head, in the vue-meta documentation . External Resources You
      can include external resources such as scripts and fonts by adding them
      globally to the nuxt.config.js or locally in the head object or function.
      You can also pass each resource an optional body: true to include the
      resource before the closingtag. Global Settings nuxt.config.js
    </p> -->
  </div>
</template>
<script>
export default {
  data() {
    return {
      title: "Seo haqida uzbekcha malumot",
      description:
        "Spagetti va köfte uchun ochmisiz? Brauzeringizga “Mening yonimdagi italyan restorani” deb yozsangiz, kechki ovqat bir marta bosish masofasida. Sizning biznesingiz makaron ishlab chiqaradimi yoki konsalting xizmatlarini taqdim etadimi, mijozlar saytingizni qidirganda qaysi kalit so'zlardan foydalanayotganini bilishingiz kerak. Agar siz Internetda topilmoqchi bo'lsangiz, maqolalaringiz va sahifalaringiz uchun to'g'ri kalit so'zlardan foydalanish muhimdir. Boshqacha qilib aytganda, to'g'ri kalit so'zlar qidiruv tizimini optimallashtirishni (SEO) yaxshilaydi. Xo'sh, eng yaxshi kalit so'zlar nima ekanligini qanday bilasiz? Qo'shimcha ma'lumot olish uchun o'qing!",
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
        },
        { hid: "og:type", name: "og:type", content: "shopping" },
        {
          hid: "og:keywords",
          name: "og:keywords",
          content:
            "nuxtjs, seo, javascript,seo haqida, development, software,uzbekcha seo ,malumot homepage,khasan,meta tag,meta teg,teg,mega,robots,qidiruv,tizim,tizimi,qidiruv tizimini optimallashtirishni yaxshilash,optimallashtirish,optimay qidiruv tizimi",
        },
      ],
    };
  },
};
</script>
<style lang=""></style>
