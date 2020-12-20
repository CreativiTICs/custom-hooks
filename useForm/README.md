# useForm Hook

Ejemplo de uso:
```
    const initialForm = {
        name: '',
        age: 0,
        email: ''
    }

    const [formValues, handleInputChange, reset] = userForm(initialForm);
    
```

useForm() // Recibe un initialForm por defecto