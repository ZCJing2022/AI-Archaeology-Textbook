# 第一编补充文献评估：分类参照、模拟训练与考古解释

**评估日期：** 2026-10-17（America/Vancouver；UTC 2026-10-18）。
**基准：** PR #51合并后的main，提交70e38c570aa1f772d31c5d5f58678d202dd8d158。
**工作分支：** feature/part1-classification-simulated-training-v1。

本报告处理用户本批17份PDF与前一批75份目录的对应、指定原文与关键页图、正式书目及必要的公开材料核查。正文仅在第3章3.3和第4章4.7各补一段，并各增加一条章末参考文献。编辑记录保存在本目录，不进入学生正文。

**证据范围：** 下列“已核原文”指实际核读的指定段落，“目视”指实际查看的PDF页面图像；独立书目核验来自出版社、作者机构或出版社提交的Crossref记录，不能替代原文。下载、文本提取、文件互斥及代码静态核对不等于通读所有页面或复现论文实验。未另注明的数值均为作者报告；本轮没有重新训练模型、复算调查原始响应或核验每篇所引的全部文献。

## 1. 文件、作品与现有教材的对应

17份附件共343个PDF页面。独立重新核对两批共92个PDF文件的页数、字节数和SHA-256，并对照[前75份目录](part1-ai-archaeology-literature-catalogue-20261017-v1.md)，得到互斥且穷尽的四组。这里的文件检查不计作全文阅读。

| 与前75份文件的关系 | 本批编号 | 文件数 | PDF页数 | 编辑处理 |
|---|---|---:|---:|---|
| 字节完全相同 | S07＝P54、S08＝P62、S09＝P52、S10＝P33 | 4 | 88 | 沿用既有定向阅读记录，不再计作新作品或本轮新读全文 |
| 字节不同，但全文与可见内容相同 | S05＝P64，Skeates | 1 | 11 | 11页提取文本逐字一致，72 dpi渲染像素亦全部一致；补官方书目核验 |
| 同一部书，正文可取得范围增加 | S06＝P46，Nigro | 1 | 77 | 旧件仅5页前置资料；本件增加正文与书末材料，单列本次实际核读页段 |
| 未在前75份文件目录中出现的论文 | S01—S04、S11—S17 | 11 | 167 | 逐项定向审阅；其中S17已用于第1章，并非教材新增书目 |

“首次进入此前75文件目录”不等于首次出版或首次进入教材。S17作者为 **Magnani**，不是文件名中的Maganani；S13为 **Tatsuda**，不是Tatasuda；S04按 **Soto Rodríguez** 著录。文件名原样保留供追溯，正式书目采用核定名称。DOI中的年份不自动决定引文年份。

Nigro两件的作者、题名、DOI、ISBN与目录一致；新件前置版权说明有极小文字差异，不称前5页逐字相同，也不计为另一部书。旧P46如实保留当时仅见前置资料的状态，本次正文阅读另记于S06，不回填为上一轮已读全书。

## 2. 本轮正文采用及原页对应

| 教材位置／论断 | 原文定位 | 支持范围与限制 |
|---|---|---|
| 第3章3.3：分类记录需要共同参照与校准 | Bloch等（2025），489—492页／PDF9—12，Survey Methodology、Survey Results、Discussion | 非AI的记录者调查；部分形状与夹杂比例判断改善，颗粒大小和溶蚀孔隙仍困难。前后题目并非全部同图配对，不使用普遍提升率 |
| 第4章4.7：模拟对象检出与用途解释 | Peck等（2026），184—189页／PDF6—11；191—192页／PDF13—14 | 两种方案模拟形态；有限田野钻探质疑焦油窑解释，军事用途仍待核实。12处初始目标参与设计，不能称完全未触及的独立发现样本 |

### 2.1 第3章3.3增加的短段

> Bloch等制作了贝壳羼和料（加入陶土的碎贝壳）的实验参照图，并通过在线调查比较有无参照图时的判断。在这项调查中，颗粒形状和夹杂比例的判断在使用参照图后有所改善，但颗粒大小及贝壳溶蚀后孔隙特征的判断仍较困难（2025，489—492页）。共同参照有助于校准记录者的判断；具体记录仍需说明观察条件与类别标准，并保留尚存的分类分歧。

该段承接已有类型学判别标准讨论，没有增加标题。观察条件、共同标准与保留分歧是教材的记录实践归纳，原文490—492页提供方法依据，不是已经证明某个古代社会群体的实验结论。

### 2.2 第4章4.7增加的短段

> 模拟资料可以补充训练样本，但模拟时采用的考古假设仍需接受检验。Peck等（2026，184—189页）比较了三种训练方案，其中两种参照疑似焦油窑的形态生成模拟目标，再用模型在真实激光雷达地形资料中寻找相似对象。研究者随后对部分目标作田野核查，在12处初始目标中的两处进行了钻探，未见支持焦油窑解释的诊断性遗存；结合附近军事基地的背景，作者提出它们可能与军事训练有关，具体用途仍待核实（191—192页）。**检出相似形态与判断遗迹用途，需要分别提供证据。**

该段接在现有Orengo与Bickler讨论之后、“可靠性不仅是一个模型分数”之前。田野证据质疑的是用途解释，没有否定形态相似本身；两处钻探属于初始目标，未写成对全部模型新增点的确认。未用性能数字替代功能证据。

### 2.3 对应章末书目

