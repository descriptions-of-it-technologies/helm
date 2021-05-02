# Helm 2 Commands.





## Contents at a Glance.
* [About.](#about)
* [Documentation.](#documentation)
* [Help.](#help)





## About.





## Documentation.





## General. 

| Key/Command                                                        | Description                                                                                                        |
| ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ |
| helm help                                                          |                                                                                                                    |
| helm version --short --client                                      |                                                                                                                    |
| helm version                                                       |                                                                                                                    |
| helm install                                                       |                                                                                                                    |
| helm install [nameApp] --name [nameAppInTheSystem]                 |                                                                                                                    |
| helm install --values=my-values.yaml [chartName]                   |                                                                                                                    |
| helm install --set version=2.0.0                                   |                                                                                                                    |
| helm fetch                                                         |                                                                                                                    |
| helm init                                                          |                                                                                                                    |
| helm status [keyWords]                                             |                                                                                                                    |
| helm search                                                        |                                                                                                                    |
| helm repo update                                                   |                                                                                                                    |
| helm upgrade                                                       |                                                                                                                    |
| helm rollback                                                      |                                                                                                                    |
| helm delete                                                        |                                                                                                                    |
| helm reset                                                         |                                                                                                                    |
| helm package                                                       |                                                                                                                    |
|                                                                    |                                                                                                                    |





## 
| Key/Command                                                                                                  | Description                                                                                                        |
| ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ |
| kubectl -n kube-system create serviceaccount tiller                                                          |                                                                                                                    |
| kubectl create clusterrolebinding tiller --clusterrole cluster-admin --serviceaccount=kube-system:tiller     |                                                                                                                    |
| kubectl get clusterrolebindings tiller                                                                       |                                                                                                                    |
|                                                                                                              |                                                                                                                    |





## Help.
