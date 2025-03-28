# Hackanoho 2025

This repo is part of a workshop for the 2025 Hackanoho at UoA, designed to help students hack being a data scientist using Large Language Models (LLMs) and public datasets. We will see how we can use LLM integrations in a common IDE (integrated development environment) to "fake it until we make it"!

## Prerequisites

To participate in this workshop, you'll need to have the following:

1. **[VS Code](https://code.visualstudio.com/)** - Visual Studio Code is required for this workshop, as we'll be using its features and extensions extensively for LLM-powered data science workflows. Click on the link to download and install.

2. **[A Github Account](https://github.com)** - You'll need a Github account (hopefully created in a previous session) to access and work with this repository. 

3. **[Pixi](https://pixi.sh/latest/#get_started/)** - A package management tool that helps manage dependencies and virtual environments.
    Install instructions vary by OS (Linux, Mac, Windows); the key thing is that all are supported.

## Getting started

1. First, fork this repository to your own GitHub account:
   - Navigate to the main repository page
   - Click the "Fork" button in the top-right corner
   - Select your GitHub account as the destination

2. Open VS Code. Select the Extensions view icon on the sidebar (or press `Ctrl+Shift+X`).
   
3. Search for the `GitHub Pull Requests and Issues` extension and install it.
   
4. You'll be prompted to sign in to your GitHub account - do this when prompted.
   
5. Clone your forked repository (not the original) to your local machine:
   - Click on the `Clone Repository` button in the Source Control view (or press `Ctrl+Shift+P` and type `Git: Clone`)
   - Select your forked version of the repository from the list or paste its URL

6. Open the cloned repository in VS Code by clicking on the `Open Repository` button.
   
7. Return to the Extensions view and search for the `Github Copilot` extension. Install it. Also install the `Github Copilot Chat`, `Python` and `Jupyter` extensions. You will see the icons for these extensions in the sidebar.
   
8. Set up your Pixi environment by running `pixi install` in the terminal.
   
9. Run the command `pixi run start` in the terminal. This will start a Jupyter notebook server. You can access the server by clicking on the link that appears in the terminal. Take note of the URL and token that are displayed by the console output. Copy the URL to the clipboard.
   
10. Open `hackanoho.ipynb` in VS Code. Click on the `Open in Notebook Editor` button that appears at the top of the file. This will open the notebook in the Jupyter notebook editor. 

Once you have the notebook open, you can start running the cells, following the instructions, and asking Copilot for help when you need it. Have fun!
