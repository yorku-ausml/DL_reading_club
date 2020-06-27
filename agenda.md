# Agenda for 10am May 22 (Fri) 2020

The followings are the presenters whom Prof. Gunho Sohn invited to give a presentation to the group. 

### May 22nd , 2020
  - 10:00 - 10:20 - Bounding-box-based object detection introduction (**Gunho Sohn**)
    - Zhao, Z.Q., 2019. Object detection with deep learning: A review. arXiv:1807.05511v2 [cs.CV] 16 Apr 2019.
  - 10:20 - 10:30 - Q&A
  - 10:30 - 10:50 - Object detection part 1 (**Hyungjy Lee**)
    - https://lilianweng.github.io/lil-log/2017/12/31/object-recognition-for-dummies-part-3.html
    - MathWorks. Anchor boxes for object detection. https://www.mathworks.com/help/vision/ug/anchor-boxes-for-object-detection.html. (accessed on May 16th, 2020)  
  - 10:50 - 11:00 - Q&A
  - 11:00 - 11:20 - Object detection  part 2 (**Thao Tran**)
    - https://lilianweng.github.io/lil-log/2018/12/27/object-detection-part-4.html    
  - 11:20 - 11:30 - Q&A
  - 11:30 - 11:50 - Weakly supervised and universal bounding box regression (**Jacob Yoo**)
    - Zhang, C.H., Cao, Y.H. and Wu, J., 2020. Rethinking the route towards weekly supervised object localization. arXiv:2002.11359v2 [cs.CV] 3 Mar 2020.
    - Lee, S., Kwak, S. and Cho, M., 2019. Universal bounding box regression and its applications. arXiv:1904.06805v1 [cs.CV] 15 Apr 2019. 
  - 11:50 - 12:00 - Q&A
<br/>


### Further reading list
  - He, Y., Zhi, C., Wang, J., Savvides, M., Zhang, X. 2019. Bounding box regression with uncertainty for accurate object detection. arXiv:1809.08545v3 [cs.CV] 16 Apr 2019.
  - Choi, J., Kwon, J. and Lee, K.M., 2018. Real-time visual tracking by deep reinforced decision making. CVIU, 171: 10-19.
<br/>


### Review
This section will review the fundamentals and current advancement of object detection. Many of you are working on this topic and familiar with most of the papers listed. However, I want you to pay attention to the following questions:
  - Understanding:
    - anchor-based, anchor-free
    - object proposal vs detector
    - regression (entire class, per single class weight update, class-agnostic, weekly supervised, universal, attention-guided)
  - Question:
    - how to transfer the knowledge/weights to detect unknown classes?
    - how to fine-tune-regress the bounding box proposal?
    - how to generate the labels for the bounding box object detection?
    - how to apply it to video sequences?
    - how to apply it fo multiple instances?
    - how to make the feature vector deeper for bound box generation?
    - does the performance increase or decrease if classified, detector and segmentation are co-supervised?   
<br/>


### Note for Hyungju and Jungwon
A technical report published by Girshik (Fast R-CNN)  provides a more detailed explanation of the bounding box regression (in Appendix).
Please review this paper as part of your presentation, especially studying the regression mathematically for the bounding box regression.
  - Girshick, R., Donahue, J., Darrell, T., Malik, J., 2014. Rich feature hierarchies for accurate object detection and semantic segmentation. Technical Report (v5). arXiv:1311.2524v5 [cs.CV] 22 Oct 2014.
<br/>
<br/>
<br/>



<!---
########################################################################################################################################################################
########################################################################################################################################################################
-->

# Agenda for 10am May 29 (Fri) 2020

The followings are the presenters whom Prof. Gunho Sohn invited to give a presentation to the group. 

