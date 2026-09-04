# Basic AI Notebooks

This repository is a small collection of notebooks I made while learning different areas of AI and machine learning. The goal is not to build production models. The goal is to show that I understand the basic workflow for loading data, preparing it, building a model, training it, and checking the results.

## Notebooks

- `001_RiceTypeClassification.ipynb` - tabular binary classification with PyTorch.
- `002_AnimalFacesClassification.ipynb` - image classification with a small CNN.
- `003_transfer_learning_01.ipynb` - transfer learning with GoogLeNet.
- `004_Audio_Classification.ipynb` - audio classification using mel spectrograms.
- `005_Text_Classification.ipynb` - text classification using a small BERT model.

## Data

Some data is included directly in the repository so the notebooks can be opened and rerun without extra setup. The image notebook uses a local `afhq` folder. The transfer learning, audio, and text notebooks use small sample datasets included in their own folders.

## Environment

The notebooks were prepared with Python and common machine learning libraries:

- PyTorch
- torchvision
- pandas
- numpy
- scikit-learn
- matplotlib
- transformers

I used a local Conda environment while preparing and running the notebooks. If you use Transformers for the text notebook, a stable 4.x version is recommended.

## Notes

The datasets and epoch counts are kept small on purpose. This makes the notebooks easier to run on a normal laptop and easier to review on GitHub. The results are meant to show the workflow, not to claim high model performance.
