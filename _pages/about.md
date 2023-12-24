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
- *2019.9 - 今* &emsp;&emsp;兰州大学 `985` `但西北偏北`  化学化工学院
  - 博士，化学信息学 (导师：姚小军教授)
  - 获博士生国家奖学金  2022.12         
  - 获博士生一等学业奖学金    2021.12
- *2015.9 - 2019.6*  青海大学 `211` `但西北偏北` 计算机技术与应用系 
  - 本科，计算机科学与技术
  - 获优秀毕业生表彰 2019.6
  - 获优秀学位论文表彰 2019.6


<span class='anchor' id='publications'></span>
# 📝 学术论文
### 代表性论文
[1] **Li, Yuquan†**, Hsieh, Chang-Yu†, ... & Yao, Xiaojun. "An adaptive graph learning method for automated molecular interactions and properties predictions." **Nature Machine Intelligence.** `2022 IF=23.8` `Top` 
[[HTML]](https://www.nature.com/articles/s42256-022-00501-8) [[PDF]](/pdf/2022a.pdf)

- 论文简介：我们提出数据集自适应图学习方法，旨在无人工干预的情况下适应给定数据集并学习出一个高性能的预测器。该方法设计了一个包含架构设计、训练超参数、优化器选择、误差函数选择的图学习配置空间，并自动完成架构设计、超参数设置、优化器以及损失函数选择，最终训练出一个用于完成下游任务的高性能集成预测器。

[2] **Li, Yuquan**, ... & Yao, Xiaojun. "Introducing block design in graph neural networks for molecular properties prediction." **Chemical Engineering Journal**. `2021 IF=16.7` `Top` 
[[HTML]](https://doi.org/10.1016/j.cej.2021.128817) [[PDF]](/pdf/2021a.pdf)

- 论文简介：鉴于图学习方法发展并非线性，不同学者的工作所设计的图网络代码实现互相之间存在较大差异，所以我们首先提出引入带有规范化层的块设计到图网络用于分子性质预测，一方面解决网络退化问题使得网络可以更深以增加表示学习能力，另一方面为自动图学习打下图网络模块标准化和可定制的坚实基础。

[3] Li, Pengyong†, **Li, Yuquan†**, ... & Yao, Xiaojun. "TrimNet : learning molecular representation from triplet messages for biomedicine." **Briefings in Bioinformatics**. `2021 IF=13.9` `Top` 
[[HTML]]( https://doi.org/10.1093/bib/bbaa266) [[PDF]](/pdf/2021c.pdf)

- 论文简介：尽管现有的图神经网络（GNN）模型在分子表征方面取得了显著进展，但仍存在一些局限性，例如参数数量庞大、计算效率不高以及对分子结构理解的局限性。为了克服这些挑战，文章提出了一种新的GNN架构——TrimNet。TrimNet的核心创新在于其三重信息机制（Triplet Message Mechanism），该机制通过原子-键-原子的结构来有效捕获分子的关键特征。这种方法不仅减少了模型的参数数量，提高了计算效率，还增强了模型对分子结构的理解和解释能力。

[4] Wang, Xiaorui.†, **Li, Yuquan†**, ... & Yao, Xiaojun. "RetroPrime: A Diverse, plausible and Transformer-based method for Single-Step retrosynthesis predictions." **Chemical Engineering Journal**. `2021 IF=16.7` `Top`
[[HTML]](https://doi.org/10.1016/j.cej.2021.129845) [[PDF]](/pdf/2021b.pdf)

- 论文简介：过去的有机化学逆合成预测工作，容易出现输出多样性不足和化学上的不可信赖性问题。RetroPrime通过集成化学家的逆合成策略，通过Transformer模型预测反应中心，从而将分子分解为合成子，然后通过另一个Transformer将合成子转换成反应物。

† Equal contribution

### 所有论文
#### 2023年度




- [2023e] Xiaodan Yin, Xiaorui Wang, **Yuquan Li**, Jike Wang, Yuwei Wang, Yafeng Deng, Tingjun Hou, Huanxiang Liu, Pei Luo, and Xiaojun Yao. "CODD-Pred: A Web Server for Efficient Target Identification and Bioactivity Prediction of Small Molecules." **Journal of Chemical Information and Modeling** 63.20 (2023): 6169-6176. [[HTML]](https://doi.org/10.1021/acs.jcim.3c00685) [[PDF]](/pdf/paper_2023e.pdf)
- [2023d] Jianmin Wang, Jiashun Mao, Chunyan Li, Hongxin Xiang, Xun Wang, Shuang Wang, Zixu Wang, Yangyang Chen, **Yuquan Li**, Heqi Sun, Kyoung Tai No, Tao Song, ,Xiangxiang Zeng. "An interface-based molecular generative framework for protein-protein interaction inhibitors." **bioRxiv** (2023): 2023-10.[[HTML]](https://doi.org/10.1101/2023.10.10.557742) [[PDF]](/pdf/paper_2023d.pdf)
- [2023c] Ruiqiang Lu, Jun Wang, Pengyong Li, **Yuquan Li**, Shuoyan Tan, Yiting Pan, Huanxiang Liu, Peng Gao, Guotong Xie, Xiaojun Yao. "Improving drug-target affinity prediction via feature fusion and knowledge distillation." **Briefings in Bioinformatics.** 24.3 (2023): bbad145. [[HTML]](https://doi.org/10.1093/bib/bbad145) 
- [2023b] Xiaorui Wang, Chang-Yu Hsieh, Xiaodan Yin, Jike Wang, **Yuquan Li**, Yafeng Deng, Dejun Jiang, Zhenxing Wu, Hongyan Du, Hongming Chen, Yun Li, Huanxiang Liu, Yuwei Wang, Pei Luo, Tingjun Hou, Xiaojun Yao.  "Generic Interpretable Reaction Condition Predictions with Open Reaction Condition Datasets and Unsupervised Learning of Reaction Center." **Research** 6 (2023): 0231. [[HTML]](https://doi.org/10.1101/2023.08.01.551396) [[PDF]](/pdf/paper_2023b.pdf)
- [2023a] Shuo Liu, Jialiang Yu, Ningxi Ni, Zidong Wang, Mengyun Chen, **Yuquan Li**, Chen Xu, Yahao Ding, Jun Zhang, Xiaojun Yao, Huanxiang Liu. "A versatile framework for drug-target interaction prediction by considering domain specific features." **bioRxiv** (2023): 2023-08. [[HTML]](https://doi.org/10.34133/research.0231) [[PDF]](/pdf/paper_2023a.pdf)

#### 2022年度
- [2022b] Dejun Jiang, Huiyong Sun, Jike Wang, Chang-Yu Hsieh, **Yuquan Li**, Zhenxing Wu, Dongsheng Cao, Jian Wu, Tingjun Hou. "Out-of-the-box deep learning prediction of quantum-mechanical partial charges by graph representation and transfer learning." **Briefings in Bioinformatics** 23.2 (2022): bbab597. [[HTML]](https://doi.org/10.1093/bib/bbab597) [[PDF]](/pdf/paper_2022b.pdf)
- [2022a] **Yuquan Li**, Chang-Yu Hsieh, Ruiqiang Lu, Xiaoqing Gong, Xiaorui Wang, Pengyong Li, Shuo Liu, Yanan Tian, Dejun Jiang, Jiaxian Yan, Qifeng Bai, Huanxiang Liu, Shengyu Zhang & Xiaojun Yao. "An adaptive graph learning method for automated molecular interactions and properties predictions." **Nature Machine Intelligence** 4.7 (2022): 645-651. [[HTML]](https://www.nature.com/articles/s42256-022-00501-8) [[PDF]](/pdf/paper_2022a.pdf)


#### 2021年度
- [2021c] Pengyong Li, **Yuquan Li**, Chang-Yu Hsieh, Shengyu Zhang, Xianggen Liu, Huanxiang Liu, Sen Song, Xiaojun Yao. "TrimNet: learning molecular representation from triplet messages for biomedicine." **Briefings in Bioinformatics** 22.4 (2021): bbaa266. [[HTML]]( https://doi.org/10.1093/bib/bbaa266) [[PDF]](/pdf/paper_2021c.pdf)
- [2021b] Xiaorui Wang, **Yuquan Li**, Jiezhong Qiu, Guangyong Chen, Huanxiang Liu, Benben Liao, Chang-Yu Hsieh, Xiaojun Yao. "RetroPrime: A Diverse, plausible and Transformer-based method for Single-Step retrosynthesis predictions." **Chemical Engineering Journal** 420 (2021): 129845. [[HTML]](https://doi.org/10.1016/j.cej.2021.129845) [[PDF]](/pdf/paper_2021b.pdf)
    
- [2021a] **Yuquan Li**, Pengyong Li, Xing Yang, Chang-Yu Hsieh, Shengyu Zhang, Xiaorui Wang, Ruiqiang Lu, Huanxiang Liu, Xiaojun Yao. "Introducing block design in graph neural networks for molecular properties prediction." **Chemical Engineering Journal** 414 (2021): 128817. [[HTML]](https://doi.org/10.1016/j.cej.2021.128817) [[PDF]](/pdf/paper_2021a.pdf)


<span class='anchor' id='jobs'></span> 
# 💼 工作经历
- 2022.7 - 2023.4 [智源人工智能研究院](https://www.baai.ac.cn/)
  - 部门：[付杰课题组](https://bigaidream.github.io/)
  - 岗位：算法实习生 
  - 工作内容：
      1. 弱监督分子原型学习Molecular rationale learning；
      2. 基于对比学习的半监督图学习
- 2020.8 - 2022.6 [腾讯公司](https://www.tencent.com/) [[实习证明PDF]](/pdf/job_2020_8.pdf) 
  - 部门：[量子实验室](https://quantum.tencent.com/) 
  - 岗位：研发-算法，理论组员工(实习)
  - 工作内容：
      1. 自动图学习分子性质、药物-靶标相互作用预测 `发表论文[1]`；
      2. 新型图神经网络架构研究 `发表论文[3]`

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

# 📃 党政工作

- 2020.12 &emsp;&emsp;&emsp;优秀研究生干部   荣誉 
- 2020.9-2021.9    防疫党员先锋队
- 2019.9-2020.9  团支部书记   
- 2019.9-2020.9  研究生会文艺部部长  
         
