# OpticalFlow
A collection of Optical Flow papers and code and some numbers.

| Network | Paper | Code | Year | Best for | Supervised/Unsupervised | Complexity | Sintel-clean EPE |
| --- | --- | --- | --- | --- | --- | --- | --- |
| FlowNet | https://arxiv.org/abs/1504.06852 | https://github.com/ClementPinard/FlowNetTorch , https://github.com/ClementPinard/FlowNetPytorch, https://github.com/aasharma90/FlowNet  | 2015 | Basic Optical Flow | Supervised | 32,070,472 parameters (FlowNetS), 32,561,032 parameters (FlowNetC) | --- |
| FlowNet 2.0 | https://arxiv.org/abs/1612.01925 | https://github.com/lmb-freiburg/flownet2, https://github.com/NVIDIA/flownet2-pytorch, https://github.com/sampepose/flownet2-tf, https://github.com/vt-vl-lab/pytorch_flownet2 | 2016 | Segmentation | Supervised | More than FlowNet | --- |
| SPyNet | https://arxiv.org/abs/1611.00850 | https://github.com/anuragranj/spynet, https://github.com/sniklaus/pytorch-spynet, https://github.com/anuragranj/spynet | Year | Fast Learning | Supervised | 1,200,250 parameters | 6.64 |
| DSTFlow | https://pdfs.semanticscholar.org/47bc/34ae6f5dc104bc289ae3bb4fa75ef75fbc21.pdf | --- | 2017 | Huge amount of Unlabeled Data  | Unsupervised | --- | --- |
| PWC-Net | https://arxiv.org/abs/1709.02371 | https://github.com/NVlabs/PWC-Net/tree/master/PyTorch, https://github.com/NVlabs/PWC-Net, https://github.com/sniklaus/pytorch-pwc | 2018 | Good Trade-Off Accuracy and Running Time | Supervised | Small Complexity | 3.45 |
| SelFlow | https://arxiv.org/pdf/1904.09117.pdf | https://github.com/ppliuboy/SelFlow,  | 2019 | No Labeled Data, Good Accuracy also for Data with Occlusions  | Unsupervised | Quite big but based on PWC-Net | 3.74 |
| PCLNet | https://arxiv.org/pdf/1907.11628.pdf | https://github.com/Kwanss/PCLNet | 2019 | With Unlabeled Data | Unsupervised | Big | --- |
