# Discussion #: 35229


## Current behavior

This project specifies `^3.5.7` of `vue`. It opens a PR suggesting an update to `3.5.13`. Furthermore, observe how this PR contains only changes to the `yarn.lock` and zero-install cache files,  and not `package.json`.

## Expected behavior

I would expect no PR to be opened. This is because `3.5.13` is within range of `^3.5.7`.

## Link to the Renovate issue or Discussion

[Put your link to the Renovate issue or Discussion here.](https://github.com/renovatebot/renovate/discussions/35229)
