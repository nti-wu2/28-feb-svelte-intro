<script>
let greeting = 'Hello';

function changeText(){
	greeting = 'Good bye';
}

let name = '';

</script>

<div class="app">
<h1>{greeting} {name}!</h1>
<input type="text" bind:value={name}>
<button on:click={changeText}>Change text</button>
</div>

<style>
h1 {
	color: red;
}
</style>