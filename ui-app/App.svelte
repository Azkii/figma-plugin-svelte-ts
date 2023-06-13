<script lang="ts">
  export let name = "Figma";
</script>

<main>
  <h1>Hello {name}!</h1>
</main>

<style lang="scss">
  * {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
  }

  main {
    text-align: center;
    box-sizing: border-box;

    h1 {
      color: #ff3e00;
      text-transform: uppercase;
      font-size: 4em;
      font-weight: 100;

      @media (max-width: 640px) {
        background-color: #ff3e00;
        color: whitesmoke;
      }
    }
  }
</style>
