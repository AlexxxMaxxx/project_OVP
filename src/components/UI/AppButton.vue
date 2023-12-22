<template>
	<!--<button class="btn" block rounded="lg" size="x-large">
	</button>-->
	<v-btn
	 variant="tonal" 
	 density="comfortable"
	 rounded="lg">
	  <slot></slot>
	</v-btn>
</template>

<script>
export default {
	name: 'app-button',
}
</script>
