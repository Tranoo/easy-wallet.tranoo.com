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
