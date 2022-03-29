# change-detection-MSDC
A PyTorch implementation of [**A multiscale self-attention deep clustering for change detection in SAR images**]  in *IEEE Transactions on Geoscience and Remote Sensing*, 2021. Available

by Huihui Dong, Wenping Ma, Licheng Jiao, Fang Liu, Lingling Li.

Pytorch version=1.1.0 (Very important to our method beacuase the effect of randomly initialized parameters):
#you can directly use the following command to install
# Run Environmental installation
conda install pytorch==1.1.0 torchvision==0.3.0 cudatoolkit=10.0 -c pytorch

Run the code:
1. run:

```
$ dash main.sh
```
#Train the networks and obtain the detection result

cite：
@article{dong2021multiscale,
  title={A multiscale self-attention deep clustering for change detection in SAR images},
  author={Dong, Huihui and Ma, Wenping and Jiao, Licheng and Liu, Fang and Li, LingLing},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  volume={60},
  pages={1--16},
  year={2021},
  publisher={IEEE}
}
