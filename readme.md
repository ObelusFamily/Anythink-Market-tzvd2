# Welcome to the Anythink Market repo

To start the app use: `./start.sh`, it'll start both the backend and the frontend.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

### Getting the backend started:

1. Create a new DB in mongoDB.
2. Create new user in DB under _DatabaseAccess_ on the left sidebar
3. Add your IP to access the DB under _NetworkAccess_ on the left sidebar
4. Create a `.env` file and add `MONGODB_URI` with you username and password
5. Go to ./backend and run `npm install / yarn`
6. Run the backend with `npm start / yarn start`
