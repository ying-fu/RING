# Grayscale-Assisted RGB Image Conversion from Near-Infrared Images

We provide the Pytorch implementation of "Grayscale-Assisted RGB Image Conversion from Near-Infrared Images"

## Requirments
1. Ubuntu 16.04
2. CUDA 9.1
3. pytorch 1.7.1

## Testing

CUDA_VISIBLE_DEVICES=7  python test.py \
--dataroot Datasets/ \
--name try_first \
--test_epoch best \
