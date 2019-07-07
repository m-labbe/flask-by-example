# flask-by-example
Example Flask Project
https://realpython.com/flask-by-example-part-1-project-setup/


Install postgres via Homebrew
```
brew install postgresql
```

Start postgres database
```
pg_ctl -D /usr/local/var/postgres start
```

Stop postgres database
```
pg_ctl -D /usr/local/var/posgres stop
```

Run the app on port 5000
```
pipenv run python app.py
```
