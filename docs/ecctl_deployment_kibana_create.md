## ecctl deployment kibana create

Creates a Kibana Cluster

### Synopsis

Creates a Kibana Cluster

```
ecctl deployment kibana create -f <definition.json> [flags]
```

### Options

```
  -f, --file-template string   JSON file that contains the Kibana cluster definition
  -h, --help                   help for create
      --id string              Optional ID to set for the Elasticsearch cluster (Overrides ID if present).
      --name string            Optional name to set for the Kibana cluster (Overrides name if present).
  -t, --track                  Tracks the progress of the performed task
```

### Options inherited from parent commands

```
      --apikey string      API key to use to authenticate (If empty will look for EC_APIKEY environment variable)
      --config string      Config name, used to have multiple configs in $HOME/.ecctl/<env> (default "config")
      --force              Do not ask for confirmation
      --format string      Formats the output using a Go template
      --host string        Base URL to use (default "https://api.elastic-cloud.com")
      --insecure           Skips all TLS validation
      --message string     A message to set on cluster operation
      --output string      Output format [text|json] (default "text")
      --pass string        Password to use to authenticate (If empty will look for EC_PASS environment variable)
      --pprof              Enables pprofing and saves the profile to pprof-20060102150405
  -q, --quiet              Suppresses the configuration file used for the run, if any
      --region string      Elastic Cloud region
      --timeout duration   Timeout to use on all HTTP calls (default 30s)
      --trace              Enables tracing saves the trace to trace-20060102150405
      --user string        Username to use to authenticate (If empty will look for EC_USER environment variable)
      --verbose            Enable verbose mode
```

### SEE ALSO

* [ecctl deployment kibana](ecctl_deployment_kibana.md)	 - Manages Kibana clusters
