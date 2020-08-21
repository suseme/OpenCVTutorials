{% include header.html %}

# 写在前面的话

**OpenCV**是计算机视觉中经典的专用库，其支持多语言、跨平台，功能强大。**OpenCV-Python**为OpenCV提供了Python接口，使得使用者在Python中能够调用C/C++，在保证易读性和运行效率的前提下，实现所需的功能。

**OpenCV-Python Tutorials**是官方提供的文档，其内容全面、简单易懂，使得初学者能够快速上手使用。2014年段力辉在当时已翻译过OpenCV3.0，但时隔五年，如今的**OpenCV4.1**中许多函数和内容已经有所更新，因此有必要对该官方文档再进行一次翻译。

翻译过程中难免有所疏漏，如发现错误，希望大家指出，谢谢支持。

OpenCV-Python Tutorials官方文档：https://docs.opencv.org/4.1.2/d6/d00/tutorial_py_root.html

# 目录

### [OpenCV中文文档](/)

### Introduction to OpenCV | OpenCV简介
Learn how to setup OpenCV-Python on your computer!
#### [OpenCV-Python Tutorials](/01.Introduction.to.OpenCV/01.0.Introduction.to.OpenCV-Python.Tutorials)

#### [1.1 OpenCV-Python教程简介](/01.Introduction.to.OpenCV/01.1.OpenCV-Python.Tutorials)
Getting Started with OpenCV-Python
#### [1.2 在Windows中安装OpenCV-Python](/01.Introduction.to.OpenCV/01.2.Install.OpenCV-Python.in.Windows)
Set Up OpenCV-Python in Windows
#### [1.3 在Fedora中安装OpenCV-Python](/01.Introduction.to.OpenCV/01.3.Install.OpenCV-Python.in.Fedora)
Set Up OpenCV-Python in Fedora
#### [1.4 在Ubuntu中安装OpenCV-Python](/01.Introduction.to.OpenCV/01.4.Install.OpenCV-Python.in.Ubuntu)
Set Up OpenCV-Python in Ubuntu

### 2 Gui Features in OpenCV | OpenCV中的GUI特性
Here you will learn how to display and save images and videos, control mouse events and create trackbar.
#### [2.1 图像入门](/02.Gui.Features.in.OpenCV/02.1.Getting.Started.with.Images)
#### [2.2 视频入门](/02.Gui.Features.in.OpenCV/02.2.Getting.Started.with.Videos)
#### [2.3 OpenCV中的绘图功能](/02.Gui.Features.in.OpenCV/02.3.Drawing.Functions.in.OpenCV)
#### [2.4 鼠标作为画笔](/02.Gui.Features.in.OpenCV/02.4.Mouse.as.a.Paint-Brush)
#### [2.5 轨迹栏作为调色板](/02.Gui.Features.in.OpenCV/02.5.Trackbar.as.the.Color.Palette)

### 3 Core Operations | 核心操作
In this section you will learn basic operations on image like pixel editing, geometric transformations, code optimization, some mathematical tools etc.
#### [3.1 图像的基本操作](/03.Core.Operations/03.1.Basic.Operations.on.Images.md)
#### [3.2 图像上的算法运算](/03.Core.Operations/03.2.Arithmetic.Operations.on.Images)
#### [3.3 性能衡量和提升技术](/03.Core.Operations/03.3.Performance.Measurement.and.Improvement.Techniques)

