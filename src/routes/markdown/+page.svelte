<style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    #visualizer {
      width: 80%;
      height: 80vh;
      display: flex;
      justify-content: start;
      align-items: start;
      padding-left: 2rem;
      padding-top: 2rem;
    }

    #container {
      width: 100%;
      height: 100%;
      display: flex;
      flex-direction: row;
      align-items: start;
    }
    textarea {
      width: 40%;
      height: 40%;
    }
    
    #project-name{
      padding-right: 43%;
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
    <div id="project-name">
      <i>name /</i>
      <i>arquive name</i>
    </div>
  </div>
  <div id="container">
      <div id="visualizer">
        <textarea />
      </div>
  </div>
</body>