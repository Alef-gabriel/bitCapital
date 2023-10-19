<style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    #visualizer {
      width: 90%;
      height: 80vh;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    #container {
      width: 100%;
      height: 100%;
      display: flex;
      flex-direction: row;
      align-items: start;
    }

    #buttons {
      display: flex;
      flex-direction: row-reverse;
      margin-top: 2rem;
      height: 10%;
      width: 40%;
    }

    #return {
      margin-right: 60%;
    }

</style>
<body>
  <div id="buttons">
    <button>Aprove</button>
    <button>Reprove</button>
    <button id="return">return</button>
  </div>
  <div id="container">
      <div id="visualizer">
        visualizer
      </div>
  </div>
</body>