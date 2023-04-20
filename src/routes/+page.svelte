<script>
import Show from "../lib/components/Show/Show.svelte";

const lazylizard = {
  src: "images/lazy-lizard-05-20-23.jpg",
  alt: "The Randomatics are playing at The Lazy Lizard on May 20th starting at 6pm.",
};
const alturaimage = {
  src: "images/altura-park-6-22-23.jpg",
  alt: "The Randomatics at Food Truck Thursdays on June 22nd"
}
const alvaradoimage = {
  src: "images/alvarado-park-7-13-23.jpg",
  alt: "The Randomatics at Thursday Food Truck Fest on July 13th"
}
</script>

<h1>Greetings from The Randomatics</h1>

<p>With such reviews as, "I don't know, I don't think they'd be very good for a kids party", and "Sorry, what are they called?...Why?", it's not hard to understand why The Randomatics are one of Albuquerque's bands. The Randomatics are as fun, festive, and fantastic as the state that bore them.</p>

<h2>Upcoming Shows</h2>
<ul class="upcoming">
  <li><Show place="Lazy Lizard" date="May 20th" time="6pm" image={lazylizard}/></li>
  <li><Show place="Food Truck Thursdays at Altura Park" date="June 22nd" time="5p - Dusk" image={alturaimage} /></li>
  <li><Show place="Thursday Food Truck Fest at Alvarado Park" date="July 13th" time="5p - Dusk" image={alvaradoimage}/></li>
</ul>

<style lang="scss">

  .upcoming {
    display: flex;
    justify-content: center;
    list-style: none;
    flex-wrap: wrap;

    li {
      align-self: stretch;
      margin: 1rem;
    }
  }
  p {color: white}
</style>
