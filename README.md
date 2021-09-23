# Get started with CML API

In addition to the UI interface, Cloudera Machine Learning provides an API to interact with the platform programmatically. This notebook demonstrates how to work with the API.

The CML API can be used to interact with projects, jobs, models, and applications. It uses revokable user API keys to handle authorization. In this project, we use the CML API Python client to make requests and manipulate the responses.

For more information about getting started with the API, please refer to our [public documentation](https://docs.cloudera.com/machine-learning/cloud/api/topics/ml-api-v2.html).

## Deploying on Cloudera Machine Learning (CML)
______

There are three ways to launch this notebook on CML:

1. **From Prototype Catalog** - Navigate to the Prototype Catalog in a CML workspace, select the "Get started with CML API" tile, click "Launch as Project", click "Configure Project"
2. **As ML Prototype** - In a CML workspace, click "New Project", add a Project Name, select "ML Prototype" as the Initial Setup option, copy in the repo URL, click "Create Project", click "Configure Project"
3. **Manual Setup** - In a CML workspace, click "New Project", add a Project Name, select "Git" as the Initial Setup option, copy in the repo URL, click "Create Project".

Once the project has been initialized in a CML workspace, run the notebook by starting a Python 3 Jupyter notebook server session. All library and dependencies are installed inline in the notebook.