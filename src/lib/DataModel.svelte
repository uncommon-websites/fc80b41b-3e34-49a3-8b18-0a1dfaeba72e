<script lang="ts">
	import { User, Briefcase, Building2, Plus, MoreHorizontal } from 'lucide-svelte';
</script>

<section id="how-it-works" class="max-w-[1200px] mx-auto px-6 py-20">
	<div class="text-center max-w-3xl mx-auto mb-20">
		<h2 class="text-4xl font-serif text-gray-900 mb-6">
			The subscription for builders. <span class="text-gray-500 font-sans text-xl font-normal block mt-4">Excession is the single source for all your creative and technical needs. No more juggling freelancers or overpaying for agencies.</span>
		</h2>
		<button class="mt-8 px-4 py-2 bg-white border border-gray-200 rounded-full text-sm font-medium hover:border-gray-300 transition-colors">
			How the subscription works
		</button>
	</div>

	<!-- Process Visual -->
	<div class="relative bg-gray-50/50 rounded-xl p-10 md:p-20 border border-gray-100 overflow-hidden">
		<!-- Background Grid -->
		<div class="absolute inset-0" style="background-image: radial-gradient(#e5e7eb 1px, transparent 1px); background-size: 20px 20px; opacity: 0.5;"></div>

		<!-- Steps -->
		<div class="relative max-w-4xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-8 z-10">
			<div class="bg-white p-6 rounded-xl border border-gray-200 shadow-sm">
				<div class="w-8 h-8 bg-black text-white rounded-full flex items-center justify-center mb-4 font-bold text-sm">1</div>
				<h3 class="font-bold text-gray-900 mb-2">Queue your tasks</h3>
				<p class="text-gray-500 text-sm">Add unlimited design or development requests to your Trello-style board.</p>
			</div>
			<div class="bg-white p-6 rounded-xl border border-gray-200 shadow-sm">
				<div class="w-8 h-8 bg-black text-white rounded-full flex items-center justify-center mb-4 font-bold text-sm">2</div>
				<h3 class="font-bold text-gray-900 mb-2">We build & iterate</h3>
				<p class="text-gray-500 text-sm">Receive your first update within 24-48 hours. We iterate until it's perfect.</p>
			</div>
			<div class="bg-white p-6 rounded-xl border border-gray-200 shadow-sm">
				<div class="w-8 h-8 bg-black text-white rounded-full flex items-center justify-center mb-4 font-bold text-sm">3</div>
				<h3 class="font-bold text-gray-900 mb-2">Ship to production</h3>
				<p class="text-gray-500 text-sm">Get pixel-perfect Figma files or production-ready React code delivered.</p>
			</div>
		</div>

		<!-- Queue Preview -->
		<div class="mt-16 bg-white border border-gray-200 rounded-lg shadow-sm overflow-hidden max-w-4xl mx-auto relative z-10">
			<div class="p-4 border-b border-gray-100 bg-gray-50 flex items-center justify-between">
				<div class="text-xs font-bold text-gray-500 uppercase tracking-wider">Active Sprint</div>
				<div class="flex gap-2">
					<div class="w-2 h-2 rounded-full bg-green-500"></div>
					<div class="text-[10px] text-gray-400 font-medium">Updated 5m ago</div>
				</div>
			</div>
			<div class="p-4 space-y-4">
				<div class="flex items-center justify-between p-3 bg-gray-50 rounded-lg border border-gray-100">
					<div class="flex items-center gap-3">
						<div class="w-8 h-8 bg-blue-100 rounded flex items-center justify-center text-blue-600 font-bold text-[10px]">UI</div>
						<div>
							<div class="text-xs font-bold text-gray-900">Mobile App Onboarding Flow</div>
							<div class="text-[10px] text-gray-400">UI/UX Design • Figma</div>
						</div>
					</div>
					<span class="bg-green-100 text-green-700 px-2 py-0.5 rounded text-[10px] font-bold">DONE</span>
				</div>
				<div class="flex items-center justify-between p-3 bg-white rounded-lg border border-gray-100">
					<div class="flex items-center gap-3">
						<div class="w-8 h-8 bg-purple-100 rounded flex items-center justify-center text-purple-600 font-bold text-[10px]">DEV</div>
						<div>
							<div class="text-xs font-bold text-gray-900">React Dashboard Components</div>
							<div class="text-[10px] text-gray-400">Front-end • React/Tailwind</div>
						</div>
					</div>
					<span class="bg-blue-100 text-blue-700 px-2 py-0.5 rounded text-[10px] font-bold">IN PROGRESS</span>
				</div>
				<div class="flex items-center justify-between p-3 bg-white rounded-lg border border-gray-100 opacity-50">
					<div class="flex items-center gap-3">
						<div class="w-8 h-8 bg-yellow-100 rounded flex items-center justify-center text-yellow-600 font-bold text-[10px]">MTN</div>
						<div>
							<div class="text-xs font-bold text-gray-900">Lottie Animation for Hero</div>
							<div class="text-[10px] text-gray-400">Motion Graphics</div>
						</div>
					</div>
					<span class="bg-gray-100 text-gray-700 px-2 py-0.5 rounded text-[10px] font-bold">QUEUED</span>
				</div>
			</div>
		</div>
	</div>
</section>
