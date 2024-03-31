<script>
  import { format } from 'date-fns';
  export let date;
  export let place;
  export let time;
  export let image;

  const showDate = new Date(`${date}, ${time}`);
  const nowDate = new Date().getTime();
  const isLater = showDate.getTime() > nowDate;
</script>

{#if isLater }
<li>
  <div class="show">
    <div class="show__date">{format(showDate, 'LLL do - hb')}</div>
    <div class="show__place">
    {#if image}
      <img src={image.src} alt={image.alt} />
    {:else}
      {place}
    {/if}
    </div>
  </div>
</li>
{/if}
<style lang="scss">

  li {
    align-self: stretch;
    margin: 1rem;
   }
  .show {
    margin: .5rem;
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
  }
</style>
