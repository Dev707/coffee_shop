# Coffee Shop Full Stack

## Full Stack Nano - IAM Final Project

Udacity has decided to open a new digitally enabled cafe for students to order drinks, socialize, and study hard. But they need help setting up their menu experience.

You have been called on to demonstrate your newly learned skills to create a full stack drink menu application. The application must:

1. Display graphics representing the ratios of ingredients in each drink.
2. Allow public users to view drink names and graphics.
3. Allow the shop baristas to see the recipe information.
4. Allow the shop managers to create new drinks and edit existing drinks.

## Manger account:

Email:
```
manger@coffeeshop.com
```

Password:
```
M123@manger
```

Token:
```
eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCIsImtpZCI6ImtSdjhnWWM0d01SNFJFX3dITnBLWCJ9.eyJpc3MiOiJodHRwczovL2Rldi01bnN2LW1mbS51cy5hdXRoMC5jb20vIiwic3ViIjoiYXV0aDB8NjExZTFiODdhZWJiNGEwMDY5OTdkY2YzIiwiYXVkIjoiY29mZmVlc2hvcCIsImlhdCI6MTYyOTQ5NjAwNSwiZXhwIjoxNjI5NTgyNDA1LCJhenAiOiJDaFhUaVVibUZtc2QwaE9BMjd0RFliT0NHZUNrU3UzcyIsInNjb3BlIjoiIiwicGVybWlzc2lvbnMiOlsiZGVsZXRlOmRyaW5rcyIsImdldDpkcmlua3MiLCJnZXQ6ZHJpbmtzLWRldGFpbCIsInBhdGNoOmRyaW5rcyIsInBvc3Q6ZHJpbmtzIl19.bLf2NbMqFXr9SsE9OS9XTgbbZ7UF1cm8doQxvyUW6CYmVQ49lZg4V7AeSk9Ge4VOYT-gcuqh7O-E3W-RIBnJfHdL6K2lHc0jS-BGBAB0u6AEpzHeAjsbgRp65kDZqeleN9JP5O24mh5r_Iiy--c0Ct_Qs6qQFnMadOBl2cC2rM8NQlNW4l0zRb_LEXix-bCqzFrnbIt8ge4TNgdpnOX7FIrZe1d4EUJwAvoJpcCJFzDvGbXsqNSqz-3-CLEJAnROaVPa-fjtBxwwYGAgW4a_3d6xmVbEptGRB7NNIJIqH5hWy5C4K0JXMJKwtHNZ0RO_TFCqT74_gY2yLrCJPmg-bQ
```

## Barista account:

Email:
```
barista@coffeeshop.com
```

Password:
```
B123@barista
```

Token:
```
eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCIsImtpZCI6ImtSdjhnWWM0d01SNFJFX3dITnBLWCJ9.eyJpc3MiOiJodHRwczovL2Rldi01bnN2LW1mbS51cy5hdXRoMC5jb20vIiwic3ViIjoiYXV0aDB8NjExZmVjMTc2MmVjYzAwMDZhYWZhN2Q3IiwiYXVkIjoiY29mZmVlc2hvcCIsImlhdCI6MTYyOTQ5MzkwNCwiZXhwIjoxNjI5NTgwMzA0LCJhenAiOiJDaFhUaVVibUZtc2QwaE9BMjd0RFliT0NHZUNrU3UzcyIsInNjb3BlIjoiIiwicGVybWlzc2lvbnMiOlsiZ2V0OmRyaW5rcyIsImdldDpkcmlua3MtZGV0YWlsIl19.Vk691-guIbemQvjrzgoI2tl3AeohB945-Jn2Nn40dtjAQleHyY3yMhxAiW87aP3O7795SInoOg_VHxhLCw8-SNEKPX-bFgGB__UYhi9UJh4jeTlStt2xJrtYy6Z4JTRnC1rDnE0z3DQqd4oxTvx_lyYzWoPDNpXBTOLBJEqWwGoMIVuA2Lazl4HjJPu9JJIlL1aiYkGbmCTEsO8CHpkMHf_GLA5jdyhWeg3pcLueqh4CqMSyAk6VOCfDaJ4IhtCbbCKtIkBqWrTXwVgdqWvkD9GmuJlhj91lvbspVPNGhw-AZXWpt_YsCov4F1-02oVbnmNM4KWIhYrsFm7WT0K5pA
```

## Tasks

There are `@TODO` comments throughout the project. We recommend tackling the sections in order. Start by reading the READMEs in:

1. [`./backend/`](./backend/README.md)
2. [`./frontend/`](./frontend/README.md)

## About the Stack

We started the full stack application for you. It is designed with some key functional areas:

### Backend

The `./backend` directory contains a partially completed Flask server with a pre-written SQLAlchemy module to simplify your data needs. You will need to complete the required endpoints, configure, and integrate Auth0 for authentication.

[View the README.md within ./backend for more details.](./backend/README.md)

### Frontend

The `./frontend` directory contains a complete Ionic frontend to consume the data from the Flask server. You will only need to update the environment variables found within (./frontend/src/environment/environment.ts) to reflect the Auth0 configuration details set up for the backend app.

[View the README.md within ./frontend for more details.](./frontend/README.md)
