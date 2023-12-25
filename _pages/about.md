---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}


<span class='anchor' id='about-me'></span>

黎育权目前是兰大在读博士研究生。科研上着力于将AI的能力应用于临床前药物发现，如自动机器学习应用于分子相互作用和分子性质预测等，以第一作者身份发表Nature子刊论文一篇(Nature Machine Intelligence)，总发表SCI论文10篇(其中主要作者身份4篇顶刊)，谷歌H-index 5，论文总引用157次。获得MCM/ICM数学建模竞赛Meritorious Winner奖、蓝桥杯软件和信息技术专业人才大赛赛区一等奖。曾获唐敖庆化学奖学金、博士生国家奖学金。参与导师国家自然基金项目两项。担任Brefings in Bioinfomatics审稿人，为中国人工智能学会会员，中国计算机学会会员，中国化学会会员。

<!-- <a href='https://scholar.google.com/citations?user=lCJi22EAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. -->


主要研究兴趣包括: 
- 深度学习 / 图学习
- 分子相互作用和性质预测
- 人工智能驱动的药物设计 (AIDD)
- 自动机器学习 (AutoML)


<span class='anchor' id='educations'></span>
# 🎓 教育经历 
- ***2019.9 - 今* &emsp;&emsp;兰州大学** `985` `但西北偏北`  化学化工学院
  - 博士，化学信息学 (导师：姚小军教授)
  - 获博士生国家奖学金  2022.12         
  - 获博士生一等学业奖学金    2021.12
- ***2015.9 - 2019.6*  青海大学** `211` `但西北偏北` 计算机技术与应用系 
  - 本科，计算机科学与技术
  - 获优秀毕业生表彰 2019.6
  - 获优秀学位论文表彰 2019.6


