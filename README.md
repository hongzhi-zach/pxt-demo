# pxt-robsense
makecode based, code editor
stable version in case of encountering errors running normal version 


-. install global pxt
`npm i -global pxt`

-. install global build tools
`npm install --global --production windows-build-tools`

-. go to `pxt` folder and run:
`npm install gulp`
`npm run build`
`npm install`

-. go to each `pxt-common-packages` and `pxt-microbit` folder and run 
`npm install gulp`
`npm install`

-. go to `pxt-microbit` folder and run 
`npm link ../pxt`
`npm link ../pxt-common-packages`