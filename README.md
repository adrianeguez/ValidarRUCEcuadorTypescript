# ValidarRUCEcuadorTypescript
Repositorio para validar el RUC en Ecuador
## ¿Cómo usarlo?
Para utilizarlo debemos de importar los dos archivos, el `validar-cedulta.ts` y el archivo `validar-ruc.ts`. El archivo `validar-ruc.ts` depende de la validación de cédula. Es por eso que se necesita importar los dos.

Para usarlo dentro del código simplemente llamarlo de la siguiente forma en cualquier archivo:


```javascript
import {validarRuc} from '../ruta/hacia/el/archivo/validar-ruc';

const ruc = '1718137159001';

if ( validarRuc(ruc) ) {
  console.log('RUC válido');
} else {
  console.log('RUC inválido');
}
```

