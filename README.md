Sure! Here's a detailed README for your project:

---

# Just Another Text Editor (J.A.T.E)

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Description

**Just Another Text Editor (J.A.T.E)** is a progressive web application (PWA) that allows users to write and store notes or code snippets with or without an internet connection. J.A.T.E is designed as a single-page application that meets the PWA criteria, offering features like offline functionality, data persistence, and installation as a native app on various devices.

This project was created to demonstrate the capabilities of modern web technologies, particularly the use of service workers, IndexedDB, and caching strategies to enable offline access and data management in a web application.

## Features

- **Offline Functionality**: Write and save notes even when there is no internet connection. Your changes will be saved locally and synced when you're back online.
- **Progressive Web App (PWA)**: Install the application on your device and use it like a native app.
- **Data Persistence with IndexedDB**: All notes are stored in IndexedDB, ensuring that your data is safe and can be accessed even when offline.
- **Service Workers**: Caching and serving assets for offline use.
- **Code Highlighting**: For easy code snippet management and syntax highlighting.

## Installation

To run the application locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/jate.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd jate
   ```

3. **Install dependencies:**

   ```bash
   npm install
   ```

4. **Build the application:**

   ```bash
   npm run build
   ```

5. **Start the development server:**

   ```bash
   npm run start
   ```

6. **Open the application:**

   Open your browser and go to `http://localhost:3000`.

## Usage

Once the application is running, you can start writing notes or code snippets in the text editor.

- **Saving Notes**: Your notes are automatically saved in the browser's IndexedDB.
- **Offline Mode**: You can access and edit your notes even when offline. The data will sync when you reconnect to the internet.
- **PWA Installation**: You can install the application on your device by clicking the "Install" button in the browser.

## Deployment

The application is deployed and can be accessed at [J.A.T.E Live](https://jate-sc3t.onrender.com/).

## Screenshots

<img width="1680" alt="Screenshot 2024-08-08 at 9 26 03 PM" src="https://github.com/user-attachments/assets/835b58dd-9e20-4a74-bdb3-1acafca30f30">

## Technologies Used

- **Frontend**:

  - HTML5
  - CSS3
  - JavaScript (ES6+)
  - Webpack
  - Babel

- **Backend**:

  - Node.js
  - Express.js

- **Database**:

  - IndexedDB (for client-side storage)

- **PWA**:
  - Service Workers
  - Web Manifest

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/yourusername/jate/issues) if you want to contribute.

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/yourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/yourFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

**William Hogan**

- **GitHub**: [b1llybagz](https://github.com/b1llybagz)
- **Website**: [b1llybagz.netlify.app](https://b1llybagz.netlify.app/)

Feel free to reach out if you have any questions or feedback!

---
