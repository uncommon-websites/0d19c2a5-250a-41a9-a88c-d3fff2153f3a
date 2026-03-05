<script lang="ts">
</script>

<nav class="fixed top-0 left-0 right-0 bg-gray-900/80 backdrop-blur-md z-50 transition-all duration-300 animate-fade-in delay-0 border-b border-gray-800">
	<div class="max-w-[1440px] mx-auto px-6 lg:px-10 h-20 flex items-center justify-between">
		
		<!-- Left: Logo & Links -->
		<div class="flex items-center gap-10">
			<!-- Logo -->
			<a href="#" class="flex items-center gap-2.5 hover:opacity-80 transition-opacity">
				<div class="w-[22px] h-[22px] bg-white rounded-[4px] skew-x-[-15deg]"></div>
				<span class="text-[26px] font-bold tracking-tight text-white mt-0.5">cal.com</span>
			</a>

			<!-- Desktop Links -->
			<div class="hidden lg:flex items-center gap-8">
				<button class="flex items-center gap-1.5 text-[15px] font-medium text-gray-300 hover:text-white transition-colors">
					Platform
					<svg class="w-3.5 h-3.5 text-gray-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
				</button>
				<button class="flex items-center gap-1.5 text-[15px] font-medium text-gray-400 hover:text-white transition-colors">
					Resources
					<svg class="w-3.5 h-3.5 text-gray-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
				</button>
				<a href="#" class="text-[15px] font-medium text-gray-400 hover:text-white transition-colors">Customers</a>
				<a href="#" class="text-[15px] font-medium text-gray-400 hover:text-white transition-colors">Pricing</a>
			</div>
		</div>

		<!-- Right: Auth Buttons -->
		<div class="flex items-center gap-4">
			<a href="#" class="hidden md:block text-[15px] font-medium text-gray-300 hover:text-white transition-colors px-4 py-2 border border-gray-700 rounded-lg hover:bg-gray-800">
				Sign in
			</a>
			<a href="#" class="text-[15px] font-medium bg-primary-500 text-white px-6 py-3 rounded-lg hover:bg-primary-600 transition-colors duration-200 active:scale-[0.97]">
				Start for free
			</a>
		</div>
	</div>
</nav>

<style>
	@keyframes fadeIn {
		from { opacity: 0; }
		to { opacity: 1; }
	}
	.animate-fade-in {
		opacity: 0;
		animation: fadeIn 0.5s cubic-bezier(0.16, 1, 0.3, 1) forwards;
	}
	.delay-0 { animation-delay: 0ms; }
</style>