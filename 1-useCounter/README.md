# useCounter

Simple contador para incrementar/decrementar el valor por defecto de 1 en 1.

## Ejemplo de uso
Recibe un número como valor inicial.

- counter: El valor actual
- increment: Agregar a un boton con el evento onClick
- decrement: Agregar a un boton con el evento onClick
- reset: Reinicia al valor inicial.

```
  const initialValue = 5;

  const {counter, increment, decrement, reset} = useCounter(initialValue);
```