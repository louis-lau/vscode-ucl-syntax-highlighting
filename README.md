# UCL Syntax Highlighting

Syntax highlighting and language configuration for UCL (Universal Configuration Language), commonly used by Rspamd.

## Download

[VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=louis-lau.ucl-syntax-highlighting)  
[Open VSX Registry](https://open-vsx.org/extension/louis-lau/ucl-syntax-highlighting)  
[Source Code](https://github.com/louis-lau/vscode-ucl-syntax-highlighting)  

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
