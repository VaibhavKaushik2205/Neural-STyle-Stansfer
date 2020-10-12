This is a tensorflow implementation of the paper: [A Neural Algorithm of Artistic Style](https://arxiv.org/pdf/1508.06576.pdf) by Leon A. Gatys, Alexander S. Ecker, and Matthias Bethge.

The paper presents an algorithm for combining the content of one image with the style of another image using convolutional neural networks. 

## How does it work?
In this algorithm, we define two distances namely the Content Distance(D_c) and the Style Distance(D_s).

**Content Distance**: It measures that how different is the content between the original image and the output image of the algorithm.
**Style Distance**: It indicates how different are the output image or feature map and the style image.
We take a third image ie the input and we transform it in order to both minimize its D_c with Content Image and D_s with Style Image.

## Images
![Footballer-The_Scream](/images/football.jpg) ![Footballer-The_Scream](/images/Football_Scream.jpg) ![Footballer-The_Scream](/images/The Scream.jpg)


