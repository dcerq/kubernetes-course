# Kubernetes Basics Project

## Overview
This project was developed as part of the "Kubernetes" course offered by Alura.
It includes a basic Kubernetes project where various YAML files are created to define Pods, Cluster IPs, nodes, configmaps, and a database YAML.
To run the project, you will need to execute the following command for each YAML file:

```bash
kubectl apply -f path/to/file.yaml
```
Monitor the deployment and check the status:
```bash
kubectl get pods
kubectl get services
kubectl get configmaps
```
