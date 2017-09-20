# Document Collection Analysis

**[Detailed documentation (TODO)](./README.md)**

This scenario demonstrates how to summarize and analyze a large collection of documents, including techniques such as phrase learning, topic modeling, and topic model analysis using Azure ML Workbench. Azure Machine Learning Workbench provides for easy scale up for very large document collection, and provides mechanisms to train and tune models within a variety of compute contexts, ranging from local compute to Data Science Virtual Machines to Spark Cluster. Easy development is provided through Jupyter notebooks within Azure Machine Learning Workbench.

## Link to the Gallery GitHub repository

The public GitHub repository for this real world scenario contains all materials, including code samples, needed for this example:

[https://github.com/Azure/MachineLearningSamples-DocumentCollectionAnalysis](https://github.com/Azure/MachineLearningSamples-DocumentCollectionAnalysis)

## Overview

With a large amount of data (especially unstructured text data) collected every day, a significant challenge is to organize, search, and understand vast quantities of these texts. This document collection analysis scenario demonstrates an efficient and automated end-to-end workflow for analyzing large document collection and enabling downstream NLP tasks.

The key elements delivered by this scenario are:

1. Learning salient multi-words phrase from documents.

1. Discovering underlying topics presented in the document collection.

1. Representing documents by the topical distribution.

1. Presenting methods for organizing, searching, and summarizing documents based on the topical content.

The methods presented in this scenario could enable a variety of critical industrial workloads, such as discovery of topic trends anomaly, document collection summarization, and similar document search. It can be applied to many different types of document analysis, such as government legislation, news stories, product reviews, customer feedbacks, and scientific research articles.

The machine learning techniques/algorithms used in this scenario include:

1. Text processing and cleaning

1. Phrase Learning

1. Topic modeling

1. Corpus summarization

1. Topical trends and anomaly detection

## Prerequisites

The prerequisites to run this example are as follows:

* Make sure that you have properly installed [Azure Machine Learning Workbench (TODO)](./README.md) by following the [quick start installation guide (TODO)](./README.md).

* This example could be run on any compute context. However, it is recommended to run it on a multi-core machine with at least of 16-GB memory and 5-GB disk space.

## Create a new Workbench project

Create a new project using this example as a template:
1.	Open Azure Machine Learning Workbench
2.	On the **Projects** page, click the **+** sign and select **New Project**
3.	In the **Create New Project** pane, fill in the information for your new project
4.	In the **Search Project Templates** search box, type "Document Collection Analysis" and select the template
5.	Click **Create**

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (for example, label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information, see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
