# kube_07

### Манифесты:
  
**[deploy_multitool.yaml](https://github.com/ufilin/kube_07/blob/main/netology-chart-ufilin/templates/deploy_multitool.yaml)**  
**[deploy_web.yaml](https://github.com/ufilin/kube_07/blob/main/netology-chart-ufilin/templates/deploy_web.yaml)**  
**[serv_cluster_multitool.yaml](https://github.com/ufilin/kube_07/blob/main/netology-chart-ufilin/templates/serv_cluster_multitool.yaml)**  
**[serv_cluster_web.yaml](https://github.com/ufilin/kube_07/blob/main/netology-chart-ufilin/templates/serv_cluster_web.yaml)**  
**[serv_node.yaml](https://github.com/ufilin/kube_07/blob/main/netology-chart-ufilin/templates/serv_node.yaml)**  
**[Chart.yaml](https://github.com/ufilin/kube_07/blob/main/netology-chart-ufilin/Chart.yaml)**  
**[values.yaml](https://github.com/ufilin/kube_07/blob/main/netology-chart-ufilin/values.yaml)**    

  
## Задание 1: Подготовить Helm-чарт для приложения  
  
### Скриншот вывода curl  
  
<p align="center">
  <img src="kube_07-1-1.png" width="800">
</p>

<p align="center">
  <img src="kube_07-1-2.png" width="800">
</p>

<p align="center">
  <img src="kube_07-1-3.png" width="800">
</p>

После изменения версии образа контейнера nginx:

<p align="center">
  <img src="kube_07-1-4.png" width="800">
</p>

Потом перечитал задание и подумал что нужно было ещё обновить версию приложения в Chart:

<p align="center">
  <img src="kube_07-1-5.png" width="800">
</p>

## Задание 2: Запустить две версии в разных неймспейсах
  
### Скриншот вывода curl

<p align="center">
  <img src="kube_07-2-1.png" width="800">
</p>