1. AnnotatedTransformer.ipynb是一个由harvarnlp创建的详解transformer model的文件
   source: https://github.com/harvardnlp/annotated-transformer/blob/master/AnnotatedTransformer.ipynb

2. 创建annotated_transformer.ipynp的目的，是为了从inference_test()部分通过简单的数据流转，
   观察数据形状如何在各个block进行变换，深入理解transformer的整体结构以及attention原理

3. 当前完成的部分为Part I: Model Architecture, 当然也只是实现了模型验证，
   其他细节问题如scaling的作用、LayerNorm的作用将会在后续进行说明

4. 其他待完成内容：
   Part II: Model Traning
   Part III: A Real World Example
