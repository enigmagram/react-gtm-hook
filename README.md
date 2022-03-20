# Publishing to github packages
```
yarn build
npm login --scope=@enigmagram --registry=https://npm.pkg.github.com
npm publish --scope=@enigmagram --registry=https://npm.pkg.github.com
```

Use github username

Use github personal access token as password
(profile -> settings -> developer settings -> personal access token)

Checkout ~/.npmrc
