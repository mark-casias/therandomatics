<script>
  export let date;
  export let place;
  export let time;
  export let image;
</script>

<div class="show">
  <div class="show__date">{date} {time}</div>
  <div class="show__place">
  {#if image}
    <img src={image.src} alt={image.alt} />
  {:else}
    {place}
  {/if}
  </div>
</div>

<style lang="scss">
  .show {
    margin: 1rem 2rem;
    height: 100%;
    border: 1px solid red;
    div {
      padding: 1rem;
    }

    img {
      max-width: 300px;
    }

    &__date {
      background-color: darkturquoise;
      color: black;
    }
    &__place {
      font-size: 2rem;
    }
    &__time {
      background-color: black;
      color: white;
    }
  }
</style>