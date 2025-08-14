# CI/CD Tools and Practices Final Project Template

This repository contains the template to be used for the Final Project for the Coursera course **CI/CD Tools and Practices**.

## Usage

This repository is to be used as a template to create your own repository in your own GitHub account. No need to Fork it as it has been set up as a Template. This will avoid confusion when making Pull Requests in the future.

From the GitHub **Code** page, press the green **Use this template** button to create your own repository from this template.

Name your repo: `ci-cd-final-project`.

## Setup

After entering the lab environment you will need to run the `setup.sh` script in the `./bin` folder to install the prerequisite software.

```bash
bash bin/setup.sh
```

Then you must exit the shell and start a new one for the Python virtual environment to be activated.

```bash
exit
```

## Tasks


## License

Licensed under the Apache License. See [LICENSE](/LICENSE)

## Author

Skills Network

## <h3 align="center"> © IBM Corporation 2023. All rights reserved. <h3/>

### Final project scenario

You’re part of a team responsible for building an innovative microservice, a RESTful API that allows users to manage and track counters. Another team has already developed the user interface (UI) for this microservice, and it's now your turn to ensure the reliability and efficiency of the backend services.

Continuous Integration (CI) with GitHub Actions
Your first task is to set up CI pipelines using GitHub Actions. The codebase comes with unit tests for the provided endpoints. Your goal is to automate the linting and testing processes. You will create a GitHub Actions workflow that triggers whenever changes are pushed to the repository.

Continuous Deployment (CD) with OpenShift Pipelines
In the second phase, establish CD pipelines within OpenShift Pipelines. These pipelines should include linting, testing, building an image, and the seamlessly deploying the microservice to an OpenShift cluster.

You need to provide the URL for your repository with the GitHub workflow and tekton yaml files in addition to other screenshots as evidence of your work. Your evidence will be essential for peer project evaluation. Best of luck with your project!


