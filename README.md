# Image_Filtering
## INTRODUCTION 
 
Most of the images are influenced by some kind of unwanted noises causing disturbance in image quality and resolution. Analyzing the images are usually processed right after removing these noises from the images. Filtering has various meanings and applications in most of the engineering and scientific problems. It provides researchers with fine results comparing with other available methods. Researchers in image/signal processing, electrical and electronic, mechanical engineering, chemistry and physics are utilizing filtering in their problems. One of the most common applications of filtering is in image processing to give a better resolution or to emphasize the edges properly. 
 
## Filtering : 
Box filter, Gaussian filter and bilateral filters are kind of well-known filters used in image processing. As we know all these filters are used for de-blurring and smoothing. In addition, with the help of these filters some facts which are clear in the original image will be blurred and the final image will be enhanced. With considering the best sigma value for bilateral filter, after comparing all these four filters we will find out that the bilateral filter is the best. As conserving the edge is needed, we want our image to be blurred and smoothed, so bilateral filtering is very useful in such a case [1][2]. This filter has various applications in engineering and science [3-9]. In this technique, colors and gray levels are joined and close values are more preferred than the far or distant ones. The main aim of the cited method is removing phantom colors in the original image which may be appeared in the edges. 
Bilateral filtering is kind of de-noising methods which can preserve sharp edges and remove some colors across the edges. This filter because of weighted mean of neighborhood pixels are easy to understand. In addition, there is a distance between pixel values, so it can be adopted properly. Last but not least, this filter is noniterative which is very simple 

Methods For Image Filtering  
 
a. Mean Filter 
The mean filter is used to give a blur effect to an image to remove the existing noisiness. It determines the mean of the pixels within the n×n method. Then it replaces the intensity of pixels by the mean. This reduces some of the noisiness present in the image and also improves the edges of an image. 

The above figure shows that some of the noisiness has been reduced, but there are some marks now which were not present in the image before. Let’s see if those marks still appear if we filter the image into grayscale: 
 
b. Gaussian Filter 
The Gaussian filter is very similar to the mean filter, but it involves a weighted mean of the pixels with a parameter as sigma. Let’s go through this method of Image Filtering: 

c. Median Filter 
The median filter computes the median of the intensity of pixels. It then replaces the norm with the pixel intensity of mean pixels. Now let’s go through this technique:   
The median effect leaves a better output by removing the noisiness of the image. It also did not leave any marks in the image that we saw in the above methods. Now let’s convert it into a grayscale image: 

5. Creating Our Own Filter 
 
Now I will create our own filter for Filtering Images than can improve the quality of the image and improves the smoothness of the picture. I will first create a function to design my own Image filter: 
  
6. Conclusion: 
 
In this Project various filtering approaches are utilized to address the issue of image recovery from its noisy counterpart. The image filtering algorithm provides us with smoothness and better resolution from the noisy version. Experiments are conducted that bilatereal filtering performs better than other filtering techniques which are available in the literature. For the future work, we will deall with applying some optimization algorithms and machine learning approaches [10- 25] to check and compare the performance analysis of different methods. 
