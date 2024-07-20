# Simple Translator App

This is a simple translator application built using Electron.js for the front end and Python Flask for the backend.

## Installation

### Prerequisites

- Node.js: Make sure you have Node.js installed. You can download it from [nodejs.org](https://nodejs.org/).

### Steps to Install

1. Clone the repository:
   - ```git clone https://github.com/your-username/translator-app.git```
   - ```cd translator-app```

2. Install dependencies:
   - ```npm install```

3. Install electron-builder: This is necessary for packaging the Electron application.
   - ```npm install --save-dev electron-builder```

4. Install Python Flask: Install Flask for the Python backend.
   - ```pip install Flask```

## Usage

### Running the Packaged Executable

1. Package the application: Once electron-builder is installed, run the following command to package your application into an executable:
   - ```npm run package```
   - This will create an executable file in the build directory, which you can run directly.

2. Run the executable: Navigate to the build directory and double-click on the executable to run the translator app.

### Running in Development Mode

If you prefer to run the application using your IDE or in development mode, simply use the following command:
   - ```npm start```
   - This will start the Electron application and you can see the app running in your default browser window.

## Features

- Translate text using Python Flask backend
- Simple and clean user interface
- Electron framework for cross-platform compatibility
