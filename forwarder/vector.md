# Vector

Vector (www.vector.dev) is an open source tool that can be used to build observability pipelines including the ability
to ingest data from a wide variety of sources and forward that data on to a wide variety of destinations (sinks) 
including Observe.

- [vector.toml](vector.toml): An example Vector congifuration file that generates synthetic Syslog data, formats it as JSON, and then
sends it to Observe using the HTTP endpoint (https://docs.observeinc.com/en/latest/content/data-ingestion/endpoints/http.html). Please 
refer to [Observe's HTTP endpoint documentation](https://docs.observeinc.com/en/latest/content/data-ingestion/endpoints/http.html) and
[Vector's HTTP sink documentation](https://vector.dev/docs/reference/configuration/sinks/http/) for additional configuration information.

*Note*: The vector.toml file is offered without any warranty expressed or implied and is not officially supported Observe Inc. content. Use at
your own risk.
