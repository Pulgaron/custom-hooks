#useForm Hook

Ejemplo de uso: 

```
    const initialForm = {
        name: '',
        age: 0,
        email: ''
    }
    const [formValues, handleInputChange,reset] = useForm(10) 

```

useForm() //recibe un valor por defecto