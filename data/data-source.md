# Data Source: Customer Segmentation Dataset

This dataset is used for customer segmentation tasks and can be found on Kaggle at the following link:

🔗 [Kaggle Dataset - Customer Segmentation](https://www.kaggle.com/datasets/yasserh/customer-segmentation-dataset/data)

## How to Download

You can download the dataset using the `kagglehub` Python package:

```python
import kagglehub

# Download the dataset
path = kagglehub.dataset_download("yasserh/customer-segmentation-dataset")

print("Path to dataset files:", path)
