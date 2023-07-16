    {
        vps
        https://www.gatsbyjs.com/docs/conceptual/data-fetching/ runtime client-side json fetching
        https://sometechblog.com/posts/deploying-gatsby-on-vps/
        /zroot/data/DK/EXAMPLES/GATSBY/*
        https://github.com/vercel/vercel/tree/main/examples/gatsby (like my myzone site)
    }

```
: nvm install --lts
Installing latest LTS version.
...
Now using node v18.16.1 (npm v9.5.1)
```
```
: npx gatsby new ewsite https://github.com/vercel/vercel/tree/main/examples/gatsby
Need to install the following packages:
  gatsby@5.11.0
Ok to proceed? (y) y
npm WARN ERESOLVE overriding peer dependency
npm WARN While resolving: react-server-dom-webpack@0.0.0-experimental-c8b778b7f-20220825
npm WARN Found: react@18.2.0
npm WARN node_modules/react
npm WARN   peer react@"^18.0.0 || ^0.0.0" from gatsby@5.11.0
npm WARN   node_modules/gatsby
npm WARN     gatsby@"5.11.0" from the root project
npm WARN     4 more (babel-plugin-remove-graphql-queries, ...)
npm WARN   5 more (react-dom, @gatsbyjs/reach-router, gatsby-link, ...)
npm WARN 
npm WARN Could not resolve dependency:
npm WARN peer react@"0.0.0-experimental-c8b778b7f-20220825" from react-server-dom-webpack@0.0.0-experimental-c8b778b7f-20220825
npm WARN node_modules/react-server-dom-webpack
npm WARN   react-server-dom-webpack@"0.0.0-experimental-c8b778b7f-20220825" from gatsby@5.11.0
npm WARN   node_modules/gatsby
npm WARN 
npm WARN Conflicting peer dependency: react@0.0.0-experimental-c8b778b7f-20220825
npm WARN node_modules/react
npm WARN   peer react@"0.0.0-experimental-c8b778b7f-20220825" from react-server-dom-webpack@0.0.0-experimental-c8b778b7f-20220825
npm WARN   node_modules/react-server-dom-webpack
npm WARN     react-server-dom-webpack@"0.0.0-experimental-c8b778b7f-20220825" from gatsby@5.11.0
npm WARN     node_modules/gatsby
npm WARN deprecated stable@0.1.8: Modern JS already guarantees Array#sort() is a stable sort, so this library is deprecated. See the compatibility table on MDN: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort#browser_compatibility
npm WARN deprecated string-similarity@1.2.2: Package no longer supported. Contact Support at https://www.npmjs.com/support for more info.
npm WARN deprecated babel-eslint@10.1.0: babel-eslint is now @babel/eslint-parser. This package will no longer receive updates.
╔════════════════════════════════════════════════════════════════════════╗
║                                                                        ║
║   Gatsby collects anonymous usage analytics                            ║
║   to help improve Gatsby for all users.                                ║
║                                                                        ║
║   If you'd like to opt-out, you can use `gatsby telemetry --disable`   ║
║   To learn more, checkout https://gatsby.dev/telemetry                 ║
║                                                                        ║
╚════════════════════════════════════════════════════════════════════════╝

 ERROR  UNKNOWN

starter https://github.com/vercel/vercel/tree/main/examples/gatsby doesn't exist



  Error: starter https://github.com/vercel/vercel/tree/main/examples/gatsby doesn't exist
  
  - init-starter.js:124 copy
    [6a76b9237e625090]/[gatsby-cli]/lib/init-starter.js:124:11
  
  - init-starter.js:287 initStarter
    [6a76b9237e625090]/[gatsby-cli]/lib/init-starter.js:287:5
  
  - create-cli.js:401 
    [6a76b9237e625090]/[gatsby-cli]/lib/create-cli.js:401:9
  


npm notice 
npm notice New minor version of npm available! 9.5.1 -> 9.8.0
npm notice Changelog: https://github.com/npm/cli/releases/tag/v9.8.0
npm notice Run npm install -g npm@9.8.0 to update!
npm notice 
```
```
: npm install -g npm@9.8.0
```
```
: npm init gatsby
Need to install the following packages:
  create-gatsby@3.11.0
Ok to proceed? (y) 
create-gatsby version 3.11.0



                                                                                                 Welcome to Gatsby!



This command will generate a new Gatsby site for you in /zsata/vcs/easy-wallet.tranoo.com with the setup you select. Let's answer some questions:


What would you like to call your site?
✔ · Easy Wallet by Tranoo.com
What would you like to name the folder where your site will be created?
✔ easy-wallet.tranoo.com/ ewsite
✔ Will you be using JavaScript or TypeScript?
· TypeScript
✔ Will you be using a CMS?
· No (or I'll add it later)
✔ Would you like to install a styling system?
· No (or I'll add it later)
✔ Would you like to install additional features with other plugins?
· Add the Google gtag script for e.g. Google Analytics
· Add responsive images
· Add an automatic sitemap
· Generate a manifest file
· Add Markdown support (without MDX)


Thanks! Here's what we'll now do:

    🛠  Create a new Gatsby site in the folder ewsite
    🔌 Install gatsby-plugin-google-gtag, gatsby-plugin-image, gatsby-plugin-sitemap, gatsby-plugin-manifest, gatsby-transformer-remark
  
✔ Shall we do this? (Y/n) · Yes
✔ Created site from template
✔ Installed Gatsby
✔ Installed plugins
✔ Created site in ewsite
🔌 Setting-up plugins...
info Adding gatsby-plugin-google-gtag
info Adding gatsby-plugin-image
info Adding gatsby-plugin-sitemap
info Adding gatsby-plugin-manifest
info Adding gatsby-transformer-remark
info Adding gatsby-plugin-sharp
info Adding gatsby-transformer-sharp
info Adding gatsby-source-filesystem
info Adding gatsby-source-filesystem
info Installed gatsby-plugin-google-gtag in gatsby-config
success Adding gatsby-plugin-google-gtag to gatsby-config - 0.254s
info Installed gatsby-plugin-image in gatsby-config
success Adding gatsby-plugin-image to gatsby-config - 0.237s
info Installed gatsby-plugin-sitemap in gatsby-config
success Adding gatsby-plugin-sitemap to gatsby-config - 0.243s
info Installed gatsby-plugin-manifest in gatsby-config
success Adding gatsby-plugin-manifest to gatsby-config - 0.267s
info Installed gatsby-transformer-remark in gatsby-config
success Adding gatsby-transformer-remark to gatsby-config - 0.276s
info Installed gatsby-plugin-sharp in gatsby-config
success Adding gatsby-plugin-sharp to gatsby-config - 0.287s
info Installed gatsby-transformer-sharp in gatsby-config
success Adding gatsby-transformer-sharp to gatsby-config - 0.294s
info Installed gatsby-source-filesystem in gatsby-config
success Adding gatsby-source-filesystem (images) to gatsby-config - 0.300s
info Installed gatsby-source-filesystem in gatsby-config
success Adding gatsby-source-filesystem (pages) to gatsby-config - 0.302s
🎉  Your new Gatsby site Easy Wallet by Tranoo.com has been successfully created
at /zsata/vcs/easy-wallet.tranoo.com/ewsite.
Start by going to the directory with

  cd ewsite

Start the local development server with

  npm run develop

See all commands at

  https://www.gatsbyjs.com/docs/reference/gatsby-cli/



:
```
