Dataset **Brackish Underwater** can be downloaded in Supervisely format:

 [Download](https://assets.supervise.ly/supervisely-supervisely-assets-public/teams_storage/U/z/BA/ZNSr9eNGRH1By3QSq6xuDsLJNhAhJWpXk1CG4iwldvhZr080DOXhuGgMwMBAF8j0cpRIW5C1N5jcPLu8RTjYpEuFk9FY4ZbzQfHIBpSkZiz0yJBDBW6gvnnM9i2P.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Brackish Underwater', dst_path='~/dtools/datasets/Brackish Underwater.tar')
```
The data in original format can be 🔗[downloaded here](https://universe.roboflow.com/brad-dwyer/brackish-underwater/dataset/2/download/coco)