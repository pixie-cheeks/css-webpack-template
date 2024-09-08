# CSS Only Webpack Template

Practically a fork of my webpack template for html-css only projects

## Important Traits

- Uses pnpm
- Uses stylelint with a BEM-compliant config
- Uses eslint with the airbnb-base config and a few personal modifications
- Almost all js files are in ES6 except for the `eslintrc.cjs`
- Tries to store config files in the `.config` subdir

## VSCode config

Removed all unnecessary options in favor of project-specific ones.
Moved it to a subdir in order to reduce clutter. Symlink it back to the root
if you need it:

```shell
ln -s .config/vscode .vscode
```
