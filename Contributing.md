# Steps to contribute

ss

## Note to myself

1. `npm init`
2. `npm i terminal-kit`
3. Must add shebang `#!/usr/bin/env node` to `index.js` to make it run as CLI.
4. Add `"bin": {"armangrewal007": "./index.js"}` to `package.json`
5. Make the script executable `chmod u+x index.js`
6. Symlink the binary to `/opt/homebrew/bin/armangrewal007` using --> `npm link`
