# 2026年10月17日新增AI与考古学文献分类目录 V1

**范围：** 75份用户上传PDF，共1,206页；P15／P29为同文两个文件，合计74项不同作品。其中P46仅为书籍前置资料，其余为73项不同文章或稿件。

**基准与用途：** 对应PR #50合并后的`main a302f83cca2c2d4b8ef9eb8e4f9935527ad87cfd`。本目录为内部编辑记录，配合[综合评估及本轮修订说明](part1-ai-archaeology-literature-assessment-20261017-v1.md)使用。75条接收记录不等于75项互相独立的证据；社论、预印本、方法指南与实证研究分别标明。

**读取口径：** 每条说明实际定向核读的原文页段。对全文作文字提取是检索步骤，不代表1,206页已逐页精读。只有明确写出“页图目视”的范围具有该读取状态。P46没有正文，只达到书目／目录级别。各条陈述的是作者报告及本次编辑判断；本轮未独立复现论文实验或统一比较模型性能。

**书目口径：** 先据原PDF，再与可取得的出版商、机构库或DOI注册记录对照。在线日期与正式卷年分开；DOI中的年份不直接充当出版年。登记信息如与原文冲突，保留冲突说明。页码中“PDF”表示文件页序，“印刷／文内”表示作品本身分页。原始文件名与指纹仅用于辨认用户提供的具体附件，不据文件名判断题名或研究结论。

## 分类索引

每项只放入一个主要类别，具体方法和交叉用途见条目。分类服务检索，不将全部数字方法归为机器学习。生成式AI类的10份文件包括P15／P29重复组，对应9项不同作品。

