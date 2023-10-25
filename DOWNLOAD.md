Dataset **Drone Dataset (UAV)** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/d/d/N0/SXA2FaIAdQAye5jqOVuzi4W0wb1Rd5Y4d1UavRZfxU3Uz7DPJD9jYw1RAuKDjCRHPmCzEqSVUlFblGyVAaR6DKMQfd2K2ABDJLDH3NY1dDLyNWuBGdIDFCFXUpNy.tar)

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

