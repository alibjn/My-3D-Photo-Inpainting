# 3D-Photo-Inpainting
My 3D Photography using Context-aware Layered Depth Inpainting

3D Photography using Context-aware Layered Depth Inpainting
Meng-Li Shih, Shih-Yang Su, Johannes Kopf, and Jia-Bin Huang
In IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2020. https://arxiv.org/pdf/2004.04727.pdf


Abstract
We propose a method for converting a single RGB-D input image into a 3D photo, i.e., a multi-layer representation for novel view synthesis that contains hallucinated color and depth structures in regions occluded in the original view. We use a Layered Depth Image with explicit pixel connectivity as underlying representation, and present a learning-based inpainting model that iteratively synthesizes new local color-and-depth content into the occluded region in a spatial context-aware manner. The resulting 3D photos can be efficiently rendered with motion parallax using standard graphics engines. We validate the effectiveness of our method on a wide range of challenging everyday scenes and show fewer artifacts when compared with the state-of-the-arts.

![image](https://user-images.githubusercontent.com/66758522/99754806-8611eb80-2ae9-11eb-9798-9bdec01865ce.png)


Description (How it works):
•	A color single RGB-D input image is used as input and the 3D photo is generated in MP4 format
•	3D photo generation is based on the multi-layer representation where these layers contain hallucinated color and depth structures in regions occluded in the original view.
•	The library uses Layered Depth Image (as input) with explicit pixel connectivity as underlying representation, and present a learning-based inpainting model that iteratively synthesizes new local color-and-depth content into the occluded region in a spatial context-aware manner.
•	The final 3D photo result image can be efficiently rendered with motion parallax using standard graphics engines.


3D Photo Inpainting - Turn Any Picture Into 3D Photo with Deep Learning and Python
Have you seen those amazing 3D photos on Facebook and Instagram? How can you create your own from regular photos? We’re going to do that with the help of a project called: 3D Photography using Context-aware Layered Depth Inpainting. We’ll try out different photos, and have a look at how it all works!
Here’s what we’ll go over:
•	Install the prerequisites for the 3D photo inpainting project
•	Convert some images into 3D photos
•	Dive deeper into how it works
•	Look into what training data was used

The results are stored in the following directories
•	Corresponding depth map estimated by MiDaS
o	E.g. /content/3d-photo-inpainting/depth/bjn.npy
•	Inpainted 3D mesh
o	E.g. /content/3d-photo-inpainting/mesh/bjn.ply
•	Rendered videos with zoom-in motion
o	E.g. /content/3d-photo-inpainting/video/bjn_zoom-in.mp4
•	Rendered videos with swing motion
o	E.g. /content/3d-photo-inpainting/video/bjn_swing.mp4
•	Rendered videos with circle motion
o	E.g. /content/3d-photo-inpainting/video/bjn_circle.mp4
![image](https://user-images.githubusercontent.com/66758522/99754734-5c58c480-2ae9-11eb-8d51-9f333b42a269.png)
