<template>
	<div id="app">
		<div id="nav">
			<div class="title">
				CAROLYN YU
			</div>
			<router-link to="/">Home</router-link> |
			<router-link to="/project">Project</router-link> |
			<a href="#">CV</a>
		</div>
		<router-view/>
	</div>
</template>

<style lang="scss">
	*{
		box-sizing: border-box;
	}
	
	body, html{
		padding: 0;
		margin: 0;
/*		background: rgba( 100, 100, 100, 0.1);*/
	}
	
	#app {
		font-family: 'Avenir', Helvetica, Arial, sans-serif;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		text-align: center;
		color: #2c3e50;
	}
	
	#nav {
		padding: 30px;
		height: 100px;
		
		a {
			font-weight: bold;
			color: #2c3e50;
			&.router-link-exact-active {
				color: #42b983;
			}
		}
	}
</style>
