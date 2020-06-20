---
layout: default
title: Kubernetes
order_n: 3
has_children: true
---

To get started using kubernetes, we defer to the [kubernetes documentation](https://kubernetes.io/docs/tasks/).

Kubernetes can be useful in your ML workflows if you need access to other infrastructure resources.  For example:
   - Deploying and serving models with a [service mesh](https://en.wikipedia.org/wiki/Service_mesh)
   - Deploying and serving arbitrary applications, such as Jupyter Notebooks or documentation sites.
   - Accessing resources that are visible from your internal k8s cluster, such as:
      - Databases, i.e. Presto, Hive
      - Storage, i.e. HDFS
      - Distributed data processing, such as Dask or Spark
      - Specialized computing such as GPUs.
      - Integration with experiment tracking systems.
   - Access to [secrets](https://kubernetes.io/docs/tasks/inject-data-application/distribute-credentials-secure/).
   - Native resource management and kubernetes for scalability and resiliance.
   - Interoperability with machine learning or data pipelines, such as [Argo](https://argoproj.github.io/), [MLFlow](https://mlflow.org/), [Prefect](https://www.prefect.io/), etc.
   - ... and much more.
