<template>
	<div class="project">
		<h1>Projects</h1>

		<div class="components">
			<div class="component" v-for="project in length">
				<ProjectCell/>
			</div>
		</div>

	</div>
</template>


<script lang="ts">
	import { Component, Vue } from "vue-property-decorator";
	import ProjectCell from "@/components/ProjectCell.vue";

	@Component({
		components: {
			ProjectCell,
		},
	})
	export default class Project extends Vue {
		private length = [1, 2, 3, 4, 5, 6];
	}

</script>

<style lang="scss">
	.project{
		width: 80%;
		margin: 0 auto;
		height: calc(100vh - 100px);
/*		overflow: hidden;*/

/*
		.components{
			overflow: auto;
		}
*/
		
		.component{
			width: 40%;
			display: inline-block;
			padding: 6px;
			background: url("../assets/cell_bg.png");
			background-size: cover;
		}
	}

</style>