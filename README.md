# gadget-hello-world
A "Hello World" contextual gmail gadget based on https://developers.google.com/gmail/contextual_gadgets

Hosted on github pages at: http://sbrudz.github.io/gadget-hello-world/

## Steps to Publish

Here are the steps I followed to get this published to the Google Apps Marketplace (as of November 24, 2015):
  1. Go to the [Developer Console](https://console.developers.google.com/) and create a new project
  1. On the Dashboard for the new project under the "Use Google APIs" section, click "Enable and manage APIs".
  1. Select the "Google Apps Marketplace SDK" under "Google Apps APIs"
  1. On the "Google Apps Marketplace SDK" page:
    1. Click the "Enable API" button
    1. Click the "Configuration" tab
    1. Click the "Create an OAuth 2.0 client ID" link, which will take you to the Credentials page
  1. On the Credentials page:
    1. Click the "Add credentials" link and choose the "OAuth 2.0 Client ID" option
    1. Click the "Configure Consent Screen" button
    1. Fill out the required information and click "Save".
    1. Under "Create client ID" per [these instructions](https://developers.google.com/api-client-library/javascript/start/start-js):
      1. Choose Application type = Web application
      1. Enter the name of your app
      1. Enter your website root in "Authorized JavaScript origins"
      1. Leave "Authorized redirect URIs" blank
      1. Click "Create" and you should see a dialog displaying your client ID and client secret.  Record these in a safe place for later use.
  1. Go back to the API Manager Overview for this project by clicking "Overview" on the left.
  1. Select the "Google Apps Marketplace SDK" under "Google Apps APIs"
  1. On the "Google Apps Marketplace SDK" page:
    1. Click the "Configuration" tab
    1. Enter configuration info as follows:
      1. Add a description
      1. Add 4 icons of various sizes
      1. Add a URL for the Terms of Service
      1. In the extensions section, check the "Universal navigation extension" and the "Gmail contextual gadget extension"

### Credits

Thanks to [Joc](http://stackoverflow.com/users/4265687/joc) for his [lovely post](http://stackoverflow.com/questions/29926796/gmail-contextual-gadget) on Stack Overflow, which provided the initial series of steps to follow to get this working.

Thanks to Noldoaran and Augiasstallputzer on Wikipedia for the public domain [globe](https://en.wikipedia.org/wiki/User:GorillaHunter/Sandbox#/media/File:Globe.png) used in the logo image.
