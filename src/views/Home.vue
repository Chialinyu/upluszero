<template>
	<div class="home">

		<div class="avatar">
			<img alt="profile" src="../assets/logo.png">
			<p> &#10077; Carolyn Yu</p>
			<p> &#10000; 游佳霖 </p>
			<p> RA in Innovative User Interface Lab at NTUST.</p>
			<br>
			<p> &#9992; Taipei, Taiwan</p>
			<p> &#9993; Email </p>


		</div>

		<div class="info">
			<h1>About</h1>
			Hi, I'm Carolyn, research assistant in <a href="http://nccuiuilab.github.io/index.html" target="_blank"> Innovation User Interface Lab </a> at National Taiwan University of Science and Technology lead by <a href="#" target="_blank">Prof. Neng-Hao Yu</a>.

			<br>.<br>.<br>.
			<p> QAQ </p>
			<br>
			<h1>Publications</h1>
			<p> Construction and Optimization of Feature Descriptor based on Dynamic
Local Intensity Order Relations of Pixel Group</p>
			Wen-Hung Liao, <b>Carolyn Yu</b>, and Yi-Chieh Wu
			<p>ICIAR 2019 <a href="#"> [PDF] </a> </p>
			<br>
			
			<h1>Education</h1>
			<p> M.S., Computer Science 2017</p>
			<p> Visual Information Processing Lab</p>
			<p> National Chengchi University</p>
			<br>
			<p> B.S., Computer Science 2015 </p>
			<p> Double major, Digital Content &amp; Technologies Program </p>
			<p> National Chengchi University</p>

			<br><br><br>
		</div>

	</div>

</template>

<style lang="scss">
	.home{
		display: flex;
		overflow: hidden;
		height: calc(100vh - 100px);
		padding: 20px;

		img{
			/*			width: 80%;*/
		}

		.avatar{
			flex: 1;
			text-align: left;
			padding: 40px;
			border-right: 0.5px solid rgba(0, 0, 0, 0.5);
		}
		.info{
			flex: 3;
			text-align: left;
			padding: 40px;
			overflow: auto;

			a{
				color: #ff8686;
				text-decoration: none;
			}
			a:hover {
				text-decoration: underline;
			}
			a:visited {
				text-decoration: none;
			}
			a:any-link {
				cursor: auto;
			}
		}
	}

</style>
