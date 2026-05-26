# Development Environment Setup Guide

This guide walks through installing the required software for the course on both **Windows** and **MacOS**.

---

# Required Software

Students will need the following installed before beginning the class:

* Java 17+
* Apache Maven
* Visual Studio Code
* IntelliJ IDEA Community Edition

---

# Windows Setup

## 1. Install Java 17+

### Download Java

Download OpenJDK 17 (Temurin recommended):

* [https://adoptium.net/](https://adoptium.net/)

### Installation Steps

1. Select:

   * Operating System: **Windows**
   * Architecture: **x64**
   * Package Type: **JDK**
   * Version: **17 (LTS)**

2. Download and run the installer.

3. During installation:

   * Enable **Set JAVA_HOME variable**
   * Enable **Add to PATH**

### Verify Installation

Open Command Prompt:

```bash
java -version
```

You should see Java 17 or higher.

---

## 2. Install Maven

### Download Maven

* [https://maven.apache.org/download.cgi](https://maven.apache.org/download.cgi)

Download:

* **Binary zip archive**

### Install Maven

1. Extract the ZIP file to:

```text
C:\Program Files\Apache\maven
```

2. Add Maven to PATH:

Search:

* **Environment Variables**

Edit the `Path` variable and add:

```text
C:\Program Files\Apache\maven\bin
```

### Verify Installation

Open Command Prompt:

```bash
mvn -version
```

---

## 3. Install Visual Studio Code

Download:

* [https://code.visualstudio.com/](https://code.visualstudio.com/)

Install with default settings.

### Recommended VS Code Extensions

Install:

* Remote-SSH

---

## 4. Install IntelliJ IDEA Community Edition

Download:

* [https://www.jetbrains.com/idea/download/](https://www.jetbrains.com/idea/download/)

Select:

* **Community Edition**

Install with default settings.

### Recommended IntelliJ Plugins

Install:

* Lombok
* Maven
* Docker
* Alfresco SDK Support (optional)

---

# MacOS Setup

## 1. Install Java 17+

### Download Java

Download OpenJDK 17:

* [https://adoptium.net/](https://adoptium.net/)

Select:

* Operating System: **macOS**
* Architecture:

  * Apple Silicon: ARM64
  * Intel Mac: x64

Install the package.

### Verify Installation

Open Terminal:

```bash
java -version
```

---

## 2. Install Homebrew (Recommended)

Open Terminal:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Verify:

```bash
brew --version
```

---

## 3. Install Maven

Using Homebrew:

```bash
brew install maven
```

Verify:

```bash
mvn -version
```

---

## 4. Install Visual Studio Code

Download:

* [https://code.visualstudio.com/](https://code.visualstudio.com/)

Or install via Homebrew:

```bash
brew install --cask visual-studio-code
```

### Recommended VS Code Extensions

Install:

* Remote-SSH

---

## 5. Install IntelliJ IDEA Community Edition

Download:

* [https://www.jetbrains.com/idea/download/](https://www.jetbrains.com/idea/download/)

Or install via Homebrew:

```bash
brew install --cask intellij-idea-ce
```

### Recommended IntelliJ Plugins

Install:

* Lombok
* Maven
* Docker
* Alfresco SDK Support (optional)

---

# Verify Your Environment

Run the following commands in a terminal:

```bash
java -version
mvn -version
```

Both commands should complete successfully.

---

# Recommended System Requirements

* 16 GB RAM recommended
* 20+ GB free disk space
* Stable internet connection
* Administrator access to install software

---

# Optional Tools

Students may also benefit from installing:

* Docker Desktop
* Postman
* Git
* GitHub Desktop

---

# Useful Downloads

| Tool           | URL                                                                                                |
| -------------- | -------------------------------------------------------------------------------------------------- |
| Java (Temurin) | [https://adoptium.net/](https://adoptium.net/)                                                     |
| Maven          | [https://maven.apache.org/](https://maven.apache.org/)                                             |
| VS Code        | [https://code.visualstudio.com/](https://code.visualstudio.com/)                                   |
| IntelliJ IDEA  | [https://www.jetbrains.com/idea/download/](https://www.jetbrains.com/idea/download/)               |
| Docker Desktop | [https://www.docker.com/products/docker-desktop/](https://www.docker.com/products/docker-desktop/) |
| Git            | [https://git-scm.com/downloads/](https://git-scm.com/downloads/)                                   |

---
