# jez.io

My personal site, written in Markdown, compiled with Pandoc, and served over
GitHub Pages.

This is the source branch. For the compiled output, see `master`.

## Developing

These setup instructions are for developing on macOS.

First time setup:

```shell
# Install the build tools
brew bundle

# Set up the site/ folder
git clone -b master https://github.com/jez/jez.github.io ./site
```

Development commands:

```
# Build the site
make build

# Build if files change
make watch

# Preview the site on http://0.0.0.0:8000
make serve

# Deploy
make deploy
```

## License

MIT License. See LICENSE.
