Dataset **Drone Dataset (UAV)** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMjgzN19Ecm9uZSBEYXRhc2V0IChVQVYpL2Ryb25lLWRhdGFzZXQtKHVhdiktRGF0YXNldE5pbmphLnRhciIsICJzaWciOiAiTUdveG1yT1BKWXoyRkpTV0ZBRGFnakdSS3Bpb3hIbS9UeVk5STBWYWdTST0ifQ==?response-content-disposition=attachment%3B%20filename%3D%22drone-dataset-%28uav%29-DatasetNinja.tar%22)

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

