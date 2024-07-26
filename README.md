## Login-Registration Backend

### Overview
This project provides a robust backend for handling user authentication and registration processes. It includes features such as email verification with expiry, secure password handling, and integration with PostgreSQL for data storage.

---

### 🚀 Features
- **User Registration**: Allows users to register with their email and password.
- **Email Verification**: Sends a verification email to users with an expiry time to confirm their email address.
- **Secure Authentication**: Implements Spring Security for secure login and password management.
- **Database Integration**: Uses PostgreSQL to store user data securely.
- **Java Mail**: Utilizes Java Mail API for sending verification emails.

---

### 🛠️ Technologies Used
- **Java**
- **Spring Boot**
- **Spring Security**
- **PostgreSQL**
- **Java Mail**

---

### 🔒 Security Considerations
- **Passwords** are securely hashed using BCrypt.
- **JWT tokens** are used for stateless authentication.
- **Email verification tokens** expire after 15 minutes.

---

### 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

---

### 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

---

### 🙏 Acknowledgements
- [Spring Boot Documentation](https://docs.spring.io/spring-boot/index.html)
- [PostgreSQL Documentation](https://www.postgresql.org/docs/)

