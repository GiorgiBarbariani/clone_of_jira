## Setting up development environment 🛠

- You need to install [postgreSQL] and create the database named `jira_development`.
- `clone from the git https://github.com/oldboyxx/jira_clone.git`
- Create the empty file `.env` in `/api`, and copy `/api/.env.example`.
- after this run `npm run install-dependencies`
- type `cd api && npm start`
- `cd client && npm start` in another terminal tab
- On the `http://localhost:8080/` port app should be run

### Accessibility ♿

All components have defined properly.

### Tests 🧪

Both API and Client are currently tested through [end-to-end Cypress tests].