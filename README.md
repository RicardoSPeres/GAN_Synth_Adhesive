<table>
  <tr>
    <td><img src="Figures/SyntheticImages/image (141).png" width=270></td>
    <td><img src="Figures/SyntheticImages/image (24).png" width=270></td>
    <td><img src="Figures/SyntheticImages/image (5).png" width=270></td>
    <td><img src="Figures/SyntheticImages/image (534).png" width=270></td>
  </tr>
  <tr>
    <td><img src="Figures/SyntheticImages/image (6).png" width=270></td>
    <td><img src="Figures/SyntheticImages/image (76).png" width=270></td>
    <td><img src="Figures/SyntheticImages/image (79).png" width=270></td>
    <td><img src="Figures/SyntheticImages/image (90).png" width=270></td>
  </tr>
</table>

# Generative Adversarial Networks for Data Augmentation in Structural Adhesive Inspection

We leverage recent advances regarding GAN training in limited data regimes to **generate synthetic images of structural adhesive defects** such as the ones seen below. We demonstrate that these realistic synthetic samples can be **used to augmented scarce datasets and improve the performance of state-of-the-art object detection models** in the automated inspection of such adhesive applications.

## Citation 
If you use our work or data in your research please cite: 

> Peres, R.S.; Azevedo, M.; Araújo, S.O.; Guedes, M.; Miranda, F.; Barata, J. (2021). Generative Adversarial Networks for Data Augmentation in Structural Adhesive Inspection. Applied Sciences.

## Dataset
The dataset used in the paper can be found at:
https://github.com/RicardoSPeres/GAN_Synth_Adhesive/releases/latest

## Generating synthetic defect images with StyleGAN2-ADA
### Visualizing truncation traversals

In this case the seeds used were 3845 and 55832, truncation values between -1.0 and 3.0 with increments of 0.05. 

<table>
  <tr>    
    <td><img src="Figures/Gifs/truncation-traversal-seed3845-start-1.0-stop3.0.gif" width=270></td>
    <td><img src="Figures/Gifs/truncation-traversal-seed55832-start-1.0-stop3.0.gif" width=270></td>
  </tr>
</table>

## Exploring the latent space with GANSpace
### Visualizing the effect of random seeds with different truncation and scale values

<table>
  <tr>
    <td><img src="Figures/Gifs/ganspace1.gif" width=270></td>
    <td><img src="Figures/Gifs/ganspace2.gif" width=270></td>
    <td><img src="Figures/Gifs/introsys1024_1.gif" width=270></td>
  </tr>
</table>

## Comparing defect detection results with YOLOv4-Tiny models trained on real and augmented datasets

<table>
  <tr>    
    <td>Real</td>    
    <td>Augmented</td>
  </tr>
</table>

<img src="Figures/results_det.jpg" width=1080>

<a href="#top">Back to top</a>
