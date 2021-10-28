This project reproduces a bug

`src/routes/index.svelte` contains some code which results in a 500:
```
<script>
	import { caretDown, caretUp } from 'svelte-awesome/icons';
</script>
```
