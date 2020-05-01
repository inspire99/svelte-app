<script>
	import Face from './Face.svelte';
	let text = 'Hello world';
	setTimeout(()=>{
		text='I am ganesh ';
		console.log('updating name to '+ name);
	},2000)
	setTimeout(()=>{
		text='Welcome to https://gansai.blogspot.com'
	},3000)
	
</script>

<h1> {text}!</h1>
<div id='mydiv'>
	
</div>
<Face/>

<style>
	h1{
		color:blue;
		background:yellow;
	}
</style>