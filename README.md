# Why3 for VS Code

Syntax highlighting and language configuration (comments, brackets, auto-closing pairs) for [Why3](https://www.why3.org/) files (`.mlw` and `.why`).

Install it from the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=qgarchery.why3-vscode) or [Open VSX](https://open-vsx.org/extension/qgarchery/why3-vscode).

## Features

- TextMate grammar for WhyML: keywords, specification clauses, definitions, quantifiers, types, strings and comments.
- Bracket matching, auto-closing pairs and `(* ... *)` block comments.

## Known issues

Highlighting of some declarations is imperfect; see `syntaxes/test/known-issues.mlw`.

## Publishing

Bump `version` in `package.json` and push.

Run the Publish workflow from the Actions tab.
It starts only through `workflow_dispatch` and publishes that version to the Marketplace.

Open VSX, from the repository root:

```
npx ovsx publish -p <token>
```

## License

MIT, see [LICENSE](LICENSE).
