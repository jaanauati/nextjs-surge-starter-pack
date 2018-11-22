## NextJs - Surge Starter Kit.

A boilerplate for frontend development using [React.js](https://reactjs.org/), [Next.js](https://nextjs.org/) and [Surge](https://surge.sh/).

### Getting Started

 #### Clone the respository:
    $ git clone git@github.com:jaanauati/nextjs-surge-starter.git your-awesome-app
    $ cd your-awesome-app/
 
 #### Edit your application settings:
        * package.json: update application name, author and any other attributes you might want to.
        * SURGE_SUBDOMAIN: this file contains your surge subdomain, make sure u edit this and set the right one.
        * CNAME: your domain name (see https://surge.sh/help/adding-a-custom-domain).

 #### Install node v10.13.0, if you are an [nvm](https://github.com/creationix/nvm) user, just run the following:
    $ nvm install && nvm use

 #### Install dependencies and enter surge settings:
    $ npm install
    $ npx surge login # you must enter your surge settings here.

 #### Deploy your code to surge:
    $ npm run deploy

### Available Commands:
    * npm run dev: Executes next.js's development server (with live reload).
    * npm run build: Next.js build command.
    * npm run start: Next.js start cmd.
    * npm run export: Build and export your application to the dist directory.
    * npm run serve: Build and serve your project in your localhost. Useful to quickly check your app before deploying.
    * npm run deploy: Build, exports and deploy your app to surge.
    * npx surge ...: Execute surge commands.
    * npx next ...: Execute more/other next.js commands. 
    * 
### Links
   - React.js: https://reactjs.org/
   - Next.js: https://nextjs.org/
   - Surge: https://surge.sh/
   - nvm: https://github.com/creationix/nvm
