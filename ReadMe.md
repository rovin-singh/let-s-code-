# React Some Important Steps: 


## Add Data into Simple Todo :

```
 const handleAdd = (text) => {
    setTodos([
      ...todos,
      {
        id: todos.length,
        title: text,
        isCompleted: false
      }
    ]);
  };
  
```