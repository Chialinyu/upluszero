<template>
	<div class="cell">
		<div>
			<img src="../assets/bg.png">
		</div>
		<h3> Project Name </h3>
		<p>
			Team member / MM, YYYY <br>
			short description about this project.
		</p>

	</div>
</template>

<script lang="ts">
	import { Component, Prop, Vue } from 'vue-property-decorator';

	@Component
	export default class ProjectCell extends Vue {
		@Prop() private msg!: string;
	}
</script>

<style scoped lang="scss">
	
	.cell{
		padding: 6px;
	}
	
	img{
		width: 100%;
	}
	
	h3 {
		margin: 40px 0 0;
	}
	ul {
		list-style-type: none;
		padding: 0;
	}
	li {
		display: inline-block;
		margin: 0 10px;
	}
	a {
		color: #42b983;
	}
</style>
