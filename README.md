# [Backstage](https://backstage.io)

This is your newly scaffolded Backstage App, Good Luck!

To start the app, run:

```sh
yarn install
yarn start
```

The frontend uses a `SignInPageBlueprint` extension registered through an app
module in `packages/app/src/App.tsx` to display GitHub sign-in instead of the
default Guest page. The GitHub backend provider and catalog user identity must
also be configured for sign-in to succeed.
