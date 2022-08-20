# MLOps
## Overview
Machine Learning Operations (MLOps) is the process of putting machine learning models into production, then maintaining and monitoring them on a continuous basis. MLOps includes everything from the data flow to the deployment of machine learning models. The primary benefits of MLOps are efficiency, scalability, and reproducibility.

### Motivation
- *introductionary*: "Why do 87% of data science projects never make it into production?" [VentureBeat; article; 2019-07](https://venturebeat.com/2019/07/19/why-do-87-of-data-science-projects-never-make-it-into-production/)

### General Resources
- [MLOps.community](https://mlops.community/)
- [MLOps.toys](https://mlops.toys/feature-store)

## Architecture

### General Concepts
- *introductionary*: "MLOps Architecture Guide" [Neptune AI; blog post; 2022-03-31](https://neptune.ai/blog/mlops-architecture-guide)
- *cult*: "Machine Learning: The High-Interest Credit Card of Technical Debt" [Google; paper; 2014](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/43146.pdf)
- *cult*: "Hidden Technical Debt in Machine Learning Systems" [Google; paper; 2015-01](https://proceedings.neurips.cc/paper/2015/file/86df7dcfd896fcaf2674f757a2463eba-Paper.pdf)
- *cult*: "The ML Test Score: A Rubric for ML Production Readiness and Technical Debt Reduction" [Google; paper; 2017](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/aad9f93b86b7addfea4c419b9100c6cdd26cacea.pdf)
- *introductionary*: "Rules of Machine Learning: Best Practices for ML Engineering (43 rules)" [Google; article & YouTube; 2018-10](https://developers.google.com/machine-learning/guides/rules-of-ml)
- *cult*: "Continuous Delivery for Machine Learning (CD4ML)" [Martin Fowler; article; 2019-09](https://martinfowler.com/articles/cd4ml.html)

### Platform Architectures
- *introductionary*: "Building an ML Platform from Scratch: Live Coding Session" [MLOps Community ; YouTube; 2021](https://www.youtube.com/watch?v=s8Jj9gzQ3xA)
- *introductionary*: "Building a CI/ CD Machine Learning Pipeline" [Cloud Guru; YouTube; 2021-06](https://www.youtube.com/watch?v=XoXvX8MyW8M)
- "The Post Modern Data Stack" [Jacopo Tagliabue; YouTube; 2022-04](https://www.youtube.com/watch?v=5kHDb-XGHtc&ab_channel=JacopoTagliabue)
- "Fireside chat #3: Reasonable Scale Machine Learning -- You're not Google and it's totally OK" [Outerbounds; YouTube; 2022-06](https://www.youtube.com/watch?v=SAal0hqqE74&ab_channel=Outerbounds)



## Testing and Continous Integration (CI)

- "Building Continuous Integration Services for Machine Learning" [Microsoft & ETH; paper; 2020-08](https://pages.cs.wisc.edu/~wentaowu/papers/kdd20-ci-for-ml.pdf)

## Tools

### General
- "A curated list of MLOps projects" [MLOps.toys](https://mlops.toys/feature-store)

### Data
- [DVC (git for data)](https://dvc.org/)
- [dbt (data build tool)](https://docs.getdbt.com/docs/introduction) - ELT instead of ETL
- [Feast (feature store)](https://docs.feast.dev/)
  - Using [Redis](https://redis.com/blog/building-feature-stores-with-redis-introduction-to-feast-with-redis/)

### Frameworks: orchestrate MLOps
- [MetaFlow](https://docs.metaflow.org/introduction/what-is-metaflow): a python library to manage real-life data science projects, [Outerbounds](https://outerbounds.com/)
- [MLRun](https://docs.mlrun.org/en/latest/) 
- [KubeFlow](https://www.kubeflow.org/docs/started/introduction/) - ML workflows on Kubernetes

### MLOps platforms: Lifecyle Management & Monitoring etc.
- [Weights&Biases](https://wandb.ai/)
- [Neptune.AI](https://neptune.ai/home)
- [Comet](https://www.comet.com/site/)
- [MLFlow](https://mlflow.org/docs/latest/index.html) - open source


 
## Cloud Use Cases
 - Comparison of AWS, Google and Azure cloud providers [Convergence: Machine-learning and cloud technology blog; blogpost; 2014-10](https://aawasthi.blogspot.com/2014/10/cloud-nomenclature-aws-google-azure.html)
 - Data Engineering on Google Cloud, Video Course [Google; YouTube; 2021-11](https://www.youtube.com/watch?v=7TYLYjaHB64&list=PLmI_IVYHB9Fred0mR-280Uro9HOH9Lo98)
