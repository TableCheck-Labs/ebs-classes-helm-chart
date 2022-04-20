# ebs-classes-helm-chart
Add all AWS EBS classes as StorageClasses on your AWS EKS clusters.

## Helm

*A hosted Helm chart* is available. Use the following commands to use it. https://tablecheck-labs.github.io/ebs-classes-helm-chart/

```
helm repo add ebs-classes https://tablecheck-labs.github.io/ebs-classes-helm-chart/
helm upgrade --install ebs-classes https://tablecheck-labs.github.io/ebs-classes-helm-chart/
```

For local installations:

```
helm upgrade --install ebs-classes ./helm/ebs-classes
```
