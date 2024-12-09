# Anvil Primer for Junior Programmers

Welcome to Anvil, the foundation for all open-source projects by Status26 Inc. This guide will help you get started with creating software solutions using the Anvil starter project.

## Coding Conventions

We follow Google's style guide for coding. Here’s why:
1. We use many Google products, so learning their conventions helps us understand our own.
2. It prepares us to contribute to Google's open-source projects.

For Python projects, refer to the [Google Style Guide for Python](https://google.github.io/styleguide/pyguide.html) for details on organizing, authoring, shipping, maintaining, and supporting your code.

## Configurations & Environments

Configurations are specific to each project, environment, and instance. In other words, every `.env` file has all the configuration variables needed to run the code in production, test, and instance environments. For security reasons, those files are never committed to the project but are instead maintained locally in the runtime environment.

## Documentation

We write most documentation in GitHub markdown and generate it with Hugo. Refer to the [GitHub Markdown Guide](https://guides.github.com/features/mastering-markdown/) and [Hugo Documentation](https://gohugo.io/documentation/) for more details.

## Testing

Every project includes sample data and tests to help you get started.

## Continuous Testing and Integration

When applicable, each project will include details on setting up a CI/CD workflow.

## TODO, Tasks, Shortcuts

Our code and documentation support syntax for TODO tasks and GitHub shortcodes to help you manage your work.

## Source of Truth

Any deviations from the mentioned guides will be specific to the project, environment, or instance. For example, this README file is specific to this project. Once the project is forked, the forked code becomes the primary source of truth for the new project. This ensures that the most relevant and accurate information is carried over and maintained across all environments.

Welcome aboard, and happy coding!