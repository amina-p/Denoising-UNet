# Denoising-UNet
Paper title : "Image Quality Improvement using convolutional denoising autoencoder based on U-Net".

Inspired by U-Net, we proposed Denoising-UNet for removing the Gaussian noise from the degraded image.
# Brief Description of Our Proposed Method
Our model named Denoising-UNet was able to denoise an input image to be as similar as the original image, yet, to improve the image quality. he proposed model has demonstrated outstanding denoising performance compared to the existing baseline methods.

The overall architecture of our proposed approach named Denoising-UNet is visualized below.
![fig6](https://user-images.githubusercontent.com/61737618/169706773-ca9523bd-0413-4f74-8b62-91fdd7192467.PNG)
# Experimental Results
CIFAR100 dataset is used to train the proposed model. 

Image denoising experiments are performed on Set5 datasets.

Visual results of image denoising. Images from top to bottom are: Original Image, Noisy Image, the recovered/denoised image from Set5 datasets, when α= 70.
![fig9](https://user-images.githubusercontent.com/61737618/169706904-791431fd-ed8d-4275-8a10-3f0d2e8a98ec.PNG)

As performance metrics, PSNR, SSIM and MSE are used to measure the performance of the proposed model. 

The model has demonstrated outstanding denoising performance compared to existing baseline methods.  In a test of denoising the test images from gaussian noise with different noise densities(α= 10, 30, 50 and 70), the proposed model achieved a statistically significant value of PSNR and SSIM up to 36.8639 and 0.9944 respectively. 
![Capture22](https://user-images.githubusercontent.com/61737618/169709918-8346d869-7e06-428f-aec6-b37343066c79.PNG)
![Capture23](https://user-images.githubusercontent.com/61737618/169709922-7e8405f0-2b02-4ddf-aee1-8c9330473ae2.PNG)
![Capture24](https://user-images.githubusercontent.com/61737618/169709923-a571da9a-3355-45db-8f99-2c86d041aa87.PNG)



# Citation
Will be updated soon.
