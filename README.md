### Fleet with Graylog

Create a file called `.env` and put the following values in it:

```
GRAYLOG_PASSWORD_SECRET=<some password at least 16 characters long>
GRAYLOG_ROOT_PASSWORD_SHA2=<sha256sum of the password secret>
```

`docker compose up` or `docker-compose up`