# heroku-buildpack-system-fonts

This buildpack makes it easy to install system fonts on Heroku [stacks](https://devcenter.heroku.com/articles/stack).

## Install

```bash
# Add the buildpack
heroku buildpacks:add --index 2 https://github.com/thatcleanlife/heroku-buildpack-system-fonts.git

#Deploy
git push heroku master
```

## Building

```bash
tar -czvf fonts.tar.gz ./fonts/
```

| Fonts   |
| ------- |
| ✓ Arial |