# [Logturm](https://logturm.com) Helm chart

Simple helm chart to deploy a vector agent to your cluster that automatically sends all cluster logs to logturm.

## Configuration
For a simple and production ready setup you only need to add the following configuration

```yaml
vector:
  customConfig:
    sinks:
      logturm_http_sink:
        auth:
          token: $TOKEN
```

---

[MIT license](LICENSE)
