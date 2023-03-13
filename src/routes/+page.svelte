<script>
import Show from "../lib/components/Show/Show.svelte";

const llimage = {
  src: "images/lazy-lizard-april-1.png",
  alt: "The Randomatics are playing at The Lazy Lizard on April 1st starting at 6pm.",
};
const nmimage = {
  src: "images/nm-guitar-show-2023.jpg",
  alt: "the band is playing at the NM guitar show on March 26th at 4pm"
}
const mvimage = {
  src: "images/monte-vista-march-2023.jpg",
  alt: "the band is playing at the Monte Vista Fire Station on March 31st starting at 7pm"
}
</script>

<h1>Greetings from The Randomatics</h1>

<p>With such reviews as, "I don't know, I don't think they'd be very good for a kids party", and "Sorry, what are they called?...Why?", it's not hard to understand why The Randomatics are one of Albuquerque's bands. The Randomatics are as fun, festive, and fantastic as the state that bore them.</p>

<h2>Upcoming Shows</h2>
<ul class="upcoming">
  <li><Show place="NM Guitar Show" date="March 26th" time="4pm" image={nmimage}/></li>
  <li><Show place="Montevista Fire Station" date="March 31st" time="7 - 10p" image={mvimage} /></li>
  <li><Show place="Lazy Lizard Grill" date="April 1st" time="6 - 9:30p" image={llimage}/></li>
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
