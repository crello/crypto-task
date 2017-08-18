#Crypto task for Crello project.

#Goal

Create a kickass cryptocurrency monitoring application.

## Feature requirements

- `/` - home route, where user could see a table with a few cryptocurrencies(up to 10) and its mocked data. Sell and Buy columns could be sorted by click. Home route also must have `login button`. `Orders button` must be visible only for logged in users.

Table example provided below:

| Currency | Sell  |  Buy  |
| -------- | ----- | ----- |
| Bitcoin  | $1000 | $2200 |
| Ethereum | $1000 | $2200 |
|   Dash   | $1000 | $2200 |

- `/orders` - orders route, which is accessible only for `authorized` users. User could authorize through `Login button` on the home page.
Orders page has table with data about cryptocurrency orders.

Table example below:

| Currency | Amount  |  Action  |   Status  |
| -------- | ------- | -------- | --------- |
| Bitcoin  |    20   |   Sell   |  Pending  |
| Ethereum |  $1000  |  $2200   | Completed |

- `login modal` - should apper after clicking login button on the home page. Email and password fields must be validated before sending on backend.

## General Techical Requirements

1. Use `Redux` for state management
2. Use `React Router v4` and setup code-splitting
3. Application should support universal (`isomorphic`) rendering (Both on client and server)
4. Style `/`, `/orders` and `login modal` at least with Bootstrap. Setting up postcss would be a plus.
5. Setup `Webpack` config
6. Setup one simple frontend test with `Jest`.
7. Project should have a clear `README`, describing how to install dependencies, prepare infrastructure and launch application

## Code delivery

Project should be uploaded to applicant's github account with full commit history.
