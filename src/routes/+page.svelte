<script>
import Show from "../lib/components/Show/Show.svelte";

const hopper240503 = {
  src: "images/hopper-2.jpg",
  alt: "The Randomatics at The Hopper on May 3rd"
}

const growers240511 = {
  src: "images/growers_mkt_poster_1.png",
  alt: "The Randomatics play the Downtown Growers Market."
}

const lazylizard240511 = {
  src: "images/lazy-lizard-240511.jpg",
  alt: "The Randomatics at Lazy Lizard Brewing"
}

const holidayBowl2 = {
  src: "images/holiday_bowl_june_poster.png",
  alt: "The Randomatics return to Skidmore's Holiday Bowl"
}

const brewlab = {
  src: "images/brewlab_aug_poster_2024.png",
  alt: "The Randomatics live at the Albuquerque Brew Lab"
}

const farmers = {
  src: "images/farmers.jpg",
  alt: "The Randomatics return to Kactus Brewing for the Farmhouse Ale event"
}
</script>

<h1>Greetings from The Randomatics</h1>

<p>With such reviews as, "I don't know, I don't think they'd be very good for a kids party", and "Sorry, what are they called?...Why?", it's not hard to understand why The Randomatics are one of Albuquerque's bands. The Randomatics are as fun, festive, and fantastic as the state that bore them.</p>

<h2>Upcoming Shows</h2>
<ul class="upcoming">
  <Show place="The Hopper" date="05/03/2024" time="18:00:00" image={hopper240503} />
  <Show place="Downtown Growers Market" date="05/11/2024" time="10:00:00" image={growers240511} />
  <Show place="Lazy Lizard Brewing" date="05/11/2024" time="18:00:00" image={lazylizard240511} />
  <Show place="Kaktus Brewing" date="6/15/2024" time="12:00:00" image={farmers} />
  <Show place="Brew Lab Albuquerque" date="08/10/2024" time="19:00:00" image={brewlab} />
</ul>

<style lang="scss">

  .upcoming {
    display: flex;
    justify-content: center;
    list-style: none;
    flex-wrap: wrap;
  }

  p {color: white}
</style>
