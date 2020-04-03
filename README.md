# camel-k-metrics

## 1. Tracing with Jaeger

```
kamel run Basic.java customizers/OpentracingCustomizer.java --name basic -d camel-opentracing -d mvn:io.jaegertracing:jaeger-client:1.2.0 --property-file basic.properties
```