# Work-Log-Summary
This repository automatically logs and summarizes my GitHub commits and pull requests every 30 minutes. It provides a convenient way to track my recent activity and see what I've worked on throughout the day.

## Features
**Automated Updates:** The repository is updated every 30 minutes with a summary of recent commits and pull requests.
**Summary Log:** Each update includes a summary of the commit messages and pull request titles.
**Easy Tracking:** Quickly review your recent activity without navigating through multiple repositories.

## How It Works
A GitHub Action workflow runs every 30 minutes to:

1. Fetch recent commits and pull requests from my GitHub profile.
2. Generate a summary of the activity.
3. Commit and push the summary to this repository.


## Setup
1. Clone this repository.
2. Configure the GitHub Action workflow to fetch your activity.
