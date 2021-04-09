<template>
	<div class="card-resumo">
		<div class="card-skill frontend">
			<div class="title">
				<h5>FRONTEND</h5>
				<v-divider></v-divider>
			</div>
			<div class="conteudo">
				<div class="mb-4">
					<h5>Avançado</h5>
					<div class="container-chips">
						<v-chip class="mr-2 mb-2" small outlined dark color="blue">HTML</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="blue">CSS</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="blue">Javascript</v-chip>
					</div>
				</div>
				<div class="mb-4">
					<h5>Intermediário</h5>
					<div class="container-chips">
						<v-chip class="mr-2 mb-2" small outlined dark color="blue">Vue</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="blue">Vuex</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="blue">Vuetify</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="blue">Quasar</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="blue">Bootstrap</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="blue">Jquery</v-chip>
					</div>
				</div>
				<div class="mb-4">
					<h5>Básico</h5>
					<div class="container-chips">
						<v-chip class="mr-2 mb-2" small outlined dark color="blue">Delphi</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="blue">Tailwind</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="blue">SASS</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="blue">React</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="blue">Nuxt</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="blue">Electron</v-chip>
					</div>
				</div>
			</div>
		</div>
		<div class="card-skill backend">
			<div class="title">
				<h5>BACKEND</h5>
				<v-divider></v-divider>
			</div>
			<div class="conteudo">
				<div class="mb-4">
					<h5>Intermediário</h5>
					<div class="container-chips">
						<v-chip class="mr-2 mb-2" small outlined dark color="red">Node</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="red">PHP</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="red">Delphi</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="red">Express</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="red">Rest</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="red">Git</v-chip>
					</div>
				</div>
				<div class="mb-4">
					<h5>Básico</h5>
					<div class="container-chips">
						<v-chip class="mr-2 mb-2" small outlined dark color="red">Typescript</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="red">Graphql</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="red">Java</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="red">Python</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="red">C++</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="red">Ionic</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="red">Jest</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="red">Arduino</v-chip>
					</div>
				</div>
			</div>
		</div>
		<div class="card-skill mobile">
			<div class="title">
				<h5>MOBILE</h5>
				<v-divider></v-divider>
			</div>
			<div class="conteudo">
				<div class="mb-4">
					<h5>Intermediário</h5>
					<div class="container-chips">
						<v-chip class="mr-2 mb-2" small outlined dark color="green">Quasar</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="green">PWA</v-chip>
					</div>
				</div>
				<div class="mb-4">
					<h5>Básico</h5>
					<div class="container-chips">
						<v-chip class="mr-2 mb-2" small outlined dark color="green">React Native</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="green">Java</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="green">Ionic</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="green">Cordova</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="green">Flutter</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="green">SDK</v-chip>
					</div>
				</div>
			</div>
		</div>
		<div class="card-skill database">
			<div class="title">
				<h5>DATABASE</h5>
				<v-divider></v-divider>
			</div>
			<div class="conteudo">
				<div class="mb-4">
					<h5>Avançado</h5>
					<div class="container-chips">
						<v-chip class="mr-2 mb-2" small outlined dark color="orange">SQL</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="orange">Firebird</v-chip>
					</div>
				</div>
				<div class="mb-4">
					<h5>Intermediário</h5>
					<div class="container-chips">
						<v-chip class="mr-2 mb-2" small outlined dark color="orange">MySQL</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="orange">SQLite</v-chip>
					</div>
				</div>
				<div class="mb-4">
					<h5>Básico</h5>
					<div class="container-chips">
						<v-chip class="mr-2 mb-2" small outlined dark color="orange">NoSQL</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="orange">Firebase</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="orange">Migration</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="orange">TypeORM</v-chip>
						<v-chip class="mr-2 mb-2" small outlined dark color="orange">PowerBi</v-chip>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {};
</script>

<style lang="sass">
#app .container-main .card-resumo
	height: 100%
	flex-grow: 12
	padding: 15px
	display: flex
	flex-wrap: wrap
	justify-content: center
	overflow-y: auto

#app .container-main .card-skill
	background: linear-gradient(159deg, #2d2d3a 0%, #2b2b35 100%)
	display: flex
	flex-direction: column
	padding: 0
	flex-grow: 1
	margin-bottom: 15px
	margin: 8px 8px 8px 8px

#app .container-main .card-skill.frontend,
#app .container-main .card-skill.backend
	max-width: calc((100% - 32px) / 2)

#app .container-main .card-skill.mobile,
#app .container-main .card-skill.database
	max-width: calc((100% - 32px) / 2)

// #app .container-main .card-skill.database
// 	max-width: 40%

#app .container-main .card-skill .title
	padding: 5px 10px

#app .container-main .card-skill.frontend .title h5
	color: #27a4fb !important
	font-weight: 500
	font-size: 1.2rem

#app .container-main .card-skill.frontend .title hr
	border-color: #27a4fb !important

#app .container-main .card-skill.backend .title h5
	color: #F44336 !important
	font-weight: 500
	font-size: 1.2rem

#app .container-main .card-skill.backend .title hr
	border-color: #F44336 !important

#app .container-main .card-skill.mobile .title h5
	color: #4CAF50 !important
	font-weight: 500
	font-size: 1.2rem

#app .container-main .card-skill.mobile .title hr
	border-color: #4CAF50 !important

#app .container-main .card-skill.database .title h5
	color: #ff9800 !important
	font-weight: 500
	font-size: 1.2rem

#app .container-main .card-skill.database .title hr
	border-color: #ff9800 !important

#app .container-main .card-skill .conteudo
	padding: 5px 15px

#app .container-main .card-skill .conteudo .container-chips
	width: 100%
	display: flex
	flex-wrap: wrap
	margin-top: 5px

@media (max-width: 960px)

	#app .container-main .card-skill
		margin: 0px 0px 8px 0px

	#app .container-main .card-skill.frontend,
	#app .container-main .card-skill.backend,
	#app .container-main .card-skill.mobile,
	#app .container-main .card-skill.database
		max-width: 100%
</style>