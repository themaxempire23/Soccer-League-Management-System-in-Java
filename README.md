# Soccer Management System

This Java application, built using the CUBA framework and MariaDB, empowers you to manage a comprehensive soccer league, providing insightful data and tools to elevate your league's organization and excitement.

Features

League Table: Gain a clear view of your league's standings with a detailed table showcasing:
Matches Played (MP)
Wins (W)
Draws (D)
Losses (L)
Goals For (GF)
Goals Against (GA)
Goal Difference (GD)
Points (Pts)
Fixture Generator: Generate balanced and exciting schedules for your league's upcoming season. This eliminates bias and ensures fair competition.
Technologies

Java: The robust and versatile programming language at the core of this system.
CUBA Platform: A powerful Java framework that streamlines development, providing essential features for web applications like:
User Interface Components
Data Access
Business Logic
Security
Administration Tools
MariaDB: A high-performance, open-source relational database management system for storing and managing your league's data.
Getting Started

Prerequisites:
Ensure you have Java Development Kit (JDK) 11 or later installed. You can download it from https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html.
Download and install the CUBA Platform Studio from https://www.jmix.io/cuba-platform/tools/.
Clone the Repository:
Bash
git clone https://github.com/your-username/soccer-management-system.git
Use code with caution.
Replace your-username with your actual GitHub username.
Import Project:
Open CUBA Platform Studio.
Go to File > Import > Project.
Select Existing Maven Projects and click Next.
Browse to the cloned project directory and click Finish.
Configure Database Connection (if necessary):
In the project view, expand the datasources node.
Right-click on [Default] and select Edit.
Update the connection details (hostname, port, username, password) to match your MariaDB instance.
Run the Application:
Right-click on your project in the project view and select Run > Run 'your-app-name'.
Replace your-app-name with the actual name of your application.
Customization

The system is designed to be adaptable. You can modify it to suit your specific league's needs, such as:

Adding new league statistics to the table
Tailoring the fixture generator algorithm
Implementing features like team management, player management, and more
Contribution

We welcome contributions from the community! Feel free to fork the repository, make changes, and submit pull requests for consideration.

License

This project is licensed under the MIT License. Refer to the LICENSE file for details.

Support

For any questions or assistance, feel free to create issues on the project's GitHub repository.
