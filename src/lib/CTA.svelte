<script lang="ts">
	import { ArrowRight } from 'lucide-svelte';
</script>

<section id="pricing" class="max-w-[1200px] mx-auto px-6 py-20">
	<div class="bg-gray-50 rounded-2xl p-12 md:p-20 flex flex-col md:flex-row items-center justify-between relative overflow-hidden">
		<div class="relative z-10 max-w-lg text-left">
			<h2 class="text-4xl font-serif text-gray-900 mb-8 leading-tight">
				Scale your output<br/>without the hiring lag.
			</h2>
			<div class="flex items-center gap-6">
				<a href="#" class="bg-black text-white text-sm font-medium px-6 py-3 rounded-lg hover:bg-gray-800 transition-colors">
					Get started
				</a>
				<a href="#" class="text-sm font-medium text-gray-600 hover:text-black transition-colors">
					Book an intro call
				</a>
			</div>
		</div>

		<!-- Pricing Tiers -->
		<div class="mt-12 md:mt-0 flex flex-col md:flex-row gap-6 relative z-10">
			<div class="bg-white p-8 rounded-xl border border-gray-200 shadow-sm w-72">
				<h3 class="font-bold text-xl mb-1">Standard</h3>
				<p class="text-gray-500 text-xs mb-4">One request at a time.</p>
				<div class="text-3xl font-bold mb-6">$4,995<span class="text-sm font-normal text-gray-400">/mo</span></div>
				<ul class="text-xs space-y-3 text-gray-600">
					<li class="flex items-center gap-2">✓ Unlimited design & dev</li>
					<li class="flex items-center gap-2">✓ 24-48h turnaround</li>
					<li class="flex items-center gap-2">✓ Unlimited revisions</li>
					<li class="flex items-center gap-2">✓ Pause or cancel anytime</li>
				</ul>
			</div>

			<div class="bg-black p-8 rounded-xl border border-gray-800 shadow-xl w-72 text-white">
				<div class="bg-primary-500 text-white text-[10px] font-bold px-2 py-1 rounded uppercase w-fit mb-4">Most Popular</div>
				<h3 class="font-bold text-xl mb-1">Pro</h3>
				<p class="text-gray-400 text-xs mb-4">Two requests at a time.</p>
				<div class="text-3xl font-bold mb-6">$7,995<span class="text-sm font-normal text-gray-500">/mo</span></div>
				<ul class="text-xs space-y-3 text-gray-300">
					<li class="flex items-center gap-2">✓ Double the output</li>
					<li class="flex items-center gap-2">✓ Priority support</li>
					<li class="flex items-center gap-2">✓ Dedicated project lead</li>
					<li class="flex items-center gap-2">✓ Advanced VR/AR support</li>
				</ul>
			</div>
		</div>
	</div>
</section>
