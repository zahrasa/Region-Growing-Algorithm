# Region-Growing-Algorithm
classical image processing

The region growing method is a well-developed technique for image segmentation. It postulates that neighboring pixels within the same region have similar intensity values.
In this repository, the area growth algorithm is implemented for the Balls.jpg image and the difference criterion is the seed pixel.

![input](https://github.com/zahrasa/Region-Growing-Algorithm/blob/main/img/Balls.jpg)

The ready-made functions cv2.setMouseCallback and cv2.EVENT_LBUTTONDBLCLK are used for graphical interface and specification of seed pixels. A sampled output is shown bellow when the seed pixel was in the white areas of the central ball. It can be seen that the algorithm has correctly specified all those connected areas just by knowing 'one' pixel (the seed).

<img src="https://github.com/zahrasa/Region-Growing-Algorithm/blob/main/img/result.png" alt="result" style="width:250px;height:250px;">
