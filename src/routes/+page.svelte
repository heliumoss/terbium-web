<script lang="ts">
	import { Github, Twitter } from 'lucide-svelte';
	import Downloads from '$lib/components/Downloads.svelte';
</script>

<section>
	<h1 class="text-5xl">Terbium</h1>
	<h2 class="text-xl">The simplest way to flash the <br /> Spotify Car Thing</h2>
</section>

<section class="flex w-full items-center justify-between">
	<div class="flex flex-col gap-2">
		<div class="flex items-center">
			<a
				href="https://github.com/heliumoss/terbium"
				target="_blank"
				class="flex items-center justify-center rounded-l-full bg-white px-3 py-2 text-lg text-black shadow-md transition-colors hover:bg-[#181717] hover:text-white"
			>
				<Github class="h-6 w-6" />
				<span class="sr-only">GitHub</span>
			</a>

			<a
				href="https://twitter.com/helium_ws"
				target="_blank"
				class="flex items-center justify-center bg-white px-3 py-2 text-lg text-black shadow-md transition-colors hover:bg-[#1DA1F2] hover:text-white"
			>
				<Twitter class="h-6 w-6" />
				<span class="sr-only">Twitter</span>
			</a>

			<a
				href="https://discord.gg/ek7re58rpv"
				target="_blank"
				class="hover:bg- flex items-center justify-center rounded-r-full bg-white px-3 py-2 text-lg text-black shadow-md transition-colors hover:bg-[#5865F2] hover:text-white"
			>
				<svg height="24" width="24" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
					<path
						d="M20.317 4.3698a19.7913 19.7913 0 00-4.8851-1.5152.0741.0741 0 00-.0785.0371c-.211.3753-.4447.8648-.6083 1.2495-1.8447-.2762-3.68-.2762-5.4868 0-.1636-.3933-.4058-.8742-.6177-1.2495a.077.077 0 00-.0785-.037 19.7363 19.7363 0 00-4.8852 1.515.0699.0699 0 00-.0321.0277C.5334 9.0458-.319 13.5799.0992 18.0578a.0824.0824 0 00.0312.0561c2.0528 1.5076 4.0413 2.4228 5.9929 3.0294a.0777.0777 0 00.0842-.0276c.4616-.6304.8731-1.2952 1.226-1.9942a.076.076 0 00-.0416-.1057c-.6528-.2476-1.2743-.5495-1.8722-.8923a.077.077 0 01-.0076-.1277c.1258-.0943.2517-.1923.3718-.2914a.0743.0743 0 01.0776-.0105c3.9278 1.7933 8.18 1.7933 12.0614 0a.0739.0739 0 01.0785.0095c.1202.099.246.1981.3728.2924a.077.077 0 01-.0066.1276 12.2986 12.2986 0 01-1.873.8914.0766.0766 0 00-.0407.1067c.3604.698.7719 1.3628 1.225 1.9932a.076.076 0 00.0842.0286c1.961-.6067 3.9495-1.5219 6.0023-3.0294a.077.077 0 00.0313-.0552c.5004-5.177-.8382-9.6739-3.5485-13.6604a.061.061 0 00-.0312-.0286zM8.02 15.3312c-1.1825 0-2.1569-1.0857-2.1569-2.419 0-1.3332.9555-2.4189 2.157-2.4189 1.2108 0 2.1757 1.0952 2.1568 2.419 0 1.3332-.9555 2.4189-2.1569 2.4189zm7.9748 0c-1.1825 0-2.1569-1.0857-2.1569-2.419 0-1.3332.9554-2.4189 2.1569-2.4189 1.2108 0 2.1757 1.0952 2.1568 2.419 0 1.3332-.946 2.4189-2.1568 2.4189Z"
						fill="currentColor"
					/>
				</svg>

				<span class="sr-only">Discord</span>
			</a>
		</div>

		<Downloads />
	</div>
	<div>
		<a
			href="https://helium.ws"
			target="_blank"
			class="flex items-center gap-2 transition-colors hover:text-pink-300"
		>
			<svg
				width="48"
				height="48"
				viewBox="0 0 130 222"
				fill="none"
				xmlns="http://www.w3.org/2000/svg"
			>
				<path
					d="M129.8 81.613C129.8 30.0625 100.788 0.300017 65.0002 0.300017C29.2121 0.300017 0.200195 30.0625 0.200195 81.613C0.200195 133.164 65.0002 179.4 65.0002 179.4C65.0002 179.4 129.8 133.164 129.8 81.613Z"
					fill="currentColor"
				/>
				<path d="M64.9998 192L35.2998 221.7H94.6998L64.9998 192Z" fill="currentColor" />
			</svg>
		</a>
	</div>
</section>
