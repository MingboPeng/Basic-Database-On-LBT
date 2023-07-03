# Basic-Database-On-LBT

欢迎！

此仓库主要储存执行Ladybug、Honeybee-Energy、Honeybee-Radiance、Dragonfly时必不可少的可复用参数信息。  

它可以是Program Type、Loads、Schedule、Construction-Set、Construction、Modifie Set以及Modifie等复用率较高的内容。  也可以是明确了来源和具体使用范围的气象数据文件（.EPW File）及设计日文件（.DDY File）。

# 前言

在建筑节能设计中，如果根据不同地区的气候条件进行合理的节能设计，则可以有效地提高建筑能效，减少能源消耗，所以不同的地区会采用不同的节能措施，并且对于相关节能技术的主要技术指标，不同地区标准中的参考和限定数值也会有所不同。例如，寒冷地区的气温较低，采暖季较长，节能设计侧重点也是保温隔热、冬季供暖以及减少能源消耗，建筑需要采用高效保温材料、采暖设备的效率要求高等等，所以在相关地区的节能设计规范或标注中，建筑围护的传热系数规定通常会以一个较低的数值进行限制，以达到最低限度的建筑节能需求。

我国现行的国家及地方节能设计规范众多，根据《公共建筑节能设计标准》GB50189-2015的规定，建筑节能气候分区主要划分为严寒、寒冷、夏热冬冷、夏热冬暖以及温和地区5个区域。其中又因我国各省份幅员辽阔，同一地区的气候可能会出现些许差别，故又在5个节能气候分区的基础上又分为A、B、C区。不仅如此，对于不同的建筑，对节能设计的要求与侧重点也是不一样的。例如在节能设计中，通常将建筑的类型分为居住建筑、公共建筑和工业建筑三大类，每一种类型的建筑都又会有独立的要求。

由于这些因素，导致我国的节能设计规范、标准以及相关指导文件五花八门，能让人眼花缭乱，沉没在信息的海洋，也导致了行业模块化、数字化的标准化信息得不到有效的搜集，对于更能够利用新技术充当效率武器的绿色建筑与节能工程师来说，在工作的进程中如没有长时间的积累，重复的工作和枯燥的信息搜集工作会降低工程师的工作幸福感。

近年，正在开展行业规范的瘦身行动，例如在现行的《建筑节能与可再生能源利用通用规范》GB55015-2021中，统一规范了各建筑类型在不同建筑节能气候分区下的围护结构热工性能等信息，进一步集中并废止了此前了五花八门的部分标准规定。

可以通过行业变革的这个契机，通过Ladybug Tools这个模块化、参数化的工具来进行标准化的信息搜集，并通过开源的形式公布给所有行业的学生、教师、工程师等，促进行业的交流以及信息化的发展。

# 预计更新计划

由于我个人经历和能力有限，所以目前仅承诺在空闲时间中更新如下内容：

- [x] ~~符合《建筑节能与可再生能源利用通用规范》GB55015-2021 附录 C 的 Program Type~~
- [x] ~~符合《民用建筑绿色性能计算标准》JGJ/T 449-2018 附录 C 的 Program Type（除居住建筑）~~
- [ ] 符合《近零能耗建筑技术标准》JGJ/T 449-2018 附录 A 的 Program Type

期望有人来进行这些内容的补充

- [ ] 符合《建筑围护结构节能工程做法及数据》09J908-3 的标准做法的 Construction
- [ ] 符合《民用建筑供暖通风与空气调节设计规范》GB 50736-2012 的 Design Day
- [ ] 符合《建筑节能与可再生能源利用通用规范》GB55015-2021 3.1 建筑和围护结构规定的 Construction Set
