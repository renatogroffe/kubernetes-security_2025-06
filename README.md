# kubernetes-security_2025-06
Conteúdos sobre execução de análises de segurança em clusters Kubernetes.

Workloads testados com o cluster do AKS - Azure Kubernetes Service:
- https://github.com/renatogroffe/Kubernetes-KEDA-Cron-Workload

Exemplo com Kubescape:

```bash
kubescape scan --format html --output report-cluster.html --severity-threshold high
```
Repositório com Pipeline do Azure DevOps demonstrando o uso do Kubescape: https://github.com/renatogroffe/azuredevops-kubescape-kubernetes-kind
