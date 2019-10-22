# AirBnb Example API

Using Adonis implements a fake and simple AirBnb api, configuring the database and migrations, creating the routes, models and controllers from the service. Also exercise the relations concepts.
In this api, we could register and logIn, using Bearer (JWT) Token.
We also have a CRUD for properties, with their properties, and the capable of having some images (a model itself).

# Adonis API application

This is the boilerplate for creating an API server in AdonisJs, it comes pre-configured with.

1. Bodyparser
2. Authentication
3. CORS
4. Lucid ORM
5. Migrations and seeds

## Setup

Use the adonis command to install the blueprint

```bash
adonis new yardstick --api-only
```

or manually clone the repo and then run `npm install`.

### Migrations

Run the following command to run startup migrations.

```js
adonis migration:run
```
