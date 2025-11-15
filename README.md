# RDCS-dataset
Here is the download link of RDCS dataset, corresponding to the paper:A Novel RGB-D Camera based Dataset for Spacecraft Pose Estimation
这里是RDCS数据集的下载链接，相关论文为：A Novel RGB-D Camera based Dataset for Spacecraft Pose Estimation（基于RGB-D相机的用于航天器位姿估计的新数据集）

In the field of close-proximity space operations, RGB-D cameras have been used widely. However, publicly available spacecraft datasets for pose estimation are primarily based solely on image data. There is no publicly available dataset based on RGB-D cameras that can be directly used. Therefore, this paper introduces a novel RGB-D camera-based spacecraft(RDCS) dataset. Due to high acquisition costs and confidentiality issues, it is difficult to obtain real spacecraft data and their associated pose information. To address this, the space environment and camera trajectories are constructed in Blender to capture pixel-aligned RGB images and depth maps of spacecraft from various observation angles. In addition, the RDCS dataset also includes pose annotations, bounding box labels, and corresponding mask images. The process focuses on addressing the challenges of acquiring the RGB image and the depth map of the spacecraft at the same keyframe while ensuring their pixel alignment, as well as determining the corresponding pose annotations. 

这是一个用于航天器位姿估计的数据集，包含8种在役或刚刚退役的航天器，其中包括rgb图像、与之像素对齐的深度图、mask图像、带噪声的mask图像、以及位姿标签与航天器整体模型（以ply点云格式存储），整个数据集是用blender仿真生成的图像，包含了不同光亮下，航天器不同角度的数据，可用于航天器分类与位姿估计。

If you are not in mainland China, you can download it through Google online disk：https://drive.google.com/file/d/16_k_vst_z31E7fvxS_5qMLyPvqlnywcH/view?usp=sharing（Copy share link to address bar and go to）. Because the uncompressed data set is very large, it is compressed in the form of.7z, After downloading, it can be unziped and used.
如果您是中国大陆的用户，可以通过百度云下载数据集，下载链接为: https://pan.baidu.com/s/1QBKrZjZwFLA3UAsRw7UyGA?pwd=vc86 提取码: vc86 

If you have any questions, please leave a message here or contact us directly via email at zhx_rbs@nuaa.edu.cn, thanks
如果您有任何问题，请在此页留言或者直接用过电子邮箱：zhx_rbs@nuaa.edu.cn联系我，谢谢
