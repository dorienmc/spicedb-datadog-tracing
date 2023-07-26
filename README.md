# spicedb-datadog-tracing
This repo shows a docker compose example of using open telemetry tracing with spicedb and datadog

Prerequisites:
- Docker (compose)
- A datadog API key

> You can use a datadog API key from a datadog learning environment. You just need to create a [datadog learning account](https://learn.datadoghq.com/) and start a course that includes a practical lab. The lab will set up a temporary learning datadog environment with a user and an API key.

# Setup
Create a `.env` file and add your datadog api key
```
echo "API_KEY=<your api key>" >> .env
```

# Start
Start with `docker compose up -d`