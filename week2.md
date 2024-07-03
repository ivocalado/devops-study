# Week 2: Kubernetes

## Activity 1: Kubernetes Basics
**Goal:** Understand the fundamentals of Kubernetes.
**Description:** Introduction to Kubernetes concepts and architecture.

**Tasks:**
1. Install Kind or set up a Kubernetes cluster.
2. Explore `kubectl` commands: `kubectl get`, `kubectl describe`, `kubectl logs`, `kubectl exec`.
3. Deploy a simple application using `kubectl run`.
4. Expose the application using `kubectl expose`.
5. Scale the application using `kubectl scale`.

**References:**
- [Kubernetes Documentation](https://kubernetes.io/docs/home/)
- [Kind Documentation](https://kind.sigs.k8s.io/docs/user/quick-start/)
- [kubectl Cheat Sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)

## Activity 2: Deployments and Services
**Goal:** Manage application deployments and services.
**Description:** Learn about Kubernetes Deployments and Services.

**Tasks:**
1. Create a Deployment for a sample application.
2. Update the Deployment with a new version of the application.
3. Roll back to a previous version using Deployment revisions.
4. Create a Service to expose the Deployment.
5. Use `kubectl port-forward` to access the application locally.

**References:**
- [Kubernetes Deployments](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/)
- [Kubernetes Services](https://kubernetes.io/docs/concepts/services-networking/service/)

## Activity 3: ConfigMaps and Secrets
**Goal:** Manage configuration and sensitive data in Kubernetes.
**Description:** Use ConfigMaps and Secrets to decouple configuration from application code.

**Tasks:**
1. Create a ConfigMap and use it in a Pod.
2. Create a Secret and use it in a Pod.
3. Use environment variables and volume mounts for ConfigMaps and Secrets.
4. Update ConfigMaps and Secrets without redeploying Pods.
5. Explore the use of `kubectl apply` for managing configurations.

**References:**
- [Kubernetes ConfigMaps](https://kubernetes.io/docs/concepts/configuration/configmap/)
- [Kubernetes Secrets](https://kubernetes.io/docs/concepts/configuration/secret/)

## Activity 4: Persistent Storage in Kubernetes
**Goal:** Understand persistent storage solutions in Kubernetes.
**Description:** Learn about Persistent Volumes (PVs) and Persistent Volume Claims (PVCs).

**Tasks:**
1. Create a Persistent Volume (PV).
2. Create a Persistent Volume Claim (PVC) and use it in a Pod.
3. Experiment with different storage classes.
4. Resize a PVC.
5. Backup and restore data from a PV.

**References:**
- [Persistent Volumes](https://kubernetes.io/docs/concepts/storage/persistent-volumes/)
- [Storage Classes](https://kubernetes.io/docs/concepts/storage/storage-classes/)

## Activity 5: Helm Charts
**Goal:** Manage Kubernetes applications using Helm.
**Description:** Introduction to Helm and its benefits for managing Kubernetes applications.

**Tasks:**
1. Install Helm.
2. Use Helm to deploy a sample application.
3. Explore Helm commands: `helm install`, `helm upgrade`, `helm rollback`, `helm uninstall`.
4. Customize Helm charts with values files.
5. Create a custom Helm chart for a simple application.

**References:**
- [Helm Documentation](https://helm.sh/docs/)
- [Helm Charts Repository](https://artifacthub.io/)
