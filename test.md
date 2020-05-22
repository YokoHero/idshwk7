# idshwk7
使用的方法是课程提供的LSB算法

### 初始文件
* LSBSteg.py --隐藏算法的源程序
* origin.jpg --隐写的目标图片
* info.txt --有隐藏的信息（学号姓名）

### 生成文件
* result.jpg --将origin.jpg隐写后的图片
* decode.txt --将result.jpg解码后得到的信息（学号姓名）

### 加密方式
LSBSteg.py encode -i origin.jpg -o result.jpg -f info.txt

### 解密方式
LSBSteg.py decode -i result.jpg -o decode.txt
