# ember-cli-phonegap-build
A basic ember-cli app trying to deploy in build.phonegap.com

Steps:
`ember new cool-app`

`cd cool-app`

`ember generate route first-route`

`ember generate route second-route`

Add some text to the corresponding templates.
Add some links to the application template so you can see the first and second page text.

`ember serve`

verified working in browser

`ember build --environment=production`

removed the `<base href="/">` tag from the `index.html file` in the dist folder.  Zipped the `dist` folder.  Added the `config.xml` file.  Uploaded to build.phonegap.com.  Ember never boots up.