| 类别 | 文件数 | 文件编号 |
|---|---:|---|
| 遥感、田野调查与空间建模 | 20 | [P02](#p02)、[P03](#p03)、[P04](#p04)、[P05](#p05)、[P09](#p09)、[P11](#p11)、[P22](#p22)、[P24](#p24)、[P27](#p27)、[P33](#p33)、[P45](#p45)、[P50](#p50)、[P52](#p52)、[P53](#p53)、[P54](#p54)、[P61](#p61)、[P63](#p63)、[P71](#p71)、[P72](#p72)、[P75](#p75) |
| 器物研究与分类评价 | 12 | [P08](#p08)、[P12](#p12)、[P20](#p20)、[P26](#p26)、[P30](#p30)、[P47](#p47)、[P48](#p48)、[P55](#p55)、[P62](#p62)、[P67](#p67)、[P70](#p70)、[P73](#p73) |
| 环境、人群与社会解释 | 7 | [P01](#p01)、[P10](#p10)、[P14](#p14)、[P32](#p32)、[P36](#p36)、[P40](#p40)、[P69](#p69) |
| 计算考古的理论、记录与基础设施 | 13 | [P06](#p06)、[P13](#p13)、[P25](#p25)、[P31](#p31)、[P38](#p38)、[P42](#p42)、[P44](#p44)、[P46](#p46)、[P49](#p49)、[P51](#p51)、[P56](#p56)、[P68](#p68)、[P74](#p74) |
| 生成式AI、古代语言与教学 | 10 | [P07](#p07)、[P15](#p15)、[P19](#p19)、[P29](#p29)、[P34](#p34)、[P37](#p37)、[P39](#p39)、[P43](#p43)、[P57](#p57)、[P58](#p58) |
| 学术规范、社群协作与包容性 | 13 | [P16](#p16)、[P17](#p17)、[P18](#p18)、[P21](#p21)、[P23](#p23)、[P28](#p28)、[P35](#p35)、[P41](#p41)、[P59](#p59)、[P60](#p60)、[P64](#p64)、[P65](#p65)、[P66](#p66) |

**本轮进入教材的来源：** P20、P49、P55、P75。其余为方法、案例、教学或背景储备；条目中的“建议”不意味着本轮已新增对应章节、练习或资源页面。

## 1. 遥感、田野调查与空间建模

### P02

Georgios Alexandros Asvestas; Christos Vasilakos. 2026. “Multi-sensor UAV predictive modelling for archaeological feature detection: from probability surfaces to excavation targets on Lesvos Island, Greece.” *Journal of Archaeological Science: Reports*. 76:106114，文内1–22页。 DOI：[10.1016/j.jasrep.2026.106114](https://doi.org/10.1016/j.jasrep.2026.106114)。

**附件：** `Asvestas 2026 Multi-sensor UAV predictive modelling for archaeological feature detection.pdf`；22页；SHA-256：`3ad3e47396e997a20045088fe9b8a59ecb1831cb2ec7f935083541636d91ca57`。

**日期与版本：** 在线日期：2026-10-06；卷期日期：2026-12。

**研究类型与本轮安排：** 实证研究：多传感器无人机遥感、逻辑回归与随机森林比较。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,7,8,21页；全部页已提取供检索，但不将自动提取等同逐页通读。

**原文定位：**

- PDF/文内7–8页：分层70/30划分、SMOTE仅用于训练集、Thermi至Arisvi的固定预处理迁移
- PDF/文内21页，§4.3：历史建筑平面之外不等于已证实无遗存；Arisvi预测尚待田野核验

**可支持的论点：**

- 综合热红外、多光谱等影像形成遗迹存在的预测面，并在第二地点应用训练地点确定的处理流程。
- 作者明确指出，Thermi评价依照既有建筑平面，Arisvi高值聚集仅形成发掘候选。

**限制与解释边界：**

- 平面记录以外作为负例不等于地下考古学缺失；模型与历史平面的一致性不是完整地下遗存的真值精度。
- 两处案例、不同季节与植被条件限制外推；所读划分程序为分层随机划分，不能自动解释为空间独立验证。

**教材用途：** 第4章模型泛化与地面核验的备用例证；本轮不再与Comer、Zimmer案例叠加。

**文件名／版本问题：** 未发现影响辨识的文件名问题。

**资料与代码状态：** 21页说明数据依文物管理机构许可按请求提供，不可标为完全开放。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1016%2Fj.jasrep.2026.106114)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。

### P03

Fereshte Azarkhordad; Juan A. Barceló; Hasan Hashemi Zarajabad; Abed Taghavi. 2026. “Using convolutional neural networks to identify qanats and analysis of their role in the formation of Zuzan City (Iran, Islamic period).” *Archaeological and Anthropological Sciences*. 18(7):159，文内1–18页。 DOI：[10.1007/s12520-026-02522-5](https://doi.org/10.1007/s12520-026-02522-5)。

**附件：** `Azarkhordad 2026 Using convolutional neural networks to identify qanats and analysis of their role in the formation of Zuzan City.pdf`；18页；SHA-256：`25dfdcb5164cd8cd63972e389f7cc8885171955c034c1136e4fb245e0eccb6e9`。

**日期与版本：** 在线日期：2026-06-22；卷期日期：2026-7。

**研究类型与本轮安排：** 实证研究：CNN识别坎儿井竖井/地表迹象，结合历史资料解释城市形成。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,9,10,13,15页；全部页已提取供检索，但不将自动提取等同逐页通读。

**原文定位：**

- PDF/文内9页：72幅标注影像，57训练、15验证
- PDF/文内10页：部分标注、目标框评价
- PDF/文内13、15页：坎儿井分布、城市史解释与待核验工作

**可支持的论点：**

- CNN用于从影像中识别与坎儿井有关的地表目标；城市供水和形成过程的解释还使用历史、地方口述等资料。

**限制与解释边界：**

- 方法段所述80/20为一次留出划分，不能因为作者使用cross-validation一词便称其实施了k折交叉验证。
- 竖井或影像线索不等于完整地下渠道；少量影像、部分标注限制性能解释。
- 模型分值不能直接当成遗迹真实存在的校准概率，空间相伴也不能独立证明城市形成的因果机制。

**教材用途：** 可为后续遥感案例储备，当前Part I只保留方法边界，不增加细节。

**文件名／版本问题：** 未发现影响辨识的文件名问题。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1007%2Fs12520-026-02522-5)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。

### P04

Elena Balmaceda-Baraona; Víctor Méndez; Virginia McRostie; Ale Vidal-Elgueta; Francisca P. Díaz. 2026. “Mapping past forests in the Atacama Desert, Chile: A remote sensing and machine learning approach for archaeology.” *Journal of Archaeological Science*. 195:106688，文内1–15页。 DOI：[10.1016/j.jas.2026.106688](https://doi.org/10.1016/j.jas.2026.106688)。

**附件：** `Balmaceda-Baraona 2026 Mapping past forests in the Atacama Desert, Chile.pdf`；15页；SHA-256：`a956dca11810461fa7baba95962e420f06311c72fda33a0caadb7c5d4109711b`。

**日期与版本：** 在线日期：2026-09-15；卷期日期：2026-11。

**研究类型与本轮安排：** 实证研究：卫星遥感与机器学习识别阿塔卡马古森林残存信号。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,6,13,14页；全部页已提取供检索，但不将自动提取等同逐页通读。

**原文定位：**

- PDF/文内6页：区域、日期及训练ROI设计
- PDF/文内13–14页：地面发现、光谱机制尚不充分、年代与人类活动关系限制

**可支持的论点：**

- 研究以现代卫星光谱特征预测古森林残留相关区域，并报告部分田野观察支持。

**限制与解释边界：**

- 不同区域使用不同时间影像与局部训练资料，结果不等于同一模型无调整跨区迁移。
- 光谱究竟反映土壤、水分还是其他机制仍需查明；识别到相关地表信号不等于直接观测过去森林。
- 森林遗留与人类活动可能跨越很长时段，空间共现不自动支持同时性或因果关系。

**教材用途：** 第3章观测—代理变量—解释的备用例证；Orengo已有同类概念，不宜重复扩写。

**文件名／版本问题：** 未发现影响辨识的文件名问题。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1016%2Fj.jas.2026.106688)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。

### P05

Sushant Begade. 2027. “Inferring Behavioural Landscape Systems in Palaeolithic Archaeology: Unsupervised Spatial Learning as a Framework for Formal Inductive Inference.” *Journal of Archaeological Method and Theory*. 34(1):4，文内1–30页。 DOI：[10.1007/s10816-026-09812-1](https://doi.org/10.1007/s10816-026-09812-1)。

**附件：** `Begade 2026 Inferring Behavioural Landscape Systems in Palaeolithic Archaeology.pdf`；30页；SHA-256：`8f9c51f9d43dc08ba769203ff0e86c25e4ac2d364e48428d4069b8de9cbea452`。

**日期与版本：** 在线日期：2026-07-17；卷期日期：2027-3。

**研究类型与本轮安排：** 方法及实证研究：158处露天旧石器时代记录的无监督空间聚类。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,13,14,21,24页；全部页已提取供检索，但不将自动提取等同逐页通读。

**原文定位：**

- PDF/文内13–14页：158处地理记录、DEM和代理变量、记录密度含义
- PDF/文内21页：聚类不能唯一识别行为机制、历时叠加限制
- PDF/文内24页：不同聚类诊断与所选k值的敏感性

**可支持的论点：**

- 以环境和原料可达性等变量进行无监督分组，用于提出景观利用的探索性解释。

**限制与解释边界：**

- 核密度来自遗存记录点，不能改称石器密度；资料缺乏统一石器数量、技术和类型清单。
- 158处露天记录可能是调查强度、埋藏过程和历时叠加的产物，聚类不是同时存在的聚落或古人群类别。
- 内部聚类稳定并不确定唯一历史机制。

**教材用途：** 第2章计算考古学与第4章探索性分析的阅读储备；当前无需新段落。

**文件名／版本问题：** 上传名标2026，对应先行在线年；正式卷34(1):4标2027。两年均保留说明，不视为未出版。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1007%2Fs10816-026-09812-1)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。
- [核查来源2](https://link.springer.com/article/10.1007/s10816-026-09812-1)：出版社页面已读书目与摘要：2026-07-17上线，34:4(2027)；页面正文订阅受限，定向原文阅读使用上传PDF

### P09

Quentin Bourgeois; Eva Kaptijn; Wouter Verschoof-van der Vaart; Karsten Lambers. 2024. “Assessing the quality of citizen science in archaeological remote sensing: results from the Heritage Quest project in the Netherlands.” *Antiquity*. 98(402):1662–1678。 DOI：[10.15184/aqy.2024.127](https://doi.org/10.15184/aqy.2024.127)。

**附件：** `Bourgeios 2024 Assessing the quality of citizen science in archaeological remote sensing.pdf`；17页；SHA-256：`41b1c3121da15e299b28ed8d340fff288f623efc0faecf9fa182027e91aa47fa`。

**日期与版本：** 在线日期：2024-10-14；卷期日期：2024-12。

**研究类型与本轮安排：** 实证研究：公民科学人工LiDAR分类及田野核查；非直接ML实验。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,5,6,9,10,13,14页；全部页已提取供检索，但不将自动提取等同逐页通读。 原页图像复核：PDF第10页。

**原文定位：**

- PDF9–10／印刷1670–1671页：已修复登记古坟的可见性偏差，380处钻探/试掘参照
- PDF13／印刷1674页：低共识和低矮小型古坟的遗漏
- PDF14／印刷1675页：结论及外推

**可支持的论点：**

- 既有登记古坟常因修复而较高、植被较少，不能代表待发现古坟的识别难度。
- 研究用219处新钻探位置加161处既有钻探/试掘结果，评价380处志愿者共识目标；较高共识通常对应较高精确率。

**限制与解释边界：**

- 380处是已提出的共识位置，不是全景观完整普查，不能由此直接估计全部遗漏。
- 约千处潜在新古坟属于样本精确率外推，不是逐处证实的千处发现。
- 少见低矮类型可能被多数志愿者漏记，投票共识不是无条件真值。

**教材用途：** 可用于第3章人工标签来源或第4章评价参照的备用短例；避免误称AI发现。

**文件名／版本问题：** 上传名Bourgeios拼写有误；原文作者Bourgeois。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.15184%2Faqy.2024.127)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。

### P11

Benjamin J. Britton; Alec McLellan; Jeffrey Brewer; Christopher Carr; Nicholas Dunning; Lin Liu. 2026. “Evaluating Broadscale Deep Learning for Maya Settlement Detection in G-LiHT Lidar.” *Journal of Archaeological Method and Theory*. 33(2):15，文内1–38页。 DOI：[10.1007/s10816-025-09741-5](https://doi.org/10.1007/s10816-025-09741-5)。

**附件：** `Britton 2026 Evaluating Broadscale Deep Learning for Maya Settlement Detection in G‑LiHT Lidar.pdf`；38页；SHA-256：`200b9f027cdf82a8d98a69f0da74ecd9f25ea6160a3ce35c1806984497680396`。

**日期与版本：** 在线日期：2025-11-19；卷期日期：2026-6。

**研究类型与本轮安排：** 实证研究：G-LiHT LiDAR、YOLOv3与玛雅建筑检测。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,19,21,24,25,26,32,33,34页；全部页已提取供检索，但不将自动提取等同逐页通读。 原页图像复核：PDF第33页。

**原文定位：**

- PDF/文内19、21、24–26页：人工筛选训练数据、评价格及表5
- PDF/文内32–33页：421平方千米条带约占大研究区1.2%，外推假设及无全面地面核验
- PDF/文内34页：代码/模型与数据可用性

**可支持的论点：**

- 作者以人工检查的2000个训练目标评估LiDAR建筑检测，结果说明方法在已抽取条带资料中的潜力。

**限制与解释边界：**

- 实际LiDAR覆盖421平方千米，不是整个35584平方千米均经模型与实地验证。
- 评价标签依专家判读及既有资料，训练和测试格未全面通过田野确认。
- 所设评价格包含有意选择的正负比例，不可视为实际部署目标率。
- 空间自相关及区域地形/保存差异仍构成外推限制。
- 若使用表5制作习题，需进一步核对评价格和目标计数的关系；400格可含多个目标，不能据合计超过400断言数值错误。

**教材用途：** 第4章泛化/评价单元的案例储备；若只补一个例子，优先P75。

**文件名／版本问题：** 正式刊年2026；在线出版2025-11-19。

**资料与代码状态：** Q2000模型DOI 10.7945/tbvg-8n31；NASA原始资料开放，部分训练资料按请求提供，未运行复现。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1007%2Fs10816-025-09741-5)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。
- [核查来源2](https://link.springer.com/article/10.1007/s10816-025-09741-5)：出版社检索结果核实正式刊年2026、在线日期2025-11-19及题名作者

### P22

Sean Field; Logan Dean. 2026. “A Computer Vision Survey of the Northern San Juan.” *American Antiquity*. 在线先行1–13页（PDF及DOI登记未分配卷期）。 DOI：[10.1017/aaq.2026.10223](https://doi.org/10.1017/aaq.2026.10223)。

**附件：** `Field 2026 A Computer Vision Survey of the Northern San Juan.pdf`；13页；SHA-256：`69796d4dd6059a431e827b9f40852eccb458b31b1f93f7276fa79b65bc670ee6`。

**日期与版本：** 在线日期：2026-09-18。

**研究类型与本轮安排：** REPORT：计算机视觉辅助北圣胡安LiDAR调查与迭代训练。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,5,6,7,8,9,10页；全部页已提取供检索，但不将自动提取等同逐页通读。

**原文定位：**

- PDF/文内5–6页：Mesa Verde训练资料与可见性、年代偏向
- PDF/文内6–8页，表1：初次部署precision0.15；负例抽样评价与全量外推
- PDF/文内9–10页：人工复核、既有遗址参照与调查边界

**可支持的论点：**

- 初始内部测试准确率93.5%的模型部署到较大区域后出现大量误报；研究结合人工复核扩充训练资料后改善结果。
- 作者区分仅根据已核查影像计算的指标与将负例样本率外推到未核查影像的指标。

**限制与解释边界：**

- 阳性影像全面人工复核、阴性影像抽样复核；最终召回率依赖未复核部分的外推假设。
- 4,905个为可见住宅相关凹陷/结构记录，不应写成全部新发现、地面确认的遗址。
- 训练资料主要反映晚期可见土著普韦布洛住宅；崖居、不可见遗存及其他时期不在同等识别范围。
- 内部高准确率与总体类别不均衡下的高准确率均不能直接代表考古调查有效性。

**教材用途：** 可替代而非叠加P75，适合第4章解释部署评价与精确率；当前作为强备用。

**文件名／版本问题：** 未发现影响辨识的文件名问题。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1017%2Faaq.2026.10223)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。

### P24

Margaret J. Furtner; Robert L. Anemone; Lei Wang; Juliet K. Brophy. 2026. “Evaluating Random Forest Model Performance for Cave and Sinkhole Prediction in the Cradle of Humankind, South Africa: Preliminary Analysis and Variable Importance Assessments.” *Journal of Archaeological Method and Theory*. 33(3):34，文内1–34页。 DOI：[10.1007/s10816-025-09761-1](https://doi.org/10.1007/s10816-025-09761-1)。

**附件：** `Furtner 2026 Evaluating Random Forest Model Performance for Cave and Sinkhole Prediction in the Cradle of Humankind.pdf`；34页；SHA-256：`6b6fa1e0f3c192e8223091313fa5d8a266f289909b1030c20fd3a6da1d2eb639`。

**日期与版本：** 在线日期：2026-03-04；卷期日期：2026-9。

**研究类型与本轮安排：** 初步实证：随机森林预测洞穴和塌陷洼地，含空间成组交叉验证。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,13,15,16,21,26,29,30页；全部页已提取供检索，但不将自动提取等同逐页通读。 原页图像复核：PDF第21页。

**原文定位：**

- PDF/文内13、15–16页：正类为地点周围像元、随机伪缺失
- PDF/文内21页：同一正类地点的像元整体分配至同一折
- PDF/文内26、29–30页：性能、限制及未来预测图/田野检验

**可支持的论点：**

- 研究将同一洞穴/洼地周围的像元作为整体分配给训练或测试，避免同一地点的相似像元跨两组。

**限制与解释边界：**

- 1080个正类像元来自15个含化石洞穴及60个地图解释位置周围，不等于1080个独立洞穴。
- 负例为背景伪缺失，非逐处确定不存在洞穴；随机选样与研究史可能影响性能。
- 文中十折是保持地点簇完整的成组划分，不应改称十个连续区域的空间分块。
- 预测目标是洞穴/洼地形态潜力，不是已确认含化石遗址；新区域预测和田野验证尚属后续工作。

**教材用途：** 可在未来教学说明为什么按遗址分组而非像元随机拆分；本轮已有Comer，避免重复。

**文件名／版本问题：** 未发现影响辨识的文件名问题。

**资料与代码状态：** 工作流程Zenodo DOI 10.5281/zenodo.15186515；输入数据按请求提供，未复现。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1007%2Fs10816-025-09761-1)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。
- [核查来源2](https://link.springer.com/article/10.1007/s10816-025-09761-1)：出版社页面已打开；书目与上传PDF及Crossref相符

### P27

Amy Hatton; Amina Jambajantsan; Paul S. Breeze; Maria Guagnin; Michael T. Fisher; Faisal al-Jibreen; Abdullah M. Alsharekh; Michael D. Petraglia; Huw S. Groucutt. 2026. “Semi-automated detection of Holocene archaeological structures along the southern edge of the Nefud desert.” *Journal of Archaeological Science: Reports*. 72:105734，文内1–10页。 DOI：[10.1016/j.jasrep.2026.105734](https://doi.org/10.1016/j.jasrep.2026.105734)。

**附件：** `Hatton 2026 Spatial patterns of Early Neolithic expansion in the north-eastern Iberian Peninsula, western Mediterranean.pdf`；10页；SHA-256：`44ce31cd49bb654331aa9360b7240f74144d6c97289ba93ac6151e97a536c59f`。

**日期与版本：** 在线日期：2026-04-10；卷期日期：2026-6。

**研究类型与本轮安排：** 实证研究：阿拉伯石构遗存的多类别语义分割模型比较。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,4,5,6,8页；全部页已提取供检索，但不将自动提取等同逐页通读。

**原文定位：**

- PDF/文内4页：人工九类记录、择六类、确定性评级及740结构
- PDF/文内5–6页：分层划分、类别不均衡与逐类结果
- PDF/文内8页：跨地理区泛化尚待测试

**可支持的论点：**

- 以六类人工标注的石构遗存比较U-Net、MA-Net、SegFormer，不同结构类型的识别差异明显。

**限制与解释边界：**

- 整体平均指标受样本多或占像元多的类别主导，不能概括稀少三角形与复杂尾状墓葬的表现。
- 训练标签包括影像高可信判读和部分田野已核位置，并非全部实地真值。
- 跨区适用性是未来测试，不能写成已证明阿拉伯半岛和黎凡特普遍可迁移。
- 分割像元指标、结构数量和发现场所数量需要分别表达。

**教材用途：** 第3章类别定义及第4章分组性能的储备。

**文件名／版本问题：** 上传文件标题错误地写成Early Neolithic expansion论文；实际为Hatton等Nefud石构遗存。与P61不是同文重复。

**资料与代码状态：** 影像和掩膜Zenodo DOI 10.5281/zenodo.17362760，坐标为遗产保护未公开；未复现。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1016%2Fj.jasrep.2026.105734)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。

### P33

Melda Küçükdemirci. 2025. “Tracing Past Agrarian Field Systems Through Ai‐Based Analysis of Satellite Imagery in Konya, Central Anatolia, Türkiye.” *Archaeological Prospection*. 32(4):881–897。 DOI：[10.1002/arp.2001](https://doi.org/10.1002/arp.2001)。

**附件：** `Küçükdemirci 2025 Tracing Past Agrarian Field Systems Through Ai-BasedAnalysis of Satellite Imagery in Konya.pdf`；17页；SHA-256：`cdfb0e07d599699facf9f8d6af18de97654f90db8a599ab03603a1be54596709`。

**日期与版本：** 在线日期：2025-07-03；卷期日期：2025-10。

**研究类型与本轮安排：** 实证研究：Google Earth影像的SVM、CNN微调与混合分类。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,7,14,15页；全部页已提取供检索，但不将自动提取等同逐页通读。

**原文定位：**

- PDF7／印刷887页：四类各250训练例，排除七幅测试片区
- PDF14／印刷894页：影像来源限制及年代/文化归属尚待证据
- PDF15／印刷895页：模型比较结论

**可支持的论点：**

- 比较三种视觉分类策略，并将选定模型用于七幅影像片区的格网状农田迹象识别。

**限制与解释边界：**

- RGB输出的空间分辨率、拍摄时间和来源不一，范围有限。
- 格网状地表形态类似所谓Celtic fields不等于已确定青铜时代或文化归属；田野、地层和测年属后续。
- 模型类别识别准确率不能替代古代土地利用解释。

**教材用途：** 后续景观遥感材料；本轮不新增。

**文件名／版本问题：** 未发现影响辨识的文件名问题。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1002%2Farp.2001)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。

### P45

Giles Spence Morrow; Parker VanValkenburgh; Christopher Wai; Steven A. Wernke. 2024. “Augmenting field data with archaeological imagery survey: mapping hilltop fortifications on the north coast of Peru.” *Antiquity*. 98(397):193–210。 DOI：[10.15184/aqy.2023.176](https://doi.org/10.15184/aqy.2023.176)。

**附件：** `Murrow 2024 Augmenting field data with archaeological imagery survey.pdf`；18页；SHA-256：`34f6b35ac1038d64af3d0b25c054e86956ecb6011ce15ae8e7272826d6e71676`。

**日期与版本：** 在线日期：2023-12-18；卷期日期：2024-2。

**研究类型与本轮安排：** 实证研究：人工协作卫星调查与既有田野记录比较；非直接ML实验。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,10,11,14,15,16页；全部页已提取供检索，但不将自动提取等同逐页通读。

**原文定位：**

- PDF10–11／印刷202–203页：影像与徒步调查的记录比较及计数单位
- PDF15–16／印刷207–208页：诊断性小遗迹、年代与后续田野核验

**可支持的论点：**

- GeoPACHA影像调查与较早的徒步调查各识别不同的山顶防御地点，合并资料扩充记录。

**限制与解释边界：**

- 原田野研究的多期占用记录须转换为地理地点才能比较，不能混合109期次与71地点。
- 相似形态不能代替防御用途与年代判断；影像不易见小型投石堆等诊断特征。
- 新影像位置仍需目标性地面核查；不能把两表所谓precision解释成已知真实全部遗址的模型精确率。
- 训练深度学习属后续可能用途，不是本文方法。

**教材用途：** 第3章资料整合与第2章数字考古学的储备；P75已足够时不再叠加。

**文件名／版本问题：** 上传名Murrow有误；第一作者为Giles Spence Morrow。刊年2024，在线2023。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.15184%2Faqy.2023.176)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。
- [核查来源2](https://www.cambridge.org/core/journals/antiquity/article/augmenting-field-data-with-archaeological-imagery-survey-mapping-hilltop-fortifications-on-the-north-coast-of-Peru/683A30ABC261C1D80AD04E13652774F5)：出版社检索结果核实书目，未作在线全文重读

### P50

Gabriela Oré Menéndez. 2026. “Agricultural Infrastructure Detection Through Multispectral Satellite Remote Sensing and PeruSAT-1 Images in Huarochirí, Peru.” *Journal of Archaeological Method and Theory*. 33(2):14，文内1–40页。 DOI：[10.1007/s10816-025-09742-4](https://doi.org/10.1007/s10816-025-09742-4)。

**附件：** `Oré Menéndez 2026 Agricultural Infrastructure Detection Through Multispectral Satellite Remote Sensing.pdf`；40页；SHA-256：`ca988b9d69cd0080e461aafad72895c4af3bccb8fd641a1cbf1b3572bc226d4d`。

**日期与版本：** 在线日期：2025-11-19；卷期日期：2026-6。

**研究类型与本轮安排：** 实证研究：多光谱顺序筛选、K-means及GIS识别农业设施。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,22,26,27,29,30,34,35页；全部页已提取供检索，但不将自动提取等同逐页通读。

**原文定位：**

- PDF/文内22页：NDVI与坡度筛选、无监督分类
- PDF/文内26–29页：51个一平方千米网格人工影像比较，表3–4
- PDF/文内30、34–35页：谱混淆、地方知识及跨区再校准

**可支持的论点：**

- 可在标准GIS流程中筛选农业设施候选；报告总体准确率79.8%，同时精确率42.8%、召回率56.9%。

**限制与解释边界：**

- 评价参照是Google Earth人工数字化，不是51网格均经田野普查。
- 自然植被、现代休耕与古老废弃梯田的光谱相近，不能由影像类属直接推定殖民期土地制度变化。
- 表述重点须为类别不均衡下多个指标的不同含义，不可只报79.8%就称高可靠。
- 其他地区须调整坡度、NDVI和建筑材料条件；不是直接可移植通用模型。

**教材用途：** 第4章简单基线与评价指标的备用；不需要新增完整GIS教程。

**文件名／版本问题：** 正式刊年2026，先行在线2025-11-19。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1007%2Fs10816-025-09742-4)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。

### P52

Laura Pey; Kevin Lane; Luis Coll; Jennifer Grant; Mario Advíncula; Andy Combey; Alexander Herrera. 2025. “Past Water Futures: A Digital Survey of Prehispanic Dams in the Central Andes.” *Archaeological Prospection*. 32(4):989–1004。 DOI：[10.1002/arp.70001](https://doi.org/10.1002/arp.70001)。

**附件：** `Pey 2025 Past Water Futures-.pdf`；16页；SHA-256：`741e7097f837386f46de0830afac692dcdefbbdc8a7995c52d94ed75681063a1`。

**日期与版本：** 在线日期：2025-08-17；卷期日期：2025-10。

**研究类型与本轮安排：** 实证项目研究：人工数字调查、GIS与选点田野/摄影测量；AI为未来方向。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,7,12,14页；全部页已提取供检索，但不将自动提取等同逐页通读。

**原文定位：**

- PDF7／印刷995页：70%区域进度、535记录/442遥感新增、选点核验标准
- PDF12／印刷1000页：功能分类改变、后续检验
- PDF14／印刷1002页：CNN与人机协作属未来计划

**可支持的论点：**

- 建立安第斯水土管理构筑物资料库，结合少量重点区田野检查和社区需求讨论修复潜力。

**限制与解释边界：**

- 水坝更易见，旧清单偏水坝，类型比例不是过去真实构筑物比例。
- 田野热点按潜在古老性、社区需求和合作可行性选择，不是用于估计全库准确率的随机验证。
- 535项含不同来源，442个新影像记录不等于442处经测年确认的前西班牙水坝。
- CNN尚未训练应用，不能列为AI发现案例。

**教材用途：** 第2章数字考古与第3章记录来源的补充阅读；本轮不插入。

**文件名／版本问题：** PDF更正说明：2025-09-09将标题Purvey更正为Prehispanic；当前标题用更正后版本。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1002%2Farp.70001)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。

### P53

Gonzalo Pimentel G.; Luis Pérez R.; Mariana Ugarte F.; Juan Gili H.; Javier Arévalo L.; Rodrigo Mendoza; Manuel Pérez-Carrasco; Marcela Sepúlveda. 2026. “Assessment of the threatened geoglyphs of Alto Caramucho, in the Atacama Desert, using new technologies.” *Antiquity*. 100(413):e53，文内1–9页。 DOI：[10.15184/aqy.2026.10372](https://doi.org/10.15184/aqy.2026.10372)。

**附件：** `Pimentel 2026 Assessment of the threatened geoglyphs of Alto Caramucho.pdf`；9页；SHA-256：`9e7d5fea9047aaa6f23599944a21adf430840769f5e15698649a5033951f34d5`。

**日期与版本：** 在线日期：2026-06-16；卷期日期：2026-10。

**研究类型与本轮安排：** Project Gallery：DeepLabv3识别车辆痕迹、摄影测量与地画损害记录。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,3,6,8页；全部页已提取供检索，但不将自动提取等同逐页通读。

**原文定位：**

- PDF/文内3页：91网格、按网格保留20%测试、DeepLabv3与F1
- PDF/文内6页：地画损害及历史影像比较

**可支持的论点：**

- 语义分割检测沙漠地表车辆痕迹，结合摄影测量和历史影像评估已有地画受损。

**限制与解释边界：**

- 目标是现代车辆痕迹，不能改称AI识别或释读地画文化意义。
- 测试F1=76.75%是所述本地影像分割表现，不等于所有损害区域已准确复原。
- 年代及损害过程还依赖多期历史影像；有限篇幅未提供本次可复现实验所需的全部材料。

**教材用途：** 第1章AI任务类别可留遗产监测备用，当前已有多个入门例子，不再扩写。

**文件名／版本问题：** 未发现影响辨识的文件名问题。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.15184%2Faqy.2026.10372)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。

### P54

Cal T. Pols; Fraser Sturt; Crystal El Safadi; Antonia Marcu. 2025. “Shipwreck detection in bathymetry data using semi-automated methods: Combining machine learning and topographic inference approaches.” *Journal of Archaeological Science*. 181:106297，文内1–14页。 DOI：[10.1016/j.jas.2025.106297](https://doi.org/10.1016/j.jas.2025.106297)。

**附件：** `Pols 2025 Shipwreck detection in bathymetry data using semi-automated methods.pdf`；14页；SHA-256：`2a31574ff0657b7e6b8b0c2020b2433d5d7d058a86cbd8d1ef1c5543a9f9b3bd`。

**日期与版本：** 在线日期：2025-07-05；卷期日期：2025-9。

**研究类型与本轮安排：** 实证研究：水深地形筛选与目标检测识别沉船。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,7,8,9,11页；全部页已提取供检索，但不将自动提取等同逐页通读。

**原文定位：**

- PDF/文内7–8页：地理测试区、形态分组及初筛
- PDF/文内9页表5：机器学习在初筛后197目标上的表现
- PDF/文内9、11页：背景地貌混淆、预训练模型迁移及全流程限制

**可支持的论点：**

- 地形规则将测试区域缩减96%，同时保留253个已知/可能沉船目标中的197个；再对筛选后的资料比较视觉模型。

**限制与解释边界：**

- 初筛已漏失目标，后续ML表5的197目标分母不能直接替代全区253目标；需报告整个流程累计漏失。
- 显眼完整沉船与小型可能沉船表现不同，类型分布影响数字。
- 未经本地微调的现成模型无正确检测；微调也未优于所有通用预训练方法，不能把预训练视为普遍迁移保证。
- 自然海床地貌产生误报；可能沉船依数据库位置判读，不等于全部实地确认。

**教材用途：** 第4章流程层面评价与迁移的强备用；本轮只留记录，避免案例堆叠。

**文件名／版本问题：** 未发现影响辨识的文件名问题。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1016%2Fj.jas.2025.106297)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。

### P61

Joel Segarra; Jose Luis Araus. 2026. “Spatial patterns of Early Neolithic expansion in the north-eastern Iberian Peninsula, western Mediterranean: A landscape and environmental machine learning approach.” *Journal of Archaeological Science: Reports*. 72:105783，文内1–11页。 DOI：[10.1016/j.jasrep.2026.105783](https://doi.org/10.1016/j.jasrep.2026.105783)。

**附件：** `Segarra 2026 Spatial patterns of Early Neolithic expansion in the north-eastern Iberian Peninsula, western Mediterranean.pdf`；11页；SHA-256：`2f3afbe88bd0e9d0f660feb49dd1df201f3962dd7959a59d67a78585e259cf76`。

**日期与版本：** 在线日期：2026-04-24；卷期日期：2026-6。

**研究类型与本轮安排：** 实证空间建模：年代插值、最低成本路径、随机森林解释新石器时代扩展。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,5,9,10页；全部页已提取供检索，但不将自动提取等同逐页通读。

**原文定位：**

- PDF/文内5页§2.3：134景观单元、插值年代派生早晚标签、随机70/30与5折
- PDF/文内9–10页：两条扩展途径假说、稀疏记录/边缘效应及进一步发掘测年需求

**可支持的论点：**

- 将年代插值、路径与环境分类结合，讨论东北伊比利亚早期农业扩展的多种可能途径。

**限制与解释边界：**

- 分类目标的早晚来自先前插值面和四分位阈值，不是134个独立直接测年。
- 方法为随机留出和普通5折，不能据文中“独立”用语认定消除了空间相关。
- 变量重要性不直接等于历史因果约束；南部一处记录可能影响大片插值，扩展路线仍需新证据。

**教材用途：** 第3章派生标签与第4章预测/解释层级的备用；不新增地区农业史。

**文件名／版本问题：** 与错误命名的P27不是重复；本篇正确作者Segarra与Araus，DOI105783。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1016%2Fj.jasrep.2026.105783)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。

### P63

Casey Haoran Shi; Cayleigh Elizabeth Haag. 2026. “Pixelated Transformations: Tracing Changing Irrigation Management Through Deep-Learning-Based Object Detection on HEXAGON and SkySat Satellite Images.” *Journal of Archaeological Method and Theory 33(3)*. 文章48，文内页1–27。 DOI：[10.1007/s10816-026-09787-z](https://doi.org/10.1007/s10816-026-09787-z)。

**附件：** `Shi 2026 Pixelated Transformations.pdf`；27页；SHA-256：`8cde6d3834b71d688c26abf5fef144a7cd2cb0c3ca8feb053d8c8d391e2206ea`。

**日期与版本：** 在线日期：2026-04-23；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** 吐鲁番坎儿井地表井丘多期卫星影像目标检测，结合土地利用分类、田野/民族志及历史资料讨论灌溉管理。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性原文核读：第1—2、6—14及18—22页相关段落；第9页划分方法已目视；出版社题录/摘要核对。未运行模型或核读补充数据。

**原文定位：**

- 印刷／文内8页；PDF第8页；Table 2及人工标注；原PDF文本核读
- 印刷／文内9页；PDF第9页；按地理位置划分train/validation/test；原PDF文本及页面目视
- 印刷／文内11页；PDF第11页；Model Performance；原PDF文本核读
- 印刷／文内12页；PDF第12页；Table 4及多日期检测数量；原PDF文本核读
- 印刷／文内14页；PDF第14页；井丘表示、维护推测与误差；原PDF文本核读
- 印刷／文内19页；PDF第19页；田野与地方灌溉组织；原PDF文本核读
- 印刷／文内22页；PDF第22页；田野资料对识别和解释的作用；原PDF文本核读

**页图核验补记：** PDF第9页已目视核验。

**可支持的论点：**

- 地表井丘检测、同一位置跨时比较、灌溉维护与社会组织解释属于不同环节，需要不同证据。
- 论文把同一地理位置的多日期影像归入同一训练/验证/测试集合，避免跨日期重复地点分散到不同集合。
- 卫星质量及光照变化可以产生表观数量下降；作者自己不把1974—1982年下降直接解释为工程破坏。

**限制与解释边界：**

- 第11页87.7%标为precision，不是accuracy；多期累计检测次数也不是独立古遗址数量。
- 正文与表格存在待澄清数字/术语对应：表2合计1340与四次340/正文1360不符；第12页正文0.818称mAP而表4同值为precision。本轮不要转抄这些数值到教材。
- 图像上的井丘/框不直接证明地下水道当时可用，框大小也只是维护的间接指标。
- 1974—2019年文化景观变化不能写成AI给古代遗存定年；社会解释依赖田野、历史和民族志背景。

**教材用途：** 适合后续一次专门、克制的中国景观案例修订，连结第1章四层证据与第4章观测条件；本轮可先记录于文献矩阵，避免与Comer空间验证段重复扩展。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1007%2Fs10816-026-09787-z)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。
- [核查来源2](https://link.springer.com/article/10.1007/s10816-026-09787-z)：出版社题录及摘要核对；在线2026-04-23，33:48。具体方法和局限核读上传PDF。

### P71

Steven A. Wernke; Parker Van Valkenburgh; James Zimmer-Dauphinee; Bethany Whitlock; Giles Spence Morrow; Ryan Smith; Douglas Smit; Grecia Roque Ortega; Kevin Ricci Jara; Daniel Plekhov; Gabriela Oré Menéndez; Scotti Norman; Giancarlo Marcone; Manuel Mamani Calloapaza; Lauren Kohut; Carla Hernández Garavito; Sofia Chacaltana-Cortez; Elizabeth Arkush. 2024. “Large-scale, collaborative imagery survey in archaeology: the Geospatial Platform for Andean Culture, History and Archaeology (GeoPACHA).” *Antiquity*. 98(397):155–171。 DOI：[10.15184/aqy.2023.177](https://doi.org/10.15184/aqy.2023.177)。

**附件：** `Wernke 2024 Large-scale, collaborative imagery survey in archaeology.pdf`；17页；SHA-256：`104c190012f00cd963232588da5fdbda985ce655602e5c38f14308acb3b546b5`。

**日期与版本：** 在线日期：2023-12-18；卷期日期：2024-2。

**研究类型与本轮安排：** 平台与实证调查综述：GeoPACHA人工协作、标准化记录；AI扩展另文/未来。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,2,6,7,8,10,11,12,13页；全部页已提取供检索，但不将自动提取等同逐页通读。 原页图像复核：PDF第8页。

**原文定位：**

- PDF2／印刷156页：历史记录与研究机会偏差
- PDF6–8／印刷160–162页：共同字段、可扩展结构、两级复核、locus定义
- PDF13／印刷167页：不完整普查与AI下一阶段

**可支持的论点：**

- 共同数据结构与区域专题字段结合、两级人工复核，使多个项目记录能够在明确条件下整合。

**限制与解释边界：**

- locus以相距100米等登记规则界定，不等于无争议的古代聚落单位。
- 不同项目只记录某些类型或所有可见类型，数据库空白不能一律当成无遗存。
- 可见分布可能是历时叠加而非同一时期聚落；覆盖大不等于完整普查。
- 本文平台调查主要人工完成，不能以全文总计冒充CNN发现量；与P75数据库时期/范围不同，数字不混用。

**教材用途：** 第3章标准化和完整性判断的备用；若已有充分讨论，保留参考资源即可。

**文件名／版本问题：** 正式刊年2024，先行在线2023-12-18。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.15184%2Faqy.2023.177)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。
- [核查来源2](https://www.cambridge.org/core/journals/antiquity/article/largescale-collaborative-imagery-survey-in-archaeology-the-geospatial-platform-for-andean-culture-history-and-archaeology-geopacha/EE49A1159422C7EA5B223B56147A2E80)：出版社原文HTML已打开；书目与上传PDF相符

### P72

Piotr Wroniecki; Mirosław Furmanek; Włodzimierz Rączkowski. 2023. “Revealing the extent of Neolithic rondel enclosures in Lower Silesia using non-invasive prospection.” *Antiquity*. 97(395):1100–1118。 DOI：[10.15184/aqy.2023.24](https://doi.org/10.15184/aqy.2023.24)。

**附件：** `Wroniecki 2023 Revealing the extent of Neolithic rondel enclosures in Lower Silesia using non-invasive prospection.pdf`；19页；SHA-256：`4ef6bece425188d642cfb45cb382e5b1ab857a2da3dfadcdf2b964a53baa31f0`。

**日期与版本：** 在线日期：2023-10-11；卷期日期：2023-10。

**研究类型与本轮安排：** 实证研究：航拍、LiDAR、磁法等非侵入式综合勘探；非直接ML实验。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,4,13,14,15,16页；全部页已提取供检索，但不将自动提取等同逐页通读。

**原文定位：**

- PDF4／印刷1103页：综合调查方法与八处新环壕
- PDF13–14／印刷1112–1113页：地表采集与遥感的不同可见性
- PDF15–16／印刷1114–1115页：同期性限制及原有外围地区解释变化

**可支持的论点：**

- 缺少地表散布物导致既有步行调查未记录的一类环壕，通过多种遥感/地球物理方法得到新记录，改变旧有分布认识。

**限制与解释边界：**

- 遥感可见性受作物、天气和拍摄时机影响，当前分布仍非完整总体。
- 空间邻近和类型相似不能证明同时使用，需地层和绝对年代。
- 文中讨论AI潜力与引述别人的应用，不等于本研究用AI发现八处环壕。

**教材用途：** 第3章未观察到不等于不存在的非AI对照储备；本轮以P75聚焦即可。

**文件名／版本问题：** 未发现影响辨识的文件名问题。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.15184%2Faqy.2023.24)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。

### P75

James Zimmer-Dauphinee; Parker VanValkenburgh; Steven A. Wernke. 2024. “Eyes of the machine: AI-assisted satellite archaeological survey in the Andes.” *Antiquity*. 98(397):245–259。 DOI：[10.15184/aqy.2023.175](https://doi.org/10.15184/aqy.2023.175)。

**附件：** `Zimmer-Dauphinee 2024 Eyes of the machine.pdf`；15页；SHA-256：`0d3ab00dc8c83c7a4d186cad72937e26edb7e5cd00bd16b95f7d656a64588f33`。

**日期与版本：** 在线日期：2023-12-18；卷期日期：2024-2。

**研究类型与本轮安排：** 实证研究：ResNet50卫星影像分类与独立人工影像调查比较。本轮采用：第4章4.6短案例及章末书目。

**阅读范围：** 上传PDF正文第1–12页（印刷245–256页）已阅读；文后参考文献未逐条追查。 原页图像复核：PDF第9,10页。

**原文定位：**

- PDF5–6／印刷249–250页：目标定义、400米内位置成组后划分80/10/10
- PDF7–9／印刷251–253页：独立人工记录、匹配单元/100米容差、不可见位置处理
- PDF10–12／印刷254–256页：互补遗漏、误报及人机协作展望

**可支持的论点：**

- 两套独立完成的影像调查互相比对，模型提示中经回看影像识别出人工调查遗漏的相关遗存，同时有现代结构及自然地貌误报。
- 评价参照须说明识别目标、空间匹配单位与影像可见性；人工记录也有遗漏。

**限制与解释边界：**

- 复核主要为重新看影像，不是每处地点已进行田野确认、断代或功能判定。
- 两种调查共同遗漏的位置仍可能存在；合并清单不是整个景观的完整真值。
- 文中人工误报不足1%为作者预期，而非独立地面测量值；疲劳是解释性假说。
- 递归人机协作是下一阶段建议，本研究主要检验两套独立调查的互补。
- 印刷253页报告453共同位置与315新位置，合计768，而文字与图4给766；该口径差异未消解，正文建议避开精确合计及基于它的习题。

**教材用途：** 本轮在第4章4.6增加短段，以252—254页说明人工影像参照与模型预测均需核验，以及影像复核与田野确认的区别；不在第3章重复增例。

**文件名／版本问题：** 正式刊年2024，先行在线2023-12-18。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.15184%2Faqy.2023.175)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。
- [核查来源2](https://www.cambridge.org/core/journals/antiquity/article/eyes-of-the-machine-aiassisted-satellite-archaeological-survey-in-the-andes/E0E17B1CFDEFD877933BFA0C0A71BED0)：出版社原文HTML已打开；书目与上传PDF相符

## 2. 器物研究与分类评价

### P08

Jarosław Bodzek; Wojciech Ostrowski; Łukasz Wilk; Paulina Zachar; Barbara Zając. 2025. “The Nietulisko Małe Hoard in the light of modern documentation methods.” *Antiquity 99(406)*. e37，文内页1–7。 DOI：[10.15184/aqy.2025.42](https://doi.org/10.15184/aqy.2025.42)。

**附件：** `Bodzek 2025 The Nietulisko Małe Hoard in the light of modern documentation methods.pdf`；7页；SHA-256：`e72d10100b5905fcf6ae4b73b99da18237cfc913fb96baf440d1d2720b02c5e2`。

**日期与版本：** 在线日期：2025-03-17；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** Antiquity Project Gallery：窖藏钱币的RTI记录与SAM分割流程。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性原文核读：PDF第1—2页及第6页结论，未评估每张图像或运行分割。

**原文定位：**

- 印刷／文内2页；PDF第2页；RTI / SAM流程；原PDF文本核读
- 印刷／文内6页；PDF第6页；结论及后续数据库计划；原PDF文本核读

**可支持的论点：**

- 同一钱币在不同照明条件下的图像分割结果可以不同，研究使用RTI生成的不同照明视图辅助分割。
- 数字记录可改进大宗钱币资料的处理和比较。

**限制与解释边界：**

- 图像分割不等于钱币图像、文字或历史含义的识别。
- 自然语言自动描述和更大范围公共数据库整合在结论中属于后续计划，不能表述为已经完成。

**教材用途：** 可用作第3章“图像为何是条件化记录”的配套阅读；正文不需要增加专门钱币段落。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.15184%2Faqy.2025.42)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。

### P12

Briggs Buchanan; Marcus J. Hamilton; Robert S. Walker. 2026. “A New Method for Classifying Dart and Arrow Projectile Points.” *American Antiquity 91(1)*. 168–182。 DOI：[10.1017/aaq.2025.10109](https://doi.org/10.1017/aaq.2025.10109)。

**附件：** `Buchanan 2026 Genetic relatedness, social status and cemetery organisation.pdf`；15页；SHA-256：`2dba34915433f69fa56a6af7f4134831a74d097ae523b0a3eacb444dddadbe2b`。

**日期与版本：** 在线日期：2025-10-27；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** 以已知投矛/箭标本为参照的功能分类：elastic net变量选择与带平滑样条的贝叶斯logistic模型。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性原文核读：PDF第1—2页、完整第4页方法、第10—11页结论讨论；未检查补充数据或重跑模型。

**原文定位：**

- 印刷／文内171页；PDF第4页；Developing a New Model；原PDF文本核读
- 印刷／文内177页；PDF第10页；分类阈值及比较；原PDF文本核读
- 印刷／文内178页；PDF第11页；局限及后续验证；原PDF文本核读

**可支持的论点：**

- 使用已知装柄标本建立器形到功能类别的概率模型，变量选择、类别比例与分类阈值均属于模型设计。
- 作者明确说明模型判别改变并不自动证明较旧模型更准确，仍需使用痕迹、残留物等独立资料。

**限制与解释边界：**

- 训练资料限定于北美已知标本，不能直接外推所有地区、时代和器形。
- 形态类别与功能不是必然一一对应；相同标本材料上的交叉验证不同于对新地区的验证。

**教材用途：** 未来可作为第4章泛化范围和独立证据的紧凑实例；本轮不再堆叠分类成绩。

**文件名／版本问题：** 上传文件题名误写为“Genetic relatedness, social status and cemetery organisation”；原PDF实际是“A New Method for Classifying Dart and Arrow Projectile Points”，与P01/P40不同。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1017%2Faaq.2025.10109)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。

### P20

Walter Crist; Éric Piette; Karen Jeneson; Dennis J.N.J. Soemers; Matthew Stephenson; Luk van Goor; Cameron Browne. 2026. “Ludus Coriovalli: using artificial intelligence-driven simulations to identify rules for an ancient board game.” *Antiquity 100(409)*. 111–126。 DOI：[10.15184/aqy.2025.10264](https://doi.org/10.15184/aqy.2025.10264)。

**附件：** `Crist 2026 Ludus Coriovalli.pdf`；16页；SHA-256：`d918d32c74d0e1f5162510a80ae8e5d1acb00d4df9dc2b9e50b89ff125b5cd2c`。

**日期与版本：** 在线日期：2026-02-11；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** 实物磨损分析、三维/显微记录与Ludii Alpha-Beta智能体对弈模拟结合，比较古代棋盘候选规则；不是深度学习从磨损图直接学习规则。本轮采用：第1章1.5短案例及章末书目。

**阅读范围：** 正文相关段落选择性核读111—123页，重点113—116及119—122；原PDF111、113、115、116、119、122页已目视核验；出版社全文页核对题录及相应方法/讨论。未核读全部补充材料、未运行模拟。

**原文定位：**

- 印刷／文内111页；PDF第1页；题名、作者、卷期页及摘要；原PDF文本及页面目视
- 印刷／文内113页；PDF第3页；The object / Possible interpretations；原PDF文本及页面目视
- 印刷／文内115页；PDF第5页；Implementation：候选规则来源；原PDF文本及页面目视
- 印刷／文内116页；PDF第6页；Implementation：Alpha-Beta对弈；原PDF文本及页面目视
- 印刷／文内119页；PDF第9页；边使用频率与磨损模式的筛选条件；原PDF文本及页面目视
- 印刷／文内122页；PDF第12页；Discussion：其他功能、其他规则与人类行为；原PDF文本及页面目视

**页图核验补记：** PDF第1、3、5、6、9、12页已目视核验。

**可支持的论点：**

- 研究先依据实物磨损与显微、三维记录提出约束，再将候选规则的模拟行棋分布与痕迹比较。
- 所测试的是来自已记录欧洲传统游戏的规则组合，采用Alpha-Beta智能体对弈；不能称为深度学习自动破解。
- 多个配置与痕迹相符，这支持棋盘功能和某类规则的可能性，但不能唯一复原实际古代玩法。

**限制与解释边界：**

- 馆藏档案仅记发现于Heerlen，其他出土背景不详；晚期罗马再利用属于论证中的推测，不能当作可靠发掘层位。
- 研究没有排除所有其他功能或所有未测试的规则；模拟最优落子与人在实际社交游戏中的行为可能不同。
- 候选规则的地区和时代来源约束了搜索范围。

**教材用途：** 本轮在第1章1.5以短例说明模拟与考古解释的关系，不增主节。突出“磨损记录—明确候选规则—模拟比较—保留多种解释”，不需要模型分数或技术名词堆叠。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.15184%2Faqy.2025.10264)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。
- [核查来源2](https://www.cambridge.org/core/journals/antiquity/article/ludus-coriovalli-using-artificial-intelligencedriven-simulations-to-identify-rules-for-an-ancient-board-game/E5644BD43F8A5DC86DD1183A3E645ED9)：出版社题录及全文相关方法/讨论核对；在线2026-02-11，100(409):111–126。

### P26

Michael Greenacre; Jonathan R. Wood. 2024. “A comprehensive workflow for compositional data analysis in archaeometry, with code in R.” *Archaeological and Anthropological Sciences 16(10)*. 文章171，文内页1–22。 DOI：[10.1007/s12520-024-02070-w](https://doi.org/10.1007/s12520-024-02070-w)。

**附件：** `Greenacre 2024 A comprehensive workflow for compositional data analysis in archaeometry.pdf`；22页；SHA-256：`bc3eadee91dd7823465b4b33ec8c0f99b1c1c8b50447d40ba9a738f1cf65bef0`。

**日期与版本：** 在线日期：2024-09-27；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** 考古化学成分数据分析方法流程及R代码，以商周青铜器目录成分资料展示转换、探索及分类。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性原文核读：第1—4、8、17—20页相关方法/结果/讨论；第4及18页已目视核验；出版社题录、摘要及补充文件入口核对。未下载或运行补充R代码。

**原文定位：**

- 印刷／文内2页；PDF第2页；成分数据与观测元素的相对性；原PDF文本核读
- 印刷／文内4页；PDF第4页；Bronzes数据、低于检出限值及异常值；原PDF文本及页面目视
- 印刷／文内17页；PDF第17页；Cross-validation；原PDF文本核读
- 印刷／文内18页；PDF第18页；Table 7及Random forests；原PDF文本及页面目视
- 印刷／文内19页；PDF第19页；年代标签及成分重叠；原PDF文本核读
- 印刷／文内20页；PDF第20页；Conclusions；原PDF文本核读

**页图核验补记：** PDF第4、18页已目视核验。

**可支持的论点：**

- 成分测量的相对性、选取元素、低于检出限与未测量字段的处理会改变可计算资料，不能把目录数字直接等同于完整器物成分。
- 295件器物贡献362次分析，故一行测量并不必然等于一件独立器物。
- 作者区分全资料拟合、训练集交叉验证与留出测试表现，并承认类型学年代标签和材料混合等因素限制预测。

**限制与解释边界：**

- 正文第17页说明按年代分层随机选择分析记录，未明确报告按器物分组留出；在核查代码之前，只能记录独立性待核，不能断言已发生泄漏。
- 表7的随机森林测试成绩78.3%不等于跨收藏、跨测量程序的青铜器独立断代验证。
- 下检出限的替代值是分析决策，不是证明元素为零；不能将本文方案写成普遍数据清洗规则。

**教材用途：** 可支持第3章一器多测、缺失语义及第4章标签/划分；当前为避免引入成分几何等新概念，优先保留为R方法参考资源与后续案例。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1007%2Fs12520-024-02070-w)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。
- [核查来源2](https://link.springer.com/article/10.1007/s12520-024-02070-w)：出版社题录、摘要与补充材料入口核对；未运行补充R代码。

### P30

Trevor L. Keevil; Emily R. Orlikoff; Jay Reti; Michael C. Pante. 2026. “When stone meets bone: characteristics of bone surface modifications made by Oldowan and Acheulean stone tool forms.” *Archaeological and Anthropological Sciences 18(9)*. 文章187，文内页1–15。 DOI：[10.1007/s12520-026-02547-w](https://doi.org/10.1007/s12520-026-02547-w)。

**附件：** `Keevil 2026 When stone meets bone.pdf`；15页；SHA-256：`93f181eebb69e254ee821c005e1ca77e0e039d3885ff008b4d5b3ad61367c6df`。

**日期与版本：** 在线日期：2026-08-20；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** 控制条件下的石器切割实验、骨表面形态记录与判别分析，并应用于少量古骨切痕。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性原文核读：第1页摘要、引言开头、第12页结论/局限相关段落。

**原文定位：**

- 印刷／文内1页；PDF第1页；摘要；原PDF文本核读
- 印刷／文内12页；PDF第12页；考古切痕投影与实验局限；原PDF文本核读

**可支持的论点：**

- 已知石器形态制造的实验切痕可以提供参照，但分类不是无误的，实际考古骨表面仍需结合痕迹形成过程。

**限制与解释边界：**

- 切割实验控制了力、角度等条件，真实屠宰行为更加多样。
- 少量古骨切痕的分类不能代表整个遗址或时期的工具使用，更不能把约65%的实验分类成绩写成确定识别。

**教材用途：** 后续功能分析或第4章实验到考古材料的外推案例；本轮不加入正文。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1007%2Fs12520-026-02547-w)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。

### P47

Riley C.W. O’Neill; Katrina Yezzi-Woodley; Jeff Calder; Peter J. Olver. 2026. “En masse scanning and semi-automated surfacing of small objects using micro-CT.” *Journal of Archaeological Science 195*. 文章106706，文内页1–13。 DOI：[10.1016/j.jas.2026.106706](https://doi.org/10.1016/j.jas.2026.106706)。

**附件：** `O'Neill 2026 En masse scanning and semi-automated surfacing of small objects using micro-CT.pdf`；13页；SHA-256：`eb34f7248de13b3be1c250d7f7d65c6c16ce88d04d94bc6099b6955d4cae1ee0`。

**日期与版本：** 在线日期：2026-10-06；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** 大批量micro-CT扫描与半自动表面提取工作流程，强调小物件身份对应和阈值选择。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性原文核读：第1—2页以及11—12页讨论相关段落；未使用代码/扫描数据。

**原文定位：**

- 印刷／文内1页；PDF第1页；摘要；原PDF文本核读
- 印刷／文内11页；PDF第11页；阈值、CT值与表面生成；原PDF文本核读
- 印刷／文内12页；PDF第12页；物件对应、打包及后续应用；原PDF文本核读

**可支持的论点：**

- 扫描体积、分割阈值和表面模型是不同的数据阶段，阈值会影响薄边等形态细节。
- 批量流程仍需保持实物与数字对象的稳定身份对应。

**限制与解释边界：**

- 文中micro-CT灰度未校准为通用Hounsfield值，不能把一个阈值视为跨扫描的物性量。
- 大规模和半自动处理不等于无人工判断，更不证明样本代表性。

**教材用途：** 适合第3章对象编号、数字表示及变换记录的配套阅读；本轮正文已有相应原则。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1016%2Fj.jas.2026.106706)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。

### P48

H.A. Orengo; I. Berganzo-Besga; J. Esmoris; F. Lumbreras; P. Aliende; M. Wallace; A. Livarda. 2026. “High-performance 3D morphometrics via deep learning and tabular foundation models: a case study on complex cereal grain classification.” *Journal of Archaeological Science 191*. 文章106607，文内页1–14。 DOI：[10.1016/j.jas.2026.106607](https://doi.org/10.1016/j.jas.2026.106607)。

**附件：** `Orengo 2026 High-performance 3D morphometrics via deep learning and tabular foundation models.pdf`；14页；SHA-256：`582d34790f46e7764715492e673865283b58220fa0ba989b8513530cd7a827ef`。

**日期与版本：** 在线日期：2026-05-28；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** 复杂大麦籽粒3D形态分类比较：球谐描述、MLP/TabPFN及MeshCNN等算法。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性原文核读：第1—2、7、12—13页相关方法和讨论；没有重跑分类或审计训练数据。

**原文定位：**

- 印刷／文内7页；PDF第7页；划分及模型评价设计；原PDF文本核读
- 印刷／文内12页；PDF第12页；模型任务及平衡准确度；原PDF文本核读
- 印刷／文内13页；PDF第13页；实验材料与后续考古资料集；原PDF文本核读

**可支持的论点：**

- 同一复杂形态任务可用不同数字表示和分类器比较；算法效果需要结合具体任务及评价设计理解。

**限制与解释边界：**

- 数据为实验参照籽粒，建立考古训练集仍是后续方向；不能把成绩改写为古代炭化谷粒的普遍识别率。
- MeshCNN的评价受计算资源限制，模型比较并非所有环节完全同条件；不同任务及平衡准确度不可混成一个通用分数。

**教材用途：** 适合后续器物/植物形态识别教学；Part I不增加模型名称和复杂特征计算。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1016%2Fj.jas.2026.106607)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。

### P55

Monica N. Ramsey; Melanie Pugliese; Lachlan Kyle-Robinson; Iban Berganzo-Besga; Rebecca Roberts; Jennifer Bates; Francesca D’Agostini; Zachary C. Dunseth; Thomas C. Hart; Emma Jenkins; Carolina Jiménez-Arteaga; Celine Kerfant; Marco Madella; Sigrid Osborne; Robert Power; Abel Ruiz-Giralt; Philippa Ryan. 2026. “Experts against automation? Comparing artificial intelligence and human identifications of multi-cell cereal husk phytoliths.” *Journal of Archaeological Science: Reports 73*. 文章号 105873；内部页码 1–12。 DOI：[10.1016/j.jasrep.2026.105873](https://doi.org/10.1016/j.jasrep.2026.105873)。

**附件：** `Ramsey 2026 Experts against automation.pdf`；12页；SHA-256：`6dfb8bef394eefa3bc6609fd20c9c3bca53eae396a07ab83ecd97b6e17b6ac05`。

**研究类型与本轮安排：** 考古植物学图像分类的模型—专家比较实验。本轮采用：第4章4.6短案例及章末书目。

**阅读范围：** 重点原文阅读：PDF 1–7、10–12 页；方法、结果和局限均已读，不声称复现数据或通读全部补充材料。原文第 2、5、7、11 页已作视觉核对。

**原文定位：**

- 原文第 2 页：现代 clean 参照材料；作者明确说明模型尚非 archaeology ready。
- 原文第 2–5 页，§2.1：378 张原始参照图像、VGG-19 工作流程和既有测试数据。
- 原文第 5 页，§§2.2–2.3：18 张调查图像的选择方式、在线调查及专家观察条件。
- 原文第 6–7 页，§3：本次图像的模型结果、专家平均结果与重复植硅体图像问题。
- 原文第 11 页，Discussion：44% 不代表专家日常研究准确率；调焦、重定向、放大及拒绝辨识的差别。

**可支持的论点：**

- 该在线比较使用 18 张现代小麦、大麦和燕麦属参照植硅体图像，每属 6 张；本次图像中模型全部分类正确，专家平均正确率为 44%。
- 调查图像从既有测试图像中按手工形态清晰度、模型热图关注和所谓随机控制等准则挑选；Triticum 的 O、P 两图经作者承认来自同一植硅体的不同裁剪。
- 作者在第 2 页限定模型训练于现代较洁净材料，在第 11 页明确真实考古工作中专家可调焦、重新观察或拒绝辨认。

**限制与解释边界：**

- 18 张选择后的图像不是考古植硅体的代表性随机样本；两图属于同一个体，不能写成 18 个完全独立样本。
- 静态线上图像与专家实际显微工作条件不同，比较并不等同完整考古鉴定工作流程的胜负。
- 此前研究的 93.68% 属于另一测试材料规模，不能与本次 18 图的 100% 合并。
- 论文公开了数据和代码入口，但本轮未下载运行，不能宣称复现实验；讨论中的未来应用不是已验证的考古成果。
- 不能把模型属级分类输出直接当作古代种植、食物加工或社会行为的历史解释。

**教材用途：** 本轮在第4章4.6增加短段，说明比较模型与人工时应检查测试图像的来源、独立性和观察条件；保留现代参照材料与考古材料的差异，不新增小节。

**文件名／版本问题：** 未发现实质性文件名错误；著录以原文题名页为准。

**独立书目或网站核查：**

- [核查来源1](https://www.sciencedirect.com/science/article/pii/S2352409X26003081)：出版者原始文章检索记录核对题名、17 名作者、Journal of Archaeological Science: Reports 73、105873、DOI 和 2026 年；原文方法来自用户上传 PDF。
- [核查来源2](https://eprints.bournemouth.ac.uk/42116/)：作者所在大学的机构库记录核对完整作者名单及正式出版 PDF；未替代上传原文的页级阅读。
- [核查来源3](https://api.crossref.org/works/10.1016%2Fj.jasrep.2026.105873)：已读取父任务取得的 Crossref 原始记录，逐项核对 DOI 与本 PDF；属于出版社登记元数据，不能替代原文方法或结果。

### P62

Paolo Sferrazza. 2025. “Archaeological and Experimental Lithic Microwear Classification Through 2D Textural Analysis and Machine Learning.” *Journal of Archaeological Method and Theory 32(1)*. 文章31，文内页1–41。 DOI：[10.1007/s10816-025-09701-z](https://doi.org/10.1007/s10816-025-09701-z)。

**附件：** `Sferrazza 2025 Archaeological and Experimental Lithic Microwear Classification.pdf`；41页；SHA-256：`6dd11f5cec3ebbbb59437ee9a5339906918658b0559003bfc4ac789c5379f92a`。

**日期与版本：** 在线日期：2025-02-15；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** 实验与考古石器微磨光的二维纹理量化、机器学习/神经网络比较与分类。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性原文核读：题名/摘要、引言及27、30—31、33页相关结果/限制；未核读全部41页或复跑大量组合。

**原文定位：**

- 印刷／文内27页；PDF第27页；分类混淆与小样本；原PDF文本核读
- 印刷／文内30页；PDF第30页；Conclusions：方法比较与80%成绩条件；原PDF文本核读
- 印刷／文内33页；PDF第33页；保存及训练资料限制；原PDF文本核读

**可支持的论点：**

- 不同接触材料及保存条件下的微磨光并非同等容易区分；总体分类成绩需要结合错类和参照材料质量。

**限制与解释边界：**

- 80%是所比较组合中的最佳结果，并不是所有考古微磨光都具有该识别率。
- 小样本、轻微埋藏后改变的考古资料与有限原料范围限制泛化；还应核查同器物图像是否分组留出，现阶段不能断言存在泄漏。

**教材用途：** 未来功能研究或第4章分类混淆的阅读案例；当前不添加额外神经网络架构说明。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1007%2Fs10816-025-09701-z)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。

### P67

Luisa Vetter-Parodi; Lucía Watson; Andrew J. Nelson. 2025. “The Hidden Treasures: The Use of Computed Tomography to Study Metal Objects in Funerary Bundles from the Central Coast of Peru.” *Latin American Antiquity*. 36(3):792–807。 DOI：[10.1017/laq.2025.6](https://doi.org/10.1017/laq.2025.6)。

**附件：** `Vetter-Parodi 2025 the hidden treasures.pdf`；16页；SHA-256：`609b8ba463530f95acefbe440ccc5fe945205b850d5ece5fcdaf4b6cdabcc197`。

**日期与版本：** 在线日期：2025-07-08；卷期日期：2025-9。

**研究类型与本轮安排：** 实证研究：CT与阈值分割研究葬包金属；非ML实验。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,3,4,13页；全部页已提取供检索，但不将自动提取等同逐页通读。

**原文定位：**

- PDF3–4／印刷794–795页：85葬包、26有金属、旧情境流失与CT参数
- PDF4／印刷795页：阈值分割、查找表伪彩不是物体实际颜色
- PDF13／印刷804页：不能据CT确定金属/合金种类

**可支持的论点：**

- CT在保持葬包完整的情况下记录金属器位置和形态，并与个体生物考古信息结合。

**限制与解释边界：**

- 不同扫描仪、参数、层厚及出土情境资料损失限制直接比较。
- 数字着色不是实际材质颜色；CT密度不能在本文直接确定合金。
- 未使用机器学习的证据，不因软件含分割功能便归类AI识别。

**教材用途：** 第1/3章数字表征与AI区别的储备，可用于防止把所有数字化技术等同AI。

**文件名／版本问题：** 未发现影响辨识的文件名问题。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1017%2Flaq.2025.6)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。

### P70

Ruohan Wang; Yuyang Tian; Long Wang; Guilin Zhang; Hongen Jiang. 2026. “Phenotypic evolution of broomcorn millet (Panicum miliaceum) in ancient Turpan, Xinjiang, China.” *Journal of Archaeological Science 195*. 文章106710，文内页1–11。 DOI：[10.1016/j.jas.2026.106710](https://doi.org/10.1016/j.jas.2026.106710)。

**附件：** `Wang 2026 Phenotypic evolution of broomcorn millet (Panicum miliaceum) in ancient Turpan, Xinjiang, China.pdf`；11页；SHA-256：`893447703018f2031c5ef5ba1e5e80bf52083658d9af85f7a2a868ab5406c474`。

**日期与版本：** 在线日期：2026-09-24；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** 现代栽培/杂草型黍参照形态分类及古代吐鲁番干燥保存籽粒应用，比较LDA、logistic和随机森林。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性原文核读：第1—2、4、7、9—10页相关方法/结果/解释；未分析原始籽粒或代码。

**原文定位：**

- 印刷／文内4页；PDF第4页；预处理、交叉验证及形态类别；原PDF文本核读
- 印刷／文内7页；PDF第7页；现代参照分类结果；原PDF文本核读
- 印刷／文内9页；PDF第9页；古代比例与农作解释；原PDF文本核读
- 印刷／文内10页；PDF第10页；局限及未来aDNA/同位素检验；原PDF文本核读

**可支持的论点：**

- 模型先依据现代参照形态学习，再将古代籽粒归为形态上更接近栽培型或杂草型的候选。
- 农业变化解释还需要出土背景、年代和历史资料，作者提出遗传或同位素后续检验。

**限制与解释边界：**

- 100%/AUC 1描述现代参照交叉验证，不是古代样本标签已知情况下的外部验证。
- 干燥保存资料、三处遗址和排除异常值的选择限制外推；“杂草型相似”不直接证明实际田间杂草身份或管理制度。

**教材用途：** 可加入植物考古参考资源，后续用于第4章现代到古代的迁移说明；本轮避免新添完美准确率叙述。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1016%2Fj.jas.2026.106710)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。

### P73

Wenpeng Xu; Zhitao Chen; Dashun Xiao; Daoyang Ye; Zelin Yang. 2025. “Unveiling maritime trading practices: micro-provenance analysis of Dehua-style porcelain from the Nanhai I shipwreck.” *Antiquity 99(404)*. 517–535。 DOI：[10.15184/aqy.2024.204](https://doi.org/10.15184/aqy.2024.204)。

**附件：** `Xu 2025 Unveiling maritime trading practices.pdf`；19页；SHA-256：`58f4a1bf5aa2730649e6ae446f037c049b9d054c455b350c023f6f9d9cb41d97`。

**日期与版本：** 在线日期：2024-12-06；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** 南海I号德化风格瓷器pXRF微观来源分析，以窑址参照和随机森林分类结合墨书、器类及船舱背景讨论贸易。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性原文核读：517—518、523、527、532页相关方法/结果/解释；未核查全部补充参照测量。

**原文定位：**

- 印刷／文内523页；PDF第7页；有目的取样、参照窑址及仪器校准；原PDF文本核读
- 印刷／文内527页；PDF第11页；随机森林与来源预测；原PDF文本核读
- 印刷／文内532页；PDF第16页；器类、墨书与贸易解释；原PDF文本核读

**可支持的论点：**

- 沉船样本与窑址参照成分之间的模型关系可形成来源候选，再与器类、墨书及装载情况一起讨论贸易。
- 样本为了覆盖器类、墨书和船舱而有目的地选择，作者明确不用于估计总体器类比例。

**限制与解释边界：**

- 99.88%的参照资料交叉验证成绩不是每件沉船器物来源均已得到独立验证。
- 不在参照库中的来源、仪器差异和有目的取样限制结论；商人身份与交易关系不是模型直接输出标签。

**教材用途：** 很适合后续“中国材料—化学数据—分类候选—贸易解释”的一页阅读；当前小幅Part I修订不再增加复杂背景。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.15184%2Faqy.2024.204)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。

## 3. 环境、人群与社会解释

### P01

Ameline Alcouffe; Sylvie Duchesne; Chahrazed Labba; Bayarkhuu Noost; Patrice Gérard; Simon Trixl; Vincent Zvenigorosky; Batshatar Erdene; Christine Keyser; Bertrand Ludes; Alexandre Ribéron; Tsagaan Turbat; Anne Boyer; Eric Crubézy. 2026. “Genetic relatedness, social status and cemetery organisation: the Xiongnu Tamir necropolis, Mongolia.” *Antiquity 100(412)*. 1032–1049。 DOI：[10.15184/aqy.2026.10360](https://doi.org/10.15184/aqy.2026.10360)。

**附件：** `Alcouffe 2026 Genetic relatedness, social status and cemetery organisation.pdf`；18页；SHA-256：`03701ff68cbbfc37c78c326ed6e8cac559c19c974fe8615d15a3960c82327fc8`。

**日期与版本：** 在线日期：2026-05-26；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** 匈奴墓地的多证据实证研究：线性判别、随机森林/SVM/XGBoost、探索聚类及文化系统发生分析。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性原文核读：PDF第1页题名/摘要、第2页引言开头、第8页方法、第16页结论；其他相关页仅检索定位。

**原文定位：**

- 印刷／文内1039页；PDF第8页；Supervised machine-learning algorithms / SHAP / Cultural phylogeny；原PDF文本核读
- 印刷／文内1047页；PDF第16页；结论；原PDF文本核读

**可支持的论点：**

- 把生物亲缘、随葬组合和空间组织作为不同证据共同讨论墓地组织；算法分类不能涵盖亲属关系的全部社会含义。
- 方法页明确47名个体、A/B谱系合并为19人家庭组并与28名无关个体比较；测试了留一法及80/20划分。

**限制与解释边界：**

- 样本小且出自单一墓地，类别合并会改变研究任务；变量贡献与SHAP结果不等于因果解释。
- 作者因本研究的数据性质未采用SMOTE，这是项目选择，不能改写为所有考古研究禁止过采样的通则。
- 文化系统发生树以24号墓为参照根节点，相关年代与编码假设属于解释条件。

**教材用途：** 可支持第1章四层证据链或第3章标签构建；当前正文已有同类概念，不宜另开墓地分析小节。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.15184%2Faqy.2026.10360)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。

### P10

Francesco Breglia; Richard Madgwick; Emily Holt; George Cooper; Marta Dal Corso; Silvia D’Aquino; Federico Polisca; Giorgio Piazzalunga; Cristiano Nicosia. 2027. “Crops in Motion: Strontium Isotope Analysis of Cereal Provenance in a Foraging-Oriented Neolithic Economy.” *Journal of Archaeological Method and Theory 34(1)*. 文章19，文内页1–24。 DOI：[10.1007/s10816-026-09830-z](https://doi.org/10.1007/s10816-026-09830-z)。

**附件：** `Breglia 2026 Crops in Motion.pdf`；24页；SHA-256：`653247051886c7576ec946c658ff8820aae1adcbb84a46e40f10313691840588`。

**日期与版本：** 在线日期：2026-09-08；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** 谷物锶同位素来源分析及本地生物可利用锶基线实测；不是机器学习识别遗址的研究。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性原文核读：PDF第1页、引言开头、第6页基线/方法、第19页结论；另核出版社题录及摘要。

**原文定位：**

- 印刷／文内6页；PDF第6页；Strontium baseline / 方法；原PDF文本核读
- 印刷／文内19页；PDF第19页；Conclusions；原PDF文本核读

**可支持的论点：**

- 大区域同位素基线的资料分布与取样来源并不均一；面向具体遗址的本地参照植物取样有助于判断谷物来源。
- 作者明确仍需扩大植物基线及考古样本，评估更细尺度变异。

**限制与解释边界：**

- 地方基线不是穷尽全部潜在来源的地图，考古谷物样本量有限。
- 不要将文中讨论的机器学习同位素空间预测图写成该项目已训练并验证的AI模型。

**教材用途：** 可支持第4章参照总体与目标材料对应的讨论；不作为本轮新增正文案例。

**文件名／版本问题：** 文件名2026对应在线发表/版权年；原PDF卷年及出版社正式卷号为2027，34:19。应同时保存两个日期，不把二者当成不同论文。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1007%2Fs10816-026-09830-z)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。
- [核查来源2](https://link.springer.com/article/10.1007/s10816-026-09830-z)：出版社题录、摘要核对；2026-09-08在线、34:19 (2027)。具体论断来自上传PDF选择性核读。

### P14

Döbereiner Chala-Aldana; Gonzalo Aranda Jiménez; Paula Becerra Fuello; Leopoldo Pena; Marta Díaz-Zorita Bonilla. 2026. “Isoscape modelling choices and their implications for archaeological mobility interpretations: A comparative 87Sr/86Sr study from southeastern Iberia.” *Journal of Archaeological Science*. 192:106639，文内1–22页。 DOI：[10.1016/j.jas.2026.106639](https://doi.org/10.1016/j.jas.2026.106639)。

**附件：** `Chala-Aldana 2026 Isoscape modelling choices and their implications for archaeological mobility interpretations.pdf`；22页；SHA-256：`7b99472a63f8c2fb4a513264346653755e40d165544514eba9b0b15b1f16db16`。

**日期与版本：** 在线日期：2026-06-26；卷期日期：2026-8。

**研究类型与本轮安排：** 比较方法实证：锶同位素环境基线、克里金和树集成模型。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,12,14,17,20页；全部页已提取供检索，但不将自动提取等同逐页通读。

**原文定位：**

- PDF/文内12页§2.5.1：七项建模选择共同变化的比较设计
- PDF/文内14、17页：验证设计及不确定性
- PDF/文内20页§4.4：不确定性分量不同、环境基线不能自行界定本地/非本地

**可支持的论点：**

- 同一区域的不同样本、尺度和建模选择会改变锶同位素预测面，影响古代移动的解释条件。

**限制与解释边界：**

- 模型、样本类型、样本密度、尺度及验证方案同时变化，不是仅比较算法的控制实验。
- 克里金预测标准误与树间标准差描述不同不确定性，不能因单位相同便直接当成等价误差。
- 内部拟合或普通交叉验证与空间分块结果不可不加说明并列排名；高分辨率不保证高考古解释确定性。

**教材用途：** 第4章模型选择与不确定性的储备；主题较专门，不建议本轮扩写同位素教材。

**文件名／版本问题：** 未发现影响辨识的文件名问题。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1016%2Fj.jas.2026.106639)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。

### P32

Samuel Kertés; Alžběta Danielisová; Daniel Bursák; Lukáš Ackerman. 2027. “Modelling Local Strontium Isotope Baselines from Human Isotopic Data Using Machine Learning: Implications for Past Mobility Studies.” *Journal of Archaeological Method and Theory*. 34(1):18，文内1–34页。 DOI：[10.1007/s10816-026-09827-8](https://doi.org/10.1007/s10816-026-09827-8)。

**附件：** `Kertes 2027 Modelling Local Strontium Isotope Baselines from Human Isotopic Data Using Machine Learning.pdf`；34页；SHA-256：`fb5aacc0648b1846a9f5b0f9afcaa80cee4c8a6e6550744794b1eaa1131fbc56`。

**日期与版本：** 在线日期：2026-09-03；卷期日期：2027-3。

**研究类型与本轮安排：** 方法及实证研究：MobSr，锶同位素分类与贝叶斯集成。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,8,10,13,19,20页；全部页已提取供检索，但不将自动提取等同逐页通读。

**原文定位：**

- PDF/文内8页：本地/非本地先验及分类器相关性的概率问题
- PDF/文内10、13页：按遗址留出，约87%与探索性95%标签一致性
- PDF/文内19–20页：非本地来源未独立核验、定居群体假设与非典型情境

**可支持的论点：**

- MobSr学习既有研究给出的本地/非本地分类，以估计可能的本地锶同位素范围。
- 报告的性能衡量与既有专家分类的一致性，而非已知个人居住史的识别准确率。

**限制与解释边界：**

- 源研究标签本身以锶同位素及基线解释产生，不能把复现同类标签当成独立验证古人迁徙。
- 83:17为训练资料导出的建模先验，不是人类迁徙规律；95%来自排除非典型案例的探索性分析。
- 同位素还受食物来源、土地利用和环境过程影响；定居群体假设不适用于所有墓地或战争遗存。
- 方法页写每次留出五处遗址，不能仅照结果页leave-one-out术语称为逐一留出。

**教材用途：** 第3章标签与历史解释层级的重要备用例证；仅在需要非影像案例时考虑。

**文件名／版本问题：** 文件名2027与正式卷年一致；已于2026-09-03先行在线，不是尚未出版。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1007%2Fs10816-026-09827-8)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。
- [核查来源2](https://link.springer.com/article/10.1007/s10816-026-09827-8)：出版社页面已打开；书目与上传PDF及Crossref相符

### P36

Zhikun Ma; Bingxin Shao; Ziming You; Francesca Monteith; Zhiwei Wan; Jian Ma. 2026. “Holocene niche divergence of wheat and barley in Central and East Eurasia.” *Journal of Archaeological Science*. 192:106619，文内1–17页。 DOI：[10.1016/j.jas.2026.106619](https://doi.org/10.1016/j.jas.2026.106619)。

**附件：** `Ma 2026 Holocene niche divergence of wheat and barley in Central and East Eurasia.pdf`；17页；SHA-256：`c5ee67e9afe517988f609d4a22a87ef330bb44a7d91e2165c3aee1c09ef3a509`。

**日期与版本：** 在线日期：2026-06-19；卷期日期：2026-8。

**研究类型与本轮安排：** 实证研究：植物考古记录、PCA、随机森林和MaxEnt生态位分析。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,4,5,14页；全部页已提取供检索，但不将自动提取等同逐页通读。

**原文定位：**

- PDF/文内4–5页：聚类、PCA、随机森林及MaxEnt分工
- PDF/文内14页§4.5：遗存类型混合、现代河流代理、谷粒存在不必为本地栽培

**可支持的论点：**

- 通过小麦和大麦考古记录与环境变量的比较，提出全新世生态位分化的解释。

**限制与解释边界：**

- 谷物出现可能涉及交换，不能自动推断本地栽培；未统一区分带壳/裸粒大麦。
- 现代河流等是宏观水文代理；变量重要性和部分依赖关系不是因果效应。
- 生态位预测不能自动消除考古发现、保存和发表偏差；不同模型所谓一致性不等于历史解释被独立证实。

**教材用途：** 第4章相关、预测与解释的非影像储备；目前不扩展农业史内容。

**文件名／版本问题：** 未发现影响辨识的文件名问题。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1016%2Fj.jas.2026.106619)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。

### P40

Weston C. McCool; Kenneth B. Vernon; Ishmael D. Medina; Joan Brenner Coltrain; Kurt M. Wilson; Brian F. Codding. 2026. “Drought, Population Pressure, and Inequality Drive Intergroup Conflict in the Precontact North American Southwest.” *American Antiquity 91(1)*. 98–116。 DOI：[10.1017/aaq.2025.10107](https://doi.org/10.1017/aaq.2025.10107)。

**附件：** `McCool 2026 Genetic relatedness, social status and cemetery organisation.pdf`；19页；SHA-256：`12c20cc8c6689006811b00727f13268ae1e774010e4a9f51d576a3f0bd664fe5`。

**日期与版本：** 在线日期：2025-12-03；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** 美洲西南史前聚落研究：防御性地形指标、财富不平等代理、人口及古气候时间序列与重复随机森林分析。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性原文核读：题名/摘要，99页引言开头，102—104、107—108、111页相关方法/讨论；其余页面检索定位。

**原文定位：**

- 印刷／文内104页；PDF第7页；防御性测量；原PDF文本核读
- 印刷／文内107页；PDF第10页；人口年代不确定性与气候重建；原PDF文本核读
- 印刷／文内108页；PDF第11页；Results：随机森林与代理变量；原PDF文本核读
- 印刷／文内111页；PDF第14页；Discussion及其他社会条件；原PDF文本核读

**可支持的论点：**

- 研究中的“冲突”由聚落防御性代理，人群和不平等也通过有条件的考古指标表示。
- 随机森林中变量相互关系需要结合独立考古材料及社会机制讨论。

**限制与解释边界：**

- 标题中的“Drive”不能直接转述成随机森林证明干旱或不平等的单一因果效应。
- 代理变量、年代分布及取样假设限制解释；模型输出并不直接观测战争事件或个体财富。

**教材用途：** 可供第1/4章区分观测、编码与社会解释的后续练习；当前案例所需背景较多，不纳入小幅正文修订。

**文件名／版本问题：** 上传题名误写为“Genetic relatedness, social status and cemetery organisation”；原PDF实际讨论北美西南干旱、人口、不平等与群体冲突，DOI不同于P01和P12。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1017%2Faaq.2025.10107)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。

### P69

L. Waltenberger; K. Rebay-Salisbury; J. Desideri; P. Mitteroecker; M. Spannagl-Steiner; D. Pany-Kucera. 2026. “The invisible evidence of birth: evaluating the relationship between pelvic shape and parity with a pelvic pattern index.” *Archaeological and Anthropological Sciences 18(9)*. 文章180，文内页1–15。 DOI：[10.1007/s12520-026-02533-2](https://doi.org/10.1007/s12520-026-02533-2)。

**附件：** `Waltenberger 2026 The invisible evidence of birth.pdf`；15页；SHA-256：`bbaf50e8d725b1dadf86d2944ddbf0ee250c2aa47da5792e8f9fd8ad7ba9166d`。

**日期与版本：** 在线日期：2026-08-05；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** 骨盆形态与生育史的加权指标及统计关联研究，比较不同骨骼/临床参照样本。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性原文核读：第1—2及第12页讨论相关段落。

**原文定位：**

- 印刷／文内12页；PDF第12页；年龄、群体差异与个体预测限制；原PDF文本核读

**可支持的论点：**

- 群体层面的形态与生育史关系不能直接用于确定个体生育次数；年龄、生活方式和测量方式影响可比性。

**限制与解释边界：**

- 作者明确不能用该指标准确预测个人生育次数，群体间也不能直接进行无条件定量比较。
- CT与实物观察可见程度不同；这不是已经训练并外部验证的深度学习诊断工具。

**教材用途：** 可备作第4章个体预测与群体关系的例子；当前无需加入特殊生物医学背景。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1007%2Fs12520-026-02533-2)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。

## 4. 计算考古的理论、记录与基础设施

### P06

Iban Berganzo-Besga; Hector A. Orengo; Felipe Lumbreras. 2026. “Best practices for the application of computer vision-based machine learning in archaeology.” *Journal of Archaeological Science*. 191:106577，文内1–13页。 DOI：[10.1016/j.jas.2026.106577](https://doi.org/10.1016/j.jas.2026.106577)。

**附件：** `Berganzo-Besga 2026a Best practices for the application of computer vision-based machine learning in archaeology.pdf`；13页；SHA-256：`932d9c328d4809f2d639aebf57b79bdb78c2e718c95b6c9c07f4b80a07a0a460`。

**日期与版本：** 在线日期：2026-05-27；卷期日期：2026-7。

**研究类型与本轮安排：** 方法指南／综合性论述（出版平台归类Research article），并非单一新发现实验。本轮不增加正文，按以下用途保留。

**阅读范围：** 上传PDF正文第1–11页已阅读；文后参考文献未逐条追查。 原页图像复核：PDF第8,9页。

**原文定位：**

- PDF/文内4–5页，§2.4.1：数据定义、标注与先划分后增广
- PDF/文内8页，§2.6.1：最终测试集不参与反复调参
- PDF/文内9页，§2.6.2–2.6.3：联合解释precision/recall；评价低密度背景情形

**可支持的论点：**

- 考古视觉模型评价需区分开发过程与最终测试，并结合精确率、召回率及无目标背景解释性能。

**限制与解释边界：**

- 这是方法建议及既有研究综合，不能作为某个新遗址发现的原始证据。
- 60/20/20划分、80%空图、置信度0.9等为文中情境性建议，不应写成统一规范。
- 随机划分比例本身不保证空间独立；高模型置信度不等于概率已校准。
- 文中对低精确率的价值判断不能替代具体调查成本与研究目标的权衡。

**教材用途：** 若第4章需要补足考古学专门方法引文，可只在既有测试集/precision–recall段末加8–9页引文；不新增一整套指标说明。

**文件名／版本问题：** 未发现影响辨识的文件名问题。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1016%2Fj.jas.2026.106577)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。
- [核查来源2](https://www.sciencedirect.com/science/article/pii/S030544032600107X)：出版社检索结果核实题名/作者/卷号文章号；打开全文页面返回Internal Error，原文证据取自上传PDF

### P13

Mario Casillo; Francesco Colace; Rosario Gaeta; Angelo Lorusso; Michele Pellegrino. 2025. “Artificial Intelligence in Archaeological Site Conservation: Trends, Challenges, and Future Directions.” *Journal of Computer Applications in Archaeology 8(1)*. 224–241。 DOI：[10.5334/jcaa.207](https://doi.org/10.5334/jcaa.207)。

**附件：** `Casillo 2025 Artificial Intelligence in archaeological site conservation- trends, challenges and future directions.pdf`；18页；SHA-256：`6e15732c12318c813992345a07b6686a458948fbebfe0eaab9efd2d7d52227fe`。

**研究类型与本轮安排：** 系统性／文献计量综述。本轮不增加正文，按以下用途保留。

**阅读范围：** 定向原文阅读：PDF 1–4 页及 15 页；检查检索方法、纳入范围和结论。

**原文定位：**

- 原刊 226–227 页（PDF 3–4）：数据库、时间范围、排除标准及筛选流程。
- 原刊 238 页（PDF 15）：结论。

**可支持的论点：**

- 在限定英文、计算机科学文献及 2020 年 1 月至 2024 年 10 月范围内，结合 Scopus、Web of Science 和 IEEE 数据进行综述；358 条初始记录、149 条去重记录、37 篇定性纳入。
- 概括遗址保护中 AI 的数据、协作及持续维护问题。

**限制与解释边界：**

- 综述不是新的遗址发现或统一性能试验。
- 文献的语言、学科、数据库与年代限制影响覆盖范围；表中不同任务的性能不能合成为考古 AI 的一般准确率。

**教材用途：** 作为研究领域概览保留；不据综述中的转引指标增加正文经验性结论。

**文件名／版本问题：** 未发现实质性文件名错误；著录以原文题名页为准。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.5334%2Fjcaa.207)：已读取父任务取得的 Crossref 原始记录，逐项核对 DOI 与本 PDF；属于出版社登记元数据，不能替代原文方法或结果。

### P25

Gabriele Gattiglia. 2025. “Managing Artificial Intelligence in Archeology. An overview.” *Journal of Cultural Heritage 71*. 225–233。 DOI：[10.1016/j.culher.2024.11.020](https://doi.org/10.1016/j.culher.2024.11.020)。

**附件：** `Gattigalia 2025 Managing artificial intelligence in archaeology- an overview.pdf`；9页；SHA-256：`74b0ea31e0b3017affbc193344534df028bc5c8cd6c4c2a522b1579ede5090a4`。

**研究类型与本轮安排：** 理论／方法批判性综述。本轮不增加正文，按以下用途保留。

**阅读范围：** 定向原文阅读：PDF 1、3–6 页；重点为考古数据、分类、透明度与理论问题。

**原文定位：**

- 原刊 228–229 页（PDF 4–5），§4.1：分类、既有数据和元数据。
- 原刊 229–230 页（PDF 5–6）：透明度及推广问题。

**可支持的论点：**

- 论述为计算而简化资料、把暂定类型当作确定标签以及复用既有分类的风险。
- 强调来源、收集过程和修改记录对于考古数据复用的重要性。

**限制与解释边界：**

- 批判性综述不是新开展的统一模型性能实验；转引的案例指标应回查原研究。
- 技术概览中若干生成模型术语表述不够严密，不适合作为 GAN、扩散模型等结构的教材解释来源。
- 2024-12-19 在线发表，正式卷期为 2025 年。

**教材用途：** 可作考古数据与分类的参考阅读；与现有教材概念相近，避免继续堆叠一般性警示。

**文件名／版本问题：** 文件名 Gattigalia 拼写错误，正确姓氏 Gattiglia；原刊题名使用 Archeology。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1016%2Fj.culher.2024.11.020)：已读取父任务取得的 Crossref 原始记录，逐项核对 DOI 与本 PDF；属于出版社登记元数据，不能替代原文方法或结果。

### P31

Tim Kerig; Johanna Hilpert; Steffen Strohm; Daniel Berger; Solène Denis; Estelle Gauthier; Juan F. Gibaja; Nicole Mallet; Michele Massa; Niccoló Mazzucco; Bianca Nessel; Jacques Pelegrin; Pierre Pétrequin; Serena Sabatini; Thomas X. Schumacher; Benjamin Serbe; Toby Wilkinson. 2023. “Interlinking research: the Big Exchange project.” *Antiquity 97(394)*. e22，文内页1–8。 DOI：[10.15184/aqy.2023.78](https://doi.org/10.15184/aqy.2023.78)。

**附件：** `Kerig 2023 Interlinking research- the Big Exchange project.pdf`；8页；SHA-256：`99cbdeb76d55b2f3c5b1ee1348e4f0603a363020596bd5134cc3425a543c2e55`。

**日期与版本：** 在线日期：2023-06-26；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** Antiquity Project Gallery：跨项目原料来源—发现地点资料整合及双模网络研究。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性核读正文第1—7页，重点第2、5—6页；第2页已目视核验；出版社题录/全文页核对。未审计原始数据库或补充资料。

**原文定位：**

- 印刷／文内2页；PDF第2页；双模网络的定义与限制；原PDF文本及页面目视
- 印刷／文内5页；PDF第5页；异质资料与Spondylus分布；原PDF文本核读
- 印刷／文内6页；PDF第6页；保存条件与空间解释；原PDF文本核读

**页图核验补记：** PDF第2页已目视核验。

**可支持的论点：**

- 原料来源与器物发现地点可构成明确含义的两类节点及其联系，跨项目资料整合需要处理来源及记录差异。
- 作者明确说明这类网络不能显示完整经济或社会网络，也不直接记录每一个生产、交换环节。

**限制与解释边界：**

- “原料来源—发现地点”联系不能自动解释为个人交易、路线或全社会交往网络。
- 空间空白既要考虑保存及调查，也要比较不同材料/背景证据，不能一律填成无交流。

**教材用途：** 适合配合Brughmans与Peeples的在线网络资源；第1章已有节点/边表示边界的清楚实例，本轮不再加平行段落。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.15184%2Faqy.2023.78)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。
- [核查来源2](https://www.cambridge.org/core/journals/antiquity/article/interlinking-research-the-big-exchange-project/D7F3E5D94EBE0CE73AE941DF94AD6C2F)：出版社题录及正文相关内容核对；在线2023-06-26，97(394):e22。

### P38

Matthew Magnani; Matthew Douglass; Whittaker Schroder; Jonathan Reeves; David R. Braun. 2020. “The Digital Revolution to Come: Photogrammetry in Archaeological Practice.” *American Antiquity 85(4)*. 737–760。 DOI：[10.1017/aaq.2020.59](https://doi.org/10.1017/aaq.2020.59)。

**附件：** `Maganani 2020 The Digital Revolution to Come.pdf`；24页；SHA-256：`9049c44bc8a408b9c28bc7d64fb976f53ec563aabc7766df8349894b1dc85020`。

**日期与版本：** 在线日期：2020-08-13；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** 摄影测量考古实践的批判性方法综述。本轮不增加正文，按以下用途保留。

**阅读范围：** 初步原文筛读：题名/摘要及引言（737—738页）完整相关段落；其他正文仅检索，未作为具体引证依据。

**原文定位：**

- 印刷／文内737页；PDF第1页；题名、摘要；原PDF文本核读
- 印刷／文内738页；PDF第2页；Introduction；原PDF文本核读

**可支持的论点：**

- 摄影测量的研究价值需要由明确考古问题和分析过程实现，三维展示本身并不等于对过去的解释。

**限制与解释边界：**

- 2020年的综述不能作为2026年全部软件、工作流程或研究普及程度的现状调查。
- 这是方法论评价，不是机器学习性能实验；不能声称所有三维项目都只做展示。

**教材用途：** 可列为数字考古学与三维资料方法阅读，不为第1章已有代理表示讨论再增重复论述。

**文件名／版本问题：** 文件名“Maganani”应为作者姓氏“Magnani”；题名无误。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1017%2Faaq.2020.59)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。

### P42

Manuel Medrano; Ashok Khosla. 2025. “How Can Data Science Contribute to Understanding the Khipu Code?.” *Latin American Antiquity 36(2)*. 497–516。 DOI：[10.1017/laq.2024.5](https://doi.org/10.1017/laq.2024.5)。

**附件：** `Medrano 2025 How Can Data Science Contribute to Understanding the Khipu Code.pdf`；20页；SHA-256：`c52ec0d0e8887719aef9acfd8c5072fc9ce9ea011f13b9a4c48d9bb414f40dc2`。

**日期与版本：** 在线日期：2024-05-06；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** 结绳记录语料的计算搜索、算术结构检验、蒙特卡洛比较及重缀假说。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性原文核读：497—498、511、513—514页相关段落；数据/代码链接仅记录，未复现。

**原文定位：**

- 印刷／文内497页；PDF第1页；摘要；原PDF文本核读
- 印刷／文内511页；PDF第15页；算术结构、Monte Carlo与未来机器学习；原PDF文本核读
- 印刷／文内513页；PDF第17页；Conclusions；原PDF文本核读
- 印刷／文内514页；PDF第18页；Data Availability / Notes；原PDF文本核读

**可支持的论点：**

- 对大规模结绳记录的明确结构进行计算搜索，可提出算术关系及重缀候选，再交由材料和历史证据评估。

**限制与解释边界：**

- 算术关系和数量编码不等于完整语义或历史信息的破译。
- 第511页把机器学习特征工程列为未来方向，不应将本研究改写为深度学习已经破解结绳文字。

**教材用途：** 可扩充铭文/古代记录参考资源，或作为“计算考古不等于机器学习”的对照阅读；当前第1章已含甲骨/铭文段落，不应再铺开新体系。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1017%2Flaq.2024.5)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。

### P44

Colleen Morgan. 2021. “An archaeology of digital things: social, political, polemical.” *Antiquity 95(384)*. 1590–1593。 DOI：[10.15184/aqy.2021.125](https://doi.org/10.15184/aqy.2021.125)。

**附件：** `Morgan 2021 An archaeology of digital things- social, political, polemical.pdf`；4页；SHA-256：`a3f7ae12acae6654fa12bf0832c2f32c6345e229a1cd46b2fd59cd882ffe0772`。

**日期与版本：** 在线日期：2021-09-10；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** Antiquity Debate Article：数字物的社会、政治及考古理论评论。本轮不增加正文，按以下用途保留。

**阅读范围：** 核读四页正文相关段落（1590—1593）；参考文献未逐项复核。

**原文定位：**

- 印刷／文内1590页；PDF第1页；论题；原PDF文本核读
- 印刷／文内1592页；PDF第3页；数字物与Minecraft示例；原PDF文本核读
- 印刷／文内1593页；PDF第4页；论证结尾；原PDF文本核读

**可支持的论点：**

- 数字物也具有物质、社会和政治背景；分析代码只是理解数字对象及其使用实践的一部分。

**限制与解释边界：**

- 作者将儿童参与Minecraft的例子明示为非结构化的偶然观察，不能转述成教育效果实验。
- 理论评论不是经验性能证据或学科统一结论。

**教材用途：** 可为教师提供数字考古概念背景；不把额外哲学术语引入本轮本科正文。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.15184%2Faqy.2021.125)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。

### P46

Lorenzo Nigro. 2026. “Archaeology & Artificial Intelligence.” *Quaderni di Vicino Oriente 18. Roma: Sapienza Università di Roma*. 上传件仅 5 页：封面、题名页、版权页及目录 i–ii；书的章节正文未提供。 DOI：[10.53131/QVO1127-60372026_1](https://doi.org/10.53131/QVO1127-60372026_1)。 ISBN：978-88-98154-30-2。

**附件：** `Nigro 2026 Archaeology and artificial intelligence.pdf`；5页；SHA-256：`70d6340aa1581b114119b4402eaf5a638dbf2e2bf6db9a229bfec718184c8df1`。

**研究类型与本轮安排：** 专著前置页与目录；书目级材料。书目／目录级储备，未取得章节正文。

**阅读范围：** 已检查全部上传的 5 页，并视觉核对封面。只有前置页和目录，未阅读章节正文。

**原文定位：**

- PDF 2：作者、书名、丛书及 Roma 2026。
- PDF 3：ISBN、DOI、2026 年 4 月发行说明。
- PDF 4–5：目录 i–ii。

**可支持的论点：**

- 可以确认这是 Lorenzo Nigro 的 2026 年书籍，ISBN 978-88-98154-30-2，属于 Quaderni di Vicino Oriente 第 18 册。
- 目录说明书中涉及 AI 与考古问题，但目录不能证明任何章节的具体论证或结果。

**限制与解释边界：**

- 上传件没有章节正文；不得标记为已通读全书、已核实章节页码上的论断或已验证实验。

**教材用途：** 作为待补全文的书目资源保留。正文引用必须先获得实际章节，不能以目录替代证据。

**文件名／版本问题：** 文件名可能让人误以为上传了全书，实际只有 5 页前置资料。

**独立书目或网站核查：**

- 核查来源1：本轮书目信息来自上传 PDF 原文；未独立完成出版社网页核验，不标作网页已核实。

### P49

Hector A. Orengo; Iban Berganzo-Besga; Felipe Lumbreras. 2026. “Theory and practice of artificial intelligence in archaeology.” *Journal of Archaeological Science*. 190:106571，文内1–9页。 DOI：[10.1016/j.jas.2026.106571](https://doi.org/10.1016/j.jas.2026.106571)。

**附件：** `Orengo 2026a Theory and practice of artificial intelligence in archaeolog.pdf`；9页；SHA-256：`ff6b0af184dd26f20d98355eb3cbbe92e3aca6957f2c41288b603ebeb35847aa`。

**日期与版本：** 在线日期：2026-04-16；卷期日期：2026-6。

**研究类型与本轮安排：** 理论与方法综合论述（平台Research article）；并非单个考古发现实验。本轮采用：细化第3章3.2及第4章4.7既有引文；不重复添加书目。

**阅读范围：** 上传PDF原文定向阅读：PDF第1,3,4,5,7,8页；全部页已提取供检索，但不将自动提取等同逐页通读。 原页图像复核：PDF第4,7页。

**原文定位：**

- PDF/文内3–4页，§2–3：稀缺/背景、记录和表征的中介性质
- PDF/文内4页：陶片的RGB、纹理代理及传感器/处理条件的外推限制
- PDF/文内7–8页，§6：任务相称评价、外部验证与可解释性边界

**可支持的论点：**

- 训练标签及数值特征是考古对象的选定表征，模型学习的是该表征下的规律。
- 常规指标及可解释性图像不能独立确认新遗迹或历史因果关系，需合适外部证据与具体任务验证。

**限制与解释边界：**

- 理论性综合文章中的具体古代发现需追溯其引用原研究；不能让此文替代全部实证原文。
- 第7节智能体/实体AI讨论含展望，不应改述成考古全流程自主系统已完成。
- 已有教材第3、4章引用，宜补精确页码，避免重复扩充概念。

**教材用途：** 本轮将第3章3.2代理表示定位细化到第3节3—4页；第4章4.7分开引用第2—3节3—4页的资料条件与第6节7—8页的实际用途验证。

**文件名／版本问题：** 未发现影响辨识的文件名问题。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1016%2Fj.jas.2026.106571)：DOI注册元数据已取得（本轮取得）；逐一将DOI与PDF首页对应，并核对题名、作者、刊物、卷期页码及日期。此为书目核验，不是全文核验。
- [核查来源2](https://www.sciencedirect.com/science/article/pii/S0305440326001019)：出版社检索结果核实题名/作者/卷号文章号；打开全文页面返回Internal Error，原文证据取自上传PDF

### P51

Sarah E. Paris; Robert A. Foley. 2027. “Bone Surface Mapping: A New Method for Recording Detailed Human Bone Surface Variation.” *Journal of Archaeological Method and Theory 34(1)*. 文章3，文内页1–23。 DOI：[10.1007/s10816-026-09811-2](https://doi.org/10.1007/s10816-026-09811-2)。

**附件：** `Paris 2026 Bone Surface Mapping.pdf`；23页；SHA-256：`08cc398e1395df6553d235b5955683bf558f5ebd20f6cb2e240f3651d8e717e4`。

**日期与版本：** 在线日期：2026-07-14；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** 人体骨表面变化的标准化二维分面记录方法，含考古案例；机器学习扩展是未来建议。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性原文核读：第1—2及19—20页相关段落；出版社页面核对作者、在线日期、正式卷年及方法概述。

**原文定位：**

- 印刷／文内2页；PDF第2页；Introduction：缺少骨骼与缺少表面变化；原PDF文本核读
- 印刷／文内19页；PDF第19页；Discussion；原PDF文本核读
- 印刷／文内20页；PDF第20页；方法应用与未来方向；原PDF文本核读

**可支持的论点：**

- 比较骨表面变化时，缺少骨骼和已保存骨骼上未见变化必须分开；记录单位及分母需要对应。

**限制与解释边界：**

- 分面是研究者设计的表示，需要可靠骨骼鉴定及保存状况记录，不能替代原物。
- 不能把未来自动化/机器学习建议说成已经验证的AI模型。

**教材用途：** 适合第3/4章缺失编码与分母的补充练习；现有陶片例子已覆盖该概念，本轮不重复插入。

**文件名／版本问题：** 文件名2026为在线/版权年；PDF及出版社正式卷年为2027（34:3），在线日期2026-07-14。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1007%2Fs10816-026-09811-2)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。
- [核查来源2](https://link.springer.com/article/10.1007/s10816-026-09811-2)：出版社题录及正文方法概述核对；2026-07-14在线、34:3 (2027)。

### P56

Galo Romero-García; Daniel Sánchez-Gómez; José Á. Garrido-Cordero; José M. Martínez-Blanes; Ana C. Sousa; Carlos P. Odriozola. 2024. “Unlocking archaeological data online via the PEPAdb (Prehistoric Europe's Personal Adornment Database) initiative for Open Science.” *Antiquity 98(398)*. e9，文内页1–6。 DOI：[10.15184/aqy.2024.2](https://doi.org/10.15184/aqy.2024.2)。

**附件：** `Romero-Garcia 2024 Unlocking archaeological data online via the PEPAdb.pdf`；6页；SHA-256：`c79a0418b41421a8b8ed09d2d7adf41738c4d32f2b103487eaf12237450cbe45`。

**日期与版本：** 在线日期：2024-01-29；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** Antiquity Project Gallery：史前欧洲个人装饰品开放资料库PEPAdb。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性原文核读：第1—2及第5页；数据库当前可用性没有独立实测。

**原文定位：**

- 印刷／文内5页；PDF第5页；下载、空间和非空间资料；原PDF文本核读

**可支持的论点：**

- 原始整理资料与进一步处理的空间/非空间资料应有清楚关系，可用格式和描述影响再利用。

**限制与解释边界：**

- 论文中的开放数据要求不能直接引用为所有地区现行法律规则。
- 文章发表时的入口不代表当前入口、许可和字段完全未变；学生资源上线前需另查网站。

**教材用途：** 可考虑放入考古资料参考资源，与FAIR讨论互相链接；不增加正文开放科学综述。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.15184%2Faqy.2024.2)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。

### P68

Justin St P. Walsh; Alice C. Gorman. 2021. “A method for space archaeology research: the International Space Station Archaeological Project.” *Antiquity 95(383)*. 1331–1343。 DOI：[10.15184/aqy.2021.114](https://doi.org/10.15184/aqy.2021.114)。

**附件：** `Walsh 2021 A method for space archaeology research.pdf`；13页；SHA-256：`cf1d57b3a89d62ac8bf01fd1066636617e89446c2e2a97493a8e561778f3f021`。

**日期与版本：** 在线日期：2021-08-24；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** 国际空间站物质文化研究的方法方案，包括历史照片档案及计算分析的拟议用途。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性原文核读：1331—1332、1335及1339页相关段落。

**原文定位：**

- 印刷／文内1335页；PDF第5页；照片档案与计算分析；原PDF文本核读
- 印刷／文内1339页；PDF第9页；研究设计及参与条件；原PDF文本核读

**可支持的论点：**

- 照片档案可成为难以直接观察环境的材料，但摄影、取景和记录目的本身需要分析。

**限制与解释边界：**

- 这里space archaeology指人类太空活动的物质文化，不是地球表面的遥感考古。
- 这篇方法方案不能表述为已完成的机器学习发现或现成验证成绩；项目后续成果须另查原始论文。

**教材用途：** 可作为教师扩展阅读，不将国际空间站研究扩成Part I新主题。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.15184%2Faqy.2021.114)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。

### P74

Filippo Zangrossi; Diego Lombao; Alessio Veneziano; Manuel Vaquero. 2026. “Beyond the Layer: A 3D-Driven Generalized Methodology for the Quantitative Dissection of Archaeological Palimpsests.” *Journal of Archaeological Method and Theory 33(3)*. 文章43，文内页1–25。 DOI：[10.1007/s10816-026-09776-2](https://doi.org/10.1007/s10816-026-09776-2)。

**附件：** `Zangrossi 2026 Beyond the layer.pdf`；25页；SHA-256：`fd8fbc81a8780975f6af17b1070a937b54ffd0b56905763c1cb0d38565eb9ce1`。

**日期与版本：** 在线日期：2026-04-15；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** ArchStrat三维拼合组空间关系/体积算法；适用域、敏感性和虚拟发掘模拟验证。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性原文核读：第1—2页及19—21页方法总结、局限与结论；没有运行仿真或审计代码。

**原文定位：**

- 印刷／文内19页；PDF第19页；三类模拟与Limitations；原PDF文本核读
- 印刷／文内20页；PDF第20页；阈值、形成过程及缺乏ground truth；原PDF文本核读
- 印刷／文内21页；PDF第21页；Conclusions / 未来案例验证；原PDF文本核读

**可支持的论点：**

- 沉积学上的一个层位可能包含多个活动事件；三维拼合组可作为进一步分解时间关系的计算资料。
- 本文验证依赖模拟，并明确提出真实案例检验和形成过程评估作为后续工作。

**限制与解释边界：**

- 只处理满足条件的拼合组，孤立出土物不进入该时间模型；组内数量、空间密度与阈值选择限制适用范围。
- 坡度、沉积、扰动及埋藏后过程尚未充分覆盖；不能把模拟中的分层识别表述为自动获得真实年代或重建全部占用事件。

**教材用途：** 未来可用来说明第3章记录单位和第4章时间平均；本轮不增加体积指标及拼合算法教学。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1007%2Fs10816-026-09776-2)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。

## 5. 生成式AI、古代语言与教学

### P07

Robert J. Bischoff. 2026. “Large Language Models in Archaeological Practice: Efficacy, Ethics, Risks, and Governance.” *OSF 预印本；Center for Open Science 登记*. 上传稿 19 页；没有期刊卷期或正式出版页码。 DOI：[10.31235/osf.io/azs6r_v1](https://doi.org/10.31235/osf.io/azs6r_v1)。

**附件：** `Bischoff 2026 Large Language Models in Archaeological Practice-.pdf`；19页；SHA-256：`ccb95b6097022b29ea8a2b602b6e31f59ebd55ea45ba306423f1b5969314d412`。

**研究类型与本轮安排：** 方法讨论＋小型自构引文核查示例；预印本。本轮不增加正文，按以下用途保留。

**阅读范围：** 定向原文阅读：PDF 1–2、9–13 页；未声称逐页通读。

**原文定位：**

- PDF 1：署名及稿件日期 2026-03-18。
- PDF 9–11，§4：作者构造的 20 条引文核查任务、评分过程及局限。
- PDF 12–13：可复核的工作流程与记录要求。

**可支持的论点：**

- 以三个自拟段落中的 20 条真实文献引文测试一个限定文章范围的检索核查流程；作者预先设置 10 条有关和 10 条误导引文，并以自己的专家判断作参照。
- 文中提出把文献处理、编码辅助及元数据整理限定为可检查的小任务；价值—风险矩阵是作者的判断框架。

**限制与解释边界：**

- 没有盲法独立标注或评审一致性检验；20 条引文的自设任务不能代表一般文献研究能力。
- 核查得分含词汇、短语及题名重合，不能直接称作已验证的通用智能体推理能力。
- PDF 没有期刊信息或 DOI。后续已核对 Crossref 登记的题名、作者及 posted-content / preprint 类型，但原平台全文尚未取得，不能推断经过同行评审或与上传稿完全同版。
- 上传稿日期为 2026-03-18，Crossref 登记 posted 为 2026-05-14；分别记录，不把后者倒填为稿件日期。

**教材用途：** 可供编辑工作流程参考；第 1 章已有智能体式 AI 和来源检查，不再增加同类警示段落。若正式引入需明确预印本和原平台版本未对照的状态。

**文件名／版本问题：** 未发现实质性文件名错误；著录以原文题名页为准。

**独立书目或网站核查：**

- [核查来源1](https://osf.io/azs6r_v1)：此原平台地址由已核对的 Crossref primary resource 字段确认；未成功取得该地址上的全文，不标作平台全文已读。
- [核查来源2](https://api.crossref.org/works/10.31235%2Fosf.io%2Fazs6r_v1)：已读取父任务取得的 Crossref 原始记录，逐项核对 DOI 与本 PDF；属于出版社登记元数据，不能替代原文方法或结果。

### P15

Carlos Heredia Chimeno. 2025. “Opening the Conversation: Rethinking How We Teach Antiquity in the Age of AI.” *AI & Antiquity: Journal of Teaching and Technology in Ancient Studies 1(1)*. 4–14；PDF 前附 HAL 存档封面。 DOI：[10.64946/aiantiquity.v1i1.editorial](https://doi.org/10.64946/aiantiquity.v1i1.editorial)。

**附件：** `Chimeno 2025 Opening the Conversation- Rethinking How We Teach Antiquity in the Age of AI.pdf`；12页；SHA-256：`4ec55a7ecf76fc2bb5a70a7ce9260688f7d73c3bdc634196981be8f29beee58b`。

**研究类型与本轮安排：** 社论的存档副本。重复文件记录：规范文献见[P29](#p29)，不独立计入文献数量。

**阅读范围：** 定向原文阅读：HAL 封面、社论开篇与结尾；与 P29 全部 11 张正文逐页做去空白文本比对。

**原文定位：**

- PDF 1：HAL 存档信息，2025-10-26 提交。
- 原刊 4 页（PDF 2）：社论论题。
- 原刊 13–14 页（PDF 11–12）：教学与评估反思。

**可支持的论点：**

- 提出生成式 AI 时代古代研究教学应重视证据、批判阅读和学术判断。
- 这是创刊号社论；它讨论的教学方向没有在本文中作为受控实验检验。

**限制与解释边界：**

- P15 比 P29 多一张 HAL 封面，其余 11 页去空白后的全文逐页完全相同；不能计作两项独立研究。
- HAL 存档日期为 2025-10-26，Crossref 发表日期为 2025-09-24；存档不构成另一项研究。

**教材用途：** 保留两条上传记录，正式文献只保留一个标准条目，以 P29 为重复组的规范记录。

**文件名／版本问题：** 与 P29 确认重复；文件名将复姓 Heredia Chimeno 简写为 Chimeno。

**独立书目或网站核查：**

- [核查来源1](https://ai-antiquity.org/index.php/ai/issue/view/issue1)：出版者正式卷期目录检索结果核对作者、题名、页码及 DOI。
- [核查来源2](https://api.crossref.org/works/10.64946%2Faiantiquity.v1i1.editorial)：已读取父任务取得的 Crossref 原始记录，逐项核对 DOI 与本 PDF；属于出版社登记元数据，不能替代原文方法或结果。

### P19

Peter J. Cobb. 2023. “Large Language Models and Generative AI, Oh My! Archaeology in the Time of ChatGPT, Midjourney, and Beyond.” *Advances in Archaeological Practice 11(3)*. 363–369。 DOI：[10.1017/aap.2023.20](https://doi.org/10.1017/aap.2023.20)。

**附件：** `Cobb 2023 Large language models and generative AI, oh my.pdf`；7页；SHA-256：`47cabc257a3842e9b35d9d1af579005cf7674627bb5cc0ba8d7e2bfbff2e72eb`。

**研究类型与本轮安排：** Digital Review／技术评论与操作示例。本轮不增加正文，按以下用途保留。

**阅读范围：** 定向原文阅读：PDF 1–5 页，检查写作、教学和生成插图示例。

**原文定位：**

- 原刊 364–365 页（PDF 2–3）：语言模型及引用、写作问题。
- 原刊 365–366 页（PDF 3–4）：教学用途。
- 原刊 367 页（PDF 5），图 3：2023 年的建筑平面图生成示例。

**可支持的论点：**

- 以当时的工具输出说明生成式 AI 在考古写作、教学和插图中的潜在用途与错误。

**限制与解释边界：**

- 数字技术评论及示例，不是有代表性样本的能力评测。
- 具体模型、提示和工具日期属于 2023 年，不能不加时间限定地代指目前产品表现。
- 其学术规范建议与教材现有第 1 章重叠。

**教材用途：** 保留为生成式 AI 进入考古实践的早期讨论；不再重复一般性模型幻觉警告。

**文件名／版本问题：** 未发现实质性文件名错误；著录以原文题名页为准。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1017%2Faap.2023.20)：已读取父任务取得的 Crossref 原始记录，逐项核对 DOI 与本 PDF；属于出版社登记元数据，不能替代原文方法或结果。

### P29

Carlos Heredia Chimeno. 2025. “Opening the Conversation: Rethinking How We Teach Antiquity in the Age of AI.” *AI & Antiquity: Journal of Teaching and Technology in Ancient Studies 1(1)*. 4–14。 DOI：[10.64946/aiantiquity.v1i1.editorial](https://doi.org/10.64946/aiantiquity.v1i1.editorial)。

**附件：** `Heredia-4-14.pdf`；11页；SHA-256：`9f6751b9acfe8a98d210e42aa2cf7e7fc7aced010363e4a7436792a00adee993`。

**研究类型与本轮安排：** 社论；P15/P29 重复组的规范记录。本轮不增加正文，按以下用途保留。

**阅读范围：** 定向阅读社论开篇和结尾；全部 11 页与 P15 去除 HAL 封面后的文本逐页比对一致。

**原文定位：**

- 原刊 4 页（PDF 1）：社论论题。
- 原刊 13–14 页（PDF 10–11）：教学与评价反思。

**可支持的论点：**

- 讨论 AI 时代古代研究教学中证据、学术判断和学习目标的关系。

**限制与解释边界：**

- 社论，不是效果试验。
- P15 与本项是同一篇文章的两个文件；只能形成一个参考文献条目。

**教材用途：** 保留一个标准书目条目；无需在正文增加重复警示。

**文件名／版本问题：** Heredia-4-14.pdf 没有题名与年份；与 P15 确认同文。

**独立书目或网站核查：**

- [核查来源1](https://ai-antiquity.org/index.php/ai/issue/view/issue1)：出版者正式卷期目录检索结果核对作者、题名、页码及 DOI。
- [核查来源2](https://api.crossref.org/works/10.64946%2Faiantiquity.v1i1.editorial)：已读取父任务取得的 Crossref 原始记录，逐项核对 DOI 与本 PDF；属于出版社登记元数据，不能替代原文方法或结果。

### P34

Yusi Liu; Daniel D’Elia; Rocco Palermo. 2026. “Let’s Chat About Archaeology: Responsible and Thoughtful Use of AI Tools in the Classroom, A Case Study.” *AI & Antiquity: Journal of Teaching and Technology in Ancient Studies 2(1)*. 25–36。 DOI：[10.64946/aiantiquity.v2i1.002](https://doi.org/10.64946/aiantiquity.v2i1.002)。

**附件：** `Liu 2026 Let’s chat about archaeology- responsible and thoughtful use of AI tools in the classroom.pdf`；12页；SHA-256：`df8a36f86fc1484202bcdae79538ab73f8b0d153dd72c50d659b9b93a623e76d`。

**研究类型与本轮安排：** 课堂案例研究／教学设计与反思。本轮不增加正文，按以下用途保留。

**阅读范围：** 12 页原文文本已阅读；对原刊 32 页（PDF 8）的教学局限作视觉复核。

**原文定位：**

- 原刊 27–28 页（PDF 3–4）：2025 年春季 Bryn Mawr 考古学导论课程与作业设计。
- 原刊 29–32 页（PDF 5–8）：学生反馈、33 份反思及作者自述不足。
- 原刊 35–36 页（PDF 11–12）：完整作业附录。

**可支持的论点：**

- 作业让学生先保存与 AI 的对话，再作为编辑以课程材料及学术资料注释、查证并修改生成文字。
- 作者在第 32 页指出：活动对研究技能的帮助较有限，学生仍需在查找和评价学术来源方面获得前置训练。

**限制与解释边界：**

- 属于课堂案例和教学反思，没有对照组或前后测，不能据摘要的 successful 推断学习效果已被因果验证。
- 学生工具选择、提示及版本不统一；33 份反思和文中某百分比的分母关系不明，不抄录百分比。
- 作者据虚构引文怀疑部分反思由 AI 生成，该线索不能独立证明作者身份或写作过程。
- 不沿用文中对百科类资料的笼统可靠性判断；教材应说明何种论断需要何种原始证据。

**教材用途：** 优先用于 reference-resources/ai-learning.qmd 的简短资源条目，突出可改编作业与第 32 页限制；不在第 1 章再加一段模型幻觉警告。

**文件名／版本问题：** 原文 PDF 题名为 in Classroom；出版者元数据为 in the Classroom。规范条目采用出版者题名并记录差异。

**独立书目或网站核查：**

- [核查来源1](https://ai-antiquity.org/index.php/ai/issue/view/volume2issue1)：已打开出版者正式卷期目录；核对作者、题名、页码及 DOI。
- [核查来源2](https://ai-antiquity.org/index.php/ai/article/view/28)：出版者原始文章页检索记录核对作者、题名、Articles 分类及 2026-02-27 发表日期。

### P37

Mitra Madanchian; Hamed Taherdoost. 2025. “The impact of artificial intelligence on research efficiency.” *Results in Engineering 26*. 文章号 104743；内部页码 1–12。 DOI：[10.1016/j.rineng.2025.104743](https://doi.org/10.1016/j.rineng.2025.104743)。

**附件：** `Madenchian 2025 The impact of artificial intelligence on research efficiency..pdf`；12页；SHA-256：`9a96725e7d0f2445591c1b12788dd67efdbe4bc9dd49b15b41be7d13db02f019`。

**研究类型与本轮安排：** 跨学科叙述性综述。本轮不增加正文，按以下用途保留。

**阅读范围：** 定向原文阅读：PDF 1–2 及 8 页的范围、研究流程和案例综述。

**原文定位：**

- 原文第 2 页：研究流程与综述范围。
- 原文第 8 页，§6.3：定性研究、档案及文献任务。

**可支持的论点：**

- 概述 AI 在检索、编码、数据处理、研究设计和写作中的可能作用及组织条件。

**限制与解释边界：**

- 跨学科叙述性综述，没有本研究新采集的考古性能数据。
- 效率改善的百分比多为转引，不能作为考古研究统一节省工时的证据。
- P64 参考注将本篇写作 2026 年，但原刊与 DOI 登记均支持 2025 年；不得随转引复制年份。

**教材用途：** 仅作一般研究工作流程背景，不用于具体考古发现或效果评估的证据。

**文件名／版本问题：** 文件名 Madenchian 拼写错误，正确姓氏 Madanchian；文件名年份 2025 正确。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1016%2Fj.rineng.2025.104743)：已读取父任务取得的 Crossref 原始记录，逐项核对 DOI 与本 PDF；属于出版社登记元数据，不能替代原文方法或结果。

### P39

Matthew Magnani; Jon Clindaniel. 2023. “Artificial Intelligence and Archaeological Illustration.” *Advances in Archaeological Practice 11(4)*. 452–460。 DOI：[10.1017/aap.2023.25](https://doi.org/10.1017/aap.2023.25)。

**附件：** `Maganani 2023 Artificial intelligence and archaeological illustration.pdf`；9页；SHA-256：`3227a3c38f45bfb037f46a8abb0926c28bf2cc09f5290f2fed0d2ff8f3606634`。

**研究类型与本轮安排：** How-to／生成插图工作流程示例。本轮不增加正文，按以下用途保留。

**阅读范围：** 定向原文阅读：PDF 1、3–4、6–7 页的示例、提示和图注。

**原文定位：**

- 原刊 454–455 页（PDF 3–4）：尼安德特人、火与埋葬主题的生成图像。
- 原刊 458 页（PDF 7），图 7：反复调整提示与生成批次。

**可支持的论点：**

- 示范如何借助生成图像表现不同考古假设；图像的细节由输入、模型和人工选择共同塑造。

**限制与解释边界：**

- 操作方法和插图示例不是历史真实性检验，不能从生成图像反过来证明古代行为。
- 2023 年这篇插图论文与教材现有另一次尼安德特人生成图像研究并非同一研究，不能把两篇的日期、方法与结论混用。
- 没有可外推的模型重建历史准确率。

**教材用途：** 参考资源或教师制作插图时可用；第 1 章已有相关案例，避免再次扩写。

**文件名／版本问题：** 文件名 Maganani 拼写错误，正确姓氏 Magnani。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1017%2Faap.2023.25)：已读取父任务取得的 Crossref 原始记录，逐项核对 DOI 与本 PDF；属于出版社登记元数据，不能替代原文方法或结果。

### P43

Isaías Arrayás Morales; Carlos Heredia Chimeno. 2026. “Same Standards, Different Pathways: Forgotten Voices, Neurodiversity, and Critical AI Literacy in Ancient History Teaching.” *AI & Antiquity: Journal of Teaching and Technology in Ancient Studies 2(2)*. 70–94。 DOI：[10.64946/aiantiquity.v2i2.005](https://doi.org/10.64946/aiantiquity.v2i2.005)。

**附件：** `Morales 2026 Same Standards, Different Pathways.pdf`；25页；SHA-256：`19c26ab73c8775913040702e43387b3541db5d77e48a167d7cf554de8f34bca7`。

**研究类型与本轮安排：** 教学创新案例／概念框架。本轮不增加正文，按以下用途保留。

**阅读范围：** 定向原文阅读：PDF 1、3–5、20–21 页，覆盖框架、课堂实施及后期修正。

**原文定位：**

- 原刊 72–74 页（PDF 3–5）：共同的学术要求与不同组织路径。
- 原刊 89–90 页（PDF 20–21）：旧版开放教育资源的局限与修改。

**可支持的论点：**

- 从 2025–26 年两门古代史课经验提出共同标准、不同呈现路径的教学框架。
- 修正后的设计不按诊断标签给学生分配学习路线，批判性 AI 素养可以使用教师提供的既有输出。

**限制与解释边界：**

- 课堂实施反思不能当作随机对照教学效果研究。
- 作者明确说明早期 Zenodo 作业材料仍保留诊断与路径关联及强制使用 AI 的旧做法；不能将旧链接不加说明地作为当前推荐模板。

**教材用途：** 教师教学设计资料；如引用应采用论文修订后的建议。当前第一编不额外引入框架名和新专题。

**文件名／版本问题：** 文件名 Morales 只保留复姓末段，规范书目应使用 Arrayás Morales。

**独立书目或网站核查：**

- [核查来源1](https://ai-antiquity.org/index.php/ai/issue/view/volume2issue2)：出版者正式卷期目录已打开，并以站内原始检索记录补充核对社论及 DOI。

### P57

Edward A. S. Ross; Jackie Baines. 2025. “Navigating the Fog: The Effectiveness of Personalised Conversational GenAI Models for Supporting Ancient Language Learning.” *AI & Antiquity: Journal of Teaching and Technology in Ancient Studies 1(1)*. 35–52。 DOI：[10.64946/aiantiquity.v1i1.002](https://doi.org/10.64946/aiantiquity.v1i1.002)。

**附件：** `Ross-Baines-35-52.pdf`；18页；SHA-256：`320bd37171702e2ad24f7e5a6a4f2f70c72238d0cd3cd7e01b0d9bb25b910658`。

**研究类型与本轮安排：** 教学工具的小规模比较测试。本轮不增加正文，按以下用途保留。

**阅读范围：** 定向原文阅读：PDF 1、4–10、13–16 页的材料准备、工具测试和结果；并未运行作者工具。

**原文定位：**

- 原刊 38–41 页（PDF 4–7）：321 个拉丁语词条、数据表与自定义聊天工具。
- 原刊 42–44 页（PDF 8–10）：超出给定词表和错误自我报告的具体输出。

**可支持的论点：**

- 作者比较基础聊天工具与附加课程资料和指令的定制工具，检验它们是否遵守古代语言教学的词汇及形式限制。
- 给工具上传材料和定制指令并未保证输出始终限于指定词表。

**限制与解释边界：**

- 这是小规模、提示和版本相关的工具测试，不是学生学习成效实验，也不能概括所有当代模型。
- 自定义 GPT 或 Gem 不等于重新训练模型参数，教材不能笼统称之为模型微调。
- 2025 年不同测试时间、有限轮次和生成随机性限制可比性；作者准备词表所需时间不能外推为一般教学工时。

**教材用途：** 适合作为古代语言课堂工具的延伸阅读；当前正文优先 P55 的直接考古材料评价案例。

**文件名／版本问题：** Ross-Baines-35-52.pdf 省略题名和年份；规范记录需补全。

**独立书目或网站核查：**

- [核查来源1](https://ai-antiquity.org/index.php/ai/issue/view/issue1)：出版者正式卷期目录检索结果核对作者、题名、页码及 DOI。

### P58

Samandar Ruziboev（PDF；出版者目录作 Samandar Ro’ziboyev）; Noyibjon Khudoyorov. 2026. “Reconstructing Silent Voices in Ancient Historiography: Re-reading the Shiji through an Inclusive Artificial Intelligence Lens.” *AI & Antiquity: Journal of Teaching and Technology in Ancient Studies 2(1)*. 76–88（出版者目录及实际末页；PDF 首页误写 76–87）。 DOI：[10.64946/aiantiquity.v2i1.005](https://doi.org/10.64946/aiantiquity.v2i1.005)。

**附件：** `Ruziboev 2026 Reconstructing Silent Voices in Ancient Historiography.pdf`；13页；SHA-256：`853d79267a409f65e539954b6e6579d073b3c43976f4125df6628cf57416d9fe`。

**研究类型与本轮安排：** 史学解释性论文；计算方法的复核材料不足。本轮不增加正文，按以下用途保留。

**阅读范围：** 定向原文阅读：PDF 1–6、9–13 页，重点核对方法、史料解释、引文与末表；未获得代码、提示或独立语料。

**原文定位：**

- 原刊 79–80 页（PDF 4–5），§4：语料处理、词频／共现及语义聚类的叙述。
- 原刊 84–85 页（PDF 9–10）：历史沉默与 AI 的解释。
- 原刊 86 页（PDF 11）：ChatGPT 引用；原刊 88 页（PDF 13）：计数表。

**可支持的论点：**

- 文章提出以《史记》卷 123《大宛列传》为对象，结合词频、共现和聚类讨论叙事中心与边缘行动者。

**限制与解释边界：**

- 提供的文本不足以重建可复现的语料版本、分词／标注准则、模型参数、提示和完整运行过程。
- 表格中的计数及 AI 生成的语义概括不能独立证明古代群体的声音或叙事机制；仍需逐句核对可靠《史记》版本和竞争解释。
- 本轮没有完成其中文引文的版本校勘，不能断言史料引文已证实正确，也不在缺乏证据时指控其造假。
- 出版者记录与 PDF 的页码和作者罗马字拼写不同，引用时必须说明并择定规范形式。

**教材用途：** 暂不作为已验证的 AI 中国古史研究成果写入正文；先保留待核项，所需材料为明确版本语料、代码／提示和逐句史料证据。

**文件名／版本问题：** PDF 首页页码与实际末页不符；作者 Ruziboev 与出版者 Ro’ziboyev 存在转写差异。

**独立书目或网站核查：**

- [核查来源1](https://ai-antiquity.org/index.php/ai/issue/view/volume2issue1)：已打开出版者正式卷期目录；核对作者、题名、页码及 DOI。

## 6. 学术规范、社群协作与包容性

### P16

Carlos Heredia Chimeno. 2026. “Neurodiversity and Ancient Studies: From Accommodation to Inclusive Design.” *AI & Antiquity: Journal of Teaching and Technology in Ancient Studies 2(2)*. 4–15。 DOI：[10.64946/aiantiquity.v2i2.editorial](https://doi.org/10.64946/aiantiquity.v2i2.editorial)。

**附件：** `Chimeno 2026 Neurodiversity and Ancient Studies.pdf`；12页；SHA-256：`bf8fe73697c3bfdae08609d6cefcc90ae5aa90a1d5de90bd6c747e5b6c9d60fa`。

**研究类型与本轮安排：** 社论／教学设计讨论。本轮不增加正文，按以下用途保留。

**阅读范围：** 定向原文阅读：PDF 1–4、9 页，覆盖论题、包容性设计主张及对 AI 使用的限定。

**原文定位：**

- 原刊 6–7 页（PDF 3–4）：学科能力与呈现形式的区分。
- 原刊 12 页（PDF 9）：批判性 AI 素养无需强制个人使用 AI。

**可支持的论点：**

- 建议把明确的任务要求、合理的呈现选择和共同的学术评价标准结合起来。
- 反对把某一诊断简单对应为固定的学习方式。

**限制与解释边界：**

- 属于社论和教学设计论证，不是 AI 或教育干预效果实验。
- 文中概述其他论文的发现应回查原研究；不能直接作为医疗或个体学习诊断建议。

**教材用途：** 作为教师的教学设计阅读，不在第一编另开神经多样性或临床概念。

**文件名／版本问题：** 未发现实质性文件名错误；著录以原文题名页为准。

**独立书目或网站核查：**

- [核查来源1](https://ai-antiquity.org/index.php/ai/issue/view/volume2issue2)：出版者正式卷期目录已打开，并以站内原始检索记录补充核对社论及 DOI。

### P17

Carlos Heredia Chimeno. 2026. “When References Mislead: Verification, AI Attribution, and Academic Bullying in Scholarly Evaluation.” *AI & Antiquity: Journal of Teaching and Technology in Ancient Studies 2(1)*. 4–10。 DOI：[10.64946/aiantiquity.v2i1.editorial](https://doi.org/10.64946/aiantiquity.v2i1.editorial)。

**附件：** `Chimeno 2026 When References Mislead.pdf`；7页；SHA-256：`f269d7adfcb60d0f6c298093388bbc686e1019e841192538cd2e43bc60320844`。

**研究类型与本轮安排：** 社论／学术评价程序讨论。本轮不增加正文，按以下用途保留。

**阅读范围：** 7 页文本已阅读；重点核对原刊 4–8 页的论证，末尾是本期内容介绍和文献。

**原文定位：**

- 原刊 4–6 页（PDF 1–3）：表面规范的引文与可追查来源。
- 原刊 6–8 页（PDF 3–5）：引文错误与 AI 归因、动机判断的区分。

**可支持的论点：**

- 主张对具体引文做可复核检查，并将来源错误与对作者使用 AI、欺骗或主观动机的判断区分。

**限制与解释边界：**

- 社论没有提供可外推的模型虚构引文发生率。
- 不能从一条错误引文就认定 AI 写作或作者有欺骗意图。
- 第 1 章已充分讨论来源核查，重复加入警告不能带来新的教学内容。

**教材用途：** 编辑记录及教师阅读可用；如加入参考资源，应明确标为社论，不另写同类正文警示。

**文件名／版本问题：** 未发现实质性文件名错误；著录以原文题名页为准。

**独立书目或网站核查：**

- [核查来源1](https://ai-antiquity.org/index.php/ai/issue/view/volume2issue1)：已打开出版者正式卷期目录；核对作者、题名、页码及 DOI。
- [核查来源2](https://ai-antiquity.org/index.php/ai/article/view/29)：出版者原始页面检索记录确认社论类别、作者及 2026-02-27 出版日期。

### P18

Amy Elizabeth Clark; Danielle A. Macdonald. 2026. “Assessing Gender Demographics of Paleolithic Researchers in North America.” *American Antiquity 91(1)*. 135–148。 DOI：[10.1017/aaq.2025.10110](https://doi.org/10.1017/aaq.2025.10110)。

**附件：** `Clark 2026 Assessing Gender Demographics of Paleolithic Researchers in North America.pdf`；14页；SHA-256：`0da0cc8fd32d63d22e0f618a276bc311ea69aa5e1e1315530ba6cf33683ae77f`。

**研究类型与本轮安排：** 专业群体的人口统计／文献计量实证研究。本轮不增加正文，按以下用途保留。

**阅读范围：** 定向原文阅读：PDF 1、3–4、11–12 页，覆盖样本定义、方法和解释范围。

**原文定位：**

- 原刊 137–138 页（PDF 3–4）：北美学界、五种期刊及 PBS 纪录片的样本构造。
- 原刊 145–146 页（PDF 11–12）：讨论。

**可支持的论点：**

- 比较美国和加拿大终身教职轨道教师、1994–2023 年指定期刊第一作者与 PBS 人类演化纪录片专家的性别构成。
- Dimensions AI 用于文献检索并结合人工筛选；研究对象是研究者的代表性。

**限制与解释边界：**

- 不是以机器学习发现考古遗存的研究；检索平台名称中的 AI 不等于本文训练了新的考古预测模型。
- 抽样、网页可见度、第一作者统计、姓名／代词推定以及性别分类方法均限制解释，不能代表全球全部旧石器考古从业者。
- 2025 年为在线先发表及 DOI 年份；上传正式卷期为 2026 年。

**教材用途：** 用于理解抽样与代表性的背景阅读；当前第一编不扩展成学科性别史专题。

**文件名／版本问题：** 未发现实质性文件名错误；著录以原文题名页为准。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1017%2Faaq.2025.10110)：已读取父任务取得的 Crossref 原始记录，逐项核对 DOI 与本 PDF；属于出版社登记元数据，不能替代原文方法或结果。

### P21

Medeia Csoba DeHass; Lori Collins; Alexandra Taitt; Julie Raymond-Yakoubian; Travis Doering; Lisa Navraq Ellanna; Eric Hollinger; Jorge Gonzalez; Edwell John Jr.; Desireé Martinez; Meghan Sigvanna Tapqaq. 2025. “Ethical Considerations in the Use of 3D Technologies to Preserve and Perpetuate Indigenous Heritage.” *American Antiquity 90(2)*. 282–306。 DOI：[10.1017/aaq.2024.82](https://doi.org/10.1017/aaq.2024.82)。

**附件：** `DeHass 2025 Ethical Considerations in the Use of 3D Technologies.pdf`；25页；SHA-256：`c1370f03af5525c5ebc9913458ce252f6052465f6753886bd3544ba4ed0938db`。

**日期与版本：** 在线日期：2025-04-21；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** 研究者、原住民社群与3D遗产专家共同提出的负责任研究及数字遗产伦理框架。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性原文核读：题名/摘要、引言开头及第17—18页完整相关段落；未逐页阅读全文。

**原文定位：**

- 印刷／文内298页；PDF第17页；3D资料的生命周期、原住民知识与治理；原PDF文本核读
- 印刷／文内299页；PDF第18页；CARE / FAIR与访问范围；原PDF文本核读

**可支持的论点：**

- 原始照片、扫描资料、处理后的三维模型与复制物都可能承载社群知识，访问与后续使用应覆盖整个资料生命周期。
- 开放共享原则需与社群决定权及具体访问条件协调。

**限制与解释边界：**

- 属于协作伦理框架，不是AI性能实验或普遍适用的法律条文。
- 不能把原住民社群的具体治理语境直接移植成所有中国考古材料必须开放或必须封闭的规则。

**教材用途：** 适合第3章共享标准后的延伸阅读，与FAIR原始文献互补；本轮不扩展伦理新节。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1017%2Faaq.2024.82)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。

### P23

Julieta Flores-Muñoz; Patricia Murrieta-Flores. 2026. “Working against Silence: Nahua Scholarly Labor, Digital Precarity, and the Politics of Archaeological Sovereignty—The MONARO Project in Veracruz, Mexico.” *Advances in Archaeological Practice 14(3)*. 469–484。 DOI：[10.1017/aap.2026.10166](https://doi.org/10.1017/aap.2026.10166)。

**附件：** `Flores-Muñoz 2026 Working against Silence.pdf`；16页；SHA-256：`5dde7f95a24f69d2f72d675942429adf5d34b00a73093e7a67a33a00c152f293`。

**研究类型与本轮安排：** 社区协作案例／数字考古知识与治理讨论。本轮不增加正文，按以下用途保留。

**阅读范围：** 定向原文阅读：题名摘要及 PDF 6–12 页的项目、元数据和治理讨论；不声称逐页通读。

**原文定位：**

- 原刊 474–475 页（PDF 6–7）：纳瓦语／西班牙语资料、转写、注释及地方解释工作。
- 原刊 476、479–480 页（PDF 8、11–12）：基础条件、访问权限与 AI 展望。

**可支持的论点：**

- MONARO 案例把地方研究者的转写、语义解释、命名和元数据决定视为知识生产的一部分。
- 记录和访问安排依赖地方参与、设备条件及不同层次的许可。

**限制与解释边界：**

- 社区协作案例及理论讨论，不是 AI 系统的准确率或自动化效果试验。
- 第 480 页仍将不少 AI 用法表述为展望；不能改写成该项目已充分实现自动知识重建。
- 开放获取论文本身不意味着其研究对象和所有社区资料可以不受限制地公开。

**教材用途：** 可供第 3 章理解记录的语境和元数据解释责任；当前有限正文修改优先选更直接的材料形成案例，本篇先保留阅读资源。

**文件名／版本问题：** 未发现实质性文件名错误；著录以原文题名页为准。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1017%2Faap.2026.10166)：已读取父任务取得的 Crossref 原始记录，逐项核对 DOI 与本 PDF；属于出版社登记元数据，不能替代原文方法或结果。

### P28

Yongyuan He（何永元）; Yi Bu（步一）. 2026. “Academic journals’ AI policies fail to curb the surge in AI-assisted academic writing.” *Proceedings of the National Academy of Sciences 123(9)*. 文章号 e2526734123；内部页码 1–7。 DOI：[10.1073/pnas.2526734123](https://doi.org/10.1073/pnas.2526734123)。

**附件：** `He 2026 Academic journals’ AI policies fail to curb the surge in AI-assisted academic writing.pdf`；7页；SHA-256：`338934d5f356ab6065ffd6617f13a9c161a1c926871bfca9edf7a57dcae2967c`。

**研究类型与本轮安排：** 跨学科文献计量观察研究。本轮不增加正文，按以下用途保留。

**阅读范围：** 定向原文阅读：PDF 1、4–6 页，检查方法、范围及作者自述局限；未检查补充材料。

**原文定位：**

- 原文第 4–6 页（PDF 4–6）：抽样、估计程序及局限。
- 原文第 5 页：群体层面估计与政策比较的限制。

**可支持的论点：**

- 对 5,114 种期刊、约 523 万篇论文摘要以及较小的全文子集作群体层面的 AI 辅助写作估计。
- 采用词汇统计混合模型估计群体变化，而非逐篇确认作者使用 AI 的行为。

**限制与解释边界：**

- 不是考古学实证研究。
- 群体概率估计不能作为单篇文章 AI 写作判定器；无法稳定区分语言润色与生成内容。
- 政策有无的二分记录、缺少精确出台时间、观察窗口及全文可得性限制因果解释；标题中的 fail 不能直接改述为政策失效已被因果实验证明。
- 全文子集中的披露比例不能直接换算为所有 AI 使用者的披露率。

**教材用途：** 教师或编辑层面的研究伦理背景；不作为考古模型性能证据，不在第一编复制其标题式结论。

**文件名／版本问题：** 未发现实质性文件名错误；著录以原文题名页为准。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1073%2Fpnas.2526734123)：已读取父任务取得的 Crossref 原始记录，逐项核对 DOI 与本 PDF；属于出版社登记元数据，不能替代原文方法或结果。

### P35

Christina Luke. 2025. “Turning 50 at the Journal of Field Archaeology.” *Journal of Field Archaeology 50(8)*. 678–679；上传 PDF 含一页平台封面。 DOI：[10.1080/00934690.2025.2578591](https://doi.org/10.1080/00934690.2025.2578591)。

**附件：** `Luke 2025 Turning 50 at the Journal of Field Archaeology.pdf`；3页；SHA-256：`7f0779834260282ff54bac485e14b41c1ffdae54384c06a320257e0b4145ac79`。

**研究类型与本轮安排：** 周年社论。本轮不增加正文，按以下用途保留。

**阅读范围：** 两页社论正文及平台封面已阅读；末页尾段未作逐行转录。

**原文定位：**

- 原刊 678 页（PDF 2）：期刊史、计算机技术与考古实践。
- 原刊 679 页（PDF 3）：采集过程与数字解释的关系。

**可支持的论点：**

- 以期刊历史和湿筛等例子提醒读者：原始材料的采集决定后续分析能够利用的信息。

**限制与解释边界：**

- 社论中的历史案例和 AI 论述没有构成新的受控研究；早期计算机应用的历史事实应追查其引文原作。

**教材用途：** 作为编辑和课程背景阅读；不单独追加教材中的数据偏差警示。

**文件名／版本问题：** 未发现实质性文件名错误；著录以原文题名页为准。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1080%2F00934690.2025.2578591)：已读取父任务取得的 Crossref 原始记录，逐项核对 DOI 与本 PDF；属于出版社登记元数据，不能替代原文方法或结果。

### P41

Alec McLellan; Cora A. Woolsey. 2024. “Thematic Analysis of Indigenous Perspectives on Archaeology and Cultural Resource Management Industries.” *American Antiquity 89(2)*. 185–201。 DOI：[10.1017/aaq.2024.7](https://doi.org/10.1017/aaq.2024.7)。

**附件：** `McLellan 2024 Thematic Analysis of Indigenous Perspectives on Archaeology and Cultural Resource Management Industries.pdf`；17页；SHA-256：`0fb60d0ce12788cf8661b9d0df85cc0e4da283e403025bb0c2d6778870efe3b2`。

**日期与版本：** 在线日期：2024-04-01；年份依据：正式期刊卷年（PDF首页及DOI登记；与在线日期分别保存）。

**研究类型与本轮安排：** 原住民参与者关于考古与文化资源管理的定性访谈及主题分析；不是机器学习文本分类。本轮不增加正文，按以下用途保留。

**阅读范围：** 选择性原文核读：题名/摘要、引言开头、188页方法及190/198—199页相关讨论/资料声明。

**原文定位：**

- 印刷／文内188页；PDF第4页；参与者招募与方法；原PDF文本核读
- 印刷／文内199页；PDF第15页；Data Availability Statement；原PDF文本核读

**可支持的论点：**

- 资料访问、报告质量和项目合作条件影响文化遗产研究与社群参与。
- 作者因同意及保密条件不公开全部访谈，资料访问需按既定程序处理。

**限制与解释边界：**

- 直接联系和滚雪球招募不是概率抽样，不能据此估计所有原住民群体的观点比例。
- 共同设计软件是合作设想/建议，不能写成已通过实验验证的解决方案。

**教材用途：** 与P21一起作为第3章共享资料的延伸阅读，不改变本科入门章的结构。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1017%2Faaq.2024.7)：本轮取得的Crossref DOI登记记录已在本条核验对照PDF题名、作者及DOI；仅书目核对，不等于全文论断验证。

### P59

Menna Salah. 2026. “Algorithmic Memory: Towards Reflexive Authenticity in Cultural Heritage.” *AI & Antiquity: Journal of Teaching and Technology in Ancient Studies 2(1)*. 65–75。 DOI：[10.64946/aiantiquity.v2i1.004](https://doi.org/10.64946/aiantiquity.v2i1.004)。

**附件：** `Salah 2026 Algorithmic Memory.pdf`；11页；SHA-256：`6dfa4d0240b439732cd27992d3bcb54569dab606c470349353d4347e4fc9b0ff`。

**研究类型与本轮安排：** 文化遗产伦理／概念框架论文。本轮不增加正文，按以下用途保留。

**阅读范围：** 定向原文阅读：PDF 1、3、5、7、9 页；检查框架、平台举例和真实性论证。

**原文定位：**

- 原刊 67–69 页（PDF 3–5）：Europeana、Perseus、Mukurtu 等例子。
- 原刊 71–73 页（PDF 7–9）：合成叙事、真实性与审查。

**可支持的论点：**

- 提出以透明度、参与式策展和审查为核心的文化遗产真实性框架。

**限制与解释边界：**

- 概念框架，不是 AI 效果实验。
- 平台是否实施特定 AI 标注、具体资料量和功能描述尚未逐一核对原平台文档，不可当作已验证系统事实转写。
- 若需讨论其中某平台，应直接引用其官方项目文档或实证论文。

**教材用途：** 作为教师背景阅读，不为第一编新增框架名称或概念层次。

**文件名／版本问题：** 未发现实质性文件名错误；著录以原文题名页为准。

**独立书目或网站核查：**

- [核查来源1](https://ai-antiquity.org/index.php/ai/issue/view/volume2issue1)：已打开出版者正式卷期目录；核对作者、题名、页码及 DOI。

### P60

Robert Schon; Emma Blake; Meg Sneeringer. 2026. “A Letter from the Editors.” *American Journal of Archaeology 130(1)*. 1–4。 DOI：[10.1086/739393](https://doi.org/10.1086/739393)。

**附件：** `Schon 2025 American Journal of Archaeology.pdf`；4页；SHA-256：`988cacb5544077fc2722c03d061d079a6bd5ae89b51b67c3a816c25ba3a139ff`。

**研究类型与本轮安排：** 编辑来信／社论。本轮不增加正文，按以下用途保留。

**阅读范围：** 4 页社论文本已阅读，核对正文期刊信息及末页三位署名。

**原文定位：**

- 原刊 1–2 页：生成式写作与数据分析的区分及编辑关切。
- 原刊 3–4 页：期刊政策、作者责任及编辑立场。

**可支持的论点：**

- 以期刊编辑身份讨论 AI 生成文本、训练语料和考古学术出版中的责任。

**限制与解释边界：**

- 社论意见及某一时间的期刊政策讨论不能改写成通用法律规则或模型能力的实验结论。
- 有关模型训练范围、推理能力、环境代价的笼统说法不是本文新检验的技术事实；如用于教材需回查原始研究。

**教材用途：** 保留为学术出版立场的阅读材料；第 1 章不再叠加一般性警告。

**文件名／版本问题：** 文件名写 Schon 2025 American Journal of Archaeology，实际题名 A Letter from the Editors、年份 2026，并有 Emma Blake 和 Meg Sneeringer 两位共同作者。

**独立书目或网站核查：**

- 核查来源1：本轮书目信息来自上传 PDF 原文；未独立完成出版社网页核验，不标作网页已核实。

### P64

Robin Skeates. 2026. “Editorial: Rewriting archaeology with AI.” *Antiquity 100(413)*. 1191–1201（含两页卷首图；社论正文自 1193 页开始）。 DOI：[10.15184/aqy.2026.10415](https://doi.org/10.15184/aqy.2026.10415)。

**附件：** `Skeates 2026 Rewriting archaeology with AI.pdf`；11页；SHA-256：`7d75fc62a550e877d6c790c33a826413c85c1b239e2d8c309d600f7a10601bd1`。

**研究类型与本轮安排：** 社论／编辑实践反思。本轮不增加正文，按以下用途保留。

**阅读范围：** 定向原文阅读：PDF 1–3、5–11 页，覆盖编辑论证、案例引文和结论；没有逐项核查全部外部引文。

**原文定位：**

- 原刊 1193 页（PDF 3）：卷期、页码与 DOI。
- 原刊 1196–1197 页（PDF 6–7）：引文、学习与 AI 作者归因。
- 原刊 1199–1201 页（PDF 9–11）：编辑经验、公开说明和人类责任；署名日期 2026-10-01。

**可支持的论点：**

- 以考古期刊编辑实践讨论研究者在资料、写作和解释中的判断责任。
- 匿名稿件处理经验属于编辑叙述；文中另外提及的考古应用需要分别回到原始研究。

**限制与解释边界：**

- 不是 AI 能力的可外推基准测试；不同评审人的意见差异不等于因果验证。
- 第 1195 页把 Madanchian 与 Taherdoost（P37）写成 2026 年，而原论文是 2025 年，说明综述／社论引文也需核实。
- 书目范围含前置图版，不能把正文第一页 1193 误作整项起始页。

**教材用途：** 可作课程的近期阅读资源；用于书目线索，不代替其引用的原始方法与结果。

**文件名／版本问题：** 未发现实质性文件名错误；著录以原文题名页为准。

**独立书目或网站核查：**

- 核查来源1：本轮书目信息来自上传 PDF 原文；未独立完成出版社网页核验，不标作网页已核实。

### P65

Martina Tenzer; Giada Pistilli; Alex Brandsen; Alex Shenfield. 2024. “Debating AI in Archaeology: applications, implications, and ethical considerations.” *Internet Archaeology 67*. 第 67 期，文章 8；网页文章无正式连续印刷页码；上传简化版 PDF 10 页。 DOI：[10.11141/ia.67.8](https://doi.org/10.11141/ia.67.8)。

**附件：** `Tenzer 2024 Debating AI in archaeology- applications, implications and ethical considerations.pdf`；10页；SHA-256：`4eb34ba0c96ba43b30de072a4d1601bca5f6d14af2493f69fcbbeae94906f5b7`。

**研究类型与本轮安排：** 学术讨论／综述性观点论文。本轮不增加正文，按以下用途保留。

**阅读范围：** 定向原文阅读：PDF 1–3、5–7 页，对照文中章节编号定位；未访问所有外部交互内容。

**原文定位：**

- §2（PDF 2–3）：考古档案和自动信息抽取示例。
- §3（PDF 5–6）：训练资料、偏差与解释。
- §4（PDF 7）：学科合作和责任。

**可支持的论点：**

- 讨论 AI 利用考古档案的潜力及分类、偏差、人工劳动和伦理问题。

**限制与解释边界：**

- 综合讨论中提到的 AGNES 等具体系统的数字与发现为转引，应回查对应原始研究。
- 文中把部分分析形容为不依赖假设的说法不宜进入教材；分析对象、记录与分类的选择均需明确。
- 电子文章应按节号引证，不把上传 PDF 页码冒充原刊页码。
- Crossref 登记作者列表把机构混入作者，并将原文 Alex Brandsen 拼作 Alex Bransden；此处以原文实际署名为准，不机械复制登记字段。

**教材用途：** 保留为考古 AI 的批判性入门阅读；当前有限正文修订不新增其概念框架。

**文件名／版本问题：** 未发现实质性文件名错误；著录以原文题名页为准。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.11141%2Fia.67.8)：已读取父任务取得的 Crossref 原始记录，逐项核对 DOI 与本 PDF；属于出版社登记元数据，不能替代原文方法或结果。

### P66

Athena Trakadas. 2026. “AI-Generated Content and Publication of Maritime Archaeological Research.” *International Journal of Nautical Archaeology 55(1)*. 1–3；上传件含平台封面共 4 页。 DOI：[10.1080/10572414.2026.2662170](https://doi.org/10.1080/10572414.2026.2662170)。

**附件：** `Trakadas 2026 AI-generated content and publication of maritime archaeological research.pdf`；4页；SHA-256：`25ca94b14f63c8a36d38544160d481c6350a407ff375c72f68d7d0a822f49eb0`。

**研究类型与本轮安排：** 社论／期刊政策讨论。本轮不增加正文，按以下用途保留。

**阅读范围：** 定向原文阅读：平台封面及原刊 1–2 页（PDF 1–3）；未逐行检查末页全部内容。

**原文定位：**

- 平台封面：题名、作者、卷期、1–3 页、DOI；标明 online 2026-05-13。
- 原刊 1–2 页：学术语言和出版责任；第 2 页引述当时期刊政策。

**可支持的论点：**

- 从水下／海事考古期刊编辑角度讨论语言辅助、生成式内容、作者责任和政策。

**限制与解释边界：**

- 社论和特定期刊政策记录不是模型性能实验，也不能直接用作所有期刊的统一规则。
- Crossref 记录的出版日期为 2026-01-02，上传平台封面写在线日期 2026-05-13；不混作同一日期，年份 2026 一致。
- 若向作者提供现行投稿指导，需要另查该期刊当前官方政策；本轮不作这种时效性指导。

**教材用途：** 作为学术出版讨论的延伸阅读，无需在第一编再增加一般性警告。

**文件名／版本问题：** 未发现实质性文件名错误；著录以原文题名页为准。

**独立书目或网站核查：**

- [核查来源1](https://api.crossref.org/works/10.1080%2F10572414.2026.2662170)：已读取父任务取得的 Crossref 原始记录，逐项核对 DOI 与本 PDF；属于出版社登记元数据，不能替代原文方法或结果。
