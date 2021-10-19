# useForm

Hook personalizado para realizar peticiones a un _endpoint_

## Ejemplo de uso

Recibe un arreglo con el nombre de cada campo del formulario con su respectivo tipo de dato.

Retorna: 
 - formValues: Un objeto con el valor actual de cada _input_.
 - handleInputChange: Manejo del evento de un _input_.
 - reset: Coloca el form con sus valores initiales.

```
  const initialForm = {
    name: "",
    age: 0,
    email: "",
  }

  const  [ formValues, handleInputChange, reset ] = useForm(initialForm);

```