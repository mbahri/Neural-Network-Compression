# A Paper List for Neural-Network-Compression
This is a paper list for neural network compression techniques such as quantization, pruning, and distillation. Most of the papers in the list are about quantization of CNNs. Only official codes are crosslinked.

# Paper List


## Quantization
- Binarized Neural Networks: Training Deep Neural Networks with Weights and Activations Constrained to +1 or -1, arXiv 2016, [[paper]](https://arxiv.org/abs/1602.02830), [[code(Theano)]](https://github.com/MatthieuCourbariaux/BinaryNet) [[code(Torch-7)]](https://github.com/itayhubara/BinaryNet), [[code(Pytorch)]](https://github.com/itayhubara/BinaryNet.pytorch), [[code(Tensorflow)]](https://github.com/itayhubara/BinaryNet.tf)

- XNOR-Net: ImageNet Classification Using Binary Convolutional Neural Networks, ECCV 2016, [[paper]](https://link.springer.com/chapter/10.1007/978-3-319-46493-0_32), [[code(Torch-7)]](https://github.com/allenai/XNOR-Net)
- DoReFa-Net: Training Low Bitwidth Convolutional Neural Networks with Low Bitwidth Gradients, arXiv 2016, [[paper]](https://arxiv.org/abs/1606.06160), [[code(Tensorflow)]](https://github.com/tensorpack/tensorpack/tree/master/examples/DoReFa-Net)
- Deep Learning With Low Precision by Half-Wave Gaussian Quantization, CVPR 2017, [[paper]](http://openaccess.thecvf.com/content_cvpr_2017/html/Cai_Deep_Learning_With_CVPR_2017_paper.html), [[code(caffe)]](https://github.com/zhaoweicai/hwgq)
- Ternary Weight Networks, NIPS workshop 2016, [[paper]](https://arxiv.org/abs/1605.04711), [[code(caffe)]](https://github.com/fengfu-chris/caffe-twns)
- Trained Ternary Quantization, ICLR 2017, [[paper]](https://openreview.net/forum?id=S1_pAu9xl&noteId=S1_pAu9xl), [[code(Tensorflow)]](https://github.com/czhu95/ternarynet)
- How to train a compact binary neural network with high accuracy?, AAAI 2017, [[paper]](https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/viewPaper/14619)
- Towards Accurate Binary Convolutional Neural Network, NIPS 2017, [[paper]](http://papers.nips.cc/paper/6638-towards-accurate-binary-convolutional-neural-network)
- Network Sketching: Exploiting Binary Structure in Deep CNNs, CVPR 2017, [[paper]](http://openaccess.thecvf.com/content_cvpr_2017/html/Guo_Network_Sketching_Exploiting_CVPR_2017_paper.html)
- WRPN: Wide Reduced-Precision Networks, ICLR 2018, [[paper]](https://openreview.net/forum?id=B1ZvaaeAZ&noteId=B1ZvaaeAZ)
- PACT: Parameterized Clipping Activation for Quantized Neural Networks, arXiv 2018, [[paper]](https://arxiv.org/abs/1805.06085)
- Bi-Real Net: Enhancing the Performance of 1-bit CNNs with Improved Representational Capability and Advanced Training Algorithm, ECCV 2018, [[paper]](http://openaccess.thecvf.com/content_ECCV_2018/html/zechun_liu_Bi-Real_Net_Enhancing_ECCV_2018_paper.html), [[code(caffe)]](https://github.com/liuzechun/Bi-Real-net)
- Alternating Multi-bit Quantization for Recurrent Neural Networks, ICLR 2018, [[paper]](https://openreview.net/forum?id=S19dR9x0b)
- NICE: Noise Injection and Clamping Estimation for Neural Network Quantization, arXiv 2018, [[paper]](https://arxiv.org/abs/1810.00162)
- True Gradient-Based Training of Deep Binary Activated Neural Networks Via Continuous Binarization, ICASSP 2018, [[paper]](https://ieeexplore.ieee.org/abstract/document/8461456/)
- Model compression via distillation and quantization, ICLR 2018, [[paper]](https://openreview.net/forum?id=S1XolQbRW), [[code(Pytorch)]](https://github.com/antspy/quantized_distillation)
- Apprentice: Using Knowledge Distillation Techniques To Improve Low-Precision Network Accuracy, ICLR 2018, [[paper]](https://openreview.net/forum?id=B1ae1lZRb&noteId=B1ae1lZRb)
- Training and Inference with Integers in Deep Neural Networks, ICLR 2018, [[paper]](https://openreview.net/forum?id=HJGXzmspb), [[code(Tensorflow)]](https://github.com/boluoweifenda/WAGE)
- Heterogeneous Bitwidth Binarization in Convolutional Neural Networks, NIPS 2018, [[paper]](http://papers.nips.cc/paper/7656-heterogeneous-bitwidth-binarization-in-convolutional-neural-networks)
- An empirical study of Binary Neural Networks' Optimisation, ICLR 2019, [[paper]](https://openreview.net/forum?id=rJfUCoR5KX)
- Accurate and Efficient 2-bit Quantized Neural Networks, SysML 2019, [[paper]](https://www.sysml.cc/doc/2019/168.pdf)
- Learning to Quantize Deep Networks by Optimizing Quantization Intervals With Task Loss, CVPR 2019, [[paper]](http://openaccess.thecvf.com/content_CVPR_2019/html/Jung_Learning_to_Quantize_Deep_Networks_by_Optimizing_Quantization_Intervals_With_CVPR_2019_paper.html)
- Structured Binary Neural Networks for Accurate Image Classification and Semantic Segmentation, CVPR 2019, [[paper]](http://openaccess.thecvf.com/content_CVPR_2019/html/Zhuang_Structured_Binary_Neural_Networks_for_Accurate_Image_Classification_and_Semantic_CVPR_2019_paper.html)
- ProxQuant: Quantized Neural Networks via Proximal Operators, ICLR 2019, [[paper]](https://openreview.net/forum?id=HyzMyhCcK7), [[code(Pytorch)]](https://github.com/allenbai01/ProxQuant)
- Circulant Binary Convolutional Networks: Enhancing the Performance of 1-Bit DCNNs With Circulant Back Propagation, CVPR 2019, [[paper]](http://openaccess.thecvf.com/content_CVPR_2019/html/Liu_Circulant_Binary_Convolutional_Networks_Enhancing_the_Performance_of_1-Bit_DCNNs_CVPR_2019_paper.html)
- Learning Channel-Wise Interactions for Binary Convolutional Neural Networks, CVPR 2019, [[paper]](http://openaccess.thecvf.com/content_CVPR_2019/html/Wang_Learning_Channel-Wise_Interactions_for_Binary_Convolutional_Neural_Networks_CVPR_2019_paper.html)
- Quantization Networks, CVPR 2019, [[paper]](http://openaccess.thecvf.com/content_CVPR_2019/html/Yang_Quantization_Networks_CVPR_2019_paper.html)
- BNN+: Improved Binary Network Training, arXiv 2019, [[paper]](https://arxiv.org/abs/1812.11800)
- Regularizing Activation Distribution for Training Binarized Deep Networks, CVPR 2019, [[paper]](http://openaccess.thecvf.com/content_CVPR_2019/html/Ding_Regularizing_Activation_Distribution_for_Training_Binarized_Deep_Networks_CVPR_2019_paper.html), [[code(Pytorch)]](https://github.com/ruizhoud/DistributionLoss)

## Pruning

## Distillation

## Separable convolution

## Understanding STE

## etc


# Copyright 
By Hyungjun Kim (hyungjunkim94@gmail.com) from Pohang University of Science and Technology (POSTECH).  