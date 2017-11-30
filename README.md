# The Journal of Open Source Containers

This is an extension of the [Open Journals](http://theoj.org) to provide a developer friendly journal for containers.

## Development
This is an application friendly to run on heroku. So you should first [make an account](https://devcenter.heroku.com/) and then [follow the instructions to deploy the application](https://devcenter.heroku.com/articles/getting-started-with-ruby#introduction). It comes down to:

1. Login with `heroku login`
2. Create the heroku branch with `heroku create`

```
heroku create
Creating app... done, ⬢ shielded-mountain-65855
https://shielded-mountain-65855.herokuapp.com/ | https://git.heroku.com/shielded-mountain-65855.git
```

3. Migrate the database to create the tables, etc.

```
heroku run rake db:migrate
```
