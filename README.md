# Simple-Shell-Script

# GitHub Repository Read Access List Script

This repository contains a shell script that lists users with read access (pull permission) to a specified GitHub repository. The script interacts with the GitHub API.

## Features

- Fetches collaborators from a specified GitHub repository
- Filters and lists users with read (pull) access

## Requirements

- `curl`: Command-line tool for making HTTP requests
- `jq`: Command-line JSON processor

## Setup

1. **Clone the repository** :

   
   git clone https://github.com/shpy07/Simple-Shell-Script.git

   cd Simple-Shell-Script

3. **Make the script executable** :

   
    chmod +x list-users.sh
  
4. **Install dependencies (if jq is not already installed)** :

   
    sudo apt update
    sudo apt install jq -y
  
5. **Usage** :

   
    Run the script with the repository owner and repository name as arguments:
   
    ./list-users.sh <repo_owner> <repo_name>

