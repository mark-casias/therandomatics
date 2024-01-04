<script>
  export let href;
  export let text;
  export let target = '_blank';
</script>

<a href={href} target={target} rel="noreferrer">{text}</a>

<style>
  a {
    padding: .25rem;
    background-color: gold;
    color: black;
    border: 1px solid black;
    border-radius: .4rem;
    text-decoration: none;
  }
</style>