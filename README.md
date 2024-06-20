# Grayscale-Assisted RGB Image Conversion from Near-Infrared Images

We provide the Pytorch implementation of "Grayscale-Assisted RGB Image Conversion from Near-Infrared Images"

## Requirments
1. Ubuntu 16.04
2. CUDA 9.1
3. pytorch 1.7.1

## Training
CUDA_VISIBLE_DEVICES=0  python train.py \
--dataroot Datasets \
--name try_first \
--batch_size 2 \
--lr 0.001 \
--epochs 501 \
--ngf 50 \
--n_epochs 200 \
--n_epochs_decay 300 \


## Testing

CUDA_VISIBLE_DEVICES=0  python test.py \
--dataroot Datasets \
--name try_first \
--test_epoch best \
