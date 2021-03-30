<script lang="ts">
</script>

<main>
  <h1>Spotizer</h1>
  <p class="description">
    Listen to music together even if your friends are using a different
    streaming platform!
  </p>
  <div>
    <button class="button-spotify"> Login to Spotify </button>
    <button class="button-deezer"> Login to Deezer </button>
  </div>
</main>

<style lang="scss">
  $spotify-color: #05C95B;
  $titles-size: 4rem;

  main {
    background-color: #020102;
    height: 100%;
    color: #fff;
  }

  h1 {
    color: $spotify-color;
    font-size: $titles-size;
    font-weight: 700;
    line-height: 1;
    margin: 0 0;
  }

  .description {
    margin-top: 0.75rem;
    font-size: 1.4rem;
  }

  button {
    padding: 0.5rem 1rem;
    margin: 0 0.5rem;
    border-radius: 0.30rem;
  }
  .button-spotify {
    background-image: linear-gradient(to right, $spotify-color, #30db94);
  }
  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
