### chatgpt_api

https://github.com/popjane/free_chatgpt_api

 * API URL:https://free.v36.cm
 * API KEY:xxxxxxxxxxxxxxxxxxxxxxxxxxxxx

1. gpt-4o-mini（速度一般，若要体验极速回复，可购买付费API）
1. gpt-3.5-turbo-0125
1. gpt-3.5-turbo-1106
1. gpt-3.5-turbo
1. gpt-3.5-turbo-16k
1. net-gpt-3.5-turbo (可联网搜索模型-稳定性稍差)
1. whisper-1
1. dall-e-2

### gemini_api（YouTube视频）

* 知识检索
* OCR 
* 深度研究

`https://lmarena.ai/?mode=direct` ：大模型竞技场，大模型目前的评分

1. aistudio.google.com : 面向开发者研究平台
1. gemini.google.com : 面向用户的产品

通过aistudio获取免费api（RPM:每min最大限度 RPD：每天最大限度）Gemini 2.5 Flash

#### NotebookLM

1. 极低的幻觉率
1. 信息散落在各种数据源（视频 音频 PDF 网页）
1. 听音频播客解闷

 新建笔记-->上传来源，创建知识库
 提问-->每一句话都对应的原文引用
 “保存到笔记”-->将对话永久保存
 深入探究对话-->生成音频播客对话

#####  cherrystudio

联网搜索

#### 长上下文

百万token的上下文长度 和 知识库信息检索

#### 多模态OCR功能

识别图像

#### api pro

* 地区：美国
* 创建付款资料（身份大全）
* 添加付款方式：信用卡或借记卡（将卡片限额到最低）

#### 国内中转

自建一个免费的代理，将API转到国内--openai-gemini--将gemini的api格式转换为openai的格式
netlify-->deploy to netlify
域名--国内直连
  供应商--openai
  api密钥 填写 aistudio上的密钥
  api地址：https://enchanting-crepe-8ec788.netlify.app

#### 多key轮询

gemini-balance
在云服务器下载docker--部署上面的gemini

`API_KEYS=["  ","   "]`
`ALLOWED_TOKENS=["   "]`
`DATABASE_TYPE=sqlite`
`SQLITE_DATABASE=default_db`

#### 免费deep search

https://github.com/u14app/deep-research
