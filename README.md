
# A Hyperspectral Image Classification Framework with Spatial Pixel Pair Features
Lingyan Ran 1
, Yanning Zhang 1,*, Wei Wei 1,* and Qilin Zhang 2
1 School of Computer Science and Engineering, Northwestern Polytechnical University, Xi’an 710072, China;
lingyanran@gmail.com
2 Highly Automated Driving Team, HERE Technologies Automotive Division, Chicago, IL 60606, USA;
samqzhang@gmail.com
* Correspondence: ynzhang@nwpu.edu.cn (Y.Z.); weiweinwpu@nwpu.edu.cn (W.W.);
Tel.: +86-130-6039-9678 (Y.Z.); +86-137-7253-8134 (W.W.)
Received: 8 August 2017; Accepted: 13 October 2017; Published: 23 October 2017

## Abstract: 

During recent years, convolutional neural network (CNN)-based methods have been
widely applied to hyperspectral image (HSI) classification by mostly mining the spectral variabilities.
However, the spatial consistency in HSI is rarely discussed except as an extra convolutional channel.
Very recently, the development of pixel pair features (PPF) for HSI classification offers a new way
of incorporating spatial information. In this paper, we first propose an improved PPF-style feature,
the spatial pixel pair feature (SPPF), that better exploits both the spatial/contextual information
and spectral information. On top of the new SPPF, we further propose a flexible multi-stream
CNN-based classification framework that is compatible with multiple in-stream sub-network designs.
The proposed SPPF is different from the original PPF in its paring pixel selection strategy: only pixels
immediately adjacent to the central one are eligible, therefore imposing stronger spatial regularization.
Additionally, with off-the-shelf classification sub-network designs, the proposed multi-stream,
late-fusion CNN-based framework outperforms competing ones without requiring extensive network
configuration tuning. Experimental results on three publicly available datasets demonstrate the
performance of the proposed SPPF-based HSI classification framework.



REF:https://www.mdpi.com/1424-8220/17/10/2421
