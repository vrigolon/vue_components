<template>
	<v-app>
		<app-menu />
		<app-toolbar />
		<v-content>
			<app-carousel />
		</v-content>
		<app-footer />
		
	</v-app>
</template>

<script>
import Footer from './Footer.vue'
import Carousel from './Carousel'
import Toolbar from './Toolbar'
import Menu from './Menu.vue'



export default {
	components: { 'app-footer': Footer, 'app-carousel': Carousel, 'app-toolbar': Toolbar, 'app-menu':Menu },

}
</script>
