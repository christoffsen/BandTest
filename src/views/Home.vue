<template>
	<div id="home">
		<h1>Roadtrippers</h1>
		<div v-for="song in songs" :key="song.name">
			<h2>{{song.name}}</h2>
			<iframe :src="song.link" width="640" height="480" allowfullscreen></iframe>
		</div>
	</div>
</template>

<script>
// @ is an alias to /src

export default {
	name: 'Home',
	data() {
		return {
			songs: [
				{"name" : "Locomotive Breath", "link" : "https://drive.google.com/file/d/1zXpsRa5PXEbYV6BHgx-iCwLJOXYGNPA_/preview"}
				,{"name" : "The Letter", "link" : "https://drive.google.com/file/d/1b-pzkCzvNNYl1Ko5Y0T80qpvCeM5UqIH/preview"}
				,{"name" : "Proud Mary", "link" : "https://drive.google.com/file/d/1Kvu42kmCtL6gaEJdgNACYc-gXn21ljOI/preview"}
				,{"name" : "I Saw Her Standing There", "link" : "https://drive.google.com/file/d/1bZ6aOvtl2bLB3VeAvwArkG_2nx-QR97F/preview"}
				,{"name" : "Last Kiss", "link" : "https://drive.google.com/file/d/1gJRzVTTIJfDx9rzvqa26DN0Sfm-zgwQv/preview"}
				,{"name" : "Keep on Runnin'", "link" : "https://drive.google.com/file/d/1qP8BG1zpkNOc_qn5i5kjdPcVKWFBewNi/preview"}
				,{"name" : "No Matter What", "link" : "https://drive.google.com/file/d/11iDgAQAcMAgpWcCeoZcg8EDwMKaFL_Bd/preview"}
				,{"name" : "Dead Flowers", "link" : "https://drive.google.com/file/d/17VEk0XCzV43hkFeEVAKG9VDXl0NL2VPO/preview"}
				,{"name" : "I Hear You Knocking", "link" : "https://drive.google.com/file/d/1IVevF0ULMmaqaQb5phVIt3dKY6Wj4aje/preview"}
			]
		}
	},
	components: {
	}
}
</script>