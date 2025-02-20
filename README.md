# Todo List Application

This is a **Todo List Application** built using **HTML, CSS, JavaScript, and Bootstrap**. It allows users to create, manage, and save tasks locally. Users can add tasks, mark them as completed, and delete them. The application uses **local storage** to persist tasks even after the page is refreshed.

## Features

- **Add Tasks**: Users can add new tasks by typing in the input field and clicking the "Add" button.
- **Mark as Completed**: Tasks can be marked as completed by checking the checkbox.
- **Delete Tasks**: Tasks can be deleted using the trash icon.
- **Save Tasks**: Tasks are saved in the browser's local storage and persist even after the page is refreshed.
- **Responsive Design**: The application is optimized for both desktop and mobile devices.

## Technologies Used

- **HTML**: For structuring the content.
- **CSS**: For styling the application.
- **Bootstrap**: For responsive design and pre-built components.
- **JavaScript**: For handling task creation, completion, deletion, and local storage.
- **Font Awesome**: For icons (e.g., trash icon).

## How to Use

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/lpkumarreddy/Todo-Application.git
   ```
2. Open the `index.html` file in your browser.
3. Add tasks by typing in the input field and clicking the "Add" button.
4. Mark tasks as completed by checking the checkbox.
5. Delete tasks by clicking the trash icon.
6. Tasks are automatically saved in local storage and will persist even after refreshing the page.

## Project Structure

- **`index.html`**: The main HTML file containing the structure of the application.
- **CSS Styling**: Custom styles are applied to the tasks, buttons, and layout.
- **JavaScript**: Handles task creation, completion, deletion, and local storage.
- **Bootstrap Components**: Used for responsive design and layout.
- **Font Awesome**: Used for the trash icon.

## Screenshots

### Home Page
![Home Page](https://via.placeholder.com/600x400.png?text=Todo+List+Home+Page)

### Task List
![Task List](https://via.placeholder.com/600x400.png?text=Task+List+Example)

## Code Explanation

### HTML Structure
- The `input` element is used for adding new tasks.
- The `button` elements are used for adding and saving tasks.
- The `ul` element dynamically displays the list of tasks.

### JavaScript Functionality
- **`getTodoListFromLocalStorage`**: Retrieves the task list from local storage.
- **`onAddTodo`**: Adds a new task to the list and updates the DOM.
- **`onTodoStatusChange`**: Marks a task as completed or incomplete.
- **`onDeleteTodo`**: Deletes a task from the list and updates the DOM.
- **`createAndAppendTodo`**: Creates and appends a new task to the DOM.
- **Local Storage**: Tasks are saved in local storage using `localStorage.setItem`.

### CSS Styling
- Custom styles are applied to the tasks, buttons, and layout.
- Bootstrap classes are used for responsive design.

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## MIT License

```plaintext
MIT License

Copyright (c) 2025 LINGAM PAVAN KUMAR REDDY

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## How to Contribute

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeatureName`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeatureName`).
5. Open a pull request.