<span class='anchor' id='publications'></span>
# 📝 学术论文
### 代表性论文
**[1]** **Li, Yuquan†**, Hsieh, Chang-Yu†, ... & Yao, Xiaojun. "An adaptive graph learning method for automated molecular interactions and properties predictions." **Nature Machine Intelligence.** `2022 IF=23.8` `Top` 
[[HTML]](https://www.nature.com/articles/s42256-022-00501-8) [[PDF]](/pdf/2022a.pdf)

- 论文简介：我们提出数据集自适应图学习方法，旨在无人工干预的情况下适应给定数据集并学习出一个高性能的预测器。该方法设计了一个包含架构设计、训练超参数、优化器选择、误差函数选择的图学习配置空间，并自动完成架构设计、超参数设置、优化器以及损失函数选择，最终训练出一个用于完成下游任务的高性能集成预测器。

**[2]** **Li, Yuquan**, ... & Yao, Xiaojun. "Introducing block design in graph neural networks for molecular properties prediction." **Chemical Engineering Journal**. `2021 IF=16.7` `Top` 
[[HTML]](https://doi.org/10.1016/j.cej.2021.128817) [[PDF]](/pdf/2021a.pdf)

- 论文简介：鉴于图学习方法发展并非线性，不同学者的工作所设计的图网络代码实现互相之间存在较大差异，所以我们首先提出引入带有规范化层的块设计到图网络用于分子性质预测，一方面解决网络退化问题使得网络可以更深以增加表示学习能力，另一方面为自动图学习打下图网络模块标准化和可定制的坚实基础。

**[3]** Li, Pengyong†, **Li, Yuquan†**, ... & Yao, Xiaojun. "TrimNet : learning molecular representation from triplet messages for biomedicine." **Briefings in Bioinformatics**. `2021 IF=13.9` `Top` 
[[HTML]]( https://doi.org/10.1093/bib/bbaa266) [[PDF]](/pdf/2021c.pdf)

- 论文简介：尽管现有的图神经网络（GNN）模型在分子表征方面取得了显著进展，但仍存在一些局限性，例如参数数量庞大、计算效率不高以及对分子结构理解的局限性。为了克服这些挑战，文章提出了一种新的GNN架构——TrimNet。TrimNet的核心创新在于其三重信息机制（Triplet Message Mechanism），该机制通过原子-键-原子的结构来有效捕获分子的关键特征。这种方法不仅减少了模型的参数数量，提高了计算效率，还增强了模型对分子结构的理解和解释能力。

**[4]** Wang, Xiaorui.†, **Li, Yuquan†**, ... & Yao, Xiaojun. "RetroPrime: A Diverse, plausible and Transformer-based method for Single-Step retrosynthesis predictions." **Chemical Engineering Journal**. `2021 IF=16.7` `Top`
[[HTML]](https://doi.org/10.1016/j.cej.2021.129845) [[PDF]](/pdf/2021b.pdf)

- 论文简介：过去的有机化学逆合成预测工作，容易出现输出多样性不足和化学上的不可信赖性问题。RetroPrime通过集成化学家的逆合成策略，通过Transformer模型预测反应中心，从而将分子分解为合成子，然后通过另一个Transformer将合成子转换成反应物。

† Equal contribution

### 所有论文
#### 2023年度

- **[2023e]** Xiaodan Yin, Xiaorui Wang, **Yuquan Li**, Jike Wang, Yuwei Wang, Yafeng Deng, Tingjun Hou, Huanxiang Liu, Pei Luo, and Xiaojun Yao. "CODD-Pred: A Web Server for Efficient Target Identification and Bioactivity Prediction of Small Molecules." **Journal of Chemical Information and Modeling** 63.20 (2023): 6169-6176. [[HTML]](https://doi.org/10.1021/acs.jcim.3c00685) [[PDF]](/pdf/paper_2023e.pdf)
- **[2023d]** Jianmin Wang, Jiashun Mao, Chunyan Li, Hongxin Xiang, Xun Wang, Shuang Wang, Zixu Wang, Yangyang Chen, **Yuquan Li**, Heqi Sun, Kyoung Tai No, Tao Song, ,Xiangxiang Zeng. "An interface-based molecular generative framework for protein-protein interaction inhibitors." **bioRxiv** (2023): 2023-10.[[HTML]](https://doi.org/10.1101/2023.10.10.557742) [[PDF]](/pdf/paper_2023d.pdf)
- **[2023c]** Ruiqiang Lu, Jun Wang, Pengyong Li, **Yuquan Li**, Shuoyan Tan, Yiting Pan, Huanxiang Liu, Peng Gao, Guotong Xie, Xiaojun Yao. "Improving drug-target affinity prediction via feature fusion and knowledge distillation." **Briefings in Bioinformatics.** 24.3 (2023): bbad145. [[HTML]](https://doi.org/10.1093/bib/bbad145) 
- **[2023b]** Xiaorui Wang, Chang-Yu Hsieh, Xiaodan Yin, Jike Wang, **Yuquan Li**, Yafeng Deng, Dejun Jiang, Zhenxing Wu, Hongyan Du, Hongming Chen, Yun Li, Huanxiang Liu, Yuwei Wang, Pei Luo, Tingjun Hou, Xiaojun Yao.  "Generic Interpretable Reaction Condition Predictions with Open Reaction Condition Datasets and Unsupervised Learning of Reaction Center." **Research** 6 (2023): 0231. [[HTML]](https://doi.org/10.1101/2023.08.01.551396) [[PDF]](/pdf/paper_2023b.pdf)
- **[2023a]** Shuo Liu, Jialiang Yu, Ningxi Ni, Zidong Wang, Mengyun Chen, **Yuquan Li**, Chen Xu, Yahao Ding, Jun Zhang, Xiaojun Yao, Huanxiang Liu. "A versatile framework for drug-target interaction prediction by considering domain specific features." **bioRxiv** (2023): 2023-08. [[HTML]](https://doi.org/10.34133/research.0231) [[PDF]](/pdf/paper_2023a.pdf)

#### 2022年度
- **[2022b]** Dejun Jiang, Huiyong Sun, Jike Wang, Chang-Yu Hsieh, **Yuquan Li**, Zhenxing Wu, Dongsheng Cao, Jian Wu, Tingjun Hou. "Out-of-the-box deep learning prediction of quantum-mechanical partial charges by graph representation and transfer learning." **Briefings in Bioinformatics** 23.2 (2022): bbab597. [[HTML]](https://doi.org/10.1093/bib/bbab597) [[PDF]](/pdf/paper_2022b.pdf)
- **[2022a]** **Yuquan Li**, Chang-Yu Hsieh, Ruiqiang Lu, Xiaoqing Gong, Xiaorui Wang, Pengyong Li, Shuo Liu, Yanan Tian, Dejun Jiang, Jiaxian Yan, Qifeng Bai, Huanxiang Liu, Shengyu Zhang & Xiaojun Yao. "An adaptive graph learning method for automated molecular interactions and properties predictions." **Nature Machine Intelligence** 4.7 (2022): 645-651. [[HTML]](https://www.nature.com/articles/s42256-022-00501-8) [[PDF]](/pdf/paper_2022a.pdf)


#### 2021年度
- **[2021c]** Pengyong Li, **Yuquan Li**, Chang-Yu Hsieh, Shengyu Zhang, Xianggen Liu, Huanxiang Liu, Sen Song, Xiaojun Yao. "TrimNet: learning molecular representation from triplet messages for biomedicine." **Briefings in Bioinformatics** 22.4 (2021): bbaa266. [[HTML]]( https://doi.org/10.1093/bib/bbaa266) [[PDF]](/pdf/paper_2021c.pdf)
- **[2021b]** Xiaorui Wang, **Yuquan Li**, Jiezhong Qiu, Guangyong Chen, Huanxiang Liu, Benben Liao, Chang-Yu Hsieh, Xiaojun Yao. "RetroPrime: A Diverse, plausible and Transformer-based method for Single-Step retrosynthesis predictions." **Chemical Engineering Journal** 420 (2021): 129845. [[HTML]](https://doi.org/10.1016/j.cej.2021.129845) [[PDF]](/pdf/paper_2021b.pdf)
    
- **[2021a]** **Yuquan Li**, Pengyong Li, Xing Yang, Chang-Yu Hsieh, Shengyu Zhang, Xiaorui Wang, Ruiqiang Lu, Huanxiang Liu, Xiaojun Yao. "Introducing block design in graph neural networks for molecular properties prediction." **Chemical Engineering Journal** 414 (2021): 128817. [[HTML]](https://doi.org/10.1016/j.cej.2021.128817) [[PDF]](/pdf/paper_2021a.pdf)


<span class='anchor' id='jobs'></span> 
# 💼 工作经历

## *2023.4 - 今*   返校科研工作
  - **进行科研项目1：**
    - 贡献度：90%, 
    - 现有难题：
    - 提出办法：
  - **进行科研项目2：**
    - 贡献度：50%, 其他50%由何牧天师弟、姚小军教授及其他同学提供
    - 现有难题：
    - 提出办法：

## *2022.7 - 2023.4* [智源人工智能研究院](https://www.baai.ac.cn/)**
  - 部门：[付杰课题组](https://bigaidream.github.io/)
  - 岗位：算法实习生 
  - 工作内容：开发先进的新型深度学习模型或框架，结合现有计算化学和生物信息学工具，解决临床前药物发现的一些挑战性难题，如数据样本量小、缺乏可解释性/泛化性/鲁棒性、预测性能差等
  - 离职原因：准备提前毕业事宜
  
  - **完成科研项目1：提出基于分子原型学习的对比学习，用于弱监督分子性质预测** 
    - 时间段：2022.7 - 2023.4
    - 贡献度：90%, 其他10%由付杰老师、姚小军教授和合作同学提供 
    - 现有难题：新药研发时针对靶点的具有准确标签的大样本数据集较难获取。
    - 提出办法：提出了基于分子原型学习的弱监督学习办法，充分利用少量标签数据和大量无标签数据学习知识。该方法使用一个可训练的神经网络从分子中提取的原型(rationale)，并将其与环境(environment)分离。然后基于提取的分子原型从大规模现有药物分子空间DrugSpaceX中寻找成药性高的原型分子集合。再随后基于原型分子集合筛选找到离原分子相近(标签距离+分子相似性)的分子作为原分子的原型增强(rationale augmentation)。最后基于原型增强进行对比学习，进而进行弱监督学习(基于AdaMatch修改的适用图数据的弱监督学习框架)。
    - 结果：只需少量的标签数据即可进行对无标签数据进行较为准确的预测。BACE数据集上使用10%标签数据，在剩下90%数据上预测AUC=0.83(另一个数据集HIV为AUC=0.75)，此结果不及预期故放弃写论文。

## *2020.8 - 2022.6* [腾讯公司](https://www.tencent.com/) [[实习证明PDF]](/pdf/job_2020_8.pdf) 
  - 部门：[量子实验室](https://quantum.tencent.com/) 
  - 岗位：研发-算法，理论组员工(实习)
  - 工作内容：开发先进的新型深度学习模型或框架，结合现有计算化学和生物信息学工具，解决临床前药物发现的一些挑战性难题，如数据样本量小、缺乏可解释性/泛化性/鲁棒性、预测性能差等
  - 离职原因：合同到期，且实习导师将更换工作单位，故没续实习
  - **完成科研项目3：提出语义伪标签的分子预训练，尝试完全不使用标签来进行分子性质预测**
    - 时间段：2021.12 - 2022.6
    - 贡献度：90%, 其他20%由韩昌俞老师、姚小军教授和合作同学提供
    - 现有难题：
    - 提出办法：
    - 结果： 
  - **完成科研项目2：提出自适应图学习用于自动化的药物-靶标相互作用和分子性质预测** [[HTML]](https://www.nature.com/articles/s42256-022-00501-8) [[PDF]](/pdf/2022a.pdf)
    - 时间段：2020.12 - 2021.12
    - 贡献度：80%, 其他20%由韩昌俞老师、姚小军教授和合作同学提供 
    - 现有难题：
    - 提出办法：
    - 结果： `发表论文GLAM[1]`
  - **完成科研项目1：基于三元消息传递机制的新型图神经网络** [[HTML]]( https://doi.org/10.1093/bib/bbaa266) [[PDF]](/pdf/2021c.pdf)
    - 时间段：2020.8 - 2022.12
    - 贡献度：50%, 其他50%由李鹏勇同学、韩昌俞老师、姚小军教授和合作同学提供
    - 现有难题：
    - 提出办法：
    - 结果： `发表论文TrimNet[3]`

## 2016.6 - 2020.8 早期科研工作
  - **早期科研项目3：引入块设计网络设计的图网络，进行分子性质预测** [[HTML]](https://doi.org/10.1016/j.cej.2021.128817) [[PDF]](/pdf/2021a.pdf)
    - 时间段：2019.9 - 2020.7（硕士一年级）
    - 贡献度：90%, 其他20%由姚小军教授及合作同学提供
    - 现有难题：
    - 提出办法：
    - 结果： 写入毕业论文，`发表论文BGNN[2]`
  - **早期科研项目2：基于机器学习的分子ADME/T性质在线预测网站** 
    - 时间段：2017.5 - 2018.6（本科大四）
    - 贡献度：70%, 其他30%由姚小军教授及合作同学提供
    - 现有难题：
    - 提出办法：
    - 结果：优秀本科学位论文
  - **早期科研项目1：基于Bagging集成学习增强的卷积神经网络**
    - 时间段：2016.6 - 2017.5 (本科大三)
    - 贡献度：100% 
    - 背景：2012年AlexNet夺冠，2014年VGG大热，2015年我开始关注机器学习和深度学习
    - 现有难题：
    - 提出办法：
    - 结果： 发表普刊一篇


<span class='anchor' id='competitions'></span>

# 🏅 竞赛经历
- *2020.3* 高能对撞粒子分类挑战赛 [[链接]](https://www.biendata.xyz/competition/jet/leaderboard/#:~:text=Passing-,yuquanli,-lipy) [[PDF]](/pdf/comp_2020_3.pdf)
  - `排名5/256`
  - 平台级，交叉学科竞赛，Biendata举办
- *2018.6* MCM/ICM数学建模竞赛 [[PDF]](/pdf/comp_2018_6.pdf)
  - `Meritorious Winner奖` `(Top 3%~7% of 20602 team)`，队长身份
  - 国家级，数学建模竞赛，工业与应用数学学会举办。 
- *2018.5* 全国高校“西普杯”信息安全铁人三项赛 [[PDF]](/pdf/comp_2018_5.pdf)
  - `赛区三等奖`
  - 国家级，信息安全竞赛，中国教育部主办
- *2018.4* “蓝桥杯〞软件和信息技术专业人才大赛java组 [[PDF]](/pdf/comp_2018_4.pdf) 
  - `赛区一等奖`，个人参赛
  - 国家级，算法设计类竞赛，中国工业和信息化部主办
- *2018.2* Kaggle餐厅访客预测竞赛 [[链接]](https://www.kaggle.com/competitions/recruit-restaurant-visitor-forecasting/leaderboard#:~:text=263-,yuquan.li,-0.51811) [[PDF]](/pdf/comp_2018_2.pdf) 
  - `排名117/2158`，队长身份
  - 平台级，机器学习竞赛，Kaggle机器学习竞赛平台
- *2017.11* 全国大学生数学建模竞赛 [[链接]](http://www.mcm.edu.cn/html_cn/node/47a37c00788711191a6333ef6d7f38c2.html) [[PDF]](/pdf/comp_2017_11.pdf) 
  - `赛区一等奖`，队长身份
  - 国家级，数学建模竞赛，中国工业与应用数学学会主办

<span class='anchor' id='rewards'></span>

# 🎉 奖项荣誉

- *2022.12* 博士生国家奖学金 [[链接]](https://chem.lzu.edu.cn/index.php?m=content&c=index&a=show&catid=77&id=8813)
- *2021.11* 唐敖庆化学奖学金 [[链接]](https://www.jlu.edu.cn/info/1095/50784.htm) [[PDF]](/pdf/rewards_2021_11.pdf) 

<span class='anchor' id='others'></span>

# 👨‍👩‍👧‍👦 学术共同体
- **审稿人**
  - Brefings in Bioinfomatics
- **学会**
  - 中国人工智能学会 会员
  - 中国计算机学会 会员
  - 中国化学会 会员

# 📃 党政工作

- 2020.12 &emsp;&emsp;&emsp;优秀研究生干部   荣誉 
- 2020.9-2021.9    防疫党员先锋队
- 2019.9-2020.9  团支部书记   
- 2019.9-2020.9  研究生会文艺部部长  
         
# 🔨 专业技能
- **编程与算法设计** `Python`：熟练使用python进行算法设计和性能优化。
- **图神经网络设计** `Pytorch`, `PyG`, `DGL`：熟练掌握Pytorch框架，PyTorch_Geometric和DGL图学习框架进行图学习科研工作。
- **自动机器学习算法** `AutoML`, `NAS`：自适应学习、自动机器学习、神经架构搜索。
- **信息学辅助药物发现** `CADD`, `AIDD`：利用化学信息学和生物信息学手段解决交叉学科中的特定问题，如活性预测、ADME/T性质评估、靶点筛选等。
- **网站设计与开发** `Flask`, `Django`, `H5`：熟练部署和制作人工智能网页应用。
- **提示词工程** `GPT4`, `DALL·E`：使用LLM等辅助科研和文书工作。