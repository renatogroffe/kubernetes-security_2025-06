# kubernetes-security_2025-06
Conteúdos sobre execução de análises de segurança em clusters Kubernetes.

Live do Canal .NET em que esses materiais foram apresentados: https://www.youtube.com/watch?v=lOGyI2RVkPs

---

Workloads testados com o cluster do AKS - Azure Kubernetes Service: https://github.com/renatogroffe/Kubernetes-KEDA-Cron-Workload

Saiba mais sobre o projeto KEDA em: https://keda.sh/

---

Exemplo com Kubescape:

```bash
kubescape scan --format html --output report-cluster.html --severity-threshold high
```

Repositório com Pipeline do Azure DevOps demonstrando o uso do Kubescape: https://github.com/renatogroffe/azuredevops-kubescape-kubernetes-kind

---

Exemplo com Popeye:

```bash
popeye -A --save --out html --output-file report-cluster.html
```

Repositório com Pipeline do Azure DevOps demonstrando o uso do Popeye: https://github.com/renatogroffe/AzureDevOps-Popeye-Kubernetes-kind

---
