# [Backstage](https://backstage.io)

This is your newly scaffolded Backstage App, Good Luck!

To start the app, run:

```sh
yarn install
yarn dev
```

## Register Github OAuth Application
1. Go to Github Settings > Developer Settings > OAuth Apps > New OAuth Application
2. Set the following values:
   - Application name: (Your app name)
   - Homepage URL: http://localhost:3000
   - Authorization callback URL: http://localhost:7007/api/auth/github/handler/frame
3. Click "Register application"
4. Copy the Client ID and generate a Client Secret - you'll need these for configuration

