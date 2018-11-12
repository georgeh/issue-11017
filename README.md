This is a test project for [WordPress/gutenberg#11017](https://github.com/WordPress/gutenberg/issues/11017)

# To test:

- `npm install`
- `./node-modules/.bin/webpack`
- Confirm that it does not error out

# To reproduce the issue:

- Edit `package.json` and change the version string to `"^6.0.1"`
- `npm update`
- `./node-modules/.bin/webpack`
- See the error about `Cannot find module '@wordpress/rich-text'`

