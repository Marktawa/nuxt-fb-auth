# Facebook Login Provider using Nuxt.js and Strapi

Basic Nuxt.js app that shows how to implement login with a Facebook login provider. Follow along on the **Learning Strapi Authentication Flows with the Facebook Provider** tutorial.

## Setup

**1 —** Clone this repository and install the dependencies
```shell
git clone git@github.com:Marktawa/nuxt-fb-auth.git
cd nuxt-fb-auth.git
yarn install
```

**2 —** Install a Strapi backend

In another folder, run these commands:
```shell
yarn create strapi-app my-project --quickstart
# or
npx create-strapi-app my-project --quickstart
```

**3 —** Create the Admin user: http://localhost:1337/admin/auth/register

**4 —** Configure your Facebook Login provider by following the instructions in the **Learning Strapi Authentication Flows with the Facebook Provider** tutorial.

**5 —** Launch the Nuxt.js app
```shell
yarn dev
```


