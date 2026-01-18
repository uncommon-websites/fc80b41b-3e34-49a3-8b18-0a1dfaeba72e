<script lang="ts">
	import { Twitter, Linkedin, Github, Youtube } from 'lucide-svelte';
</script>

<footer class="bg-black text-white pt-20 pb-10 px-6">
	<div class="max-w-[1200px] mx-auto">
		<div class="grid grid-cols-2 md:grid-cols-6 gap-10 mb-20">
			<!-- Logo Column -->
			<div class="col-span-2">
				<a href="/" class="flex items-center gap-2 text-white mb-6">
					<svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
						<rect x="4" y="4" width="16" height="16" rx="2" stroke="white" stroke-width="2"/>
						<path d="M4 12H20M12 4V20" stroke="white" stroke-width="1.5"/>
					</svg>
					<span class="font-bold text-xl tracking-tight uppercase">Excession</span>
				</a>
				<p class="text-gray-400 text-sm max-w-xs leading-relaxed">
					Unlimited design and development for high-velocity startups. Build faster, ship better.
				</p>
			</div>

			<!-- Columns -->
			<div>
				<h4 class="text-sm font-medium text-gray-400 mb-4">Services</h4>
				<ul class="space-y-3 text-sm text-gray-300">
					<li><a href="#" class="hover:text-white">UI/UX Design</a></li>
					<li><a href="#" class="hover:text-white">React Development</a></li>
					<li><a href="#" class="hover:text-white">Mobile Apps</a></li>
					<li><a href="#" class="hover:text-white">Motion Graphics</a></li>
					<li><a href="#" class="hover:text-white">VR Experiences</a></li>
				</ul>
			</div>

			<div>
				<h4 class="text-sm font-medium text-gray-400 mb-4">Company</h4>
				<ul class="space-y-3 text-sm text-gray-300">
					<li><a href="#" class="hover:text-white">About Us</a></li>
					<li><a href="#" class="hover:text-white">Our Process</a></li>
					<li><a href="#" class="hover:text-white">Pricing</a></li>
					<li><a href="#" class="hover:text-white">Careers</a></li>
				</ul>
			</div>

			<div>
				<h4 class="text-sm font-medium text-gray-400 mb-4">Resources</h4>
				<ul class="space-y-3 text-sm text-gray-300">
					<li><a href="#" class="hover:text-white">Blog</a></li>
					<li><a href="#" class="hover:text-white">Help Center</a></li>
					<li><a href="#" class="hover:text-white">System Status</a></li>
				</ul>
			</div>

			<div>
				<h4 class="text-sm font-medium text-gray-400 mb-4">Legal</h4>
				<ul class="space-y-3 text-sm text-gray-300">
					<li><a href="#" class="hover:text-white">Privacy Policy</a></li>
					<li><a href="#" class="hover:text-white">Terms of Service</a></li>
					<li><a href="#" class="hover:text-white">Security</a></li>
				</ul>
			</div>
		</div>

		<div class="border-t border-gray-800 pt-8 flex flex-col md:flex-row items-center justify-between gap-4">
			<div class="flex items-center gap-6">
				<a href="#" class="text-gray-500 hover:text-white transition-colors"><Linkedin size={20} /></a>
				<a href="#" class="text-gray-500 hover:text-white transition-colors"><Twitter size={20} /></a>
				<a href="#" class="text-gray-500 hover:text-white transition-colors"><Github size={20} /></a>
			</div>
			
			<div class="flex items-center gap-6 text-xs text-gray-500">
				<span>© 2025 Excession Studio. All rights reserved.</span>
			</div>
		</div>
	</div>
</footer>
