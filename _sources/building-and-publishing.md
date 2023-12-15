

To publish I've been following these instructions: https://jupyterbook.org/en/stable/publish/gh-pages.html


```bash
jupyterbook build .
ghp-import -n -p -f _build/html
```


as a prereq you have to have a github repo. after pushing you need to go to eh repo settings and set the pages branch to be `gh-pages`
