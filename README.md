# My Web App

This is a React-based web application that implements a functional login system, a Onebox screen with keyboard shortcuts, a custom text editor, and light/dark mode. The app also allows users to reply to messages with a custom email body.

## Table of Contents
- [Getting Started](#getting-started)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Keyboard Shortcuts](#keyboard-shortcuts)
- [Customization](#customization)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

Follow the instructions below to set up and run the project on your local machine.

### Features
- **Login Page**: Users can log in using their credentials.
- **Onebox Screen**: Displays a list of threads fetched from the backend, with keyboard shortcuts for quick actions.
- **Custom Text Editor**: A rich text editor with custom buttons such as "SAVE" and "Variables."
- **Reply Functionality**: Users can reply to a thread with a custom email body in HTML format.
- **Light/Dark Mode**: Toggle between light and dark themes.

## Project Structure


## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/my-app.git
    cd my-app
    ```

2. **Install dependencies:**

    Make sure you have Node.js and npm installed on your machine. Then, run:

    ```bash
    npm install
    ```

3. **Start the development server:**

    ```bash
    npm start
    ```

    This will run the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Usage

- **Login**: Access the login page and enter your credentials to log in.
- **Onebox**: After logging in, you will be redirected to the Onebox screen where you can view and manage threads.
- **Editor**: Navigate to the custom text editor to create and manage your content.
- **Reply**: Use the reply box to send replies to threads with custom HTML bodies.
- **Theme**: Toggle between light and dark modes using the theme switcher.

## Keyboard Shortcuts

- **D**: Delete the selected thread.
- **R**: Open the reply box for the selected thread.

## Customization

- **Text Editor**: The custom buttons in the text editor can be modified in the `TextEditor.js` component.
- **Theme Colors**: Adjust the light and dark mode colors in `App.css`.

## Technologies Used

- **React**: For building the user interface.
- **Axios**: For making HTTP requests to the backend API.
- **Draft.js**: For the custom rich text editor.
- **CSS**: For styling and theme management.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-branch`.
5. Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
