# openssl-heroku

A Heroku buildpack for openssl that always downloads the latest static build.
Unlike other build packs, I never compile anything and remove this git.

## Usage
### This buildpack should be added before any Python install
Add the following to your `.buildpacks`:

```
https://github.com/amivin/openssl-heroku.git
```

Or run the following from the heroku command line:

```
heroku buildpacks:add https://github.com/amivin/openssl-heroku.git
```
