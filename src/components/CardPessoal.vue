<template>
	<div class="card-pessoal">
		<div class="card-header">
			<v-avatar size="90" class="mb-4">
				<img src="http://github.com/guigagb.png" alt="avatar" />
			</v-avatar>
			<h3 class="person-name">Guilherme Trindade</h3>
			<label class="position small-text">Programador Fullstack</label>
		</div>
		<div id="scrollbar2" data-scrollbar="true" tabindex="-1">
			<div class="info-pessoal py-4">
				<div class="info-pessoal-group">
					<h5 class="bold">Cidade:</h5>
					<label>Brasília</label>
				</div>
				<div class="info-pessoal-group">
					<h5 class="bold">Estado:</h5>
					<label>Distrito Federal</label>
				</div>
				<div class="info-pessoal-group">
					<h5 class="bold">Idade:</h5>
					<label>26 Anos</label>
				</div>
			</div>
			<v-divider></v-divider>
			<slot class="card-pessoal-content mt-2" name="card-pessoal-content"></slot>
			<div class="container-lang-skill">
				<div class="lang-skill">
					<v-progress-circular :value="100" size="50" color="primary">
						<span>100%</span>
					</v-progress-circular>
					<h4 class="pt-3">Português</h4>
				</div>
				<div class="lang-skill">
					<v-progress-circular :value="50" size="50" color="primary">
						<span>50%</span>
					</v-progress-circular>
					<h4 class="pt-3">Inglês</h4>
				</div>
			</div>
			<v-divider></v-divider>
			<div class="py-4">
				<h5 class="light">Apaixonado por programação.</h5>
				<h5 class="light pt-2">Movido por desafios.</h5>
			</div>
		</div>
		<social-media class="d-none d-md-flex d-lg-flex d-xl-flex"></social-media>
	</div>
</template>

<script>
import SocialMedia from "./SocialMedia.vue";
export default {
	components: { SocialMedia },
};
</script>

<style lang="sass">
#app .container-main .card-pessoal
	background: red
	height: 100%
	flex-grow: 1
	position: relative
	background: #20202a
	box-shadow: 0 3px 8px 0 rgba(15, 15, 20, 0.2)
	min-width: 290px
	width: 290px
	overflow: hidden
	padding-bottom: 45px

#app .container-main .card-pessoal .card-header
	display: flex
	flex-direction: column
	padding: 30px 0
	align-items: center
	min-height: 210px
	width: 100%
	background: linear-gradient(159deg, rgba(37, 37, 50, 0.98) 0%, rgba(35, 35, 45, 0.98) 100%)
	box-shadow: 0 1px 4px 0 rgba(15, 15, 20, 0.1)

#app .container-main .card-pessoal #scrollbar2
	overflow: auto
	outline: none
	padding: 0 30px
	height: calc( 100% - 210px)
	display: flex
	flex-direction: column

#app .container-main .card-pessoal #scrollbar2 .info-pessoal-group
	display: flex
	justify-content: space-between
	padding-top: 2px

#app .container-main .card-pessoal #scrollbar2 .card-pessoal-content
	flex-grow: 1

#app .container-main .card-pessoal #scrollbar2 .container-lang-skill
	display: flex
	justify-content: space-around
	padding: 15px 0

#app .container-main .card-pessoal #scrollbar2 .container-lang-skill .lang-skill
	display: flex
	flex-direction: column
	align-items: center
	justify-content: center

#app .container-main .card-pessoal #scrollbar2 .container-lang-skill .lang-skill span
	color: #8c8c8e
	font-size: 10px

#app .container-main .card-pessoal #scrollbar2 .container-lang-skill .lang-skill h4
	font-weight: 500
</style>