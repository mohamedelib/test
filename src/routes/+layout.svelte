<script>
  import favicon from "$lib/assets/favicon.svg";

  let { children } = $props();
</script>

<svelte:head>
  <header>
    <nav>
      <ul>
        <li><a class="active" href="">Home</a></li>
        <li><a href="">Projects</a></li>
        <li><a href="">Contact</a></li>
        <li><a href="">Blabla</a></li>
      </ul>
    </nav>
  </header>

  <style>
    ul {
      list-style: none;
      display: flex;
      flex-direction: row;
      justify-content: space-between;
      gap: 30px;
    }

    a {
      text-decoration: none;
      color: white;
      padding: 6px 10px;
      border-radius: 8px;

      &:hover {
        background: #a32d2d;
      }
    }

    nav {
      display: flex;
      background: var(--black);
      padding: 20px;
    }

    .active {
      background: #a32d2d;
    }

    header {
      justify-content: center;
      display: flex;
      align-items: center;
    }
  </style>
</svelte:head>

{@render children()}
