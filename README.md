# Generative Adversarial Networks for Data Augmentation in Structural Adhesive Inspection

We leverage recent advances regarding GAN training in limited data regimes to **generate synthetic images of structural adhesive defects** such as the ones seen below. We demonstrate that these realistic synthetic samples can be **used to augmented scarce datasets and improve the performance of state-of-the-art object detection models** in the automated inspection of such adhesive applications.

## Citation 

> Peres, R.S.; Azevedo, M.; Araújo, S.O.; Guedes, M.; Miranda, F.; Barata, J. (2021). Generative Adversarial Networks for Data Augmentation in Structural Adhesive Inspection. Applied Sciences, **Under Review**.

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

## Generating Synthetic Defect Images with StyleGAN2-ADA
### Visualizing Truncation Traversals

<table>
  <tr>
    <td><img src="Figures/Gifs/introsys1024_1.gif" width=270></td>
    <td><img src="Figures/Gifs/truncation-traversal-seed3845-start-1.0-stop3.0.gif" width=270></td>
    <td><img src="Figures/Gifs/truncation-traversal-seed55832-start-1.0-stop3.0.gif" width=270></td>
  </tr>
</table>

## Exploring the latent space with GANSpace
### Visualizing the effect of random seeds with different truncation and scale values

<table>
  <tr>
    <td><img src="Figures/Movies/ganspace1.mp4" width=270></td>
    <td><img src="Figures/Movies/ganspace2.mp4" width=270></td>
    <td><img src="Figures/Movies/ganspace3.mp4" width=270></td>
  </tr>
</table>

## Comparing Results from Training with Real, Synthetic and Augmented Datasets

<table>
  <tr>
    <td>Synthetic</td>
    <td>Real</td>    
    <td>Augmented</td>
  </tr>
  <tr>
    <td><img src="results/yolov4_s/result_test_1.jpg" width=270></td>
    <td><img src="results/yolov4_r/result_test_1.jpg" width=270></td>
    <td><img src="results/yolov4_a/result_test_1.jpg" width=270></td>
  </tr>  
  <tr>
    <td><img src="results/yolov4_s/result_test_5.jpg" width=270></td>
    <td><img src="results/yolov4_r/result_test_5.jpg" width=270></td>
    <td><img src="results/yolov4_a/result_test_5.jpg" width=270></td>
  </tr> 
  <tr>
    <td><img src="results/yolov4_s/result_test_6.jpg" width=270></td>
    <td><img src="results/yolov4_r/result_test_6.jpg" width=270></td>
    <td><img src="results/yolov4_a/result_test_6.jpg" width=270></td>
  </tr> 
  <tr>
    <td><img src="results/yolov4_s/result_test_7.jpg" width=270></td>
    <td><img src="results/yolov4_r/result_test_7.jpg" width=270></td>
    <td><img src="results/yolov4_a/result_test_7.jpg" width=270></td>
  </tr> 
  <tr>
    <td><img src="results/yolov4_s/result_test_9.jpg" width=270></td>
    <td><img src="results/yolov4_r/result_test_9.jpg" width=270></td>
    <td><img src="results/yolov4_a/result_test_9.jpg" width=270></td>
  </tr> 
  <tr>
    <td><img src="results/yolov4_s/result_test_19.jpg" width=270></td>
    <td><img src="results/yolov4_r/result_test_19.jpg" width=270></td>
    <td><img src="results/yolov4_a/result_test_19.jpg" width=270></td>
  </tr> 
  <tr>
    <td><img src="results/yolov4_s/result_test_20.jpg" width=270></td>
    <td><img src="results/yolov4_r/result_test_20.jpg" width=270></td>
    <td><img src="results/yolov4_a/result_test_20.jpg" width=270></td>
  </tr> 
  <tr>
    <td><img src="results/yolov4_s/result_test_21.jpg" width=270></td>
    <td><img src="results/yolov4_r/result_test_21.jpg" width=270></td>
    <td><img src="results/yolov4_a/result_test_21.jpg" width=270></td>
  </tr> 
</table>

<a href="#top">Back to top</a>
