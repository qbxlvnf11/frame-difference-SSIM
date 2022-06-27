
Description
=============

<img src="https://user-images.githubusercontent.com/52263269/176017021-514af297-0bba-4909-85b1-2629a7014586.png" width="20%"></img>

#### - Frame difference
  - How different are the pixel values and structures of the two images?

#### - SSIM (Structural Similarity Index Measure)
  -  A perception-based model that considers image degradation as perceived change in structural information, while also incorporating important perceptual phenomena, including both luminance masking and contrast masking terms.
  -  More details: https://en.wikipedia.org/wiki/Structural_similarity

Contents
=============

#### - Computing frame difference between current frame and previous frame or first frame
  - Read video
  - Comparision current frame with previous frame or first frame 
    - Frame difference score represented as SSIM (Structural Similarity Index Measure)
    - 'Score = 1' means that current frame and frame to compare are perfecly same
  - Filtering by score threshold
  - Visualization of bar chart using frame difference scores

References
=============

#### - SSIM

[https://pypi.org/project/av/](https://pyimagesearch.com/2017/06/19/image-difference-with-opencv-and-python/)

Author
=============

#### - LinkedIn: https://www.linkedin.com/in/taeyong-kong-016bb2154

#### - Blog URL: https://blog.naver.com/qbxlvnf11

#### - Email: qbxlvnf11@google.com, qbxlvnf11@naver.com
