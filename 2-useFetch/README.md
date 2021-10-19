# useFetch

Hook para realizar peticiones a un _endpoint_

## Ejemplo de uso

Recibe una url para realizar la petición.

- data: Retorna la información; en caso de error retorna null.
- loading: Util para mostrar/ocultar un loader.
- error: Retorna null; en caso de un error 'No se pudo cargar la info'.

```
  const url = 'https://nombre.dominio/endpoint'

  const {data: null, loading: true, error: null} = useFetch(url);
```