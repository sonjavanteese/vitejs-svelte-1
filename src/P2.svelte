<script>
import svelteLogo from './assets/svelte.svg'
import Counter from './lib/Counter.svelte'
import Page from './lib/Page.svelte'
</script>

<Page>

<div class="container">
    <div>
        <a href="https://vitejs.dev" target="_blank" rel="noreferrer">
            <img src="/vite.svg" class="logo" alt="Vite Logo" />
        </a>
        <a href="https://svelte.dev" target="_blank" rel="noreferrer">
            <img src={svelteLogo} class="logo svelte" alt="Svelte Logo" />
        </a>
    </div>
    <h1>Page 2</h1>
        <hr>
    <div class="card">
        <Counter />
    </div>
    <p> Check out <a href="https://github.com/sveltejs/kit#readme" target="_blank" rel="noreferrer">SvelteKit</a>, the official Svelte app framework powered by Vite! </p>
    <p class="read-the-docs"> Click on the Vite and Svelte logos to learn more </p>
    <details>
        <summary> Show More</summary>
        <p> Godfather ipsum dolor sit amet. Why do you hurt me, Michael? I've always been loyal to you. I'm your older brother, Mike, and I was stepped over! I don't feel I have to wipe everybody out, Tom. Just my enemies. Your enemies always get strong on what you leave behind. </p>
        <p> Do me this favor. I won't forget it. Ask your friends in the neighborhood about me. They'll tell you I know how to return a favor. I don't trust a doctor who can hardly speak English. I have a sentimental weakness for my children and I spoil them, as you can see. They talk when they should listen. Fredo, you're my older brother, and I love you. But don't ever take sides with anyone against the Family again. Ever. Don't you know that I would use all of my power to prevent something like that from happening? </p>
        <p> Only don't tell me you're innocent. Because it insults my intelligence and makes me very angry. Michael, you never told me you knew Johnny Fontane! Te salut, Don Corleone. Don't ever give an order like that again. Not while I'm alive. Leave the gun. Take the cannoli. </p>
    </details>
</div>
</Page>