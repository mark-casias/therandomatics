<script>
import Show from "../lib/components/Show/Show.svelte";

const holidayBowl2 = {
  src: "images/holiday_bowl_july_poster1.jpg",
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

const thirsy = {
  src: "images/thirsty_eye_aug_gig_2.png",
  alt: "The Randomatics are back at Thirsty Eye Brewing!"
}
</script>

<h1>Greetings from The Randomatics</h1>

<p>With such reviews as, "I don't know, I don't think they'd be very good for a kids party", and "Sorry, what are they called?...Why?", it's not hard to understand why The Randomatics are one of Albuquerque's bands. The Randomatics are as fun, festive, and fantastic as the state that bore them.</p>

<h2>Upcoming Shows</h2>
<ul class="upcoming">
  <Show place="Kaktus Brewing" date="6/15/2024" time="12:00:00" image={farmers} />
  <Show place="Skidmore's Bowling" date="7/28/2024" time="14:00:00" image={holidayBowl2} />
  <Show place="Thirsty Eye" date="08/03/2024" time="19:00:00" image={thirsy} />
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
