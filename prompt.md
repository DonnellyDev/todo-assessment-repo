# Interactive Todo List

You are tasked with implementing an interactive todo list using JavaScript and DOM manipulation. You are provided with an HTML file containing the basic structure of the todo list, including an input field, an "Add" button, and a div with the id "todoItems" where the todo items will be displayed.
Requirements:

Use the following data array as the initial set of todos:

```javascript
let todos = [
    { id: 1, text: "Buy groceries", completed: false },
    { id: 2, text: "Finish homework", completed: true },
    { id: 3, text: "Call mom", completed: false }
];
```

1. Display the existing todos from the data array when the page loads.
2. Implement functionality to add new todos:
   - When the user enters text in the input field and clicks the "Add" button, a new todo should be added to the list.
   - The input field should be cleared after adding a todo.

3. Each todo item should have:

   - A checkbox to toggle its completion status
   - The todo text
   - A delete button

4. Implement functionality to toggle a todo's completion status:

    - When a user clicks on a todo's checkbox, its completion status should toggle between completed and not completed.
    - Completed todos should have a line-through style applied to their text.

5. Implement functionality to delete a todo:
   - When a user clicks the delete button on a todo, that todo should be removed from the list.

6. Ensure that the UI stays in sync with the data model (the todos array) at all times.

Your task is to write the JavaScript code that implements these features using DOM manipulation techniques. Focus on creating a solution that is both functional and demonstrates good practices in handling user interactions and updating the UI.
