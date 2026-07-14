# 健康地理

武汉大学资源与环境科学学院《健康地理学》课程(300035001012，2026夏季)

|Author|戴劭勍|
|---|---|
|E-mail|shaoqing.dai@outlook.com|

简介：本部分材料仅限于我授课的两部分内容：健康地理中的空间技术与健康地理中的人工智能。

# 大纲

#### 1 健康地理中的空间技术——感知与描绘健康格局
##### 1.1 引言：为什么需要空间视角
##### 1.2 健康地理中空间数据的获取 (感知)
###### 1.2.1 定位人与地点：Global Navigation Satellite System (GNSS)、Located Based Services (LBS)与地理编码(Geocoding)
###### 1.2.2 环境感知：Remote Sensing (RS)/Earth Observation (EO)
##### 1.3 健康地理中空间数据的处理与表征 (描绘)
###### 1.3.1 空间数据管理基础 (从数据库、GIS到城市大脑)
###### 1.3.2 核心空间操作：缓冲区分析、叠置分析、网络分析、空间插值
###### 1.3.3 环境暴露与人群特征的空间表征
##### 1.4 健康地理中空间模式与关联分析 (诊断人地关系)
###### 1.4.1 地理学三定律
###### 1.4.2 时空统计 (从点模式挖掘到空间回归)
###### 1.4.3 本章总结：从空间模式到对“复杂人地关系”的挖掘
#### 2 健康地理中的人工智能——赋能与洞察
##### 2.1 引言: AI如何赋能健康地理
##### 2.2 机器学习
###### 2.2.1 数据集
###### 2.2.2 分类任务
###### 2.2.3 预测任务
###### 2.2.4 性能评估
###### 2.2.5 集成学习
##### 2.3 深度学习
###### 2.3.1 计算机视觉（CV）应用：街景图像、遥感影像解读
###### 2.3.2 多模态数据集成与高级预测模型
##### 2.4 可解释人工智能（XAI）：打开“黑箱”，建立信任
##### 2.5 大语言模型（LLM）、生成式AI与Agent：知识引擎与决策辅助
###### 2.5.1 健康领域垂向大模型
###### 2.5.2 基础模型的微调与调整
###### 2.5.3 Agent元年 
###### 2.5.4 面向地理任务的Agent
##### 2.6 终极议题：融合、伦理与未来
###### 2.6.1 电车难题
###### 2.6.2 算法公平性、隐私保护与负责任创新

# 教案
## 第一章教案：健康地理中的空间技术——感知与描绘健康格局 (3学时)
### 第1-2讲：引言与数据获取
- 教学目标：理解健康地理空间视角的必要性；掌握GNSS/LBS与RS数据的基本原理与应用场景。
- 教学内容：
    - 总览：介绍三大模块逻辑关系。
    - 为什么需要空间视角？ 从约翰·斯诺霍乱地图到新冠疫情仪表盘。
    - 定位人与地点：GNSS/LBS原理，地理编码（Geocoding）实操演示（以医院、病例数据为例）。
    - 感知环境：遥感（RS）基本原理，展示NDVI、土地利用、夜间灯光等与健康相关的遥感产品，介绍GEE，planetary computer，AIE以及AEF等云平台与AI技术
- 教学活动：展示医院地理编码、基于可穿戴设备的实时环境暴露评估
### 第3-4讲：数据处理、表征与核心操作
- 教学目标：掌握GIS核心空间操作，能进行环境与人群的空间表征。
- 教学内容：
    - GIS数据管理基础：数据库、GIS、城市大脑。
    - 核心空间操作：缓冲区分析（食品环境暴露差异、绿地研究缓冲区选择）、叠置分析（环境暴露评估）、网络分析（医疗设施可达性、两步移动搜索法）、空间插值（污染物暴露插值）。
    - 环境/人群表征实践：春运迁徙的短期空气污染暴露疾病负担计算
