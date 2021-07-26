## particles.js

### A lightweight JavaScript library for creating particles.

------------------------------
### `Demo / Generator`

Click on picture to see Demo/Generator on web

<a href="http://vincentgarreau.com/particles.js/" target="_blank"><img src="http://vincentgarreau.com/particles.js/assets/img/github-screen.jpg" alt="particles.js generator" /></a>

Configure, export, and share your particles.js configuration on CodePen: <br />
http://vincentgarreau.com/particles.js/

CodePen demo: <br />
http://codepen.io/VincentGarreau/pen/pnlso

-------------------------------
### `Note`

* If you clone this repository you can show on web a background similar to the picture above
* But, `if you want to change the background,` follow this steps:

`First part:`
1. Go to http://vincentgarreau.com/particles.js/
2. In rigth side you can see Control Panel
3. Click on "DEFAULT" and choose an option (e.g NASA, Bubble, Snow, Nyan cat)
4. e.g if you choose Snow, try to click on particles->shape->circle
5. when you click on "circle" you can choose an option (e.g circle, edge, triangle, polygon, star, image)
6. Let's try to change the configuration (e.g number, color, size, opacity, ...)
7. Finally, click on "Download current config (json)" below at the end, and the browser will download "particlesjs-config.json"

`Second part:`
1. Open "particlesjs-config.json" file and copy all content
2. Open "app.js" and paste under "particlesJS('particles-js',"

**app.js**
```javascript

particlesJS('particles-js',
  
  /* Erase all content below and Paste all content of "Download current config (json)" */
  {
    "particles": {
      "number": {
        "value": 180,
        "density": {
          "enable": true,
          "value_area": 800
        }
      },
      
      [...]
      [...]
```

-------------------------------


