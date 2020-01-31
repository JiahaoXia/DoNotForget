### Details Related to Tensorflow
##### 1. [tf.train.Example usage](https://blog.csdn.net/hfutdog/article/details/86244944)
##### 2. [tensorflow 三种保存格式](https://zhuanlan.zhihu.com/p/60064947)
</br>(1) checkpoint(*.ckpt)
</br>---model.ckpt-240000.data-00000-of-00001: 
</br>---model.ckpt-240000.index: 描述variable中key和value的对应关系
</br>---model.ckpt-240000.meta: tensorflow完整的网络图结构
</br>(2) GraphDef(*.pb)
</br>包含protobuf对象序列化后的数据，包含了计算图，可以从中得到所有运算符(operators）的细节，也包含tensors
</br>(3) SavedModel
</br>该格式为 GraphDef 和 CheckPoint 的结合体，另外还有标记模型输入和输出参数的 SignatureDef。从 SavedModel 中可以提取 GraphDef 和 CheckPoint 对象
### Learning Materials 
##### 1. [斯坦福tensorflow教程](https://www.jianshu.com/p/c2692590e00f)
##### 2. [CS 20: Tensorflow for Deep Learning Research](https://web.stanford.edu/class/cs20si/syllabus.html)
