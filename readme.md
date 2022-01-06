# Generate Notes Action
This repo contains a github action that will retrieve release notes for you using [GitHub REST API](https://docs.github.com/en/rest/reference/releases#generate-release-notes-content-for-a-release)

## Usage
update `org-repo`, `previous_tag_name`, and `tag_name` files with desired parameters

## Setup
Add your github username and personal access token to action secrets named `GIT_USER` and `GIT_PAT` respevtively
