# accounts-modular-deskto-app
Accounts-modular MERN webapp converted to desktop app using Electron Forge

Steps to convert MERN webapp to desktop app with Electron forge

1.  serve client side react app's production build folder statically from express.js
2   npm install --save-dev electron
3.  add "electron main.js" to start script in package.json (main.js being the file used to launch Electron app window and load the server file)
4.  npm install --save-dev @electron-forge/cli
5.  npx electron-forge import (it will alter package.json)
6.  add app icon to "packagerConfig" : {"icon" : "path/to/icon"}
7.  npm run package
8.  npm run make (if you want to create a distributable)
