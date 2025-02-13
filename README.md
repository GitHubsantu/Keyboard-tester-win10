# Keyboard Tester

## Overview
Keyboard Tester is a Windows application designed to help users test the functionality of their keyboard. It visually displays the keys pressed and checks for any issues with key response. This project is lightweight, easy to use, and customizable.

## Features
- Real-time keypress visualization.
- Lightweight and fast.
- User-friendly interface.
- Portable application (no installation required).

## How I Made This Project (Step by Step)

### 1. **Setting Up the Environment**
   - Installed [Node.js](https://nodejs.org/) to manage the JavaScript environment.
   - Installed [Electron.js](https://www.electronjs.org/) to create the desktop application.

### 2. **Initializing the Project**
   - Created a new project folder.
   - Initialized the project with `npm init`:
     ```bash
     npm init -y
     ```

### 3. **Adding Dependencies**
   - Installed the necessary dependencies:
     ```bash
     npm install electron
     ```

### 4. **Creating the Application Files**
   - Added the following essential files:
     - `main.js`: The main Electron process.
     - `index.html`: The interface of the application.
     - `renderer.js`: Handles keypress detection.

### 5. **Configuring Electron**
   - Configured the `main.js` file to create the application window and load `index.html`.

### 6. **Building the Application**
   - Added a build script to `package.json`:
     ```json
     "scripts": {
       "start": "electron .",
       "build": "electron-packager . KeyboardTester --platform=win32 --arch=x64 --out=dist --overwrite"
     }
     ```
   - Built the application with:
     ```bash
     npm run build
     ```

### 7. **Packaging the Application**
   - Used [Electron Packager](https://github.com/electron/electron-packager) to create a distributable `.exe` file.

### 8. **Testing and Debugging**
   - Tested the application extensively on Windows.
   - Fixed bugs related to keypress detection and UI responsiveness.

### 9. **Adding the Final Touches**
   - Created icons for the application.
   - Packaged the final build into a `.zip` file.

## How You Can Make This Project
Follow the steps below to create your own version of the Keyboard Tester application:

### Prerequisites
1. Install [Node.js](https://nodejs.org/).
2. Install [Git](https://git-scm.com/).

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/GitHubsantu/Keyboard-tester-win10.git
   cd Keyboard-tester-win10
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the application in development mode:
   ```bash
   npm start
   ```

4. Build the application:
   ```bash
   npm run build
   ```
   The built `.exe` file will be located in the `dist/win-unpacked/` directory.

### Optional
- Customize the `index.html` and `renderer.js` files to add your own design or features.

## Download Link
You can download the latest version of the application here:
[Keyboard Tester Setup 1.0.0.exe](https://github.com/GitHubsantu/Keyboard-tester-win10/releases/download/v1.0.0/Keyboard.Tester.By.DevOps.Setup.v1.0.0.exe)

[Keyboard Tester Releases Details](https://github.com/GitHubsantu/Keyboard-tester-win10/releases)

## Contributing
If you'd like to contribute to this project, feel free to submit a pull request or open an issue on GitHub.

## License
This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).

---
**Created by DevOps**  
GitHub: [https://github.com/githubsantu](https://github.com/githubsantu)
