<template lang="html">
  <div>
    <h1>Android uchun Telegram</h1>
    <p>
      Bu yerda Android qurilmangiz uchun Telegramni yuklab olishingiz mumkin. Bu
      versiya kamroq cheklovlarga ega va bevosita telegram.org saytidan
      avtomatik yangilanishlarni qabul qiladi
    </p>
  </div>
</template>
<script>
export default {
  data() {
    return {
      title: "Khasan Seo Optimization",
      description:
        "O'zbekcha telegram ochish va tilini o'zgartirish, kanallarda odam ko'paytirish,gruppaga odam qo'shish xizmatlari,",
    };
  },
  mounted() {
    console.log(window.location.host + this.$route.path);
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
            "telegram o'rnatish,telegram,kirish,ochish,telegraph,telegram code,o'zbekcha telegram,telegramni o'bekcha qilish,gruppalar,shaxsiy,botlar,kanallar,tanlanganlar,pullik telegram,telegram premium,premium,yangi telegram,xizmatlar,odam qo'shish,qo'shish,ko'paytirish,odam ko'paytirish,telegramda odam ko'paytirish",
        },
      ],
    };
  },
};
</script>
<style lang=""></style>
