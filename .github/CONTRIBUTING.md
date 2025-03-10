# Contributing to GeneralsSuperMaps

Thank you for your interest in contributing to this Generals/Zero Hour map repository! This document outlines the process
for contributing, using GitHub Desktop to simplify the workflow for all users, including those less familiar with GitHub.

## Getting Started: Easy Setup with GitHub Desktop

1. **GitHub Account:**
    - If you don't have one, create a GitHub account at [github.com](https://github.com). This is your online space for
    storing and sharing your code and map contributions.

2. **GitHub Desktop:**
    - Download and install GitHub Desktop from [desktop.github.com](https://desktop.github.com). This is a user-friendly
    application that lets you manage your contributions without needing to use command-line tools.

## Contribution Workflow: Step-by-Step Guide

1. **Fork the Repository: Making Your Own Copy**
    - Navigate to the repository on GitHub.
    - Click the "Fork" button in the top-right corner. Think of this as making a personal copy of the project to your
    own GitHub account.

2. **Clone Your Fork: Downloading to Your Computer**
    - Open GitHub Desktop.
    - Click "File" > "Clone repository."
    - Select your forked repository from the "GitHub.com" tab. This will be the copy you just made.
    - Choose a local directory (folder) on your computer to store the repository. This is where the map files will be
    downloaded.
    - Click "Clone." GitHub Desktop will now download all the files to your computer.

3. **Create a Branch: A Separate Workspace**
    - In GitHub Desktop, go to the "Current Branch" dropdown at the top.
    - Click "New Branch."
    - Give your branch a descriptive name (e.g., `feature/defcon-7`, `bugfix/terrain-chi01`). This keeps your changes
    separate from the main project until they are ready.
    - Click "Create Branch." You're now working in your own isolated workspace.

4. **Add or Modify Maps: Making Your Changes**
    - **Adding a New Map:**
        - Create a new folder inside the `maps/` directory with your map's name (e.g., `maps/Defcon 7/`).
        - Place the required files inside:
            - `.map` (the primary map file, created with World Builder)
            - `.tga` (map thumbnail, in `.tga` format)
            - `map.ini` (optional, for custom rules)
            - `map.str` (optional, for custom text strings)
            - Any other necessary files (readme, textures, etc.)
    - **Modifying an Existing Map:**
        - Navigate to the map's folder within `maps/`.
        - Edit the files using World Builder or a text editor.
    - After making changes, return to GitHub Desktop to see the modifications you've made.

5. **Commit Your Changes: Saving Your Work Locally**
    - In GitHub Desktop, review the modified files in the "Changes" tab. This shows you what you've altered.
    - Write a clear and concise commit message explaining your changes (e.g., "Added new map 'Defcon 7' with initial
    layout," "Fixed terrain issues in mission 'CHI01'"). Think of this as a note to yourself and others about what you did.
    - Click "Commit to [your-branch-name]." This saves your changes locally on your computer.

6. **Push Your Changes: Uploading to GitHub**
    - Click "Push origin" in the top-right corner of GitHub Desktop. This sends your locally saved changes to your
    forked repository on GitHub, making them visible online.

7. **Create a Pull Request (PR): Submitting Your Contribution**
    - In GitHub Desktop, click "View on GitHub." This opens your repository in your web browser.
    - Click the "Compare & pull request" button. This starts the process of submitting your changes to the main project.
    - Write a clear title and description for your PR, explaining the changes you made and why. Be detailed!
    - Click "Create pull request." The repository maintainers will review your PR and may request changes or merge it.

8. **Keep Your Fork Updated: Staying Synced**
    - Switch to the `main` branch in GitHub Desktop.
    - Click "Fetch origin" to check for updates from the original repository.
    - If updates are available, click "Pull origin" to download them.
    - Switch back to your working branch and merge the updates to avoid conflicts. This ensures your work is based on
    the latest version of the project.

## Best Practices: Making Your Contributions Shine

- **Small, Focused Commits:** Keep commits small and focused on a single logical change. This makes reviewing and
understanding your changes easier.
- **Clear Commit Messages:** Use descriptive commit messages. Explain what you did and why.
- **Test Your Maps:** Ensure your maps function correctly in the game before submitting a PR. Thorough testing is crucial.
- **Regularly Update Your Fork:** This helps prevent merge conflicts and keeps your work up-to-date.
- **Follow Existing Conventions:** Adhere to the existing file structure and naming conventions in the repository.
Consistency is key.
- **Map Compatibility:** Please try to ensure maps are compatible with the latest version of Generals/Zero Hour. If a
map is only compatible with a specific mod, please state this in the maps readme file.

## Questions and Support: We're Here to Help

If you have any questions or need assistance, please feel free to open an issue in the repository or join the
[Community Outpost Discord](https://www.community-outpost.com/discord).

Thank you for contributing to the Generals/Zero Hour community!
