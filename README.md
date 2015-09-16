Heroku MOL test
===============

| A static sandbox for MOL integration

This a **free** solution for both MOL developers and external developers to
develop solutions together.

Installation
------------

1. Install [git](https://git-scm.com/)
1. Create a [heroku](https://heroku.com) account
1. Install the [heroku toolbelt](https://toolbelt.heroku.com/)
1. Ask [John Wright](mailto:john.wright@mailonline.co.uk) to give you access to the account
1. Clone the repo: `heroku git:clone -a mol-test`
1. Install [nvm](https://github.com/creationix/nvm)
1. Install the correct version of node (from within the project): `nvm install`
1. Install the required dependencies: `npm install`

Viewing the project
-------------------

```
heroku open
```

Running locally
---------------

```
npm start
```

If you'd like a better development environment use the watch command instead:

```
npm i -g nodemon
npm run watch
```

Deploying
---------

1. Commit your changes: `git add -A && git commit`
1. Push your changes: `git push heroku master`
