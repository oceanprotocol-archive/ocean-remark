# OCEAN Protocol remark settings

This package contains settings for [remark](https://github.com/remarkjs/remark-lint).
In OCEAN, we use these settings to ensure good formatting and readability on markdown files.

You can use the instructions in this repository to run automatic formatting on any markdown file,
across other repositories using markdown.

## Installation

Clone this repository. In your console, run:

```console
npm install
```

To check your installation, this repository contains a test.md file so you can run the following:

```console
./node_modules/.bin/remark test.md
```

A set of warnings should appear when running remark on the `test.md` file.

## Usage

To show potential differences:

```console
./node_modules/.bin/remark path/to/file.md
```

To rewrite the file automatically:

```console
./node_modules/.bin/remark /path/to/file.md -o
```
