#执行main.py
$python main.py
#如果你无法运行，缺少cv2
$pip install opencv-python
#如果报错ModuleNotFoundError: No module named 'sklearn.cross_validation'

#将对应的引入文件改为
$from sklearn.model_selection import KFold
$from sklearn.model_selection import train_test_split
最后缺少什么包就安装什么包就可以。
