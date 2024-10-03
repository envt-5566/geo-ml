# geo-ml

## Local development

### Docker

Build the local development image:

```
docker build -t envt-5566 .
```

Launch the container:

```
docker run -it --rm \
  -p 8888:8888 \
  -v "${PWD}":/home/jovyan/work \
  envt-5566
```

## Colab deployment

These notebooks can be run from Google Colab via the following URLs:

* Introduction to ML: https://colab.research.google.com/github/envt-5566/geo-ml/blob/main/notebooks/ml-introduction.ipynb
* Evaluating geospatial ML models: https://colab.research.google.com/github/envt-5566/geo-ml/blob/main/notebooks/evaluating-ml-models.ipynb
* Practice exercise 1: https://colab.research.google.com/github/envt-5566/geo-ml/blob/main/notebooks/practice-exercise-1.ipynb