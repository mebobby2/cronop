# cronop

## Install into K8s cluster
1. make manifests (generates the CRDs, roles, and webhook k8s definitions)
2. make install (installs the CRD into the k8s cluster)
3. make run (run the controller on the k8s cluster)

Upto:

https://book.kubebuilder.io/cronjob-tutorial/controller-implementation.html#3-clean-up-old-jobs-according-to-the-history-limit
