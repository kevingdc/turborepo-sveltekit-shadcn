<script lang="ts">
	import { Button, Avatar, Card, Input } from '@repo/ui';
</script>

<div class="h-full w-full">
	<div class="flex h-full flex-col items-center justify-center">
		<h1 class="text-2xl">Web</h1>
		<Card.Root>
			<Avatar.Root>
				<Avatar.Fallback>CN</Avatar.Fallback>
			</Avatar.Root>

			<Button variant="default" class="rounded-full">Hello</Button>
			<Input placeholder="Type something" />
		</Card.Root>
		<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
	</div>
</div>
