# havenls

[haven](https://github.com/anselic/haven)'s ~~language server~~ for the [Language Server Protocol](https://microsoft.github.io/language-server-protocol/).

Right now it is not a language server, but a syntax highlighter for haven. We plan to implement the language server inside haven, but haven is not ready for that yet.

## Installation

For VSCode or its forks:

```shell
$ cd editors/vscode
$ bun run package # or node, etc.
#  DONE  Packaged: <snip>/havenls/editors/vscode/haven-syntax-0.1.0.vsix (9 files, 4.15KB)
$ code --install-extension ./haven-syntax-0.1.0.vsix
```