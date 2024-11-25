<script lang="ts">
	import * as Card from '$lib/components/ui/card';
	import { Button } from '$lib/components/ui/button';
	import { GithubLogo } from 'phosphor-svelte';
	import { GITHUB_REPO } from '$lib/const/social';
</script>

<Card.Root class="mx-4 min-w-96 max-w-md shadow">
	<Card.Header>
		<Card.Title>Under Maintenance</Card.Title>
	</Card.Header>
	<Card.Content>
		<p>The service is under maintenance and active development.</p>
		<br />
		<p>Operations will probably resume after 15th December 2024 (I am tryin' my best).</p>
	</Card.Content>
	<Card.Footer class="flex justify-end">
		<Button href={GITHUB_REPO} target="_blank"><GithubLogo size={20} /> Github</Button>
	</Card.Footer>
</Card.Root>
