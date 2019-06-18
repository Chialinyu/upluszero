<template>
	<div id="app">
		<div id="nav">
			<div class="title">
				CAROLYN YU
			</div>
			<div class="buttoms">
				<div class="buttom"><router-link to="/">Home</router-link></div> |
				<div class="buttom"><router-link to="/project">Project</router-link></div> |
				<div class="buttom"><a href="#">CV</a></div>
			</div>
		</div>
		<router-view/>
	</div>
</template>

<style lang="scss">
	*{
		box-sizing: border-box;
	}

	@font-face{
		font-family: desdemon;
		src: url(./assets/desdemon.ttf);
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
		color: #868686;
	}

	#nav {
		padding: 30px;
		height: 100px;

		a {
			font-weight: bold;
			color: #868686;
			&.router-link-exact-active {
				color: #ff8686;
			}
		}

		.title{
			font-size: 40px;
			width: 20%;
			margin: auto;
			font-family: desdemon;
			border-bottom: 0.5px solid rgba(0, 0, 0, 0.2);
		}

		.buttom{
			display: inline-block;
			padding: 15px 5%;
		}

	}
</style>
