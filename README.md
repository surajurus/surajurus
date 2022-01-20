
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      .container {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(225px, 1fr));
        grid-template-rows: repeat(auto-fill, minmax(150px, 1fr));
        grid-gap: 5px;
        grid-auto-rows: minmax(100px,auto);
        grid-auto-columns: minmax(50px,auto);


      }
      .item {

        background-color: lightcoral;
        border: 3px yellow solid;
        border-radius: 2px;


      }

    </style>
  </head>
  <body>
    <div class="container">
      <div class="item" id="one"><b>dabba 1</b></div>
      <div class="item" id="two"><b>dabba 2</b></div>
      <div class="item"><b>dabba 3</b></div>
      <div class="item"><b>dabba 4</b></div>
      <div class="item"><b>dabba 5</b></div>

    </div>
  </body>
</html>
