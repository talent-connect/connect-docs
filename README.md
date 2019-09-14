# Environments, hosting, building and deployment

There are currently three environments:

* demonstration
* production
* development \(local\)

The build + deployment process for `redi-connect-front` and `redi-connect-admin` is the same. `redi-connect-backend` only has a deployment process.

## redi-connect-front and redi-connect-admin build and deployment

Both `front` and `admin` are configured via environment variables stored in `.env.<environment-name>` files. On running `yarn build` the variables are loaded via `env-cmd` . The setup was set up using this article: [https://dev.to/jam3/managing-env-variables-for-provisional-builds-h37](https://dev.to/jam3/managing-env-variables-for-provisional-builds-h37)



