# Exam Simulation System

The **Exam Simulation System** is a web-based application that allows users to register, take exams, and manage exam content. It's built using PHP and HTML, and you can run it locally using XAMPP.

## Features

- **User Registration:**
  - Students and teachers can register with unique codes.
  - Admins can manage user accounts.

- **Exam Creation and Management:**
  - Admins can create and manage exams.
  - Define questions, options, and correct answers.
  - Set time limits for each exam.

- **Taking Exams:**
  - Students can log in and take exams.
  - Timer keeps track of the remaining time.
  - Instant feedback on correct and incorrect answers.

## Installation

1. **XAMPP Setup:**
   - Download and install [XAMPP](https://www.apachefriends.org/download.html) (if not already installed).
   - Start the Apache and MySQL services.

2. **Database Configuration:**
   - Create a new MySQL database (e.g., `exam_simulation_system`).
   - Import the SQL schema from `database.sql`.

3. **Project Setup:**
   - Clone this repository.
   - Place the project files in the `htdocs` directory of your XAMPP installation.

4. **Configuration:**
   - Update the database connection details in `config.php`.

5. **Access the Application:**
   - Open your web browser and navigate to `http://localhost/exam-simulation-system`.

## Usage

1. **Admin Dashboard:**
   - Log in as an admin (use the predefined admin credentials).
   - Create exams, manage users, and view exam results.

2. **Student Dashboard:**
   - Log in as a student (use the predefined student credentials).
   - Take available exams and view results.


## Contributing

Contributions are welcome! If you find any issues or have suggestions, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to replace specific details about your exam simulation system. Good luck with your project! 🚀📝¹²



¹: [XAMPP Tutorial: how to create your own local test server](https://www.ionos.com/digitalguide/server/tools/xampp-tutorial-create-your-own-local-test-server/)
²: [refer to phpdocs for more learnings](https://www.bing.com/ck/a?!&&p=90d25c06df61be4dJmltdHM9MTcxNTEyNjQwMCZpZ3VpZD0xMjNjYTBlMC1kY2EyLTZiNTAtMTk4Yi1iMzczZGQzMTZhNTQmaW5zaWQ9NTIxNg&ptn=3&ver=2&hsh=3&fclid=123ca0e0-dca2-6b50-198b-b373dd316a54&psq=php+docs&u=a1aHR0cHM6Ly93d3cucGhwLm5ldC9kb2NzLnBocA&ntb=1)
