
# Demo for Kubernetes at de:code 2018 

## Description

* Target k8s applications - https://github.com/yokawasa/azure-k8s-daas-ticketmonster-demo
* Use Filebeat, Metricbeat, Packetbeat for collecting system metrics & application logs

## Prepare

Need to apply [kube-state-metrics](https://github.com/kubernetes/kube-state-metrics) before creating metricbeat. It collects some metrics from kube-state-metrics.
