# OAuth-Gotchas

## Gotchas in Development
1. Note that the URL in your browser bar during development needs to match the URL that you registered as the "Redirect URI". If the Redirect URI states "http: //localhost:<port number>/callback", when you open up the frontend of your application in the browser using the Loopback Address "127.0.0.1", your OAuth flow will break during the final redirect. All URLs / domains need to be in strict agreement!!!<br>
<br>
## Gotchas in Production
