<script>
  export let label = "nwp-app"
</script>


<header class="app-bar">
  <nav>
    <div class="brand">
    {label}
    </div>
    <aside>
      <button>
      <span>
      Button 
      </span>
        <svg version="1.1" xmlns="http://www.w3.org/2000/svg" class="icon" viewBox="0 0 24 24"><title>start</title>
        <path d="M16.641 1.688l5.672 5.672-5.672 5.625h4.359v8.016h-8.016v-8.016h3.656l-5.625-5.625v3.656h-8.016v-8.016h8.016v4.359zM3 21v-8.016h8.016v8.016h-8.016z"></path></svg>
      </button>
    </aside>
  </nav>
</header>




<style lang="scss">
  .app-bar {
    --color: #565c64;
    --color-act: #0369a1;
    --bg: #ffffff;
    --bgs: #f4f4f4;
    --bg-btn: #e2e2e2; 
    --appbar-hight: 56px;

    width: 100%;
    position: sticky;
    top: 0;
    left: 0;
    z-index: 20;
    margin: 0;
    padding: 0;
    border-bottom: 1px solid #eee;
    background-color: var(--bgs);
    color: var(--color);
    nav {
      display: flex;
      align-items: center;
      justify-content: space-between;
      min-height: var(--appbar-hight);
      button {
        display: inline-flex;
        align-items: center;
        justify-content: space-around;
        min-height: var(--appbar-hight);
        color: var(--color);
        padding: 0.2rem 1rem;
        border-radius: 0;
        font-weight: 500;
        cursor: pointer;
        transition: color 0.25s;
        &:hover {
          opacity: 0.7;
          background-color: var(--bg-btn);
        }
        &:active,
        &.active {
          background-color: var(--bg-btn);
          opacity: 0.8;
          color: var(--color-act);
        }
        svg {
          display: inline-block;
          width: 1.2em;
          height: 1.2em;
          stroke-width: 0;
          stroke: currentColor;
          fill: currentColor;
          margin: 0 .2rem;
        }
      }
      
      .brand {
        padding: 0 var(--px, 1rem);
        font-size: 1.2rem;
        font-weight: 600;
      }
    }
  }
  

</style>
