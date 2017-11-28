# 检测算法集合

-  **人脸检测**  
    - 各种算法对比  
    准确性：face++>dlib>云从>NPD> PICO>Opecv  
    速度: PICO>NPD>dlib>opencv  
    
    - 肤色分割&adaboost  
    [人脸及肤色检测](https://github.com/smartadpole/SkinSplit)（速度极慢）  
    
    - 于仕琪人脸检测动态库（深圳大学）   
  [Win 版](https://github.com/smartadpole/libfacedetection) (*Visual Studio*)    
  [ARM 版](https://github.com/smartadpole/YSQfastfd)（*ARM硬件只能用该项目中测试使用的硬件*）  
    - Pico  
  [CODE](https://github.com/smartadpole/pico)
  [论文](https://arxiv.org/pdf/1305.4537.pdf)
  [主页](https://arxiv.org/abs/1305.4537)
  [解析](http://blog.csdn.net/u010333076/article/details/51397332)  
  720\*480大小的图片在不考虑检测效果的情况下，时间可以达到7ms左右；  
  检测效果很差   
    - NPD  
  [CODE](https://github.com/smartadpole/NPD) 
  [解析](http://blog.csdn.net/u010333076/article/details/51397332) 
  [论文](https://arxiv.org/pdf/1408.1656.pdf)
  [主页](https://arxiv.org/abs/1408.1656)
  [优化](http://blog.csdn.net/qq_14845119/article/details/52576902)(PCA降维、训练）  
  
    - TLD  
    [CODE](https://github.com/smartadpole/TLD)
    [分析](http://blog.csdn.net/crzy_sparrow/article/details/7398904)
    [论文](http://info.ee.surrey.ac.uk/Personal/Z.Kalal/Publications/2010_icip.pdf)  
    
    - JDA  
    [CODE](https://github.com/smartadpole/JDA)  
    
    - BBF  
    [分析](http://libccv.org/doc/doc-bbf/)  
       
- **运动检测**
    - [32种检测算法](https://github.com/smartadpole/bgslibrary)