### 4 Image Processing in OpenCV | OpenCV中的图像处理
In this section you will learn different image processing functions inside OpenCV.
#### [4.1 改变颜色空间](/04.Image.Processing.in.OpenCV/04.1.Changing.Colorspaces)
#### [4.2 图像几何变换](/04.Image.Processing.in.OpenCV/04.2.Geometric.Transformations.of.Images)
#### [4.3 图像阈值](/04.Image.Processing.in.OpenCV/04.3.Image.Thresholding)
#### [4.4 图像平滑](/04.Image.Processing.in.OpenCV/04.4.Smoothing.Images)
#### [4.5 形态转换](/04.Image.Processing.in.OpenCV/04.5.Morphological.Transformations)
#### [4.6 图像梯度](/04.Image.Processing.in.OpenCV/04.6.Image.Gradients)
#### [4.7 Canny边缘检测](/04.Image.Processing.in.OpenCV/04.7.Canny.Edge.Detection)
#### [4.8 图像金字塔](/04.Image.Processing.in.OpenCV/04.8.Image.Pyramids)
#### [4.9.1 OpenCV中的轮廓](/04.Image.Processing.in.OpenCV/04.9.1.Contours.Getting.Started)
#### [4.9.2 轮廓特征](/04.Image.Processing.in.OpenCV/04.9.2.Contour.Features)
#### [4.9.3 轮廓属性](/04.Image.Processing.in.OpenCV/04.9.3.Contour.Properties)
#### [4.9.4 轮廓：更多属性](/04.Image.Processing.in.OpenCV/04.9.4.Contours.More.Functions)
#### [4.9.5 轮廓分层](/04.Image.Processing.in.OpenCV/04.9.5.Contours.Hierarchy)
#### [4.10.1 直方图-1：查找，绘制，分析](/04.Image.Processing.in.OpenCV/04.10.1.Histograms-1.Find.Plot.Analyze)
#### [4.10.2 直方图-2：直方图均衡](/04.Image.Processing.in.OpenCV/4.10.2.Histograms-2.Histogram.Equalization)
#### [4.10.3 直方图3：二维直方图](/04.Image.Processing.in.OpenCV/04.10.3.Histograms-3.2D.Histograms)
#### [4.10.4 直方图-4：直方图反投影](/04.Image.Processing.in.OpenCV/04.10.4.Histogram-4.Histogram.Backprojection)
#### [4.11 傅里叶变换](/04.Image.Processing.in.OpenCV/04.11.Image.Transforms.in.OpenCV)
#### [4.12 模板匹配](/04.Image.Processing.in.OpenCV/04.12.Template.Matching)
#### [4.13 霍夫线变换](/04.Image.Processing.in.OpenCV/04.13.Hough.Line.Transform)
#### [4.14 霍夫圈变换](/04.Image.Processing.in.OpenCV/04.14.Hough.Circle.Transform)
#### [4.15 图像分割与分水岭算法](/04.Image.Processing.in.OpenCV/04.15.Image.Segmentation.with.Watershed.Algorithm)
#### [4.16 交互式前景提取使用GrabCut算法](/04.Image.Processing.in.OpenCV/04.16.Interactive.Foreground.Extraction.using.GrabCut.Algorithm)

### 5 Feature Detection and Description | 特征检测与描述
In this section you will learn about feature detectors and descriptors
#### [5.1 理解特征](/05.Feature.Detection.and.Description/05.1.Understanding.Features)
#### [5.2 哈里斯角检测](/05.Feature.Detection.and.Description/05.2.Harris.Corner.Detection)
#### [5.3 Shi-Tomasi拐角探测器和良好的跟踪功能](/05.Feature.Detection.and.Description/05.3.Shi-Tomasi.Corner.Detector-Good.Features.to.Track)
#### [5.4 SIFT（尺度不变特征变换）简介](/05.Feature.Detection.and.Description/05.4.Introduction.to.SIFT)
#### [5.5 SURF简介（加速的强大功能）](/05.Feature.Detection.and.Description/05.5.Introduction.to.SURF)
#### [5.6 用于角点检测的FAST算法](/05.Feature.Detection.and.Description/05.6.FAST.Algorithm.for.Corner.Detection)
#### [5.7 BRIEF（二进制的鲁棒独立基本特征）](/05.Feature.Detection.and.Description/05.7.BRIEF)
#### [5.8 ORB（定向快速和旋转简要）](/05.Feature.Detection.and.Description/05.8.ORB)
#### [5.9 特征匹配](/05.Feature.Detection.and.Description/05.9.Feature.Matching)
#### [5.10 特征匹配+单应性查找对象](/05.Feature.Detection.and.Description/05.10.Feature.Matching-Homography.to.find.Objects)

