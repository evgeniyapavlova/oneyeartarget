<script>
	import '$lib/styles/styles.scss';
</script>

<div class="app">
	<slot />
</div>
<footer>
	<section>
		Copyright © Unger Academy® - All right reserved <br />

		Unger Academy S.r.l. - Via Castellana 86/C, 30030 Martellago (VE), Italy - VAT N°: IT04662580275
		<br />

		<a href="#" target="_blank">Privacy Policy</a> - <a href="#" target="_blank">Terms of Use</a> -
		<a href="#" target="_blank">Cookie Policy</a> - support@ungeracademy.com
	</section>
</footer>

<style>
	.app {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
		padding: 40px 0;
	}
</style>
