```bash
bal openapi flatten -i docs/spec/openapi.yaml -o docs/spec
```

```bash
bal openapi align -i docs/spec/flattened_openapi.yaml -o docs/spec
```

```bash
bal openapi -i docs/spec/aligned_ballerina_openapi.yaml -o . --mode client
```