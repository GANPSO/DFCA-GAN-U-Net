_If you use this code, please cite our work:  
[1] GANPSO, « GANPSO/DFCA-GAN-U-Net: DFCA ». Zenodo, févr. 09, 2025. doi: 10.5281/zenodo.14841534._

**GAN.ipynb - _Image and Mask Generation with GAN_**
This notebook implements a Generative Adversarial Network (GAN) to generate synthetic images and their corresponding masks. The GAN comprises a Generator (producing images and masks) and a Discriminator (distinguishing real vs. fake pairs). The generated images and masks are evaluated using a pre-trained U-Net model, achieving a Mean Dice Coefficient of 0.7534 and a Mean IoU of 0.6190.

**DFCA_GAN.ipynb - _Image and Mask Generation with DFCA-GAN_**
This notebook implements a Dynamic Feature Contextual Activation GAN (DFCA-GAN) to generate synthetic images and their corresponding masks. The DFCA-GAN enhances the generator and discriminator with DFCA modules, which dynamically scale features based on global context, improving the quality of generated images and masks. The generated outputs are evaluated using a pre-trained U-Net model, achieving a Mean Dice Coefficient of 0.8269 and Mean IoU of 0.7250. Additionally, the best-generated images and masks (with Dice > 0.90) are filtered, resulting in 724 high-quality pairs with a Mean Dice of 0.9890 and Mean IoU of 0.9786. 
