<style>
  .home-container {
    align-items: center;
    display: flex;
    flex: 1;
    justify-content: center;
    margin: 2em 0;
    min-height: 400px;
  }

  .home-copy {
    flex: 1;
  }

  h1 {
    font-weight: 700;
    margin-bottom: 0.5em;
  }

  p {
    font-size: 1.4em;
    line-height: 1.5;
  }

  figure {
    margin: 0 1em;
    text-align: center;
  }

  figcaption {
    font-size: 0.8em;
    font-style: italic;
  }

  img {
    width: 100%;
    max-width: 400px;
  }

  @media (max-width: 1020px) {
    p {
      font-size: 1.2em;
    }

    img {
      max-width: 300px;
    }
  }

  @media (max-width: 800px) {
    .home-container {
      flex-direction: column;
    }

    .home-copy {
      flex: 0;
      padding-bottom: 2em;
      text-align: center;
    }
  }
</style>

<svelte:head>
  <title>Sapper Blog</title>
</svelte:head>

<div class="home-container">
  <div class="home-copy">
    <h1>GREAT SUCCESS!</h1>
    <p>
      Check out the
      <a href="https://twitter.com/hash2666" target="_blank">Twitter.</a>
      Have fun with Sapper!
    </p>
  </div>

  <figure>
    <img alt="Person typing on laptop" src="headerimg.png" />
    <figcaption>

      <a href="https://twitter.com/hash2666" target="_blank">twitter</a>
    </figcaption>
  </figure>
</div>
