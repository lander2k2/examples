## An example using Ory Cloud with Ory Keto self hosted

This example shows basic configuration of `cookie_session` authenticator for oathkeeper and `remote_json` for authorization

## Running locally

```
   git clone git@github.com:ory/examples
   cd examples/oathkeeper/02-authenticators
   docker-compose up
```

Wait for a couple of seconds and open `http://127.0.0.1:8080/hello`

You can find read configuration of [`access-rules.yml`](./oathkeeper/access-rules.yml) and
[`oathkeeper.yml`](./oathkeeper/oathkeeper.yml)