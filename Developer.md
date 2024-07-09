# Developer's guide

## Prepare
1. `sudo npm install -g grunt-cli@1.2.0 bower`
2. nvm install v22.4.1

## Build
1. `cd omega-build` 
2. `npm run deps`
3. `npm run dev`
4. `grunt`
5. `cd ..`
6. `cd omega-target-chromium-extension/build/`
7. `zip -r switchomega.zip .` 

## Install
1. copy switchomega.zip to host where you have the target browser, then unzip it
2. find "manage extension" buttion and enable "developer mode"
3. click "Load unpacked" button and select the unziped x folder