### May 29nd , 2020
  - Weakly supervised and universal bounding box regression (**Jacob Yoo**)
    - Zhang, C.H., Cao, Y.H. and Wu, J., 2020. Rethinking the route towards weekly supervised object localization. arXiv:2002.11359v2 [cs.CV] 3 Mar 2020.
    - Lee, S., Kwak, S. and Cho, M., 2019. Universal bounding box regression and its applications. arXiv:1904.06805v1 [cs.CV] 15 Apr 2019. 
  - Section 3.3 - Recent advances in deep learning for object detection (**Zhen Liu**)
  - ConerNet and CenterNet (**Muhammad Kamran**)
<br/>


### Notice from Professor
I (Prof. Gunho Sohn) split the group into two (one who recently joined the lab and the other who already started their program since last year).
The first group will be asked to review the sections in the review paper (recent advances in deep learning for object detection attached), 
while the second group will review specific paper).

For the next week (May 29th), I would like to invite Zhen and Kamran to lead the group reading on Friday.  
  - Zhen:  Section 3.3 - Recent advances in deep learning for object detection
  - Kamran: ConerNet and CenterNet

Kamran's reading is related to keypoint-based object detection and you can find a summary of this field in the same review paper (Section 3.4.3). 
It is important everyone gets familiar with the papers and actively participate in the group discussion - learning and teaching each other as a group. 

I uploaded the papers for the next week's reading club in the dropbox. 
<br/>
<br/>


### Note for Jacob
I (Prof. Gunho Sohn) am sending one paper (Relation-Shape Convolutional Neural Network for Point Cloud Analysis) for your review. 
It was published in ICCV 2019. I keep searching for papers related to feature representation for segmentation, instance detection and clustering.
It will help you to design your deep sampling.
<br/>
<br/>
<br/>



<!---
########################################################################################################################################################################
########################################################################################################################################################################
-->

# Agenda for 10am June 5 (Fri) 2020

#### Professor:
  - Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization

#### Jacob:
  - Weakly supervised and universal bounding box regression
<br>
<br>
<br>



<!---
########################################################################################################################################################################
########################################################################################################################################################################
-->

# Agenda for 10am June 12 (Fri) 2020

#### Peter:
  - M2Det: A single-short object detector based on multi-level feature pyramid

#### Maryam:
  - UNet++: A nested U-Net architecture
  - ANU-Net: attention-based nested U-Net to exploit full resolution
<br>
<br>
<br>




<!---
########################################################################################################################################################################
########################################################################################################################################################################
-->

# Agenda for 10am June 19 (Fri) 2020

#### Avin:
  - Unsupervised learning of depth and Ego-motion from video
  - D3VO-Deep depth, deep pose and deep uncertainty for monocular visual odometry (CVPR 2020)
  - Digging into self-supervised monocular depth estimation (ICCV2019)

#### Brian:
  - [Improved Road Connectivity by Joint Learning of Orientation and Segmentation](http://openaccess.thecvf.com/content_CVPR_2019/papers/Batra_Improved_Road_Connectivity_by_Joint_Learning_of_Orientation_and_Segmentation_CVPR_2019_paper.pdf)
<br>
<br>
<br>



<!---
########################################################################################################################################################################
########################################################################################################################################################################
-->

# Agenda for 10am June 26 (Fri) 2020

#### Maryam:
  - Bilateral-Branch Network with Cumulative Learning for Long-Tailed Visual Recognition 
  - Learning to Segment 3D Point Clouds in 2D Image Space 
  - Cars Can’t Fly up in the Sky: Improving Urban-Scene Segmentation via Height-driven Attention Networks

#### Brian:
  - LIFT: Learned Invariant Feature Transform
  - SuperPoint: Self-Supervised Interest Point Detection and Description
  - [UnsuperPoint: End-to-end Unsupervised Interest Point Detector and Descriptor](https://arxiv.org/abs/1907.04011)
  
### etc:
  - [Neural Outlier Rejection for Self-Supervised Keypoint Learning](https://arxiv.org/abs/1912.10615)
<br>
<br>
<br>




