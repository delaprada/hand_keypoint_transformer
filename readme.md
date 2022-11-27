# Hand Keypoint Detection with Transformer -- Pytorch

This repository is mainly built upon Pytorch. We wish to use Transformer to realize hand keypoint detection on videos.

## TODO
- [ ] Add result
- [ ] Add visualization notebook

## Update
- 2022.11.27 Add source code and README.md


## Usage
Use [Resnet](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf) as backbone:
```
python train.py --cfg ./experiments/TP_R_256x192_d256_h1024_enc4_mh8.yaml
```
Use [HRNet](https://openaccess.thecvf.com/content_CVPR_2019/papers/Sun_Deep_High-Resolution_Representation_Learning_for_Human_Pose_Estimation_CVPR_2019_paper.pdf) as backbone:
```
python train.py --cfg ./experiments/TP_H_w48_256x192_stage3_1_4_d96_h192_relu_enc6_mh1.yaml
```