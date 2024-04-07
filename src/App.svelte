<script>
  import { Confetti } from "svelte-confetti";
</script>

<main>
  <Confetti infinite cone x={[1, 2.5]} y={[0.25, 0.75]} size={70} fallDistance=0px colorArray={["url(/plonker.png)"]} />
  <!-- <Confetti infinite size=30 colorArray={["url(../public/plonker.png)"]} /> -->
  
  <h1>Andy Ferris is cool!</h1>
  <p>Return to Alison Ferris if found in the park</p>
</main>
