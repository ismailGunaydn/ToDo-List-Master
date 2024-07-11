
1. TodoItemFormatter Class:
- This class is responsible for formatting the task, due date, and status of To-Do items.
- The methods `formatTask(task)`, `formatDueDate(dueDate)`, and `formatStatus(completed)` are used to format the textual representation of tasks.

2. TodoManager Class:
- This class manages the To-Do items and provides functionalities to add, edit, delete, toggle status, filter, and save to local storage.
- It includes methods like `addTodo(task, dueDate)`, `editTodo(id, updatedTask)`, `deleteTodo(id)`, `toggleTodoStatus(id)`, `clearAllTodos()`, `filterTodos(status)`, `getRandomId()`, and `saveToLocalStorage()`.

3. UIManager Class:
- This class handles the user interface interactions and event handling for adding new tasks, deleting all tasks, toggling task status, and filtering tasks.
- Methods like `addEventListeners()`, `handleAddTodo()`, `handleClearAllTodos()`, `showAllTodos()`, `displayTodos(todos)`, `handleEditTodo(id)`, `handleToggleStatus(id)`, `handleDeleteTodo(id)`, `handleFilterTodos(status)`, and `showAlertMessage(message, type)` are part of this class.
- Event listeners are added to handle user interactions such as button clicks and keypress events.

4. ThemeSwitcher Class:
- This class manages the application's theme and facilitates theme changes in the user interface.
- The methods `init()`, `addThemeEventListeners()`, `setTheme(themeName)`, `saveThemeToLocalStorage(themeName)`, and `getThemeFromLocalStorage()` are involved in handling theme switching functionality.

The `init()` method initializes the theme switcher, retrieves the saved theme from localStorage, and adds event listeners to theme change buttons.
The `addThemeEventListeners()` method listens for click events on theme change buttons and updates the theme by setting the `data-theme` attribute of the HTML element.
The `saveThemeToLocalStorage(themeName)` method saves the selected theme to localStorage, retaining the user's theme preference across visits.
The `getThemeFromLocalStorage()` method retrieves the saved theme from localStorage for application theme consistency.

Feel free to ask if you have any more specific questions or need further clarification on any part of the code!
