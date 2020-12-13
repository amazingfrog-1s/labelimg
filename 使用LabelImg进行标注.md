# 使用LabelImg进行标注

​	使用LabelImg,标注文件统一保存为.xml

1. #### LabelImg的安装:

   https://github.com/tzutalin/labelImg

   (windows或者ubuntu都可以)

2. #### 使用方法:

   - 打开labelImg

   ```
   cd labelImg # 下载labelImg的路径
   python3 labelImg.py # 打开labelImg
   ```

   - 改变默认保存Annotations的路径: 点击左边`Change Save Dir`,选择当前文件夹下的`Annotations`
   
     ps. 每个种类的文件夹包括两个子目录: `\Annotations`和`\JPEGImages`
   
   - 快捷键:
     
     - W 新建矩形框
     - Ctrl+S 保存当前标注
     - A 前一张图
     - D 后一张图

**labels:**

烟雾: smog

   太阳: sun

   室内灯: lamp