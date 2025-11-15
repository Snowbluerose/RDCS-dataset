# RDCS-dataset
Here is the download link of RDCS dataset, corresponding to the paper:A Novel RGB-D Camera based Dataset for Spacecraft Pose Estimation
这里是RDCS数据集的下载链接，相关论文为：A Novel RGB-D Camera based Dataset for Spacecraft Pose Estimation（基于RGB-D相机的用于航天器位姿估计的新数据集）

The thesis has been employed but not yet published. The article has been hired but has not been published yet. If it is published, I will add a link here. 论文已录用但还未公开,如果公开了我将在此补充链接。

Abstract：

In the field of close-proximity space operations, RGB-D cameras have been used widely. However, publicly available spacecraft datasets for pose estimation are primarily based solely on image data. There is no publicly available dataset based on RGB-D cameras that can be directly used. Therefore, this paper introduces a novel RGB-D camera-based spacecraft(RDCS) dataset. Due to high acquisition costs and confidentiality issues, it is difficult to obtain real spacecraft data and their associated pose information. To address this, the space environment and camera trajectories are constructed in Blender to capture pixel-aligned RGB images and depth maps of spacecraft from various observation angles. In addition, the RDCS dataset also includes pose annotations, bounding box labels, and corresponding mask images. The process focuses on addressing the challenges of acquiring the RGB image and the depth map of the spacecraft at the same keyframe while ensuring their pixel alignment, as well as determining the corresponding pose annotations. 

摘要：
这是一个用于航天器位姿估计的数据集，包含8种在役或刚刚退役的航天器，其中包括rgb图像、与之像素对齐的深度图、mask图像、带噪声的mask图像、以及位姿标签与航天器整体模型（以ply点云格式存储），整个数据集是用blender仿真生成的图像，包含了不同光亮下，不同背景下，航天器不同角度的数据，可用于航天器分类与位姿估计。
部分图像如下：

<img width="122" height="92" alt="image" src="https://github.com/user-attachments/assets/59c1d887-97eb-409d-8516-16160ff1e30f" />General satellite

<img width="121" height="91" alt="image" src="https://github.com/user-attachments/assets/11e448c7-07f3-4bab-9bbc-d40641c36fad" />B330

<img width="124" height="93" alt="image" src="https://github.com/user-attachments/assets/dcd3f768-3d86-423c-a31a-2822a93294a3" />Dragon 2

<img width="124" height="94" alt="image" src="https://github.com/user-attachments/assets/8b88d748-9ead-4ebe-80fa-eebc6b2f29f8" />Enhanced Cygnus

<img width="125" height="94" alt="image" src="https://github.com/user-attachments/assets/4781d5ea-3dcf-43ac-858c-e543c7a7742d" />Nauka

<img width="125" height="94" alt="image" src="https://github.com/user-attachments/assets/df8fcd09-930d-40dd-8597-61826e8e2c52" />CST-100 Starliner

<img width="124" height="93" alt="image" src="https://github.com/user-attachments/assets/b557cfaf-6a0a-407e-aa9b-e4ea2fc2a98a" />Dream Chaser

<img width="124" height="93" alt="image" src="https://github.com/user-attachments/assets/8f1fdf7a-6e56-4f06-875c-c6935fb510cf" />Boeing Airlock

<img width="158" height="119" alt="image" src="https://github.com/user-attachments/assets/e55ac372-7013-4709-9c86-d5d0861b34f2" />the mask image of the B330
（with bounding box）

<img width="154" height="115" alt="image" src="https://github.com/user-attachments/assets/df6267a6-2231-4473-8557-902eb26a82e0" />the depth map of the B330

If you are not in mainland China, you can download it through Google online disk：https://drive.google.com/file/d/16_k_vst_z31E7fvxS_5qMLyPvqlnywcH/view?usp=sharing（Copy share link to address bar and go to）. Because the uncompressed data set is very large, it is compressed in the form of.7z, After downloading, it can be unziped and used.
如果您是中国大陆的用户，可以通过百度云下载数据集，下载链接为: https://pan.baidu.com/s/1QBKrZjZwFLA3UAsRw7UyGA?pwd=vc86 提取码: vc86 ，因为原版数据集太大，所以以.7z格式进行了压缩，下载后自行解压即可使用

If you have any questions, please leave a message here or contact us directly via email at zhx_rbs@nuaa.edu.cn, thanks

如果您有任何问题，请在此页留言或者直接用过电子邮箱：zhx_rbs@nuaa.edu.cn联系我，谢谢
