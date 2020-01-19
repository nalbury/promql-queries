# promql-queries
Helpful Prometheus Queries

Can by copy pasted into prometheus/grafana:

```
cat pod-resources/cpu-usage.promql |pbcopy
```

Or used with the [promql cli](https://github.com/nalbury/promql-cli):

```
promql "$(cat pod-resources/cpu-usage.promql)"
```