- 教学活动：拆解春运迁徙的短期空气污染暴露疾病负担计算。
### 第5讲：空间模式与关联分析
- 教学目标：掌握时空统计与生物统计的基本思想，能解读其结果，并应用于相关的健康地理问题分析。
- 教学内容：
    - 地理学三定律：空间自相关性、空间异质性与空间相似性
    - 时空统计：Moran's I，LISA，Getis Ord G，Geostatistics, Satscan，Geodetector, Geographically Weighted Regression，Multi-level regression/OR,地理/时空归因框架，Explainable Artifical Intelligence(XAI) 。
    - 本章总结与桥接： 从空间模式到对“复杂人地关系”的挖掘    
- 教学活动：应用XAI分析基于通勤路径的建成环境暴露与肥胖关联。
## 第二章教案：健康地理中的人工智能——赋能与洞察 (3学时)
### 第6讲：AI如何赋能健康地理
- 教学目标：理解AI在健康地理中的赋能角色；掌握机器学习基本概念、分类与预测任务的基本流程。
- 教学内容：
    - AI赋能健康地理: EHJ街景CVD论文; ACM WWW 遥感+街景预测抑郁论文; 蚂蚁阿福AI医生。
    - 机器学习中的数据集划分。
    - 分类任务：遥感影像分类、CT影像分类。
    - 预测任务：代谢综合征得分建模(NC)。
    - 性能评估：交叉验证、评估指标与超参数调优
    - 集成学习：弱分类器组合的理念与消融实验
### 第7讲：深度学习
- 教学目标：深度学习在健康地理中的应用；主要包括街景图像、遥感影像以及多模态数据。
- 教学内容：
    - 计算机视觉与街景图像应用于健康地理：基于街景图像的建成环境审计；基于街景图像与多模态地理数据的居住环境评估。
    - 计算机视觉与遥感影像应用于健康地理：街景图像与遥感影像融合；基于FCN的遥感影像建筑物识别。
    - 多模态数据应用于健康地理：基于地理加权神经网络的高分辨率人口建模；基于多模态数据融合的城市可骑行性评估；多模态医疗大数据用于预测血糖波动与2型糖尿病风险。
### 第8讲：可解释AI、大语言模型与Agent
- 教学目标：认识“黑箱”问题的挑战与XAI的价值；了解LLM在健康地理中的潜力。
- 教学内容：
    - 可解释AI（XAI）：PDP与SHAP等方法如何帮助理解AI模型的决策。
    - LLM在健康地理中的应用场景：Dutch Style; 本草大模型; LLM生成社区健康状况预测; 基础大语言模型在肺癌筛查中临床决策潜力。
    - Agent元年: 从龙虾、养马、Claude Code、Codex到Open Code
    - 面向地理的Agent：MCP服务、Geocode、GeoAgent、CogitoAgent
### 第9讲：终极议题
- 教学目标：讨论AI相关的伦理限制，对技术伦理进行批判性思考；完成课程整体复盘。
- 教学内容：
    - 经典例子：电车难题。
    - 算法公平性、隐私保护与负责任创新：NEJM上的两篇AI时代下的冷思考。
    - 总结


## 参考书目及资料

### 书目

1. 吴息凤, 庄贵华, 金焰, 王超龙, 毛琛 (主编). (2026). *医学大数据与人工智能应用* (教育部101计划核心课程教材). 北京: 人民卫生出版社. ISBN: 9787117387644.

2. 施迅, 王法辉 (著). (2016). *地理信息技术在公共卫生和健康领域的应用*. 北京: 高等教育出版社. ISBN: 9787040440522.

3. 贾鹏 (著). (2024). *健康地理学*. 北京: 高等教育出版社. ISBN: 9787040634037.

4. 戴劭勍. (2024). *应用统计学与R语言实现笔记*. https://gisersqdai.top/Note-of-Applied-Statistics-with-R-Book/



### 期刊论文

1. Carletti, M., Pandit, J., Gadaleta, M., Chiang, D., Delgado, F., Quartuccio, K., Fernandez, B., Raygoza Garay, J. A., Torkamani, A., Miotto, R., Rossman, H., Berk, B., Baca-Motes, K., Kheterpal, V., Segal, E., Topol, E. J., Ramos, E., & Quer, G. (2025). Multimodal AI correlates of glucose spikes in people with normal glucose regulation, pre-diabetes and type 2 diabetes. *Nature Medicine*, *31*(9), 3121–3127. https://doi.org/10.1038/s41591-025-03849-7

