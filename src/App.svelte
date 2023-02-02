<script>
import svelteLogo from './assets/svelte.svg'
import Counter from './lib/Counter.svelte'
import AppBar from './lib/AppBar.svelte'
import P1 from './P1.svelte'
import P2 from './P2.svelte'
let act1 = false
const toggle = () => { act1 = !act1 }
</script>


<AppBar {toggle} />
<main>
{#if act1}
<P2></P2>
{:else}
<P1></P1>
{/if}
</main>

<style>



.logo {
height: 6em;
padding: 1.5em;
will-change: filter;
transition: filter 300ms;
}
.logo:hover {
filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.svelte:hover {
filter: drop-shadow(0 0 2em #ff3e00aa);
}
.read-the-docs {
color: #888;
}
</style>
