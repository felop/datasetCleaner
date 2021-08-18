# datasetCleaner
A small library that deletes every corrupted image in a dataset

[![downloads per month](https://img.shields.io/pypi/dm/datasetCleaner?color=red)](https://pypi.org/project/datasetCleaner/)  ![python version](https://img.shields.io/pypi/pyversions/datasetCleaner)  ![license](https://img.shields.io/pypi/l/datasetCleaner)  [![version](https://img.shields.io/pypi/v/datasetCleaner)](https://pypi.org/project/datasetCleaner/)

### 🛠 Installation
```python
pip install datasetCleaner
```

### 🛠 How to use it :
```python
datasetCleaner.clean(path)
```
this python function removes all corrupted images in the path. <br /> (⚠️WARNING⚠️ : this command deletes all non-image files in the directory, such as text files, videos and folders.