2. Chen, Z., Dazard, J. E., Khalifa, Y., Motairek, I., Al-Kindi, S., & Rajagopalan, S. (2024). Artificial intelligence–based assessment of built environment from Google Street View and coronary artery disease prevalence. *European Heart Journal*, *45*(17), 1540–1549. https://doi.org/10.1093/eurheartj/ehae158

3. Christakis, N. A., & Fowler, J. H. (2007). The spread of obesity in a large social network over 32 years. *New England Journal of Medicine*, *357*(4), 370–379. https://doi.org/10.1056/NEJMsa066082

4. Dai, S., Li, Y., Stein, A., Yang, S., & Jia, P. (2024). Street view imagery-based built environment auditing tools: A systematic review. *International Journal of Geographical Information Science*, *38*(6), 1136–1157. https://doi.org/10.1080/13658816.2024.2336034

5. Dai, S., Zhao, W., Wang, Y., Huang, X., Chen, Z., Lei, J., Stein, A., & Jia, P. (2023). Assessing spatiotemporal bikeability using multi-source geospatial big data: A case study of Xiamen, China. *International Journal of Applied Earth Observation and Geoinformation*, *125*, 103539. https://doi.org/10.1016/j.jag.2023.103539

6. Dai, S., Zuo, S., & Ren, Y. (2020). A spatial database of CO2 emissions, urban form fragmentation and city-scale effect related impact factors for the low carbon urban system in Jinjiang city, China. *Data in Brief*, *29*, 105274. https://doi.org/10.1016/j.dib.2020.105274

7. Duan, H., Tan, L., Eils, R., et al. (2025). Multi-center benchmarking of large language models for clinical decision support in lung cancer screening. *Cell Reports Medicine*, *6*(10), 102465. https://doi.org/10.1016/j.xcrm.2025.102465

8. Guo, L., Liu, F., Zhu, W., Liu, J., Li, M., Wang, J., Wang, Z., Li, J., Wang, Y., Liu, B., Zhang, X., Yu, C., & Jiang, T. (2025). Pathways from early-life urbanicity to adult neurobehavioral traits via menarche timing. *Nature Cities*, *2*(12), 1226–1239. https://doi.org/10.1038/s44284-025-00352-5

9. Jia, P., Xue, H., Yin, L., Stein, A., Wang, M., & Wang, Y. (2019). Spatial technologies in obesity research: Current applications and future promise. *Trends in Endocrinology and Metabolism*, *30*(3), 211–223. https://doi.org/10.1016/j.tem.2018.12.003

10. Li, C., Yang, X., Qin, K., Yang, S., Dai, S., Yin, C., Yang, S., Shi, Y., & Jia, P. (2025). Effects of short-term exposure to air pollutants on real-time blood pressure: A wearable device-based study in China. *Journal of Urban Health*, *102*(5), 1011–1023. https://doi.org/10.1007/s11524-025-01017-3

11. Liu, C., Chen, Y., Shi, H., Lu, J., Jian, B., Pan, J., Cai, L., Wang, J., Yu, J., Gao, Z., Zhang, X., Bai, L., Zhang, Y., Li, J., Bercea, C. I., Ouyang, C., Chen, C., Xiong, Z., Wiestler, B., Wachinger, C., Duncan, J. S., Rueckert, D., Bai, W., & Arcucci, R. (2025). Does DINOv3 set a new medical vision standard? Benchmarking 2D and 3D classification, segmentation, and registration. *arXiv preprint*. https://arxiv.org/abs/2509.06467

12. Lv, W., Lei, Y., Liu, F., Yan, J., Song, Y., & Zhao, W. (2025). gdverse: An R Package for Spatial Stratified Heterogeneity Family. *Transactions in GIS*, *29*(2), e70032. https://doi.org/10.1111/tgis.70032

