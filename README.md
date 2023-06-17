# Node.js container env

## Introduction :open_book:

This is a minimal, secure and extensible dev container that you can use on your machine to develop node.js app.

## Why should you use dev containers for building node.js apps? :man_shrugging:

Reason you should use dev containers:

1. Coding environment stays the same for all the team members
2. Stop polluting local machine with installing and removing software with residuals still left. With this approach you can easily create and destroy fully fledged dev environment without polluting local machine with softwares.
3. Less time spent on debugging because of different dev env configurations.

......and many more

## How to use it? :thinking:

To get started with development, you need to follow these steps:

1. Create a repository from this template repository
2. The node.js version the dev container will use is 20.3, but if you want to use any other version of node.js modify this line with version you want. Please refer to [this](<https://edu.chainguard.dev/chainguard/chainguard-images/reference/node/overview/>) documentation for available versions.
3. Start the dev environment by running this command `sh setup-dev-env.sh`.
4. Attach your vscode to dev container named `nodejs-dev-env`.
5. Now start building amazing apps :rocket:

**NOTE - As mentioned this is a minimal dev env for node.js, so I highly recommend to customize the Dockerfile to include for e.g. tsconfig.json, eslint/prettier configs, etc for your usecase**

## Reference links

1. [Chainguard getting started with node.js](https://edu.chainguard.dev/chainguard/chainguard-images/reference/node/getting-started-node/)
2. [List of chainguard os packages for installation](https://github.com/wolfi-dev/os) for upadting the docker image to include certain packages.
