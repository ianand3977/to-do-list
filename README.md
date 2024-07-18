# To-Do List App

This is a simple and interactive To-Do List application that allows users to add, mark as completed, and remove tasks. The tasks are stored in the browser's local storage, ensuring they persist across sessions.

![image](https://github.com/user-attachments/assets/941ad802-8597-42f8-bc30-3172a83df99c)


## Features

- Add new tasks to the list.
- Mark tasks as completed by clicking on them.
- Remove tasks by clicking the close (×) button.
- Persist tasks using local storage so that tasks are saved even after refreshing the page.

## Technologies Used

- HTML
- CSS
- JavaScript

## How to Use

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/ianand3977/to-do-list.git
    ```

2. Navigate to the project directory:

    ```bash
    cd to-do-list
    ```

3. Open `index.html` in your preferred browser.

4. Add your tasks using the input box and click the "Add" button to save them.



## Code Explanation

### HTML

The HTML file creates the basic structure of the To-Do List app, including the input box, add button, and the list container where tasks are displayed.

### CSS

The CSS file styles the To-Do List app, making it visually appealing and user-friendly. It includes styles for the container, input box, buttons, and list items.

### JavaScript

The JavaScript file contains the core functionality of the To-Do List app. It includes functions to add tasks, mark them as completed, remove tasks, and save/load tasks to/from local storage.

#### Functions:

- **addTask()**: Adds a new task to the list. If the input box is empty, it alerts the user to enter a task.
- **saveData()**: Saves the current list of tasks to local storage.
- **showTask()**: Loads tasks from local storage when the page is loaded or refreshed.
- **Event Listeners**: Handles click events on list items and close buttons to mark tasks as completed or remove them, respectively.

## Local Storage

The app uses the browser's local storage to save tasks, ensuring that tasks persist even after the page is refreshed. This is handled by the `saveData()` and `showTask()` functions.

## Contributing

If you'd like to contribute to this project, please fork the repository and create a pull request with your changes.
