# Helm 3 Commands.





## Contents at a Glance.
* [About.](#about)
* [Documentation.](#documentation)
* [General.](#general)  
* [Useful links.](#useful-links)  
* [Help.](#help)





## About.





## Documentation.





## General.

| Key/Command                                                                         | Description                                                                                                        |
| ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| helm version                                                                        |                                                                                                                    |
| helm version --short --client                                                       |                                                                                                                    |
| helm list                                                                           |                                                                                                                    |
| helm show chart [nameChart]                                                         |                                                                                                                    |
|                                                                                     |                                                                                                                    |





## helm template

| Key/Command                                                                         | Description                                                                                                        |
| ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| helm template [nameChart] [chartDir] [flags]                                        |                                                                                                                    |
| helm template . -f ./values/prometheus.yaml                                                                                    |                                                                                                                    |
|                                                                                     |                                                                                                                    |





## helm install

| Key/Command                                                                         | Description                                                                                                        |
| ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| helm install [nameAppInTheSystem] [nameApp]                                         |                                                                                                                    |
| helm install --values valuesFile.yaml                                               |                                                                                                                    |
|                                                                                     |                                                                                                                    |





## helm create

| Key/Command                                                                         | Description                                                                                                        |
| ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| helm create [nameApp]                                                               |                                                                                                                    |
|                                                                                     |                                                                                                                    |





## helm upgrade

| Key/Command                                                                         | Description                                                                                                        |
| ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| helm upgrade [nameChart] [chartLocation] --set deployment.tag=1.0.4                 |                                                                                                                    |
|                                                                                     |                                                                                                                    |





## helm plugin

| Key/Command                                                                         | Description                                                                                                        |
| ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| helm plugin list                                                                    |                                                                                                                    |
| helm plugin install [namePlugin]                                                    |                                                                                                                    |
| helm [namePlugin] help                                                              |                                                                                                                    |
| helm uninstall [namePlugin]                                                         |                                                                                                                    |
|                                                                                     |                                                                                                                    |





## helm repo

| Key/Command                                                                         | Description                                                                                                        |
| ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| helm search repo [nameRepo]                                                         |                                                                                                                    |
| helm repo add stable https://kubernetes-charts.storage.googleapis.com/              | Add a chart repository.                                                                                            |
| helm repo update                                                                    |                                                                                                                    |
|                                                                                     |                                                                                                                    |



## Sort this commands.

| Key/Command                                                                         | Description                                                                                                        |
| ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| helm repo add strimzi https://strimzi.io/charts/                                    |                                                                                                                    |
| helm install strimzi strimzi/strimzi-kafka-operator --namespace microcks            |                                                                                                                    |
|                                                                                     |                                                                                                                    |





## Useful links.
* [Introduction to Helm | Kubernetes Tutorial | Beginners Guide](https://www.youtube.com/watch?v=5_J7RWLLVeQ)
* []()





## Help.
