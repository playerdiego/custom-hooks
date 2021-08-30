# useForm

example: 

```
    const initialForm = {
        name: 'Diego',
        age: 19,
        email: 'diego@gmail.com'
    }
    const [values, handleInputChange, reset, setValues] = useForm(initialForm)
```