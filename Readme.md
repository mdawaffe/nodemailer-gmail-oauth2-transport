Gmail OAuth2 Transport for Nodemailer
=====================================

Nodemailer Transport for Sending Email or Creating Drafts with Gmail via OAuth2 Credentials.

For authentication example and bin script, see [`send-gmail`](https://github.com/mdawaffe/send-gmail).

Config
------

`config.json`

```js
{
	"google": {
		"CLIENT_ID": "...",
		"CLIENT_SECRET": "...",
		"REDIRECT_URL": "urn:ietf:wg:oauth:2.0:oob"
		"RESTRICT_AUTH_DOMAIN" : "my-google-apps-domain.com",
	}
}
```
