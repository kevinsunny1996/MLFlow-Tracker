## What this repo is about?

### MLFlow doesn't offer an official helm chart repo / docker image and since the End to End Data Science Project being worked upon needs this tool and Airflow for data pipelines, we're maintaining a docker image for the same and creating a custom helm chart out of it.

## Prerequisites:
- Knowledge of Docker (Creating a dockerfile and keeping track of images with tags)
- Knowledge of package management using pip
- Creating a custom helm chart and managing dependencies (Secrets Manager will be used to get passwords and other sensitive info).
- Knowledge of creating Github Actions deployment pipelines (Will be used for image creation , Packer was to be used however couldn't find any relevant sources on how to integrate it with AWS ECR).

## References to get around this problem:
- [MLFlow Server hosting tutorial](https://pilotcoresystems.com/insights/deploying-airflow-mlflow-in-kubernetes-eks/)
- [Getting started with Helm](https://helm.sh/docs/intro/install/)