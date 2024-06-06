This is a repository of helm charts for firefly installation on kubernetes cluster
There are 3 helm charts for the different parts of the application and will be installed separately.
This will create PVC in local drive of the kubernetes cluster in case of minikube, k3s and other local k8s distros, as the current helm chart uses the local persistent volume.
Pending- PVC for cloud hosted k8s distros need to be added

To be changed when installing
1. Please change secrets for the charts in values.yaml of respectiv charts before installing helm charts, there are dummy values present for now.
2. Please change the location for the storage location of the PV in values.yaml present in respective charts.
