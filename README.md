# TaskManager

TaskManager is a Task Management App built with JavaScript, HTML, CSS, and the Py4web framework. The app allows users to create, manage, delete tasks, and add comments to tasks efficiently.

## Features

- **Add Tasks**: Create new tasks with details.
- **Edit Tasks**: Modify existing tasks.
- **Delete Tasks**: Remove tasks that are no longer needed.
- **Task Completion**: Mark tasks as completed or pending.
- **Add Comments**: Add comments to tasks for additional context or notes.
- **Responsive Design**: The app is mobile-friendly and works on all device sizes.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Py4web framework (Python)

## Installation

### Prerequisites

- Python 3.6 or higher
- Pip (Python package installer)

### Steps

1. **Clone the repository**

    ```bash
    git clone https://github.com/your-username/task-manager.git
    cd task-manager
    ```

2. **Set up a virtual environment**

    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Py4web server**

    ```bash
    py4web run apps -H localhost -P 8000
    ```

5. **Access the app**

    Open your browser and go to `http://localhost:8000/taskManager`

## Usage

- **Adding a Task**: Use the input field to enter a task description and click the "Add Task" button.
- **Editing a Task**: Click the "Edit" button next to the task you want to modify.
- **Deleting a Task**: Click the "Delete" button next to the task you want to remove.
- **Marking as Complete**: Click the checkbox next to the task to mark it as completed.
- **Adding Comments**: Click the "Add Comment" button next to a task to add comments.



