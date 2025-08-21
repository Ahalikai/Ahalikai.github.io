李 凯

15380251715	Aha15380251715@gmail.com

广东省深圳市南山区学苑大道1088号 南方科技大学 (518055)

# 教育背景
2023.09–2026.06	  硕士 研究生	      南方科技大学 (深圳，双一流)	    电子信息（计算机方向）

2018.09–2022.06	  学士 本科	        江西水利电力大学 (南昌)	        计算机科学与技术专业

2019.07–2019.08	北京大学暑期访学

2020.01–2020.09 武汉大学计算机学院访学

# 科研经历
## 学术论文

[1] **Kai Li (李凯)**, Ruihao Zheng, Xinye Hao, Zhenkun Wang*, Multi-Objective Infeasibility Diagnosis for Routing Problems Using Large Language Models, arXiv preprint arXiv:2508.03406. (**CCF A**, Under Review)

[2] **Kai Li (李凯)**, Fei Liu, Zhenkun Wang*, Xialiang Tong, Xiongwei Han, Mingxuan Yuan, Qingfu Zhang, ARS: Automatic Routing Solver with Large Language Models, arXiv preprint arXiv:2502.15359. (**CCF A**, Under Review)

[3] **Kai Li (李凯)**, Kangnian Lin, Ruihao Zheng, Zhenkun Wang*, Selection Strategy Based on Proper Pareto Optimality in Evolutionary Multi-Objective Optimization, International Conference on Parallel Problem Solving From Nature, 2024. (PPSN, **CCF B**)

[4] **Kai Li (李凯)**, Hui Wang*, Wenjun Wang, Feng Wang, Zhihua Cui, Improving Artificial Bee Colony Algorithm Using Modified Nearest Neighbor Sequence, Journal of King Saud University - Computer and Information Sciences, 2022, 34(10): 8807-8824.  (**SCI**, IF: 13.473)

[5] **Kai Li (李凯)**, Minyang Xu, Tao Zeng, Tingyu Ye, Luqi Zhang, Wenjun Wang, Hui Wang*, A new artificial bee colony algorithm based on modified search strategy, International Journal of Computing Science and Mathematics, 2022, 15(4): 387-395. (**SCI**)

[6] Xin Li, **Kai Li (李凯)**, Tao Zeng, Tingyu Ye, Luqi Zhang, Hui Wang*, Artificial bee colony with multiple search strategies and a new updating mechanism, International Journal of Computing Science and Mathematics, 2023, 18(1): 44-53. (**SCI**)


## 发明专利
[1] **李凯**,甘建军,冯祥胜. 基于AOD-Net的交通道路图像大气能见度检测方法[P]. 江西省：CN112330675B, 2022-08-23. (**授权**, 专利号：ZL202011472880.4)

## 计算机软件著作权
[1] NIT Online Judge 系统.(授权编号：2019R11L1414923)

[2] 海上搜索查询资源系统.(授权编号：2019R11L117810)

[3] 基于MFC实现的人工智能斗地主游戏软件.(授权编号：2019R11L1415137)

[4] NIT瑶湖学院学生综合素质评价管理系统.(授权编号：2019R11L1415296)

# 工作经历
## 2023.01-2023.08                                   上海驭矩信息科技有限公司                             机器视觉工程师

训练Yolo-v7 (TensorRT推理) 识别码头吊具，并用LSD检测机械边缘，从而实时检测位姿状态情况。

为监测雷达点云的鬼点现象，搭建深度学习的雨、雪、雾等气象检测算法 (应用本人的发明专利)。

采用Yolact对码头箱体进行实例分割，再用OpenCV提取图像特征，实现抓箱孔外的闭锁检测。

采用DarkNet框架，轻量化车道线模型(SCNN、Ultra Fast)，并重写为C++的.cfg模型，落地应用。

## 2022.02-2022.06                                 商汤科技-上海人工智能实验室                                见习研究员

基于Pytorch实现2D车道线检测算法 (SCNN、Ultra Fast)、3D车道线检测算法 (3D-LaneNet、Gen-LaneNet) 以及半监督方法 (Mean Teacher、Noisy Student)。

