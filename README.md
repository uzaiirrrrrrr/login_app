Android Login App (Java)

An Android application built in Java that provides a simple and modern authentication flow including Login, Signup, Forgot Password, Reset Password, and Main activity screens. This project demonstrates user navigation, validation, and activity interaction using clean and modular code.

🚀 Features

🧑‍💻 Login Activity – Allows users to sign in with validation checks (e.g., username: uzair, password: 123).

📝 Signup Activity – Lets new users register their account information.

🔁 Forgot Password Activity – Enables users to request a password reset.

🔒 Reset Password Activity – Allows users to securely create a new password.

🏠 Main Activity – Displays a welcome screen after successful login.

🧱 Project Structure
app/
 ├── java/
 │    └── com.example.loginapp/
 │          ├── LoginActivity.java
 │          ├── SignupActivity.java
 │          ├── ForgetPasswordActivity.java
 │          ├── ResetPasswordActivity.java
 │          └── MainActivity.java
 │
 └── res/
      ├── layout/
      │    ├── activity_login.xml
      │    ├── activity_signup.xml
      │    ├── activity_forget_password.xml
      │    ├── activity_reset_password.xml
      │    └── activity_main.xml
      └── values/
           └── colors.xml, strings.xml, styles.xml

🛠️ Technologies Used

Language: Java

IDE: Android Studio

Architecture: Activity-based navigation

UI Design: XML with modern and responsive layouts

⚙️ How to Run

Clone the repository:

git clone https://github.com/uzaiirrrrrrr/login_app


Open the project in Android Studio.

Sync Gradle and build the project.

Run the app on an emulator or physical Android device.

🔑 Default Login Credentials
Username	Password
uzair	123
📸 Screenshots (Optional)

Add screenshots of your Login, Signup, and Main screens here.

🤝 Contributing

Contributions are welcome!
If you’d like to improve the design, add database integration (e.g., Firebase), or enhance validation, feel free to fork the repo and submit a pull request.

📄 License

This project is licensed under the MIT License – feel free to use, modify, and distribute.
