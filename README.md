# Github-Docker Actions Runner
This repository will create a Docker container for using with Github Actions.

### Getting Started
1. Clone this repo
2. Build docker image: `docker build --tag runner-image .`
3. Run the container with: ```docker run --detach --env ORGANIZATION=<YOUR-GITHUB-ORGANIZATION> --env ACCESS_TOKEN=<YOUR-GITHUB-ACCESS-TOKEN> --name runner runner-image```

### Organization and access token
1. ACCESS_TOKEN can be obtained [Tokens](https://github.com/settings/tokens) token MUST have `admin:org` and `manage_runners:enterprise` scope 
2. ORGANIZATION is the name of the org, ex: nestorperezdev
