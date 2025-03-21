# Java-Basics

Welcome to the **Java-Basics** repository!  
This repository is created to help beginners understand and practice the fundamentals of Java programming.

## 🛠 Requirements

Before you begin, make sure you have **Java Development Kit (JDK) 24** installed on your machine.

### 📥 Download JDK 24

You can download JDK 24 from the official Oracle website:

🔗 [[Download JDK 24]([https://www.oracle.com/java/technologies/javase/jdk24-archive-downloads.html](https://download.oracle.com/java/24/latest/jdk-24_windows-x64_bin.exe))](https://download.oracle.com/java/24/latest/jdk-24_windows-x64_bin.exe)

> Follow the instructions based on your operating system (Windows, macOS, or Linux) and complete the installation.

**For Windows:**
1. Download the `.exe` installer.
2. Run the installer and follow the setup wizard.
3. During installation, check "Set JAVA_HOME environment variable".
4. After installation, restart your terminal or Command Prompt.

**For macOS:**
1. Download the `.dmg` installer.
2. Open the file and follow the installation instructions.
3. You may need to add the JDK path to your shell profile (e.g., `.zshrc` or `.bash_profile`).

**For Linux:**
1. Download the `.tar.gz` package.
2. Extract it and move it to `/usr/lib/jvm/` or a preferred location.
3. Set environment variables:
    ```bash
    export JAVA_HOME=/path/to/jdk-24
    export PATH=$JAVA_HOME/bin:$PATH
    ```
4. Add the above lines to `.bashrc`, `.zshrc`, or equivalent.

## ✅ Verify Installation

To verify if Java is successfully installed, open your terminal or command prompt and run:

```bash
java --version
