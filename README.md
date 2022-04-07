# Glitch chart

## Installation
Copy and edit `secrets.yaml.sample` and `values.yaml.sample` to provide your
own `secrets.yaml` and `values.yaml` files, and then deploy the Helm chart
with: 

```
helm upgrade --install -f secrets.yaml glitch .
```
