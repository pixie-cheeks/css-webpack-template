# CSS Only Webpack Template

Practically a fork of my webpack template for html-css only projects

## Important Traits

- Uses pnpm
- Uses stylelint with a BEM-compliant config
- Tries to store config files in the `.config` subdir

## VSCode config

Removed all unnecessary options in favor of project-specific ones.
Moved it to a subdir in order to reduce clutter. Symlink it back to the root
if you need it:

```shell
ln -s .config/vscode .vscode
```
