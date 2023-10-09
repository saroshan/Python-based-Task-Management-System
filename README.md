# Python-based-Task-Management-System


This Python-based Task Management System allows users to efficiently create, manage, and track tasks. The system is designed with a focus on user management, task management, task listing, task notifications, and optional features like task categories and task analytics. It adheres to Object-Oriented Programming (OOP) principles and utilizes appropriate data structures.

## Features

### 1. User Management

- Create and manage user profiles.
- Users have a username, full name, and email address.

### 2. Task Management

- Users can create tasks with the following attributes:
  - Title: A short, descriptive title for the task.
  - Description: Additional details about the task.
  - Due Date: The date by which the task should be completed.
  - Priority: The priority level of the task (e.g., High, Medium, Low).
  - Status: The current status of the task (e.g., Not Started, In Progress, Completed).
- Users can assign tasks to themselves or other users.
- Users can mark tasks as completed.
- Users can edit and delete tasks.

### 3. Task Listing

- Users can view a list of tasks, filtered by criteria such as status, due date, or priority.
- Tasks are displayed in a user-friendly format, including task details and their current status.

### 4. Task Notifications

- Users receive notifications for upcoming tasks that are nearing their due dates.
- Notifications can be sent via email or displayed within the system.

### 5. Task Categories (Optional)

- Users can categorize tasks into different categories (e.g., Work, Personal, Shopping).
- Users can view tasks by category.

### 6. Task Analytics (Optional)

- Users can view statistics and analytics about their tasks, such as the number of completed tasks per week or the average time taken to complete tasks.

## Usage

To run the Task Management System, follow these steps:

1. Clone the repository to your local machine.

bash
git clone https://github.com/saroshan/task-management-system.git
cd task-management-system


2. Install any required dependencies.

bash
pip install -r requirements.txt


3. Run the main application.

bash
python main.py


4. Access the system through your web browser or follow the command-line interface prompts.

## Implementation Details

- The system is implemented using Python and follows Object-Oriented Programming (OOP) principles.
- User and task information is stored in appropriate data structures, such as dictionaries and lists.
- Error handling is in place for cases like editing or deleting tasks that don't exist.
- Tasks are uniquely identified using task IDs.

## Optional Features

If you wish to implement optional features like task categories or task analytics, you can refer to the respective sections of the codebase or documentation for more details.

## Contributors

- [Roshan Sawant](https://github.com/saroshan) - Lead Developer

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to the open-source community and libraries that made this Task Management System possible.

---

Feel free to customize this README file to match your project's specifics and provide more details about your implementation. Include information on how to set up a database if you choose to go beyond storing data in memory.
