<script>
import Show from "../lib/components/Show/Show.svelte";

const lizard240127 = {
  src: "images/ll-24-01-27.jpg",
  alt: "The Randomatics return to Lazy Lizard on January 27th"
};

const thirsty240202 = {
  src: "images/20240202--thirsty-eye-groundhog.png",
  alt: "The Randomatics first show at Thirsty Eye on February 2nd"
}

const kactus20240215 = {
  src: "images/kaktus_gig_poster.png",
  alt: "The Randomatics at Kaktus Brewing on February 15th."
};

const bowling240218 = {
  src: "images/20240218-holiday_bowl.jpg",
  alt: "The Randomatics at Holiday Bowl!"
};

const hopper240503 = {
  src: "images/hopper-2.jpg",
  alt: "The Randomatics at The Hopper on May 3rd"
}
</script>

<h1>Greetings from The Randomatics</h1>

<p>With such reviews as, "I don't know, I don't think they'd be very good for a kids party", and "Sorry, what are they called?...Why?", it's not hard to understand why The Randomatics are one of Albuquerque's bands. The Randomatics are as fun, festive, and fantastic as the state that bore them.</p>

<h2>Upcoming Shows</h2>
<ul class="upcoming">
  <Show place="Kaktus Brewing" date="02/15/2024" time="18:30:00" image={kactus20240215} />
  <Show place="Skidmore's Holiday Bowl" date="02/18/2024" time="14:00:00" image={bowling240218} />
  <Show place="The Hopper" date="05/03/2024" time="18:00:00" image={hopper240503} />
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
