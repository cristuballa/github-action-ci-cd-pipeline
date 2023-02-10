# github-action-ci-cd-pipeline
![example event parameter](https://github.com/cristuballa/github-action-ci-cd-pipeline/.github/workflows/ci-cd.yml/badge.svg?event=push)

# GitHub Action Test Project (dotnet 7 & C#)

This project is a sample implementation of a .NET 7 application using C#, designed for testing purposes with GitHub Actions. The project showcases the use of GitHub Actions for continuous integration and testing.

## Prerequisites

- .NET 7 SDK
- A GitHub account

## Getting Started

1. Clone this repository to your local machine using `https://github.com/cristuballa/github-action-ci-cd-pipeline.git`
2. Navigate to the project directory using the command line
3. Run `dotnet restore` to install the required packages
4. Run `dotnet build` to build the project
5. Run `dotnet test` to execute the test cases

## GitHub Actions

This project contains a sample workflow file for GitHub Actions that runs the tests for the project on every push to the repository. The workflow file is located at `.github/workflows/ci-cd.yml`.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork this repository
2. Create a new branch for your changes (e.g. `git checkout -b my-new-feature`)
3. Commit your changes (e.g. `git commit -am 'Added a new feature'`)
4. Push to the branch (e.g. `git push origin my-new-feature`)
5. Create a new pull request

