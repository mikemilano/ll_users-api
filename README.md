# Lunch & Learn: Symfony Users API

This is a Symfony skeleton with a Lando and Makefile added to make it easy to follow along the Lunch & Learn.

This starting point was created like this:

```bash
composer create-project symfony/skeleton users-api
cd users-api/
composer require symfony/orm-pack
```

After that, the `.lando` and `Makefile` were added and the `.env` file was configured for the database connection.

## What we're building

This app is an unsecured microservice for user data meant to be hosted on a private network accessible 
to only trusted systems. For example, an OAuth application would be accessible to the public
and make API requests to this Users API over a private network.

The objects we'll build can be extended to be used with Symfony's security component but the purpose
of this is to demonstrate how to create/maintain entities and expose them over an API.

## Get started

```
lando start
```
