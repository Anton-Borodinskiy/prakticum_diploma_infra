# Пельменная Infra
Репозиторий для хранения кода и развертывания инфраструктуры.

# Terraform 
Для создания инфраструктуры в облаке мы используем Terraform, в качетве облачного провадера выступает Yandex Cloud.

# Кластер K8S

- В качестве ingress controller используется NGINX Ingress
- Для мониторинга стек Prometheus + Grafana
- Для деплоя ArgoCD
- ArgoCD, Prometheus+Grafana, Ingress controller описаны в виде Helm Charts для их быстрого развертывания в k8s

# Ресурсы инфраструктуры
http://grafana.tech.antonborodinskiy.ru
http://argocd.tech.antonborodinskiy.ru
https://prometheus.tech.antonborodinskiy.ru
