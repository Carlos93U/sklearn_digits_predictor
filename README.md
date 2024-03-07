# SKLEARN_DIGITS_PREDICTOR | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/800px-Python-logo-notext.svg.png" height=20> | <img src="https://i.postimg.cc/cHqB5VtL/scikit-learn-logo.png" height=20>| <img src="https://pandas.pydata.org/static/img/pandas_white.svg" height=20>  | <img src="https://i.postimg.cc/m2dwfTdm/numpy-logo.png" height=20> |  <img src="https://matplotlib.org/_static/logo_dark.svg" height=20> | <img src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" height=20> | [<img src="https://static-00.iconduck.com/assets.00/github-icon-2048x1988-jzvzcf2t.png" height=20> ](https://github.com/Carlos93U) | [<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/640px-LinkedIn_logo_initials.png" height=20>](https://www.linkedin.com/in/juan-carlos-huillcas/) |

## 1. Resume

This project employs machine learning algorithms to identify digits from 0 to 9. The necessary data and algorithms are within the sklearn library. Essential procedures are carried out for applications such as optical character recognition in the automotive industry.

[![ocr-intro-1.webp](https://i.postimg.cc/3RC8JJ00/ocr-intro-1.webp)](https://postimg.cc/tZJQBb59)

## 2. Data Set Characteristics

The load_digits dataset from sklearn contains images of handwritten digits from 0 to 9 in an 8x8 pixel grayscale format. With 1797 samples, each image has a label indicating the corresponding digit. Widely used in machine learning for classification and pattern recognition, each image is represented as a matrix of pixels with grayscale intensities ranging from 0 to 16.

| Characteristic | Value |
|--------------|--------------|
| `Number of Instances`    | 1797    |
| `Number of Attributes`    | 64    |
| `Attribute Information`    | 8x8 image of integer pixels in the range 0 to 16    |
| `Missing Attribute Values`    | None    |

The multiclass logistic regression model from sklearn is employed using the load_digits data. The notebook includes all the necessary code to load, analyze, and subsequently train and test the model.

## 3. Setting up

*Create a virtual enviroment with:*

```
python3 -m venv env

```
*Activate virtual enviroment:*

```
source env/bin/activate
```

*Install requirements*

```
pip install -r requirements.txt
```

## 4. Running

* *Open a Jupiter Notebook:*
* *Run All*
* *See outputs*

[![output.png](https://i.postimg.cc/gJ7ny6Tf/output.png)](https://postimg.cc/9RGmCzVp)

## 5. Libraries and documentation

* [Python](https://www.python.org/doc/)
* [sklearn](https://scikit-learn.org/stable/)
* [pandas](https://pandas.pydata.org/)
* [numpy](https://numpy.org/)
* [matplotlib](https://matplotlib.org/)
* [seaborn](https://seaborn.pydata.org/index.html#)