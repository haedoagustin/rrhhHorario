# Horarios de Portal SIAPE

Creado por https://github.com/sysi-lp

1. Instalar extensión en chrome: 
https://chrome.google.com/webstore/detail/custom-javascript-for-web/poakhlngfciodnhlhhgnaaelnpjljija

2. Agregar el script:
```javascript
var Dia = new Date();var ticks = Dia.getTime();var URL= window.location.pathname;console.log(URL);if ( (URL.includes("fichada"))) {$.getScript("https://kity-linuxero.github.io/rrhhHorario/horario.js?"+ticks);}
```