<script>
  import Button from "../lib/components/Button/Button.svelte";
  import Signup from "../lib/components/Signup/Signup.svelte";
</script>
<svelte:head>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=League+Spartan:wght@500&display=swap" rel="stylesheet">
</svelte:head>

<div class="header">
  <img src="/logo-square.png" alt="The Randomatics Logo" />
  <div class="menu">
    <Button href="https://www.facebook.com/therandomatics" text="Facebook" />
    <Button href="https://www.instagram.com/the_randomatics" text="Instagram" />
    <Button href="https://www.youtube.com/therandomatics505" text="Videos" />
  </div>
</div>
<div class="main">
  <slot />
</div>
<footer>
  <Signup />
</footer>

<style lang="scss" global>
    body {
      font-family: 'League Spartan', sans-serif;
      color: #44e0cf;
      background-color: black;
      font-size: 1.5rem;
    }
  .header {
    text-align: center;

    img {
      max-width: 80vw;
    }
  }

  .menu {
    margin: .5rem;
    padding: .5rem 0;
    background-color: darkturquoise;
  }
  .main {
    width: 75vw;
    margin: 0 auto;
  }
  footer {
    width: 75vw;
    margin: 0 auto;
  }
</style>