<script>
	import { base } from '$app/paths';
	import { searchString } from '$lib/stores/affs';
	import Tg from './Tg.svelte';
	import Photo from './Photo.svelte';
</script>

<section class="title">
	<h2>NO COST TRAINING FOR ASPIRING TRADERS</h2>
	<h1>How to Use Systems to Extract Profits from the Markets</h1>
	<h3>...without Useless Discretionary Analysis!</h3>
</section>

<section class="content">
	<div class="content-photo">
		<Photo />
		<div class="content-photo-caption">
			More than 100,000 traders have already used my strategy and made profit
		</div>
	</div>
	<div class="content-cta">
		<div class="cta">
			<a href="https://iqoption.com/en/register{$searchString}" class="button">
				YES! Watch The Training Now!
				<svg
					version="1.1"
					id="Layer_1"
					xmlns="http://www.w3.org/2000/svg"
					xmlns:xlink="http://www.w3.org/1999/xlink"
					x="0px"
					y="0px"
					viewBox="0 0 120.64 122.88"
					style="enable-background:new 0 0 120.64 122.88"
					xml:space="preserve"
					preserveAspectRatio="none"
					><g
						><path
							d="M54.03,108.91c-1.55,1.63-2.31,3.74-2.28,5.85c0.03,2.11,0.84,4.2,2.44,5.79l0.12,0.12c1.58,1.5,3.6,2.23,5.61,2.2 c2.01-0.03,4.01-0.82,5.55-2.37c17.66-17.66,35.13-35.61,52.68-53.4c0.07-0.05,0.13-0.1,0.19-0.16c1.55-1.63,2.31-3.76,2.28-5.87 c-0.03-2.11-0.85-4.21-2.45-5.8l-0.27-0.26C100.43,37.47,82.98,19.87,65.46,2.36C63.93,0.82,61.93,0.03,59.92,0 c-2.01-0.03-4.03,0.7-5.61,2.21l-0.15,0.15c-1.57,1.58-2.38,3.66-2.41,5.76c-0.03,2.1,0.73,4.22,2.28,5.85l47.22,47.27 L54.03,108.91L54.03,108.91z M2.26,106.91c-1.54,1.62-2.29,3.73-2.26,5.83c0.03,2.11,0.84,4.2,2.44,5.79l0.12,0.12 c1.57,1.5,3.6,2.23,5.61,2.21c2.01-0.03,4.02-0.82,5.55-2.37C31.01,101.2,48.87,84.2,66.39,67.12c0.07-0.05,0.14-0.11,0.21-0.17 c1.55-1.63,2.31-3.76,2.28-5.87c-0.03-2.11-0.85-4.21-2.45-5.8C48.94,38.33,31.36,21.44,13.83,4.51l-0.12-0.13 c-1.53-1.54-3.53-2.32-5.54-2.35C6.16,2,4.14,2.73,2.56,4.23L2.41,4.38C0.84,5.96,0.03,8.05,0,10.14c-0.03,2.1,0.73,4.22,2.28,5.85 l47.18,45.24L2.26,106.91L2.26,106.91z"
						/>
					</g>
				</svg>
			</a>

			<Tg>Any other questions?</Tg>
		</div>
		<picture>
			<source srcset="{base}/images/tp.avif" type="image/avif" />
			<source srcset="{base}/images/tp.webp" type="image/webp" />
			<img src="{base}/images/tp.jpg" alt="Trustpilot" />
		</picture>
	</div>

	<div class="content-text">
		<h2>EXCLUSIVE TRAINING:</h2>
		<ul class="content-list">
			<li>
				<strong>​The little-known approach</strong> used by most successful traders that doesn't require
				long hours in front of a screen.
			</li>
			<li>
				<strong>The unique & powerful tool</strong> to create Trading Systems with an edge in the markets,
				even if you don't consider yourself a computer genius.
			</li>
			<li>
				<strong>How to manage risk with a well-diversified portfolio</strong> even if you don't have
				millions.
			</li>
		</ul>
	</div>
</section>

<section class="content-note">
	<h4>NOTE: This Training is NOT for Everyone...</h4>
	<p class="content-note-large">
		Not everyone can become a profitable trader. Your results are not guaranteed. This training is
		only for those that are hard working, realize that success does not come easy, and are willing
		to put in the work when problems arise. This training will however give you insight behind one
		of the top Systematic Traders of all time!
	</p>
	<p class="content-note-small">
		Nothing on this page, any of our websites, or any of our content or curriculum is a promise or
		guarantee of results or future earnings, and we do not offer any legal, medical, tax or other
		professional advice. Any financial numbers referenced here, or on any of our sites, are
		illustrative of concepts only and should not be considered average earnings, exact earnings, or
		promises for actual or future performance. Use caution and always consult your accountant,
		lawyer or professional advisor before acting on this or any information related to a lifestyle
		change or your business or finances. You alone are responsible and accountable for your
		decisions, actions and results in life, and by your registration here you agree not to attempt
		to hold us liable for your decisions, actions or results, at any time, under any circumstance.
		<br /> <br />
		This site is not a part of the Facebook website or Facebook Inc. Additionally, This site is NOT endorsed
		by Facebook in any way. FACEBOOK is a trademark of FACEBOOK, Inc.
	</p>
</section>
