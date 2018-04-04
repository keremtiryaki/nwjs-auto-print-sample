
# nwjs-auto-print-sample

## Description
An auto print sample created with nwjs. 
It supports Windows XP 
(also nwjs supports osx and linux but not tested by us.)


## Overview
Starts the application silently (in the tray). The main window will be opened in 2 secs. 
Then it will try to find printers and It will print the textarea#payload element with the first printer automatically.

## Requirements
```
install Nodejs
install npm
npm install nw-builder -g
install brew (optional to build windows exe with macosx)
brew install wine (optional to build windows exe with macosx)
```

## To run on macos for development
```
Download nwjs sdk and extract main folder use 
npm run start
```

## To build for macos
```
npm run build
```

## To build for windows xp
```
npm run bw
```

