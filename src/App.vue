<template>
	<v-app>
		<v-main class="pa-4 full-height">
			<div class="container-main d-flex">
				<card-pessoal></card-pessoal>
				<card-resumo></card-resumo>
			</div>
		</v-main>
	</v-app>
</template>

<script>
import CardPessoal from "./components/CardPessoal.vue";
import CardResumo from "./components/CardResumo.vue";
export default {
	name: "App",

	components: { CardPessoal, CardResumo },

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
	width: 100%
	background: #191923
	overflow: hidden
	color: #8c8c8e
	font-family: 'Poppins', sans-serif
	font-size: 14px

#app .container-main
	background: #1e1e28
	height: 100%
	box-shadow: 0 3px 8px 0 rgba(15, 15, 20, 0.2)
</style>
