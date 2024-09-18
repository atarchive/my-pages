---
title: Welcome to my blog
---
# 大模型推理加速器
## MECLA
### motivation
- 针对存储优化
- (token和维度)(attention层和FFN的占比)
- (针对FFN和QKV的优化)
- FC计算的时候由于算力不够，需要不断移动权重，考虑压缩
- batch？
- 需要再学习一下transformer
- 
### solution
- sub-matrix partition(SSMP)
- 从一个block派生出来其他的block
- 分块，每个块再进行拆分
- finetune:（量化?）(精度甚至不掉or提高??)
- 匹配硬件 
- 动态调整
- 知识蒸馏？

## Tender
- 针对outlier的？
- 量化(不同的量化方法的精度影响)
- 
