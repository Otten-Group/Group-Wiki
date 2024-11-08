# Group-Wiki

Welcome to the **Otten Group Wiki!** This repository serves as a centralized resource for our lab’s projects, coding guidelines, documentation, and shared knowledge. This README will help you set up your environment, install required tools, and clone the repository to start contributing.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Setting Up Your Development Environment](#setting-up-your-development-environment)
  1. [Installing Git](#installing-git)
  2. [Installing Python](#installing-python)
  3. [Setting Up an IDE (PyCharm)](#setting-up-an-ide-pycharm)
- [Cloning the Repository](#cloning-the-repository)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [Contact Information](#contact-information)

## Prerequisites

To start working with our repositories, you’ll need to install Git, Python, and a code editor (we recommend PyCharm).

### Installing Git

Git is a version control tool we use for tracking changes in our code. Follow these steps to install it:

**For Windows:**
- Download the Git installer from [git-scm.com](https://git-scm.com).
- Run the installer, and follow the default setup steps.
- To verify the installation, open Command Prompt and type:
    ```bash
    git --version
    ```

**For macOS:**
- Open Terminal and run:
    ```bash
    brew install git
    ```

**For Linux:**
- Open your terminal and use your package manager (e.g., apt for Debian/Ubuntu) to install Git:
    ```bash
    sudo apt update
    sudo apt install git
    ```
- Confirm the installation:
    ```bash
    git --version
    ```

### Installing Python

We primarily use Python for coding in our projects. Install the latest version of Python (preferably 3.8 or higher):

1. Download Python from the [official website](https://www.python.org/downloads/).
2. Run the installer and make sure to check the option to Add Python to PATH.
3. Verify the installation by opening your terminal or command prompt and running:
    ```bash
    python --version
    ```

### Setting Up an IDE (PyCharm)

We recommend PyCharm as it provides an integrated environment suited for Python development.

- Download PyCharm Community Edition from [JetBrains](https://www.jetbrains.com/pycharm/download/).
- Install PyCharm and configure it with your Git and Python setup:
  - Open PyCharm and go to `Settings > Version Control` to connect Git.
  - Go to `Settings > Project Interpreter` to ensure Python is correctly linked.

## Cloning the Repository

Once Git is installed, you can clone this repository to your local machine:

- Open your terminal or command prompt.
- Navigate to the directory where you want to store the repository.
- Run the following command to clone the repository:
    ```bash
    git clone https://github.com/your-organization/group-wiki.git
    ```
- Navigate into the cloned directory:
    ```bash
    cd group-wiki
    ```

## Getting Started

Now that you have the repository cloned, you can open it in PyCharm or your preferred IDE and start exploring.

### Installing Required Packages

- If the project requires additional Python packages, they will typically be listed in a `requirements.txt` file.
- To install these packages, run:
    ```bash
    pip install -r requirements.txt
    ```

## Contributing

To contribute to this wiki, follow these steps:

1. Create a New Branch:
    ```bash
    git checkout -b your-feature-branch
    ```
2. Make Your Changes and Commit them with clear messages:
    ```bash
    git add .
    git commit -m "Add brief description of your changes"
    ```
3. Push your Branch to the repository:
    ```bash
    git push origin your-feature-branch
    ```
4. Create a Pull Request: Go to GitHub and open a pull request to merge your changes into the main branch.

## Contact Information

For any questions or help with setup, please contact Fionn Ferreira at fionn@fionnferreira.com.
