<script>
</script>

<!-- Expertise-sectie -->
<section
  class="expertise section"
>
  <!-- Header van de expertise-sectie -->
  <header
    class="expertise-header"
  >
    <h2
      class="expertise-title"
    >
      Expertise
    </h2>
  </header>

  <!-- Wrapper voor de expertise cards -->
  <div
    class="expertise__wrapper"
  >
    <!-- Klimaatadaptatie card -->
    <div
      class="expertise__card"
    >
      <picture>
        <source
          srcset="assets/Untitled4.webp"
          type="image/webp"
        />
        <img
          class="expertise3"
          src="assets/Untitled4.png"
          alt="Illustratie klimaatadaptatie voor een groenere wereld"
          width="100px"
          height="100px"
        />
      </picture>
      <h3>
        Klimaatadaptatie
      </h3>
      <a
        href="#klimaat"
        class="button"
        aria-label="Meer informatie over klimaatadaptatie"
      >
        <p
          class="button_text2"
        >
          Meer
          informatie
        </p>
      </a>
    </div>

    <!-- Waterkwaliteit card -->
    <div
      class="expertise__card"
    >
      <picture>
        <source
          srcset="assets/Untitled3.webp"
          type="image/webp"
        />
        <img
          class="expertise2"
          src="assets/Untitled3.png"
          alt="Illustratie waterkwaliteit en milieubehoud"
          width="100px"
          height="100px"
        />
      </picture>
      <h3>
        Waterkwaliteit
      </h3>
      <a
        href="#waterkwaliteit"
        class="button"
        aria-label="Meer informatie over waterkwaliteit"
      >
        <p
          class="button_text2"
        >
          Meer
          informatie
        </p>
      </a>
    </div>

    <!-- B-Rain card -->
    <div
      class="expertise__card"
    >
      <picture>
        <source
          srcset="assets/brainlogo.webp"
          type="image/webp"
        />
        <img
          class="expertise2"
          src="assets/brainlogo.png"
          alt="Illustratie B-Rain, een innovatieve oplossing"
          width="100px"
          height="100px"
        />
      </picture>
      <h3>
        B-Rain
      </h3>
      <a
        href="#brain"
        class="button"
        aria-label="Meer informatie over B-Rain"
      >
        <p
          class="button_text2"
        >
          Meer
          informatie
        </p>
      </a>
    </div>
  </div>
</section>

<!-- Styles voor de Expertise-sectie -->
<style>
  .expertise {
    background-color: white;
    display: flex;
    flex-direction: column;
    position: relative;
  }

  .expertise-header {
    margin-left: 14rem;
  }

  .expertise-title {
    font-size: 1.5rem;
    color: var(
      --darkblue
    );
    font-weight: 600;
    text-align: left;
  }

  .expertise h3 {
    font-size: 1.3rem;
    color: var(
      --darkblue
    );
    font-weight: 600;
    text-align: center;
    padding-bottom: 1em;
  }

  .expertise__wrapper {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    padding: 4rem
      2rem;
    gap: 3rem;
  }

  .expertise__card {
    margin: 0 auto;
    height: 25em;
    width: 18em;
    border-radius: 4px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    box-shadow: 0
      4px 6px
      rgba(
        174,
        190,
        205,
        0.3
      );
    background-color: var(
      --lg-bg
    );
    color: var(
      --darkblue
    );
    transition: 0.3s
      ease-in;
  }

  .expertise__card
    img {
    width: 250px;
    padding-bottom: 2em;
  }

  .expertise__card
    .expertise2 {
    width: 250px;
    padding-top: 1em;
    padding-bottom: 0.5em;
  }

  .expertise__card:nth-child(
      2
    ),
  .expertise__card:nth-child(
      3
    ) {
    background-color: var(
      --lg-bg
    );
  }

  .expertise__card:hover {
    transform: scale(
      1.075
    );
    transition: 0.3s
      ease-in;
    cursor: pointer;
  }

  .button {
    display: inline-block;
    background-color: var(
      --green
    );
    color: white;
    padding: 0.7rem
      1rem;
    height: 50px;
    border-radius: 5px;
    font-weight: var(
      --font-semi-bold
    );
    transition: 0.3s;
    text-decoration: none;
  }

  .button_text2 {
    text-decoration: none;
    color: white;
    font-size: 1rem;
  }

  @media screen and (min-width: 1024px) {
    .expertise__wrapper {
      flex-direction: row;
      justify-content: space-around;
      padding: 4rem
        8rem;
      gap: 3rem;
    }
  }
  @media screen and (max-width: 1023px) {
    .expertise-title {
      text-align: center; /* Center the expertise title on smaller screens */
    }

    .expertise__wrapper {
      flex-direction: column;
      align-items: center; /* Center expertise cards on smaller screens */
    }

    .expertise-header {
      margin-left: 0; /* Remove the left margin on smaller screens */
    }
  }
</style>
