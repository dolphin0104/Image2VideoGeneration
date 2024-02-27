![image](https://github.com/dolphin0104/Image2VideoGeneration/assets/34062125/1a9a9f81-0c86-4940-911a-808b68ce2961)# Generating High Quality Video From a Single Image


<p align="center">
  <video src="samples/m1.mp4" width="500px"></video>
</p>




## Test Results on Natural Scene (GoPro Dataset)

| ![](/samples/s1.png)  | ![](/samples/s1_gt.gif) | ![](/samples/s1_jin.gif) | ![](/samples/s1_zhang.gif) |
| :----------: | :----------: | :----------: | :----------: |
| Input Blur  | Ground-Truth 11 Frames | Jin et al. 7 Frames | Zhang et al. 15 Frames |
| ![](/samples/s1_mag.png)  | ![](/samples/s1_ours_11.gif) | ![](/samples/s1_ours_7.gif) | ![](/samples/s1_ours_15.gif) |
| Magnified part of input  | Ours 11 Frames | Ours 7 Frames | Ours 15 Frames |

| ![](/samples/s6.png)  | ![](/samples/s6_gt.gif) | ![](/samples/s6_jin.gif) | ![](/samples/s6_zhang.gif) |
| :----------: | :----------: | :----------: | :----------: |
| Input Blur  | Ground-Truth 11 Frames | Jin et al. 7 Frames | Zhang et al. 15 Frames |
| ![](/samples/s6_mag.png)  | ![](/samples/s6_ours_11.gif) | ![](/samples/s6_ours_7.gif) | ![](/samples/s6_ours_15.gif) |
| Magnified part of input  | Ours 11 Frames | Ours 7 Frames | Ours 15 Frames |


| ![](/samples/s2.png)  | ![](/samples/s2_gt.gif) | ![](/samples/s2_jin.gif) | ![](/samples/s2_zhang.gif) |
| :----------: | :----------: | :----------: | :----------: |
| Input Blur  | Ground-Truth 11 Frames | Jin et al. 7 Frames | Zhang et al. 15 Frames |
| ![](/samples/s2_mag.png)  | ![](/samples/s2_ours_11.gif) | ![](/samples/s2_ours_7.gif) | ![](/samples/s2_ours_15.gif) |
| Magnified part of input  | Ours 11 Frames | Ours 7 Frames | Ours 15 Frames |


| ![](/samples/s3.png)  | ![](/samples/s3_gt.gif) | ![](/samples/s3_jin.gif) | ![](/samples/s3_zhang.gif) |
| :----------: | :----------: | :----------: | :----------: |
| Input Blur  | Ground-Truth 11 Frames | Jin et al. 7 Frames | Zhang et al. 15 Frames |
| ![](/samples/s3_mag.png)  | ![](/samples/s3_ours_11.gif) | ![](/samples/s3_ours_7.gif) | ![](/samples/s3_ours_15.gif) |
| Magnified part of input  | Ours 11 Frames | Ours 7 Frames | Ours 15 Frames |

| ![](/samples/s4.png)  | ![](/samples/s4_gt.gif) | ![](/samples/s4_jin.gif) | ![](/samples/s4_zhang.gif) |
| :----------: | :----------: | :----------: | :----------: |
| Input Blur  | Ground-Truth 11 Frames | Jin et al. 7 Frames | Zhang et al. 15 Frames |
| ![](/samples/s4_mag.png)  | ![](/samples/s4_ours_11.gif) | ![](/samples/s4_ours_7.gif) | ![](/samples/s4_ours_15.gif) |
| Magnified part of input  | Ours 11 Frames | Ours 7 Frames | Ours 15 Frames |

| ![](/samples/s5.png)  | ![](/samples/s5_gt.gif) | ![](/samples/s5_jin.gif) | ![](/samples/s5_zhang.gif) |
| :----------: | :----------: | :----------: | :----------: |
| Input Blur  | Ground-Truth 11 Frames | Jin et al. 7 Frames | Zhang et al. 15 Frames |
| ![](/samples/s5_mag.png)  | ![](/samples/s5_ours_11.gif) | ![](/samples/s5_ours_7.gif) | ![](/samples/s5_ours_15.gif) |
| Magnified part of input  | Ours 11 Frames | Ours 7 Frames | Ours 15 Frames |

## Test Results on Human Dancing Datset (B-Aist++ Dataset)

| ![](/samples/s7.png)  | ![](/samples/s7_gt.gif) | ![](/samples/s7_zhong.gif) | ![](/samples/s7_ours.gif) |
| :----------: | :----------: | :----------: | :----------: |
| ![](/samples/s8.png)  | ![](/samples/s8_gt.gif) | ![](/samples/s8_zhong.gif) | ![](/samples/s8_ours.gif) |
| Input Blur  | Ground-Truth 7 Frames | Zhong et al. 7 Frames | Ours 7 Frames |

## References
+ S. Nah T. H. Kim and K. M. Lee "Deep multi-scale convolutional neural network for dynamic scene deblurring" Proc. IEEE Conf. Comput. Vis. Pattern Recognit. (CVPR) pp. 3883-3891 Jul. 2017.
+ M. Jin, G. Meishvili, and P. Favaro, “Learning to extract a video sequence from a single motion-blurred image,” in Proc. IEEE Conf. Comput. Vis. Pattern Recognit. (CVPR), June 2018, pp. 6334–6342. 
+ Y. Zhang, C. Wang, S. J. Maybank and D. Tao. "Exposure Trajectory Recovery From Motion Blur”, in IEEE Trans. Pattern Anal. Mach. Intell. (TPAMI), vol. 44, no. 11, pp. 7490-7504, 1 Nov. 2022
+ Z. Zhong, X. Sun, Z. Wu, Y. Zheng, S. Lin, and I. Sato, “Animation from Blur: Multi-modal Blur Decomposition with Motion Guidance”. In European Conf. on Comput. Vis. (ECCV), vol 13679. Springer, Cham. 2022.

