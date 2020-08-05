<script lang="ts">
  import Tailwind from "./Tailwind.svelte";
</script>

<style lang="scss">
  .wrapper {
    text-align: center;
    .title {
      font-size: 52px;
      color: #333;
      font-weight: bolder;
      margin-bottom: 15px;
    }

    .paragraph {
      font-size: 18px;
      color: #444;

      a {
        color: #ec407a;
        font-weight: bolder;
      }
    }
  }
</style>

<Tailwind />
<section class="container h-screen mx-auto flex justify-center items-center">
  <div class="wrapper">
    <h1 class="title">Hello Svelte!</h1>
    <p class="paragraph">
      Visit the
      <a href="https://svelte.dev/tutorial">Svelte tutorial</a>
      to learn how to build Svelte apps.
    </p>
    <p class="paragraph">With this template you can used Svelte, tailwind, scss and postcss</p>
  </div>

</section>
