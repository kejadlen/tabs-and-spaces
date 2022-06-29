# tabs-and-spaces

Tabs or spaces? Why not both?

```sh
git config --global filter.tabs-and-spaces.clean "prettier --config .prettierrc.canon.json --stdin-filepath index.js"
git config --global filter.tabs-and-spaces.smudge "prettier --stdin-filepath index.js"
```
