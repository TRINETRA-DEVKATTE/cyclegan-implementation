# CycleGAN Implementation

This repository contains an implementation of the CycleGAN model proposed in the paper "Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks". The CycleGAN model enables unpaired image-to-image translation, allowing us to learn mappings between different domains without requiring paired training data.

![CycleGAN](./cyclegan.png)


## Overview

CycleGAN is a generative adversarial network (GAN) architecture that can learn to translate images from one domain to another without the need for paired examples. It consists of two generators and two discriminators. The generators learn to translate images from one domain to another and vice versa, while the discriminators aim to distinguish between the generated and real images.

## Prerequisites

- Python 3.6+
- PyTorch
- NumPy
- matplotlib

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository:

   ```
   git clone https://github.com/TRINETRA-DEVKATTE/cyclegan-implementation.git
   ```

2. Open the `CycleGan.ipynb` file in Jupyter Notebook or any other compatible environment.

3. Install the required dependencies by running the following command in a code cell:

   ```python
   !pip install -r requirements.txt
   ```

4. Download the dataset or prepare your own dataset.

5. Follow the instructions provided in the notebook to train and test the CycleGAN model.

For more detailed instructions and customizable options, please refer to the notebook.


## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Acknowledgements

I would like to acknowledge and give credit to the authors of the original CycleGAN paper:

- Jun-Yan Zhu
- Taesung Park
- Phillip Isola
- Alexei A. Efros

Their work on unpaired image-to-image translation using cycle-consistent adversarial networks has significantly contributed to the field of machine learning and computer vision. We appreciate their valuable research and the resources they have provided to the community.

If you use this implementation or refer to their work, please cite their paper:

```
@inproceedings{zhu2017unpaired,
  title={Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks},
  author={Zhu, Jun-Yan and Park, Taesung and Isola, Phillip and Efros, Alexei A},
  booktitle={Proceedings of the IEEE International Conference on Computer Vision (ICCV)},
  year={2017}
}
```

[Original CycleGAN Paper](https://arxiv.org/abs/1703.10593) | [CycleGAN Project Page](https://junyanz.github.io/CycleGAN/) | [CycleGAN GitHub Repository](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix/blob/master/README.md)


## References

- [CycleGAN: Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks](https://arxiv.org/abs/1703.10593)
