<template>
	<v-app>
		<v-main class="pa-4 full-height">
			<div class="container-main d-flex">
				<card-pessoal>
					<template v-slot:card-pessoal-content>
						<card-resumo class="mt-1 hidden-md-and-up"></card-resumo>
						<v-divider class="mt-2 hidden-md-and-up"></v-divider>
					</template>
				</card-pessoal>
				<card-resumo class="d-none d-md-flex d-lg-flex d-xl-flex"></card-resumo>
				<!-- <menu-right></menu-right> -->
			</div>
			<social-media class="hidden-md-and-up"></social-media>
		</v-main>
	</v-app>
</template>

<script>
import CardPessoal from "./components/CardPessoal.vue";
import CardResumo from "./components/CardResumo.vue";
import SocialMedia from "./components/SocialMedia.vue";
// import MenuRight from "./components/MenuRight.vue";

export default {
	name: "App",

	// components: { CardPessoal, CardResumo, MenuRight },
	components: { CardPessoal, CardResumo, SocialMedia },

	data: () => ({
		//
	}),
};
</script>

<style lang="sass">
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap')

[data-scrollbar]
	display: block
	position: relative

html
	overflow: hidden !important

body
	height: 100vh
	width: 100%
	overflow: hidden

.full-height
	height: 100%

h1, h2, h3, h4, h5, h6
	color: #FAFAFC

.small-text
	font-size: 12px

.theme--light.v-divider
	border-color: #8c8c8e

.light
	font-weight: 300
	color: #FAFAFC

a
	text-decoration: none

#app
	height: 100vh
	width: 100vw
	background: #191923
	overflow: hidden
	color: #8c8c8e
	font-family: 'Poppins', sans-serif
	font-size: 14px

#app .container-main
	max-width: 1440px
	margin-left: auto
	margin-right: auto
	background: #1e1e28
	background-size: cover
	width: 100%
	height: 100%
	position: relative
	overflow: hidden
	-webkit-box-shadow: 0 3px 8px 0 rgba(15, 15, 20, 0.2)
	box-shadow: 0 3px 8px 0 rgba(15, 15, 20, 0.2)

::-webkit-scrollbar
	width: 2px
	height: 2px

::-webkit-scrollbar-button
	width: 0px
	height: 0px

::-webkit-scrollbar-thumb
	background: #6b6b6b
	border: 0px none #ffffff
	border-radius: 50px

::-webkit-scrollbar-thumb:hover
	background: #ffffff

::-webkit-scrollbar-thumb:active
	background: #000000

::-webkit-scrollbar-track
	background: #373737
	border: 0px none #ffffff
	border-radius: 50px

::-webkit-scrollbar-track:hover
	background: #666666

::-webkit-scrollbar-track:active
	background: #333333

::-webkit-scrollbar-corner
	background: transparent
</style>
