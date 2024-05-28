# GitHub Auto Commit Bot

This repository contains a simple Python script and GitHub Actions workflow to automate daily commits, keeping your GitHub contribution graph green and active.

## Features

- Daily Commits: Automates the process of making a commit to the repository every day.
- GitHub Actions: Uses GitHub Actions to schedule and run the commit script automatically.
- Easy Setup: Simply clone the repository, customize the script, and set up the workflow.

## Usage

#### Fork the Repository:

- Fork this repository: Click the 'Fork' button at the top right of this page to create your own copy of this repository.
- Clone the forked repository:

```bash
git clone https://github.com/yourusername/your-repository.git
cd your-repository
```

#### Set Up the Auto Commit Script

- Add the auto commit script. Modify the auto_commit.py script as needed.
- Set up GitHub Actions. Ensure the workflow file .github/workflows/auto_commit.yml is in place.

#### Commit and push changes:

```bash
git add .
git commit -m "Initial commit with auto commit script and workflow"
git push
```

## Script Details

- auto_commit.py: This script updates a file with the current timestamp and pushes the changes to GitHub.
- auto_commit.yml: The GitHub Actions workflow file that schedules the script to run daily.

## Contributions

Feel free to open issues or submit pull requests if you have any suggestions or improvements.

## Disclaimer

This project is for educational purposes only. It is designed to demonstrate how to use GitHub Actions for automation tasks. Using this bot to artificially inflate your contribution graph is discouraged and may violate GitHub's terms of service. Use responsibly and consider the ethical implications of automated commits.
