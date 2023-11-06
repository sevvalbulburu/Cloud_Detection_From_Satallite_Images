# Cloud_Detection_U-Net

## Documentation

- [Article](/Doc/Article.pdf)
- [Paper](/Doc/Paper.pdf)
- [Paper with Turnitin](/Doc/Paper_Turnitin_Result.pdf)
- [Video Representation](https://drive.google.com/file/d/1crRzMjeCqPOINIVaqHGycWWxyhWkVLg0/view)

## Dependencies
- Python 3.10.9 is used while development and recommended. The code can be executed with Jupyter or a similar IDE. For the use of Jupyter Notebook, it's recommended to download Anaconda.

- Install libraries by typing:
```
$ pip3 install -r requirements.txt
```

- To accelerate model training, CUDA and CuDNN installations should be performed to enable and optimize GPU usage.

## Database

Landsat 8 satellite imagery has been used as a dataset.

The dataset is available on Kaggle before being uploaded to the hub.

Kaggle link: https://www.kaggle.com/datasets/sorour/38cloud-cloud-segmentation-in-satellite-images

With the help of the Hub using a Python library, the pre-uploaded dataset can be fetched in the code.

Link to the dataset fetched in the code: hub://margauxmforsythe/38-cloud-segmentation

### Collaboration
Collaborated with [Alperen Ölçer](https://github.com/Alperenlcr)
