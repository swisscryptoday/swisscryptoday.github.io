# Swiss Crypto Day

A full day of cryptography talks in Switzerland.

## Local Development

This site uses [Devbox](https://www.jetify.com/devbox) to manage dependencies and provide a consistent development environment.

### Installing Devbox

Follow the installation instructions at: https://www.jetify.com/devbox/docs/installing_devbox/

Quick install (macOS/Linux):
```bash
curl -fsSL https://get.jetify.com/devbox | bash
```

### Running the Site Locally

Once Devbox is installed, start the Jekyll development server:

```bash
devbox run serve
```

The site will be available at `http://127.0.0.1:4000` with LiveReload enabled for automatic browser refresh on file changes.

### First Run

The first time you run `devbox run serve`, it will:
- Install Ruby and Bundler via Nix
- Install all gem dependencies via `bundle install`
- Build and serve the site

This may take a few minutes on the first run, but subsequent runs will be much faster.

## GitHub Pages

This site is automatically deployed to GitHub Pages when changes are merged to the master branch.
