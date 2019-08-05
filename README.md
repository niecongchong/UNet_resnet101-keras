# UNet-keras
### 代码组织形式

* `train.ipynb:`模型训练，包含超参设置、模型调用、训练、可视化。
* `test_crop_image.py:`模型测试，包含模型加载、测试、可视化。
* `dataloaders/generater.py:`数据加载，数据路径获取、图片读取、预处理及在线扩充。
* `model/unet_resnet101:`模型定义。
* `utils/loss.py:`损失函数，包含`dice_loss、ce_dice_loss、jaccard_loss(IoU loss)、ce_jaccard_loss、tversky_loss、focal_loss`
* `utils/metrics.py:`评价指标，包含`precision、recall、accuracy、iou、f1`等。
* `train.html:`训练过程记录，保存为html文件。
