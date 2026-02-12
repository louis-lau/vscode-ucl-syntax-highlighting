# UCL Syntax Highlighting

Syntax highlighting and language configuration for UCL (Universal Configuration Language), commonly used by Rspamd.

## Features

- UCL-aware highlighting for comments, strings, heredocs, variables, macros, numbers, and literals.
- Language configuration for `#` line comments, `/* */` block comments, and common brackets.

## File Associations

- `.ucl`
- `.conf` (broad; if it conflicts with other configs, override via `files.associations`)

## Development

```bash
npm install
npm test
```

Grammar source lives in `syntaxes/ucl.tmLanguage.yml` and is generated to `syntaxes/ucl.tmLanguage.json` via:

```bash
npm run convert-grammar
```

## Known Limitations

- Nested block comments are not fully represented by TextMate grammars.
- Heredoc delimiters are matched as uppercase identifiers in the grammar.