### 6 Video analysis (video module) | 视频分析
In this section you will learn different techniques to work with videos like object tracking etc.
#### [6.1 如何使用背景分离方法](/06.Video.analysis/06.1.How.to.Use.Background.Subtraction.Methods)
#### [6.2 Meanshift和Camshift](/06.Video.analysis/06.2.Meanshift.and.Camshift)
#### [6.3 光流](/06.Video.analysis/06.3.Optical.Flow)

### 7 相机校准和3D重建
In this section we will learn about camera calibration, stereo imaging etc.
#### [7.1 相机校准](/07.Camera.Calibration.and.3D.Reconstruction/07.1.Camera.Calibration)
#### [7.2 姿态估计](/07.Camera.Calibration.and.3D.Reconstruction/07.2.Pose.Estimation)
#### [7.3 对极几何](/07.Camera.Calibration.and.3D.Reconstruction/07.3.Epipolar.Geometry)
#### [7.4 立体图像的深度图](/07.Camera.Calibration.and.3D.Reconstruction/07.4.Depth.Map.from.Stereo.Images)

### 8 Machine Learning | 机器学习
In this section you will learn different image processing functions inside OpenCV.
#### 8.1 K-Nearest Neighbour
Learn to use kNN for classification Plus learn about handwritten digit recognition using kNN
##### [8.1.1 Understanding k-Nearest Neighbour | 理解KNN](/08.Machine.Learning/08.1.1.Understanding.k-Nearest.Neighbour)  
Get a basic understanding of what kNN is
##### [8.1.2 OCR of Hand-written Data using kNN | 使用OCR手写数据集运行 KNN](/08.Machine.Learning/08.1.2.OCR.of.Hand-written.Data.using.kNN)  
Now let's use kNN in OpenCV for digit recognition OCR
#### 8.2 Support Vector Machines (SVM)
Understand concepts of SVM
##### [8.2.1 Understanding SVM |  理解SVM](/08.Machine.Learning/08.2.1.Understanding.SVM)  
Get a basic understanding of what SVM is
##### [8.2.2 OCR of Hand-written Data using SVM | 使用OCR手写数据集运行SVM](/08.Machine.Learning/08.2.2.OCR.of.Hand-written.Data.using.SVM)  
Let's use SVM functionalities in OpenCV
#### 8.3 K-Means Clustering
Learn to use K-Means Clustering to group data to a number of clusters. Plus learn to do color quantization using K-Means Clustering
##### [8.3.1 Understanding K-Means Clustering | 理解K均值聚类](/08.Machine.Learning/08.3.1.Understanding.K-Means.Clustering)  
Read to get an intuitive understanding of K-Means Clustering
##### [8.3.2 K-Means Clustering in OpenCV | OpenCV中的K均值](/08.Machine.Learning/08.3.2.K-Means.Clustering.in.OpenCV)  
Now let's try K-Means functions in OpenCV

### 9 计算摄影学
In this section you will learn different computational photography techniques like image denoising etc.
#### [9.1 图像去噪](/09.Computational.Photography/09.1.Image.Denoising)
#### [9.2 图像修补](/09.Computational.Photography/09.2.Image.Inpainting)
#### [9.3 高动态范围](/09.Computational.Photography/09.3.High.Dynamic.Range)

### 10 目标检测
In this section you will learn object detection techniques like face detection etc.
#### [10.1 级联分类器](/10.Object.Detection/10.1.Cascade.Classifier)
#### [10.2 级联分类器训练](/10.Object.Detection/10.2.Cascade.Classifier.Training)

### OpenCV-Python Binding
In this section, we will see how OpenCV-Python bindings are generated
#### [11.1 OpenCV-Python Bindings](/11.OpenCV-Python.Bindings/11.1.OpenCV-Python.Bindings)

# 关于

{% include fooder.html %}