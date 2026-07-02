<script>
  let title = $state("Ninja gaming guides");
  const updateTitle = () => {
    title = "iets anders";
  };
</script>

<!-- <div class="index">
  <h2>{title}</h2>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam natus beatae
    animi perspiciatis soluta corrupti. Error voluptatem velit temporibus, quia
    fugiat odio autem ipsam labore aliquid dolore, maiores vitae aliquam! Lorem
    ipsum dolor sit amet, consectetur adipisicing elit. Natus autem, blanditiis
    enim provident aut, vitae animi ab vel delectus dolor repellat quo aliquam a
    consequatur placeat, sunt vero. Enim, facere.
  </p>
  <button onclick={updateTitle}>change title</button>
  <input type="text" bind:value={title} />
</div> -->

<style>
  @import url("https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap");
  :root {
    --red: #f09595;
    --black: #0b0b0b;
  }

  * {
    margin: 0;
    padding: 0;
    list-style: none;
    box-sizing: border-box;
  }
  .index {
    text-align: center;
    display: block;
    margin: 20px auto;
  }

  :global(body) {
    background-color: var(--black);
    font-family: "Inter", sans-serif;
  }
</style>
