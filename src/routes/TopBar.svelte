<script lang="ts">
    import { goto } from '$app/navigation';
    import IconButton, { Icon } from '@smui/icon-button';
    import TopAppBar, { Row, Section, Title } from '@smui/top-app-bar';

	import { mdiArrowLeftBold } from '@mdi/js';

	export let prev: boolean | undefined;
</script>

<TopAppBar variant="static">
    <Row>
		<Section style={"flex: 0 0 auto"}>
			{#if prev}
				<IconButton class="material-icons" on:click={() => {history.back()}}>
					<Icon tag="svg" viewBox="0 0 24 24">
						<path fill="currentColor" d={mdiArrowLeftBold} />
					</Icon>
				</IconButton>
			{/if}
		</Section>
		<Section>
			<Title>PFAS eine schleichende Bedrohung</Title>
		</Section>
	</Row>    
</TopAppBar>