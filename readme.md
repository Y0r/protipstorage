Telegram Storage instance for chanel.

* Developed using _ library to handle Telegram API.
* Built on docker to keep setup clear and scalable.

# Installation

1) Build container 'docker build -t storage .'
2) Run 'docker compose up'

### Mongo debug:

1) Run 'docker compose exec mongo_db sh' to open container CLi.
2) Run 'mongosh' to start session (?).

Then you can use different commands:
- show collections
- show tables
- db.logs.find()

_logs - table name to display._