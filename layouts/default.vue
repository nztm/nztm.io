<template>
  <div>
    <nuxt />
  </div>
</template>

<style lang="stylus">

html
	font-family 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif
	font-size 16px
	word-spacing 1px
	-ms-text-size-adjust 100%
	-webkit-text-size-adjust 100%
	-moz-osx-font-smoothing grayscale
	-webkit-font-smoothing antialiased
	box-sizing border-box
*,
*:before,
*:after
	box-sizing border-box
	margin 0

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
