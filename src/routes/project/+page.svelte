<style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    #visualizer {
      width: 50%;
      height: 65vh;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    i {
      padding-left: 2rem;
    }
    #container {
      width: 100%;
      height: 100%;
      display: flex;
      flex-direction: row;
      align-items: start;
    }

    #dirs {
      display: flex;
      flex-direction: column;
      align-items: start;
      height: 40%;
      width: 40%;
    }

    #buttons {
      display: flex;
      flex-direction: row-reverse;
      margin-top: 1rem;
      height: 10%;
      width: 40%;
    }

    #columns {
      display: flex;
      flex-direction: column;
      width: 50%;
      height: 30%;
    }

    #section {
      display: flex;
      flex-direction: row;
    }

    p {
      margin-left: 0.8rem;
    }

    #buy {
      display: flex;
      flex-direction: row-reverse;
      align-items: end;
      padding-right: 2rem;
    }
</style>
<body>
  <div id="columns">
    <div id="section">
      <p>Balance ETH</p>
      <p>Proposal</p>
    </div>

    <div id="section">
      <p>Saque</p>
      <p>Fading</p>
    </div>
    <div id="buttons">
      <button>Sell</button>
    </div>
  </div>
  <div id="container">
      <div id="dirs">
          <i>Archive</i>
          <i>Archive</i>
      </div>
      <div id="visualizer">
        visualizer
      </div>
  </div>
  <div id="buy">
    <button>Buy</button>
  </div>
</body>