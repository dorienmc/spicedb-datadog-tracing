# spicedb-datadog-tracing
This repo shows a docker compose example of using open telemetry tracing with spicedb and datadog

Prerequisites:
- Docker (compose)
- A datadog API key

> You can use a datadog API key from a datadog learning environment. You just need to create a [datadog learning account](https://learn.datadoghq.com/) and start a course that includes a practical lab. The lab will set up a temporary learning datadog environment with a user and an API key.

> Beware: the datadog learning environments will filter apps based on an environment (for example `dd101-dev`), make sure that the environment in the docker compose matches.

# Setup
Create a `.env` file and add your datadog api key
```
echo "API_KEY=<your api key>" >> .env
```

# Docker compose
Start with `docker compose up -d`
Stop with `docker compose down`