本仓库包含测试yolov8预训练模型性能的相关文件
new_coco_road.py为总离线测试脚本
以.pt结尾的三个模型为在线推理使用的模型
以.om结尾的三个模型为离线推理使用的模型
1080.zip是约30张分辨率为1920*1080的图片，用于测试模型推理对应分辨率图片时的速度
new_coco_road2017.json为coco2017数据集的验证集的图片的标注文件，含有5000张图片的标注信息，以json形式存储，用于测试模型推理coco数据集图片时的精准度
coco2017验证集所包含图片共5000张，由于体积过大无法传入，可去[https://blog.csdn.net/weixin_43599336/article/details/86533575](http://images.cocodataset.org/zips/val2017.zip) 自行下载
