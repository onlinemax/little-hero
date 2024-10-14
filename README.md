

# How to Contribute to the Little Hero Project on GitHub

## Introduction
This guide will teach you how to contribute to the Little Hero project. It covers everything from bringing the code to your local computer (your own machine) to sending your changes back to the main project. You’ll be making something called a "pull request" to suggest your changes for review.

### What You'll Need:
- A GitHub account (sign up at [GitHub](https://github.com) if you don’t have one).
- [Visual Studio Code (VSCode)](https://code.visualstudio.com/), a tool to edit the code.
- [Git](https://git-scm.com/) installed on your computer.

---

## Step-by-Step Guide

### Step 1: Fork the Repository
First, you need to create your own copy of the Little Hero project.

1. **Go to the repository**: [Little Hero GitHub](https://github.com/onlinemax/little-hero).
2. **Click the "Fork" button** in the upper-right corner. This will create a copy of the project under your own GitHub account.

### Step 2: Clone the Repository (Initial Setup)
You’ll clone the project to your local computer only once.

1. **Open Visual Studio Code (VSCode)**.
2. **Open the Terminal in VSCode**:
   - Click on **View > Terminal** from the top menu, or press `Ctrl + ` (backtick) on your keyboard.
3. **Copy the link to your fork**:
   - On your GitHub fork page (which should be `https://github.com/YourUsername/little-hero`), click the green **"Code"** button and copy the link under **HTTPS**.
4. **Clone the repository to your local machine** by typing this command in the terminal (replacing `YourUsername` with your GitHub username):
   ```bash
   git clone https://github.com/YourUsername/little-hero.git
   ```
5. Press **Enter**. This will download the project files to your computer.

### Step 3: Pull the Latest Changes (Subsequent Updates)
After the initial setup, you can easily update your local copy with changes from the remote repository using `git pull`.

1. **Navigate to Your Local Repository**:
   - In the terminal, use the `cd` command to change your directory:
   ```bash
   cd path/to/your/little-hero
   ```
   - Replace `path/to/your/little-hero` with the actual path to your local repository.

2. **Pull the Latest Changes**:
   - Run the following command to fetch and merge changes from the remote `main` branch:
   ```bash
   git pull origin main
   ```

3. **Handling Conflicts**:
   - If there are any conflicts, Git will notify you. You'll need to resolve them manually, add the resolved files, and commit again.

### Step 4: Make Changes to the Code
Now that the project is on your computer, you can edit the code.

1. **Open the project in VSCode**:
   - In VSCode, click **File > Open Folder**, then navigate to the `little-hero` folder and click **Open**.
   
2. **Edit the code**:
   - Browse through the files and make your changes. If you're unsure where to start, follow the instructions in the project's README or ask the project maintainers for guidance.

### Step 5: Commit Your Changes
After making changes, you need to "commit" them (which means saving the changes with a message explaining what you did).

1. **Open the Terminal in VSCode** if it's not already open.
2. **Add your changes** by typing:
   ```bash
   git add .
   ```
   This tells Git to track the changes you made.

3. **Commit your changes** with a message describing what you did:
   ```bash
   git commit -m "Brief description of changes"
   ```
   Example: 
   ```bash
   git commit -m "Fixed the hero's attack function"
   ```

### Step 6: Push Your Changes to GitHub
Now, you'll send your changes to your GitHub fork (the online copy you made earlier).

1. **Push your changes** by typing:
   ```bash
   git push origin main
   ```

### Step 7: Create a Pull Request
A pull request (PR) is how you ask the project maintainers to look at your changes and potentially include them in the main project.

1. **Go to your fork on GitHub** (e.g., `https://github.com/YourUsername/little-hero`).
2. **Click the "Pull Request" button** near the top of the page.
3. **Compare changes**: GitHub will automatically show the differences between your code and the main project.
4. **Create the pull request**:
   - Add a **title** and **description** of the changes you made.
   - Click **"Create Pull Request"**.

Now, the project maintainers will review your changes, and if everything looks good, they’ll merge your work into the main project!

---

## Common Commands Recap
Here’s a quick reference for the commands you’ll use most often:

- **Clone a repository** (initial setup):
  ```bash
  git clone https://github.com/YourUsername/little-hero.git
  ```

- **Navigate to your repository**:
  ```bash
  cd path/to/your/little-hero
  ```

- **Pull the latest changes** (subsequent updates):
  ```bash
  git pull origin main
  ```

- **Add changes**:
  ```bash
  git add .
  ```

- **Commit changes**:
  ```bash
  git commit -m "Your message here"
  ```

- **Push changes**:
  ```bash
  git push origin main
  ```

---

## Need Help?
Don’t hesitate to ask questions if you get stuck. GitHub has an active community, and the maintainers of the Little Hero project will be happy to assist you!

Happy coding! 😊💻

