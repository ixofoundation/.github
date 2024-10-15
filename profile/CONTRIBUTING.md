# Contributing to the IXO Foundation

Thank you for your interest in contributing to the IXO Foundation!
We welcome contributions from the community to help build, improve, and refine the Internet of Impacts. Whether you’re fixing bugs, building features, improving documentation, or helping with testing, we’re excited to work with you!

This document provides guidelines for contributing to IXO projects and ensuring a smooth collaboration process.

Table of Contents

•	Getting Started
•	Code of Conduct
•	How to Contribute
•	Reporting Issues
•	Suggesting Features
•	Code Contributions
•	Code Style Guidelines
•	Submitting Pull Requests
•	Community & Support
•	License

## Getting Started

Before contributing, please take a moment to read through this guide. For any questions, feel free to join our Discord or Telegram community.

If you’re new to open-source contribution, we suggest checking out GitHub’s How to Contribute guide.

## Code of Conduct

We are committed to fostering an inclusive, respectful, and collaborative community. All contributors are expected to adhere to our Code of Conduct in all interactions, both in our repositories and other IXO community spaces.

## How to Contribute

We value all types of contributions, whether it’s reporting issues, suggesting new features, or submitting code. Here’s how you can get involved:

## Reporting Issues

Found a bug? Please help us track and fix it by opening an issue. When submitting an issue, please include:

•	A clear title and detailed description.
•	Steps to reproduce the bug or issue.
•	Any relevant screenshots or logs, if applicable.
•	What you expected to happen and what actually happened.

## Suggesting Features

Have an idea for a feature? We’re always open to hearing new ideas that align with IXO’s mission. When suggesting a feature:

•	Open a feature request issue and describe the feature clearly.
•	Explain the use case and how it benefits IXO or the developer community.
•	Optionally, suggest implementation details or examples.

## Code Contributions

We welcome code contributions! Whether it’s fixing a bug or adding a new feature, here’s how to get started:

1.	Fork the repository you want to contribute to.
2.	Clone your fork locally:

```bash
git clone https://github.com/your-username/repo-name.git
cd repo-name
```

3.	Create a new branch for your feature or bugfix:

```bash
git checkout -b feature-or-bugfix-name
```

4.	Write your code, adhering to our code style and guidelines.
5.	Test your changes locally to ensure they work as expected.
6.	Commit your changes and push the branch to your fork:

```bash
git add .
git commit -m "Add feature or fix bug description"
git push origin feature-or-bugfix-name
```

7.	Open a Pull Request (PR) to the main branch of the original repository. Make sure to reference the related issue (if any) and provide a clear description of your changes.

## Code Style Guidelines

To ensure consistency across the IXO codebase, please adhere to the following code style guidelines:

•	Follow the Prettier and ESLint rules for TypeScript and JavaScript.
•	Use TypeScript when working on frontend and SDK-related projects.
•	Use CosmWasm best practices for smart contract development.
•	Keep code modular and well-commented.
•	Write unit tests for any new functionality.

## Please run linters and tests before submitting your changes:

```bash
npm run lint
npm run test
```

## Submitting Pull Requests

To ensure smooth collaboration, please follow these guidelines when submitting a pull request (PR):

1.	Provide a clear description of your changes, what problem they solve, and how they were tested.
2.	Reference any related issues by mentioning the issue number in your PR description (e.g., “Fixes #123”).
3.	Include screenshots or logs where applicable.
4.	Ensure your code follows the established code style guidelines.
5.	Make sure all tests pass before submitting.
6.	Be responsive to any feedback from reviewers. If changes are requested, address them promptly.

After your PR is reviewed and approved, it will be merged by a maintainer.

## Community & Support

We are building a collaborative, inclusive community around IXO. Here’s how you can get involved and stay connected:

•	Discord: Join the discussion and ask questions on Discord.
•	Telegram: Follow updates and engage with the IXO community on Telegram.
•	Discussions: Participate in GitHub Discussions to share ideas, ask questions, and propose features.

## License

By contributing to IXO repositories, you agree that your contributions will be licensed under the Apache 2.0 License.

Thank you for helping us build the Internet of Impacts!
