# aws-mlops-bootcamp
----------

## Overview

SageMaker projects introduce MLOps templates that automatically provision the underlying resources needed to enable CI/CD capabilities for your ML development lifecycle. You can use a number of built-in templates  or create your own custom template (https://docs.aws.amazon.com/sagemaker/latest/dgsagemaker-projects-templates-custom.html ). You can use SageMaker Pipelines independently to create automated workflows; however, when used in combination with SageMaker projects, the additional CI/CD capabilities are provided automatically. 

Amazon SageMaker Pipelines makes it easy for data scientists and engineers to build, automate, and scale end to end machine learning pipelines. SageMaker Pipelines is a native workflow orchestration tool  for building ML pipelines that take advantage of direct Amazon SageMaker  integration. Three components improve the operational resilience and reproducibility of your ML workflows: pipelines, model registry, and projects. These workflow automation components enable you to easily scale your ability to build, train, test, and deploy hundreds of models in production, iterate faster, reduce errors due to manual orchestration, and build repeatable mechanisms.

This workshop focuses on using an MLOps template in SageMaker Project to bootstrap your ML workload and estrablish a CI/CD pattern from sample code. We show how to use the built-in build, train, and deploy project template as a base for a avalone classification example. This base template enables CI/CD for training ML models, registering model artifacts to the model registry, and automating model deployment with manual approval and automated testing. Also, we show how to use model monitor in SageMaker and visualize the result.

## Workshop

1. [MLOps Template for building, training and deploying models](MLOps%20Template/README.md)
2. [Change the model to something else (e.g. MNIST)](Custom%20Model/README.md)
3. [Set up model monitoring](Model%20Monitoring/README.md)