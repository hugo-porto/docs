# docs

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/2b44c015a10b4a7bb19951952d7f2a63)](https://app.codacy.com/gh/hugo-porto/docs/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)

This repository contains the documentation for the Hugo Porto project. It includes guides, tutorials, and other helpful
resources for users and contributors. The documentation is written in Markdown, a lightweight markup language that you
can learn in minutes. We strive to keep our documentation clear, concise, and up-to-date. Contributions are always
welcome! Please make sure to check out the 'Commands' and 'Tools' sections below to understand our workflow and tooling.

## Requirements

- [Hugo](https://gohugo.io/) - version 0.118.4 or higher
- [Go](https://golang.org/) - version 1.16 or higher
- [Node.js](https://nodejs.org/) - version 18.x or higher
- [npm](https://www.npmjs.com/) - version 8.x or higher

## Documentation

- [Getting started](getting_started.md)

## Tools

### markdownlint

We are using markdownlint to lint all markdown files in the project. You can install it using brew:

```shell
brew install markdownlint-cli
```

## Commands

### make lint

The `make lint` command is used to run linting tools on our codebase. This is helpful in identifying some common and
uncommon mistakes that are made during coding.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the terms of the MIT license. For more details, see the [LICENSE](LICENSE) file in the
project root.
