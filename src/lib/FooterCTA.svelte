<script lang="ts">
</script>

<section class="py-32 px-6 text-center relative overflow-hidden">
	<!-- Background Grid of Avatars/Logos -->
	<div class="absolute inset-0 opacity-10 pointer-events-none flex flex-wrap content-center justify-center gap-4 overflow-hidden mask-image-gradient">
		<!-- Generating a grid of placeholders -->
		{#each Array(100) as _, i}
			<div class="w-10 h-10 bg-gray-900 rounded-lg flex items-center justify-center text-[10px] font-bold text-white">
				{String.fromCharCode(65 + (i % 26))}
			</div>
		{/each}
	</div>
	
	<!-- Fade out edges -->
	<div class="absolute inset-0 bg-gradient-to-b from-white via-transparent to-white pointer-events-none"></div>
	<div class="absolute inset-0 bg-gradient-to-r from-white via-transparent to-white pointer-events-none"></div>

	<div class="relative z-10 max-w-2xl mx-auto">
		<h2 class="text-5xl font-serif text-gray-900 mb-8">
			The design and dev engine for high-velocity startups.
		</h2>
		
		<div class="flex items-center justify-center gap-4">
			<a href="#pricing" class="bg-black text-white text-sm font-medium px-5 py-2.5 rounded-lg hover:bg-gray-800 transition-colors">
				See plans
			</a>
			<a href="#" class="text-sm font-medium text-gray-600 hover:text-black border border-gray-200 px-5 py-2.5 rounded-lg hover:border-gray-300 transition-colors">
				Book a call
			</a>
		</div>
	</div>
</section>

<style>
	.mask-image-gradient {
		mask-image: radial-gradient(circle, transparent 20%, black 100%);
		-webkit-mask-image: radial-gradient(circle, transparent 20%, black 100%);
	}
</style>
