# HASi-MD
 HASi-MD WHATSAPP BOT POWER BY HASiNTHA
{
 "name": "HASi bot",
  "description": "Javascript WhatsApp bot made by HASi Official",
  "logo": "https://telegra.ph/file/ef48cc8d2d26081f7d46a.jpg",
  "keywords": ["bot"],
  "success_url": "/",

    "env": {
        "SESSION_ID": {
            "description": "Type the Session-ID you got from pair or scan qr.",
            "required": true,
            "value": "put session id here"
        }
    },
    "buildpacks": [
        {
            "url": "https://github.com/heroku/heroku-buildpack-nodejs.git"
        }
     ],
  "stack": "heroku-24"
}