13. Ouyang, T., Zhang, X., Han, Z., Shang, Y., & Li, Y. (2024). Health CLIP: Depression rate prediction using health related features in satellite and street view images. In *Companion Proceedings of the ACM Web Conference 2024* (pp. 1142–1145). https://doi.org/10.1145/3589335.3651451

14. Ge, Q., Li, Y., Qin, K., Li, C., Yang, S., Yin, C., Liu, Y., Dai, S., & Jia, P. (2025). High-resolution population density mapping in urban areas using a contextualized geographically weighted neural network (CGWNN) model. *Applied Geography*, *182*, 103708. https://doi.org/10.1016/j.apgeog.2025.103708

15. Richter, J., Neumayr, A., Garba-Djirmay, A., et al. (2025). The Basel ultrasonography protocol for assessing hepatosplenic pathologies in Asian schistosomiasis: Report of a WHO expert meeting. *Infectious Diseases of Poverty*, *14*, 83. https://doi.org/10.1186/s40249-025-01349-x

16. Sakhvidi, F. Z., Browning, M. H. E. M., Samuelsson, K., Labib, S. M., Psyllidis, A., Amegah, A. K., Astell-Burt, T., Bach, A., Jerrett, M., Bratman, G. N., van den Bosch, M., de Hoogh, K., de Vries, S., Dzhambov, A. M., Fallah Madvari, R., Feng, X., Fernandes, A., Fuertes, E., Giannico, V., Gouveia, N., Hartig, T., Heinrich, J., Hystad, P., Ibarluzea, J., Jacquemin, B., James, P., Jashni, M., Knibbs, L. D., Knobel, P., Kogevinas, M., Lertxundi, A., Markevych, I., Mehrparvar, A., Miri, M., Mitchell, R., Nawrot, T. S., Nieuwenhuijsen, M. J., O'Callaghan-Gordo, C., Pearce, J., Plusquin, M., Sanesi, G., Su, J. G., Triguero-Mas, M., Ubalde-Lopez, M., Valentin, A., White, M. P., Yang, B. Y., Yang, J., Zhang, J., Zhao, T., Helbich, M., & Dadvand, P. (2025). Methodological guidance for selecting buffers in greenspace–health studies. *The Lancet Planetary Health*, *9*(11), e101370. https://doi.org/10.1016/j.lanplh.2025.101370

17. Sallis, J. F., Cerin, E., Kerr, J., Adams, M. A., Sugiyama, T., Christiansen, L. B., Schipperijn, J., Davey, R., Salvo, D., Frank, L. D., De Bourdeaudhuij, I., & Owen, N. (2020). Built environment, physical activity, and obesity: Findings from the International Physical Activity and Environment Network (IPEN) adult study. *Annual Review of Public Health*, *41*, 119–139. https://doi.org/10.1146/annurev-publhealth-040218-043657

18. Siegenfeld, A. F., & Bar-Yam, Y. (2020). An introduction to complex systems science and its applications. *Complexity*, 2020, 6105872. https://doi.org/10.1155/2020/6105872

19. Volandes, A. E., Davis, A. D., & Goldstein, N. E. (2025). From bandwidth to bedside — Bringing AI-enabled care to rural America. *New England Journal of Medicine*, *393*(22), 2182–2185. https://doi.org/10.1056/NEJMp2509491

20. Weiss, D. J., Nelson, A., Gibson, H. S., Temperley, W., Peedell, S., Lieber, A., Hancher, M., Poyart, E., Belchior, S., Fullman, N., Mappin, B., Dalrymple, U., Rozier, J., Lucas, T. C. D., Howes, R. E., Tusting, L. S., Kang, S. Y., Cameron, E., Bisanzio, D., Battle, K. E., Bhatt, S., & Gething, P. W. (2018). A global map of travel time to cities to assess inequalities in accessibility in 2015. *Nature*, *553*(7688), 333–336. https://doi.org/10.1038/nature25181

21. Yang, S., Yu, B., Yu, W., Dai, S., Feng, C., Shao, Y., Zhao, X., Li, X., He, T., & Jia, P. (2023). Development and validation of an age-sex-ethnicity-specific metabolic syndrome score in the Chinese adults. *Nature Communications*, *14*(1), 6988. https://doi.org/10.1038/s41467-023-42423-y

