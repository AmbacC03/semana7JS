```
function Ship(calado, tripulacion) {
    this.calado = calado;
    this.tripulacion = tripulacion
;
  
    this.isWorthIt = function () {
      return this.calado - this.tripulacion * 1.5 > 20;
    };
  }
```
