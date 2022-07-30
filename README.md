# Skin Pamper
    developed in Python using keras library, and classified skin lesions using the CNN, trained end-to-end from images directly, using only pixels values. 

## Dataset
[Skin Cancer MNIST: HAM10000](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000?select=HAM10000_images_part_2) a large collection of multi-source dermatoscopic images of pigmented lesions is available in Kaggle. The  required datasets is directly downloaded into workspace using `wget`

`HAM10000_metadata.csv`

    - RangeIndex: 10015 entries, 0 to 10014
    - Data columns (total 7 columns):

| # |   Column     |   Non-Null Count|  Dtype    |
|---|--------------|--------------   |  -----    |
| 0 | lesion_id    | 10015 non-null  |  object   |
| 1 | image_id     | 10015 non-null  |  object   |
| 2 | dx           | 10015 non-null  |  object   |
| 3 | dx_type      | 10015 non-null  |  object   |
| 4 | age          | 9958 non-null   |  float64  |
| 5 | sex          | 10015 non-null  |  object   |
| 6 | localization | 10015 non-null  |  object   |

`hmnist_28_28_RGB.csv`

    - RangeIndex: 10015 entries, 0 to 10014
    - Columns: 2353 entries, pixel0000 to label
    - dtypes: int64(2353)
    - this file contains pixel values of image by rows
