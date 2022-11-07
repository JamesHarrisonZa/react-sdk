# Contributing to the A/B Smartly JavaScript SDK

The A/B Smartly JavaScript SDK is an open source project and we welcome your feedback and contributions.
The information below describes how to build and test the project, and how to submit a pull request.

## Development

### Development process

1. Fork the repository and create a topic branch from `main` branch. Please use a descriptive name for your branch.
2. While developing, use descriptive messages in your commits. Avoid short or meaningless sentences like: "fix bug".
3. Make sure to add tests for both positive and negative cases.
4. Run the linter script of the project and fix any issues you find.
5. Run the build script and make sure it runs with no errors.
6. Run all tests and make sure there are no failures.
7. `git push` your changes to GitHub within your topic branch.
8. Open a Pull Request from your forked repo and into the `main` branch of the original repository.
9. When creating your PR, please fill out all the fields of the PR template, as applicable, for the project.
10. Check for conflicts once the pull request is created to make sure your PR can be merged cleanly into `main`.
11. Keep an eye out for any feedback or comments from A/B Smartly's SDK team.

### Building the SDK

For widespread use of the SDK with different environments and module formats, we have these different builds:

- An ESM build
- A **CommonJS** modules compatible build.

The different builds can be generated all at once with the command `npm run build`. Refer to [package.json](package.json) for more insight on the build scripts.

### Running tests

The project includes unit tests for both browser and Node.js environments.

All tests can be run at once with the command `npm run test`.

For additional testing scripts or to get more insight on how these work, please refer to our [package.json](package.json) file.

# Contact

If you have any other questions or need to contact us directly we can be reached at sdk@absmartly.com
