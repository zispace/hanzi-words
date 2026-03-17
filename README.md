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

- 现代汉语词典
  - [x] 《现代汉语词典》（第 7 版，2016 年）
- [x] 《现代汉语大词典》（阮智富 / 郭忠新主编，上海辞书出版社）
- [x] 《近代汉语词典》（白维国 主编，上海教育出版社）
- [x] 《古代汉语词典》(第一版) 商务印书馆 2003
- [x] 现代汉语规范词典(第2、4版)

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
- 在线词典数据

[moe-yixingci]: http://www.moe.gov.cn/jyb_sjzl/ziliao/A19/201001/t20100115_75687.html

### 专名词库

- 人名 `person`
- 地名 `location`
  - 自2024年10月起，国家统计局不再公开统计用区划代码和城乡划分代码，仅作为工作中使用的内部资料。[原文](https://www.stats.gov.cn/hd/lyzx/zxgk/202509/t20250903_1960996.html)
  - 民政部行政区划（2026年起每年1月发布更新） [链接](https://dmfw.mca.gov.cn/XzqhVersionPublish.html)
  - 县级以上行政区划代码（1981年至今） [yescallop/areacodes](https://github.com/yescallop/areacodes)

## 附录

- 现代汉语常用词表（2008年草案/2021年第2版） 在[zispace/hanzi-words-cycb](https://github.com/zispace/hanzi-words-cycb)
- 《咬文嚼字》等年度字词、流行语，参见[zispace/hanzi-words-annual](https://github.com/zispace/hanzi-words-annual)
- 补充词表（百科词条、输入法词库、NLP词库等），参见[zispace/hanzi-words-ext](https://github.com/zispace/hanzi-words-ext)
