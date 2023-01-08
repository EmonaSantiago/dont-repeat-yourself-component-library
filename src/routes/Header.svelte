<header>
  <button onclick="window.location.href='';">
    <h1>CMD MIDTERM</h1>
  </button>
  <nav class="navigation">
    <button
      onclick="window.location.href='https://emonasantiago.github.io/tech-stack/';"
    >
      <a>Beoogde leerresultaten</a>
    </button>
    <button
      onclick="window.location.href='https://emonasantiago.github.io/tech-stack/';"
    >
      <a>Onderwijsleeromgeving</a>
    </button>
    <button
      onclick="window.location.href='https://emonasantiago.github.io/tech-stack/';"
    >
      <a>Toetsing</a>
    </button>
    <button
      onclick="window.location.href='https://emonasantiago.github.io/tech-stack/';"
    >
      <a>Gerealiseerde leerresultaten</a>
    </button>
  </nav>
</header>

<style>
  header {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    padding: 1rem;
  }

  .navigation h1 {
    float: left;
  }

  .navigation a {
    font-size: 18px;
    margin: 1em;
    /* float: right; */
  }
  .navigation {
    background-color: white;
    color: rgb(0, 0, 0);
  }

  button {
    background: none;
    color: inherit;
    border: none;
    padding: 0;
    font: inherit;
    cursor: pointer;
    outline: inherit;
  }
  button:hover {
    border: 3px solid #fff021;
  }
</style>
