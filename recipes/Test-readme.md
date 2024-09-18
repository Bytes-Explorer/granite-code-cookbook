<h1 align="center">Data Prep Kit</h1>

[Data Prep Kit]((https://github.com/IBM/data-prep-kit)) is a toolkit for streamlining data preparation for developers looking to build LLM-enabled applications via fine-tuning, RAG or instruction-tuning. Data Prep Kit contributes a set of modules that the developer can get started with to easily build data pipelines suitable for their use case. These modules have been tested while producing pre-training datasets for the Granite open source LLM models [Granite models](https://huggingface.co/ibm-granite).

The modules are built on common frameworks (for Spark and Ray), called the data processing library that allows the developers to build new custom modules that readily scale across a variety of runtimes.

![alt text](Data-prep-kit-diagram.png)

Features of the toolkit: 

- Supports both code and natural language modalities in a single framework.
- It offers 20+ [data prep module](transforms) ranging from data ingestion, data quality, cleaning, data chunking and other data transformations.
- Provides scale flexibility with support for various run times: Python, Ray, Spark and KFP on Ray, targeting laptop-scale to datacenter-scale processing.
- It provides [example data processing pipelines]([examples](https://github.com/IBM/data-prep-kit/tree/dev/examples/notebooks)) that can help you get started quickly. 
- It provides the [Data processing library](data-processing-lib/ray) to enable contribution of new custom modules targeting new use cases without needing extensive Ray or Spark expertise.
- It provides automation via kubeflow pipelines. 



