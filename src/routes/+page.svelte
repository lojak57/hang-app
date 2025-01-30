<script lang="ts">
  let title = "Hang App";
</script>

<svelte:head>
  <title>{title}</title>
</svelte:head>

<main>
  <h1>{title}</h1>
  <p>Welcome to your new hangout spot!</p>
</main>

<style>
  main {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    padding: 1rem;
    background-color: #f9fafb;
  }

  h1 {
    font-size: 2.5rem;
    font-weight: 700;
    color: #1f2937;
    margin-bottom: 1rem;
  }

  p {
    font-size: 1.25rem;
    color: #4b5563;
    text-align: center;
    max-width: 600px;
    line-height: 1.6;
  }
</style>
