<script>
import Show from "../lib/components/Show/Show.svelte";

const thirsty240405 = {
  src: "images/thirsty_eye_april_poster.jpg",
  alt: "The Randomatics return to Thirsty Eye"
}

const hopper240503 = {
  src: "images/hopper-2.jpg",
  alt: "The Randomatics at The Hopper on May 3rd"
}

const lizardtail240420 = {
  src: "images/lizard_tail_poster_5.jpg",
  alt: "The Randomatics at Lizard Tail Brewing"
}

const lazylizard240511 = {
  src: "images/lazy-lizard-240511.jpg",
  alt: "The Randomatics at Lazy Lizard Brewing"
}
</script>

<h1>Greetings from The Randomatics</h1>

<p>With such reviews as, "I don't know, I don't think they'd be very good for a kids party", and "Sorry, what are they called?...Why?", it's not hard to understand why The Randomatics are one of Albuquerque's bands. The Randomatics are as fun, festive, and fantastic as the state that bore them.</p>

<h2>Upcoming Shows</h2>
<ul class="upcoming">
  <Show place="Thirsty Eye Brewing" date="04/05/2024" time="19:00:00" image={thirsty240405} />
  <Show place="Lizard Tail Brewing" date="04/20/2024" time="19:00:00" image={lizardtail240420} />
  <Show place="The Hopper" date="05/03/2024" time="18:00:00" image={hopper240503} />
  <Show place="Lazy Lizard Brewing" date="05/13/2024" time="18:00:00" image={lazylizard240511} />
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
