<template lang="html">
  <div>
    <!-- <p>
      Meta tags are snippets of code that tell search engines important
      information about your web page, such as how they should display it in
      search results. They also tell web browsers how to display it to visitors.
      Every web page has meta tags, but they’re only visible in the HTML code.
      In this guide, you’ll learn how to use, and not to use, the six most
      important meta tags for SEO: Meta title Meta description Meta robots Meta
      refresh redirect Meta charset Meta viewport Meta title This is the page
      title that Google and most other search engines show in search results.
    </p> -->
  </div>
</template>
<script>
export default {
  data() {
    return {
      title: "Welcome to my site",
      description:
        "Kontentingizni yaratishda siz kalit so'z tadqiqotingizdagi juda ko'p atamalarni kiritmasligingiz kerak. Google ham, bizning bepul kalit so'z vositamiz ham sizga faqat muhim, ammo majburiy bo'lmagan takliflarni beradi. Matningizni har doim foydalanuvchilar uchun o'qilishi va qiziqarli bo'ladigan tarzda yozing. O'tmishdagi turli yangilanishlar orqali Google endi foydalanuvchilarga haqiqiy qiymat bermaydigan ortiqcha optimallashtirilgan SEO matnlarini aniqlay oladi. Shuning uchun, siz har doim o'zingizdan foydalanuvchilaringiz uchun kontent yaratishda nimaga qiziqayotganini so'rashingiz kerak. Buni ovozli kalit so'zlarni o'rganish bilan birlashtirish sizga foydalanuvchilar uchun qimmatli va qidiruv tizimlari uchun optimallashtirilgan tarkibni yaratishga yordam beradi.",
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
     
        { hid: "og:type", name: "og:type", content: "shopping" },
        {
          hid: "og:keywords",
          name: "og:keywords",
          content:
            "nuxtjs, seo, javascript,seo haqida, development, software,uzbekcha seo ,malumot homepage,khasan,meta tag,meta teg,teg,mega,robots,search,engine,optimization,seo,optimization,uzbekcha,ma'lumot,",
        },
      ],
    };
  },
};
</script>
<style lang="css"></style>
