# DLNLP
### 如何构建LSTM的输入数据（X）和标签(label)：
B：begin  E：end  M:middle   S:sigle


例如：小明喜欢自然语言处理的问题

分词后的结果为：小B明E喜B欢E自B然E语B言E处B理E的S问B题E

>训练数据：

1. 小 B
2. 小明 E
3. 小明喜 B
4. 小明喜欢 E
5. 小明喜欢自B
6. 小明喜欢自然E
7. 小明喜欢自然语B
8. 小明喜欢自然语言E
9. ......

