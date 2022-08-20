# PICTOR-YOLO


# **Construction Object Detection**


### Article

[**Deep Convolutional Networks for Construction Object Detection Under Different Visual Conditions**](https://www.frontiersin.org/articles/10.3389/fbuil.2020.00097/full) \
Nipun D. Nath, Amir H. Behzadan\
Frontiers in Built Environment 6, pp. 97

Please cite the article if you use the dataset, model or method(s), or find the article useful in your research. Thank you!

### LaTeX citation:

```
@article{Nath2020,
    author  = {Nipun D. Nath and Amir H. Behzadan},
    title   = {Deep Convolutional Networks for Construction Object Detection Under Different Visual Conditions},
    journal = {Frontiers in Built Environment},
    volume  = {6},
    year    = {2020},
    pages   = {97}
```

## **Dataset**

### Dataset statisctics

The dataset (named **Pictor-v2**) contains 1,105 crowd-sourced and 1,402 web-mined images of buildings, equipment, and workers. Crowd-sourced and web-mined images contain 2,611 and 2,257 instances of workers, respectively. A brief statistics of the dataset is shown in the following figure.

<img src="extras/graphics/Fig-03.jpg" alt="Dataset" width="840" align="middle"/>

### Annotation example

**@TODO:** Please stay tuned!

### Download the crowd-sourced dataset

The crowd-sourced images and annotated labels can be found in these Google Drive folders:
- [Crowd-sourced images](https://drive.google.com/drive/folders/1cZHC_qz4qphXJT5dJTvkgvAgttoPp_Jd?usp=sharing).
- [Train, test, and validation labels](https://drive.google.com/drive/folders/1nD0bS41aP1lTz6rxmlNUuw1x9g4r4AQS?usp=sharing).

## **Methods**

The methodology presented in the paper is summarized in the following figure:

<img src="extras/graphics/Fig-02.jpg" alt="Methods/Approaches" width="840" align="middle"/>

## **Results**

- The mean-average-precision (mAP) of YOLO-v2 models in detecting classes:

<img src="extras/graphics/Fig-09.jpg" alt="Results" width="640" align="middle"/>

- The mean-average-precision (mAP) of YOLO-v3 models in detecting classes:

<img src="extras/graphics/Fig-10.jpg" alt="Results" width="640" align="middle"/>


## **Pre-trained Models**

Models trained on different combinations of Pictor-v2 dataset are available in the [Google Drive folder](https://drive.google.com/drive/folders/13UdlVcA4osdn-oABGN4NfY7dSdjqllqd?usp=sharing).

The folder contains following models:
- YOLO-v2 trained on crowd-sourced dataset.
- YOLO-v2 trained on web-mined dataset.
- YOLO-v2 trained on combined (crowd-sourced + web-mined) dataset.
- YOLO-v3 trained on crowd-sourced dataset.
- YOLO-v3 trained on web-mined dataset.
- YOLO-v3 trained on combined (crowd-sourced + web-mined) dataset (**BEST PERFORMING MODEL**).

## **Tutorials**

Please follow the notebooks in [tutorials](https://github.com/nipundebnath/pictor-ppe/blob/master/tutorials/) folder to learn more about:
- Building YOLO model from scratch using tensorflow 2.0
- Interpret YOLO output and convert to bounding boxes with class label and confidence score.