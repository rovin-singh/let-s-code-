# Some Important Coding Step : 

### Table of Contents

| No. | Questions |
| --- | --------- |
|   | **Core React** |
|1  | [Add data into simple Todo ?](#Add-data-into-simple-Todo) |


## Let's Code 


    
1. ### Add data into simple Todo ?

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


   **[⬆ Back to Top](#table-of-contents)**
