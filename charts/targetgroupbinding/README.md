# Helm Chart for TargetGroupBinding (AWS Load Balancer Controller)

This is a helm chart created for https://kubernetes-sigs.github.io/aws-load-balancer-controller/v2.4/guide/targetgroupbinding/targetgroupbinding/

## Usage

* Currently it supports `serviceRef` and `nodeSelector` only one of the Elements is supported at a time

Setting the values file below:
```yaml
service:
    name: name-of-the-service
    port: 80
```
Or
```yaml
nodeSelector:
    foo: bar
```