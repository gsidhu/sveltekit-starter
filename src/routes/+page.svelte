<script>
  import confetti from 'canvas-confetti';
  
  function celebrate() {
    let xray = Math.random()
    confetti({
      particleCount: 100,
      spread: 70,
      origin: { y: 0.6, x: xray > 0.7 | xray < 0.3 ? 0.5 : xray }
    });
  }
</script>

<div class="h-100 mx-auto text-center">
  <img src="./asterisk.png" alt="vonnegut-asterisk" width="128" height="128" />
  <h1>And so it goes.</h1>
  <p class="lead my-4">
    <button class="btn btn-lg btn-secondary fw-bold border-dark bg-dark" on:click={() => celebrate()}>Celebrate</button>
  </p>
</div>