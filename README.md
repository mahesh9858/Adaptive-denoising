The development of feed-forward denoising convolutional neural networks (DnCNN) has raised the level of competition in the quickly developing field of image denoising. 
In this Study, we introduce adaptive layer to the well-known DnCNN model, enabling it to identify and adapt to different kinds and intensities of noise automatically. This 
adaptive approach allows the model to dynamically adjust its parameters based on the noise characteristics. Furthermore, an innovative feedback mechanism is integrated, 
where the denoised output is recurrently fed back into the model, facilitating iterative refinement cycles. This results in increased precision and adaptability, especially in 
scenarios with varying or unknown noise types and levels. Preliminary tests have indicated not only improved denoising outcomes but also increased efficiency, setting 
a promising direction for future applications in real world image processing challenges. Our method involves the addition of various types of noise, including Gaussian noise, 
salt and pepper noise, and speckle noise to get clean images with specific noise levels. The DnCNN model is then employed to perform image denoising, aiming to restore the 
clean version of the image. We evaluate the effectiveness of our approach by measuring the Peak Signal-to-Noise Ratio (PSNR), loss factor, and Structural Similarity Index 
Measure (SSIM) between the denoised images and their corresponding clean versions. The results demonstrate the capability of the enhanced DnCNN model to effectively 
denoise images corrupted with different types and levels of noise, achieving high PSNR and SSIM scores while minimizing loss. This model is more effectively denoised in the 
case of Gaussian noise when compared with speckle and salt and pepper noises. This approach showcases the potential of deep learning techniques for robust image 
denoising applications in various domains, including computer vision and medical imaging
