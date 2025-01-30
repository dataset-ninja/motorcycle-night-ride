Dataset **Motorcycle Night Ride** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzM0NDFfTW90b3JjeWNsZSBOaWdodCBSaWRlL21vdG9yY3ljbGUtbmlnaHQtcmlkZS1EYXRhc2V0TmluamEudGFyIiwgInNpZyI6ICJQWVNDU1BGUjZCeU1yaStQWEZhejZrZDV0ZE04MmV4SnhhWFc1cE8yd1Z3PSJ9)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Motorcycle Night Ride', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/sadhliroomyprime/motorcycle-night-ride-semantic-segmentation/download?datasetVersionNumber=2).