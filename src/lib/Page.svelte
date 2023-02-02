<script>
import { fade, fly } from 'svelte/transition'
export let op_fade = {duration: 500}
export let op_fly = { x: 300, duration: 1000 }
export let test = false
</script>

<section class:test={test} in:fly={op_fly} out:fade={op_fade}>
      <slot />
</section>

<style>
  section {
    --color: #565c64;
    --bg: #ffffff;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    width: 100%;
    overflow-x: hidden;
    background-color: var(--bg);
  }
  .test {
    border: 1px solid red;
  }
</style>