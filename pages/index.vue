<template lang="pug">
html
  body
    section.container
      .box
        img.icon(src="~/assets/img/icon.png" srcset="~/assets/img/icon@2x.png 2x, ~/assets/img/icon@3x.png 3x")
        p.name Tomohiro Nozaki
        p.job Front-end Engineer / Designer
        .skill
          p Vue.js / Nuxt.js / Expo
          p Motion Animation / Web Design
          p Photograph / Tech Blogger
        .btn
          a.tw-btn(href="https://twitter.com/nztm_tw")
            i.fab.fa-twitter
          a.insta-btn(href="https://www.instagram.com/nztm_insta")
            i.fab.fa-instagram
          a.fb-btn(href="https://www.facebook.com/profile.php?id=100012512234101")
            i.fab.fa-facebook-f
</template>