22. Ying, Y., Dai, S., Koeva, M., Kuffer, M., Persello, C., Zhou, W., & Zevenbergen, J. (2025). Toward 3D hedonic price model for vertically developed cities using street view images and machine learning methods. *Habitat International*, *156*, 103288. https://doi.org/10.1016/j.habitatint.2025.103288

23. Yin, C., Zhang, Z., Dai, S., & Chen, Y. (2025). Built environments and obesity: A framework considering residences, commute routes, and workplaces. *Cities*, *160*, 105842. https://doi.org/10.1016/j.cities.2025.105842

24. Yun, G., He, Y., Jiang, Y., Dou, P., & Dai, S. (2019). PM2.5 spatiotemporal evolution and drivers in the Yangtze River Delta between 2005 and 2015. *Atmosphere*, *10*(2), 55. https://doi.org/10.3390/atmos10020055

25. Zhao, H., & Lai, Y. (2025). Leveraging LLMs and explainable AI to decode citizen complaints for neighborhood respiratory health prediction. *Urban Informatics*, *4*, 23. https://doi.org/10.1007/s44212-025-00092-w

26. Zuo, S., Dai, S., & Ren, Y. (2019). More fragmentized urban form more CO2 emissions? A comprehensive relationship from the combination analysis across different scales. *Journal of Cleaner Production*, *244*, 118659. https://doi.org/10.1016/j.jclepro.2019.118659

27. Lyu, W., Lei, Y., Yi, W., Song, Y., Li, X., Dai, S., Qin, Y., Zhao, W. (2026). Causal discovery in urban data with temporal empirical dynamic modeling: The R package tEDM. *Computers, Environment and Urban Systems*, *127*, 102435. https://doi.org/10.1016/j.compenvurbsys.2026.102435

28. Lyu, W., Dai, S., Song, Y., Zhao, W., Yi, W., Xiao, Y., Jia, N. (2026). Measuring causal strengths from spatial cross-sectional data with geographical cross mapping cardinality. *International Journal of Geographical Information Science* 1–23. https://doi.org/10.1080/13658816.2026.2687121

29. Li, Z., Zhang, F., Dai, S., Zhao, W. (2026). Bridging street view coverage disparities through geographic identity preserving generation from satellite view. *ISPRS Journal of Photogrammetry and Remote Sensing*  *236* 622-639. https://doi.org/10.1080/13658816.2026.2687121



### 中文期刊论文

1. 戴劭勍, 李佳佳, 杨维旭, 陈方煜, 江辉仙. (2020). 春节期间的PM2.5污染短期暴露健康效应评估——以长三角地区25个城市为例. *上海城市规划*, *05*, 22–29. https://doi.org/10.11982/j.supr.20200504



### 微信推送

1. Another Earth︱AlphaEarth Foundations 重新定义地球观测与测绘的未来. *一览众山小·可持续城市与交通*.

2. 新版白话空间统计. *虾神说D*.

3. "发展与保护的天平"：使用PLUS模型分析多土地利用情境下的生态系统服务价值差异. *极思客栈*.

4. 智慧医疗翻不过的那座山. *NEJM医学前沿*.

5. 告别“龙虾崇拜”：我用 Codex 挑战了农林科学的复杂任务. *植物功能生态*.

6. ESRI发力AI，发布ArcGIS MCP服务支持. *麻辣GIS*.

## 其他相关课程

1. 裴韬. (2016). 地理信息科学B课程. 中国科学院大学.

2. 王劲峰. (2017). 时空数据分析与建模课程. 中国科学院大学.

3. 戴劭勍. (2024). 基于地理归因框架探究城市二氧化碳不确定性的影响因素. 和鲸GeoAI Workshop.

4. ITC, University of Twente. (2022). Advanced Image Analysis.


### 相关网站

1. COVID-19仪表盘: https://gisersqdai.shinyapps.io/COVID19VIS/

2. 代谢综合征得分计算器: https://gisersqdai.shinyapps.io/mets_severiity_calculator/

