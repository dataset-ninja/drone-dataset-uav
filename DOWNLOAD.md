Dataset **Drone Dataset (UAV)** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzI4MzdfRHJvbmUgRGF0YXNldCAoVUFWKS9kcm9uZS1kYXRhc2V0LSh1YXYpLURhdGFzZXROaW5qYS50YXIiLCAic2lnIjogIktnUWprREVaTm50TEJiYVZwLzE1SDgwK0dHQWVKSXZwUXlZYkRCbnY2cnM9In0=)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Drone Dataset (UAV)', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

