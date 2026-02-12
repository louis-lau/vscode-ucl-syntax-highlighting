# UCL Syntax Highlighting

Syntax highlighting and language configuration for UCL (Universal Configuration Language), commonly used by Rspamd.

## File Associations

- `.ucl`
- `.conf`
- `.ucl.conf`

## Development

```bash
npm install
npm test
```

Grammar source lives in `syntaxes/ucl.tmLanguage.yml` and is generated to `syntaxes/ucl.tmLanguage.json` via:

```bash
npm run convert-grammar
```
