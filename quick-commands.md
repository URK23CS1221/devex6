# Quick Reference for kubectl Commands

## Getting Started

- **Get all resources**: `kubectl get all`
- **Get nodes**: `kubectl get nodes`
- **Get namespaces**: `kubectl get namespaces`

## Pod Management

- **Create a pod**: `kubectl run <pod-name> --image=<image>`
- **Delete a pod**: `kubectl delete pod <pod-name>`
- **Get pod logs**: `kubectl logs <pod-name>`

## Deployment Management

- **Create a deployment**: `kubectl create deployment <deployment-name> --image=<image>`
- **Scale a deployment**: `kubectl scale deployment <deployment-name> --replicas=<number>`
- **Update a deployment**: `kubectl set image deployment/<deployment-name> <container-name>=<image>`  
- **Get deployment status**: `kubectl rollout status deployment/<deployment-name>`

## Service Management

- **Expose a deployment**: `kubectl expose deployment <deployment-name> --type=<type> --port=<port>`
- **Get services**: `kubectl get services`

## Other Useful Commands

- **Apply configuration from a file**: `kubectl apply -f <file-name>.yaml`
- **Describe a resource**: `kubectl describe <resource> <name>`