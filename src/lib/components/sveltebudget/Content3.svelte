<script lang="ts">
	import AOS from 'aos';
	import 'aos/dist/aos.css';
	import { onMount } from 'svelte';

	// Initialize AOS after the component has been mounted
	onMount(() => {
		AOS.init();
	});
</script>

<section class="flex items-center justify-center h-screen py-24 bg-gray-900">
	<div class="px-4 mx-auto sm:px-6 lg:px-8 max-w-7xl">
		<div class="grid items-center grid-cols-1 gap-y-12 md:grid-cols-7 md:gap-x-12 lg:gap-x-24">
			<div class="md:col-span-3" data-aos="fade-up">
				<img class="object-cover w-full rounded-md" src="/jokowi.jpeg" alt="Joko Widodo Photos" />
			</div>

			<div class="md:col-span-4">
				<blockquote class="mt-6">
					<p
						class="text-2xl font-normal text-white lg:text-4xl"
						data-aos="fade-up"
						data-aos-delay="300"
					>
						“The 2024 State Budget is formulated to address present and future challenges, so the
						2024 State Budget is directed at <span
							class="text-transparent bg-clip-text bg-gradient-to-r from-cyan-500 to-amber-400"
							>accelerating inclusive and sustainable economic transformation</span
						>.”
					</p>
				</blockquote>

				<hr class="mt-10 border-gray-800" data-aos="fade-up" data-aos-delay="500" />

				<div class="mt-8 sm:flex sm:items-center sm:justify-between">
					<div class="flex-1" data-aos="fade-up" data-aos-delay="700">
						<p class="text-xl font-normal text-white">Joko Widodo</p>
						<p class="mt-1 text-sm font-normal text-gray-400">President of Indonesia</p>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>
