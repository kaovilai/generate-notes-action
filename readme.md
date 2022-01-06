# Generate Notes Action
This repo contains a github action that will retrieve release notes for you using [GitHub REST API](https://docs.github.com/en/rest/reference/releases#generate-release-notes-content-for-a-release)

## Usage
update previous_tag_name and tag_name parameters by updating values in the respective files.

## Setup
Add your github username and personal access token to action secrets to `GIT_USER` and `GIT_PAT` respevtively 
https://github.com/<your-username>/generate-notes-action/settings/secrets/actions