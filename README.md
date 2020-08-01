# 中文不良短文本语料库使用说明

本语料库为具有不良语义信息的应用描述信息合集。

采集方式：
我们采集多家应用市场上的应用描述信息，通过人工复核的方式进行筛查，筛选了具有不良语义信息的描述文本和正常应用描述文本。

分类：

| 名称 |  数据量 | 说明 |
| --- |  --- | --- | 
| legal_app_corpus.text |  5300  | 正常应用的描述合集 |
| objectionable_app_corpus.text |  1200  | 不良应用的描述合集 |

语料库的每条信息以 json 格式提供，每一行代表一条有效的 json 格式数据，json 字段说明：

| 字段名 |  说明 |
| --- |  --- | 
| des_id |  描述信息 ID |
| app_name |  采集到的应用名称 |
| app_description |  应用描述信息 |


本库主要用于不良语义信息的相关研究使用。

# 版权说明
本项目为非商业项目，为纯搜集和汇总资料，如有侵权，请在issue下留言。

# Chinese Objectionable Short Corpus 
This corpus is a collection of application description information with objectionable semantic information.

Collection method:
We collected application description information from multiple application markets and screened them by manual review, and screened description texts with objectionable semantic information and normal application description texts.

Classification：

| name |  count | description |
| --- |  --- | --- | 
| legal_app_corpus |  5300  | normal application description |
| objectionable_app_corpus |  1200  | objectionable semantic information |

Each piece of information in the corpus is provided in json format, each line represents a valid json format data, json field description: 

| Field name |  description |
| --- |  --- | 
| des_id |  ID |
| app_name |  Collected application name |
| app_description |  Application description |

This corpus is mainly used for research related to objectionable semantic information.

# Copyright Notice

This project is a non-commercial project. It is purely collected and summarized. If there is any infringement, please leave a message under issue.
