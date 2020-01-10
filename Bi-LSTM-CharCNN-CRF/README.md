# NER-pytorch
记录自己写的BILSTM-CRF、ELMo、BERT来做NER模型的代码

### Bi-LSTM-CharCNN-CRF

- model.py
  - 
- util.py  一些数据处理函数、构建embedding向量函数。
- span_util.py  
  - BIEOS->BIO 
  - BIO->BIEOS
  - 计算F1的函数（词级别的）restrict-f1首先将预测序列中的实体召回，方便计算准确率召回率F1。

- metrics.py

  - 从span_util.py 召回实体后计算准确率召回率F1。

- data.py

  - 构建词、字的词典等函数

- crf.py

- dataset文件夹

  conll2003数据集，格式转换成了，text-bieos-bio字典形式

  

  

  

  

  