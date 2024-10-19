# Morphle Labs Pvt Ltd Assignment

This repository contains the solution and code for the Morphle Labs Pvt Ltd Assignment. It demonstrates the implementation of a Flask application with an `/htop` endpoint. The `/htop` endpoint provides essential system details such as the username, server time in IST, and the output of the `top` command. The application is designed to run seamlessly in GitHub Codespaces.

## Features

- **System Monitoring:** Displays real-time system information such as CPU usage, memory, and active processes using the `top` command.
- **User Information:** Retrieves and displays the current user running the Flask application.
- **Server Time in IST:** The server time is displayed in Indian Standard Time (IST) format.

## How to Run

To run this project locally, follow the steps below:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Morphle-Labs-Pvt-Ltd-Assignment.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Morphle-Labs-Pvt-Ltd-Assignment
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Flask application:
    ```bash
    python app.py
    ```

5. Visit the `/htop` endpoint by opening your browser and navigating to:
    ```
    http://localhost:5000/htop
    ```

## Deployed Application

The application has been deployed on GitHub Codespaces and can be accessed publicly via the following link:
[https://fictional-space-parakeet-jvjpw5x545r2jjj6-5000.app.github.dev/htop](https://fictional-space-parakeet-jvjpw5x545r2jjj6-5000.app.github.dev/htop)

## Technologies Used

- **Python**: Flask framework is used to build the backend.
- **Subprocess**: To capture and display the output of the `top` command.
- **GitHub Codespaces**: The application is designed to run in GitHub Codespaces, enabling easy access to system monitoring on remote servers.

## Contact

For any inquiries or further information, please contact the developer:

- **Full Name**: Angadi Mohammad Sadiq
- **Email**: [angadimohammadsadiq@gmail.com](mailto:angadimohammadsadiq@gmail.com)

---

This project is part of the Morphle Labs Pvt Ltd assignment submission.
