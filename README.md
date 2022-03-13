ArgoCD cli
```
argocd app create istio --helm-chart deployment --repo https://oktaysavdi.github.io/helm/charts/ --revision 0.1.0 --dest-namespace gitops-lab --dest-server https://kubernetes.default.svc --values-literal-file values2.yml
```
