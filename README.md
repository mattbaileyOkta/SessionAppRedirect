# Session App Redirect

This demo is to help show how you can use Global Redirect to send a user to a specfic page/application once they have a session. The use case was mainly designed around having multiple registration pages, after the user actives the account how do you point the user back to application where they registered?

# Setup

You need:

Okta tenant
SSR Enabled (if that is how you want to trigger the redirect)
Global Redirect enabled and pointing at your page
API key
Proxy- I use the Proxy from okta-dac/byob projects (this is needed as we are calling the users API endpoint with a userID)

## Running Locally
```
npm install
npm run dev
```