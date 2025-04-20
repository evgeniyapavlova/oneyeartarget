<script>
	import AllBlocks from '$comps/AllBlocks.svelte';
	import meta_img from '$lib/images/meta__img__en.jpg';
	const title = 'How to Use Systems to Extract Profits from the Markets';
	const desc =
		'NO COST TRAINING FOR ASPIRING TRADERS - Why the Systematic Method is actually your best bet to make money on the markets!';
</script>

<svelte:head>
	<title>{title}</title>
	<meta name="description" content={desc} />
	<meta property="og:title" content={title} />
	<meta property="og:description" content={desc} />
	<meta property="og:image" content={meta_img} />
	<meta name="twitter:card" content="summary_large_image" />
	<meta name="twitter:title" content={title} />
	<meta name="twitter:description" content={desc} />
	<meta name="twitter:image" content={meta_img} />
</svelte:head>

<AllBlocks />
