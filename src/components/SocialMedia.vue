<template>
	<div class="container-social-media">
		<a href="https://www.github.com/guigagb/" title="github" target="_blank">
			<v-icon color="#8c8c8e">mdi mdi-github</v-icon>
		</a>
		<a href="https://www.linkedin.com/in/guilherme-trindade/" title="linkedin" target="_blank">
			<v-icon color="#8c8c8e">mdi mdi-linkedin</v-icon>
		</a>
		<a href="https://api.whatsapp.com/send?phone=5561983090055" title="whatsapp" target="_blank">
			<v-icon color="#8c8c8e">mdi mdi-whatsapp</v-icon>
		</a>
		<a href="https://t.me/guigagb" title="telegram" target="_blank">
			<v-icon color="#8c8c8e">mdi mdi-telegram</v-icon>
		</a>
	</div>
</template>

<script>
export default {};
</script>

<style lang="sass">
#app  .container-social-media
    background: linear-gradient(159deg, rgba(37, 37, 50, 0.98) 0%, rgba(35, 35, 45, 0.98) 100%)
    box-shadow: 0 1px 4px 0 rgba(15, 15, 20, 0.1)
    position: absolute
    bottom: 0
    left: 0
    width: 100%
    height: 3rem
    display: flex
    align-items: center
    justify-content: space-around

#app .container-social-media i:hover
    color: #f2f2f2 !important
</style>