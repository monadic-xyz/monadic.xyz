# monadic.xyz homepage

## Set up

1. Clone repo
2. In your terminal cd to the project folder
3. Run `$ npm install`
4. Run `$ gulp`

## Build

1. Run `gulp build`
2. The 'docs' folder contains the build

## Deploy

The site is deployed with [GithubPages](https://pages.github.com/) from the
masters branch `docs/` directory. So a deploy invovles a `gulp build` and a push
to master afterwards, or based on a PR where the output files in `docs/` are
updated.
