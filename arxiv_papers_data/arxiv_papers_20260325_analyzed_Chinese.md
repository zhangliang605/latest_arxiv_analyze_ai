# 20260325
[![Subscribe_Visitors](https://visitor-badge.laobi.icu/badge?page_id=nituchao.latest_arxiv_analyze_ai_rss)](https://github.com/nituchao/latest_arxiv_analyze_ai)

## 1. `cs.AI` - 我，我自己和π：评估和解释大语言模型的内省能力 [PDF](https://arxiv.org/pdf/2603.20276), [HTML](https://arxiv.org/abs/2603.20276)
### Authors
Atharv Naphade,Samarth Bhargav,Sean Lim,Mcnair Shah
### Background
人类智能的一个重要特征是反省能力，即评估和推理自身认知过程的能力。大语言模型（LLMs）中这种反省能力正在成为一种有前景但也存在争议的能力。目前的评估往往无法区分真正的元认知与一般世界知识的应用或基于文本的自我模拟。
### Innovation
该论文提出了一种原则性的分类法，将反省能力形式化为模型策略和参数上特定操作的潜在计算。为了隔离通用反省的组成部分，论文提出了用于严格能力测试的综合性评估套件——内省基准(Introspect-Bench)。研究发现，领先模型在预测自身行为时表现出对自身策略的优先访问，超越同行模型。此外，论文提供了因果性、机制性的证据，解释了LLMs是如何在无明确训练的情况下学习反省能力的，以及反省机制是如何通过注意力扩散产生的。
### Conclusion
研究结果表明，前沿的模型在预测自身行为时对自身策略具有优先访问权，并且填补了从无明确训练到具备内省能力之间的知识空白，通过注意力扩散机制来理解反省的计算基础。
## 2. `cs.AI` - FactorSmith：基于马尔可夫决策过程分解与规划者-设计师-批评者细化的有代理人模拟生成 [PDF](https://arxiv.org/pdf/2603.20270), [HTML](https://arxiv.org/abs/2603.20270)
### Authors
Ali Shamsaddinlou,Morteza NourelahiAlamdari
### Background
从自然语言规范生成可执行模拟仍然是一个具有挑战性的问题，因为大型语言模型（LLMs）在面对大量互联代码库时的推理能力有限。FactorSmith框架通过结合两种互补的理念，即有因素部分可观测马尔可夫决策过程（POMDP）分解进行有原则的上下文缩减和层级规划者-设计师-批评者有代理人工作流，逐步迭代质量改进，解决了这一问题。
### Innovation
FactorSmith提出了一种方法，该方法利用有因素部分可观测马尔可夫决策过程（POMDP）表示法，分解模拟规范为可操作模块步骤，每个步骤仅处理最小相关的状态变量子集，从而限制任何单一LLM调用必须处理的上下文窗口。此外，FactorSmith嵌入每个有因素步骤中的三个代理人的交互：规划者协调工作流程，设计师提出代码实体，批评者通过结构化评分评估质量，实现迭代细化和恢复。
### Conclusion
FactorSmith在PyGame学习环境基准测试中生成了与非有代理人因素为基础的基线相比，改进了提示对齐、减少了运行时错误和提高了代码质量的模拟。
## 3. `cs.AI` - 利用自然语言处理和机器学习进行数据稀缺地区的基于证据的粮食安全政策决策 [PDF](https://arxiv.org/pdf/2603.20425), [HTML](https://arxiv.org/abs/2603.20425)
### Authors
Karan Kumar Singh,Nikita Gajbhiye
### Background
在数据稀缺地区制定粮食安全政策仍然是一个关键挑战，由于受限的结构化数据集、分散的文本报告和决策系统中的人口统计偏差。
### Innovation
提出了一种名为ZeroHungerAI的集成自然语言处理（NLP）和机器学习（ML）框架，用于在极端数据稀缺条件下进行基于证据的粮食安全政策建模。该系统结合了结构化的社会经济指标和上下文政策文本嵌入，使用基于DistilBERT的迁移学习架构。实验表明，系统在一种包含25个地区1200样本的混合数据集上展示了优越的预测性能，分类准确率达到91%，精确度为0.89，召回率为0.85，F1分为0.86，并在不平衡条件下表现出色。与传统的支持向量机（SVM）和逻辑回归模型相比，性能分别提高了13%和17%。公平优化减少了人口统计偏差差异至3%，确保了农村和城市政策推理的公平性。
### Conclusion
实验结果证实，基于变换器的上下文学习显著增强了低资源治理环境下的政策智能，使饥饿预测系统具备了可扩展性和公平性。
## 4. `cs.AI` - AgentComm-Bench: Stress-Testing Cooperative Embodied AI Under Latency, Packet Loss, and Bandwidth Collapse [PDF](https://arxiv.org/pdf/2603.20285), [HTML](https://arxiv.org/abs/2603.20285)
### Authors
Aayam Bansal,Ishaan Gangwani
### Background
当前，协同多代理方法在具身人工智领域大多在理想化的通信环境下评估，即没有延迟、没有数据包丢失且带宽无限。但在实际环境中，如机器人、自主车辆和无人机等无线通信的操控下，面临的是更加严苛的通信条件。因此，迫切需要一个能够系统测试这些系统在各种通信缺陷情况下的性能的基准套件。
### Innovation
提出了AgentComm-Bench，这是一个基准套件和评估协议，用于系统性地测试协同具身AI在六种通信缺陷维度下的表现：延迟、数据包丢失、带宽受限、异步更新、老化内存和冲突传感器数据。该基准涵盖了三个任务家族：协同感知、多代理路径导航和协同区域搜索，并评估了五种通信策略，包括一个基于冗余消息编码与老化感知融合的减轻方法。
### Conclusion
实验结果表明，依赖于通信的任务表现急剧下降：老化内存和带宽受限分别导致导航效率超过96%的下降，而内容篡改（老化或冲突数据）则将感知F1分数降低了超过85%。通信缺陷的脆弱性取决于缺陷类型与任务设计的相互作用。冗余消息编码在80%的数据包丢失条件下将导航性能提高了超过一倍。研究团队建议在报道协作具身AI工作的实验结果时，报告在多种缺陷条件下的性能。
## 5. `cs.AI` - LLM-增强能量对比学习在文本属性图中检测异常分布 [PDF](https://arxiv.org/pdf/2603.20293), [HTML](https://arxiv.org/abs/2603.20293)
### Authors
Xiaoxu Ma,Dong Li,Minglai Shao,Xintao Wu,Chen Zhao
### Background
文本属性图是节点具有文本属性的图，被广泛用于表示引用、社交和交易网络等实际网络。然而，现有的图学习方法经常假设训练数据和测试数据的分布一致，这在面对异常分布数据（OOD数据）时会导致性能显著下降。
### Innovation
本文提出了一种名为 LLM-增强能量对比学习 (LECT) 的新方法，该方法结合了大型语言模型 (LLM) 和能量对比学习。LECT 通过利用 LLM 的语义理解和上下文知识生成高质量的伪 OOD 节点来生成 OOD 样本，并基于能量函数应用对比学习来区分在分布 (IND) 节点和 OOD 节点。
### Conclusion
在六个基准数据集上的广泛实验证明，LECT 方法在分类准确性和鲁棒 OOD 检测能力方面都优于现有的最佳基线方法。
## 6. `cs.AI` - 从临床笔记中在相互依赖约束下进行结构化数据提取的深度反思推理在数字医疗中的应用 [PDF](https://arxiv.org/pdf/2603.20435), [HTML](https://arxiv.org/abs/2603.20435)
### Authors
Jingwei Huang,Kuroush Nezafati,Zhikai Chi,Ruichen Rong,Colin Treager,Tingyi Wanyan,Yueshuang Xu,Xiaowei Zhan,Patrick Leavey,Guanghua Xiao,Wenqi Shi,Yang Xie
### Background
从临床笔记中提取结构化信息需要处理复杂的逻辑依赖关系，现有基于大型语言模型（LLM）的提取流水线难以捕捉这些依赖性，导致临床不一致的输出。
### Innovation
提出了一种深层反思推理（深思推理）的大语言模型代理框架，该框架通过检查变量之间、输入文本以及检索到的领域知识的一致性，迭代地自我批判和修订结构化输出，直至输出收敛。该方法在三个不同的肿瘤学应用中得到了广泛评价。
### Conclusion
实证结果表明，深度反思推理能够系统地提高LLM在处理相互依赖约束下的结构化数据提取的可靠性，生成更加一致的机器可操作的临床数据集，并促进使用机器学习和数据科学进行知识发现，以推动数字健康的发展。
## 7. `cs.AI` - 通过即插即用预测器构建领域专门化的树形思维 [PDF](https://arxiv.org/pdf/2603.20267), [HTML](https://arxiv.org/abs/2603.20267)
### Authors
Xuanqi Gao,Haoyu Wang,Jun Sun,Shiqing Ma,Chao Shen
### Background
大型语言模型（LLMs）在复杂推理方面取得了显著进展，然而常用的树形思维（ToT）框架在探索深度和计算效率之间存在权衡。现有的ToT实现往往依赖于基于LLM的自评估或严格的启发式算法进行分支修剪，这使得它们在广泛的应用中过于昂贵且缺乏灵活性。
### Innovation
本文提出了一种灵活的、即插即用的预测器（DST），它作为一个轻量级、监督的启发式算法，用于指导ToT搜索过程。该预测器实现了动态、上下文相关的修剪，使得在简单的推理步骤中可以近乎贪心地高效进行搜索，并在遇到不确定性或任务复杂性时才适当地扩展搜索光束。
### Conclusion
通过在数学推理、通用推理和复杂的逻辑推理等多种基准测试上的实验，我们证明了该方法在与强大的基线方法（包括标准ToT）相比时，实现了相当的或更优异的准确率，同时将计算开销减少了26%到75%。我们的工作成功解决了树形推理中的准确性和效率之间的权衡问题，将ToT从一项资源密集型的技术转变为了复杂问题求解中可扩展且实用的范式。
## 8. `cs.AI` - AgenticGEO：一种生成引擎优化的自演化代理系统 [PDF](https://arxiv.org/pdf/2603.20213), [HTML](https://arxiv.org/abs/2603.20213)
### Authors
Jiaqi Yuan,Jialu Wang,Zihan Wang,Qingyun Sun,Ruijie Wang,Jianxin Li
### Background
生成式搜索引擎代表了从传统的基于排名的检索向基于大型语言模型（LLM）的合成的转变，改变了优化目标从排名优先性转向内容包容性。生成引擎优化（GEO）具体旨在通过战略性地操纵源内容来最大化在黑盒摘要输出中的可见性和归因。现有的方法依赖于静态启发式、单一提示优化或容易过拟合的引擎偏好规则推断。这些方法不能灵活适应各种内容或生成引擎行为的变化，而且有效优化这些策略需要无法实践的交互反馈量。
### Innovation
我们提出了AgenticGEO，一个自进化的代理框架，将优化建模为内容条件下的控制问题，以增强内在内容质量并能够适应黑盒引擎的不可预测行为。AgenticGEO采用MAP-Elites档案来进化多样且组合化的策略，减轻了交互成本。同时引入了Co-Evolving Critic，一个轻量级的代理，可以近似模型反馈，用于选择和细化内容特定的策略，有效地指导进化搜索和推理时的规划。
### Conclusion
通过在两个代表性引擎上进行大量的领域内和跨领域的实验，AgenticGEO在三个数据集上优于14个基准模型，达到了最先进的性能，并证明了其稳健的可迁移性。
## 9. `cs.AI` - 内存投毒攻击与安全多智能体系统 [PDF](https://arxiv.org/pdf/2603.20357), [HTML](https://arxiv.org/abs/2603.20357)
### Authors
Vicenç Torra,Maria Bras-Amorós
### Background
近年来，针对具有自主性和多智能体系统的内存投毒攻击引起了关注。这在很大程度上归因于大型语言模型 (LLMs) 促进了代理的构建和部署。当前，正在使用不同类型的内存系统，如语义记忆、情景记忆和短期记忆。这些不同类型的内存系统根据其持续时间、起源和定位进行区分。短期记忆来源于用户的末端并分布在不同智能体中，而长期稳定的记忆则定位在成熟的知识数据库中。
### Innovation
本文首先介绍了主要的内存系统类型，然后讨论了在这些不同类型的内存系统中发生内存投毒攻击的可行性，并提出了缓解策略。还提出了基于私有知识检索的局部推断作为缓解语义记忆投毒的一种策略。本文还强调了代理间交互引起的实际风险，这些风险在文献中关注较少，且具有一定的难以定型和解决的特点。
### Conclusion
本文为设计时就具备安全性的智能体做出了贡献。
## 10. `cs.AI` - WebNavigator：基于交互图检索的全局网页导航 [PDF](https://arxiv.org/pdf/2603.20366), [HTML](https://arxiv.org/abs/2603.20366)
### Authors
Xuanwang Zhang,Yuteng Han,Jinnan Qi,Mulong Xie,Zhen Wu,Xinyu Dai
### Background
尽管自主网页导航取得了重大进展，但现有的方法在复杂网页环境中的表现仍远低于人类水平。这种限制来自于拓扑盲性，即代理仅通过试错方式探索而无法访问环境的全局拓扑结构。
### Innovation
提出了一种名为WebNavigator的方法，将网页导航重新定义为确定性的检索和路径查找，而非概率性探索。WebNavigator通过零成本启发式探索离线构建交互图，并在线实施检索-推理-远程迁移的工作流?
### Conclusion
WebNavigator在WebArena和OnlineMind2Web上实现了最先进的性能。在WebArena多站点任务中，WebNavigator的成功率达到72.9%，远超企业级代理的表现。这项工作揭示了拓扑盲性而非模型推理能力是自主网页导航的未被重视的瓶颈。
## 11. `cs.AI` - SymCircuit: 通过熵正则化强化学习实现可计算概率电路的贝叶斯结构推理 [PDF](https://arxiv.org/pdf/2603.20392), [HTML](https://arxiv.org/abs/2603.20392)
### Authors
Y. Sungtaek Ju
### Background
概率电路（PC）结构学习受到贪婪算法的困扰，这些算法作出不可逆的、局部最优的决策。现有方法存在的问题是决策过程不可逆且局部最优。
### Innovation
提出了SymCircuit，采用熵正则化强化学习替换贪婪搜索，训练一个生成性策略，通过贝叶斯后验获得最优策略，并通过语法约束的自回归Transformer实现有效的电路生成。此外，还提出了选项级REINFORCE，降低了噪音，显著提高了样本效率。
### Conclusion
SymCircuit方法在NLTCS数据集上弥补了93%与LearnSPN的差距，初步结果表明该方法在Plants数据集（69变量）上具有可扩展性。
## 12. `cs.AI` - 压缩是唯一的需要：建模数学 [PDF](https://arxiv.org/pdf/2603.20396), [HTML](https://arxiv.org/abs/2603.20396)
### Authors
Vitaly Aksenov,Eve Bodnia,Michael H. Freedman,Michael Mulligan
### Background
人类数学(HM)是人类发现并认可的数学，这是形式数学(FM)中的一个极为狭小的子集。形式数学包含所有的有效推导结果。本文通过探讨数学定义和定理之间的层次嵌套关系，使用代数中的半群(monoids)模型来分析这一现象。文章指出，在自由阿贝尔半群$A_n$中，稀疏的宏集可实现指数级的表达能力扩展。而在自由非阿贝尔半群$F_n$中，即使密度较高的宏集也仅能实现线性扩展，只有接近最大密度的宏集才能实现超线性扩展。研究者使用一个大型的Lean 4数学库MathLib作为替代的人类数学中的数学发现，发现未展开长度（即展开后最基础的符号数量）与深度和包装长度均呈指数增长，而包装长度在整个深度范围都是近似恒定的。这对Free Abelian Monoid $A_n$的模型表示支持，却不支持Free Non-Abelian Monoid $F_n$的模型。
### Innovation
文章提出了使用自由阿贝尔半群和自由非阿贝尔半群来建模数学公式和定义的方法，揭示了压缩（即通过定义和定理来减少表达式的复杂性）在人类数学发现中的关键作用，并通过具体实验数据验证了这一观点。此外，文章还讨论了如何通过依赖图的压缩度量和类似PageRank的分析方法来量化数学兴趣，并指导自动化推理系统更加有效地专注于更具压缩性的区域。
### Conclusion
研究表明，人类数学专注于一个随着空间整体规模呈指数增长的多项式增长子集。数学中的压缩机制，特别是通过定义和定理的层次嵌套，在实现这种压缩方面起着关键作用。这种理解有助于进一步探索数学结构的本质，指导自动化推理系统的开发，并可能对数学教育和研究产生深远影响。
## 13. `cs.AI` - 在不同空间中思考：特定领域的潜在几何结构在跨架构转换中幸存 [PDF](https://arxiv.org/pdf/2603.20406), [HTML](https://arxiv.org/abs/2603.20406)
### Authors
Marcus Armstrong,Navid Ayoobi,Arjun Mukherjee
### Background
研究独立训练的语言模型是否能够趋于几何兼容的潜在表示，并探讨这种兼容性是否能在推断时不更新权重的情况下纠正模型行为。
### Innovation
开发了一种线性投影矩阵，该矩阵能够将大型教师模型的激活向量映射到较小的学生模型的坐标系统中，通过替换学生模型的内部状态为翻译后的教师表示，实现生成过程中对学生残差流的干预。
### Conclusion
研究发现几何对齐质量与行为修正率之间几乎没有相关性，干预强度对架构特定，不同领域的学生模型表现出不同的敏感性，总是在迁移时出现灾难性崩溃，证明了领域特定的子空间几何构形是语言模型的普遍性质。
## 14. `cs.AI` - 测量中具有可扩展精度描述不确定性的全面框架 [PDF](https://arxiv.org/pdf/2603.20365), [HTML](https://arxiv.org/abs/2603.20365)
### Authors
Ali Darijani,Jürgen Beyerer,Zahra Sadat Hajseyed Nasrollah,Luisa Hoffmann,Michael Heizmann
### Background
概率论已成为各科学和技术领域衡量不确定性的主要框架，特别是在测量和控制系统中。然而，过于依赖简单的高斯假设（尤其是在控制理论、制造和测量系统中），会导致对复杂现象的不完整且多阶段损失性近似表示，特别是在多阶段过程中不确定性传播方面不准确。
### Innovation
本文提出了一种全面且计算上可行的框架，用于使用概率密度函数（PDF）表征和传播测量系统中的定量属性。文章提倡使用高斯混合模型（GMMs），这是一种可调化的PDF近似模型，能够在精度、内存和计算之间进行权衡，并且在数学和计算上能够实现高性能和许多情况下可以提供封闭形式的解决方案。
### Conclusion
论文在制造和测量应用场景，特别是在圆型工厂中展示了GMMs框架的有效性，该框架支持精确的不确定性表征和传播，并且在许多情况下能够保持计算的可行性，同时提高了准确性，超过传统的高斯框架。
## 15. `cs.AI` - 自然语言处理过程中意义生产的机制 [PDF](https://arxiv.org/pdf/2603.20381), [HTML](https://arxiv.org/abs/2603.20381)
### Authors
Christopher J. Agostino,Quan Le Thien,Nayan D'Souza,Louis van der Elst
### Background
理解自然语言处理过程中产生意义的基本机制是设计安全、体贴、吸引人和赋权的人工智能交互的关键。认知科学和社交心理学中的实验表明，人类的意义处理更多地遵循量子逻辑机制而不是经典的布尔理论。最近在大规模语言模型中发现类似结果的实验显示，对含糊表达的理解中存在着明显违反贝尔不等式的上下文现象。
### Innovation
研究了从四数量级规模跨度的模型中CHSH $|S|$参数——与不等式相关的度量——的变化，并将其与MMLU、幻觉率和无意义检测基准进行交叉参考。发现$|S|$分布在四分位范围统计量最明显地区分了不同模型，这一统计量完全与所有外部基准正交，而违反率与所有三个基准间存在轻微的负相关但并不显著。进一步探讨了$|S|$如何随采样参数和单词顺序变化，并讨论了信息论约束对提示注入防御及其人工效用的影响，强调了构建和维护大量社交上下文的必要性，这种影响比获得同意更重要，是一种更微妙和基本的操纵形式，能在具体解释出现前塑造可能的解释空间。
### Conclusion
在不同的语言模型参数范围内，CHSH $|S|$参数的分布统计量在区分模型方面最显著，且这一统计量与外部基准始终保持正交。而违反率与基准之间有轻微的负相关但不显著。还需要进一步研究$|S|$随采样参数和单词顺序的变化，这将对提示注入防御及其人工效用产生重大影响，强调了社交上下文的构建与维护在大批量处理中的重要性。
## 16. `cs.AI` - Meta-Learning for Repeated Bayesian Persuasion [PDF](https://arxiv.org/pdf/2603.20408), [HTML](https://arxiv.org/abs/2603.20408)
### Authors
Ata Poyraz Turna,Asrin Efe Yorulmaz,Tamer Başar
### Background
经典贝叶斯说服理论研究如何在单一战略互动中通过精心设计的信号策略影响接收者。然而，在许多实际环境中，这样的互动会跨越多个博弈重复发生，这为利用任务结构相似性提供了机会。本研究引入了元说服算法，这是在在线贝叶斯说服（OBP）和马尔可夫说服过程（MPP）框架下的首次理论成果，涵盖了完全反馈和臂反馈设置。
### Innovation
该研究提出了元说服算法，这在OBP和MPP框架下首次建立了理论成果。这些算法在自然任务相似性概念下证明了更尖锐的遗憾率，并优于OBP和MPP的最佳已知收敛率。同时，当游戏序列被任意选择时，它们恢复了单一游戏的保证。
### Conclusion
此外，我们通过数值实验补充了我们的理论分析，突出了遗憾率的改进以及在重复说服环境中的元学习优势。
## 17. `cs.AI` - 代理中的ALARA原则：通过便携式可组合多代理团队实现最低权限上下文工程 [PDF](https://arxiv.org/pdf/2603.20380), [HTML](https://arxiv.org/abs/2603.20380)
### Authors
Christopher J. Agostino,Nayan D'Souza
### Background
工业从业者和学术研究人员经常使用多代理系统来加速工作，但这些系统运行的框架缺乏一种简单且统一的机制来规模性管理代理的核心方面，这影响了个人与代理之间的互动质量以及从业者协调达成共同目标的能力。代理框架已经支持了更加复杂的多代理系统，但定义这些代理能做什么的行为规范仍分散在文本指令文件、框架内部配置以及分离于个体代理定义的机制（如MCP服务器）中，这使得这些规范难以共享、版本管理和团队协作维护。
### Innovation
作者引入了一个声明式的上下文-代理-工具(CAT)数据层，通过相互关联的文件来确定每个代理工具访问权限及其上下文的最小要求。并开发了名为npcsh的命令行界面来执行这些文件。这种系统结构化解析和实施这些文件，使得修改代理工具列表会保证带来行为变化，而不是模型可能或可能不遵循的建议。
### Conclusion
作者评估了22个本地托管的模型，参数量从0.6B到35B，覆盖了115个实际任务，包括文件操作、网络搜索、多步骤脚本编写、工具链和多代理委托。通过这些任务，作者描述了哪些模型家族在哪些任务范畴内表现良好，在$rlap{约}{raisebox{0.35cm}{2500}}$次执行中哪里表现不佳。
## 18. `cs.AI` - Leum-VL技术报告 [PDF](https://arxiv.org/pdf/2603.20354), [HTML](https://arxiv.org/abs/2603.20354)
### Authors
Yuxuan He,Chaiming Huang,Yifan Wu,Hongjun Wang,Chenkui Shen,Jifan Zhang,Long Li
### Background
当前的多模态模型在解析和生成视频中的注意力组织方面存在局限性，虽然可以描述场景、回答基于事件的问题和阅读屏幕上的文字，但对于基于时间轴的单元，如钩子、剪辑理由、镜头带来的紧张感以及面向平台的包装提示等识别度较低。因此，论文提出了一种名为SV6D（六维度结构视频）的表征框架，该框架将互联网原生视频分解为六个互补的结构维度：主体、审美、摄像语言、编辑、叙事和传播，每个标签都与时间线上可观察的证据相关联。此外，还通过验证的强化学习进一步完善了基于感知任务的框架，实现了结构化目标并通过专家驱动的后训练管道实现了Leum-VL-8B视频语言模型。
### Innovation
SV6D框架通过对视频进行六维结构分解（主体、审美、摄像语言、编辑、叙事和传播），并结合匈牙利匹配的时间错配、维度语义标签距离和质量正则化，实现了一种统一的优化目标。该模型在VideoMME（无字幕）、MVBench和MotionBench等任务上取得了70.8、70.0和61.6的分数，同时在一般多模态评估任务（如MMBench-EN）上仍保持竞争力。还提出了FeedBench作为结构敏感短视频理解的基准，结果表明视频AI中缺失的层不是像素生成而是结构表示。
### Conclusion
Leum-VL-8B视频语言模型通过专家驱动的后训练管道实现了SV6D提出的结构化目标，并通过验证的强化学习进一步优化。该模型实现了多个视频理解任务上的良好性能，并表明视频AI的关键挑战在于结构表示而不仅仅是像素生成。
## 19. `cs.AI` - PA3：通过思维链增强政策意识的代理对齐 [PDF](https://arxiv.org/pdf/2603.14602), [HTML](https://arxiv.org/abs/2603.14602)
### Authors
Shubhashis Roy Dipta,Daniel Bis,Kun Zhou,Lichao Wang,Benjamin Z. Yao,Chenlei Guo,Ruhi Sarikaya
### Background
大语言模型（LLMs）在工具使用任务中表现出色，但在遵循复杂的、特定于企业的规则时存在问题。尽管模型可以理解所提供的业务规则，并在上下文中推理，但将所有政策包含在每个查询中会增加延时并浪费计算资源。此外，长长的提示会导致长的上下文，这会因为“针在干草堆中”的问题而损害整体性能。
### Innovation
提出了一种多阶段对齐方法，该方法在推理时教会模型回忆和应用相关业务政策，而不包括完整的业务政策在上下文中。同时，引入了一种基于Jaccard得分的PolicyRecall奖励和一种Hallucination惩罚用于GRPO训练。
### Conclusion
我们的最佳模型在基准测试中表现优于16个点，并且相比相同模型大小的类似in-context基准提高了3个点的性能，同时使用了40%更少的单词。
## 20. `cs.AI` - 大型物联网网络的基于深度学习的智能IDS [PDF](https://arxiv.org/pdf/2603.16342), [HTML](https://arxiv.org/abs/2603.16342)
### Authors
Isha Andrade,Shalaka S Mahadik,Mithun Mukherjee,Pranav M Pawar,Raja Muthalagu
### Background
随着大规模物联网网络的普及，它不仅改变了组织的运作方式，提高了自动化流程的效率，简化了我们的日常生活，同时也增加了安全风险，因为未经授权的设备可能通过入侵这些网络并利用现有弱点进行特定攻击类型来获取网络访问权。
### Innovation
提出了一种基于卷积神经网络（CNN）的入侵检测系统（IDS）和一种基于长短期记忆（LSTM）的IDS，并通过CICIoT2023数据集评估了基于深度学习的这两个智能IDS的性能。采用深度学习的智能IDS能够使用二分类、分组和多分类来识别和分类各种网络威胁。
### Conclusion
提出基于卷积神经网络的IDS在二分类、分组和多分类中的准确率分别是99.34%、99.02%和98.6%；基于长短期记忆的IDS的准确率分别是99.42%、99.13%和98.68%。
## 21. `cs.AI` - MHPO: 调制感知风险的策略优化方法以增强强化学习的稳定性 [PDF](https://arxiv.org/pdf/2603.16929), [HTML](https://arxiv.org/abs/2603.16929)
### Authors
Hongjun Wang,Wei Liu,Weibo Gu,Xing Sun,Kai Han
### Background
Group Relative Policy Optimization（GRPO）等基于框架的训练稳定调节其重要性比率至关重要，但现有的比率控制方法，如硬限制，存在非可微边界和梯度消失区域的问题，无法保持梯度的连续性。此外，这些方法缺乏风险意识机制来适应性地抑制极端偏差，使优化过程中容易遭受突然的策略变化。
### Innovation
我们提出了新颖的调制感知风险策略优化方法（MHPO），其引入了一种日志忠实度调制器（LFM），将无界的重要性比率映射到一个有界、可微的领域，防止高方差异常令牌导致损失景观的不稳定，同时确保全局梯度稳定性。此外，引入的解耦风险惩罚（DHP）利用生存分析中的累积风险函数独立调节积极和消极策略变化。通过使用感知风险的惩罚来塑造优化景观，MHPO实现了对非对称策略变化的精细调节，同时缓解了过度扩展导致的模式崩溃和灾难收缩导致的策略侵蚀。
### Conclusion
MHPO在各类基于文本和视觉语言的任务的推理基准测试中被广泛评估，结果表明，该方法在保持训练稳定性的基础上，优于现有方法，具有更优的性能。
## 22. `cs.AI` - 大型奖励模型：基于视觉语言模型的通用在线机器人奖励生成 [PDF](https://arxiv.org/pdf/2603.16065), [HTML](https://arxiv.org/abs/2603.16065)
### Authors
Yanru Wu,Weiduo Yuan,Ang Qi,Vitor Guizilini,Jiageng Mao,Yue Wang
### Background
强化学习（RL）在改善机器人的操作策略方面展现出巨大潜力，但其效果受限于设计通用奖励函数的难度。
### Innovation
提出了一种框架，通过将基础视觉语言模型（VLMs）适应为在线奖励生成器，实现在线策略优化。该模型基于一个大型多源数据集，包含真实机器人轨迹、人机互动和多样化模拟环境数据进行训练。该方法利用VLM生成基于当前视觉观察的多维度奖励信号，并通过初始化的仿生学习（IL）策略引导模型在闭环中纠正亚优行为，无需对整个轨迹进行事后评估。
### Conclusion
实验结果显示，该方法在30个RL迭代内显著提高了初始IL策略的成功率，展示了极高的样本效率。这表明，基于VLM生成的信号可以为解决执行错误提供可靠的反馈，有效避免了手动奖励工程的需求，促进了机器人学习的高效在线优化。
## 23. `cs.AI` - 推理密集型检索代理的计算分配 [PDF](https://arxiv.org/pdf/2603.14635), [HTML](https://arxiv.org/abs/2603.14635)
### Authors
Sreeja Apparaju,Nilesh Gupta
### Background
随着代理的长期操作，其记忆存储不断增强，使得信息检索变得至关重要。许多代理查询需要进行推理密集型检索，其中查询和相关文档之间的联系需要推理来加以桥接。现有的基于大语言模型（LLM）增强的流水线方法通过查询扩展和候选重排序解决了这一问题，但这些方法引入了显著的推理成本。本研究通过BRIGHT基准和Gemini 2.5模型家族，研究了推理密集型检索流水线中的计算分配问题。
### Innovation
该研究通过BRIGHT基准和Gemini 2.5模型家族，分析了计算资源在查询扩展和候选重排序阶段的不同分配方式，发现重排序从强大模型和更深层候选池中受益显著，而查询扩展在较强模型中仅表现出轻微增益。同时，推理时长在两个阶段中的改进效果并不明显。
### Conclusion
计算资源应集中于重排序阶段，而不是均匀分配在流水线的各个阶段。
## 24. `cs.AI` - 无缝欺骗：更大规模的语言模型是更好的知识隐匿者 [PDF](https://arxiv.org/pdf/2603.14672), [HTML](https://arxiv.org/abs/2603.14672)
### Authors
Dhananjay Ashok,Ruth-Ann Armstrong,Jonathan May
### Background
语言模型（LMs）可能会吸收有害的知识，但在接受审计时却假装不知情。最近发现了一些语言模型表现出欺骗行为的模式，研究旨在训练分类器以检测模型是否在积极隐藏知识。
### Innovation
提出了训练分类器以识别语言模型是否在积极隐藏知识的方法。初始实验表明，与人类评估者相比，基于梯度的欺骗更容易被检测，但发现分类器不能可靠地泛化到未见过的模型架构和隐藏知识的主题。随着模型规模的增加，可识别的隐匿痕迹减弱，超700亿参数的模型上分类器的表现不超过随机水平。
### Conclusion
揭露了在黑盒审计语言模型方面的关键局限性，强调了需要开发检测模型是否积极隐藏其中知识的稳健方法。
## 25. `cs.AI` - VorTEX：不同重叠比例的目标语音提取 [PDF](https://arxiv.org/pdf/2603.14803), [HTML](https://arxiv.org/abs/2603.14803)
### Authors
Ro-hoon Oh,Jihwan Seol,Bugeun Kim
### Background
目标语音提取（TSE）旨在从混合信号中恢复目标说话人的声音。虽然基于文本提示的方法已经显示出潜力，但大多数方法假设完全重叠的混合信号，限制了对不完全重叠的现实情况下的行为理解。
### Innovation
本文提出了VorTEX（不同时重叠比例的目标语音提取），这是一种基于文本提示的目标语音提取架构，包含一个分离主要提取和辅助正则化路径的解耦自适应多分支融合模块（DAM）。此外，还构建了PORTE（包含不同时重叠比例的双说话人数据集），并提出了检测抑制行为的SuRE诊断指标。实验表明，现有模型在重叠条件下会表现出抑制或残留干扰，而VorTEX在20%到100%的重叠范围内达到最佳分离保真度，同时保持零SuRE，表明在没有抑制驱动的伪影的情况下实现了稳健提取。
### Conclusion
实验结果表明，针对20%至100%的重叠范围，VorTEX实现了最高的分离保真度，且在所有重叠率下均未显示抑制行为，证明了该方法在不产生抑制驱动的伪影的情况下实现了稳健的提取效果。
## 26. `cs.AI` - 并非所有潜在空间都是平坦的：超曲面概念控制 [PDF](https://arxiv.org/pdf/2603.14093), [HTML](https://arxiv.org/abs/2603.14093)
### Authors
Maria Rosaria Briglia,Simone Facchiano,Paolo Cursi,Alessio Sampieri,Emanuele Rodolà,Guido Maria D'Amely di Melendugno,Luca Franco,Fabio Galasso,Iacopo Masi
### Background
随着现代图到文本(T2I)模型生成逼真内容的能力不断提高，不安全内容生成的风险也在增加，因此加强对模型输出的控制变得至关重要。现有的控制方法通过调整文本嵌入的空间向量化调整，引导模型远离不安全的概念。但是，研究提出了一种基于平行运输的新颖控制机制，使用语义对齐的超曲面表示空间，以实现更表达性和稳定的概念操控，这种方法重新利用了现成的生成模型和最先进的超曲面文本编码器，并通过轻量级适配器连接起来。
### Innovation
提出了名为超曲面控制（HyCon）的新型概念控制机制，它利用语义对齐的超曲面表示空间，通过平行传输来实现概念操控。HyCon在实现出色表现的同时，保持了控制的可靠性和灵活性。
### Conclusion
HyCon在四个安全基准和四个T2I框架上取得了最佳结果，证明了超曲面控制是一种实用且灵活的方法，可以实现更可靠的图到文本生成。
## 27. `cs.AI` - 实时生成模型预测控制的隐式最大似然估计 [PDF](https://arxiv.org/pdf/2603.13733), [HTML](https://arxiv.org/abs/2603.13733)
### Authors
Grayson Lee,Minh Bui,Shuzi Zhou,Yankai Li,Mo Chen,Ke Li
### Background
扩散模型最近在路径规划中表现出强大的性能，这是因为它们能够捕捉到复杂行为的多种模态分布。然而，这些模型的一个关键限制是它们的推理速度慢，这归因于迭代的去噪过程。这使得它们在闭环模型预测控制等实时应用中不太合适，这类应用需要快速生成计划并不断适应变化的环境。
### Innovation
本文研究了隐式最大似然估计（IMLE）作为规划的另一种生成建模方法。IMLE提供了强大的模式覆盖能力，同时使推理速度快上两个数量级，特别适合实时模型预测控制任务。实验结果表明，在标准离线强化学习基准上，IMLE与标准的扩散模型规划器相比实现了具有竞争力的性能，同时在开环和闭环设置下显著提高了规划速度。进一步在实际的闭环人类导航场景中验证了IMLE，实时操作，展示了它如何在动态环境中实现快速和适应性的计划生成。
### Conclusion
结果显示，IMLE在多种测试环境中都能实现实时应用，并且在开放环和闭环设置中都能提高规划速度。IMLE在标准离线强化学习基准测试中达到了与标准扩散模型规划器相当的性能，但在实时应用中表现出更好的性能。
## 28. `cs.AI` - Fast-WAM: 世界行动模型在测试时间需要未来想象吗？ [PDF](https://arxiv.org/pdf/2603.16666), [HTML](https://arxiv.org/abs/2603.16666)
### Authors
Tianyuan Yuan,Zibin Dong,Yicheng Liu,Hang Zhao
### Background
世界行动模型（WAMs）因其明确建模视觉观察在执行动作下的演变，被认为是视觉-语言-行动（VLA）模型的替代方案。现有WAM模型主要遵循想象然后执行的范式，但由于迭代视频降噪导致评估时间延迟较大，但仍不清楚显式未来想象是否是强行动表现的必要条件。本文通过评估WAM在测试时不需未来想象时的表现，探讨了视频建模和未来预测对WAM性能的影响。
### Innovation
提出了Fast-WAM架构，该架构在训练时保持视频共训练，但在测试时不进行未来预测，以分离视频建模与显式未来生成的作用并进行比较。Fast-WAM在仿真基准（LIBERO和RoboTwin）和实际任务上实现了与现有技术相近的表现，且运行时间仅为190毫秒，比现有WAM提高了4倍速度。结果显示，视频预测的主要价值可能在于提升训练中的世界表示，而非在测试时生成未来观察。
### Conclusion
研究结果表明，视频预测的主要价值可能在于增强训练中的世界表示，而不是测试时生成未来观察。Fast-WAM在不进行实体预训练的情况下，在仿真和实际任务上实现了与最先进的方法相当的表现，且具有较低的延迟，加强了其在行动建模领域的实用性。
## 29. `cs.AI` - CAMA: 探索在c-MARL中的合谋对抗攻击 [PDF](https://arxiv.org/pdf/2603.20390), [HTML](https://arxiv.org/abs/2603.20390)
### Authors
Men Niu,Xinxin Fan,Quanliang Jing,Shaoye Luo,Yunfeng Lu
### Background
合谋多智能体强化学习(c-MARL)已在社会机器人、具身智能、无人机群等多种实际应用中得到广泛应用。然而，针对c-MARL系统的许多对抗性攻击仍然存在，且现有的研究主要集中在单一对手的干扰攻击和白盒对抗性攻击，这类攻击 mainly 通过操控智能体的内部观察或行动来执行。
### Innovation
本研究创造性地提出了三种合谋对抗攻击，并设计了统一的策略级合谋攻击框架CAMA；从破坏性、隐蔽性和攻击成本的角度理论分析了攻击的有效性；通过智能体观测信息的融合和攻击触发控制技术实现上述合谋攻击；实验结果表明，三种合谋攻击具有提升攻击效果、维持高隐蔽性和稳定性等优势。
### Conclusion
本工作填补了c-MARL中合谋对抗学习领域的空白。
## 30. `cs.AI` - ProMAS: 基于马尔可夫转换动态的主动式多智能体系统错误预估 [PDF](https://arxiv.org/pdf/2603.20260), [HTML](https://arxiv.org/abs/2603.20260)
### Authors
Xinkui Zhao,Sai Liu,Yifan Zhang,Qingyu Ma,Guanjie Cheng,Naibo Wang,Chang Liu
### Background
将大型语言模型（LLMs）整合进多智能体系统（MAS）中，能够通过协作推理解决复杂的长时间任务。然而，这种集体智能具有脆弱性，单一的逻辑谬误可以迅速传播并导致系统级故障。当前大多数研究依赖事后故障分析，阻碍了实时干预。在“Who&When”基准测试上，大多数方法在处理推理日志的27%的情况下实现了22.97%的步骤准确性。
### Innovation
我们提出了PROMAS，一种利用马尔可夫转换进行预测错误分析的主动框架。PROMAS从因果增量特征中提取并量化向量马尔可夫空间，通过结合主动预测头部和跳变检测，利用风险加速定位错误而不是静态阈值。相比于被动监控方法，PROMAS在减少数据开销73%的同时提高了22.97%的步进准确性；虽然这是以牺牲事后方法的部分准确性为代价的，但显著提高了干预的及时性。
### Conclusion
PROMAS方法在处理多智能体系统中的错误预见方面具有优势，尤其是在提高及时性诊断方面，同时减少了数据开销，展示了其在复杂任务中的应用潜力。
## 31. `cs.CV` - HumanOmni-Speaker: Identify Who Said What and When [PDF](https://arxiv.org/pdf/2603.21664), [HTML](https://arxiv.org/abs/2603.21664)
### Authors
Detao Bai,Shimin Yao,Weixuan Chen,Xihan Wei,Zhiheng Ma
### Background
尽管全模态大型语言模型在联合感官处理方面取得了进展，但它们在人类交互的核心方面——理解复杂的多人对话动态并准确回答“谁在何时说了什么”这一问题上仍然存在根本困难。当前模型受到‘表象的胜任力’的困扰——它们利用传统基准中的视觉偏见来规避真正的跨模态对齐，同时依赖稀疏、低帧率的视觉抽样，这破坏了诸如唇动这样的关键高频动态。
### Innovation
本文引入了Visual-Registered Speaker Diarization and Recognition (VR-SDR)和HumanOmni-Speaker基准。通过严格消除视觉捷径，VR-SDR要求仅通过自然语言查询实现真正端到端的空间-时间身份绑定。为解决基础架构感知差距，提出了HumanOmni-Speaker并采用Visual Delta Encoder。通过以25fps采样原始视频并显式压缩帧间运动残差为每帧仅6个标记，捕获细粒度的音素和说话人轨迹，同时避免标记数量爆炸。
### Conclusion
最终，HumanOmni-Speaker展示了强大的多模态协同作用，能够实现原生态的唇读和高精度的空间定位，且无需侵入性裁剪，在一系列以说话人为中心的任务中表现优异。
## 32. `cs.CV` - FedCVU：跨视图视频理解的联邦学习 [PDF](https://arxiv.org/pdf/2603.21647), [HTML](https://arxiv.org/abs/2603.21647)
### Authors
Shenghan Zhang,Run Ling,Ke Cao,Ao Ma,Zhanjie Zhang
### Background
联邦学习（FL）已经成为隐私保护多摄像机视频理解的一个有前景的框架。然而，在跨视图场景中应用FL面临三大挑战：（i）不同的视角和背景导致客户端数据分布高度非IID，且容易过拟合到特定视角的模式；（ii）局部分布偏差导致对齐不佳的表示，阻碍了跨视图语义的一致性；（iii）大视频模型架构导致了重大的通信开销。
### Innovation
为解决这些问题，本文提出了一种联邦框架FedCVU，包含三个组件：VS-Norm，用于保存归一化参数以处理视角特定的统计信息；CV-Align，一种轻量级对比度正则化模块，以提高跨视图表示的一致性；SLA，一种选择性层聚合策略，在不影响精度的情况下减少通信。
### Conclusion
在跨视图协议下的行为理解和行人重识别任务中进行的大量实验表明，FedCVU始终提高了未见过视图的准确性，同时保持了已见过视图的性能，并超越了最先进的FL基线，显示了在域异质性和通信约束方面的鲁棒性。
## 33. `cs.CV` - PGR-Net：用于脑肿瘤MRI分割的先验指导ROI推理网络 [PDF](https://arxiv.org/pdf/2603.21626), [HTML](https://arxiv.org/abs/2603.21626)
### Authors
Jiacheng Lu,Hui Ding,Shiyu Zhang,Guoping Huo
### Background
脑肿瘤MRI分割对于临床诊断和治疗计划至关重要，有助于精确检测病灶及放射治疗靶区的界定。然而，肿瘤病灶仅占图像空间的一小部分，导致严重的空间稀疏性。现有分割网络常常忽略了临床观察到的肿瘤发生的空间先验，导致在大量背景区域进行了冗余的特征计算。因此，本文探讨了解决该问题的方法。
### Innovation
本文提出了一种名为PGR-Net (Prior-Guided ROI Reasoning Network)的方法，这是一种明确的ROI感知框架，结合数据驱动的空间先验集以捕捉病灶的分布和规模特征，为更稳定的分割提供全局指导。通过使用层次化的Top-K ROI决策机制，PGR-Net在编码器层逐步选择最有信心的病灶候选区域，以提高定位精度。进一步开发了WinGS-ROI（滑窗高斯-空间衰减ROI）模块，该模块使用具有空间衰减函数的多窗口高斯模板生成中心增强指导图，从而在整个网络中引导特征学习。
### Conclusion
在BraTS-2019/2023和MSD Task01上进行的实验表明，PGR-Net在使用8.64M参数的情况下表现优于现有方法，尤其是在Whole Tumor区域，Dice分数分别为89.02%、91.82%和89.67%。相关代码可在该页面获得。
## 34. `cs.CV` - 大型视觉语言模型中重思考令牌减少 [PDF](https://arxiv.org/pdf/2603.21701), [HTML](https://arxiv.org/abs/2603.21701)
### Authors
Yi Wang,Haofei Zhang,Qihan Huang,Anda Cao,Gongfan Fang,Wei Wang,Xuan Jin,Jie Song,Mingli Song,Xinchao Wang
### Background
大型视觉语言模型（LVLMs）在视觉理解与推理方面表现出色，但是大量的视觉令牌会引发较高的推理成本。尽管一些令牌减少方法降低了这一问题，主要针对单一回合的视觉问答（VQA），但多回合VQA（MT-VQA）却较少得到关注。MT-VQA面临额外的挑战，即后续问题在未知的情况下可能会引用图像的任意区域，现有策略在处理时效果不佳。目前的方法可以分为两类：基于提示的方法会偏向初始文本提示，丢弃后续回合有用的信 息；基于提示的方法虽然理论上适用于多回合设置，但却依赖于启发式减少指标，如注意力得分，导致性能不佳。
### Innovation
本文提出了一个基于学习的提示无关方法，称为MetaCompress，其突破了启发式设计的限制。作者将令牌减少视为可学习的压缩映射，并统一现有方法（如剪枝和合并）为单一学习目标。通过这种公式化方式，作者介绍了一种数据高效的训练框架，能够以较低的计算成本学习最佳压缩映射。大量的实验证明，MetaCompress在MT-VQA基准上实现了更高的效率-精度权衡，并且具有较强的跨对话回合的一般化能力。
### Conclusion
在多个LVLM架构下进行的广泛实验表明，MetaCompress在效率-准确性折衷方面表现出色，同时保持了强大的跨对话回合的一般化能力。我们的代码已发布。
## 35. `cs.CV` - 基于经验和直觉的多级适应性框架用于多对象跟踪：构建测试时校准 [PDF](https://arxiv.org/pdf/2603.21629), [HTML](https://arxiv.org/abs/2603.21629)
### Authors
Wen Guo(1),Pengfei Zhao(1),Zongmeng Wang(4),Yufan Hu(2),Junyu Gao(3) ((1) Shandong Technology and Business University, (2) University of Science and Technology Beijing, (3) Institute of Automation, Chinese Academy of Sciences, (4) Inner Mongolia University)
### Background
多对象跟踪(MOT)一直是计算机视觉中的基础任务，在多个实际应用场景中具有广泛的应用。然而，由于训练数据和测试数据在外观、运动模式和类别的分布差异，模型在在线推理时性能显著下降。既有的测试时自适应(TTA)方法虽然能够缓解这一问题，但在MOT任务中往往效果不佳，主要原因是它们忽略了帧间和视频间的时空一致性及身份关联。
### Innovation
本文提出了一种基于经验和直觉的测试时校准框架(TCEI)。该框架通过两大学习系统实现多级自适应：直觉系统利用瞬时记忆快速预测最近观察到的对象，经验系统则利用先前测试视频积累的经验重新评估和校准这些直觉预测。此外，框架还利用在线测试阶段中的确信对象和不确定对象作为历史先验和反思案例，帮助模型适应测试环境，缓解性能下降。
### Conclusion
广泛的实验表明，提出的TCEI框架在多个基准数据集上表现出优异性能，显著提升了模型在分布漂移情况下的适应能力。代码已在相应网站开源。
## 36. `cs.CV` - OmniFM: 向泛模态和任务无关的异质医疗成像联邦学习迈进 [PDF](https://arxiv.org/pdf/2603.21660), [HTML](https://arxiv.org/abs/2603.21660)
### Authors
Meilin Liu,Jiaying Wang,Jing Shan
### Background
联邦学习（FL）已成为协作医疗图像分析的有希望的范式，但现有框架仍然紧密耦合于特定任务的骨干网络，对异质成像模态非常脆弱。这种限制导致在现实世界中难以部署，因为不同机构在模态分布上差异很大，并且必须支持多种多样的下游任务。
### Innovation
我们提出了OmniFM，这是一个模态和任务无关的FL框架，它统一了分类、分割、超分辨率、视觉问答和多模态融合的训练，而无需重新设计优化流水线。OmniFM 根据关键的频域洞察：低频频谱分量在跨模态下表现出高度一致性并编码模态不变的解剖结构，它通过（i）全局谱知识检索来注入全局频率先验，（ii）嵌入式跨注意力融合来对齐表示，以及（iii）前缀-后缀谱提示来联合条件全局和个性化线索，并通过频谱近邻对齐目标来进行正则化，以稳定聚合。
### Conclusion
在实际数据集上的实验表明，OmniFM 在跨模态异质性下持续超越最先进的 FL 基准，并在微调和从零开始训练设置下都取得了优越的结果。
## 37. `cs.CV` - 跨场景无配对数据去雨适配：超像素结构先验与多阶段伪雨合成 [PDF](https://arxiv.org/pdf/2603.21661), [HTML](https://arxiv.org/abs/2603.21661)
### Authors
Kangbo Zhao,Miaoxin Guan,Xiang Chen,Yukai Shi,Jinshan Pan
### Background
图像去雨在低层计算机视觉中扮演着关键角色，为可靠的大气户外监控和自动驾驶系统奠定基础。尽管深度学习方法在对齐场景中取得了显著成功，但它们在未见过的Out-of-Distribution（OOD）场景下往往会遭受严重性能下降。这主要源于合成训练数据集与实际环境中的复杂物理雨天动态之间的显著领域差异。
### Innovation
该论文提出了一种开创性的跨场景去雨适配框架，摒弃了对目标领域配对雨景观察的需求，仅利用无雨背景图像。通过Superpixel Generation（Sup-Gen）模块从源域中提取稳定的结构先验，并引入分辨率自适应融合策略将这些源结构与目标背景对齐，确保合成多样且真实的伪数据。此外，通过多阶段噪声生成机制，实现了伪雨合成机制，模拟真实雨丝。该框架作为通用插拔模块，可以与任意去雨架构无缝集成。
### Conclusion
在先进的模型上进行的大量实验表明，该方法在OOD域中能够实现高达32%至59%的PSNR增益，并显著加速了训练收敛。
## 38. `cs.CV` - RefracGS: 通过三维高斯光线追踪实现折射水面上的新型视图合成 [PDF](https://arxiv.org/pdf/2603.21695), [HTML](https://arxiv.org/abs/2603.21695)
### Authors
Yiming Shao,Qiyu Dai,Chong Gao,Guanbin Li,Yeqiang Wang,He Sun,Qiong Zeng,Baoquan Chen,Wenzheng Chen
### Background
新型视图合成（NVS）通过非平面折射表面提出基本挑战，因为这些表面造成了严重的、空间变化的光学失真。尽管像NeRF和3D Gaussian Splatting (3DGS)等最近的表示方法在NVS方面表现出色，但它们假设光线沿直线传播，这在折射情况下会失败，导致显著的艺术品。
### Innovation
我们引入了RefracGS框架，该框架联合重构折射水面和接口下的场景。我们的关键见解是明确解耦折射边界和目标对象：折射面通过神经高度场建模，捕捉波几何结构，而底层场景作为3D Gaussian场表示。我们用斯涅尔定律和Snell定律建立了折射感知的高斯光追踪方法，计算非线性光线轨迹，并高效渲染底层的Gaussian场，同时反向传播损失梯度到参数化的折射面。通过端到端联合优化两种表示，此方法确保高质量的NVS和表面恢复的一致性。
### Conclusion
我们在合成和复杂的实际场景上进行的实验表明，RefracGS在视觉质量上优于之前的折射方法，同时实现了15倍的训练速度和每秒200帧的实时渲染。RefracGS的项目页面可在this https URL找到。
## 39. `cs.CV` - 无需密集张量：事件摄像头体素网格上的全稀疏目标检测 [PDF](https://arxiv.org/pdf/2603.21638), [HTML](https://arxiv.org/abs/2603.21638)
### Authors
Mohamad Yazan Sadoun,Sarah Sharif,Yaser Mike Banad
### Background
事件相机产生的异步、高动态范围流适合于检测小型快速移动的无人机，然而现有的事件驱动检测器通常会将稀疏事件流转换成密集张量，这忽略了神经形态感知的表示效率。因此，本文的背景是介绍一种通过稀疏卷积在仅操作已占用体素位置而不生成任何密集特征张量的情况下进行物体检测的方法。
### Innovation
本文提出了SparseVoxelDet，这是首个完全基于稀疏体素的目标检测器。SparseVoxelDet在事件相机环境下表现出了优异的性能。在FRED基准测试中，该模型每个帧仅处理14,900个活跃体素（0.23%的体素网格），达到了83.38%的mAP，相比之下，传统稠密YOLOv11基线模型处理409,600像素（87.68%的mAP）。该稀疏表示方法相比于等效的稠密3D体素张量实现了858倍的GPU内存压缩和3670倍的存储减少，其表示成本随场景动态变化而非传感器分辨率变化。
### Conclusion
稀疏表示法的实验结果表明，原生稀疏处理是事件相机目标检测的一种可行方案，无需依赖神经形态计算硬件，同时提供了一种其表示成本受场景活动而非像素数控制的框架，这一特性对于随着事件相机分辨率的提高变得愈发重要。
## 40. `cs.CV` - PPGL-Swarm：在嗜铬细胞瘤和副神经节瘤中实现综合多模态风险分层和遗传综合征检测 [PDF](https://arxiv.org/pdf/2603.21700), [HTML](https://arxiv.org/abs/2603.21700)
### Authors
Zelin Liu,Xiangfu Yu,Jie Huang,Ge Wang,Yizhe Yuan,Zhenyu Yi,Jing Xie,Haotian Jiang,Lichi Zhang
### Background
嗜铬细胞瘤和副神经节瘤（PPGLs）是少见的神经内分泌肿瘤，大约15-25%的患者会发展成转移性疾病，5年生存率最低仅为34%。PPGL可能提示遗传性综合征的需要更为严格和综合征特定的治疗方法和监测，但临床医生在常规护理中常未能识别这些关联。使用GAPP评分进行PPGL分级时，仍存在诊断限制：（1）GAPP评分需要临床医生手动评估六大独立组件，工作量大；（2）关键组件如细胞学和Ki-67通常以主观标准进行评估；（3）GAPP未能涵盖多种临床相关的转移风险因素，如SDHB突变，SDHB突变与高达35-75%的转移率有关。现有的诊断系统多数缺乏可追溯的决策推理，并且不结合特化的知识，如PPGL的基因型信息。
### Innovation
我们提出了一个名为PPGL-Swarm的代理驱动诊断系统，旨在解决上述限制。PPGL-Swarm系统生成全面报告，包括自动化GAPP评分（带有量化细胞学和Ki-67），基因风险警报，以及整合所有证据的多模态报告。系统通过将诊断分解为微任务赋予每个任务专门的代理，以提供可审计的推理轨迹。基因和表格代理利用知识增强以更好地解释基因型和实验室发现。我们利用强化学习来精装修订工具选择和任务分配。
### Conclusion
通过PPGL-Swarm系统，我们实现了对嗜铬细胞瘤和副神经节瘤进行综合多模态风险分层，同时也能够检测遗传综合征。这一系统能够提供更为全面和可靠的诊断信息，协助提高临床护理的质量。
## 41. `cs.LG` - 基于Spherical Hellinger Kantorovich动力学的Sinkhorn基联想记忆检索 [PDF](https://arxiv.org/pdf/2603.20656), [HTML](https://arxiv.org/abs/2603.20656)
### Authors
Aratrika Mustafi,Soumya Mukherjee
### Background
本文提出的是一项关于权重点云的密集联想记忆的研究。存储模式和查询是有限支持概率测量，检索由从修正Sinkhorn散度构建的Hopfield样式log-sum-exp能量函数最小化来定义。在局部分离和PL类型条件下，作者证明了基底不变性、几何收敛到局部最小值，并给出了最小值保持与对应存储模式接近的界限。在随机模式模型下，作者进一步表明这些Sinkhorn基底几乎以概率为零是分离的，这意味着在环境维度中记忆容量呈指数增长。
### Innovation
本文提出了一种基于Spherical Hellinger Kantorovich动力学的联想记忆检索方法。它利用Sinkhorn能量函数来最小化检索过程中的距离度量，并通过动力学框架更新支持位置和权重。这种方法优于传统的欧几里得Hopfield模型，尤其是在处理扰动查询时。
### Conclusion
在局部分离和PL条件下的实验表明，该方法能够从扰动查询中稳定地恢复存储模式。随机模式模型的实验进一步证明了记忆容量在高维度下的显著增长。
## 42. `cs.LG` - RoboECC: 多因素感知的边缘-云协同部署方案用于VLA模型 [PDF](https://arxiv.org/pdf/2603.20711), [HTML](https://arxiv.org/abs/2603.20711)
### Authors
Zihao Zheng,Hangyu Cao,Jiayu Chen,Sicheng Tian,Chenyue Li,Maoliang Li,Xinhao Sun,Guojie Luo,Xiang Chen
### Background
视觉-语言-行动（VLA）模型是嵌入式智能的主流，但面临着较高的推理成本。边缘-云协作（ECC）部署通过缓解边缘设备的计算压力来满足实时需求，是一种有效的解决方案。然而，现有ECC框架对VLA模型并不理想，主要由于两个挑战：(1) 多样化的模型结构使得难以识别出最优的ECC分割点；(2) 即使最优分割点被确定，网络带宽的变化也会导致性能波动。
### Innovation
本文提出了一种针对各种VLA模型的新型边缘-云协作部署框架，称为RoboECC。具体而言，我们提出了一种模型-硬件共感知的分割策略，以帮助找到各种VLA模型的最优分割点，并且还提出了一种网络感知的部署调整方法来适应网络波动以维持最优性能。
### Conclusion
实验表明，RoboECC在与原有方法相似或相近的性能下，可以实现高达3.28倍的速度提升，仅有2.55倍~2.62倍的额外成本。
## 43. `cs.LG` - NDT: 非微分变换器及其在情感分析中的应用 [PDF](https://arxiv.org/pdf/2603.20704), [HTML](https://arxiv.org/abs/2603.20704)
### Authors
Soudeep Ghoshal,Himanshu Buckchash,Sarita Paudel,Rubén Ruiz-Torrubiano
### Background
理解人类文本中的情感对于机器与人类有意义的交互至关重要，并且从客户反馈到社交媒体，这一理解是核心内容。尽管取得了显著进展，准确捕捉情感仍然是一个具有挑战性的问题，这也推动了这一领域的进一步研究。
### Innovation
该论文提出了一种名为非微分变换器（NDT）的新模型，该模型受到最新的微分变换器（DT）模型的启发但采用了相反的方法。它采用了纯加性策略，仅使用正权重学习，确保这些专门化的注意力视角能够建设性地融合，而无需依赖减法来进行噪声消除。论文还指出这种方法在包含正负权重的较少限制的线性组合中也可能表现出色。
### Conclusion
在多个数据集上对所提模型进行情感分析测试取得了竞争力的表现。研究结果、面临的挑战及未来的研究议程也在此论文中进行了讨论。
## 44. `cs.LG` - 高维度在线学习的异步分解方法：非发散结果、动态正则化及其延伸 [PDF](https://arxiv.org/pdf/2603.20696), [HTML](https://arxiv.org/abs/2603.20696)
### Authors
Shixiang Liu,Zhifan Li,Hanming Yang,Jianxin Yin
### Background
现有的高维度在线学习方法在数据批次增加时经常面临误差边界或每批次样本大小发散的问题。
### Innovation
提出了一种异步分解框架，利用摘要统计构造当前批次的学习替代得分函数。该框架通过动态正则化迭代硬阈值算法实现，提供了一种计算上和内存上高效的稀疏在线优化解。
### Conclusion
理论分析表明，该方法能保持非发散的误差边界和$l_0$稀疏性，随着批次积累，还能获得类似完整历史数据集的最优精度。
## 45. `cs.LG` - mmWave-Diffusion：一种基于观测关联条件扩散模型的新型呼吸传感框架 [PDF](https://arxiv.org/pdf/2603.20700), [HTML](https://arxiv.org/abs/2603.20700)
### Authors
Yong Wang,Qifan Shen,Bao Zhang,Zijun Huang,Chengbo Zhu,Shuai Yao,Qisong Wu
### Background
毫米波（mmWave）雷达可以实现无接触的呼吸监测。然而，由于身体产生的非平稳干扰，细微的监测往往会被破坏。
### Innovation
本文提出了一种基于观测关联的条件扩散框架——mmWave-Diffusion。该框架直接建模雷达相位观测值与呼吸真实值之间的残差，在观测一致的邻域内初始化采样，而不是从高斯噪声开始。这使得生成过程与测量物理一致，从而减少了推理开销。此外，伴随的Radar Diffusion Transformer（RDT）明确地条件于相位观测，通过像素级别双位置编码强制严格的逐时一对一对齐，并通过带状掩码多头交叉注意力注入局部物理先验，使得仅在20次反向步骤中就能实现稳健的去噪和干扰消除。
### Conclusion
在13.25小时同步雷达呼吸数据上评估，mmWave-Diffusion在波形重建和呼吸率估计方面达到了最先进的效果，表现出了强大的泛化能力。相关代码库可在以下网址访问：this https URL。
## 46. `cs.LG` - 脑连接体的层次多尺度结构-功能耦合 [PDF](https://arxiv.org/pdf/2603.20680), [HTML](https://arxiv.org/abs/2603.20680)
### Authors
Jianwei Chen,Zhengyang Miao,Wenjie Cai,Jiaxue Tang,Boxing Liu,Yunfan Zhang,Yuhang Yang,Hao Tang,Carola-Bibiane Schönlieb,Zaixu Cui,Du Lei,Shouliang Qi,Chao Li
### Background
将结构连接体和功能连接体的整合仍然充满挑战，因为它们之间关系是非线性的，并且按嵌套模块层次组织。现有的方法难以同时理解不同层次的结构和功能连接体之间的关系。
### Innovation
提出了一个层次多尺度结构-功能耦合框架，用于连接体的整合。该框架包括：基于原型的模块聚类（PMPool），通过选择原型ROI并优化差分模块度启发式目标函数，学习模态特异性多尺度社区；基于注意力的层次耦合模块（AHCM），建模层次内和跨层次的结构-功能连接体相互作用，以产生丰富的层次耦合表示；耦合导向聚类损失（CgC-Loss），通过与耦合信号正则化结构和功能社区分配，允许跨模态相互作用塑造不同层次的社区对齐。
### Conclusion
该研究模型在四个队列中跨三种任务对预测脑年龄、认知评分和疾病分类的表现优于基准和其他最先进的方法。消融和敏感性分析验证了关键组件的贡献。最终，学习的耦合的可视化揭示了可解释的差异，表明该框架捕获了生物学上有意义的结构-功能关系。
## 47. `cs.LG` - RLVR培训的大型语言模型在通用问答中的效果不佳：评估方法及简单解决方案 [PDF](https://arxiv.org/pdf/2603.20799), [HTML](https://arxiv.org/abs/2603.20799)
### Authors
Kaiyuan Li,Jing-Cheng Pang,Yang Yu
### Background
RLVR（可验证奖励的强化学习）通过刺激大型语言模型的思考过程，显著提升了它们在可验证任务上的推理能力。但现有研究并未全面验证RLVR是否能自动提升大型语言模型在一般问题回答（GQA）上的表现。
### Innovation
提出了一种跨代评估框架，通过将生成的思考上下文输入不同能力的大型语言模型来测量中间推理的质量。发现在GQA任务上的效果远低于在可验证任务上，同时提出了一种简单方法——分离思考和响应训练（START），首先仅训练思考过程，使用最终答案定义奖励。
### Conclusion
表明在GQA任务上的思考过程效果较低，需要额外针对GQA进行显式训练。直接在GQA上进行RL训练不如RLVR有效，START方法能在多个GQA基准和RL算法上提高思考质量和最终答案质量。
## 48. `cs.LG` - Multi-RF Fusion with Multi-GNN Blending for Molecular Property Prediction [PDF](https://arxiv.org/pdf/2603.20724), [HTML](https://arxiv.org/abs/2603.20724)
### Authors
Zacharie Bugaud
### Background
该研究使用了多射频（Multi-RF）融合方法，在分子性质预测任务上达到了较高的性能。方法结合了随机森林（Random Forest）和图形神经网络（Graph Neural Network，GNN），并使用了多种分子指纹（分子特征表示）来增强模型的表现。
### Innovation
1. 通过将`max_features`设置为0.20而不是默认的`sqrt(d)`，模型在特定切分的测试上获得了0.008的AUC提升。2. 在融合GNN预测之前，将10个随机种子的GNN预测结果进行平均，从而消除了GNN的种子变异，降低了最终的标准差。3. 使用了rank-averaged的随机森林模型集成，并通过与GNN预测融合提高模型性能。
### Conclusion
该方法在OGB的molhiv数据集上取得了第一名，AUC为0.8476，超过了HyperFusion的结果，并且使用了多种分子指纹特征，提出的方法不仅提高了性能，也增加了模型的稳定性。
## 49. `cs.LG` - 基于视觉-语言-行动模型的实用世界模型强化学习方法 [PDF](https://arxiv.org/pdf/2603.20607), [HTML](https://arxiv.org/abs/2603.20607)
### Authors
Zhilong Zhang,Haoxiang Ren,Yihao Sun,Yifei Sheng,Haonan Wang,Haoxin Lin,Zhichao Wu,Pierre-Luc Bacon,Yang Yu
### Background
Vision-Language-Action (VLA) 模型在机器人控制中表现出强大的泛化能力，但使用强化学习(Reinforcement Learning, RL)进行微调时，由于现实世界交互的高成本和安全风险，其应用受到限制。通过交互式的虚拟世界模型训练VLA模型可以避免这些问题，但在像素级世界建模、多视角一致性以及稀疏奖励下的累积错误等方面带来了新的挑战。
### Innovation
本文基于大规模多模态模型和基于模型的RL的最新进展，提出了一种实用的VLA微调框架VLA-MBPO。其关键设计选择包括：(i) 为高效的世界建模适应统一多模态模型(UMMs)；(ii) 交错视图解码机制以确保多视角一致性；(iii) 分块分支的回放以减轻累积错误。理论分析和各种模拟和现实任务的实验表明，VLA-MBPO显著提升了策略性能和样本效率，证明了其在实际机器人部署中的稳健性和可扩展性。
### Conclusion
VLA-MBPO框架增强了VLA模型在实际机器人部署中的性能和样本效率，展示了其在现实环境中的稳健性和可扩展性。
## 50. `cs.LG` - LassoFlexNet：基于局部特征嵌入和可调组lasso机制的灵活神经架构 [PDF](https://arxiv.org/pdf/2603.20631), [HTML](https://arxiv.org/abs/2603.20631)
### Authors
Kry Yik Chau Lui,Cheng Chi,Kishore Basu,Yanshuai Cao
### Background
尽管深度神经网络在视觉和语言领域占据主导地位，但在处理表数据时往往不如基于树的模型表现良好。为了弥合这一差距，作者将五个关键的归纳偏置引入深度学习：对无关特征的稳健性、轴对齐性、局部非规则性、特征异质性和训练稳定性。
### Innovation
提出了LassoFlexNet架构，通过Per-Feature Embeddings评估每个输入的线性和非线性边际贡献，并使用Tied Group Lasso机制稀疏地选择相关变量。由于这些组件引入了优化挑战，可能会使标准近端方法不稳定，因此开发了一种SeqHPAR加权指数移动平均（EMA）优化器来确保稳定收敛。
### Conclusion
LassoFlexNet在三个基准上的52个数据集中与或优于领先树模型，达到最高10%的相对性能提升，同时保持类似Lasso的可解释性。通过消融研究和理论证明，验证了该架构增强的表达能力和结构上对不必要的旋转不变性的打破。
