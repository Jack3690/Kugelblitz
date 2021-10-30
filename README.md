# Marvin and Fasi.ai Notebooks for Data Analysis and Visualization

&#x1F534;&nbsp;&nbsp; Now framework-agnostic! [(Example core notebook)](Examples_core.ipynb) &nbsp;&#x1F534;

&#x1F517;&nbsp;&nbsp; For further explanation of the methods and more examples of the resulting maps, see our [Github Pages website](https://pair-code.github.io/saliency)  &nbsp;&#x1F517;

If upgrading from an older version, update old imports to `import saliency.tf1 as saliency`. We provide wrappers to make the framework-agnostic version compatible with TF1 models. [(Example TF1 notebook)](Examples_tf1.ipynb)

## Introduction

This repository contains code for the following saliency techniques:

*   Guided Integrated Gradients* ([paper](https://arxiv.org/abs/2106.09788), [poster](https://github.com/PAIR-code/saliency/blob/master/docs/CVPR_Guided_IG_Poster.pdf))
*   XRAI* ([paper](https://arxiv.org/abs/1906.02825), [poster](https://github.com/PAIR-code/saliency/blob/master/docs/ICCV_XRAI_Poster.pdf))
*   SmoothGrad* ([paper](https://arxiv.org/abs/1706.03825))
*   Vanilla Gradients
    ([paper](https://scholar.google.com/scholar?q=Visualizing+higher-layer+features+of+a+deep+network&btnG=&hl=en&as_sdt=0%2C22),
    [paper](https://arxiv.org/abs/1312.6034))
*   Guided Backpropogation ([paper](https://arxiv.org/abs/1412.6806))
*   Integrated Gradients ([paper](https://arxiv.org/abs/1703.01365))
*   Occlusion
*   Grad-CAM ([paper](https://arxiv.org/abs/1610.02391))
*   Blur IG ([paper](https://arxiv.org/abs/2004.03383))


## Conclusion/Disclaimer

If you have any questions or suggestions for improvements to this repo,
please contact the owners of the  repository.

This is not an official Google product.
