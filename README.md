# InboxLink

This repository contains the source code for InboxLink, an email system application developed in C# using Windows Forms. The application allows users to compose and send emails, view their inbox, sent items, and manage their profile.

## Features

- Compose and send emails
- View inbox and sent items
- User authentication and signup
- Profile management

## Installation

### Database Setup

1. **Database Scripts**: The database scripts are included in the `database_scripts` directory. Use these scripts to set up the necessary database schema and tables.

2. **SQL Server**: Make sure you have Microsoft SQL Server installed on your machine.

3. **Run Scripts**: Open SQL Server Management Studio (SSMS) and connect to your SQL Server instance. Open each script file (`create_database.sql`, `create_tables.sql`) in SSMS and execute them to create the database and tables.

4. **Connection String**: Update the connection string in the C# code to match your SQL Server settings. You can find the connection string in the `compose.cs`, `landing.cs`, `login.cs`, and `signup.cs` files.

### Application Setup

1. Clone the repository to your local machine:


2. Open the solution file (`Email_System.sln`) in Visual Studio.

3. Build and run the project.

## Usage

1. **Sign Up**: If you're a new user, sign up for an account by providing your details such as name, email, username, and password.

2. **Log In**: Log in to your account using your username and password.

3. **Compose Email**: Click on the compose button to write a new email. Select the recipient from the dropdown list, enter the subject and body of the email, then click send.

4. **View Inbox**: Click on the inbox icon to view received emails.

5. **View Sent Items**: Click on the sent items icon to view emails you've sent.

6. **Manage Profile**: Click on the profile icon to manage your profile details.

## Dependencies

- .NET Framework
- Microsoft SQL Server

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

- Rahul R P(https://github.com/rprahul07)





