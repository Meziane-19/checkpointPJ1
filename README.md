# Git Workflow & Automation Checkpoint

This repository demonstrates a foundational mastery of Git version control, branching strategies, and workflow automation.

## Key Features Demonstrated:
* Branching Strategy: Managed parallel development using feature branches (`note-alice` and `note-bob`).
* Conflict Resolution: Manually resolved merge conflicts to maintain code integrity.
* Git Hooks: Implemented a custom pre-commit shell script to enforce data quality (preventing empty titles in markdown files).
* Remote Management: Synchronized local development with GitHub using secure authentication and remote tracking.

## How the Pre-Commit Hook Works:
The hook automatically triggers before every commit. It scans the notes/ directory to ensure no .md file has an empty first line. If a file is empty, the commit is blocked with an error message.

## Technologies Used:
* Git / GitHub
* Linux CLI (Bash)
* Kali Linux
