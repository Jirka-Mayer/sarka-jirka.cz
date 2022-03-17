## Development

The project is built using [Parcel](https://parceljs.org/) and for that you need to have node.js installed. The easiest option is to install node via nvm (node version manager).

Here you can install nvm: https://github.com/nvm-sh/nvm#installing-and-updating

Then you can install nodejs:

    nvm install v17.7.1

Lastly, you have to install all required packages, including parcel (after pulling this repository):

    npm install

Now to start developing, simply run:

    npm run dev

You can view the developed website at http://localhost:1234

When you are ready to deploy, you build the website into the `public` folder by running:

    npm run build

The website becomes live the moment it gets pushed to github.
