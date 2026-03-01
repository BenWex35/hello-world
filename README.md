# hello-world
This repository is for practicing the github flow
Hello, My name is Benjamin. This is my practice for Github

## How to Clone This Repo and Work in VSCode (Week-06)

Follow these steps to clone the repository to your laptop and open it in VSCode:

### Prerequisites
- Install [Git](https://git-scm.com/downloads) on your laptop
- Install [Visual Studio Code](https://code.visualstudio.com/)

### Steps

1. **Copy the repository URL**
   - Go to this repository on GitHub: `https://github.com/BenWex35/hello-world`
   - Click the green **Code** button
   - Copy the HTTPS URL (e.g. `https://github.com/BenWex35/hello-world.git`)

2. **Open a terminal** (Command Prompt, PowerShell, or Git Bash on Windows; Terminal on Mac/Linux)

3. **Clone the repository**
   ```bash
   git clone https://github.com/BenWex35/hello-world.git
   ```

4. **Navigate into the project folder**
   ```bash
   cd hello-world
   ```

5. **Open the folder in VSCode**
   ```bash
   code .
   ```
   > If `code .` doesn't work, open VSCode manually and go to **File → Open Folder**, then select the `hello-world` folder.

6. **You're ready to work!**
   - Make your changes in VSCode
   - Use the built-in terminal in VSCode (**Terminal → New Terminal**) to run git commands
   - Stage, commit, and push your changes back to GitHub:
     ```bash
     git add .
     git commit -m "Your commit message"
     git push
     ```
