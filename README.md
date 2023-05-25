# Awesome Chinese LLM: A curated list of Chinese Large Language Model

# Datasets

* [NKCorpus](https://gitee.com/lidongwen1997/nkunlp-preprocessing) - 利用海量网络数据构建大型高质量中文数据集
* [BELLE](https://github.com/LianjiaTech/BELLE/tree/main/data/10M) - 10M中文数据集
* [MOSS](https://github.com/OpenLMLab/MOSS#%E6%95%B0%E6%8D%AE) - MOSS训练数据
* [Chinese Scientific Literature Dataset](https://github.com/ydli-ai/CSL) - A Large-scale Chinese Scientific Literature Dataset 中文科学文献数据集
* [CLUECorpus2020](https://github.com/CLUEbenchmark/CLUECorpus2020/) - 通过对Common Crawl的中文部分进行语料清洗，最终得到100GB的高质量中文预训练语料
* [News Commentary v13](https://github.com/dbiir/UER-py/wiki/%E9%A2%84%E8%AE%AD%E7%BB%83%E6%95%B0%E6%8D%AE) - News Commentary v13包括平行语料
* [WuDaoCorpora Text文本预训练数据集](https://data.baai.ac.cn/details/WuDaoCorporaText) - 北京智源人工智能研究院（智源研究院）构建的大规模、高质量数据集
* [MNBVC(Massive Never-ending BT Vast Chinese corpus)超大规模中文语料集](https://github.com/esbatmop/MNBVC) - 对标chatGPT训练的40T数据。MNBVC数据集不但包括主流文化，也包括各个小众文化甚至火星文的数据。MNBVC数据集包括新闻、作文、小说、书籍、杂志、论文、台词、帖子、wiki、古诗、歌词、商品介绍、笑话、糗事、聊天记录等一切形式的纯文本中文数据。
* [chinese-poetry](https://github.com/chinese-poetry/chinese-poetry) - 最全中华古诗词数据库, 唐宋两朝近一万四千古诗人, 接近5.5万首唐诗加26万宋诗. 两宋时期1564位词人，21050首词。

# Pre-trained LLM

| Model | Size | Architecture | Repo/Chkpt | Paper | 
| ----- | ---- | ------------ | ----------- | ----- |
| 鹏程.盘古α | 13B | Decoder | [Github](https://github.com/huawei-noah/Pretrained-Language-Model) | [Paper](https://arxiv.org/pdf/2104.12369.pdf) |
| GLM | 130B | Decoder | [Github](https://github.com/THUDM/GLM-130B) | [Paper](https://arxiv.org/pdf/2210.02414.pdf) |
| MOSS | | | [Github](https://github.com/OpenLMLab/MOSS) |

# Instruction finetuned LLM
| Model | Owner | Backbone | Repo/Chkpt | Release Date | 
| ----- | ---- | ------------ | ----------- | ----- |
| ChatGLM-6B| [THUDM](https://github.com/THUDM) | GLM | [Github](https://github.com/THUDM/ChatGLM-6B) | 2023-03-16 |
| Chinese-Vicuna | [Facico](https://github.com/Facico) | LLaMA | [Github](https://github.com/Facico/Chinese-Vicuna) | 2023-03-23 |
| BELLE | [Ke Technologies](https://github.com/LianjiaTech) | LLaMA | [Github](https://github.com/LianjiaTech/BELLE) | 2023-03-26 |
| Luotuo | 商汤科技&华中师范大学 | GLM-6B | [Github](https://github.com/LC1332/Luotuo-Chinese-LLM) | 2023-03-31|
| 本草[原名：华驼(HuaTuo)]: 基于中文医学知识的LLaMA微调模型 | LLaMA | [Github](https://github.com/SCIR-HI/Huatuo-Llama-Med-Chinese) | 2023-03-31 |
| Phoenix | 港中文(深圳) | BLOOMZ | [Github](https://github.com/FreedomIntelligence/LLMZoo) | 2023-04-28 |
| Linly | [Computer Vision Institute, SZU](https://github.com/CVI-SZU) | LLaMA | [Github](https://github.com/CVI-SZU/Linly) | |
| LaWGPT: 基于中文法律知识的大语言模型| | Chinese-LLaMA、ChatGLM|  [Github](https://github.com/pengxiao-song/LaWGPT) | 2023-05-13 |


