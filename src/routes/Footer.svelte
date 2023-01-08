<footer>
  <!-- <section id="Footer">© 2022 CMD AMSTERDAM</section> -->
  <div id="Footer">
    <div id="scroll-text">
      © 2022 CMD AMSTERDAM
      <div />
    </div>
  </div>
</footer>

<style>
  #Footer {
    overflow: hidden;
    height: 4em;
    background-color: black;
    color: white;
    padding: 2em;
  }
  #scroll-text {
    text-align: right;
    /* animation properties */
    -moz-transform: translateX(-100%);
    -webkit-transform: translateX(-100%);
    transform: translateX(-100%);
    -moz-animation: my-animation 50s linear infinite;
    -webkit-animation: my-animation 50s linear infinite;
    animation: my-animation 50s linear infinite;
  }
  /* for Firefox */
  @-moz-keyframes my-animation {
    from {
      -moz-transform: translateX(-100%);
    }
    to {
      -moz-transform: translateX(100%);
    }
  }
  /* for Chrome */
  @-webkit-keyframes my-animation {
    from {
      -webkit-transform: translateX(-100%);
    }
    to {
      -webkit-transform: translateX(100%);
    }
  }
  @keyframes my-animation {
    from {
      -moz-transform: translateX(-100%);
      -webkit-transform: translateX(-100%);
      transform: translateX(-100%);
    }
    to {
      -moz-transform: translateX(100%);
      -webkit-transform: translateX(100%);
      transform: translateX(100%);
    }
  }
</style>
