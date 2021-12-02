# Apple Music web app using electron.js

I'm using this to be able to select a proper app for audio routing using Voicemeeter. Anyways, this is more lightweight that the actual iTunes app on Windows.

Tested on Windows 11.

## How to compile

> I'm assuming you have Node.js already installed. I suggest to use the latest LTS version available.
> {.is-warning}

1. Download/Clone this
1. Initialize with npm
    1. `npm init`
    2. Make sure you have electron installed using `npm install --save-dev electron`
    3. Check if your app is running with `npm start`
1. Make any changes as you want
1. Prep for compile
    1. Add electron forge `npm install --save-dev @electron-forge/cli`
    1. Run `npx electron-forge import`
1. Compile
    1. Just run `npm run make`

Enjoy!
