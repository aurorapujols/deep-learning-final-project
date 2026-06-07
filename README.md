# Deep Learning Course: Final Project

In this repository, we have the code, results, report and presentation for the final project report.

*Authors:* **Clara Oberle Melero** i **Aurora Pujols Rial**

## Reproducibility

We have all the code in the [`final-project-code.ipynb`](/final-project-code.ipynb) notebook. 

### Kaggle
We created it and executed it in Kaggle, where we also needed to put our [dataset](https://www.kaggle.com/datasets/aurorapujolsrial/ck-dataset-facial-expression-images). The code was executed with a GPU T4 x2.

To import in Kaggle, a notebook can be importet directly from the file we provide. The dataset needs to be specifically added under the `Input` tab at the right bar of the notebook editing view. It is public so there should be no problem to access it.

### Google Colab
To reproduce in Google Colab, the kaggle dataset can be downloaded. Then, mounting the data into a Google Colab notebook and by changing the `data_path` and `results_path` to the corresponding ones.

Cell 2 should be uncommented, and cell 3 not executed. Additionally, cell 67 only needed to be executed once for feature extraction and generation of the mel-spectrograms and MFCC features `.npy` files. These are already in the Kaggle dataset.

### CSV filenames
There might be some mismatch in the filenames stored in the `features.csv` file of the dataset. If it happens, the path in each row and column needs to change and this is done in cell 73.

## Report
The project explanation, methodology, results, discussions and conclusions are available in the [report](/team_xi_project_report.pdf).

## Presentation
The [presentation slides](/team_xi_project_presentation.pdf) are available in pdf format.

## Results

All results we obtained are available in the [results](/results/) folder. It includes images, plots, models, and the images we put together for the final report (as well as two images [image1](/results/CNN/FCNN_architecture.png) and [image2](/results/CNN/CNN_attention.png) that were obtained from reference [5]).