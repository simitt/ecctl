## ecctl deployment template create

Creates a new deployment template (Available for ECE only)

### Synopsis

Creates a new deployment template (Available for ECE only)

```
ecctl deployment template create --file <definition.json> [flags]
```

### Options

```
  -f, --file string                    Deployment template definition.
  -h, --help                           help for create
      --hide-instance-configurations   Hides instance configurations - only visible when using the JSON output.
      --template-id string             Optional deployment template ID. Otherwise the deployment template will be created with an auto-generated ID.
```

### Options inherited from parent commands

```
      --apikey string      API key to use to authenticate (If empty will look for EC_APIKEY environment variable)
      --config string      Config name, used to have multiple configs in $HOME/.ecctl/<env> (default "config")
      --force              Do not ask for confirmation
      --format string      Formats the output using a Go template
      --host string        Base URL to use
      --insecure           Skips all TLS validation
      --message string     A message to set on cluster operation
      --output string      Output format [text|json] (default "text")
      --pass string        Password to use to authenticate (If empty will look for EC_PASS environment variable)
      --pprof              Enables pprofing and saves the profile to pprof-20060102150405
  -q, --quiet              Suppresses the configuration file used for the run, if any
      --region string      Elasticsearch Service region
      --timeout duration   Timeout to use on all HTTP calls (default 30s)
      --trace              Enables tracing saves the trace to trace-20060102150405
      --user string        Username to use to authenticate (If empty will look for EC_USER environment variable)
      --verbose            Enable verbose mode
```

### SEE ALSO

* [ecctl deployment template](ecctl_deployment_template.md)	 - Interacts with deployment template APIs
