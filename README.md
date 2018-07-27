# MobileFaceNet_ncnn
use NCNN to run a MobileFaceNet demo on Linux

## instructions
0.install Qt
1.install opencv2.4.13(should be 2.4.x)
2.download and compile ncnn[https://github.com/Tencent/ncnn]
  in this step, you can chose to use x86 or ARM. ARM is faster than x86 on Debian 9 i7-3770k@3.5GHz
3.copy ncnn-master/src and ncnn-master/build/src/*.cpp and *.h to your project path replace mine
4.replace the opencv include and lib path in the project file of Qt
5.build the project
6.put your model in the build_file/src/
7.modify the path to your model and test_dataset in main.cpp
8.run
