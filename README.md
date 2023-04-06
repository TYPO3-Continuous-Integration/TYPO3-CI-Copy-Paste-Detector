# TYPO3 CopyPaste detector Lint Github Action

This action lints CopyPaste detector code of your TYPO3 extension.

NOTE: The CopyPaste detector got archived and is no longer maintained.
Therefore this action is also archived and no longer maintained.

## Inputs

### `Files`

Files you want to lint. Default `Classes Configuration Tests`.

## Example usage

```
uses: typo3-continuous-integration/typo3-ci-copy-paste-detector@v1
with: 
  files: 'Classes Configuration Tests'
```
