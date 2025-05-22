# Digitaltack github-actions

This repository aims to store custom GitHub Actions that facilitate and optimize workflows. Here, you will find a collection of reusable actions that you can easily integrate into your own GitHub workflows.

## What are GitHub Actions?
GitHub Actions is a feature of GitHub that allows you to automate, customize, and execute workflows directly in your repository. With actions, you can set up processes that are triggered by events in your repository, such as pushes, pull requests, and more.

## How to Use the Actions
To use one of our actions in your workflow, simply add the following line to your .github/workflows/your-workflow.yml file:

- name: Action Name
  uses: digitaltack/github-actions/some-action@v1 (tag, branch name, sha ref)
  with:
    - optional parameters

## Contributing
We welcome contributions! If you have an action you'd like to share or improvements to suggest, please open an issue or submit a pull request.