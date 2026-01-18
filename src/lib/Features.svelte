<script lang="ts">
	import { ArrowRight, Zap, Bot, Database, BarChart3, Mail, MessageSquare, Calendar, CheckCircle2, Search, Plus, MoreHorizontal } from 'lucide-svelte';
</script>

<section id="services" class="max-w-[1200px] mx-auto px-6 py-20">
	<div class="mb-20 max-w-2xl">
		<h2 class="text-4xl font-serif text-gray-900 mb-6">
			Your product team, on demand. <span class="text-gray-500 font-sans text-xl font-normal block mt-4">From pixel-perfect Figma prototypes to production-ready React code and immersive VR experiences. We handle the heavy lifting so you can focus on the roadmap.</span>
		</h2>
	</div>

	<div class="border border-gray-200 rounded-xl overflow-hidden bg-white shadow-sm">
		<!-- Row 1: Unlimited Requests -->
		<div class="grid grid-cols-1 md:grid-cols-3 border-b border-gray-200">
			<div class="p-12 flex flex-col justify-between border-r border-gray-200">
				<div>
					<h3 class="text-xl font-bold text-gray-900 mb-4">Unlimited requests</h3>
					<p class="text-gray-500 leading-relaxed mb-8">
						Add as many design or development tasks to your queue as you want. We work through them one by one, with daily updates.
					</p>
				</div>
				<a href="#pricing" class="inline-flex items-center gap-2 text-sm font-medium text-gray-900 hover:opacity-70 transition-opacity">
					View plans <ArrowRight size={16} />
				</a>
			</div>
			<div class="col-span-2 bg-gray-50/50 p-0 flex items-center justify-center overflow-hidden relative">
				<img 
					src="/generated/image-a-clean-organized-dashboard-showing-a-pr-1768723234689-2.webp" 
					alt="Task Queue" 
					class="w-full h-full object-cover"
				/>
			</div>
		</div>

		<!-- Row 2: 24-48h Turnaround -->
		<div class="grid grid-cols-1 md:grid-cols-3 border-b border-gray-200">
			<div class="p-12 flex flex-col justify-between border-r border-gray-200">
				<div>
					<h3 class="text-xl font-bold text-gray-900 mb-4">Rapid turnaround</h3>
					<p class="text-gray-500 leading-relaxed mb-8">
						Most design and front-end tasks are delivered in 48 hours or less. High velocity is built into our DNA.
					</p>
				</div>
				<div class="flex items-center gap-4">
					<div class="flex flex-col">
						<span class="text-2xl font-bold text-black">24h</span>
						<span class="text-[10px] text-gray-400 uppercase tracking-wider">Avg. Start</span>
					</div>
					<div class="w-px h-8 bg-gray-200"></div>
					<div class="flex flex-col">
						<span class="text-2xl font-bold text-black">48h</span>
						<span class="text-[10px] text-gray-400 uppercase tracking-wider">Avg. Delivery</span>
					</div>
				</div>
			</div>
			<div class="col-span-2 bg-gray-50/50 p-12 flex items-center justify-center relative">
				<div class="bg-white rounded-xl shadow-sm border border-gray-200 w-full max-w-md overflow-hidden">
					<div class="p-3 border-b border-gray-100 flex items-center gap-2 bg-gray-50/50">
						<Zap size={16} class="text-yellow-500 fill-yellow-500" />
						<span class="text-xs font-medium text-gray-700">Sprint Status: Active</span>
					</div>
					<div class="p-4 space-y-4">
						<div class="flex gap-3">
							<div class="w-8 h-8 rounded-full bg-gray-100 flex items-center justify-center flex-shrink-0">
								<CheckCircle2 size={16} class="text-green-600" />
							</div>
							<div class="flex-1">
								<div class="bg-gray-50 rounded-lg p-3 text-sm text-gray-800 mb-2">
									<p class="font-medium mb-1">Landing Page UI Kit</p>
									<p class="text-gray-500 text-xs">Delivered • 36 hours ago</p>
								</div>
								
								<div class="bg-white border border-gray-200 rounded-lg p-3 text-sm text-gray-800 mb-2 shadow-sm">
									<div class="flex items-center gap-2 mb-2">
										<div class="w-4 h-4 rounded bg-blue-100 flex items-center justify-center text-[10px] text-blue-600 animate-pulse"></div>
										<span class="font-medium">React Component Library</span>
									</div>
									<p class="text-gray-500 text-xs">In Progress • Estimated delivery: Tomorrow</p>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>

		<!-- Row 3: Full-stack Creative -->
		<div class="grid grid-cols-1 md:grid-cols-3">
			<div class="p-12 flex flex-col justify-between border-r border-gray-200">
				<div>
					<h3 class="text-xl font-bold text-gray-900 mb-4">Full-stack creative</h3>
					<p class="text-gray-500 leading-relaxed mb-8">
						From Figma prototypes to production React code, motion graphics to VR experiences. We are your complete product team.
					</p>
				</div>
				<div class="flex flex-wrap gap-2">
					<span class="px-2 py-1 bg-gray-100 text-[10px] font-medium rounded uppercase">UI/UX</span>
					<span class="px-2 py-1 bg-gray-100 text-[10px] font-medium rounded uppercase">React</span>
					<span class="px-2 py-1 bg-gray-100 text-[10px] font-medium rounded uppercase">Mobile</span>
					<span class="px-2 py-1 bg-gray-100 text-[10px] font-medium rounded uppercase">VR/AR</span>
				</div>
			</div>
			<div class="col-span-2 bg-gray-50/50 p-0 flex items-center justify-center relative">
				<img 
					src="/generated/image-close-up-of-a-designers-hands-using-a-hi-1768723232289-1.webp" 
					alt="Expert Craftsmanship" 
					class="w-full h-full object-cover"
				/>
			</div>
		</div>
	</div>
</section>
