# cronop

## Development
1. make manifests (generates the CRDs, roles, and webhook k8s definitions)
2. make install (installs the CRD into the k8s cluster)
3. make run (run the controller on local machine against a k8s cluster)
4. kubectl apply -f config/samples/batch_v1_cronjob.yaml (deploy test CRD)
5. kubectl get cronjob.batch.tutorial.kubebuilder.io (view the list of custom CRDs for this type)

Upto:

https://book.kubebuilder.io/cronjob-tutorial/running.html
Now that we know it's working, we can run it in the cluster
