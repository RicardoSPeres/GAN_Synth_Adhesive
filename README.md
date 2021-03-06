# Generative Adversarial Networks for Data Augmentation in Structural Adhesive Inspection

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

We leverage recent advances regarding GAN training in limited data regimes to **generate synthetic images of structural adhesive defects** such as the ones seen above. We demonstrate that these realistic synthetic samples can be **used to augmented scarce datasets and improve the performance of state-of-the-art object detection models** in the automated inspection of such adhesive applications.

## Citation 

> Peres, R.S.; Azevedo, M.; Araújo, S.O.; Guedes, M.; Miranda, F.; Barata, J. (2021). Generative Adversarial Networks for Data Augmentation in Structural Adhesive Inspection. Applied Sciences, **Under Review**.

## Generating Synthetic Defect Images with StyleGAN2-ADA

<table>
  <tr>
    <td><img src="Figures/Gifs/introsys1024_1.gif" width=270></td>
    <td><img src="results/see-q-product.jpg" width=270></td>
    <td><img src="results/gluesim_demo2.gif" width=270></td>
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
