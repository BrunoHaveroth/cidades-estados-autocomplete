# cidades-estados-autocomplete
This library is a modification of city-states-inv0.2.js, available in: https://code.google.com/p/cidades-estados-js/downloads/detail?name=cidades-estados-v0.2.js&can=2&q=.

Is replaced the SELECT of cities for component autocomplite do Jquery UI.

# how to use

1- Import in your project:
  - jquery
  - jquery UI - JS/CSS
  - cidades-estados-autocomplete.js
  
2- In your HTML:
  ```html
    <select name="estado" id="estado"></select>
    <input class="city" name="cidade" id="cidade">
  ```
3- In your JS
  ```javascript
    new dgCidadesEstados( 
      $('#estado').get(0),
      $('#cidade').get(0),
      true
    );
  ```
  
