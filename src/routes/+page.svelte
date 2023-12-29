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

const lizard1123 = {
  src: "images/lazy-lizard-11-11-23.jpg",
  alt: "The anniversary of our first show at the Lazy Lizard"
}

const mollys0909 = {
  src: "images/rando-mollys.jpg",
  alt: "The Randomatics first show at Molly's Bar and Grill on Setpember 9th"
}

const brewlab081023 = {
  src: "images/brewlab-8-10-23.png",
  alt: "The Randomatics at Brewlab in Rio Rancho on August 10th"
}

const lizard240127 = {
  src: "images/ll-24-01-27.jpg",
  alt: "The Randomatics return to Lazy Lizard on January 27th"
};

const thirsty240202 = {
  src: "images/thirsty-eye-24-02-02.jpg",
  alt: "The Randomatics first show at Thirsty Eye on February 2nd"
}
</script>

<h1>Greetings from The Randomatics</h1>

<p>With such reviews as, "I don't know, I don't think they'd be very good for a kids party", and "Sorry, what are they called?...Why?", it's not hard to understand why The Randomatics are one of Albuquerque's bands. The Randomatics are as fun, festive, and fantastic as the state that bore them.</p>

<h2>Upcoming Shows</h2>
<ul class="upcoming">
  <Show place="Lazy Lizard" date="01/27/2024" time="18:00:00" image={lizard240127} />
  <Show place="Thirsty Eye Brewing" date="02/02/2024" time="18:00:00" image={thirsty240202} />
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
