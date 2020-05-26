# week8 百度语音识别&语音合成
## 一、语音识别   Automatic Speech Recognition（ASR）
1. 百度API平台的短语音识别，支持识别多种语言，包括方言
2. 只支持 pcm/wav/amr 格式，极速版额外支持m4a 格式
3. 百度的短语音识别最大支持音频为60s
## 二、语音合成   Text-to-Speach（TTS)
1. 语音合成是将计算机自己产生的、或外部输入的文字信息转变为可以听得懂的、流利的汉语口语输出的技术。
## 三、视频转换为音频
1. 采用python自带的 **moviepy** 模块
2. 下载命令
```
pip install moviepy
```
3. 改模块还可用于剪辑音频，可一段一段剪，也可批量剪
