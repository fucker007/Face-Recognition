人脸识别电脑开机锁  
============================  
安装本项目  
-------------  
本项目无需安装下载即可用  
```git clone https://github.com/fucker007/Face-Recognition.git```  
相关报错  
--------------    

#执行main.py  
```$python main.py```  
#如果你无法运行，缺少cv2  
```$pip install opencv-python```    
#如果报错ModuleNotFoundError: No module named 'sklearn.cross_validation'  

#将对应的引入文件改为  
```from sklearn.model_selection import KFold```   
```from sklearn.model_selection import train_test_split```    
最后缺少什么包就安装什么包就可以。  

运行步骤  
-------------  
*1 录入图片
*2 训练模型
*3 测试识别效果

