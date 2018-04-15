# yolov3_visualstdio2015_gpu
The run-time system: Windows10 + x64 + Visual_Studio2015

First You need to download the yolov3 weights : https://pjreddie.com/darknet/yolo/

Then you  need other lib or configuration: CUDA 、CUDNN、 OpenCV 

If you have install CUDA、CUDNN and OpenCV:
   you need to find the yolov3Gpu.vcxproj in the project and revise the cuda path and add the libs.
   meanwhile you need to make sure the version of OpenCV and CUDNN.

The CUDA revise location of yolov3Gpu.vcxproj is in row 55 and 280.
The OpenCV revise location of yolov3Gpu.vcxproj is in row 73 74 and 101.


My Computer about the version of CUDA CUDNN OpenCV:

    CUDA8.0 + CUDNN6.5 + OpenCV3.3.1
    
The gpu version is faster and enjoy it.

My blog link : https://blog.csdn.net/small_munich/article/details/79721466
