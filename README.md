# ToDoList-COD5436

Company_name : CODTECH IT SOLUTIONS

Intern Name : Aluganti Supriya 
ID : COD5436

TASK-1 : TO-DO LIST WEB APPLICATION

Code Explaination :
Sure, let's break down the provided code:

---------------------------HTML:
- The HTML structure defines the layout of the To-Do List application.
- It consists of a header displaying the title, a form for adding new to-do items, a select dropdown for filtering to-dos, and a container for displaying the to-do list.

-------------------------- CSS:
- The CSS file styles the HTML elements, defining their appearance, layout, and animations.
- It sets the background color, font styles, button styles, and layout properties.

--------------------------- JavaScript:
*DOM Selection
   - It selects various elements from the DOM using `document.querySelector`.
Event Listeners
   - `DOMContentLoaded`: When the DOM content is loaded, it calls the `getLocalTodos` function to retrieve to-dos from local storage and display them.
   - `click` event on the todo button: Calls the `addTodo` function to add a new to-do item.
   - `click` event on the todo list: Calls the `deleteCheck` function to handle deleting or marking to-dos as completed.
   - `change` event on the filter dropdown: Calls the `filterTodo` function to filter displayed to-dos based on their completion status.
Functions
   - `addTodo`: Adds a new to-do item to the list by creating HTML elements dynamically and appending them to the DOM. It also saves the new to-do to local storage.
   - `deleteCheck`: Handles the deletion of to-do items or marking them as completed. It also removes the corresponding to-do from local storage.
   - `filterTodo`: Filters displayed to-dos based on the selected option in the filter dropdown.
   - `saveLocalTodos`: Saves the current to-do list to local storage.
   - `getLocalTodos`: Retrieves saved to-dos from local storage and displays them on the page.
   - `removeLocalTodos`: Removes a to-do item from local storage.

---Conclusion :
- The code creates a simple but functional To-Do List application with the ability to add, delete, and filter to-dos. It uses local storage for data persistence, allowing the to-do list to be retained even after refreshing the page.
