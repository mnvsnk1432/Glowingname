<!DOCTYPE html>
<html>
    <head>
        <meta chars="utf-8">
        <meta name="viewpoint" content="width=device-width, initial-scale=1.0">

        <title>lighting name</title>
      <style>
      
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    
}

body{
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: black;
}

h2{
    display: flex;
    color: transparent;
    font-size: 15vw;
}

h2 span{
    animation: animate 2s linear infinite;
    animation-delay: calc((0.1s) * var(--i));
}
@keyframes animate {
    0%{
        color:white;
        filter:blur(1px) hue-rotate(0deg);
        text-shadow: 0 0 10px #00b3ff,
        0 0 20px #00b3ff, 
        0 0 40px #00b3ff, 
        0 0 80px #00b3ff, 
        0 0 120px #00b3ff, 
        0 0 200px #00b3ff,
        0 0 300px #00b3ff, 
        0 0 400px #00b3ff ;
    }
    30%, 70%{
        color:white;
        filter:blur(1px) hue-rotate(360deg);
        text-shadow: 0 0 10px #00b3ff,
        0 0 20px #00b3ff, 
        0 0 40px #00b3ff, 
        0 0 80px #00b3ff, 
        0 0 120px #00b3ff, 
        0 0 200px #00b3ff ;
    }
    100%{
        color: transparent;
        box-shadow: none;
        filter: blur(2px) hue-rotate(0deg);
    }
}

      </style>
    </head>
    <body>
        <h2>
            <span style="--i:1;">M</span>
            <span style="--i:2;">n</span>
            <span style="--i:3;">v</span>
            <span style="--i:4;">s</span>
            <span style="--i:5;">n</span>
            <span style="--i:6;">k</span>
            
        </h2>
    </body>
</html>
