<script>
  import Button from "../lib/components/Button/Button.svelte";
  import Signup from "../lib/components/Signup/Signup.svelte";
</script>

<div class="header">
  <img src="/logo-square.png" alt="The Randomatics Logo" />
  <div class="menu">
    <Button href="https://www.facebook.com/therandomatics" text="Facebook" />
    <Button href="https://www.instagram.com/therandomatics" text="Instagram" />
    <Button href="https://www.youtube.com/therandomatics505" text="Videos" />
  </div>
</div>
<div class="main">
  <slot />
</div>
<footer>
  <Signup />
</footer>

<style>
  .header {
    text-align: center;
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