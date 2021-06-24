# Opdracht3
Textures
![grass](https://user-images.githubusercontent.com/86419683/123298548-e30acf80-d518-11eb-961e-da010f751757.jpg)
![wood](https://user-images.githubusercontent.com/86419683/123298560-e7cf8380-d518-11eb-8079-b70b8f9ef36f.jpg)


<!DOCTYPE html>
<html>
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
