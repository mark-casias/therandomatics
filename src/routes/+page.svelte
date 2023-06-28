<script>
import Show from "../lib/components/Show/Show.svelte";

const alvaradoimage = {
  src: "images/alvarado-park-7-13-23.jpg",
  alt: "The Randomatics at Thursday Food Truck Fest on July 13th"
}

const lizard0823 = {
  src: "images/lazy-lizard-08-12-23.jpg",
  alt: "The Randomatics return to the Lazy Lizard on August 12th"
}
</script>

<h1>Greetings from The Randomatics</h1>

<p>With such reviews as, "I don't know, I don't think they'd be very good for a kids party", and "Sorry, what are they called?...Why?", it's not hard to understand why The Randomatics are one of Albuquerque's bands. The Randomatics are as fun, festive, and fantastic as the state that bore them.</p>

<h2>Upcoming Shows</h2>
<ul class="upcoming">
  <Show place="Thursday Food Truck Fest at Alvarado Park" date="07/13/2023" time="17:00:00" image={alvaradoimage}/>
  <Show place="The Lazy Lizard" date="8/12/2023" time="18:00:00" image={lizard0823}/>
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
