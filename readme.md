# Apps analysis

## 1. Introduction

This is an exersice to analyze the apps data in the Google Play Store and the App Store. The goal is to normalize and merge the data to analyze different aspects of the apps.

## 2. Data

The data used to this analysis can be found on Kaggle:

- https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps

- https://www.kaggle.com/datasets/gauthamp10/apple-appstore-apps

In order to not commit the full data to the repository, the data is not included in the repository. The data can be downloaded from the links above and placed in the `data` folder. On the data folder you can find a sample of the data, to make this example executable, and also on the first lines of the Jupiter notebook you can find a flag to switch between sample or real data parsing.

## 3. Execution

The analysis is done in a Jupyter notebook. The notebook is located in the `jupyter_notebooks` folder. The notebook is self contained and can be executed from the first cell to the last one.
Also the environment to run the notebook is described on a docker-compose file. The docker-compose file is located in the root folder of the repository. To run the notebook with docker-compose, you need to have docker and docker-compose installed on your machine. Then you can run the following command:

```bash
docker-compose up
```

This will start a Jupyter server on your machine. You can access the server on the following URL:

http://127.0.0.1:8888/lab

## 4. Results

If you don't want to run the notebook, github allows you to visualize the notebook, and the precalculated results. You can access the notebook on the following URL:

https://github.com/damdev/apps_analysis/blob/main/jupyter_notebooks/apps_analysis.ipynb