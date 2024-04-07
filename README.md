# Simple Todo List Application with Docker

![preview of todo list app](<gb/Screenshot 2024-04-08 054742.png>)

---

This is a straightforward todo list application that runs with Docker, providing you with an easy way to manage your tasks.

## Features

- **Add New Todo Lists:** Create and add as many todo lists as you like to organize your tasks effectively.
  
- **Review Created Todo Lists:** Easily review and manage the todo lists you've created at any time.
  
- **Delete Completed Todo Lists:** Mark your tasks as done and remove them from your todo lists effortlessly.

**Note:** It's important to be aware that any unsaved todo lists may be lost if the application is shut down for an extended period.

## Getting Started

To run this application locally using Docker, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Build the docker-compose:
    ```bash
    docker-compose up --build
    ```
    or
   ```bash
   docker-compose up -d
   ```
4. Access the application in your web browser at ```http://localhost:5000/```.

## Contributing

Contributions are welcome! If you have any ideas, improvements, or feature requests, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
