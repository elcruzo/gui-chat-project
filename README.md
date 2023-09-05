# Python GUI Chat App

A Python-based Graphical User Interface (GUI) chat application using sockets and tkinter for both client and server sides.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributions](#contributions)
- [License](#license)

## Introduction

This Python GUI Chat App allows users to chat with each other in real-time. It consists of both client and server scripts, enabling multiple users to connect and communicate over a local network.

## Features

- Real-time chat between multiple users.
- User-friendly GUI built with tkinter.
- Server and client scripts included for easy setup.

## Requirements

To use this chat application, you need the following:

- Python 3.x
- The `tkinter` Library (usually included with Python Standard library)
- The `socket` Library (usually included with Python Standard library)
- The `threading` Library (usually included with Python Standard library)
- An active network connection
- Two or more computers or instances to act as clients

## Installation

1. Clone this repository or download the ZIP file and extract it to your preferred location on both the client and server computers.

   ```bash
   git clone https://github.com/elcruzo/gui-chat-project.git
   ```
2. Navigate to the project directory:

   ```bash
   cd gui-chat-project
   ```
3. Ensure you have Python 3.x installed. You can check by running:

   ```bash
   python3 --version
   ```

   If Python is not installed, you can download it from the official [Python website](https://www.python.org/downloads/).

## Usage

Server (server.py)

1. Open a terminal or command prompt on the computer you want to use as the server.
2. Navigate to the project directory where the `server.py` script is located.
3. Run the server script:

   ```bash
   python server.py
   ```
4. The server will start listening for incoming client connections on the specified IP address and port.

Client (client.py)

1. Open a terminal or command prompt on each client computer.
2. Navigate to the project directory where the `client.py` script is located.
3. Run the client script:

   ```bash
   python client.py
4. A GUI window will appear, prompting you to enter a nickname. Enter a unique nickname for each client.
5. Once a nickname is entered, you can start chatting with other connected clients.
6. To send a message, type it in the input area and click the "Send" button.
7. To exit the chat, simply close the GUI window.

## Contributions

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix.

3. Make your changes and commit them with descriptive commit messages.

4. Push your branch to your fork.

5. Create a pull request to the main repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Have fun exploring my User-friendly Chat App! If you have any questions or run into issues, don't hesitate to ask for help.
