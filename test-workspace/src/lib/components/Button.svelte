<script lang="ts">
	let buttonEl: HTMLButtonElement;
</script>

<div class="Button mdc-touch-target-wrapper">
	<button bind:this={buttonEl} class="mdc-button mdc-button--touch mdc-button--raised">
		<span class="mdc-button__ripple" />
		<span class="mdc-button__touch" />
		<span class="mdc-button__label">My Accessible Button</span>
	</button>
</div>

<style lang="postcss">
	.Button {
		.mdc-button {
			color: red;
		}
	}
</style>
