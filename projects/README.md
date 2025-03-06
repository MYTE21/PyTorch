# 🗂️ PyTorch Projects

There are 5 hands-on projects to understand and apply PyTorch syntax in real-world tasks.
1. Tabular Classification.
2. Image Classification Using Convolutional Neural Network (CNN).
3. Image Classification Using Pre-trained Models.
4. Audio Classification.
5. Text Classification Using BERT.

We can download the datasets directly from Kaggle using [Opendatasets](https://pypi.org/project/opendatasets/):
* Install opendatasets:
    ```bash
    pip install opendatasets --quiet
    ```
* Downloading datasets from Kaggle:
    ```python
    import opendatasets as od
    od.download("<kaggle-dataset-link>")
    ```

## Tabular Classification
* Dataset: [Rice type classification](https://www.kaggle.com/datasets/mssmartypants/rice-type-classification).

It's a binary classification dataset. The rice is either Jasmin - 1 or Gonen - 0. I think this maybe good or bad 
quality rice.


Attributes: 
1. id (❌ We should remove this as it doesn't represent anything)
2. Area 
3. MajorAxisLength
4. MinorAxisLength 
5. Eccentricity 
6. ConvexArea 
7. EquivDiameter 
8. Extent 
9. Perimeter 
10. Roundness 
11. AspectRation 
12. Class

