# Virtual Makeup

This Project enhances the facial properties of Image such as change the hair color, apply different shades of lipsticks.
 <div class="row">    
    <div class="col">
      <img src="https://github.com/sauravakolia/VirtualMakeup/blob/main/orig.png" style="width:50%">
    </div>  
    <div class="col">
      <img src="https://github.com/sauravakolia/VirtualMakeup/blob/main/hair.png" style="width:50%">
    </div> 
  </div>

# Motivation
The project automate the process of makeup thus, saves the time and extra expenses on the trial of different makeup products. This project can be quite useful in the present situation of lockdown.

# Methodology
For this project facial segmentation is done using Bisenet (Bilateral Segmentation Network for Real-time Semantic Segmentation). </br>
The Bisenet architecture proved to be  a right balance between the speed and segmentation performance as compared to other Segmentation architectures.</br>

<img src="https://github.com/sauravakolia/VirtualMakeup/blob/main/bisenet.png">

# Dataset
<a href="https://github.com/switchablenorms/CelebAMask-HQ">CelebAMask-HQ</a> dataset is used for this project.</br>
</br>
CelebAMask-HQ is a large-scale face image dataset that has 30,000 high-resolution face images selected from the CelebA dataset by following CelebA-HQ. Each image has segmentation mask of facial attributes corresponding to CelebA.

# Future Work
Implementation of project on the app.
