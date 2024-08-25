# 📧 React Newsletter Subscription with EmailJS

This project is a simple React application that allows users to subscribe to a newsletter by entering their email address. Upon subscribing, the user automatically receives a confirmation email in their inbox. The email-sending functionality is powered by [EmailJS](https://www.emailjs.com/), a service that enables sending emails directly from your client-side application.

## 🚀 Features

- **Email Subscription**: Users can subscribe to a newsletter by entering their email address in a form.
- **Automatic Confirmation Email**: Once a user subscribes, they receive an automatic confirmation email in their inbox.
- **Responsive Design**: The form is designed to be responsive and user-friendly across various devices.
- **Client-Side Email Sending**: Leveraging EmailJS, the email sending process is handled entirely on the client side, with no need for a backend server.

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/bhagirath1312/Newsletter-using-react-and-emailjs.git
   cd react-newsletter-emailjs/Newsletter

2. **Install dependencies**:
   ```bash
   npm install

3. **Setup EmailJS**:
   
  - Create an account at [EmailJS](https://www.emailjs.com).
  - Create a new email service and email template.
  - Obtain your Service ID, Template ID, and User ID from the EmailJS dashboard.
  - Update the EmailJS configuration in the sendConfirmationEmail function found in src/App.js:
    - Replace 'xxxxxxxx' with your Service ID.
    - Replace 'xxxxxxxx' with your Template ID.
    - Replace 'xxxxxxxx' with your User ID.

4. **Run the application**:
   
   Start the development server with:
   ```bash
   npm start
   ```
   Open your browser and navigate to http://localhost:3000 to view the application.

6. **Optional: Build for Production**:

   To create a production build of the application, run:
   ```bash
   npm run build
   ```
   This will generate a build directory with optimized production files.

## 📝 Usage
  1. Open the application in your browser.
  2. Enter an email address in the subscription form.
  3. Click the “Subscribe” button.
  4. A confirmation email will be sent to the provided email address.

## 💻 Technologies Used
  -	React: A JavaScript library for building user interfaces.
  -	EmailJS: A service for sending emails directly from client-side applications.

## 🤝 Contributing

  Contributions are welcome! If you find any issues or want to improve the project, feel free to open an issue or submit a pull request.

## 📧 Contact

  For any inquiries or support, please contact me at bhattibhagirath4618@gmail.com
