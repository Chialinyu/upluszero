<template>
	<div class="home">

		<div class="avatar">
			<img alt="profile" src="../assets/logo.png">
			<p> Carolyn Yu</p>
			<p> 游佳霖 </p>
			<p> RA in Innovative User Interface Lab at NTUST.</p>
			<br>
			<p> Loation: Taipei</p>
			<p> Email </p>


		</div>

		<div class="info">
			<h1>Education</h1>
			<p> NCCU </p>
			<br><br><br>
			<p> NCCU </p>
			<br><br><br>
			<p> NCCU </p>
			<br><br><br>
			<p> QAQ </p>
			<br><br><br>
			<h1>Education</h1>
			<p> NCCU </p>
			<br><br><br>
			<p> NCCU </p>
			<br><br><br>
			<p> NCCU </p>
			<br><br><br>
			<p> QAQ </p>
			<br><br><br>
		</div>

	</div>

</template>

<style>
	.home{
		display: flex;
		overflow: hidden;
		height: calc(100vh - 100px);
		padding: 20px;
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
	}
</style>
