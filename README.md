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

Extract the contents of the tarball to the `fonts` directory.

```bash
tar -xvzf fonts.tar.gz ./fonts/
```

Add new fonts to the `fonts` directory.

Compress the contents of the `fonts` directory into a tarball.

```bash
tar -czvf fonts.tar.gz ./fonts/
```

| Fonts        |
| ------------ |
| ✓ Inter      |
| ✓ Manrope    |
| ✓ Montserrat |
| ✓ NotoSerif  |
| ✓ Nunito     |
| ✓ Poppins    |
| ✓ PT Sans    |
