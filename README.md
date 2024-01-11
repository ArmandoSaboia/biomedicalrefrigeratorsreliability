## Software and Tools Requirements

Here's a guide to setting up all of the required software and tools:

1. [GithubAccount](https://github.com):
Follow the steps for creating a GitHub account and verifying your email.
2. [VsCodeIDE](https://code.visualstudio.com/download):
Download and install VS Code.
3. [GitCLI](https://git-scm.com/downloads): 
Download the installer for your operating system.
Run the installer and follow the instructions.
Verify installation:
Open a terminal or command prompt and type git --version. If Git is installed correctly, you'll see the version information.
4. [PostgreSQL](https://www.postgresql.org/download/):
Installation options:
Direct installation: Download and install PostgreSQL.
Package manager: Use a package manager like Homebrew (macOS) or apt (Ubuntu) to install PostgreSQL.
Docker: Use the official PostgreSQL Docker image (discussed later).
5. [Docker](https://www.docker.com/get-started):
Download and install:
Visit website and follow the instructions for your operating system.
Verify installation:
Open a terminal or command prompt and type docker --version. If Docker is installed correctly, you'll see the version information.
6. [Streamlit](https://streamlit.io/):
Installation:
Open a terminal or command prompt and type pip install streamlit.

Additional notes:

Setting up PostgreSQL Database: Once PostgreSQL is installed, you'll need to create a database and user for your application.
Using Docker for PostgreSQL: If you prefer to use Docker, you can pull and run the official PostgreSQL image: docker run -d -p 5432:5432 -e POSTGRES_PASSWORD=your_password postgres.
Integration with VS Code: VS Code has extensions for Git, Docker, and PostgreSQL that can enhance your workflow.
