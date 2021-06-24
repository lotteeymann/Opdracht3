# Opdracht3
Textures
<!DOCTYPE html>
<html>
  [grass](https://user-images.githubusercontent.com/86419683/123298019-64ae2d80-d518-11eb-8189-ad245d4a52b2.jpg)
  [wood](https://user-images.githubusercontent.com/86419683/123298052-6b3ca500-d518-11eb-87d1-9591d41778c2.jpg)

  <head>
    <meta charset="utf-8">
    <title>Hello, WebVR! • A-Frame</title>
    <meta name="viewport" content="width=device-width">
    <script src="https://aframe.io/releases/1.0.4/aframe.min.js"></script>
    <script src="scripts/main.js" defer></script>
  </head>
  <body>
    <a-scene background="color: #333333">
      <a-assets>
          <img id="wood" src="images/wood.jpg" />   
      </a-assets>
      <a-box id="myBox" 
        position="0 1 -3" 
        rotation="0 45 0" 
        width="3" 
        height="1" 
        depth="1" 
        material="src:#wood"
        shadow>
      </a-box>
      <a-plane id="ground"
        position="0 0 -4" 
        rotation="-90 0 0" 
        width="100" 
        height="100" 
        color="#7BC8A4" 
        shadow>
      </a-plane> 
    </a-scene>
  </body>
</html>
