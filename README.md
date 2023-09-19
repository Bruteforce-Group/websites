<!DOCTYPE html>
<html lang="en">

  <head>
    <meta charset="utf-8" />
    <link rel="icon" href="favicon.png" type="image/png" sizes="16x16">
    <meta name="who" content="watch.out" />
    <style>
      body {
        background-color: black;
        display: flex;
        align-items: center;
        justify-content: center;
        height: 100vh;
      }

      #coming-soon {
        font-family: 'Helvetica', sans-serif;
        color: white;
        opacity: 0;
        animation: fade 5s infinite;
        font-size: 4em;
      }

      @keyframes fade {
        0% {
          opacity: 0;
        }

        50% {
          opacity: 1;
        }

        100% {
          opacity: 0;
        }
      }

    </style>
    <title>Bruteforce Group!</title>
  </head>

  <body>
    <div id="coming-soon">... it's coming</div>
  </body>

</html>
