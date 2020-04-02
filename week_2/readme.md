# :neckbeard: 本周主要内容
1. API文档阅读以及计算机视觉入门（认知服务）
2. 尝试使用微软Azure、face++等AI开放平台返回人脸识别结果
3. 使用requests，用代码获得API回复
4. 将返回的json数据用pandas黑魔法用数据框的形式展示
## :dizzy: 感想
1. 我在作业中使用的AI开放平台相关API文档
   1. [微软Azure](https://westus.dev.cognitive.microsoft.com/docs/services/563879b61984550e40cbbe8d/operations/563879b61984550f30395236)
   2. [face++](https://console.faceplusplus.com.cn/documents/4888373)
   3. [百度AI](https://ai.baidu.com/ai-doc/FACE/yk37c1u4t)
2. 使用感想   
   Azure和face++的api文档阅读起来非常方便，简洁又有逻辑，代码示例也很简单，百度的相对起来就要麻烦许多。Azure和face++平台只需要注册账号获取相应的key和url，而百度需要获取url、apikey、secretkey，还需创建一个api应用才可以调用。我还尝试过使用腾讯的AI开放平台，但比百度的还要麻烦许多，且api文档写的不是很简洁。Azure的缺点是申请免费账户时需要有visa卡或大王卡，但本人都没有，只能申请为期7天的试用账户，所以我更偏爱face++.
## :foggy: 转换成表格
1. pandas黑魔法
```
import pandas as pd
from pandas.io.json import json_normalize
```
json_normalize()可以将json转换成表格形式   
2. pandas常规方法   
pd.DataFrame()   
**json_normalize比dataframe灵活，且更加使用**
## :ocean: 数据缺失的填充   
```
import numpy as np
```
导入这个模块，使用模块里的fillna()函数