- Bloch, Lindsay C., Erin S. Nelson, Neill J. Wallis, and Ashley M. Rutkoski. 2025. [“Creating Standardized Guides for Pottery Temper Characterization.”](https://doi.org/10.1017/aap.2025.8) *Advances in Archaeological Practice* 13(4): 481–495.
- Peck, Katherine, Claudine Gravel-Miguel, Grant Snitker, and Matthew Helmer. 2026. [“Using Simulated Training Data to Locate Archaeological Sites with Machine Learning.”](https://doi.org/10.1017/aap.2025.10130) *Advances in Archaeological Practice* 14(2): 179–197.

两篇作者顺序、正式卷期页码及DOI已与出版版和Cambridge／Crossref核对。Bloch为2025年13(4):481—495；Peck为2026年14(2):179—197，不按其DOI中的2025错定引文年。两段均经独立逐句措辞复核，保留调查范围、有限田野核查与用途解释的不确定性。

## 3. 逐项来源核验与取舍

以下按S编号排列。S11、S16的最终采用文字以第2节为准；其他项目仅保留内部阅读与资源候选记录，本轮未扩大参考资源页。

### S01：Chen与Huang的多模态甲骨知识组织

**阅读范围：** 20页提取文本；重点逐段阅读方法、数据、指标、结果、消融、讨论与数据声明（PDF 4–19），并核对题名及参考文献信息。未逐一核查其所有转引文献。 实际目视PDF页：1,10,13,14,15,16。

#### 书目、版本与页码

Chen, Tiancheng, and Dong Huang. 2026. “Construction of multimodal oracle bone semantic reasoning and knowledge graphs in archaeology under artificial intelligence technology.” *Scientific Reports*. Article in Press. Published online 12 September 2026. https://doi.org/10.1038/s41598-026-71440-2.

上传件20页，没有连续原刊页码；以下“PDF页”均指文件页序。官方网页仍标明这是已接受的先行版，将由最终Version of Record替换；当前元数据没有卷、文章号或首末页，不能把DOI尾号当作文章号。第1页实际图像页脚标有2026-09-12上线日期，初始文本抽取遗漏了该行。

官方核验入口：

- [出版社页面](https://www.nature.com/articles/s41598-026-71440-2)：作者、完整题名、上线日期及先行版状态；已读取官方HTML中的citation元数据。
- [官方20页先行PDF](https://www.nature.com/articles/s41598-026-71440-2_reference.pdf)：与上传件题名和DOI一致。
- [官方补充材料DOCX](https://media.springernature.com/original/springer-static/esm/art%3A10.1038%2Fs41598-026-71440-2/MediaObjects/41598_2026_71440_MOESM1_ESM.docx)：从出版社HTML链接取得，HTTP200；读取了S1.1–S1.5、S2指标文字说明及S1–S7表。

#### 方法与数据：必须区分计数单位

作者从Oracle-241的78,565幅字符图像、241类中选20,000幅，其中12,000幅与释文、字义或卜辞语境组成图文对，其余8,000幅用于视觉域适配。图文训练、验证、测试分别为9,600、1,200、1,200对（PDF13，表2）。**12,000是图文配对数，不能改写为12,000片独立出土甲骨。** 表2另列12,000条释文记录，但主文及已读补充材料没有提供逐项图像—全文释文—实际著录号对照表。

论文声明，按原始记录ID划分时，相关图像、释文、实体及图节点保持在同一子集；同一头实体—关系—尾实体组合只进入一个子集，测试与验证目标边不参加训练阶段的信息传播、参数更新及负样本构造（PDF13–14）。这是作者明确报告的控制设计，不能说成“简单随机逐图拆分”或“没有防泄漏措施”。不过，原始记录ID与独立实物甲骨、跨著录本重复记录之间的具体映射，当前仍不能独立复核。8000幅适配图像的来源重叠处理、20000幅中的手写/扫描域比例也未见说明；这不等于已证实发生泄漏。

结构知识来自四个数字资源和60种专著、论文及资料汇编。两人独立标注、第三位专家裁决；保留来源、别名与争议标记，监督数据仅使用较确定或达成共识的释读。作者报告的人工一致性指标与2,400条复核记录可见PDF14。补充材料S1详细规定了实体、关系、别名、冲突与问题生成的处理规则。

问答由各子集的已确认三元组枚举1–3跳路径，剔除循环、多答案、证据不完整及争议记录；共18,000问，训练/验证/测试为14,400/1,800/1,800（PDF14；补充S1.4）。答案是路径端点实体，证据是已标三元组序列。S1.5示例明确仅演示格式，G00037、P00112等不是可查的甲骨著录号。

#### 结果是什么，不能据此说什么

图文检索、实体/关系抽取、图约束一致性与标准答案匹配，是不同评价对象（PDF10–12）。作者报告实体F1为92.4%±0.3%、关系F1为89.5%±0.4%，答案匹配准确率为92.8%±0.4%（PDF15–17，表4–8）。这些数字属于作者实验结果；本轮没有复现，不能称为“未释字破解率”或“商代历史解释准确率”。

尤其是以专家共识图中的路径生成问题，再匹配专家确认的端点答案，证明的是这个问题定义及数据边界内的计算表现。它并不独立确立新字义、新人物身份或新历史事实。路径排名、最弱边置信度及图连通性也不是直接的历史真实性概率。作者在PDF18明确要求回到原拓片、释文来源与专家判断复核，并将跨地区、跨古文字语料的迁移验证列为未来工作。

#### 具体待澄清问题

**表3的R@1与Median Rank不能直接按正文同一查询集的定义协调。** PDF10的式24–25定义：R@1为正确匹配位于第1名的查询比例，Median Rank为同一组查询名次的中位数。PDF15表3中全部模型R@1均超过50%，而中位名次列为3–8；OAMR分别为69.8%和3。若超过半数查询的正确名次为1，其中位名次应当为1。若实际按方向或子样本作了不同聚合，需要额外说明；正文与已读补充材料未提供这种口径。本轮已逐页目视核实这两处，并未自行改数或据此推断学术不端。这个问题足以支持暂不采用该表的成绩宣传。

**来源入口不能替代完整复现材料。** [Oracle-241官方项目](https://github.com/wm-bupt/STSN)确认78,565幅手写/摹写及扫描字符、241类，但下载需大学邮箱申请密码；它提供的是Wang、Deng与Liu的STSN项目，不能冒称Chen的OAMR代码。论文所引[CHANT入口](https://www.chant.org/Database.aspx)转到登录页；[复旦图书馆说明](https://library.fudan.edu.cn/e8/6e/c42799a518254/page.htm)确认名称是汉达文库“新甲骨文”，并称九部著录共67,683片。Chen表2的Handian不宜译成另一平台“汉典”。文章PDF18–19明确说受原数据库协议约束的图像与释文不作二次分发。

主文及补充材料有通用规则、参数、性能表和占位示例，但本轮未见完整的实际图文配对表、所有结构知识来源目录、分割文件、实际著录号列表或OAMR代码/权重入口。这里记录的是已查材料的范围；不据此断言作者没有保存这些资料。

#### 教材安排

第1章已经区分识字、检索、释读、复原及历史解释。当前把此文列为“多模态知识组织与问答”内部候选即可。若后续确需增加知识图谱的简短说明，可强调关系图依赖人工释读、实体定义与来源核查，已知图路径问答不同于未知字义的考释；无需增加模型名称、超参数、成绩表或“突破”叙述。

### S02. Fajardo与Argüello：聚落聚集、资料表示与历史假说

Fajardo, Sebastian, and Pedro Argüello. 2024. “Sociopolitical evolution, population clustering, and technology among early sedentary communities in northeastern Andes, Colombia.” *Journal of Anthropological Archaeology* 76:101628. [DOI](https://doi.org/10.1016/j.jaa.2024.101628).

**版本与读取：** PDF与[Crossref记录](https://api.crossref.org/works/10.1016/j.jaa.2024.101628)相互核对，在线2024-10-08、卷期2024年12月。正文按文章内1—13页定位，与PDF页序一致。定向核读1—5、9—11页，实际目视4页的方法与表1；未将自动提取的其他页面计为逐页通读。

**资料与方法：** 3—4页区分两个调查区、地表采集与植被条件下的铲探，剔除错误后汇总2,226个记录单位。陶片密度及其时间尺度调整用于近似活动分布，再采用IDW插值与DBSCAN聚类。地表陶片密度不是人口普查，聚类也不自动对应过去居民自我认同的社区。

**解释边界：** 4—5页的邻域距离和最小点数依资料与可视格局选择，不同区域／时期参数不一；同一批观察经过不同算法所得结果，不能当成来自独立资料的相互印证。9—11页将聚落聚集与社会政治过程、计数／书写等技术联系起来，是仍需比较的历史假说；作者讨论环境、仪式、冲突、有限发掘及易腐记录等其他可能。不能写成“机器学习证明聚集造成书写”或普遍的线性演化规律。

**处理：** 作为计算考古、代理指标和竞争解释的储备，本轮不再叠加第一编案例。资料声明区分可取得的Sogamoso数据与按需提供的Tunja数据；本次未审计全部调查数据库。

### S03：Davis 等2024——计算考古不等于深度学习

Davis, Dylan S., Alejandra I. Domic, George Manahira, and Kristina Douglass. 2024. “Geophysics elucidate long-term socio-ecological dynamics of foraging, pastoralism, and mixed subsistence strategies on SW Madagascar.” Journal of Anthropological Archaeology 75: 101612. https://doi.org/10.1016/j.jaa.2024.101612

**核验与读取：** 出版版、作者机构记录与出版社提交的Crossref记录核对正式书目。读正文1—10页及11页声明；实际目视10页。PDF页序与文章内1—13页一致。

方法 pp.3–4 是多时相 PlanetScope 影像、季节中值、NDVI、M-statistic 与 Wilcoxon 检验，分析用 R；没有原创 ML/DL 训练或预测模型。p.4 的考古位置及分类来源于地表调查、器物、动物骨和牲畜围栏等线索，并以四处发掘、AMS及陶器序列补充年代背景。

需要分别记录：

1. 340个沿海考古位置与80个地表无考古材料位置；内陆16个牧业聚落与15个比较位置。
2. 131个渔猎采集堆积与31个混合生业堆积是筛选出的子集，不能与340简单相加。
3. 影像数量是重复环境观测数量，不能当成遗址样本量；地表未见材料也不等于地下绝对不存在遗存。
4. 原文 p.10 §4.2 明列样本不均、密植被限制调查以及需沉积物/地球化学补验。现代光谱和NDVI变化只是关于环境稳定性的代理，不能直接等同于古代多样性或长期韧性已测定。
5. p.7 Table 3 绝大部分M值低于1，但湿季蓝光为1.029；不要重复“全部低于1”。Wilcoxon检验的组间差异也不证明空间独立。
6. 方法段写2018–2021，§3.2出现2018–2022，本轮未解决此时间窗不一致；没有必要把这一细节写入教材。

分类为计算／遥感考古和环境代理解释。原文有意义，但不宜包装成新的AI发现实例。

### S04. Soto Rodríguez：梯田、适宜性模型与社会解释

Soto Rodríguez, Luis Miguel. 2026. “Landesque capital and ideal distribution models: mapping agricultural suitability in the Sierra Nevada de Santa Marta, Colombia.” *Journal of Anthropological Archaeology* 82:101772. [DOI](https://doi.org/10.1016/j.jaa.2026.101772).

**版本与读取：** PDF与[Crossref记录](https://api.crossref.org/works/10.1016/j.jaa.2026.101772)相互核对；在线2026-05-05、卷期2026年6月。PDF与文章内1—19页一致。定向核读1、3—4、7—9、14、16页及17页资料声明，实际目视8页。

**资料与方法：** 7—9页的2,526个去重梯田位置、5,005个随机背景点和五项地形变量用于模型。主体为二项GLM，另以GAM和随机森林检查敏感性；五个约2 km空间块用于验证。随机森林训练AUC约0.789、分块约0.665，GLM约0.713与0.714，是特定资料的结果，不能概括为一种算法普遍优于另一种。随机背景点也不是经田野证明没有遗址的点。

**解释边界：** 9页明确由梯田分布生成适宜性指标的循环论证风险，不能再用同一批梯田证明它们“偏好”由其自身拟合的环境。该指标是相关性基准，不是外部测得的农业产量。个体梯田缺少独立年代，合并模型与分期地点面属于不同资料层级。残差空间结构可来自遗漏变量、测量、调查、时段混合或非线性，不能一律归为社会作用。16页的空间可及性不排除劳动、收益与权力的不平等，也没有独立检验人口密度的Allee效应。

**处理与访问：** 为后续模型与历史解释比较保留，本轮不扩写第一编。[作者声明的资料与R代码入口](https://github.com/luismiguelsoto/Landesque_Capital_and_Ideal_Distribution_Models_in_Tairona_chiefdoms)按原文记录，未完成该仓库文件审计或结果复算。

### S05：Skeates社论的版本与证据性质

**阅读范围：** 11页提取文本全部检查，重点社论正文PDF3–11；未逐项独立查证社论所引所有外部文献与出版政策。 实际目视PDF页：3,9。

Skeates, Robin. 2026. “Editorial: Rewriting archaeology with AI.” *Antiquity* 100(413):1191–1201. https://doi.org/10.15184/aqy.2026.10415. Published online 1 October 2026.

整项起止页包括两页卷首图1191–1192；社论正文为1193–1201，即PDF3–11。已核对[Cambridge完整页面](https://www.cambridge.org/core/journals/antiquity/article/editorial-rewriting-archaeology-with-ai/491435E5B0D9D4E80911FC6C3E77336F)及[出版社Crossref登记记录](https://api.crossref.org/works/10.15184/aqy.2026.10415)，题名、作者、卷期、页码与上线日期均吻合。

新S05的SHA-256为`07028a79c5703c00c66da7abcca30936de4e2109573b69bf3e45f0bea00bc7aa`，旧P64为`7d75fc62a550e877d6c790c33a826413c85c1b239e2d8c309d600f7a10601bd1`。文件大小分别645902与645731字节。但两文件11页提取文本逐字相同，11页72dpi渲染像素也全部一致。应标作同一作品、同一可见内容版本的重复上传。

社论在1197页讨论引文确有作者或DOI却不能支持邻近陈述、事实错误及循环论证；1199–1201页讨论披露、人工审查与研究者责任。1200页的匿名投稿经历是编辑叙述，不能由三位评审的意见推导普遍发生率或因果效应。社论自己指出文体迹象不能单独证明未披露AI使用，因此不能把其列举的特征变成自动判断作者的规则。文中转引的遗址发现或性能仍应回查原始研究。

此前P64已收录，本轮只需补足版本判重与官方网页已核的记录。没有必要再给第一编增加一般性警示段落，也不能把2026年的社论转述当成所有期刊恒定通用的投稿政策。

### S06. Nigro：从前置资料到指定正文核读

Nigro, Lorenzo. 2026. *Archaeology & Artificial Intelligence*. Quaderni di Vicino Oriente XVIII. Roma: Sapienza Università di Roma. ISBN 978-88-98154-30-2. [DOI](https://doi.org/10.53131/QVO1127-60372026_1).

**版本核定：** 对应旧P46同一本书。本件77个PDF页面，前5页为封面、题名、版权与目录；正文印刷1页始于PDF6，即所引正文印刷页＝PDF页−5。实际核读前置资料，正文1—3、9—10、27—35、47—50页；实际目视版权页PDF3及印刷32、48页，不称已通读全部章节。

[出版社书目及全文入口](https://www.vicino-oriente-journal.it/index.php/quaderni-di-vo/article/view/503)与[Sapienza书目记录](https://iris.uniroma1.it/handle/11573/1768113)均成功读取，核对作者、丛书、ISBN、DOI及2026年出版；出版社列2026-04-09。机构书目记录本身不替代正文证据。

| 印刷页／PDF页 | 作者论述 | 使用界限 |
|---|---|---|
| 1—3／6—8 | 考古推理与计算方法的连续性、AI的定位 | 理论阅读，不用来核定全部技术史时间线 |
| 9—10／14—15 | 模式识别、分类、生成与历史理解的区别 | 作者论证，不是证明全部AI普遍不能解释历史的实验 |
| 27—30／32—35 | 资料单位、选择、分类、标准化与情境 | 标准化可能掩盖差异，不自动恢复缺失情境 |
| 31—35／36—40 | 相关、解释与可解释模型 | 特征贡献不直接证明历史因果，分类仍是待解释的中间结果 |
| 47—50／52—55 | 问题先于模型、验证、透明性与责任 | 48页9.3强调情境与多种证据，适合方法论导读 |

这是一部批判性理论专著，未在本轮取得新的模型实验。没有逐条核定所有旁引，不把“没有AI便不可能研究”等宽泛立场写成教材普遍结论。所读段落与第一编已有内容多有重合，本轮更新实际可读范围与阅读路径，暂不重复扩写正文或资源页；P46仍保留上一轮仅有前置资料的历史状态。

### S07. 对应P54的字节完全重复文件

Cal T. Pols; Fraser Sturt; Crystal El Safadi; Antonia Marcu. 2025. “Shipwreck detection in bathymetry data using semi-automated methods: Combining machine learning and topographic inference approaches.” *Journal of Archaeological Science*. 181:106297，文内1–14页。 DOI：[10.1016/j.jas.2025.106297](https://doi.org/10.1016/j.jas.2025.106297)。

**本轮证据与处理：** 实际字节与SHA-256比较确认重复，未再次通读该文。沿用PR #51目录的定向原文定位：7—9、11页；地形初筛已漏失目标，后续模型的条件成绩不能代替全流程；候选沉船不全等于实地确认。 不重复增加书目，历史读取范围仍以[原目录P54](part1-ai-archaeology-literature-catalogue-20261017-v1.md#p54)为准。

### S08. 对应P62的字节完全重复文件

Paolo Sferrazza. 2025. “Archaeological and Experimental Lithic Microwear Classification Through 2D Textural Analysis and Machine Learning.” *Journal of Archaeological Method and Theory 32(1)*. 文章31，文内页1–41。 DOI：[10.1007/s10816-025-09701-z](https://doi.org/10.1007/s10816-025-09701-z)。

**本轮证据与处理：** 实际字节与SHA-256比较确认重复，未再次通读该文。沿用PR #51目录的定向原文定位：27、30—31、33页；最佳组合成绩不是所有保存状态、原料与接触材料的普遍识别率；未确认的分组问题不直接断言为泄漏。 不重复增加书目，历史读取范围仍以[原目录P62](part1-ai-archaeology-literature-catalogue-20261017-v1.md#p62)为准。

### S09. 对应P52的字节完全重复文件

Laura Pey; Kevin Lane; Luis Coll; Jennifer Grant; Mario Advíncula; Andy Combey; Alexander Herrera. 2025. “Past Water Futures: A Digital Survey of Prehispanic Dams in the Central Andes.” *Archaeological Prospection*. 32(4):989–1004。 DOI：[10.1002/arp.70001](https://doi.org/10.1002/arp.70001)。

**本轮证据与处理：** 实际字节与SHA-256比较确认重复，未再次通读该文。沿用PR #51目录的定向原文定位：995、1000、1002页；人工数字调查、GIS与选点田野研究；CNN为未来计划，新增影像记录不是全部经测年确认的古代水坝。 不重复增加书目，历史读取范围仍以[原目录P52](part1-ai-archaeology-literature-catalogue-20261017-v1.md#p52)为准。

### S10. 对应P33的字节完全重复文件

Melda Küçükdemirci. 2025. “Tracing Past Agrarian Field Systems Through Ai‐Based Analysis of Satellite Imagery in Konya, Central Anatolia, Türkiye.” *Archaeological Prospection*. 32(4):881–897。 DOI：[10.1002/arp.2001](https://doi.org/10.1002/arp.2001)。

**本轮证据与处理：** 实际字节与SHA-256比较确认重复，未再次通读该文。沿用PR #51目录的定向原文定位：887、894—895页；影像来源、分辨率及日期限制推广；格网形态不等于已确定年代或文化归属。 不重复增加书目，历史读取范围仍以[原目录P33](part1-ai-archaeology-literature-catalogue-20261017-v1.md#p33)为准。

### S11. Bloch 等：陶器羼和料参照图与记录一致性

**正式书目**

Bloch, L. C., Nelson, E. S., Wallis, N. J., & Rutkoski, A. M. (2025). Creating Standardized Guides for Pottery Temper Characterization. *Advances in Archaeological Practice*, 13(4), 481–495. https://doi.org/10.1017/aap.2025.8

Cambridge 与 Crossref 均确认正式作者顺序为 **Bloch、Nelson、Wallis、Rutkoski**。卷期为2025年11月，Cambridge上线日期为2025年12月17日。Zenodo补充条目的作者顺序不同，章末书目应按正式论文。PDF页码加480即印刷页码。

#### 可支持的教材论断

| 论断 | 原文位置 | 支持与限制 |
|---|---|---|
| 为属性类别提供共同参照可帮助校准记录者 | 489–491页，Survey Methodology / Survey Results，表2 | 提供参照图后，壳屑形状、夹杂比例的识别总体改善。粒度及溶蚀孔隙仍困难；不能概括为所有属性均同等改善。 |
| 分类准确度与研究者信心应区分 | 491页，表2与表3；492页讨论 | 信心上升不是类别“真值”获得证明；答案由作者商定，14项中4项未达共识。 |
| 数据说明应包括参照标准、观察条件与判断分歧 | 490–492页 | 理想实验图板不能涵盖全部保存状态，二维在线判断也不等同于实物显微观察。 |
| 此研究可说明可靠数据准备，不是AI性能案例 | 483–485、492页 | 论文只在讨论中提及机器学习；制陶实践共同体、社会网络等是更大项目的后续研究目标。本文没有用AI验证具体政治群体。 |

方法是制作**49个烧制小块**：3种壳材 × 4种粒度（含未筛）× 4种比例 = 48，另加1个无壳空白。烧制后各切半，一半浸酸去壳，生成**98幅参照图**。这与摘要中“98个独特小块”的口径不同，教材若使用数字应依方法部分，或直接省去数量。原文见486–488页。

调查正文报告259名完成必答题，但经验分组表2、3总数为256。本文没有解释3人的差额，本次也未获取匿名原始响应来判断原因。前阶段是6题、后阶段8题，并非全部同图配对或随机组间试验。故不建议在教材写“准确率普遍提高8.1%”；可保留“部分属性识别有所改善”的局部结论。

**资源状态**

- [Cambridge正式论文](https://www.cambridge.org/core/journals/advances-in-archaeological-practice/article/creating-standardized-guides-for-pottery-temper-characterization/8457BEE89B4512CF527CE7BA246EE750)与[Crossref记录](https://api.crossref.org/works/10.1017/aap.2025.8)已核实。
- [Zenodo补充材料](https://zenodo.org/records/15717882)列参照图板、Qualtrics完整问卷及匿名响应，ZIP为11,507,490字节；本次核实记录和文件清单，未下载全包。
- 正式论文许可为CC BY-NC-SA 4.0；Zenodo API的补充材料许可为CC BY-SA 4.0，两者应分别记录。

**阅读与图像范围：**正文、结果和声明读至PDF13页，参考文献浏览至15页；视觉核对PDF7、9、11、12页，即印刷487、489、491、492页。不是匿名响应重新分析。

### S12. Montalvo-Puente 等：尺寸模式与计数货币假说

**正式书目**

Montalvo-Puente, C. E., Lago, G., Cardarelli, L., Constantine-Castro, A. R., & Pérez-Molina, J. C. (2026). Counting rather than weighing: metrological analysis and machine learning reveal the monetary potential of pre-contact Ecuadorian axe-monies. *Journal of Archaeological Science: Reports*, 69, 105525. https://doi.org/10.1016/j.jasrep.2025.105525

上线2025年11月29日，正式卷期为2026年2月。DOI里的2025不是章末引文年份。内部页码1–15与PDF页码一致，105525是文章编号。

#### 资料与方法

共3,588件器物纳入计量分析，其中2,429件有俯视照片；包含2023年前期研究的728件。来源分为：

- 261件来自田野调查或发掘；
- 1,152件只报告来源地区而无受控发掘语境；
- 2,175件来源与语境均未知。

这些器物件数见5–6页§3.1。作者说明现有资料不允许可靠地按遗址、地区和时期比较，因此将样本合并分析。

计量部分用高度代表尺寸，HDBSCAN识别两组和噪声，组内高度中位数为4.9和7.8 cm。图像流程包括YOLOv8分割、256×256二值轮廓、ResNet50编码、**高度回归与轮廓重建双目标**，最后再对学得的表示做PCA（6–9页，§§3.2–4.2）。训练/测试按器物图像随机80/20划分，没有跨馆藏或时期外推验证。

#### 论断与界限

| 原文结果或解释 | 位置 | 教材使用界限 |
|---|---|---|
| 高度与宽度呈双峰，形态与尺寸存在关联 | 8—9页结果文字；图4、8—11见8、10—12页；表2见8页 | 可说明观察到尺寸模式；不能单凭此模式确定流通制度、铸造制度或社会组织。 |
| 图像模型预测高度的R²为0.60 | 8页§4.2；图8在10页 | 是尺寸回归结果，不是“识别货币正确率60%”。高度已参与特征学习，PC1与高度相关也不是完全独立的发现。 |
| 作者支持“计数而非称量”的货币解释 | 10–12页§5；12页§6 | 应写“提出/支持一种假说”，不能写“AI证明了货币制度”。 |
| 尚无法确认或排除时空变化 | 8页§4.1、12页§5 | 地理、年代与收藏选择可能影响总体分布；大样本量不能弥补出土语境缺失。 |

原文2页已列出其他学者把此类物品理解为随葬用品的意见，作者自己的2023年研究曾倾向于具有共同形制的砷铜铸锭。新的尺寸资料改变了作者的判断，是可讨论的研究过程。至于是否实际充当交换媒介、金属储藏、随葬用品，或兼具多种用途，还需要使用和埋藏情境、年代、材质等证据。缺少规则重量分布也不能在逻辑上排尽所有按重量交易的方式。

**须保留的原文问题**

- 6页把第25百分位标为Q2，并把MAD写成相对中位数的绝对偏差算术平均，和“中位数绝对偏差”的名称不一致。此次已视觉核对，但没有重算表2，不宜从文中搬用统计公式。
- 13页数据可用性声明仍写“接受后放入仓储”及“供审稿人使用”。[Bologna IRIS机构记录](https://cris.unibo.it/handle/11585/1030593)的检索内容列有公开PDF与5.57 MB补充ZIP；直接抓取遇到403，未检查ZIP内容，不能写已完成数据/代码复现核验。
- 11页关于中国早期布、刀等货币的年代与国家担保概括不是本文实证研究；其旁引本次未核实，不建议转作中国考古证据。
- 原文前后出现500–1532与400–1532 CE范围，相关文化和材料的年代不同。避免为整个汇总模型赋予单一精确时段。

**阅读与图像范围：**正文1–12页与13页数据声明；视觉核对6、8、12页。书目由[Crossref](https://api.crossref.org/works/10.1016/j.jasrep.2025.105525)、[ScienceDirect正式记录](https://www.sciencedirect.com/science/article/pii/S2352409X25005589)及IRIS记录相互核实；没有重跑模型，也未逐条核验其欧洲、中国、安第斯史的旁引。

### S13. Tatsuda 等：须惠器三维形态的监督分类

**正式书目**

Tatsuda, W., Hori, R., Morikawa, K., & Inoue, H. (2026). Deep learning-based morphological classification of ceramics: A case study of 3D point cloud analysis for Sue ware, Japan. *Journal of Archaeological Science*, 187, 106472. https://doi.org/10.1016/j.jas.2026.106472

上传文件名中的 **Tatasuda** 应在书目中改为 **Tatsuda**。作者为Wataru Tatsuda、Ryo Hori、Kimiyasu Morikawa、Hayata Inoue。上线2026年1月16日，卷期为2026年3月。PDF1–11页与文内页码相同。

#### 研究对象和成绩究竟是什么

917件均为日本猿投窑系8世纪至9世纪中叶器物，以完整或半完整、能够恢复截面的开放器形为主，不能重建者和内表面难采集的封闭器被排除（3页§§2.1–2.2）。类别来自既有人工类型体系：DC390、DBR154、DB129、B186、P58。每件点云被转为1024点并作方向/尺度处理，然后训练Point Transformer。

论文报告每折200 epochs最后一次评价的平均 **macro F1=0.9320**（5–7页§§3.2、4.1，表2），不是“准确率93.2%”，也不是独立断代。DB和B的F1分别为0.8317和0.8779，说明总体数值会掩盖具体类型边界困难。

| 论断 | 支持页段 | 限制 |
|---|---|---|
| 网络能在该资料中学习与既定类别有关的形态特征 | 3、5–7页 | 标签由人给定；并未独立建立古代人自己的分类或独立年代。 |
| B/DB边界值得重新检视 | 7–10页，PCA、Grad-CAM、§5.3 | 模型不足与标签/真实形态连续性均可能造成混淆；不能仅凭混淆就断言古人把两类餐具互换使用。 |
| 三维局部特征可能补充二维轮廓 | 7–9页，6个选定边界例中5个与标签一致 | 6个选例不等于对所有二维方法的全面受控基准；显著图只反映模型决策关联。 |
| 数据和代码可公开取得 | 10页及Zenodo/GitHub | 已实际检查清单和代码，不等于已训练复现，也不等于在其他窑址/年代适用。 |

监督训练后的PCA和层次聚类可描述已学到的特征结构，不能表述为不依赖原始标签的独立类型发现。作者9–10页也明确说需要其他陶器、消费地点与时期的资料验证。关于饮食习惯从手食转为匙筷、餐具功能变化的讨论仍是考古解释，模型分类指标不直接证明它。

#### 公开代码与分组的独立核查

直接读取[Zenodo记录18262381](https://zenodo.org/records/18262381)与API：版本v1.0.7、许可CC BY 4.0、ZIP为429,930,501字节；**没有下载这个大包**。通过[对应GitHub发布版本](https://github.com/dv-wataru-tatsuda/ceramicnet-supplement/tree/v1.0.7)读取README、47.7 KB脚本、10份归档训练/测试清单及完整文件树，下载后核对Git blob SHA。

结果：

| 折 | 训练件数 | 测试件数 | 同文件交集 | 测试集P类 |
|---|---:|---:|---:|---:|
| 1 | 733 | 184 | 0 | 10 |
| 2 | 733 | 184 | 0 | 12 |
| 3 | 734 | 183 | 0 | 6 |
| 4 | 734 | 183 | 0 | 12 |
| 5 | 734 | 183 | 0 | 18 |

五折测试共917个不同文件，与公开主数据树的917个点云文件完全对应，类数与论文一致；文件树中未见两个主数据文件共享同一blob。**这证明文件层面的划分互斥，不是逐件实物同一性或几何近重复审计。**

需要保留三个具体差异：

1. **严格分层描述不成立。** 论文5页§3.2称保持各类比例；[v1.0.7脚本](https://github.com/dv-wataru-tatsuda/ceramicnet-supplement/blob/v1.0.7/CeramicNet%2BPointTransformer.py)却使用普通`KFold`，归档P类6至18件的折间分布也不符合严格分层。可称“五折内部验证”，不能称“严格分层五折”。
2. **不能说主实验已经使用旋转和加噪增强。** 脚本虽然定义这些函数，但训练与测试构造器均为`transforms=None`，取样时也未调用变换。DCFLIP是独立的倒置稳健性实验，不是混入训练/测试的额外独立器物。
3. **数字以表格为准。** 5–6页文字称154个DBR正确，表1的正确值为150/154；表1各行总数与真实类型数对应。正文关于矩阵行列的文字也有不一致。无需将这些排版/描述差异扩大为整体结果无效，但不要直接照搬。

原始模型文件blob为`ffac696282c3d50291743e420b651719f7f34d87`；API返回的树标识为`067914c7c31f23471309931cb4c7d128089d6473`。

**阅读与图像范围：**读主要正文1–10页并浏览10–11页书目；视觉核对3、6、7、10页。书目用[Crossref](https://api.crossref.org/works/10.1016/j.jas.2026.106472)与[正式出版记录](https://www.sciencedirect.com/science/article/pii/S0305440326000026)核对；数据访问和代码是上述限定范围的静态核查。没有训练、没有下载全部点云、没有逐条核验其原有陶器编年文献。

### S14：Peker——图块测试与历史归属的边界

Peker, Emin Atabey. 2026. “Deep Learning–Based Detection of Ancient Agricultural Terraces Using Multisensor Data Fusion: A Case Study from the Bozburun Peninsula, Turkey.” Advances in Archaeological Practice 14(2): 198–217. https://doi.org/10.1017/aap.2025.10142

**核验与读取：** 出版版、出版社与Crossref核对正式书目。读正文198—216页并浏览末尾书目；实际目视204、213、214页。印刷页＝PDF页＋197。

- **数据与分析单位：** pp.202–205，16个工作区共37.8 ha，形成256个512×512图块；30 cm RGB及DEM，作者手工标注梯田／非梯田像元。10次 Monte Carlo 为图块随机划分，每次161训练、69验证、26测试。它没有证明跨地域独立泛化，也不是256个独立田野样本。
- **公开实现补充：** [Zenodo 16905405](https://zenodo.org/records/16905405)只有 `early_fusion.py`、`config.yaml`、`requirements.txt`。脚本按已载入图块调用两次 `train_test_split`；生成器明确为 **without augmentation**，故不能声称用增强扩充了本研究训练样本。本文未详交代37.8 ha／16工作区如何对应256图块；没有原始数组，不能据此推定切片重叠、增强历史或精确独立性。
- **成绩范围：** pp.207、209，早期融合平均测试 IoU=.754、accuracy=.859，来自测试图块；不能说这是对193 km²所有地点完成田野验证后的准确率。RGB-only平均IoU=.729；作者 p.215 承认增加地形数据的收益相对有限。
- **专家比较：** p.214 Table 9 使用共同覆盖范围内的23个测试图块；作者自身标注、既有专家广义地图与像元分割的生产方式不同。只适合解释比较基准，不宜给出“AI胜过考古专家”的结论。
- **关键限制：** p.213 明确说辨别古代与现代梯田超出研究范围、需要田野核查。因此 p.208 的 **2,517 ha 是预测/制图面积**，不能直接写成全部已证实的希腊化时代梯田。形态、年代、土地利用历史应分别核验。
- **开放范围：** p.216，原始正射影像与DEM须研究授权，训练权重按需提供，专家地图为许可比较材料；公开代码不等于完整开放数据和全部四种模型的可复现包。

本轮仅列入内部候选记录，不增加重复的性能比较段落。

### S15：Davis与Lipo2026——须标为编辑部主张

Davis, Dylan S., and Carl P. Lipo. 2026. “The Future of Archaeological Prospection.” Archaeological Prospection 33(3): 691–696. https://doi.org/10.1002/arp.70046

**核验与读取：** 出版版、出版社与Crossref核对正式书目。读正文691—695及数据声明；实际目视691、694页。印刷页＝PDF页＋690，正式首末页不用早期1—6替代。

pp.692–694 支持“无损勘探应回答考古问题，并公开从采集到解释的处理链”。作者列出参数、训练数据、代码、模型及人工核验要求；p.695明确说明没有生成或分析新数据集。

这些文字适合作为方法透明和可重复性的一种编辑立场。不要转引其中笼统的“CNN达到80%准确率”或技术前景措辞作为新的实证统计；若要说某条已成为现行期刊强制规定，还须查当时的作者指南。本文说全面实施预计2026年12月完成，不能用它证明2026年10月所有要求已经生效。

### S16：Peck 等——模拟形态与田野检验

Peck, Katherine, Claudine Gravel-Miguel, Grant Snitker, and Matthew Helmer. 2026. “Using Simulated Training Data to Locate Archaeological Sites with Machine Learning.” Advances in Archaeological Practice 14(2): 179–197. https://doi.org/10.1017/aap.2025.10130

**核验与读取：** 出版版、出版社与Crossref核对正式书目。读正文179—194页及195页材料声明；实际目视191、192、193页。印刷页＝PDF页＋178。

#### 论断、页段与解释边界

| 可以支持的论断 | 原文印刷页／PDF页 | 必须保留的限制 |
|---|---|---|
| 原始12个目标来自 Kisatchie National Forest、Camp Livingston 附近的激光雷达判读，起初被假设为焦油窑，但其形态与普通焦油窑不同。 | 182–184／4–6 | 目标功能尚未确认；不能把模型的“tar kiln”类别名称当成已证实的考古标签。 |
| 两种方法在真实 DEM 中生成模拟环状土堤等形态；第三种方法反转已有焦油窑 DEM，三组各379对象。 | 185–189／7–11 | 模拟尺寸和形态参考了原始12目标；这12对象并非完全未参与设计的独立发现样本。 |
| 训练背景和实际预测区不同：两组模拟背景约180 km²，第三组真实改造背景约90 km²，实际预测区约4 km²。 | 185／7 | 只是特定类型、特定设计下的模拟到真实图像应用，不能宣称多地区、多遗址类型的泛化已解决。 |
| 图块分割、训练增强、内部评价和真实地形检出是不同环节。 | 188–190／10–12 | 内部 testing dataset 的 F1 被用于选择可视化组合（p.190）；不宜将其当作完全未触及的最终测试。 |
| 实地访问11个原始目标、钻探其中2个，另访问2个高置信候选；植被使部分目标无法接近。 | 191／13 | 不是全部预测点均已发掘或田野确认。 |
| 两处钻探未见支持焦油窑解释的诊断性遗存；结合军营背景与1944年军事手册，作者提出可能的榴弹炮阵地解释。 | 191–192／13–14 | 作者要求进一步历史研究与同类地点比较；不能写成已确认全部目标均为炮位。 |

这里特别适合强调：**形态检出与用途解释分别需要证据**。研究并不是“AI发现焦油窑”的成功故事；其考古价值之一恰在于后续证据使原有解释被修正。

#### 数值与方法核验问题

- **原文 Method 3 数量有内部不一致，已视觉核实。** p.191 为 1,858 个原始预测，去除 1,482 个，余 376 个；随后又写检出11个原始目标、7个额外候选、369个误报。p.193 Table 2 却给11个真阳性、431个误报。这些数字不能同时代表同一最终集合。教材建议不引用这组精度、F1或预测总数；本次不擅自更正原文。
- 重叠切片本身**不够证明数据泄漏**。论文 p.188 有256×256、错开128像元的切片；[官方仓库 README](https://github.com/NMC-CRS/simulated-training-data-for-archaeological-site-detection)说明分组后调用清理函数重新分配跨组重叠切片。我们仅核对公开说明，未复现该历史训练。
- Table 2 的“真阳性”依据原始12个形态目标，不等于田野确认的焦油窑。三个方法的9／12、12／12、11／12是形态检出参照，不是用途判断准确率。
- [代码存档](https://zenodo.org/records/17082764)是 v1.0（2025-09-09）；论文引用概念 DOI 10.5281/zenodo.17082763，API 解析至版本 DOI 10.5281/zenodo.17082764。开放性仅核对入口、许可和清单；未把“有代码”写成已复现。

### S17：Magnani与Clindaniel，已被第1章覆盖

**阅读范围：** 16页提取文本；重点完整阅读研究设计、样本来源、嵌入/聚类/年份估计、定量结果及定性解释（原刊221–231/PDF4–14）。未重跑代码、模型或逐项核查全部尼安德特人研究引文。 实际目视PDF页：6,13。

Magnani, Matthew, and Jon Clindaniel. 2026. “Artificial Intelligence and the Interpretation of the Past.” *Advances in Archaeological Practice* 14(2):218–233. https://doi.org/10.1017/aap.2025.10110.

[出版社页面](https://www.cambridge.org/core/journals/advances-in-archaeological-practice/article/artificial-intelligence-and-the-interpretation-of-the-past/8FE3F2CB6BBFAD49F75FFC3031158A5A)确认2025-12-18先行上线，卷期为May2026。上传文件名的Maganani应在内部索引中纠正为Magnani；文件名的2026a不自动成为书目后缀。原刊页码=PDF页序+217。

研究以DALL-E3在普通/专家提示及允许/限制提示改写的四个条件下各生成100幅图像，共400幅；GPT-3.5以普通/专家提示各生成100段，共200段文字（221–223页）。这里的“专家”是提示条件，不是另行接入专家审核过的知识库。

比较语料为JSTOR/Constellate按关键词与学科范围取得的2063篇摘要，时间1923–2023。由于可得全文仅378篇且偏早期，作者选择摘要（223页）。不能写作2063篇全文或全部尼安德特人研究。

CLIP将图文表示成向量，UMAP与HDBSCAN用于分群；余弦距离比较语义相近程度。所谓最近平均年份，是最相近20年的平均，作者把它界定为探索性时间亲近性指标（223–225页）。它不直接衡量事实准确率，也不能识别模型实际上用了哪些年代的训练资料。体裁差异、JSTOR覆盖及摘要可用性均影响比较范围。作者在229–230页的定性讨论指出玻璃容器、金属器具等时代错置及性别表征偏向；本轮未重编码全部400幅图像，不能自行给出这些错误的总体发生率。

**现有第1章段落已经准确。** 已检查“尼安德特人生活场景的生成与评价”及章末书目：模型名、2063篇摘要、221/223/223–225/230页均对应原文，且已经说明内容相似性不是事实准确率。故本附件应增加来源可核查性，不应生成第二个重复案例或书目。

文章221、223、231页称代码、提示与支持材料置于[Zenodo](https://doi.org/10.5281/zenodo.11117535)。本轮该入口未成功打开，直接API返回403；因此保留“作者公开声明”的证据等级，没有声称本轮审计了完整复现包，也不推断数据不存在。


## 4. 修改范围、独立复核与技术状态

本轮用两个短例补足现有论证：分类标准如何影响数据记录，以及模拟训练的考古假设如何接受田野检验。没有把全部附件变成章内必读资料；第1、2章和参考资源页不改动，不启动第5章。重复材料只作版本对应，不重复加入章末书目。

**文件范围：**

- chapters/chapter-03.qmd：3.3一段及末尾一条Bloch书目。
- chapters/chapter-04.qmd：4.7一段及末尾一条Peck书目。
- editorial-reviews/part1-claim-original-page-interpretation-matrix-v1.md：新增本轮两项论断及报告链接，区分历史验收。
- 本报告：17份附件的对应、指定页段、限制、取舍与验收状态。

**独立复核：** 两段分别再次对照原文和现有章节上下文，采用“在这项调查中”、极简术语解释、三种方案中两种模拟、12处初始目标中两处钻探等限定。去重计数另经实际文件重算确认。重点原文图像与文本均有直接检查，不以摘要或书目代替两段的具体论据。

**本轮技术状态：** 源文结构检查通过：第1—4章主节仍为7／8／9／8，末尾均只有一个“参考文献”节，书目为20／26／14／16条。两章所有既有标题与显式锚点逐字不变；移除各自新增段落与书目后，与基准源文完全一致。第1、2章及本次使用的基准文件Git blob指纹与已核main文件树一致。四文件的空白检查通过，内部相对链接及附件编号／指纹另作对应核查。以上为源文静态检查，不是Quarto渲染或生成HTML验收。

**仍待完成：** 用户对本轮新源文的Quarto渲染、预览、生成HTML与搜索索引提交，以及远端对应核验。Draft PR不根据PR #51或更早的日志合并。本轮没有运行论文模型，也未生成或修改docs文件。

## 5. 本批附件指纹

文件名保留上传原样，正式拼写按上文；页数、大小和SHA-256用于确认版本，不构成全文学术核验。

| 编号 | 上传文件名 | PDF页数 | 字节数 | SHA-256 |
|---|---|---:|---:|---|
| S01 | Chen 2026 Construction of multimodal oracle bone semantic reasoning and knowledge graphs in archaeology.pdf | 20 | 1671505 | `b891347aab7e474235f86a6793329191cb3bf715a82652f31156e22f30ea9cc3` |
| S02 | Fajardo 2024 Sociopolitical evolution, population clustering, and technology among early sedentary communities in northeastern Andes.pdf | 13 | 9159192 | `df8de6601aa3c1e1b5c8532c12638a0ea7b72d528dc1f3bbd28a95f55551fe06` |
| S03 | Davis 2024 Geophysics elucidate long-term socio-ecological dynamics.pdf | 13 | 2609936 | `2bc459a4e159bfc03bc3e5bfbeacc95c554abfb673742d0b4491cc6f5494ac54` |
| S04 | Rodríguez 2026 Landesque capital and ideal distribution models.pdf | 19 | 20072657 | `74e45c413ee76c2df6fcce3f2aa27b17b92ff8760d8ec7e0dec609d4e00835a5` |
| S05 | Skeates 2026 Rewriting archaeology with AI(1).pdf | 11 | 645902 | `07028a79c5703c00c66da7abcca30936de4e2109573b69bf3e45f0bea00bc7aa` |
| S06 | Nigro 2026 Archaeology and artificial intelligence(1).pdf | 77 | 4985435 | `f0483779f379bcccc0b33f87832f9c1905ff2359ed57ea1d096585016db1c329` |
| S07 | Pols 2025 Shipwreck detection in bathymetry data using semi-automated methods(1).pdf | 14 | 4102467 | `2a31574ff0657b7e6b8b0c2020b2433d5d7d058a86cbd8d1ef1c5543a9f9b3bd` |
| S08 | Sferrazza 2025 Archaeological and Experimental Lithic Microwear Classification(1).pdf | 41 | 5166240 | `6dd11f5cec3ebbbb59437ee9a5339906918658b0559003bfc4ac789c5379f92a` |
| S09 | Pey 2025 Past Water Futures-(1).pdf | 16 | 17588235 | `741e7097f837386f46de0830afac692dcdefbbdc8a7995c52d94ed75681063a1` |
| S10 | Küçükdemirci 2025 Tracing Past Agrarian Field Systems Through Ai-BasedAnalysis of Satellite Imagery in Konya(1).pdf | 17 | 22426055 | `cdfb0e07d599699facf9f8d6af18de97654f90db8a599ab03603a1be54596709` |
| S11 | Bloch 2025 Creating Standardized Guides for Pottery Temper Characterization.pdf | 15 | 1015558 | `84d26fde36c995b9016e009b17d145bc6110852d338613a22f9148d47035658a` |
| S12 | Montalvo-Puente 2026 Counting rather than weighing.pdf | 15 | 15572716 | `1f8649498497260759a49d1b85e4d243879f30eddc2c0f3a329abb1aaa15f06e` |
| S13 | Tatasuda 2026 Deep learning-based morphological classification of ceramics.pdf | 11 | 3131457 | `3a0b8858d0f2c69792e654a1e478e19133626537ed8ab483c45026fe8ab6a0a5` |
| S14 | Peker 2026 Deep Learning–Based Detection of Ancient Agricultural Terraces.pdf | 20 | 10457179 | `1caaf3b8f6f79c6da2f94f1e17252f675fd8eac1f86e08dc98b61bfadf03608c` |
| S15 | Davis 2026 The Future of Archaeological Prospection.pdf | 6 | 430068 | `5d2df9b86e61e384c939da3c3268b32bf08e612775711e27aabc83b0b876525c` |
| S16 | Peck 2026 Using Simulated Training Data to Locate Archaeological Sites with Machine Learning.pdf | 19 | 8397135 | `d9c9440c1523ba77fa40fe47410e8d0405a2a050a7fb9714ceaa36320c1c7187` |
| S17 | Maganani 2026a Artificial Intelligence and the Interpretation of the Past.pdf | 16 | 2561664 | `1f3260c15e8a2c04d2b6ff740ad3a056d1c124ed274f865e7b922b84de7879b1` |
