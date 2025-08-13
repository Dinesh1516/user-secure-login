# User Secure Login - Authentication System

A secure user authentication web application built with Node.js and Express.js, featuring multiple levels of security implementation including password hashing, sessions, and OAuth integration.

## 🚀 Features

- **User Registration & Login**: Secure user account creation and authentication
- **Password Security**: Multiple authentication levels implemented
- **Session Management**: Secure user sessions with express-session
- **Responsive Design**: Clean and modern UI with Bootstrap styling
- **Secret Sharing**: Authenticated users can share and view secrets
- **Multiple Security Levels**: Progressive security implementation from basic to advanced

## 🛠️ Technologies Used

- **Backend**: Node.js, Express.js
- **Template Engine**: EJS (Embedded JavaScript)
- **Database**: MongoDB with Mongoose ODM
- **Authentication**: Passport.js with multiple strategies
- **Security**: bcrypt for password hashing, express-session
- **Styling**: Bootstrap CSS framework
- **Environment**: dotenv for environment variable management

## 📁 Project Structure

```
├── css/                    # Additional stylesheets
├── partials/              # Reusable EJS components
├── public/                # Static files (CSS, images, etc.)
├── views/                 # EJS template files
│   ├── partials/          # Header and footer components
│   ├── home.ejs          # Landing page
│   ├── login.ejs         # User login form
│   ├── register.ejs      # User registration form
│   ├── secrets.ejs       # Protected secrets page
│   └── submit.ejs        # Secret submission form
├── index.js              # Main application file
└── package.json          # Project dependencies
```

## 🔧 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Dinesh1516/user-secure-login.git
   cd user-secure-login
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Environment Setup**
   Create a `.env` file in the root directory:
   ```
   SESSION_SECRET=your-secret-key-here
   MONGODB_URI=your-mongodb-connection-string
   ```

4. **Run the application**
   ```bash
   npm start
   # or for development
   nodemon index.js
   ```

5. **Access the application**
   Open your browser and navigate to `http://localhost:3000`

## 🔐 Authentication Levels

This project demonstrates progressive security implementation:

1. **Level 1**: Basic username/password storage
2. **Level 2**: Database encryption
3. **Level 3**: Password hashing with bcrypt
4. **Level 4**: Session-based authentication
5. **Level 5**: OAuth integration (Google, Facebook)

## 🖥️ Usage

1. **Register**: Create a new account with email and password
2. **Login**: Sign in with your credentials
3. **Access Secrets**: View shared secrets from other users
4. **Submit Secrets**: Share your own anonymous secrets
5. **Logout**: Secure session termination

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Dinesh**
- GitHub: [@Dinesh1516](https://github.com/Dinesh1516)

## 🙏 Acknowledgments

- Built as part of web development learning journey
- Inspired by security best practices in web authentication
- Thanks to the open-source community for the amazing tools and libraries

---

⭐ **If you found this project helpful, please give it a star!** ⭐
