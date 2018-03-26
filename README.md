# Tranditional-Neural-transfer

In order to classify the papers I have read, I treated the articles in the following list as trandition-neural-transder, just for research convenience.
## A Taxonomy of Current Methods
### 1. "Slow" Neural Methods Based on `Image Optimization`
:ballot_box_with_check: [**A Neural Algorithm of Artistic Style**][[paper]](https://arxiv.org/abs/1508.06576)*(first neural style transfer paper)*

:star: **Code:**

*   [Torch-based](https://github.com/jcjohnson/neural-style)
*   [TensorFlow-based](https://github.com/anishathalye/neural-style)
*   [TensorFlow-based with L-BFGS optimizer support](https://github.com/cysmith/neural-style-tf)
*   [Caffe-based](https://github.com/fzliu/style-transfer) 
*   [Keras-based](https://github.com/titu1994/Neural-Style-Transfer)

:ballot_box_with_check: [**Image Style Transfer Using Convolutional Neural Networks**] [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf) *(CVPR 2016)*

:blue_book: [**Demystifying Neural Style Transfer**][[paper]](https://arxiv.org/abs/1701.01036)*(Theoretical Explanation)* *(IJCAI 2017)*

:star: **Code:**

*   [MXNet-based](https://github.com/lyttonhao/Neural-Style-MMD)

:blue_book: [**Stable and Controllable Neural Texture Synthesis and Style Transfer Using Histogram Losses**][[paper]](https://arxiv.org/abs/1701.08893)

:blue_book: [**Combining Markov Random Fields and Convolutional Neural Networks for Image Synthesis**][[paper]](https://arxiv.org/abs/1601.04589)*(CVPR 2016)*

### 2. "Fast" Neural Methods Based On `Model Optimization`
### 2.1 `Per-Style-Per-Model` "Fast" Neural Methods

:ballot_box_with_check: [**Perceptual Losses for Real-Time Style Transfer and Super-Resolution**][[paper]](https://arxiv.org/pdf/1603.08155.pdf)  *(ECCV 2016)*

:star: **Code:**

*   [Torch-based](https://github.com/jcjohnson/fast-neural-style)
*   [TensorFlow-based](https://github.com/lengstrom/fast-style-transfer)

:blue_book: [**Precomputed Real-Time Texture Synthesis with Markovian Generative Adversarial Networks**] [[Paper]](https://arxiv.org/pdf/1604.04382.pdf)  *(ECCV 2016)*

:star: **Code:**

*   [Torch-based](https://github.com/chuanli11/MGANs)

:blue_book: [**Texture Networks: Feed-forward Synthesis of Textures and Stylized Images**] [[Paper]](http://www.jmlr.org/proceedings/papers/v48/ulyanov16.pdf)  *(ICML 2016)*

:star: **Code:**

*   [TensorFlow-based](https://github.com/tgyg-jegli/tf_texture_net)

:blue_book: [**Improved Texture Networks: Maximizing Quality and Diversity in Feed-forward Stylization and Texture Synthesis**] [[Paper]](https://arxiv.org/pdf/1701.02096.pdf)  *(CVPR 2017)*

:star: **Code:**

*   [Torch-based](https://github.com/DmitryUlyanov/texture_nets)

:blue_book: [**Precomputed Real-Time Texture Synthesis with Markovian Generative Adversarial Networks**] [[Paper]](https://arxiv.org/pdf/1604.04382.pdf)  *(ECCV 2016)*

:star: **Code:**

*   [Torch-based](https://github.com/chuanli11/MGANs)

### 2.2 `Multiple-Style-Per-Model` "Fast" Neural Methods

:blue_book: [**A Learned Representation for Artistic Style**] [[Paper]](https://arxiv.org/pdf/1610.07629.pdf)  *(ICLR 2017)*

:star: **Code:**

*   [TensorFlow-based](https://github.com/tensorflow/magenta/tree/master/magenta/models/image_stylization)

:blue_book: [**Multi-style Generative Network for Real-time Transfer**] [[Paper]](https://arxiv.org/pdf/1703.06953.pdf)

:star: **Code:**

*   [PyTorch-based](https://github.com/zhanghang1989/PyTorch-Style-Transfer)
*   [Torch-based](https://github.com/zhanghang1989/MSG-Net)

:blue_book: [**StyleBank: An Explicit Representation for Neural Image Style Transfer**] [[Paper]](https://arxiv.org/pdf/1703.09210.pdf)  *(CVPR 2017)*

:blue_book: [**Diversified Texture Synthesis With Feed-Forward Networks**] [[Paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Li_Diversified_Texture_Synthesis_CVPR_2017_paper.pdf)  *(CVPR 2017)* 

:star: **Code:**

*   [Torch-based](https://github.com/Yijunmaverick/MultiTextureSynthesis)

### 2.3. Arbitrary-Style-Per-Model "Fast" Neural Methods

:blue_book: [**Fast Patch-based Style Transfer of Arbitrary Style**] [[Paper]](https://arxiv.org/pdf/1612.04337.pdf) 

:star: **Code:**

*   [Torch-based](https://github.com/rtqichen/style-swap)

:blue_book: [**Arbitrary Style Transfer in Real-time with Adaptive Instance Normalization**] [[Paper]](https://arxiv.org/pdf/1703.06868.pdf)  *(ICCV 2017)*

:star: **Code:**

*   [Torch-based](https://github.com/xunhuang1995/AdaIN-style)


## Slight Modifications of Current Methods

###  1. Modifications of "Slow" Neural Methods

:grey_question: [**Exploring the Neural Algorithm of Artistic Style**] [[Paper]](https://arxiv.org/pdf/1602.07188.pdf) 

:grey_question: [**Improving the Neural Algorithm of Artistic Style**] [[Paper]](https://arxiv.org/pdf/1605.04603.pdf) 

:grey_question: [**Preserving Color in Neural Artistic Style Transfer**] [[Paper]](https://arxiv.org/pdf/1606.05897.pdf) 

:grey_question: [**Controlling Perceptual Factors in Neural Style Transfer**] [[Paper]](https://arxiv.org/pdf/1611.07865.pdf)  *(CVPR 2017)* 

:star: **Code:**

*   [Torch-based](https://github.com/leongatys/NeuralImageSynthesis)

###  2. Modifications of "Fast" Neural Methods

:star: [**Instance Normalization：The Missing Ingredient for Fast Stylization**] [[Paper]](https://arxiv.org/pdf/1607.08022.pdf) 

:star: **Code:**

*   [Torch-based](https://github.com/DmitryUlyanov/texture_nets)

:grey_question: [**Depth-Preserving Style Transfer**] [[Paper]](https://github.com/xiumingzhang/depth-preserving-neural-style-transfer/blob/master/report/egpaper_final.pdf) 

:star: **Code:**

*   [Torch-based](https://github.com/xiumingzhang/depth-preserving-neural-style-transfer)

:grey_question: [**Depth-Aware Neural Style Transfer**]  *(NPAR 2017)*

## Extensions

:grey_question: [**Semantic Style Transfer and Turning Two-Bit Doodles into Fine Artwork**] [[Paper]](https://arxiv.org/pdf/1603.01768.pdf) 

:star: **Code:**

*   [Torch-based](https://github.com/alexjc/neural-doodle)

:grey_question: [**Painting Style Transfer for Head Portraits Using Convolutional Neural Networks**] [[Paper]](http://dl.acm.org/citation.cfm?id=2925968)  *(SIGGRAPH 2016)*

:grey_question: [**Son of Zorn's Lemma Targeted Style Transfer Using Instance-aware Semantic Segmentation**] [[Paper]](https://arxiv.org/pdf/1701.02357.pdf)  *(ICASSP 2017)*

:grey_question: [**Style Transfer for Anime Sketches with Enhanced Residual U-net and Auxiliary Classifier GAN**] [[Paper]](https://arxiv.org/pdf/1706.03319.pdf)

:grey_question: [**Artistic Style Transfer for Videos**] [[Paper]](https://arxiv.org/pdf/1604.08610.pdf)  *(GCPR 2016)*

:star: **Code:**

*   [Torch-based](https://github.com/manuelruder/artistic-videos)

:grey_question: [**DeepMovie: Using Optical Flow and Deep Neural Networks to Stylize Movies**] [[Paper]](https://arxiv.org/pdf/1605.08153.pdf) 

:grey_question: [**Characterizing and Improving Stability in Neural Style Transfer**] [[Paper]](https://arxiv.org/pdf/1705.02092.pdf))  *(ICCV 2017)*

:grey_question: [**Coherent Online Video Style Transfer**] [[Paper]](https://arxiv.org/pdf/1703.09211.pdf)  *(ICCV 2017)*  *(First end-to-end video style transfer?)*

:grey_question: [**Real-Time Neural Style Transfer for Videos**] [[Paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Huang_Real-Time_Neural_Style_CVPR_2017_paper.pdf)  *(CVPR 2017)* 

:grey_question: [**Deep Photo Style Transfer**] [[Paper]](https://arxiv.org/pdf/1703.07511.pdf)  *(CVPR 2017)*

:star: **Code:**

*   [Torch-based](https://github.com/luanfujun/deep-photo-styletransfer)
*   [TensorFlow-based](https://github.com/LouieYang/deep-photo-styletransfer-tf)

## Application

:grey_question: [**Prisma**](https://prisma-ai.com/) 

:grey_question: [**Ostagram**](https://ostagram.ru/) 

:star: **Code:**

*   [Website code](https://github.com/SergeyMorugin/ostagram)

:grey_question: [**Deep Forger**](https://deepforger.com/) 


## Application Papers

:grey_question: [**Bringing Impressionism to Life with Neural Style Transfer in Come Swim**] [[Paper]](https://arxiv.org/pdf/1701.04928.pdf) 

:grey_question: [**Imaging Novecento. A Mobile App for Automatic Recognition of Artworks and Transfer of Artistic Styles**] [[Paper]](https://www.micc.unifi.it/wp-content/uploads/2017/01/imaging900.pdf) 

## Blogs 

:grey_question: [**Caffe2Go**][https://code.facebook.com/posts/196146247499076/delivering-real-time-ai-in-the-palm-of-your-hand/]

:grey_question: [**Supercharging Style Transfer**][https://research.googleblog.com/2016/10/supercharging-style-transfer.html]

:grey_question: [**Issue of Layer Chosen Strategy**][http://yongchengjing.com/pdf/Issue_layerChosenStrategy_neuralStyleTransfer.pdf]

:grey_question: [**Picking an optimizer for Style Transfer**][https://blog.slavv.com/picking-an-optimizer-for-style-transfer-86e7b8cba84b]

## Exciting New Directions

:grey_question: **Character Style Transfer**

*   [**Awesome Typography: Statistics-based Text Effects Transfer**][[Paper]](https://arxiv.org/abs/1611.09026)  *(CVPR 2017)*

:star: **Code:**

*   [Matlab-based](https://github.com/williamyang1991/Text-Effects-Transfer)

*   [**Rewrite: Neural Style Transfer For Chinese Fonts**][[Project]](https://github.com/kaonashi-tyc/Rewrite)

:grey_question: **Visual Attribute Transfer through Deep Image Analogy**[[Paper]](https://arxiv.org/pdf/1705.01088.pdf)  *(SIGGRAPH 2017)*

:star: **Code:**

*   [Caffe-based](https://github.com/msracver/Deep-Image-Analogy)

:white_check_mark: **Fashion Style Generator** [[Paper]](https://www.ijcai.org/proceedings/2017/0520.pdf)  *(IJCAI 2017)*
