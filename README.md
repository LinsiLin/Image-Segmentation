# Image-Segmentation using Mean Shift Algorithm
#### Image segmentation means labeling pixels according to the image intensity such that pixels with similar intensity have same label.

Data:<br>
• 3 Color images
– Baboon, Lena, Pepper<br>
– A set of pixels with a 3D 8bit (0-255) RGB feature<br>
– Feature space is a 3D histogram of RBG colors (Color space) or 5D RBG-Space feature<br>

• 6 Grayscale images<br>
– Baboon, Lena, Pepper, Barbara, Cameraman, Goldhill<br>
– A set of pixels with a 1D 8bit (0-255) feature<br>
– Feature space is a 1D histogram of intensity values or 3D intensity-Space feature<br>

![alt text](https://github.com/LinsiLin/Image-Segmentation/blob/main/result1.png)
![alt text](https://github.com/LinsiLin/Image-Segmentation/blob/main/result2.png)
![alt text](https://github.com/LinsiLin/Image-Segmentation/blob/main/result3.png)

The choice of bandwidth influences the convergence rate and the number of clusters.<br>

As we can see from the output pictures, a very small bandwidth might result in too many clusters, while a large bandwidth might result in incorrect clustering and might merge distinct clusters. As the bandwidth increases, the high intensity places such as eyes, nose in the picture become more prominent.


Reference:
D. Comaniciu, P. Meer
Mean Shift: A Robust Approach toward Feature Space Analysis, IEEE Trans. Pattern Analysis Machine Intelligence, 24(5):603-619 (2002)
