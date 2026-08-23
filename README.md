# Envoy Gateway Kubernetes system stack for Wodby

Envoy Gateway supplies the Kubernetes Gateway API and ingress control plane for
Wodby clusters configured to use Envoy Gateway.

This repository defines the Wodby stack manifests and default service
composition for Envoy Gateway.

<!-- wodby:generated:start -->

## Stack contract

- [Envoy Gateway stack on Wodby](https://wodby.com/stacks/envoy-gateway)
- [Wodby Kubernetes platform](https://wodby.com)
- [Wodby stack documentation](https://wodby.com/docs/2.0/stacks/)
- [Stack manifest reference](https://wodby.com/docs/2.0/stacks/template/)

## System service definitions

- [Envoy Gateway system service](https://github.com/wodby/service-envoy-gateway)

## What's included

| Component / service | Default configuration |
| --- | --- |
| Envoy Gateway<br>`envoy-gateway` | required; enabled by default |

System services are enabled or disabled according to the cluster provider and
infrastructure configuration.

## Validate the stack manifest

```bash
wodby stack validate-manifest stack.yml --org <org-id>
```

<!-- wodby:generated:end -->