搭建离线车道线真值系统：载入预训练模型、构建Multi-Optimizer、利用Pseudo Label提升算法性能。

参加Waymo 3D Semantic Segmentation Challenge：利用多帧融合对道路上的23类点云信息（如汽车、摩托车、行人等）进行分类，算法性能排名第一。

## 2020.05-2020.09                       东软集团股份有限公司-江西省人民医院                      见习软件工程师
开发“挂号直通车”功能：根据患者过往挂号记录，个性化引导患者，节省患者时间。搭建流程引擎，调用HIS接口，查询SQL Sever中已有的挂号记录，采用C#设计WinForm窗体并显示。

沟通院方需求、完善设备功能、利用PR修改视频、发行新版本、利用C#对设备进行批量更新。

与公司其他部门共同对PDA、医护机器人等设备进行配置，在疫情期间助力医疗信息化、智能化。

# 实践项目
## 2025.04-至今                          基于大语言模型的路径问题多目标不可行性诊断方法                第一作者

针对用户需求不合理、模型没有可行域的不完备问题，提出了一种基于多目标优化的自动路径求解器。该求解器以路径长度和约束程度为优化目标，能够生成一组不同程度模型修改的代表性路径方案。

构建模型诊断系统：利用LLM Agent生成方案分析程序，依据代表性方案为用户提供多样化的诊断建议。

第一作者完成 Multi-Objective Infeasibility Diagnosis for Routing Problems Using Large Language Models (已投稿**CCF A**会议)。

## 2024.01-2025.03                   基于大语言模型的车辆路径问题建模与自动算法设计                第一作者

与华为诺亚方舟实验室联合发布 RoutBench 数据集：面向现实车辆路径问题，涵盖上千类不同场景。

提出基于大语言模型的通用算法设计范式：构建自动路径求解器，实现用户提出需求，无需专家介入，直接产出方案。ARS通过LLM Agent理解用户需求自动设计算法，并结合启发式策略高效处理新的问题。

ARS能够自动处理91.67％的常见车辆路径问题，并在各类问题上比其他七个LLM方法提升至少30%。

第一作者完成 ARS: Automatic Routing Solver with Large Language Models (已投稿**CCF A**会议)。

## 2019.05-2020.05                基于深度学习的交通道路图像大气能见度监测方法研究              项目负责人

重构经典大气光散射模型，并利用深度学习算法AOD-Net对大气光散射模型中的K(x)参数进行估算。

将AOD-Net产出的K(x)输入清晰图像重建模型，生成去雾后的清晰图像。

针对图像中不同物体因景深差异受雾影响不同的特点，通过对清晰图像与原始图像的网格化相似度对比，分析雾体影响的不均匀性，进而计算能见度级别。

PC端：采用PyQt搭建GUI；Web端：SSM+Flask调用算法，VUE+Element-UI+ECharts可视化。

视频讲解：https://www.bilibili.com/video/BV1Av4y1d71z/


# 访学经历
## 2020.01-2020.09                                              武汉大学                                                  计算机学院

XXX作战实验设计平台：编写NSGAⅡ对XXX多目标代理模型进行求解，并使用PyQt搭建GUI。

救灾物资调度系统：基于人工蜂群算法构建物资调度模型，结合AirGis和Qt实现调配方案的可视化。

无人机群仿真平台：搭建AirSim平台，通过Shell控制Unreal Engine 4虚拟引擎中的无人机。

## 2019.07-2019.08                                              北京大学                                                       教务部

参加北京大学暑期学校(第三学期)，选修课程《ACM/ICPC竞赛训练》,《Applied Algorithms》。

# 专业技能
掌握 C++：参加 ACM-ICPC、奥林匹克信息学竞赛(NOIP)并获奖。

熟悉 Python：相关项目作品获2021年中国大学生计算机设计大赛-国家二等奖(排名第一)。

英语：四级已过，能阅读本专业外文文献，具有运用英文写作的科研训练经历。

# 个人链接

HomePage：https://AhaLiKai.github.io/

Google Scholar：https://scholar.google.com/citations?user=cSfbiYkAAAAJ
