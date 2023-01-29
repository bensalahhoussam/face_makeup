# face_makeup tensorflow implementation


## Network Architecture 

The proposed Bilateral Segmentation Network (BiSeNet) with Spatial Path and Context Path.

The task of semantic segmentation, there attempt to preserve the resolution of the input image to encode enough spatial information with dilated convolution, 
while other try to capture sufficient receptive field with pyramid pooling module, These methods indicate that the spatial information and the receptive field are crucial to achieving high accuracy,so the purpose spatial Path is to preserve the spatial size of the original input image and encode rich spatial information.

The spatial Path contains three layers. Each layer includes a convolution with stride = 2, followed by batch normalization and ReLU.
It encodes rich spatial information due to the large spatial size of feature maps.

![Screenshot 2023-01-28 200032](https://user-images.githubusercontent.com/112108580/215286252-6da364ad-88b9-4c7a-a9b0-5b08383a1584.png)
