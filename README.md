<!doctype html>
  <head>
    <style>

      #cuadrado1 {
        width:100px;
        height: 100px;
        background: red;
        position: relative;
        animation: movin 5s infinite;
        

      }
      @keyframes movin{
        0% {top: 0px;}
        50%{top: 50px; background:blue;}
        100% {top: 300px}

        
      }
      #cuadrado2 {width:100px;
        height: 100px;
        background: black;
        position: relative;
        animation: movin 5s infinite;
     
      }



    </style>
  </head>  
  <body>
    hola mundo!
    <div id="cuadrado1">

    </div>
    <div id="cuadrado2">

    </div>

  </body>

</html
