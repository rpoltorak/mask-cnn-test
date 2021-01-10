# CNN for mask recognition

## Data preparation

1. Download [RMFD dataset](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset) (first part - RMFD)
2. Extract .zip file to `data` directory.
3. Move the content to the following directiories:
   - AFDB_face_dataset -> data/no_mask
   - AFDB_masked_face_dataset -> data/mask

## Run project

Run the following commands:

```Shell
virtualenv env --python=3.8

source env/bin/activate

pip3 install -r requirements.txt

jupyter notebook
```

## Requirements

- Python 3.8 (3.9 is not supported because of Tensorflow)

Solution based on:

- [Real-World Masked Face Dataset（RMFD）](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset)
- [Medium post: How I built a Face Mask Detector for COVID-19 using PyTorch Lightning](https://towardsdatascience.com/how-i-built-a-face-mask-detector-for-covid-19-using-pytorch-lightning-67eb3752fd61)
