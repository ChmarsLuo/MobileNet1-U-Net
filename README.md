# MobileNet-U-Net

##本文目的在于探索MobileNet系列(MobileNet V1、MobileNet V2、MobileNet V3)网络做U-Net编码阶段的backbone，正如我们知道轻量级神经网络MobileNet能很好地提取特征，有效的降低参数量。,那MobileNet和U-Net能查出什么样的火花呢，让我们拭目以待吧
**1.整个库一共包含以下内容：**  
|  
|————dataset:    
------------|————build:  
----------------------|————train:  
----------------------|————val:  
----------------------|————test:  
------------|————build_aug  
------------|reslut:    
|————logs:      
|————nets:      
---------|————unet    
---------|————mobilenetv1    
---------|————mobilenetv2    
---------|————mobilenetv3_small    
---------|————Mobilenetv3_large    
|————eval    
|————predict    
|————train     

**2.mobilenet系列网络做编码骨架**  
整个编码过程可以参考文件夹net中的代码  
|————nets:      
---------|————unet    
---------|————mobilenetv1    
---------|————mobilenetv2    
---------|————mobilenetv3_small    
---------|————Mobilenetv3_large  

**3.数据集**
本文所采用的数据集是马赛诸塞州建筑图
