<script lang="js">
  import Paper, { Title, Content } from '@smui/paper';
  import Button, { Label } from '@smui/button';
  import LayoutGrid, { Cell } from '@smui/layout-grid';

</script>
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/svelte-material-ui@6.0.0/bare.min.css"
/>

<!-- Roboto -->
<link
  rel="stylesheet"
  href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,600,700"
/>

<style type="text/scss">
	@use '@material/typography/mdc-typography';

	.paper-container{
		margin-top: 35vh;
	}
</style>

<div class="paper-container">
	<Paper>
		<div class="paper-wrapper">
			<Title><h1 class="mdc-typography--headline1" style="text-align: center;">Rachasak.org</h1></Title>
			<Content>
				<p class="mdc-typography--body1">The <i>official, professional</i> website for Mr. Rachasak</p>
				<small class="mdc-typography--body1">coming soon</small>
				<p class="mdc-typography--body1" style="text-align: center;">
					<Button href="https://www.ericconsultant.in.th" target="_blank" variant="outlined">
						<Label>Eric Legal & Consultant</Label>
					</Button>
				</p>
			</Content>
		</div>
	</Paper>
</div>
