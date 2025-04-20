<script>
	import { base } from '$app/paths';

	const photoName = 'photo1';
</script>

<picture>
	<source srcset="{base}/images/{photoName}.avif" type="image/avif" />
	<source srcset="{base}/images/{photoName}.webp" type="image/webp" />
	<img src="{base}/images/{photoName}.jpg" alt="Presenter" />
</picture>
