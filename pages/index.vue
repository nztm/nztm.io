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

<style lang="stylus">
body
	background-color #2c3134
.container
	margin 0 auto
	min-height 100vh
	display flex
	justify-content center
	align-items center
	text-align center

.icon
	margin -130px 0 0 0

.box
	margin 130px 30px 0 30px
	width 470px
	height 500px
	-webkit-backdrop-filter blur(30px)
	backdrop-filter blur(30px)
	box-shadow 0 10px 10px 0 rgba(55, 67, 116, 0.25)
	background-color #fff
	border-radius 40px

.name
	margin-top -15px
	font-family 'M PLUS Rounded 1c', sans-serif
	font-size 30px
	font-weight bold
	font-style normal
	font-stretch normal
	line-height 1.5
	letter-spacing normal
	text-align center
	color #707070

.job
	margin 5px 0
	font-family 'M PLUS Rounded 1c', sans-serif
	font-size 15px
	font-weight bold
	font-style normal
	font-stretch normal
	line-height 1.47
	letter-spacing normal
	text-align center
	color #b5b5b5

.skill
	padding 10px 0
	font-family 'M PLUS 1p', sans-serif
	font-size 18px
	font-weight 500
	font-style normal
	font-stretch normal
	line-height 1.5
	letter-spacing normal
	text-align center
	color #b5b5b5

.btn
	margin-top 40px
	display flex
	justify-content center

.tw-btn
	width 70px
	height 70px
	margin 5px
	border-radius 10px
	-webkit-backdrop-filter blur(30px)
	backdrop-filter blur(30px)
	box-shadow 0 10px 15px 0 rgba(55, 67, 116, 0.25)
	background-color #74BBE8
	color #fff
	font-size 34px
	text-decoration none
	display flex
	align-items center
	justify-content center

.insta-btn
	width 70px
	height 70px
	margin 5px
	border-radius 10px
	-webkit-backdrop-filter blur(30px)
	backdrop-filter blur(30px)
	box-shadow 0 10px 15px 0 rgba(55, 67, 116, 0.25)
	background-image linear-gradient(225deg, #ff9300, #fa3a93 50%, #f457e2)
	color #fff
	font-size 34px
	text-decoration none
	display flex
	align-items center
	justify-content center

.fb-btn
	width 70px
	height 70px
	margin 5px
	border-radius 10px
	-webkit-backdrop-filter blur(30px)
	backdrop-filter blur(30px)
	box-shadow 0 10px 15px 0 rgba(55, 67, 116, 0.25)
	background-color #4b76d5
	color #fff
	font-size 34px
	text-decoration none
	display flex
	align-items center
	justify-content center
</style>
