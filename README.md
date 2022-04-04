# gops-flux-config

## Local

```sh
kind create cluster
flux install
helm template . | kubectl apply -f -
```

## Flux managing Flux Remotely

See [example](./examples/remote/).

