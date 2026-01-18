<script lang="ts">
	import { Mail, Calendar, Database, Activity, Search, Bell, CheckSquare, BarChart2, Zap, MoreHorizontal, Filter, RefreshCw, Plus } from 'lucide-svelte';
</script>

<section class="max-w-[1200px] mx-auto px-6 py-20 text-center">
	<div class="max-w-3xl mx-auto mb-12">
		<h2 class="text-4xl font-serif text-gray-900 mb-6">
			Production-ready, immediately. <span class="text-gray-500 font-sans text-xl font-normal block mt-4">Forget months of recruitment. Excession delivers senior-level design and engineering output from day one, scaling with your ambition.</span>
		</h2>
		<button class="mt-8 px-5 py-2.5 bg-black text-white rounded-lg text-sm font-medium hover:bg-gray-800 transition-colors">
			Start your subscription
		</button>
	</div>

	<!-- Categories -->
	<div class="flex justify-center flex-wrap gap-4 mb-12">
		<button class="flex items-center gap-2 px-4 py-2 bg-white border border-gray-200 rounded-full text-xs font-medium text-gray-900 shadow-sm hover:bg-gray-50">
			<Zap size={14} /> UI/UX Design
		</button>
		<button class="flex items-center gap-2 px-4 py-2 bg-white border border-gray-200 rounded-full text-xs font-medium text-gray-500 hover:text-gray-900 hover:bg-gray-50 transition-colors">
			<Database size={14} /> React Builds
		</button>
		<button class="flex items-center gap-2 px-4 py-2 bg-white border border-gray-200 rounded-full text-xs font-medium text-gray-500 hover:text-gray-900 hover:bg-gray-50 transition-colors">
			<Activity size={14} /> Motion Graphics
		</button>
		<button class="flex items-center gap-2 px-4 py-2 bg-white border border-gray-200 rounded-full text-xs font-medium text-gray-500 hover:text-gray-900 hover:bg-gray-50 transition-colors">
			<Plus size={14} /> VR Experiments
		</button>
	</div>

	<!-- UI Preview -->
	<div class="relative bg-white rounded-xl border border-gray-200 shadow-xl overflow-hidden text-left max-w-5xl mx-auto">
		<!-- Header -->
		<div class="h-14 border-b border-gray-200 flex items-center justify-between px-6 bg-white">
			<div class="flex items-center gap-4">
				<div class="w-8 h-8 rounded-full bg-black flex items-center justify-center text-white text-[10px] font-bold">EX</div>
				<div>
					<div class="text-sm font-semibold text-gray-900">Project: Alpha Dashboard</div>
					<div class="text-xs text-gray-500">Status: Polishing</div>
				</div>
			</div>
			<div class="flex items-center gap-3">
				<div class="flex -space-x-2">
					<div class="w-6 h-6 rounded-full bg-blue-500 border-2 border-white"></div>
					<div class="w-6 h-6 rounded-full bg-purple-500 border-2 border-white"></div>
				</div>
				<button class="text-xs font-medium text-gray-600">Active Sprint</button>
			</div>
		</div>

		<div class="flex h-[500px]">
			<!-- Sidebar -->
			<div class="w-64 border-r border-gray-200 bg-gray-50/30 p-4 flex flex-col gap-1">
				<div class="text-[11px] font-medium text-gray-400 mb-2 uppercase tracking-wider">Scope</div>
				
				<div class="grid grid-cols-[20px_1fr] gap-2 text-xs mb-4">
					<div class="text-gray-400"><Zap size={14} /></div>
					<div class="text-gray-900">12 UI Components</div>
					
					<div class="text-gray-400"><Database size={14} /></div>
					<div class="text-gray-900">React/Next.js Build</div>
					
					<div class="text-gray-400"><Activity size={14} /></div>
					<div class="text-gray-900">3 Motion Prototypes</div>
				</div>

				<div class="text-[11px] font-medium text-gray-400 mb-2 uppercase tracking-wider mt-4">Tech Stack</div>
				<div class="flex flex-wrap gap-2 mt-2">
					<span class="bg-white border border-gray-200 px-2 py-1 rounded text-[10px] text-gray-600">Tailwind</span>
					<span class="bg-white border border-gray-200 px-2 py-1 rounded text-[10px] text-gray-600">Framer Motion</span>
					<span class="bg-white border border-gray-200 px-2 py-1 rounded text-[10px] text-gray-600">TypeScript</span>
				</div>
			</div>

			<!-- Main Content -->
			<div class="flex-1 bg-white p-6 overflow-y-auto">
				<div class="flex items-center justify-between mb-6">
					<h3 class="text-sm font-semibold text-gray-900 flex items-center gap-2">
						<Activity size={16} /> Delivery Timeline
					</h3>
					<button class="text-xs text-blue-600 font-medium">View in Figma</button>
				</div>

				<!-- Highlight Card -->
				<div class="bg-gray-50 border border-gray-100 rounded-lg p-4 mb-8">
					<p class="text-sm text-gray-700 leading-relaxed">
						"The dashboard UI is now fully responsive. We've optimized the data visualization components for high-density information display."
					</p>
					<div class="flex items-center gap-2 mt-3">
						<div class="w-5 h-5 rounded-full bg-black flex items-center justify-center text-[10px] text-white">EX</div>
						<span class="text-xs text-gray-500">Update from Lead Designer</span>
					</div>
				</div>

				<!-- Timeline -->
				<div class="relative pl-4 border-l border-gray-200 space-y-8">
					<div class="relative">
						<div class="absolute -left-[21px] top-0 w-3 h-3 rounded-full bg-green-500 border-2 border-white"></div>
						<div class="flex items-start justify-between">
							<div>
								<div class="text-sm font-medium text-gray-900">Task Delivered: Auth Flow UI</div>
								<p class="text-xs text-gray-500 mt-1">Pixel-perfect Figma files for Login, Signup, and Reset Password.</p>
							</div>
							<span class="text-xs text-gray-400">Today</span>
						</div>
					</div>

					<div class="relative">
						<div class="absolute -left-[21px] top-0 w-3 h-3 rounded-full bg-blue-500 border-2 border-white"></div>
						<div class="flex items-start justify-between">
							<div>
								<div class="text-sm font-medium text-gray-900">In Progress: Data Grid Component</div>
								<div class="text-xs text-gray-500 mt-1">Building high-performance React table with sorting and filtering.</div>
							</div>
							<span class="text-xs text-gray-400">ETA: Tomorrow</span>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>
