https://github.com/open-telemetry/opentelemetry-go-contrib

https://github.com/open-telemetry/opentelemetry-go-contrib/tree/main/instrumentation/net/http/otelhttp/example

```sh
go get go.opentelemetry.io/contrib/instrumentation/net/http

```

```mermaid
graph LR

subgraph "go.opentelemetry.io/otel"
    otel.SetMeterProvider
end

subgraph "go.opentelemetry.io/otel/api/global"
    global.SetMeterProvider
end

otel.SetMeterProvider --> global.SetMeterProvider
```


Package trace contains support for OpenTelemetry distributed tracing.
https://pkg.go.dev/go.opentelemetry.io/otel/sdk/trace
