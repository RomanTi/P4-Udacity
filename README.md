3 part were optimized:

CPR optimization to archive >90 score on pagespeed insights:
  
- CSS was inlined
- Media query was configured to use print.css
- JS was made async
- Images were resized and compressed
- CSS, JS and HTML were minified


Rendeding optimization to achieve 60FPS:

- updatePositions function is optimized;
- number of sliding pizzas was reduced to 50 instead of 200;
- hardware accelerated composition enabled for the class .mover;
- getElementsByClassName is used instead of querySelectorAll;

Rendeding optimization to achieve time to resize pizzas less than 5 ms :

- changePizzaSizes function was optimized;


To Open WebSite please open index.html file in dist folder.
To Open Pizza application please open pizza.html in dist/views folder