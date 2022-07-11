## vscode-js-console-utils-with-emoji

Fork from [vscode-js-console-utils](https://github.com/whtouche/vscode-js-console-utils)

![preview](https://i.imgur.com/0tiesd2.gif)

## Installing

This extension is available for free in the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=liaohui5.vscode-js-console-utils-with-emoji)

## Usage

With selection:

- Highlight a variable (or really any text)
- Press Cmd+Shift+L
- The output (on a new line) will be: console.log('variable: ', variable);

Without selection:

- Press Cmd+Shift+L
- The output (on the same line) will be: console.log();

To remove console.logs:

- Press Cmd+Shift+D
- This will delete all console.log statements in the current document

## Commands

| name                             | feature                         |
| :------------------------------- | :------------------------------ |
| extension.insertLogStatement     | Insert console.log in next line |
| extension.deleteAllLogStatements | Delete all console.log          |

extension.insertLogStatement

## License

[MIT License](LICENSE)
