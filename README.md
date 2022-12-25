# Dev Feed

## About

A simple social network app for developers complete with an integration to showcase github repositories using github username.

### Built with

* [![React][React.js]][React-url]
* [![Express][Express]][Express-url]
* [![MongoDB][MongoDB]][MongoDB-url]

## Getting Started

### Development

1. Sign up at [MongoDB Atlas](https://www.mongodb.com/atlas/database) to create a new MongoDB cluster OR use a locally running empty instance of mongoDB.
2. Clone this repository: `https://github.com/AnirudhGowdar/dev-feed.git`
3. Run `npm run setup` to install required packages.
4. Create a default.json file with `mongoURI` value obtained from step 1 and a `jwtToken` value containing any long string of characters.

```json
{
    "mongoURI": "YOUR_MONGO_URI_STRING_HERE",
    "jwtSecret": "LONG_STRING_OF_ALPHANUMERIC_CHARS"
}
```

[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Express]: https://img.shields.io/badge/Express.js-404D59?style=for-the-badge
[Express-url]: https://expressjs.com
[MongoDB]: https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white
[MongoDB-url]: https://www.mongodb.com
