<script lang="ts">
	import { X } from 'lucide-svelte';
</script>

<div class="fixed top-0 left-0 right-0 z-50">
	<!-- Top Banner -->
	<div class="bg-black text-white text-xs font-medium py-2.5 px-4 relative">
		<div class="flex justify-center items-center gap-2">
			<span>Unlimited design and development for startups.</span>
			<span class="opacity-70">→</span>
		</div>
		<button class="absolute right-4 top-1/2 -translate-y-1/2 text-white/60 hover:text-white">
			<X size={14} />
		</button>
	</div>

	<!-- Main Nav -->
	<nav class="bg-white/90 backdrop-blur-md border-b border-gray-200">
		<div class="max-w-[1400px] mx-auto px-6 h-16 flex items-center justify-between">
			<div class="flex items-center gap-8">
				<a href="/" class="flex items-center gap-2 text-black hover:opacity-80 transition-opacity">
					<svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
						<rect x="4" y="4" width="16" height="16" rx="2" stroke="currentColor" stroke-width="2.5"/>
						<path d="M4 12H20M12 4V20" stroke="currentColor" stroke-width="1.5" stroke-linecap="round"/>
					</svg>
					<span class="font-bold text-xl tracking-tight uppercase">Excession</span>
				</a>

				<div class="hidden md:flex items-center gap-6 text-sm font-medium text-gray-600">
					<a href="#services" class="hover:text-black">Services</a>
					<a href="#how-it-works" class="hover:text-black">How it works</a>
					<a href="#pricing" class="hover:text-black">Pricing</a>
				</div>
			</div>

			<div class="flex items-center gap-4">
				<a href="#pricing" class="bg-black text-white text-sm font-medium px-4 py-2 rounded-lg hover:bg-gray-800 transition-colors">
					See plans
				</a>
			</div>
		</div>
	</nav>
</div>
