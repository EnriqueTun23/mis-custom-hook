## useFetch Hook

Ejemplo de uso: 
```
    const initialForm = {
        name: '',
        age: 0,
        email: 'ejemploqq@correo.com'
    }
    const [ values, handleInputChange, reset ] = useForm(initialForm);
```

useForm() // recibe la validacion para el uso en el formulario