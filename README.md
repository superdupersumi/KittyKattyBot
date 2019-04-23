# KittyKattyBot

## Deploy on local machine

In your terminal, run the following command to start a local server

```
python -m SimpleHTTPServer
```

Then go to http://localhost:8000 to view the site.

## Deploy on Netlify

This service is automatically deployed on Netlify at https://kittykattybot.netlify.com when you push your code to GitHub.

## Functions on Netlify

If you head over to https://kittykattybot.netlify.com/.netlify/functions/hello you should receive `Meoooow` in the response body.

See `functions/hello.js` for implementation details.
