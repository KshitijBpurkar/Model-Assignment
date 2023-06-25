# Model-Assignment (Porosity Calculation)

Description Of Process: Canny Edge detection algorithm is used to create a new image that shows the edges of the original image. Then the average value of all pixels in the new image is calculated. Those pixels with value less than average are considered dark (porous region pixels).The percentage of the dark pixels with respect to the total number of pixels is calculated, which is the porosity percentage.

Porosity: The final calculated Porosity is 32.2927%

Tunable Parameters: The Max and Min Value for the Canny image conversion process [cv.Canny(img,Min=150,Max=175)] can affect the accuracy of the answer. The difference between them, if large will result in more edges detected and if small will result in less edges detected which will affect the final answer


