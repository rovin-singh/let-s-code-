# React Some Important Steps:

### Add Data into Simple Todo :

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

### Toggle simple Todo Data :

```
 const handleToggle = (id) => {
    const updatedData = todos.map((item) =>
      item.id === id
        ? {
            ...item,
            isCompleted: !item.isCompleted
          }
        : item
    );
    setTodos(updatedData);
  };

```

### Delete data from Simple Todo :

```
 const handleDelete = (id) => {
    let newTodos = todos.filter((item) => item.id !== id);
    setTodos(newTodos);
  };

```
