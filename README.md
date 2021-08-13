# TYPO3 CopyPaste detector Lint Github Action

This action checks the code of your TYPO3 extension with the [CopyPaste detector](https://github.com/sebastianbergmann/phpcpd) regarding duplicate lines of code. This helps to write better code and reduce the maintenance afford of your code.

## Inputs

### `Files`

Base folder(s) you want to check. Default `Classes Configuration Tests`.

## Example usage

```
uses: typo3-continuous-integration/typo3-ci-copy-paste-detector@v1
with: 
  files: 'Classes Configuration Tests'
```
