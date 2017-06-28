API Basejump: Timestamp microservice
User stories:
1) I can pass a string as a parameter, and it will check to see whether that string contains either a unix timestamp or a natural language date (example: January 1, 2016)
2) If it does, it returns both the Unix timestamp and the natural language form of that date.
3) If it does not contain a date or Unix timestamp, it returns null for those properties.
Example usage:
https://timestamp-microservice-api.glitch.me/December%2015,%202015
https://timestamp-microservice-api.glitch.me/1450137600
Example output:
{ "unix": 1450137600, "natural": "December 15, 2015" }



Your Project
------------

On the front-end,
- edit `public/client.js`, `public/style.css` and `views/index.html`
- drag in `assets`, like images or music, to add them to your project

On the back-end,
- your app starts at `server.js`
- add frameworks and packages in `package.json`
- safely store app secrets in `.env` (nobody can see this but you and people you invite)


