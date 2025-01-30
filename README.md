# Flutter News App 2.0

## Introduction

Welcome to the **Flutter News App**, a powerful and efficient way to stay updated with the latest news from around the world. This app is designed to provide users with a seamless news reading experience, offering a wide range of features to enhance user engagement and satisfaction.

### Key Features:

- **Real-Time Updates**: Stay informed with the latest news as it happens, thanks to our real-time news feed.
- **Categorized News**: Easily navigate through different categories such as Politics, Sports, Technology, Entertainment, and more.
- **User-Friendly Interface**: Enjoy a clean and intuitive interface that makes reading news enjoyable and hassle-free.
- **Customizable Notifications**: Receive notifications for the categories you care about the most.

---

## Installation

Follow these steps to set up and run the project:

### Prerequisites

Ensure you have the following tools and versions installed:

- **Java JDK version**: 17
- **Android Studio**: Latest version
- **Xcode**: Latest version (for macOS users)
- **Dart version**: 3.5.4
- **Flutter SDK version**: 3.24.5

---

## Java JDK 17 Installation Guide

### Windows

1. **Download JDK 17**:  
   Visit the official Oracle download page to download JDK 17:  
   [Oracle JDK 17 Downloads](https://www.oracle.com/java/technologies/javase-jdk17-downloads.html)

2. **Install JDK 17**:

   - Run the downloaded installer.
   - Follow the on-screen instructions to complete the installation.

3. **Set up Environment Variables**:

   - Open the **Start Menu**, search for "Environment Variables," and click on **Edit the system environment variables**.
   - In the **System Properties** window, click **Environment Variables**.
   - Under "System variables," click **New** and add:
     - **Variable Name**: `JAVA_HOME`
     - **Variable Value**: Path to the JDK installation directory (e.g., `C:\Program Files\Java\jdk-17`).
   - Locate the **Path** variable, click **Edit**, and add `%JAVA_HOME%\bin`.
   - Click **OK** to save the changes.

4. **Verify Installation**:
   - Open a new Command Prompt and type:
     ```bash
     java -version
     ```
   - You should see the installed JDK version (e.g., `java version "17.x.x"`).

---

### macOS

1. **Download JDK 17**:  
   Visit the official Oracle download page to download JDK 17:  
   [Oracle JDK 17 Downloads](https://www.oracle.com/java/technologies/javase-jdk17-downloads.html)

2. **Install JDK 17**:

   - Open the downloaded `.dmg` file and follow the instructions to install JDK 17.

3. **Set up JDK Path**:

   - Open a terminal and run the following commands:
     ```bash
     export JAVA_HOME=$(/usr/libexec/java_home -v 17)
     export PATH=$JAVA_HOME/bin:$PATH
     source ~/.zshrc
     ```
   - If you're using **Bash**, replace `~/.zshrc` with `~/.bash_profile` in the third command.

4. **Configure Flutter**:
   Run the following command to configure Flutter to use JDK 17:

   ```bash
   flutter config --jdk-dir "/Library/Java/JavaVirtualMachines/jdk-17.jdk/Contents/Home"
   ```

5. **Verify Installation**:
   - Open a terminal and type:
     ```bash
     java -version
     ```
   - You should see the installed JDK version (e.g., `java version "17.x.x"`).

---

## Setup Instructions

### Step 1: Clean the Project

Run the following command to clean the project:

```bash
flutter clean
```

### Step 2: Get Dependencies

Run the following command to fetch the dependencies:

```bash
flutter pub get
```

### Step 3: Run the Project

Run the following command to start the project with a specific flavor:

```bash
flutter run --flavor [channel-name]
```

---

## About the Author

**Flutter News App** is developed by **Gray Television**. The user interface is designed to provide a seamless and efficient user experience.

---

## Announcement

This project is currently under development.
