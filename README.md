# Java Codespace

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

A pre-configured GitHub Codespaces development environment for Java, featuring Java 17 with JavaFX support via the Zulu JDK and a VNC-enabled desktop for GUI application development.

## Overview

This repository provides a ready-to-use GitHub Codespaces dev container setup for Java development. It comes with Java 17 (Zulu FX build) pre-installed, VS Code Java extensions, and a lightweight desktop environment accessible through a web browser, making it ideal for developing and testing Java GUI applications in the cloud.

## Features

- Pre-configured Java 17 development environment with JavaFX support (Zulu FX)
- GitHub Codespaces-ready with one-click setup
- Integrated VNC desktop environment for GUI application testing
- VS Code Java Extension Pack pre-installed
- Dark theme and optimized editor settings out of the box
- GitHub Classroom extension support

## Prerequisites

- A [GitHub](https://github.com) account
- Access to [GitHub Codespaces](https://github.com/features/codespaces)

## Getting Started

### Installation

1. Click the green **Code** button on the repository page.
2. Select the **Codespaces** tab.
3. Click **Create codespace on main**.

The dev container will automatically build with Java 17 and all required tools.

### Usage

1. Once the Codespace is ready, create your Java files in the workspace.

2. Compile and run from the integrated terminal:
   ```bash
   javac MyApp.java
   java MyApp
   ```

3. For GUI applications, access the VNC desktop:
   - Open port **6080** in the browser (forwarded automatically).
   - The desktop environment allows you to see JavaFX and Swing application windows.

## Tech Stack

- **Language:** Java 17
- **JDK:** Zulu 17.0.4.1 with JavaFX
- **Container:** VS Code Dev Containers
- **Platform:** GitHub Codespaces
- **Desktop:** VNC via desktop-lite

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
