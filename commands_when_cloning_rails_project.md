## Commands when cloning a rails project

1. Clone the code from github


```
git clone git@github.com:CoderAcademy-MEL/celebrities-app.git
```

2. `cd` into the new directory

3. Install the javascript dependencies


```
yarn install
```

4. Create the postgres database

```
rails db:create
```

5. Execute the migration files to format the db

```
rails db:migrate
```

6. `rails s`
