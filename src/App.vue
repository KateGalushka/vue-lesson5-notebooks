<template>
	<product-panel :cardList="notebooksList"/>
</template>

<script>
import { notebooksList } from './constants/3_data_notebooks.js';
import ProductPanel from './components/ProductPanel.vue';

export default {
    name: 'App',
    components: { ProductPanel },
	 data(){
		return {
			notebooksList
		}
	}
}
</script>

<style>

</style>
