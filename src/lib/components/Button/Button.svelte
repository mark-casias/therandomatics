<script>
  export let href;
  export let text;
</script>

<a href={href} target="_blank" rel="noreferrer">{text}</a>

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