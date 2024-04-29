# Monet_GAN
 ABSTRACT: Paint Like Monet: Two-Objective Discriminator GAN to Mimic Monet’s Painting Style
 
## Sources:
- Based on Kaggle Competition: I'm Something of a Painter Myself (https://www.kaggle.com/competitions/gan-getting-started/overview) 
- Baseline file copied in Feb. 2024 from Saravana Kumar, which was copied from UnfriendlyAI
- Data from: https://www.kaggle.com/competitions/gan-getting-started/data (For storage purposes, I have not included the images in this repo; use the link to download the image directories from Kaggle)

## Explanation of Code (more explanations in ipynb file)
- Basically, there's a generator and a discriminator in a GAN (Generative Adversarial Network)
- Takes in landscape photographs and images of Monet's paintings
- The generator and discriminator train each other and work together to make an image that combines the photograph with Monet's style

### Example:

Monet painting:

![monet example](https://github.com/mdbromhal/Monet_GAN/blob/3429964ecbe36662b6c1df88a09ae04204fc0a43/000c1e3bff.jpg)

Landscape photograph:

![landscape example](https://github.com/mdbromhal/Monet_GAN/blob/3429964ecbe36662b6c1df88a09ae04204fc0a43/00068bc07f.jpg)

**And the GAN will combine these to make its own image in Monet's style**

Example from kaggle competition submission:

![results example](https://github.com/mdbromhal/Monet_GAN/blob/3429964ecbe36662b6c1df88a09ae04204fc0a43/Screen%20Shot%202024-04-29%20at%201.51.32%20PM.png)

## Poster Presentation
![poster photo](https://github.com/mdbromhal/Monet_GAN/blob/51c378b8cd963e4765a139404fb1451a314e8e50/Megdalia_MonetGAN_poster.png)
