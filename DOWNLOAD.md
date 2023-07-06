Dataset **Brackish Underwater** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/w/d/tC/Vl8mRPUdOz2KQungVSMV7Ib1UuNPuOjqFpwoZDfRDfk97Olfns4tyZur6jOyxqBQ0P1gmtPiIX7bAhFazVluvkoELBfqLGpUUFbfxLODtPyx9XxTeirMyYaBHYqH.tar)

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