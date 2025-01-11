# 汉语常用词表

数据原始来源见 `txt` 文件开头部分，词表数据有修正、合并、去重等处理。

## 格式说明

文件格式如下，文件开头以# 开头的几行是注释

```tsv
# 资源名
# 原始资料等注释说明
#
# 如果是多列，这个是TSV格式列名，第一列应是词语

词语
词语	列2	列3
```

## 文件

### 词典类 `dict`

**简体中文**

- 现代汉语常用词表
  - [x] 《现代汉语常用词表（草案）》2008 年
  - [ ] 《现代汉语常用词表》（第 2 版，2021 年）
- 现代汉语词典
  - [x] 《现代汉语词典》（第 7 版，2016 年）
- [x] 《现代汉语大词典》（阮智富 / 郭忠新主编，上海辞书出版社）
- [x] 《近代汉语词典》（白维国 主编，上海教育出版社）

**繁体中文**

- [x] 《中華語文大辭典》（2016 年）、《兩岸詞典》（兩岸差異用詞）
  - 中華語文知識庫 https://www.chinese-linguipedia.org
  - 中华语文知识库 https://www.zhonghuayuwen.org/ 【对应中国大陆简体版本】
- [x] 臺灣台語常用詞辭典

### 一般词表 `words`

- 汉语水平考试（HSK）
  - [x] 【新版】共三等九级：汉语水平考试于 2010 年起改用六级分级制（初等和中等），即新 HSK；《国际中文教育中文水平等级标准》2021 年，新增 HSK 7-9 级（高等）
  - [x] 【老版】甲乙丙丁四级：《中国汉语水平考试（HSK）办法》（1992 年发布）；《汉语水平词汇与汉字等级大纲（HSK）》（2001 年修订）
- 异形词整理表
  - [x] [《第一批异形词整理表》][moe-yixingci] 2001 年：338 组异形词以及【附录】含有非规范字的异形词（44 组）
  - [x] 《第二批异形词（草案）》非正式文件
  - [ ] 《现代汉语异形词规范手册》上海辞书出版社
- 其他词表
  - 古代年号
  - 词牌名
  - ……

[moe-yixingci]: http://www.moe.gov.cn/jyb_sjzl/ziliao/A19/201001/t20100115_75687.html

### 专名词库

- 人名
- 地名

---

## 补充资料

### 词典类资料

- 《现代汉语方言大词典》（PDF） <https://github.com/ZWolken/Great-Dictionary-of-Modern-Chinese-Dialects>
- 人名(人物、名人、文学家、字号、名字)词典索引 https://forum.freemdict.com/t/topic/15726
- 人名地名类辞典 10 部 https://forum.freemdict.com/t/topic/33176

### 输入法词库

- 搜狗输入法细胞词库 <https://github.com/zispace/dict-scel>, <https://pinyin.sogou.com/dict/>
- Rime 配置：雾凇拼音（简体词库） https://github.com/iDvel/rime-ice
- Rime 配置：白霜拼音 https://github.com/gaboolic/rime-frost
- 中文维基百科拼音词库（Fcitx 5） https://github.com/felixonmars/fcitx5-pinyin-zhwiki
- 单手笔顺输入法码表: <https://gitee.com/yq-ysy/one-hand_code> <https://github.com/YQ-YSY/stroke-seq_MB>
- 自建拼音输入法词库（Fcitx5/GBoard） https://github.com/wuhgit/CustomPinyinDictionary
- Gboard 词库语料库 https://github.com/entr0pia/corpus-of-gboard_dict_3

### 通用词库

- HanLP 词库 https://github.com/hankcs/HanLP
  - 数据包 [data-for-1.7.5.zip](https://file.hankcs.com/hanlp/data-for-1.7.5.zip)
- 敏感词/审查词汇总：https://github.com/hantang/data-corpus/tree/main/censorship
- 同义词 https://github.com/jaaack-wang/Chinese-Synonyms
  - 哈工大同义词词林扩展版 https://github.com/BiLiangLtd/WordSimilarity/tree/master/data, https://www.ltp-cloud.com/download
  - 同义词词林（梅家驹等，1983 年） https://forum.freemdict.com/t/topic/1211
- THUOCL 中文词库（IT、财经、成语、地名、历史名人、诗词、、医学、饮食、法律、汽车、动物等类）https://github.com/thunlp/THUOCL

### 专名类词库

- 中文、日文、英文人名语料库：https://github.com/wainshine/Chinese-Names-Corpus
- CCNC 大型中文姓名语料库 https://github.com/jaaack-wang/ccnc
- NER 数据集 https://github.com/GuocaiL/nlp_corpus
- 公司和机构名语料库 https://github.com/wainshine/Company-Names-Corpus
- 领域词汇知识库（涵盖 68 个领域、共计 916 万词） https://github.com/liuhuanyong/DomainWordsDict
