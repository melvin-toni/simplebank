Generate new DB migration file
migrate create -ext sql -dir db/migration -seq init_schema

Library :
https://docs.sqlc.dev/en/stable/overview/install.html

Generate SQLC :
docker run --rm -v "%cd%:/src" -w /src kjconroy/sqlc generate