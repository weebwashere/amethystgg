<script lang="ts">
	import '../app.postcss';
	import { AppShell, AppBar } from '@skeletonlabs/skeleton';
	import { LightSwitch, CodeBlock } from '@skeletonlabs/skeleton';
</script>

<!-- App Shell -->
<AppShell>
	<svelte:fragment slot="header">
		<!-- App Bar -->
		<AppBar>
		<LightSwitch />
			<svelte:fragment slot="lead">
				<h1 class="font-abc lowercase">AMETHYST</h1>
			</svelte:fragment>
			<svelte:fragment slot="trail">
				<a
					class="btn btn-sm variant-ghost-surface font-abc"
					href="https://www.guilded.gg/b/2e702266-2dfe-4796-b61c-ccbb0536444c"
					target="_blank"
					rel="noreferrer"
				>
					Support Server
				</a>
				<a
					class="btn btn-sm variant-ghost-surface font-abc"
					href="https://twitter.com/weebisdev"
					target="_blank"
					rel="noreferrer"
				>
					Twitter
				</a>
				<a
					class="btn btn-sm variant-ghost-surface font-abc"
					href="https://github.com/skeletonlabs/skeleton"
					target="_blank"
					rel="noreferrer"
				>
					GitHub
				</a>
			</svelte:fragment>
		</AppBar>
	</svelte:fragment>
	<!-- Page Route Content -->
	<slot />
</AppShell>
