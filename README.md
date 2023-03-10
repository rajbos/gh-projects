# CLI extension for Projects

## Installation

Install `go version 1.19+`

```bash
brew install go
```

Install the CLI

```bash
brew install gh
```

Install this extension

```bash
gh extension install github/gh-projects
```

## Commands

For more information and a list of available commands

```bash
gh projects -h
```

## Access tokens
To use this plugin you need to use an Access Token that has at least the scope `read:org` for reading the projects at the organization level. When using a Personal Access Token, make sure to use a Clasic token, and NOT a new fine grained token (those do not have access to the GraphQL API that is used).

For adding issues or pull requests to a repo, you need to give the Access Token the following scope: `TODO`.

## Additional Resources

- [About Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)
- [About Extensions](https://docs.github.com/en/github-cli/github-cli/creating-github-cli-extensions)
- [Extensions Deep Dive](https://github.blog/2023-01-13-new-github-cli-extension-tools/)

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md)

## Issues

Please open issues at https://github.com/github/gh-projects/issues

## License

This project is licensed under the terms of the MIT open source license. Please refer to [MIT](./LICENSE) for the full terms.

## Maintainers

See [CODEOWNERS](./CODEOWNERS)

## Support

See [SUPPORT](./SUPPORT.md)
