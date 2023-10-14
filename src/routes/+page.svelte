<style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    #visualizer {
      width: 50%;
      height: 80vh;
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
      margin-top: 3rem;
      height: 10%;
      width: 40%;
    }

</style>
<body>
  <div id="buttons">
    <button>Create +</button>
    <button>Delete</button>
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
</body>