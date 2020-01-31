### Details Related to Tensorflow
##### 1. [tf.train.Example usage](https://blog.csdn.net/hfutdog/article/details/86244944)
##### 2. [tensorflow 三种保存格式](https://zhuanlan.zhihu.com/p/60064947)
</br>(1) checkpoint(*.ckpt)
---model.ckpt-240000.data-00000-of-00001: 
---model.ckpt-240000.index: 描述variable中key和value的对应关系
---model.ckpt-240000.meta: tensorflow完整的网络图结构
(2) GraphDef(*.pb)
包含protobuf对象序列化后的数据，包含了计算图，可以从中得到所有运算符(operators）的细节，也包含tensors
(3) SavedModel
该格式为 GraphDef 和 CheckPoint 的结合体，另外还有标记模型输入和输出参数的 SignatureDef。从 SavedModel 中可以提取 GraphDef 和 CheckPoint 对象
