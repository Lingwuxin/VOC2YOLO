VOC2YOLO
===
VOC数据集转YOLO数据集
===
一个将VOC格式的数据集标签转换成YOLO格式的数据集标签的脚本
---
<br>
遍历并转换数据集标签的方法如下

```
vtoy=HandleVocData()
vtoy(path='datasets_labels_path',savepath='labels_savepath')
```
在遍历所有VOC格式的数据集标签后获取class.txt

```
vtoy.makeClassFile()
```

或者

```
print(vtoy.class_txt_dict)
```
