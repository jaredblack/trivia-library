<script lang="ts">
	import '../app.postcss';
	import { AppShell, AppBar } from '@skeletonlabs/skeleton';
</script>
<AppShell>
	<svelte:fragment slot="header">
		
		<AppBar>
			<svelte:fragment slot="lead">
				<strong class="text-xl uppercase">Trivia Library</strong>
			</svelte:fragment>
		</AppBar>
	</svelte:fragment>
	<slot />
</AppShell>
