<script lang="ts">
	import AOS from 'aos';
	import 'aos/dist/aos.css';
	import { onMount } from 'svelte';

	// Initialize AOS after the component has been mounted
	onMount(() => {
		AOS.init();
	});
</script>

<section class="flex items-center justify-center h-screen bg-gradient-to-b from-gray-50 to-white">
	<div class="px-4 mx-auto overflow-auto max-w-7xl sm:px-6 lg:px-8">
		<div class="grid grid-cols-1 gap-8 lg:grid-cols-4">
			<!-- First Section -->
			<div class="relative mt-2 lg:col-span-1">
				<div class="relative flex justify-start">
					<!-- Fixed the closing quote here -->
					<span class="text-xl text-gray-900 lg:text-base" data-aos="fade-up">
						Lower commodity prices, particularly for coal, have decreased natural resource related
						non-tax revenues, such as mining royalties.
					</span>
				</div>
			</div>

			<!-- Second section -->
			<div class="mt-2 lg:col-span-3" data-aos="fade-up" data-aos-delay="300">
				<iframe
					title="Non-tax revenues drop as commodity prices moderate"
					aria-label="Table"
					id="datawrapper-chart-ScdkT"
					src="https://datawrapper.dwcdn.net/ScdkT/1/"
					scrolling="no"
					frameborder="0"
					style="width: 0; min-width: 100% !important; border: none;"
					data-external="1"
				/>

				<script type="text/javascript">
					!(function () {
						'use strict';
						window.addEventListener('message', function (a) {
							if (void 0 !== a.data['datawrapper-height']) {
								var e = document.querySelectorAll('iframe');
								for (var t in a.data['datawrapper-height'])
									for (var r = 0; r < e.length; r++)
										if (e[r].contentWindow === a.source) {
											var i = a.data['datawrapper-height'][t] + 'px';
											e[r].style.height = i;
										}
							}
						});
					})();
				</script>
			</div>
		</div>
	</div>
</section>
