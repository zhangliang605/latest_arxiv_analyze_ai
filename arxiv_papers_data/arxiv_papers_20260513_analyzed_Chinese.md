# 20260513
[![Subscribe_Visitors](https://visitor-badge.laobi.icu/badge?page_id=nituchao.latest_arxiv_analyze_ai_rss)](https://github.com/nituchao/latest_arxiv_analyze_ai)

## 1. `cs.AI` - 信念还是电路？图学习的因果证据 [PDF](https://arxiv.org/pdf/2605.08405), [HTML](https://arxiv.org/abs/2605.08405)
### Authors
Katharine Kowalyshyn,Timothy Duggan,Daniel Little,Michael C Hughes
### Background
本文探讨了大规模语言模型（LLMs）在上下文学习中的机制，即它们是通过匹配最近的令牌模式还是推断潜在结构来进行学习的。为此，作者设计了一个使用图随机游走任务，考察哪些图结构被模型学习到。理论认为答案是可决定的：模型要么关注全局拓扑结构，要么复制局部过渡。
### Innovation
文章提出了两条证据，表明单一机制不足以解释模型的学习过程。通过对主成分分析（PCA）内部表示结构的重建，发现模型在混合比例的中间阶段同时编码了两种图拓扑结构。此外，通过干预实验中的残差流激活补丁和图差异引导，展示了在顶层补丁和线性定向控制下的预测行为，这表明真实结构推理和诱导电路在并行运行。
### Conclusion
整体来看，我们的发现最符合一个双机制解释，其中真正的结构推理和诱导电路在并行运行。
## 2. `cs.AI` - PLACO: 一种多阶段框架，用于提高人类与人工智能团队的成本效益性能 [PDF](https://arxiv.org/pdf/2605.08388), [HTML](https://arxiv.org/abs/2605.08388)
### Authors
Pranavkumar Mallela,Vinay Kumar,Shashi Shekhar Jha,Shweta Jain
### Background
人类与AI的团队协作在提高整体系统性能方面扮演着关键角色，尤其是在单靠人类或模型无法独立实现这种性能的情况下。自强大的生成型AI模型出现以来，许多常规任务已经演变为人类与AI的协作任务。从撰写文章到开发高级算法，人们发现借助AI的协助使工作进度大幅加快。在分类任务中，最终输出是单一的硬标签，因此关键是如何有效地结合人类和模型的输出结果。
### Innovation
本文提出了一种多阶段框架PLACO，旨在合理平衡成本与性能，特别是在人类与AI团队协作的情况下。该框架通过使用贝叶斯规则，结合了人类和模型的输出结果，考虑了模型的实例级概率和人类的类别级概率校准。
### Conclusion
该研究提出了一种新颖的多阶段框架PLACO，旨在通过合理利用低成本的人类外推员和高成本的AI，优化人类与AI团队的性能和成本效益。该研究证实了PLACO框架的有效性，并为未来在成本和性能优化方面提供了有益的见解。
## 3. `cs.AI` - 视觉-语言模型中可靠性的存在：注意力、隐藏状态和因果电路的机制研究 [PDF](https://arxiv.org/pdf/2605.08200), [HTML](https://arxiv.org/abs/2605.08200)
### Authors
Logan Mann,Ajit Saravanan,Ishan Dave,Shikhar Shiromani,Saadullah Ismail,Yi Xia,Emily Huang
### Background
大多数人认为，视觉-语言模型的注意力图越清晰，其答案越可信，但该研究直接检验了这一假设。研究通过一个统一分析管道——模型可靠性探测器（VRP），在三个开放权重的视觉-语言模型（LLaVA-1.5、PaliGemma、Qwen2-VL；参数量为3-7B）中比较了注意力结构、生成动态和隐藏状态几何结构与单一正确性标签之间的差异。
### Innovation
该研究通过一个统一分析管道——模型可靠性探测器（VRP），首次直接分析了注意力结构、生成动态和隐藏状态几何结构与模型正确性之间的关系。研究发现，即使注意力对于特征提取至关重要，其结构也不能成为正确性的有效预测指标。同时，研究揭示了可靠性的判定更依赖于隐藏状态的几何结构、跨层差距形成和稀疏晚期层电路，而不仅仅是注意力图的清晰度。
### Conclusion
在3-7B参数量的视觉-语言模型中，可靠性的检测更多地来自于隐藏状态的几何结构、跨层差距的形成和稀疏晚期层电路，而不是注意力图的清晰度。
## 4. `cs.AI` - Auto-Rubric作为奖励：从隐式偏好到明确的多模态生成标准 [PDF](https://arxiv.org/pdf/2605.08354), [HTML](https://arxiv.org/abs/2605.08354)
### Authors
Juanxi Tian,Fengyuan Liu,Jiaming Han,Yilei Jiang,Yongliang Wu,Yesheng Liu,Haodong Li,Furong Xu,Wanhua Li
### Background
多模态生成模型需要与人类偏好对齐，但现有方法（如RLHF）往往将人类的多维度偏好简化为单一指标或成对标签，导致透明度不足和容易受到奖励操控。虽然Rubrics-as-Reward (RaR) 方法试图通过显式的准则来恢复这种结构，但仍存在可靠的、可扩展和数据效率低的问题。
### Innovation
本文提出了一种Auto-Rubric as Reward (ARR) 框架，将奖励建模从隐式权重优化重新定义为基于明确准则的分解。具体而言，ARR 将大型语言模型内部化的偏好知识外化为特定提示的准则，并将整体意图转换为独立可验证的质量维度。在此基础上，提出了Rubric Policy Optimization (RPO) 方法，将ARR的结构化多维评估转化为稳健的二元奖励，用基于准据的偏好决策取代不透明的标量回归，稳定政策梯度。实验结果显示，ARR-RPO 在文本到图像生成和图像编辑基准测试中优于成对奖励模型和VLM评判员。
### Conclusion
明确外部化隐式偏好知识为结构化准据可以实现更可靠和数据高效的多模态对齐，瓶颈在于缺乏因素化的界面，而非知识不足。
## 5. `cs.AI` - 嵌入偏好而非语义 [PDF](https://arxiv.org/pdf/2605.08360), [HTML](https://arxiv.org/abs/2605.08360)
### Authors
Carter Blair,Ariel D. Procaccia,Milind Tambe
### Background
现代AI开启了集体决策的方式，参与者以自由形式的文本表达观点，而不是在固定候选人集上投票。将这些意见嵌入向量空间，可以利用设施位置问题和公平聚类的相关文献。然而，标准文本嵌入测量语义相似性，而在设施位置问题和公平聚类中所需的是一种称为‘偏好相似性’：参与者与文本的一致性应与其距离成反比。现成的嵌入通过语义和偏好相似性之间的相关性继承了一种粗糙的偏好信号，但在相关性破裂时无法捕捉偏好。
### Innovation
论文形式化了一个不变性问题：文本嵌入模型同时编码了一个相关性的偏好信号（观点和价值观）和语义噪声（风格和措辞），这两种信号在观察上是共变的，因此依赖于噪声的几何结构可能会显得偏好正确但实际上不是。提出了通过设计合适数量的合成训练数据来打破语义和偏好之间的相关性，从而将最优评分者从噪声主导的余弦向偏好主导牵引的方法，显著提高了在11个在线讨论数据集上的偏好预测。
### Conclusion
研究表明，这种设计合适数量的合成训练数据的方法，可以将最优评分者从对噪声主导的余弦向偏好主导牵引，显著提高了偏好预测的准确性，在11个在线讨论数据集上有明显改善。
## 6. `cs.AI` - SkillLens：低成本LLM代理的自适应多粒度技能重用 [PDF](https://arxiv.org/pdf/2605.08386), [HTML](https://arxiv.org/abs/2605.08386)
### Authors
Yongliang Miao,Ziyang Yu,Liang Zhao,Bowen Zhu,Hasibul Haque
### Background
技能库已成为语言模型（LLM）代理在任务间重用程序经验的实际方式。然而，现有系统通常将技能视为平面的单一分辨率提示块。这在相关性和成本之间造成了张力：注入粗粒度技能可能会引入无关或误导性的背景，而重写整个技能则成本高昂且往往是不必要的。
### Innovation
我们提出了SkillLens，这是一种分层技能演变框架，将技能组织成由策略、策略、过程和原语组成的四层图，并以混合粒度检索它们。给定一个任务，SkillLens首先检索语义上相关的技能种子，通过技能图上的度修正随机步行扩展它们，然后使用验证器决定每个访问单元是否应接受、分解、重写或跳过。这使代理可以直接重用兼容的子技能，仅适应局部不匹配的组件。为了随着时间改进系统，SkillLens进一步细化多粒度技能和验证器以改进其路由决策。我们提供了理论分析，证明在稀疏的不匹配假设下，混合粒度的适应性开销是亚线性的，并且进化的更新规则单调提高验证目标直到局部最优。
### Conclusion
我们在MuLocbench和ALFWorld上对SkillLens进行了测试，发现它在强基于技能的基本模型上有一致的改进，对于软件本地化，准确率为1的增益高达6.31个百分点，代理成功比例从45.00%提高到51.31%。
## 7. `cs.AI` - 基于学习优化策略的教学意识启发式程 Yazı: 基于学习优化策略的教学意识启发式程序演化 [PDF](https://arxiv.org/pdf/2605.10634), [HTML](https://arxiv.org/abs/2605.10634)
### Authors
Minyu Chen,Song Qin,Ling-I Wu,Jianxin Xue,Guoqiang Li
### Background
基于大型语言模型（LLM）的自动启发式设计已经显示出为组合优化生成可执行启发式的方法潜力，但现有方法主要依赖于末尾性能表现。本研究旨在改进启发式设计的方法。
### Innovation
提出了一个'教学意识进化框架'，该框架使用独立训练的学习优化策略作为行为教师。这一方法不部署或模仿教师，而是查询在候选启发式程序访问的状态上教师的行为偏好，并将其用作进化过程的局部反馈。通过这种方式，搜索过程既受到任务性能的影响，也受到教师行为信号的指导。
### Conclusion
在调度、路由和图优化基准测试上的实验表明，该方法在不依赖神经推理的部署下，性能优于基于末尾性能的LLM启发式进化基线。结果表明，学习优化策略可以重新利用作为自动启发式发现的行为反馈源。
## 8. `cs.AI` - 透明箱谬误：为什么AI部署需要一个经过校准的验证制度 [PDF](https://arxiv.org/pdf/2605.10601), [HTML](https://arxiv.org/abs/2605.10601)
### Authors
Phongsakon Mark Konrad,Tim Lukas Adam,Ane Cathrine Holst Merrild,Riccardo Terrenzi,Rebecca De Rosa,Toygar Tanyel,Serkan Ayvaz
### Background
在医疗保健、信用、就业和刑事司法等敏感领域部署AI时，通常会因为难以解释模型内部机制而被视为不安全，从而依赖于机械可解释性来解决超出其适配范围的部署挑战。社会长期以来通过认证、监控、问责、上诉和吊销等手段来管理不透明的专业知识，而不是通过层面解释机制。最近的研究显示内部表示与输出纠正之间的53个百分点差异，以及仅有9.0%的FDA批准的AI/ML设备文档包含前瞻性上市后监控研究，进一步证明了机械理解与部署授权之间的区别。
### Innovation
提出了一种新的验证制度——经过校准的验证，作为授权的标准，该制度包括六个可报告的要素，并提出了最小组合规则，这一制度应该与模型卡片、排行榜以及监管披露中的能力评分并列。
### Conclusion
授权应该基于特定使用场景，而非通用模型，并且应该是领域相关的、可独立验证的、部署后的监控、问责的、可争议的和可撤销的。
## 9. `cs.AI` - 层级因果推断：可解释模型预测控制的基础框架 [PDF](https://arxiv.org/pdf/2605.10624), [HTML](https://arxiv.org/abs/2605.10624)
### Authors
Ramesh Arvind Naagarajan,Zühal Wagner,Stefan Streif
### Background
模型预测控制（MPC）被广泛应用于安全关键基础设施的操作中，通过对未来轨迹进行预测并优化控制操作来发挥其作用。然而，这种控制方法伴随着非线性动力学、严格的安全约束以及数值优化的挑战，进而使得控制操作变得对人类操作员而言不透明，从而降低了信任度并阻碍了其部署。
### Innovation
本文提出了层级因果推断（HCA），该方法结合了(i)基于领域知识图谱的物理信息推理，(ii)KKT多重乘数的优化证据，以及(iii)PCMCI算法的时间因果发现，以生成非线性MPC计算出的控制操作的忠实、可解释的说明。HCA在三个不同的控制应用（温室气候、楼宇暖通空调、化学过程工程）中得到了专家的验证，其解释准确性相比LIME提高了53%，并在特定领域的KKT阈值校准后进一步提高到0.88。消融研究证实每个证据来源对于解释都是必不可少的。
### Conclusion
相比之下，一旦移除任何部分，准确性的下降幅度在32%至37%之间。同时，HCA的排名和验证方法适用于模型预测控制之外的其他预测决策系统，如基于学习的控制和轨迹规划。
## 10. `cs.AI` - diffGHOST：基于扩散生成的博弈隐秘合成轨迹 [PDF](https://arxiv.org/pdf/2605.10647), [HTML](https://arxiv.org/abs/2605.10647)
### Authors
Florent Guépin,Cheick Tidiani Cisse,Denis Renaud,François Bidet,Arnaud Legendre
### Background
轨迹数据如今在众多应用中具有重要价值，但同时它们也含有高度个人化的信息，面临高度敏感性问题。为了解决这一挑战，合成移动轨迹已成为一种有前景的解决方法，能够在获取移动信息的同时保护隐私。然而，现有的最先进的模型往往依赖于生成模型隐含的隐私保护假定，在保持轨迹效用的同时未能提供隐私保证。
### Innovation
本文引入了一种基于潜在空间分段的条件扩散模型diffGHOST，旨在解决这一挑战。该模型通过条件分割的潜在空间来识别并缓解关键样本的记忆性问题，从而能够同时保持轨迹的效用和用户的隐私。
### Conclusion
diffGHOST为解决生成轨迹数据的隐私保护问题提供了一种新型的方法。通过条件分割的潜在空间，diffGHOST能够在保持轨迹效用的同时，有效缓解纪念效应，提供更强的隐私保护。
## 11. `cs.AI` - 航行在LLM评估的海洋中：探究毒性基准中的的偏见 [PDF](https://arxiv.org/pdf/2605.10639), [HTML](https://arxiv.org/abs/2605.10639)
### Authors
Regina Gugg,Selina Niederländer,Andreas Stöckl,Martin Flechl
### Background
随着大语言模型（LLMs）在研究和行业中迅速推广，userparalleled》， unseren Leistung und vergleichbare Metri und in unterschiedlichenen Setup on beschrieben(), 迹深地挖掘了模型固有偏倚的不稳定性，表明更稳健和全面的安全性评估框架的迫切需要。
### Innovation
本研究创新性在于揭示了基准设置下的行为差异'on特别是将任务从填字补全转变为总结时显著增加了基准设置标记内容为有害的趋势; 一些基准设置在分析数据不同的环境下无法保持行为一致; 更进一步观察到到模型固有不稳定性表明更稳健和系统评估框架的重要性。
### Conclusion
本研究通过探究当前毒性标准中的被忽视的固有偏倚，这强调了建立更加稳健和全面的安全评估框架的迫切需要; 吠项实验结果表明对照变会设置下的基准行为存在显著差异; 以及针对分析数据差异揭示了当前标准在任务转换和和数据变动过程中不稳定性; 最终提出有必要开发更为全面稳健的基准系统以确保先进模型进行全面有效的安全评估。
## 12. `cs.AI` - Agent Beings 使用 Agent：Agent Cybernetics 是基础代理缺失的科学 [PDF](https://arxiv.org/pdf/2605.10754), [HTML](https://arxiv.org/abs/2605.10754)
### Authors
Xinrun Wang,Chang Yang,He Zhao,Zhuoyi Lin,Shuyue Hu
### Background
基于大型语言模型（LLM）的基础代理在数千步骤中感知、推理和执行，正迅速成为在开放长周期复杂任务中部署人工智能的主要范式。虽然具有重要意义，但该领域依旧主要依靠工程实践。虽然工程实践形成了有用的原始技能（工具循环、记忆库、托架、反思步骤），但它们通常是通过经验试错而非从第一原理构建的。基础代理在长时间运行中保持任务状态、超出表示能力时的应对策略、安全自改进所需的架构特性等基本问题仍未解决。
### Innovation
本文通过将古典控制论的六条基本法则映射到六条代理设计原则，进而合成为三条工程目标（可靠运行、终身运行和自我改进），提出了一个名为代理控制论的框架。该框架通过三个应用领域（代码生成、计算机使用和自动化研究），识别出失败模式并提供了具体的工程建议。作者认为，代理控制论为解决基础代理的研究提供了新的研究视角和科学基础，有助于其在实际中的有原则和可靠的部署。
### Conclusion
代理控制论提供了基础代理需要的科学基础，将帮助这种代理实现有原则和可靠的现实世界应用。
## 13. `cs.AI` - PRISM：多代理LLM管道中敏感信息泄露的生成时检测与缓解 [PDF](https://arxiv.org/pdf/2605.10614), [HTML](https://arxiv.org/abs/2605.10614)
### Authors
Riya Tapwal,Abhishek Kumar,Carsten Maple
### Background
多代理语言模型系统存在一个安全风险，即一个代理访问的敏感信息可以通过共享上下文传播并在下游输出中重新出现，即便没有明确的敌对意图。现有防御措施，包括基于提示的保障、静态模式匹配和LLM作为裁判的过滤，都并非针对这一情境设计：它们通常是在生成后运作，主要依赖表面形式的模式，或在不建模生成过程的情况下增加显著的延迟。现有的这些方法都不能很好地处理这一问题。
### Innovation
本文提出了PRISM，一种实时防御机制，将其视为生成过程中连续的风险累积问题。在每次解码步骤中，PRISM结合了16种信号（包括词法、结构、信息论、行为和上下文特征），生成一个校准的风险评分，从而实现针对单个标记进行干预。它通过测量生成动力学中的熵崩溃和logit集中度增强来早期预警泄露风险。PRISM在2000个任务的对抗基准测试中表现优异，覆盖13类攻击、三个压力水平的异构四代理管道，其F1值为0.832，准确率为1.000，召回率为0.712，且在基准测试中未观察到任何泄露（0.0%任务级泄露率），同时保留了输出的0.893的实用性，远优于最强基线Span Tagger，后者的F1值为0.719，且任务级泄露率为15.0%。
### Conclusion
PRISM在检测与缓解多代理LLM管道中敏感信息泄露方面表现出色，通过实证研究表明，它能够有效减少泄露事件，同时保持高实用性。
## 14. `cs.AI` - Micro-Defects Expose Macro-Fakes: Detecting AI-Generated Images via Local Distributional Shifts [PDF](https://arxiv.org/pdf/2605.09296), [HTML](https://arxiv.org/abs/2605.09296)
### Authors
Boxuan Zhang,Jianing Zhu,Qifan Wang,Jiang Liu,Ruixiang Tang
### Background
最近的生成模型能够产出高度逼真图像，这增加了区分真实和AI生成图像的难度。现有的基于预训练特征提取器的检测器倾向于过度依赖全局语义，而未能敏感地捕捉至关重要的微小异常。
### Innovation
提出了一种名为Micro-Defects expose Macro-Fakes（MDMF）的局部分布感知检测框架，该框架通过放大微观统计异常为宏观分布差异来检测AI生成图像。引入了可学习的Patch Forensic Signature，将语义补丁嵌入投影到一个紧凑的法医潜在空间。采用最大均值离散性（MMD）衡量生成图像与真实图像之间的分布差异，并通过理论分析证明了在生成图像中存在的法医信号可以导致更大的分布差异，从而实现更可靠的真实图像分离。
### Conclusion
广泛的实验表明，MDMF在多个基准测试中始终优于基线检测器，验证了其普遍有效性。
## 15. `cs.AI` - MC$^2$: Monte Carlo Correction for Fast Elliptic PDE Solving [PDF](https://arxiv.org/pdf/2605.09288), [HTML](https://arxiv.org/abs/2605.09288)
### Authors
Ethan Hsu,Hong Meng Yam,Ivan Ge
### Background
传统的偏微分方程(PDE)求解器是科学研究的基础，但在实际部署中受到计算能力的限制。经典的 Walk-on-Spheres (WoS) 蒙特卡洛求解器虽然无偏且不依赖几何结构，但计算速度较慢。而基于学习的求解器虽然速度快但会因分布偏移而产生偏差。
### Innovation
本文提出了MC$^2$，这是一种将低预算Monte Carlo求解器的结果作为结构化的估计值，并利用单次前向传播学习神经网络修正，从而实现高保真度求解的混合沃斯-神经网络（WoS-NN）PDE求解器。MC$^2$能显著超越所有评估的经典、降噪及神经算子基线，为有限计算环境下PDE求解奠定了实验基础。
### Conclusion
MC$^2$ 和 PDEZoo 一起实证证明了有限样本的蒙特卡洛误差是可结构化的、可学习的、单次前向传播可纠正的，并展示出其能够比仅用沃斯方法快约1000倍的速度解决PDE问题。此外，PDEZoo 提供了评价基础设施，填补了该领域此前的空白。
## 16. `cs.AI` - 通过数学推理探索SFT泛化：记忆定理而非实例 [PDF](https://arxiv.org/pdf/2605.09270), [HTML](https://arxiv.org/abs/2605.09270)
### Authors
Ruiying Peng,Mengyu Yang,Jing Lei,Xiaohui Li,Xueyu Wu,Xinlei Chen
### Background
监督微调（SFT）被广泛应用于特定任务的适应中，但近期的研究表明，它系统性地削弱了推理泛化能力。研究认为问题出在记忆本身，而非其目标：传统的SFT促使模型利用和记忆问题-解决方案对中的表面关联，从而在遇到表象变化的输入时变得脆弱。
### Innovation
提出了Theorem-SFT，重新定向监督目标，使模型学习如何应用规则，而不是关注答案的外观。Theorem-SFT在基准测试和不同模型系列中表现出普遍收益：在MATH上提高了8.8%，在GeoQA上提高了20.27%。单独微调MLP层就可达到全层的性能，表明前馈组件是推理规则的主要所在。研究引发了对泛化失败原因的新视角：泛化失败不是源于记忆机制，而是记忆了错误的归纳目标。
### Conclusion
泛化失败的根源不在于记忆机制本身，而在于记忆了错误的归纳目标。通过Theorem-SFT，模型被教导应用规则，而非仅仅记忆答案，从而提高了泛化能力。
## 17. `cs.AI` - 半监督神经超分辨率在网格基模拟中的应用 [PDF](https://arxiv.org/pdf/2605.09284), [HTML](https://arxiv.org/abs/2605.09284)
### Authors
Jiyeon Kim,Youngjoon Hong,Won-Yong Shin
### Background
网格基模拟可以提供高保真的偏微分方程（PDEs）解决方案，但通常需要精细网格来实现这样的准确性，这会导致巨大的计算开销。超分辨率技术通过从低成本的低分辨率(LR)解决方案重建高分辨率(HR)、高保真解决方案来减轻这种成本问题。然而，训练神经网络进行超分辨率通常需要大量的昂贵的HR监督数据。
### Innovation
提出了SuperMeshNet，这是一种HR数据高效、辅助消息传递神经网络（MPNNs）进行网格基模拟的半监督神经超分辨率框架。SuperMeshNet核心引入了互补学习，这是一种半监督方法，能够有效利用一小部分配对的LR-HR数据和大量的未配对的LR数据，通过两种联合训练的互补MPNN模型实现。此外，通过引入归纳偏置来丰富模型，并通过实验证明进一步提高了超分辨率性能。
### Conclusion
广泛的实验表明，SuperMeshNet在不使用归纳偏置的情况下要求90%的HR数据量来实现比完全监督基准更低的均方根误差（RMSE）。源代码和数据集可在给定的链接中获得。
## 18. `cs.AI` - 迈向大型语言模型的有效理论：一种表示学习方法 [PDF](https://arxiv.org/pdf/2605.09294), [HTML](https://arxiv.org/abs/2605.09294)
### Authors
Muhammed Ustaomeroglu,Guannan Qu
### Background
本文提出了代表有效理论（RET）框架，该框架通过学习宏观状态来描述大语言模型的计算过程，而不是微观细节。背景在于现有的方法多基于微观细节，而无法捕捉到宏观层次的重要结构。RET通过自监督目标（类似BYOL/JEPA）从隐藏状态轨迹中学习宏观状态，并将激活粗粒度化为宏观变量，这些变量保留了对预测和解释有意义的高层次结构。
### Innovation
创新点在于提出了RET框架，通过自监督学习的方法，将大语言模型的计算过程从微观层面提升到宏观层面，捕捉到更高的层次结构。具体创新包括采用了BYOL/JEPA式的自监督目标，学习宏观状态并将其细分为宏观变量，这些变量能够保持对预测和解释重要的高层次结构。
### Conclusion
通过RET，模型能够输出具有时间一致性并揭示推理过程中的“心理状态轨迹”的宏观状态，捕捉高层次语义结构，并支持早期预测行为结果（如奉承），还提供了因果操作手段以调控生成过程，使其趋向于可解释的计算阶段。这些结果表明，大语言模型的计算过程可以通过RET实现有用的、动态有意义的描述，这有助于解释、预测和干涉。
## 19. `cs.AI` - 轨迹的陷阱：走向理解并缓解代理记忆中的误关联 [PDF](https://arxiv.org/pdf/2605.09330), [HTML](https://arxiv.org/abs/2605.09330)
### Authors
Luoxi Tang,Rupali Rajendra Vaje,Yuqiao Meng,Sakshi Sunil Narkar,Weicheng Ma,Zeyu Ding,Dazheng Zhang,Zhaohan Xi
### Background
代理记忆使得大语言模型能够超越单一上下文窗口存储信息并在后续决策中重用，但同时也引入了一个新的风险：误关联，即检索的记忆携带有误关联的证据，并将错误的推理传播到下游决策中。尽管广泛使用代理记忆，这种风险依旧缺乏深入探索。现有研究主要集中在理解和评估代理记忆的效果和潜在问题，但尚未广泛讨论如何解决由于误关联带来的风险。
### Innovation
该研究从两个方面着手解决代理记忆中的误关联问题。首先，通过因果结构识别标准类型的误关联模式，并记录在轨迹级别的记忆中。诊断基于此基准的代理记忆系统显示，记忆在干净输入上改善了推理，但在误关联存在时却加剧了对这些模式的依赖性。其次，提出了一种名为CAMEL的即插即用校准方法，可以在写入和检索时在各种记忆架构上运行。CAMEL方法在所有三种类型中一致减少了对误关联模式的依赖，同时在干净输入上保持或改善了性能，并在针对校准的自适应攻击中保持鲁棒性。
### Conclusion
整体而言，CAMEL提供了一种原理和技术相结合的轻量级解决方案，以确保代理记忆的可靠部署。
## 20. `cs.AI` - 长时序Q学习：通过n步不等式实现精确的价值学习 [PDF](https://arxiv.org/pdf/2605.05812), [HTML](https://arxiv.org/abs/2605.05812)
### Authors
Armaan A. Abraham,Lucy Xiaoyang Shi,Chelsea Finn
### Background
off-policy、基于价值的强化学习方法，如Q学习因其可以从任意经验学习，包括由旧策略或其它代理收集的数据而受到青睐。但在实践中，自我强化（bootstrapping）使得长时间学习变得脆弱：在状态估计中的误差会通过时间差分（TD）更新向后传播，并随着时间累积。
### Innovation
本文提出了长时序Q学习（LQL），它通过引入一种针对累积错误的原理性遏制机制，解决了Q学习中长时序学习的脆弱性问题。LQL将先前的最优性紧缩观察应用到实践稳定机制中，使用一个分段线性损失函数来惩罚这些界限的违约，这种方法无需额外的辅助网络或额外的正向传递。
### Conclusion
将LQL与多个前沿方法结合应用于各种在线和离线到在线基准测试中，LQL在相似的运算时间内总能超越单步TD学习和n步TD学习，从而在精度和效率上表现出色。
## 21. `cs.AI` - Workspace-Bench 1.0: Benchmarking AI Agents on Workspace Tasks with Large-Scale File Dependencies [PDF](https://arxiv.org/pdf/2605.03596), [HTML](https://arxiv.org/abs/2605.03596)
### Authors
Zirui Tang,Xuanhe Zhou,Yumou Liu,Linchun Li,Weizheng Wang,Hongzhang Huang,Jun Zhou,Jiachen Song,Shaoli Yu,Jinqi Wang,Zihang Zhou,Hongyi Zhou,Yuting Lv,Jinyang Li,Jiashuo Liu,Ruoyu Chen,Chunwei Liu,GuoLiang Li,Jihua Kang,Fan Wu
### Background
现有的基准主要评估代理在预制或合成文件上的性能，这些文件具有有限的真实世界依赖关系，这种程度的工作空间评估相对较少。现有研究未能全面评估AI代理在处理真实工作空间时的能力，特别是涉及大量文件依赖关系的工作任务。
### Innovation
本研究提出了Workspace-Bench，这是一个用于评估AI代理在具有大量文件依赖关系的工作空间学习任务上的基准。该基准使用5种工人类型、74种文件类型、20,476个文件构建了真实的工作空间，并编制了388个任务，每个任务具有自己的文件依赖关系图。此外，还提供了Workspace-Bench-Lite，这是一个包含100个任务的较小版本，减少了评估成本约70%。
### Conclusion
实验结果表明，当前的代理在工作空间学习中仍远未可靠，最佳表现仅约为60%，远低于人类的结果80.7%，并且代理之间的平均性能仅为45.1%。
## 22. `cs.AI` - 干预复杂性作为典范奖励与智能测量 [PDF](https://arxiv.org/pdf/2605.02175), [HTML](https://arxiv.org/abs/2605.02175)
### Authors
Brendan McCane
### Background
Legg--Hutter的通用智能度量提供了一个严格的标量评估，作为所有可计算环境中预期奖励的总体智能度量，权重为简单性。然而，该度量的前提是一个外部指定的奖励函数，提出了奖励基元是否固然是任意的或是否有一个标准选择的问题。
### Innovation
提出了一个称为干预复杂性的新度量，它具有五个自然属性：环境产生的、普遍的、最小的、敏感的和成就偏好。基于编码归纳偏好的资源函数（如程序长度、执行时间和能量），ρ-干预复杂性成为一种通用奖励。进一步提出了智能的二维表征：代理能力（相对于预言者最优的标准代理行为）和学习效率（经验增长时这种能力提高的速度）。分离定理表明，资源偏好的选择决定了最终度量的可计算性：行动计数IC在多项式时间内可计算，而没有预言者访问的程序长度IC是不可计算的。”“裸IC与预言者IC之间的差距精确量化了学习中的信息理论内容。”
### Conclusion
研究了超智能和预训练通用代理的含义。
## 23. `cs.AI` - 一种用于罕见疾病诊断和风险基因优先级确定的多功能AI代理 [PDF](https://arxiv.org/pdf/2605.06226), [HTML](https://arxiv.org/abs/2605.06226)
### Authors
Tianyu Liu,Wangjie Zheng,Rui Yang,Benny Kai Guo Loo,Hui Zhang,Jeffries Lauran,Jianlei Gu,Botao Yu,Weihao Xuan,Kexin Huang,Nan Liu,James Zou,Yonghui Jiang,Hua Xu,Hongyu Zhao
### Background
准确和及时的诊断对于有效治疗至关重要，尤其是在罕见疾病的背景下。然而，当前的诊断工作流程经常导致评估时间延长和低诊断准确性。
### Innovation
我们介绍了Hygieia，这是一个多模态的人工智能代理系统，旨在通过整合表型特征、遗传资料和临床记录等多来源数据来支持精准疾病诊断。Hygieia采用基于路由器的和知识增强的框架，减轻幻觉并针对不同类型疾病定制诊断策略。特别地，它优先考虑与罕见疾病相关的基因风险因素，并提供信心评分以协助临床决策。
### Conclusion
我们的研究证明，Hygieia在多个诊断标准上达到了最先进的性能。通过与耶鲁医学院和杜克—那那慕斯医学科学院的临床专家合作，我们进一步验证了其实用价值，包括（1）与专业医生相比，Hygieia的诊断性能提高了12%-60%；（2）其在处理实际病例时协助医护人员的能力。我们的发现表明，Hygieia不仅提高了诊断的准确性和可解释性，还显著减少了医务人员的工作量，突显了其在临床决策支持系统中的潜在价值。
## 24. `cs.AI` - 过程比输出更重要，用于区分人类与机器 [PDF](https://arxiv.org/pdf/2605.06524), [HTML](https://arxiv.org/abs/2605.06524)
### Authors
Milena Rmus,Mathew D. Hardy,Thomas L. Griffiths,Mayank Agrawal
### Background
随着大型语言模型和自主代理在在线环境中的部署，可靠的人机区分变得越来越重要。当前的方法关注系统能否产生与人类行为或响应无法区分的输出，以评估其智能。认知科学提出了另一种视角：评估行为产生的过程。为了测试认知过程能否可靠地区分人类和机器，本文引入了包含30项认知任务的CogCAPTCHA30，这些任务旨在即使任务性能匹配，也能提取诊断过程特征。通过该测试，过程特征提供了比仅依赖性能指标更强的区分信号，在匹配输出的情况下可靠地将人类与代理区分开（均值过程特征分类器AUC = 0.88）。
### Innovation
本文提出了CogCAPTCHA30，这是一种包含30项认知任务的测试，旨在即使任务性能匹配，也能检测出诊断的过程水平特征。该测试揭示了过程特征相比仅依赖性能指标提供了更强的区分信号，并引入了针对大型语言模型以及代理的特定工作和过细调整方法，以更进一步模仿人类行为。
### Conclusion
广泛微调人类决策可以相对改善大型语言模型的人类任务过程，而针对特定任务的过程水平监督进一步改善了行为模仿。然而，这种优势在跨任务迁移时会减弱，因为监督的过程目标可能不会自然地适应不同的任务。明确的过细过程监督可以改善人类行为的模仿，但前提是必须有适用于特定任务的过程表示，这强调出了过程描述作为实现人类级认知过程的关键瓶颈。
## 25. `cs.AI` - RL能否教会LLMs进行长时推理？表达能力是关键 [PDF](https://arxiv.org/pdf/2605.06638), [HTML](https://arxiv.org/abs/2605.06638)
### Authors
Tianle Wang,Zhaoyang Wang,Guangchen Lan,Xinpeng Wei,Sipeng Zhang,Guanwen Qiu,Abulhair Saparov
### Background
尽管将强化学习（RL）应用于提升大型语言模型（LLM）的推理能力取得了进展，但缺乏系统研究训练量随任务难度变化的方式，主要原因是缺少可控的、可扩展的环境。以往观察到LLM在长时推理中的局限性，可能导致认为这些局限性是归因于自回归变换器架构的固有问题。
### Innovation
研究人员提出了ScaleLogic，一个可独立控制两个难度维度的合成逻辑推理框架，即推理深度（即，时间跨度）和底层逻辑的表达性。该框架支持从简单的假设逻辑、“if-then”到更复杂的基于一阶逻辑的推理，包括合取、“and”、析取、“or”、否定、“not”和全称量化的所有逻辑。通过ScaleLogic，他们展示了RL训练计算量T与推理深度D之间遵循幂定律关系（T ∝ D^γ，R² > 0.99），并且数值γ随着逻辑表达性的增加而单调增加。另外，他们通过多个RL方法证明了这种关系的普适性，并证明了基于课程的训练能显著提高扩展效率。
### Conclusion
研究结果表明，LLM在长时推理中的局限性并非源于底层架构的固有问题，而是由于训练方法和数据的不足。通过提高训练设置的表达性，可以显著提升模型在下游任务上的性能表现和计算效率。
## 26. `cs.CL` - 大型语言模型的功能元认知分解与引导 [PDF](https://arxiv.org/pdf/2605.08942), [HTML](https://arxiv.org/abs/2605.08942)
### Authors
Yanshi Li,Xueru Bai,Shuman Liu,Haibo Zhang,Anxiang Zeng
### Background
大型语言模型（LLMs）在评估环境中表现出对自身评估背景的认知意识，这种现象可能导致其在基准测试中的表现测量出现偏差。然而，这种现象是否仅体现了单一的行为特征，还是反映了模型内部更深层次的结构存在争议。
### Innovation
本文提出，LLMs在内部维护一个可分解的功能元认知状态空间，这包括评估意识、自我评估能力、感知风险、计算资源分配、观众专家适应性以及意图等因素。通过残差流分析在多个推理模型中，研究发现这些状态可以从内部激活中线性解码，并在每一层中表现出不同的特征轮廓。通过引导模型激活沿探针衍生的方向，研究进一步展示了每个功能元认知状态对推理行为的因果调节方式，从而影响任务中的冗长性、准确性和与安全相关的响应。
### Conclusion
研究发现，基准测试中的表现不仅反映任务能力，还可能反映了特定功能元认知状态的激活。理解并控制这些内部状态对于实现可靠的推理模型评估和部署至关重要，本文提供了研究人工系统功能元认知的机制性框架。相关代码和数据已公开在指定链接处。
## 27. `cs.CL` - LLM-不可知论的语义表示攻击 [PDF](https://arxiv.org/pdf/2605.08898), [HTML](https://arxiv.org/abs/2605.08898)
### Authors
Jiawei Lian,Jianhong Pan,Lefan Wang,Yi Wang,Tairan Huang,Shaohui Mei,Lap-Pui Chau
### Background
大型语言模型（LLMs）越来越多地采用对齐技术来防止生成有害输出。尽管这些技术有所保障，但攻击者可以通过精心构造的对抗性提示绕过它们。现有的主流Token级优化方法主要依赖于优化具体肯定模板（例如，“textit{Sure, here is...}”），然而这种方式面临着诸多问题，如收敛效果不佳、提示的自然性受到损害和跨模型泛化能力不足。针对这些问题，论文提出了语义表示攻击（SRA）作为一种新的LLM无关的方法，从根本上重新定义了从精确文本目标到恶意语义表示的对抗性目标。
### Innovation
本文提出了语义表示攻击（SRA），重新定义了对抗性目标，从精确文本目标转向可能的恶意语义表示。开启了语义层面的对抗性攻击研究。论文还理论地建立了语义一致性与收敛性的关系，并推导出跨模型语义泛化界限，证明语义一致性能够保障白盒语义收敛和黑盒可转移性。技术层面上，论文通过语义表示启发式搜索算法（SRHS），在分段Token扩展中保持意图解释性和结构一致性。通过广泛的试验，验证了该框架能够在26种开源LLMs上实现99.71%的平均攻击成功率，并且具有较强的可转移性和隐蔽性。
### Conclusion
本文的研究结果表明，通过语义表示攻击可以有效应对现有Token级优化方法的不足，该方法在多种LLM上都能保持高效和隐蔽的攻击效果。未来该方法可以用于评估和改进LLM的安全性，进一步研究如何提高对抗样本的通用性和隐蔽性，并探索在更多场景下的应用。
## 28. `cs.CL` - LLiMba：使用单个GPU适应3B参数语言模型的撒丁语 [PDF](https://arxiv.org/pdf/2605.09015), [HTML](https://arxiv.org/abs/2605.09015)
### Authors
Luca Ballore
### Background
撒丁语是罗曼语族中大约有一百万使用者的语言，但在现代自然语言处理（NLP）领域几乎没有存在感，商业服务不支持它，现有的语言模型也无法可靠地生成它。本文介绍了LLiMba，这是一个通过持续预训练（CPT）和监督微调（SFT）适应撒丁语的3亿参数模型，适应工作是在单个24GB的消费级GPU上进行的。
### Innovation
引入了LLiMba，这是一种通过持续预训练和监督微调适应撒丁语的3亿参数模型。模型的适应工作是在单个消费级GPU上进行的。特别地，研究者比较了五种不同的微调配置，发现排名为r256的rsLoRA配置在所有旨在转换为撒丁语的方向上表现最佳。此外，研究还揭示了打分消融实验中各种配置的表现和发展，这不仅衡量了其定量表现，而且还揭示了定量度量无法捕捉的定性差异。
### Conclusion
研究结果显示，适配器容量比在罗曼语预训练基础模型上适配罗曼低资源目标的洛RA变种选择更重要，更强的正则化不总是有益的，并且翻译评价指标平滑地将具有不同定性行为的模型排列起来。此外，跨脚本的困惑度比较需要考虑字节回退标记化，这会使得对于除拉丁语以外的脚本降低指标值。
## 29. `cs.CL` - GAMBIT: 一个多模式基准测试，用于多智能体LLM集体的对抗鲁棒性 [PDF](https://arxiv.org/pdf/2605.09027), [HTML](https://arxiv.org/abs/2605.09027)
### Authors
Alexandre Le Mercier,Chris Develder,Thomas Demeester
### Background
在多智能体系统（MAS）中，单一欺骗性智能体可以毁掉整个由机构人工智能集体获得的利益，并且能够逃避部署的防御措施。然而，现有的针对MAS的对抗性研究仅针对浅层任务，未考虑适应性对手，这些对手会进化他们的策略来逃避已经训练用于捕捉它们的检测器。为此，该研究引入了GAMBIT基准测试，旨在填补这方面的空白。
### Innovation
GAMBIT是一个具有三种评估模式和两个独立评分的基准测试，用于评估冒名顶替检测器。它包括一个包含27,804个标签实例、跨越240种共生进化冒名策略的数据集。其贡献包括：（1）使用国际象棋作为潜在的深度推理问题和Gemini 3.1 Pro作为代理，GAMBIT和其数据集被释放出来，以评估冒名顶替检测器在现实约束条件下对抗隐身适应性冒名者的效果；（2）介绍了一种基于高效进化框架的适应性冒名顶替智能体，该框架不仅适用于国际象棋，还可以使集体任务性能崩溃，同时几乎完全不可被检测（使用基于Gemini的检测器时的F1分数为50.5%）；（3）证明了对于适应性对手，零样本评估可能会非常高误导：具有几乎相同的零样本评分的两种检测器在少量样本自适应上的差异高达8倍，而元学习的变体快20倍，这种差异仅在重新校准模式中可见。
### Conclusion
GAMBIT为多智能体系统中与对抗性攻击和防御共同进化提供了一个先例，该冒名顶替框架具有超越应用场景的一般性，并有望在其快速进化的对抗系统中用于快速重新校准的技术。
## 30. `cs.CL` - 情感意义偏差中的相变：隐藏在断裂前的缓慢趋势 [PDF](https://arxiv.org/pdf/2605.09043), [HTML](https://arxiv.org/abs/2605.09043)
### Authors
Napassorn Litchiowong
### Background
研究讨论了对话伙伴之间的情感意义偏差（AMD），一种单个词语在双方被赋予不同情感意义的现象。这里构建了一个基于言语行为理论、共同背景积累以及熵正则化博弈论的数学模型来描述AMD的变化动态，并探讨了在对话崩盘（CGA）过程中AMD的变化。
### Innovation
提出了情感意义偏差（AMD）的概念，并基于AMD构建了一个逻辑最优反应法则，发现在βα>4时，amd驱动的负担增加会导致修复协调的突然失稳。通过分析On Conversations Gone Awry (CGA-Wiki; N=652) 数据集，发现对话崩盘时存在多个层次的关键性迟滞迹象，而AMD作为唯一与理论框架相一致的指标，提供了独特的时序特征。
### Conclusion
在边界条件分析中（CGA-CMV; N=1,169），尽管证据混杂但方向一致，研究证实了AMD作为对话修复协调崩塌前的早期指标的重要性，并强调了AMD在理解对话进程中情感意义变化的重要性。
## 31. `cs.CL` - Evaluating Pragmatic Reasoning in Large Language Model: Evidence from Scalar Diversity on [PDF](https://arxiv.org/pdf/2605.09042), [HTML](https://arxiv.org/abs/2605.09042)
### Authors
Ye-eun Cho
### Background
评价大型语言模型（实用推理方面仍面临挑战， 模型行为可能因响应不同给定的提示有所不同。。 有研究表明，在 基于提示的判断可能判定和模型内部概率分布之间的差异可能导致对模型性能反映的能力和训练所 的行为疑问。 本研究旨在通过将霍与莱维（2 3年）提出的标量多样性作为一种分级诊断工具来解决这一问题, 通过在不同 夰多种模型和实验设置中 包括直接概率测量和元提示的范式 on 肨的的分类多样性梯度仅在特定的实验条件组合中出现， 暗示实用推理现象在大型语言模型中反映的是内部概率推理与由诱导的提示行为之间的互动而不是单一评估范式的下的稳定能力。
### Innovation
本研究创新性使用将实现将标量多样性作为一种分级诊断工具用于评价大型语言模型中的实用推理行为 on 通过比较直接概率测量与元提示的两种范式在多个模型和 大行中的差异 on 以及在特定实验条件组合中 的表现 on 从而揭示出实用推理行为在大型语言模型中的 是由 内部概率推理和 与 莫的提示行为之间的一种互动效果， 与单一评估范式下的稳定能力假设存在显著差异。
### Conclusion
研究表明 on 基础标量多样性梯度在特定实验条件组合中才开始显现 outperformance， 叆以及的方法 on 均未表现出绝对的优势 on 说明实模型在实用推理上的行为变增加了可以通过不同 夎内部的概率推理与外部的提示行为之间的互动来解释 on 与单一的评估范式不能完全捕捉这一复杂的推理过程 on 这因此强调在解读大型语言模型的实用推理能力时 膂需要综合考虑模型内部与外部多个因素的相互 互动影响 不能简单地依靠单一的评估方法。
## 32. `cs.CL` - 量子启发式变分核核与可可解释性型人工智能框架的跨地区太阳能和风能能预测研究 [PDF](https://arxiv.org/pdf/2605.09032), [HTML](https://arxiv.org/abs/2605.09032)
### Authors
Pavan Manjunath,Thomas Prufer
### Background
可靠的太阳能和风能能发电经过系统的可靠短期预测是现代电网系统的一个结构上的的前提。大多数已发布的预测模型主要常是在单一气候区间上并进行参数调整和评估，且主要在算法上的新颖性上主要集中在传统递归神经网络上 on以及整体式基础模型上 main这些模型同时承担预测和解释功能。但但是本文研究提出了一种四fort四四层次结构预测框架 that包括四个步骤。首先是获取小时发电光照辐射和 on and及表面程序接口 on面 on阶段提供了三种经典的基线线线拟—— on on自动回归模型、梯度提升树增强模型以及两个定面神经网络 on and on一种最终的预测模型结合 another产生残差余误差 an on阶段是一种基于六量子比特硬件有效答案套 on一种六量子比特硬件高效算答案 with 的三层纠缠层 on最后 step一阶段是一种生成型人工智能 on on面向表面表面层的析法， in用于处理真实基准数字 on on具备结构化自然语言解释 in该三个区域源自表面表面上档案 Iber 犟的north面北海 on on以及混合德克得三面德层
### Innovation
该引入了一种基于量子启发式变分 on变核 on核核核的可 on变异核结构 on on提出 force个预测框架 that on这框架引入了四个层次多全个层次步骤：方法步骤明确区分结构化Natural on和自然语言解释能力 on on最后一步基 on on on面上神经网络表面处理真实数据 bas线 n并没有为on最终提供了强当前余误差处理甲一量子面建的基础 on on上面上量子启发式变异变核核核面的常解释能力 on on这显着提高了模型性能与 on并多个不同困难模型和 on on在复杂天气可以惯处理方 on on showed表现了量子启发式核核核的在复杂天气环境上的优越性能 with on on on十五倍于 on on对频比调幅径基础上的的核核径核核性能上 on on这为建立给数预测提供了新的方向 on on on on同时 on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on on-on conclusion adultes
### Conclusion
 on本研究提出的一种新颖的基于量子启发式变r onk变 on on on on核面上的的模型框架 on on on on这框架能 on在on on多种场景步种困难模型和 on on on on个十字地区s西德三面 圂色的基 on on on on上 on线础能预测任务上 on以及复杂在复杂天气条件上 on strong on上有良好的on on突出性能表现这这表明 on on on on on novel机启发式变面核核在复杂天气预测上的优势 参年这一点为僵硬的预测提供了新方向 on on on on基于自然此模型框架可以进一步在实证研究上一更强性能和表现高增强预报能力上 on on on在复杂的天气预测条件条件中表现 on on on on同时上于在实证研究中深入一一步进一步验证其效果 on on on on
## 33. `cs.CL` - TELL-TALE: Task 效率 LLMs 与 Task 意识层剔除 [PDF](https://arxiv.org/pdf/2510.22767), [HTML](https://arxiv.org/abs/2510.22767)
### Authors
Omar Naim,Krish Sharma,Niyar R Barman,Nicholas Asher
### Background
现有的大语言模型通常采用固定架构，尽管越来越多的证据表明，并非所有层次在每个下游任务中的作用都相同。因此，如何根据特定的任务需求调整大语言模型的架构成为一个重要研究方向。
### Innovation
作者提出了TALE（Task-Aware Layer Elimination），这是一种在推理时根据任务特性选择性去除无关或有害层的方法。TALE能够在不重新训练的情况下优化特定任务的性能，同时减少了计算成本。并且TALE与微调结合使用，还能进一步提高性能。
### Conclusion
TALE 方法在 9 个任务和 5 种模型家族中表现优异，在零样本和少量样本设置下，TALE 不仅匹配或超越了基线模型，还能显著降低计算成本。TALE 方法对于新任务的计算资源需求适中，是任务专用大语言模型推理的一种可行和可部署的方案。
## 34. `cs.CL` - LILO: 使用自然语言反馈的贝叶斯优化 [PDF](https://arxiv.org/pdf/2510.17671), [HTML](https://arxiv.org/abs/2510.17671)
### Authors
Katarzyna Kobalczyk,Zhiyuan Jerry Lin,Benjamin Letham,Zhuokai Zhao,Maximilian Balandat,Eytan Bakshy
### Background
许多现实世界的优化问题受到复杂且主观的偏好驱动，这些偏好难以用明确的封闭形式目标表达。为了解决这一问题，本文介绍了一种名为 Language-in-the-Loop Optimization (LILO) 的框架。LILO 使用大型语言模型（LLM）将决策者的自由文本反馈和先验知识转化为结构化的偏好信号，从而超越了传统偏好贝叶斯优化中常见的标量或成对反馈假设。
### Innovation
LILO 引入了一种使用大型语言模型（LLM）将自由形式的自然语言反馈和先验知识转化为结构化偏好信号的新框架，以克服传统偏好贝叶斯优化的限制。LLM 得出的偏好信号通过高斯过程代理模型进行整合，能够进行具有校准不确定性驱动的探索。LILO 通过使 LLM 在支持角色而非作为优化器本身，保留了贝叶斯优化中的样本效率和稳定性，并提供了一种灵活且富有表现力的反馈接口。在合成和真实世界基准测试中，LILO 在所有基准中表现出色，特别是在反馈有限的情况下表现尤为突出。
### Conclusion
LILO 为了优化具有复杂和主观偏好的问题，通过将语言模型转化为结构化偏好信号来超越了传统反馈假设，该方法在多个基准测试中表现出更高的性能。
## 35. `cs.CL` - 探求人工智能推理的临界点（CritPt）：前沿物理研究基准 [PDF](https://arxiv.org/pdf/2509.26574), [HTML](https://arxiv.org/abs/2509.26574)
### Authors
Minhui Zhu,Minyang Tian,Xiaocheng Yang,Tianci Zhou,Lifan Yuan,Penghao Zhu,Eli Chertkov,Shengyan Liu,Yufeng Du,Ziming Ji,Indranil Das,Qingzhi Chen,Junyi Cao,Yufeng Du,Jiabin Yu,Peixue Wu,Jinchen He,Yifan Su,Yikun Jiang,Yujie Zhang,Chang Liu,Ze-Min Huang,Weizhen Jia,Yunkai Wang,Farshid Jafarpour,Yong Zhao,Xinan Chen,Jessie Shelton,Aaron W. Young,John Bartolotta,Wenchao Xu,Yue Sun,Anjun Chu,Victor Colussi,Chris Akers,Nathan Brooks,Wenbo Fu,Jinchao Zhao,Marvin Qi,Anqi Mu,Yubo Yang,Allen Zang,Yang Lyu,Peizhi Mai,Christopher Wilson,Xuefei Guo,Juntai Zhou,Daniel Inafuku,Chi Xue,Luyu Gao,Ze Yang,Yaïr Hein,Yonatan Kahn,Kevin Zhou,Di Luo,John Drew Wilson,Jarrod T. Reilly,Dmytro Bandak,Ofir Press,Liang Yang,Xueying Wang,Hao Tong,Nicolas Chia,Eliu Huerta,Hao Peng
### Background
近年来，大型语言模型（LLMs）在高中数学竞赛和编程中的推理能力得到了快速发展，但对于复杂且开放性的前沿物理研究挑战，它们能否有效地进行推理尚不清楚。研究者希望了解这些模型能够辅助物理学家进行哪些类型的推理任务。为此，本文提出了CritPt基准测试，这是第一个专门针对未公开的、研究级别的推理任务的测试，涵盖了现代物理学的多个领域，包括凝聚态物理学、量子物理、原子分子光学物理学、天体物理学、高能物理学、数学物理学、统计物理学、核物理学、非线性动力学、流体力学和生物学物理学等。
### Innovation
CritPt基准测试设计了一个含有71个综合研究挑战的测试，每个挑战进一步分解为190个更细化的任务。这些挑战的题目由50多名活跃的物理学家基于他们自己的研究新创造。所有的问题都被手工策划，以确保具有猜忌难、机器可验证的答案，并且由高度定制的自动化评分管道进行评估。研究发现，当前最先进的LLM在孤立的检查点上初现希望，但在解决完整的研究级挑战方面仍然远远不够：基础模型的最佳平均准确率仅达到5.7%（GPT-5高版），在配备编程工具后也只能略有提升至约10%。通过CritPt提供的现实且标准化的评估，明确了当前模型能力与现实物理研究需求之间的巨大差距。
### Conclusion
CritPt基准测试揭示了当前模型能力与物理研究要求之间的巨大差距，强调了指导科学基础AI工具发展的基础。
## 36. `cs.CL` - 视觉文档检索中基于注意力的增强方法 [PDF](https://arxiv.org/pdf/2511.13415), [HTML](https://arxiv.org/abs/2511.13415)
### Authors
Wanqing Cui,Wei Huang,Yazhi Guo,Yibo Hu,Meiguang Jin,Junfeng Ma,Keping Bi
### Background
视觉文档检索需要理解各种多模态内容以满足隐含的信息需求。最近的技术使用基于屏幕快照的文档编码并结合精细的后期交互来编码整体信息和捕捉细微的对齐方式，显著提高了检索性能。然而，现有的检索器仍然使用粗略的整体相关性标签进行训练，未能揭示哪些区域支持匹配。这导致检索器倾向于依赖表面级线索，难以捕捉隐含的语义连接，从而限制了其处理非抽取信息的能力。
### Innovation
本文提出了一个基于注意力的检索增强框架（AGREE）。该框架利用多模态大型语言模型（MLLM）的跨模态注意力作为代理监督，指导检索器识别相关的文档区域。具体而言，AGREE从MLLM中提取注意力图，该图突出显示了根据查询的重点关注的文档区域。这些注意力分数作为局部、区域级别的相关性信号。在训练过程中，AGREE将局部信号与整体的文档级相关标签结合起来，共同优化检索器。这种双重监督使模型不仅能学习文档是否匹配，还能学习哪些内容驱动了相关性。实验结果表明，AGREE在具有挑战性的视觉文档检索基准ViDoRe V2上显著超越了仅使用全局监督的基线，平均nDCG@1和nDCG@5分别提高了12.82%和5.03%。
### Conclusion
定量和定性的分析进一步表明，AGREE促进查询术语与文档区域之间的更深对齐，超越表面级匹配，朝着更准确和可解释的检索迈进。我们的代码可在以下链接获取：[代码链接]。
## 37. `cs.CL` - 重新思考在数学推理中LLM后训练阶段专家轨迹的利用 [PDF](https://arxiv.org/pdf/2512.11470), [HTML](https://arxiv.org/abs/2512.11470)
### Authors
Bowen Ding,Yuhan Chen,Jiayang Lyv,Jiyao Yuan,Qi Zhu,Shuangshuang Tian,Dantong Zhu,Futing Wang,Heyuan Deng,Fei Mi,Lifeng Shang,Tao Lin
### Background
监督微调（SFT）和强化学习（RL）主导了数学推理的后训练环境，但它们在依赖专家轨迹上存在根本差异。为了理解如何最大限度地利用这些轨迹，本文提出了塑性天花板框架，该框架通过分解最终性能天花板为基础的SFT性能和后续的RL塑性（即通过RL的最大改进），实证奠定了后训练环境的基础。
### Innovation
本文提出了塑性天花板框架，通过分解最终性能天花板为SFT性能和RL塑性，它建立了顺序SFT-然后-RL流水线作为优标准准，解决了同步方法中固有的稳定性和过早收敛问题。此外，论文得出了精确的扩展指南：（1）在SFT的稳定或轻度过拟合阶段过渡到RL可最大化最终的天花板，既保障了稳健的SFT基础，也提供了大量的RL塑性；（2）反驳了SFT-然后-RL缩放中的“少即是多”假设，证明了数据量是主要的后训练潜力，而轨迹难度是性能的乘数；（3）SFT的最小验证损失是选择使最终性能天花板最大化的专家轨迹的可靠指标。
### Conclusion
研究结果提供了实用指南，以最大限度地从专家轨迹中提取价值。
## 38. `cs.CL` - MapFormer: 自主学习认知地图的输入依赖位置嵌入 [PDF](https://arxiv.org/pdf/2511.19279), [HTML](https://arxiv.org/abs/2511.19279)
### Authors
Victor Rambaud,Salvador Mascarenhas,Yair Lakretz
### Background
认知地图是一种内部模型，能够编码世界中实体之间的抽象关系，为人类和动物提供在新情境中适应的能力，而目前的AI系统还无法实现这种强大的离分布泛化能力（OOD泛化）。因此，本文旨在通过引入新的基于Transformer的架构——MapFormers，来填补这一差距。MapFormers可以从观察数据中学习认知地图，并在无需监督的情况下进行路径整合。
### Innovation
提出了MapFormers架构，该架构可以在模型中学习认知地图，同时实现路径整合，并且通过更新位置嵌入的方式将输入依赖的矩阵引入，从而能够区分输入中的结构性关系和具体内容。MapFormers还提出了两种变体，它们分别用于建模情景记忆（EM）和工作记忆（WM），通过结合绝对和相对位置编码。研究在多个认知能力任务中测试了MapFormers的效果，结果表明其在标准模型失效的情况下实现了接近完美的OOD泛化能力，并且在自然数据测试中的困惑度也得到了提升，这表明该原理能够扩展到大规模的现实世界领域。
### Conclusion
通过有效的并行计算在可交换的映射上，MapFormers实现了显著的OOD泛化性能提升。此外，MapFormers还能够学习非可交换的认知地图，进一步证明了输入依赖的矩阵在驱动物理关系与内容分离，进而实现鲁棒OOD泛化的关键作用。
## 39. `cs.CL` - Knowledge is on Enough: Inject inject RL Skills for Continuously Adaptotyping [PDF](https://arxiv.org/pdf/2601.11258), [HTML](https://arxiv.org/abs/2601.11258)
### Authors
Pingzhi Tang,Yiding Wang,Muhan Zhang
### Background
大型语言模型（ (LLMs) 在会面临一个知识截止点的问题，，即督导精细调教 (SFT) 是一种常见的方法来来更新模型的知识已有的知识中。。 但是这种方法可能可能只能确保事实内容可靠地地更新进度中。此外，, 弰井决策中依赖于推理的技能， 豫合规则井调， ，常常需要借助强化学习 (RL) 来获取决策技能。 和然而 RL 在求解在线问题内有效在线线线线剂量在线线适应上 存在较高的计算 有效性挑战。研究表明 SFT 和 RL 的更新本来就是并不相冲突。基于这些动理解作者提出了一个参数化技能调教框架 (PaST)， 该框架旨在支持模块化技能调教，  并通过提取技能向量技能 和 在模型上 迷你 SFT 中 these 在知识融入问题中的回答任问题 (SQuAD on L onGLE) 和 基准技能运用 (ToolBench) 上显示了该的有效性。 on上 SFT 的基础上 PaST表现更加优越。”
### Innovation
本文PaST引入了一种全新的的方法”的的方法。实际技能的上理将这些技能通过弱化 ”- 绔出” * 技能注入拼音统一上线 瞋 在线 on模型上 中 当进行结构化技能 融合的灵活性上/以及有效地实施进行 适应性的模型调整。”  通过这一框架在性能--工具上 caseQA 和象LongLE上（ 上上获得了8..% 的精度提升 on to训练设置李工具上 Bench on 我们期许在更大的 数据集和证明该框架的可ability 在多元技能参数上 贀调教和和上 的上度和 跨领域域 上的 的转移能能力上 生的
### Conclusion
大型语言模型面临着知识 cut
## 40. `cs.CV` - 将带有CoT的3D空间推理提炼到轻量级的视觉语言模型中 [PDF](https://arxiv.org/pdf/2605.09719), [HTML](https://arxiv.org/abs/2605.09719)
### Authors
Alaa Asfour,Christopher Indris,Leihan Chen,Tejas Vyas,Guanghui Wang
### Background
现有的大规模3D视觉语言模型（VLMs）如LLaVA-3D虽然拥有强大的空间推理能力，但由于计算成本高，难以部署。本文旨在降低这一挑战。
### Innovation
提出了一种知识蒸馏框架，将7B参数的教师模型的空间推理能力转移到2.29B参数的学生模型上。利用VGGT作为视觉编码器，并采用包含不确定性感知损失加权的多任务蒸馏管道。此外，引入了“隐藏的CoT”方法，以在无需链式推理数据的情况下改进推理能力。该学生模型能够同时执行空间描述、深度估计和目标检测任务。
### Conclusion
在ScanNet和3D-FRONT数据集上进行的实验表明，模型具有强大的空间理解能力，实现了邻近和接触任务68-72%的准确率。该框架使3D场景问答能够在资源受限的平台上高效运行。
## 41. `cs.CV` - 分类判别性投影作为合成数据效用预测的分类器重构 [PDF](https://arxiv.org/pdf/2605.09697), [HTML](https://arxiv.org/abs/2605.09697)
### Authors
Radhika Amar Desai,Modigari Narendra
### Background
在许多实际的计算机视觉应用中，如医学成像和工业检测，二分类任务特征在于正样本极度稀缺。一种常用的方法是使用图像到图像的变换技术从负样本生成合成的正样本数据。然而，一个根本性的挑战是如何可靠地评估使用合成数据是否会提升下游模型性能。
### Innovation
本文提出了一种基于几何学的度量标准，可以在无需训练模型的情况下预测合成数据的效用。方法在预训练基础模型的嵌入空间中运作，通过表示样本间的差异向量来表示数据集。通过测量相对投影误差来判断线性分类器的权重向量是否能在这些变化构成的子空间中表达。实验表明，在多个数据集和模型架构上，该度量标准与基于真实负样本和合成正样本混合数据训练的CNN的下游分类性能高度相关。
### Conclusion
研究结果表明，所提出的方法为在样本稀缺条件下评估合成数据质量提供了一种实用且有信息量的方法。
## 42. `cs.CV` - ConFixGS: 在驾驶场景中使用意识置信扩散先验学习修复前馈3D高斯散点图 [PDF](https://arxiv.org/pdf/2605.09688), [HTML](https://arxiv.org/abs/2605.09688)
### Authors
Rui Song,Tianhui Cai,Markus Gross,Xingcheng Zhou,Zewei Zhou,Zhiyu Huang,Olaf Wysocki,Jiaqi Ma
### Background
3DGS（3D Gaussian Splatting）在基于轨迹的稀疏视图驾驶场景中常常表现不佳。现有修复方法主要针对基于优化的3DGS，而基于扩散的方法通常仅在观测视点附近进行迭代细化，导致前馈3DGS的修复情况尚未得到深入探索。
### Innovation
提出了一种名为ConFixGS的插件式方法，其利用具有意识置信度的扩散先验学习修复3DGS。通过从预先训练好的前馈模型开始，ConFixGS生成增强的扩散本地伪目标，并通过基于重投影的交叉验证来验证这些目标的有效性。生成的密集置信图指导细化过程，增强可信赖的细节同时抑制虚假或不一致的证据。
### Conclusion
在Waymo、nuScenes和KITTI数据集上，ConFixGS提高了困难的新视角合成表现，PSNR提高了多达3.68 dB，FID降低了近一半。我们的结果表明，意识置信融合生成先验和支撑视图一致性是实现稳健前馈3D驾驶场景重建的关键原则。
## 43. `cs.CV` - MOTOR-Bench: 实际场景数据集及多智能体框架的零样本人类心理状态理解 [PDF](https://arxiv.org/pdf/2605.09703), [HTML](https://arxiv.org/abs/2605.09703)
### Authors
Xiaoyu Yuan,Niklas Heikkala,Tiina Törmänen,Hanna Järvenoja,Guoying Zhao,Haoyu Chen
### Background
对于现实世界中的智能系统来说，理解人类的心理状态对其行为至关重要。然而，当前的研究大多集中在预测孤立的心理状态标签上，缺乏对复杂人际互动的结构化标注。这一局限性限制了系统进行深层次的心理状态推理，尤其是在零样本情况下。
### Innovation
本文引入了MOTOR-Bench，其包含MOTOR-dataset（1,440个协作学习场景的多模态视频片段），用于支持结构化分析。这些数据展示了现实世界数据的挑战，如自然类别不平衡、视觉噪声和领域特定的语言。此外，我们提出了名为MOTOR-MAS的推理多智能体框架，通过结构化协调机制协调多个智能体来推断显式行为、内部认知和心理情绪。实验结果显示，该框架在宏F1得分上优于现有的单一模型基准15.93点，且在预测内部认知方面优于通用多智能体基准10.2点。
### Conclusion
当前方法在结构化推理方面的局限性表明现有方法仍难以从可观察行为推理到深层次的心理状态。我们的MOTOR-MAS框架能够有效提升零样本人类心理状态理解的性能。
## 44. `cs.CV` - 胎儿脑部成像：超声视频关键帧检测的复合神经网络方法 [PDF](https://arxiv.org/pdf/2605.09750), [HTML](https://arxiv.org/abs/2605.09750)
### Authors
Aleksander Zamojski,Kacper Jarczak,Radoslaw Roszczyk
### Background
本文提出了一种新颖的方法来检测超声视频中的关键帧，特别关注胎儿脑部成像。超声成像在监测胎儿健康状态和诊断相关疾病方面发挥着重要作用，尤其是在大脑成像中。然而，现有的方法在效率和准确性上存在挑战，特别是在大量视频数据中准确、快速地识别关键帧以进行进一步的分析方面。
### Innovation
本文提出了一种由卷积神经网络（CNN）和循环神经网络（RNN）组成的复合神经网络架构。CNN可以从单个视频帧中提取空间特征，而RNN则捕捉每个视频序列中连续帧之间的时序依赖关系。这种方法旨在提高胎儿脑部超声成像分析的效率和准确性，从而支持更早地检测、诊断和治疗选择性胎儿脑部疾病。
### Conclusion
所提出的模型可能改进胎儿脑部超声成像分析的效率和准确性，从而支持早期检测、诊断和治疗计划的选择性胎儿脑部疾病。
## 45. `cs.CV` - 转变漂移为约束：在非稳态多流环境中稳健的推理对齐 [PDF](https://arxiv.org/pdf/2510.04142), [HTML](https://arxiv.org/abs/2510.04142)
### Authors
Xiaoyu Yang,En Yu,Wei Duan,Jie Lu
### Background
本文探讨了多模态大型语言模型（MLLMs）推理对齐中的一个关键但尚未充分探索的挑战：在非稳态环境中，源模型的多层次推理分布常常不可预测地演变，导致系统性的偏见和漂移传播至目标模型。
### Innovation
本文提出了一个名为自主偏好优化（APO）的新框架，将模型间的差异视作动态负约束，而不是噪声。APO采用两阶段协议：首先，监督式自举将目标模型置入源模型能力的并集中；其次，通过多负Plackett-Luce目标增强约束感知优化，显式抑制漂移轨迹，生成一致的共识流形。
### Conclusion
实验结果显示，本文的7B模型在胸部X光图像解读中表现出更优的鲁棒性，其平均准确率甚至超过专有源模型。此外，本文发布了CXR-MAX，一个包含七大小规模MLLMs共170,982个推理轨迹的大规模基准数据集，旨在促进漂移环境下的推理对齐研究。
## 46. `cs.CV` - ViSurf: 视觉监督和增强强化微调方法 [PDF](https://arxiv.org/pdf/2510.10606), [HTML](https://arxiv.org/abs/2510.10606)
### Authors
Yuqi Liu,Liangyu Chen,Jiazhen Liu,Mingkang Zhu,Zhisheng Zhong,Bei Yu,Jiaya Jia
### Background
后训练大型视觉与语言模型（LVLMs）通常涉及监督微调（SFT）来注入知识，或者使用可验证奖励的强化学习（RLVR）来提高性能。然而，SFT往往会带来次优性能，而RLVR则受限于模型的知识库。顺序使用SFT → RLVR的管道可以解决问题，但是引入了显著的计算开销，并且容易引起灾难性遗忘。
### Innovation
提出了ViSurf（视觉监督和增强强化微调），这是一种统一的单阶段模式，结合了SFT和RLVR的优点。通过分析它们的训练目标，建立了统一的框架，直接将ground-truth标签注入到RLVR的演练中，实现外部监督和内部强化的同时进行。还引入了三种新的奖励控制策略，以确保训练稳定性和优化。广泛的实验表明，ViSurf在各种基准上均优于独立的SFT、RLVR及传统的两阶段管道。
### Conclusion
深入分析进一步证实了这些发现，验证了ViSurf的推导和设计原理。
## 47. `cs.CV` - 基于原型的视图变换器联邦提示调谐中的提示估计 [PDF](https://arxiv.org/pdf/2510.25372), [HTML](https://arxiv.org/abs/2510.25372)
### Authors
M Yashwanth,Sharannya Ghosh,Aditay Tripathi,Anirban Chakraborty
### Background
预训练视觉变换器（ViTs）的视觉提示调整（VPT）已被证明是一种参数高效的方法，用于在有限数据下将大型模型适应下游任务。其参数效率使其特别适用于通信和计算预算受限的联邦学习（FL）。然而，全局提示调整难以在异构客户端间泛化，而个性化调整过度拟合局部数据且缺乏泛化能力。
### Innovation
本文提出了PEP-FedPT（基于原型的提示估计用于联邦提示调谐），这是一种统一框架，旨在实现联邦提示调谐中提示的泛化和个人化。该框架引入了一种新颖的类条件混合提示（CCMP），该提示基于随全球共享提示维护的客户类特定提示。对于每个输入，CCMP使用源自全局类原型和客户类先验的权重，动态组合类特定提示。这种方法可以在存储客户依赖可训练参数的情况下，实现样本级别的提示个性化。通过传统的联邦平均技术协作优化提示。
### Conclusion
在CIFAR-100、TinyImageNet、DomainNet和iNaturalist数据集上的全面评估表明，PEP-FedPT在各种数据异构场景下持续超越最新基线，为视图变换器的联邦提示调谐提供了坚实的基础，实现高效和可泛化的提示调谐。
## 48. `cs.CV` - UniGeoSeg: 针对地理空间场景的统一开放世界分割 [PDF](https://arxiv.org/pdf/2511.23332), [HTML](https://arxiv.org/abs/2511.23332)
### Authors
Shuo Ni,Di Wang,He Chen,Haonan Guo,Ning Zhang,Jing Zhang
### Background
遥感领域中的指令驱动分割通过生成掩码来利用指导信息，具有广泛的应用潜力。然而，当前方法面临着任务描述碎片化和指导数据有限的问题，影响了有效理解和泛化能力。
### Innovation
为了解决这些问题，我们引入了GeoSeg-1M，这是首个百万元级别的遥感指令驱动分割数据集，通过自动掩码过滤和指令生成管道，从多个公开数据集中合成引用、交互和推理分割指令。在此基础上，我们构建了GeoSeg-Bench，一个具有挑战性的基准，用于评估在不同指令驱动任务和复杂地理空间场景中的上下文理解和推理能力。此外，我们提出了UniGeoSeg统一框架，该框架采用了任务感知文本增强、潜在知识记忆和逐步训练策略，以促进多任务学习。广泛实验表明，UniGeoSeg在GeoSeg-Bench和多种公开基准上表现出优越的性能，同时具有强大的零样本泛化能力。
### Conclusion
我们的实验结果表明，UniGeoSeg在GeoSeg-Bench和多样化的公开基准上都达到了最先进的性能，并显示出很强的零样本泛化能力。我们已将数据集和源代码发布在指定网址：this https URL
## 49. `cs.CV` - Uni-Hand: 在主观视图中的通用手部运动预测 [PDF](https://arxiv.org/pdf/2511.12878), [HTML](https://arxiv.org/abs/2511.12878)
### Authors
Junyi Ma,Wentao Bao,Jingyi Xu,Guanzhong Sun,Yu Zheng,Erhang Zhang,Xieyuanli Chen,Hesheng Wang
### Background
对于增强现实和人机政策转移等应用来说，在主观视图中预测人类手部运动至关重要。尽管已有多种基于手部轨迹预测（HTP）的方法生成未来的可能手部路径点，但这些方法仍然存在预测目标不足、模态间差距、手部和头部动作纠缠以及下游任务验证有限等局限性。
### Innovation
本文提出了一种通用的手部运动预测框架，考虑了多模态输入、多维度和多目标预测模式以及与下游应用相关的多任务可操作性。通过视知觉融合、全局语境整合和任务感知文本嵌入注入，该框架能够同时预测2D和3D空间中的手部路径点。提出了一个新颖的双向扩散分支，以同时预测人类头部和手部运动，从而捕捉它们在主观视图中的运动协同效应。通过引入目标指示器，预测模型可以预测手腕或手指的具体关节路径点，而不仅仅是广泛研究的手心点。此外，还通过预测手部与物体的交互状态（接触/分离），进一步促进了下游任务。
### Conclusion
作为文献中首次在手部运动预测算法评估中纳入下游任务评价的工作，Uni-Hand 在多维度和多目标手部运动预测方面取得了最先进的性能，并且在包括人机政策转移和动作预知/识别等多下游任务中的广泛验证展示了其出色的表现。
## 50. `cs.CV` - 非黑色素瘤皮肤组织病理性分析中超越视觉特征的神经组织关系建模 [PDF](https://arxiv.org/pdf/2512.06949), [HTML](https://arxiv.org/abs/2512.06949)
### Authors
Shravan Venkatraman,Muthu Subash Kavitha,Joe Dhanith P R,V Manikandarajan,Jia Wu
### Background
组织病理学图像分割在皮肤癌诊断中至关重要，但如何建模空间上下文和不同组织间的相互关系依然困难，尤其是在组织重叠或形态相似的区域。现有的基于卷积神经网络（CNN）的方法主要基于视觉纹理，通常将不同的组织视作独立的区域，未能编码生物学上下文。
### Innovation
本文介绍了一种名为Neural Tissue Relation Modeling (NTRM)的新分割框架，通过将图神经网络与CNN结合来构建组织级别之间的空间和功能关系。NTRM通过图生成上下文信息，并通过空间投影来细化分割。NTRM明确地编码了不同组织之间的依赖关系，产生了结构上连贯的预测，尤其在边界密集的区域。
### Conclusion
在Histopathology Non-Melanoma Skin Cancer Segmentation数据集上，NTRM在Dice相似系数上表现优异，比当前最优模型高出4.9%到31.25%。我们的实验表明，关系建模为更具有上下文意识和可解释性的组织病理学分割提供了一条原理上的路径。
## 51. `cs.LG` - 当值感知的KV移除有所帮助时？固定合同诊断法研究 [PDF](https://arxiv.org/pdf/2605.08234), [HTML](https://arxiv.org/abs/2605.08234)
### Authors
Ruijie Zhang,Haozhe Liang,Da Chang,Li Hu,Fanqi Kong,Huaxiao Yin,Yu Li
### Background
长上下文LLM解码受到读取大量KV缓存时的内存和带宽成本限制。KV压缩通过保持部分缓存减少了这部分成本，但对于一个选择器的成功或失败，仅从任务准确性无法解释其原因。选择器在三个步骤中可能发生故障：可能会错过未来解码所需的证据、给予不改变输出的标记高分数、或者在小缓存中调整得分时破坏相关证据。
### Innovation
引入了一种固定合同诊断方法，该方法保持选择器的设置固定，同时一次改变一个决策槽。对于价值排名，探测器结合了一块的注意力质量与删除这块后估计的输出变化。在LongBench上，该探测器在正差值单元格中有72.6%的积极反应，在非正差值单元格中有32.4%的积极反应。NeedleBench M-RT 32k 和RULER 8k检查探测器支持分支检索的封闭性，264单元格符号评估将支持恢复、输出值排名从边界附近的杠杆效应中分离出来。这导致的顺序是恢复解码侧的证据，对输出值进行排名，并在投影过程中保护联合作证。
### Conclusion
结果表明，通过固定合同诊断方法和特定缓存压缩技术，可以有效管理和优化KV缓存，从而提升LLM的性能。
## 52. `cs.LG` - 分布谱诊断在模算术Transformer模型中的Grokking转换局部化 [PDF](https://arxiv.org/pdf/2605.08237), [HTML](https://arxiv.org/abs/2605.08237)
### Authors
Ziyue Wang,Yufeng Ying,Takafumi Kanamori
### Background
该研究探讨了在Grokking现象中模型如何在训练数据拟合良好但测试准确性仍较低时，晚些时候才会开始泛化。研究团队希望在测试准确性上升之前，是否可以从观察到的训练轨迹中局部化这种转变，并将其作为诊断问题来解决，具有明确的阈值/假正率/提前时间权衡。
### Innovation
该研究通过任务依赖的可观测指标（用经验分布汇总），将它们映射到Wasserstein/分位数坐标，并使用Hankel动态模式分解（DMD）进行分析。结果显示残差在运行级别grokking与非grokking鉴别中的AUROC约为0.93。这类扰动实验显示，在测试的$wd=1$池中，高残差窗的短期扰动偏差大约是低残差窗的三倍。这表明，残差不仅仅是在窗口级别的一种总范数代理信号，且指示残差顺序的范数信号是更强的运行级别指标，而逻辑概率表现最佳。
### Conclusion
研究将残差定位为运行级别的监控和局部化信号，在研究的模算术Transformer设置中，而不是作为通用的早期预警预测器或干预规则。
## 53. `cs.LG` - LaWM: Least Action World Model Model for Long-Horizon Physical Consistency from Visual Observations [PDF](https://arxiv.org/pdf/2605.08279), [HTML](https://arxiv.org/abs/2605.08279)
### Authors
Qixin Xiao,Maani Ghaffari
### Background
在体态人工智能（Embodied AI））领域中， 预测性基于视觉观察观测 的学习是一项挑战性问题问题题
### Innovation
本文提出了一个名字为拉WM的隐空间世界模型（Least Action World Model ModelLaWM) 
### Conclusion
通过变化观察基于隐空间拉格朗日动量函数的框架, 兟能在物理干净的合成动力学和具有体态机器人交互基准测试中改进物理不变性、 幓致一致性和运动平滑度以及外观和和几何
## 54. `cs.LG` - 物理规则执行的重要性在于精确性 [PDF](https://arxiv.org/pdf/2605.08285), [HTML](https://arxiv.org/abs/2605.08285)
### Authors
Bum Jun Kim
### Background
自回归科学预测器通常在将每个预测状态反馈回模型之前对其进行修复，以施加物理或结构约束。然而，仍不清楚强大的物理规则执行何时可靠，何时成为分布偏移的来源。本文通过考察修复映射在目标流形上的身份性质及其与目标几何结构的对齐情况，研究了这一点。实验比较了原始预测、事后修复和循环修复在周期不可压缩纳维-斯托克斯流、非周期CFDBench流动以及层次预测辅助任务中的表现。
### Innovation
研究了物理规则执行在精确性方面的必要性，特别是在不同条件下的表现，明确了在无法提供精确投影情况下，更强的基于泊松的清理可以减少发散但同时增加滚动输出误差，并通过控制不匹配、筛查清理、自适应门控和外部主干检查来确定最佳近似的操作点。层次预测也给出了相似的模式，精确预测调整提供了一个稳定的基准，而混合顶部-向下修复则依靠验证调优的历史比例顶部-向下重调整，依赖于数据集。
### Conclusion
在执行物理约束之前，应该先进行操作-数据对齐以评估其强度。在无法提供精确投影的情况下，基于泊松的清理可能具有更强的效果，但需要小心权衡发散减少与滚动输出误差增加之间的关系。
## 55. `cs.LG` - 具有最佳动作查询的多臂老虎机 [PDF](https://arxiv.org/pdf/2605.08287), [HTML](https://arxiv.org/abs/2605.08287)
### Authors
Francesco Bacchiocchi,Matteo Castiglioni,Alberto Marchesi,Francesco Emanuele Stradi
### Background
研究了配备最佳动作查询的多臂老虎机（MABs）。以往的工作在全反馈模型中探讨了这种设定，其中学习者可以在每个回合后观察所有臂的奖励，并展示了当环境是随机或对抗时，$k$ 次最佳动作查询可以将最优遗憾从 $tilde{text{O}}(text{sqrt}(T))$ 降低到 $tilde{text{O}}(text{min}frac{T}{k}, text{sqrt}(T))$。但是，这种改进是否适用于更现实的带反馈模型仍然未知，即学习者仅能观察到选择臂的奖励。
### Innovation
论文完全解答了这个问题。论文提出了当臂的奖励是随机但相关时，全反馈结果无法适用，任何算法的遗憾下界为 $text{Omega}(text{sqrt}(T-k))$。对于对抗环境，这个下界同样适用。但在臂的奖励是随机且独立同分布时，可以实现 $tilde{text{O}}(text{min}frac{T}{k}, text{sqrt}(T-k))$ 的遗憾，同时也给出了相应的下界，至多相差对数因子。
### Conclusion
论文提供了在带反馈模型中，最佳动作查询能够带来的益处的完整描述，补充了前人关于多臂老虎机的研究。
## 57. `cs.LG` - cohort INRs编码的内容及其冻结位置 [PDF](https://arxiv.org/pdf/2605.08298), [HTML](https://arxiv.org/abs/2605.08298)
### Authors
Vasiliki Sideri-Lampretsa,Sophie Starck,Robbie Holland,Julian McGinnis,Daniel Rueckert
### Background
已有人使用已训练的初始层来加速和改进新信号的拟合过程，但对于共享编码器中的哪些层能学到可转移的表示以及这些表示代表什么，仍然不清楚。本文针对SIREN和Fourier特征MLP（FFMLP）这两种标准骨干网络回答了这两方面的问题。研究者在测试阶段调整共享编码器的固定深度，并发现最优深度与权重稳定秩最高的层相对应。此外，冻结在这一深度上的性能优于标准的微调方法。然而，确定哪些层进行转移并不能解释这些层编码的内容。为了进一步解决这个问题，本文采用稀疏自动编码器（SAE）进行分解，首次将INR激活分解为稀疏字典原子。研究发现SIREN和FFMLP在组拟合质量上表现相似，但在学习的字典方面存在质的差异。
### Innovation
本文通过调整共享编码器的固定深度，发现最优的深度与权重稳定秩最高的层相对应，从而证明了从训练好的初始层初始化新信号的有效性。此外，引入稀疏自动编码器将INR激活分解为稀疏字典原子，揭示了SIREN和FFMLP在学习的字典方面的差异。这部分揭示了组训练的INRs中传递的内容，并将激活转换为可检验的字典原子，为理解INRs编码的内容和设计旨在推广而非记忆的架构提供了新的工具。
### Conclusion
本文为组训练的INRs中传递的内容提供了首个机械解释，并将他们在现有的字典原子中转变为可检验的形式。这些工具为理解INRs编码的内容和设计关注推广而非记忆的架构开辟了新的途径。
## 58. `cs.LG` - mHC-SSM：流专用适配器的态空间语言模型中的形式约束超连接 [PDF](https://arxiv.org/pdf/2605.08300), [HTML](https://arxiv.org/abs/2605.08300)
### Authors
Abdulvahap Mutlu,Şengül Doğan,Türker Tuncer
### Background
该研究探索了形式约束超连接（mHC）在多流残差拓扑结构中的应用，特别是在构成状态空间模型（SSM）的语言模型中。
### Innovation
文章提出了一种形式约束的流专用适配器，这种机制在状态空间模型中引入了轻量级的流特异性能力，同时保持了先前的流混合机制。
### Conclusion
研究通过与单一流SSM、静态形式约束超连接SSM以及含有适配器的形式约束超连接SSM的对比实验，证明了形式约束超连接和流专用适配器可以有效改善语言模型的验证损失和困惑度，尽管这会带来轻微的吞吐量降低和内存使用增加。
## 59. `cs.LG` - 预热：从预训练转导器生成混合状态空间模型 [PDF](https://arxiv.org/pdf/2605.08301), [HTML](https://arxiv.org/abs/2605.08301)
### Authors
Aditya Chattopadhyay,Elvis Nunez,Prannay Kaul,Benjamin Bowman,Evan Becker,Luca Zancato,David Thomas,Wei Xia,Stefano Soatto
### Background
该研究介绍了一种结合了注意力机制和递归状态空间模型（SSM）的混合状态空间模型。这类模型旨在平衡注意力机制的临时记忆与递归状态空间模型的压缩遗忘记忆，从而提供比Transformer更小的关键值缓存和更快的解码速度，同时还具有更丰富的架构设计空间。然而，目前探索这一设计空间的规模需要从头开始训练，这是大多数大型混合架构研究难以逾越的障碍。
### Innovation
该研究提出了‘预热’（Priming）方法，该方法将混合架构的设计从预训练问题转化为知识转移问题。它通过预训练的转导器初始化混合模型并通过短期内的对齐和后处理阶段恢复下游质量，使用不到0.5%的源预训练中使用的数据预算。这种方法对转导器的家族（如Qwen、Llama、Mistral）、模型类别（密集或Mixture-of-Experts）和模型规模都是通用的。这使研究人员能够在相同条件下，首次进行大规模的SSM层类型的对比研究。
### Conclusion
研究评估了Gated KalmaNet（GKA）、Gated DeltaNet（GDN）和Mamba-2模型，并表明这些模型的表达能力等级（GKA>GDN>Mamba-2）直接预测了其在长时间上下文推理任务上的下游性能。通过缩放预热方法，实现了具有原生128K上下文的8B/32B推理模型。实验表明，混合GKA 32B模型相较于其源Qwen3-32B提升了3.8个百分点的推理性能，同时保持在与后训练的Transformer相同的精度水平，并且可以实现2.3倍更高的解码吞吐量。为了促进混合架构的研究，研究者发布了用于长上下文推理和指令跟随的预热混合模型库，以及预热的训练和推理代码。
## 60. `cs.LG` - 基于图神经网络的结构位移预测 [PDF](https://arxiv.org/pdf/2605.08303), [HTML](https://arxiv.org/abs/2605.08303)
### Authors
Hung-Fu Chang,Tzu-Kang Lin,Yung-Li Cheng
### Background
结构在外荷载下的准确位移预测是结构健康监测和地震安全性评估的基础。尽管有限元方法（FEM）因其高精度而广泛使用，但其计算成本太高，不适合实时监控应用。
### Innovation
本研究提出了一种基于图神经网络（GNN）的数据驱动框架，将结构系统表示为图，节点代表节点，边代表结构成员。通过将几何和机械属性纳入图表示中，该模型直接从模拟数据中学习荷载与结构响应之间的关系。与传统的神经网络模型相比，GNN框架在预测位移和旋转方面表现出更高的准确性。
### Conclusion
所提出的GNN框架在预测位移和旋转方面表现出了高精度，并且优于传统的神经网络模型，展示了其作为一种快速且高效的替代传统FEM分析方法的潜力。
## 61. `cs.LG` - SGc-r-ml:在实际世界的I帕克金森病长期评估I中的中的I可靠性和解释性II的I框架 [PDF](https://arxiv.org/pdf/2605.08302), [HTML](https://arxiv.org/abs/2605.08302)
### Authors
Wenbin Wei,Ruixiang Gao,Suyuan Yao,Xuanzhen Zhao,Cheng Huang,Hen-Wei Huang
### Background
现有的数字帕金森病诊断面临多种挑战，例如模态多样性、设备偏置和 不标签的不完整性。现有研究主要注重预测，缺乏在回顾性的、可靠性评估中的所需机制，即何时拒绝评估、重新测试以及从哪个症状维度进行预测等关于此，本研究提出了SGC-RML方法，将言语、步态、可穿戴运动、生产力任务以及临床变量映射到一个共享的的8维度症状节点空间（即7个临床症状节点和一个响应状态辅助节点连接神经元非和和和性和神经二维症状通过症状地图进行统一。通过引入不确定性估计、校准和和选择性路由The理论不仅能预测症状和严重程度、还能在证据不充分时拒绝评估、重新测试。本研究在五个真实世界PD数据集上上进行验证、涵盖了分类、回归、事件检测和长期严重程度预测。实验结果显示SGC-RML在ONONUTI上的均绝对误差（为4.1、在OPMI上的AUC为083、在POND上的AUC为80. 在无泄漏的时空绑定下下、基于特定锚定点和UCI之时、实现提供了相对依赖（运动MAE 之38、CCC  儿）的校准长期评估I（运动MAI 344、ccc 56、在部分80的情况下。基于Daphnet LOSO协议I实现了AUC 之80。这些结果表明SGC-RM于能够在不完整信息下下情况下、提供准确、校准准、可可和性和症状可可解性的PD长期回顾性I评估。
### Innovation
本研究创新点在于的方法在于 SGC-R在中I中将多种生理和临床变量I映射到共享的I症状I空间I。通过引入不确定性估计I校I与S校准和定和和N和选择择性路由样理论I、不仅I能能预测症状与严重程度I还能I在I证据不充分时I时拒绝评估、重评估。本研究方法I充分利用了I有限的的多元I数据I提供了可靠的I并且解释性的I长期评估II框架。
### Conclusion
SGC-R在L在不完整I模态条件I下了实现了准确统一I的I病I评估I框架I、提供了准确可靠性的I解释性的I和长期PD的长期I回顾性I评估I。在多种实际情况I下了II研究结果I显示ISGC-RM在可以I准确I校准性审计II症状解荅性P的长期I回顾II评估I在不完整I多元I信息I条件下I具有I优势。
## 62. `cs.LG` - PRISM：通过调度-内存协同设计实现快速在线大语言模型服务 [PDF](https://arxiv.org/pdf/2605.08581), [HTML](https://arxiv.org/abs/2605.08581)
### Authors
Xingyu Qu,Tianhao Lin,Yiqi Li,Zhiyu Chen,Sheng Wang
### Background
现代在线大型语言模型（LLM）服务，如检索增强生成（RAG）和代理系统，展示了两种显著特征：提示分段（例如，系统指令、检索段落、工具输出）和热点偏斜，其中一小部分这些段落会在用户请求中反复出现。如果不联合利用这些模式，会导致热点段落的重复填充，从而延长TTFT（第一个请求到响应的时间），影响吞吐量和用户感知的响应性。现有的研究分别处理这些模式：键值缓存管理主要利用段落复用，而调度重新排序请求以改进缓存局部性，但这两者并未同步考虑请求接纳与键值缓存保留。
### Innovation
我们提出了PRISM（Prefix Reuse Optimization Integrated Scheduling and Memory），通过设计一个知查询调度器（QAS）与一个需求感知的Radix树（DART），实现请求接纳与精确前缀键值缓存保留的同步。PRISM通过同时考虑调度和缓存管理，显著减少了平均每个QPS的P99 TTFT，提高了精确前缀键值缓存命中率。
### Conclusion
我们的评估结果显示，与最强基线相比，PRISM在4B和13B模型中分别减少了平均每个QPS的P99 TTFT，并增加了精确前缀键值缓存命中率。
## 63. `cs.LG` - 基于推理的时序预测训练 [PDF](https://arxiv.org/pdf/2605.08625), [HTML](https://arxiv.org/abs/2605.08625)
### Authors
Md Atik Ahamed,Mihir Parmar,Palash Goyal,Chun-Liang Li,Qiang Cheng,Tomas Pfister,Jinsung Yoon
### Background
时间序列基础模型（TSFMs）擅长数值预测，但缺乏对定量关系的解释能力。直接将大型语言模型（LLMs）应用于时序数据会引入语态差距：文本分词器会将连续的数值分解成碎片，破坏数学关系并增加序列长度，导致计算困难。
### Innovation
本文引入了STRIDE（战略时间序列推理馈入蒸馏嵌入）框架，该框架将LLM推理直接集成到TSFMs的连续嵌入空间中。STRIDE通过动态将LLM的均值池化隐藏状态作为跨模态先验投影到目标数值编码器中，而不是使用离散的标记。联合优化使用交叉熵和分位数损失。
### Conclusion
评估表明，STRIDE在GIFT-Eval上达到了最先进的数值预测性能（0.674 MASE，0.454 CRPS），并在TFRBench上的领域内和领域外数值预测和推理性能均表现出色。STRIDE作为即插即用增强，能够在不同LLM配置下提高多种TSFM的性能，通过注入语义推理为TSFMs提供了可解释的推理能力，并显著改进了预测精度。
## 64. `cs.LG` - PAAC：了解隐私的代理设备云协作 [PDF](https://arxiv.org/pdf/2605.08646), [HTML](https://arxiv.org/abs/2605.08646)
### Authors
Liangqi Yuan,Wenzhi Fang,Shiqiang Wang,Christopher G. Brinton
### Background
大型语言模型（LLM）代理面临结构性冲突：云端代理提供强大的推理能力但会暴露用户数据，而设备端代理保留隐私但总体能力受限。现有设备与云端设计将这一界限视为计算分配而不是适用于代理工作负载的信任边界，并且现有组件化方法在策略灵活性和工具调用所需的结构忠实度之间进行选择。
### Innovation
我们开发了PAAC，这是一种隐私意识代理框架，该框架将计划者和执行者分解与设备云边界对齐，使得角色的专业化本身成为隐私机制。云端代理使用类型化的占位符令牌进行推理，这些占位符令牌保留了每个敏感值的推理角色但丢弃了其内容，而设备端代理识别敏感间隔并简化每个步骤的执行结果为紧凑的关键发现。组件化限制设备端LLM仅提出需要遮蔽的间隔，而确定性注册表执行所有替换和恢复，确保操作直接设备可执行。
### Conclusion
在严格隐私设置下的三个代理基准测试中，PAAC在隐私和准确性之间占据帕累托前沿，平均准确性提高了15-36%，平均泄露减少了2-6倍，超出最先进的设备云基线，在隐私目标方面有很大优势。我们还在10个领域中的17个额外基准测试中发现持续改进，包括数学、科学和金融。
## 65. `cs.LG` - Sketch-and-Verify: 结构化推理时扩展性利用程序草图 [PDF](https://arxiv.org/pdf/2605.08658), [HTML](https://arxiv.org/abs/2605.08658)
### Authors
Shan Jiang,Zijian Yi,Chenguang Zhu
### Background
该研究背景在于，当代码模型的小型和经济时（比如使用Gemini 3.1 Flash Lite），由于延迟、部署或预算原因而无法使用更强大的模型。如何有效利用额外的测试时间计算呢？研究通过量化平滑采样（flat sampling）和通过程序草图进行推理（SketchVerify）在搜索空间中的表现来探索方案。
### Innovation
提出了一种名为SketchVerify的成本-性能策略，它将搜索空间分解为通过大型语言模型（LLM）生成多种算法策略的程序草图，并通过执行验证和指纹聚类进行选择。这种方法在小型模型（如Lite）上显著地在特定问题上提高了性能，并证明了在不同部署层级上的效益差异。
### Conclusion
研究发现，当Lite模型使用Sketch K=2，M=5时，在具有挑战性的问题上能恢复58%的解，比不使用草图的平滑采样方法提高了32个百分点。对于更大层级的Pro模型，则更推荐使用贪婪算法而非草图方法，即当更强的层级可用时，使用贪婪算法；否则，利用草图方法是有效的方法。此外，研究通过多种测试和分析展示了这种方法的有效性。
## 66. `cs.LG` - AAAC: Activation-Aware Adaptive Codebooks for 4-bit LLM Weight Quantization [PDF](https://arxiv.org/pdf/2605.08692), [HTML](https://arxiv.org/abs/2605.08692)
### Authors
Beshr IslamBouli,David Jin
### Background
4位权重后训练量化被广泛应用于减少大型语言模型推理的内存和计算成本。现有的后训练量化(PTQ)方法，如AWQ和GPTQ，通过缩放、剪裁或误差补偿改善权重映射到固定4位网格的方式。为了进一步提高准确度，OmniQuant和QuIP//#等方法使用基于梯度的算法，但代价是长时间的量化时间。
### Innovation
提出了一种轻量级方法AAAC（Activation-Aware Adaptive Codebooks），以4位量化大型语言模型的权重。AAAC用两个小型学习标量码本（64字节/层）取代了标准量化中的固定标量码本。每组权重选择最小化激活加权重构误差的码本，将选择存储在组的正标量的未使用的符号位中，没有额外的存储开销。AAAC在单个GPU上完成时间在3到30分钟之间，不增加额外的内存。评估结果显示，AAAC在量化时间减少多个数量级的情况下优于基准方法。
### Conclusion
AAAC在相对较少的量化时间内优于AWQ、GPTQ、IF4、GPTVQ、OmniQuant、SqueezeLLM和QuIP//#等现有的后训练量化方法。
## 67. `cs.LG` - 软桥策略生成性Actor- Critic算法 [PDF](https://arxiv.org/pdf/2605.08733), [HTML](https://arxiv.org/abs/2605.08733)
### Authors
Ke He,Le He,Shunpu Tang,Yafei Wang,Lisheng Fan
### Background
生成性策略如扩 散和流模型在最大熵在线强化学习中由于能够建模多模态和高度非高斯动作分布而显得吸引力。然而，在训练有效的软生成策略的过程中，有两个常见障碍，它们经常同时出现：一是边际动作密度难以获得，现有方法通常依赖于熵界估计、启发式代理或近似；二是迭代共享参数抽样器提高了推断成本，并增加了循环网络评估中反向传播时间，从而增加了内存成本并使策略优化变得不稳定。
### Innovation
我们提出了一种软生成性actor-critic算法(SoftGAC)，其actor定义了一个从固定基础潜变量到终端动作潜变量的结构化桥梁，这种桥梁允许我们将最大熵目标提升为可解析推导的路径对数相对熵目标，作为相对于高熵参考过程的路径对数相对熵目标。在实际的有限步骤实现中，这个问题简化为仅通过取样过渡控制能量来精确实现，从而获得了原则上的软正则化。此外，为了保持单次pass actor的轻量性，我们使用小步骤特定桥梁转换，每评估一次每个取样动作一次，同时保持参数预算与强大的actor基线相当。
### Conclusion
广泛的实验已经在具有挑战性的连续控制基准上显示，SoftGAC 在高延迟范围内达到或优于强大的生成性政策基线，包括扩散和流匹配策略，并且在计算量与回报率之间的权衡中表现出显著改进。
## 68. `cs.LG` - AdaPreLoRA：Adafactor预条件低秩适应 [PDF](https://arxiv.org/pdf/2605.08734), [HTML](https://arxiv.org/abs/2605.08734)
### Authors
Ziyun Liu,Fengmiao Bian,Jian-Feng Cai
### Background
低秩适应（LoRA）通过两个低秩因子的乘积重新参数化权重更新，但生成器映射这些因素到权重矩阵的雅可比矩阵 $J_{G}$ 级数不足，因此由任何 ${W}$-空间预条件器 ${F}_t$ 引入的因素空间预条件器 $J_{G}^* {F}_t J_{G}$ 奇异，从而标准链式规则无法唯一反转映射预条件 ${W}$-空间方向回因素空间更新。
### Innovation
本文提出 AdaPreLoRA，它在预条件器设计空间内结合了感知梯度统计数据的 ${F}_t$ 和闭式求解因素空间的问题，以便在 ${O}((m+n)r)$ 内存内以 ${H}_t$ 修正不平衡最小化因素贡献。这种方法在对 LoRA 优化器的实现进行改进时，使优化器既具有竞争力，又具有较低的峰值 GPU 内存消耗。
### Conclusion
在 GPT-2（端到端），Mistral-7B 和 Qwen2-7B（GLUE，ARC，GSM8K）以及扩散模型个性化方面，AdaPreLoRA 与一系列代表性 LoRA 优化器具有竞争力，甚至在某些方面有所改进，同时保持峰值 GPU 内存消耗与 LoRA 优化器相同。
## 69. `cs.LG` - SlimQwen: 探索大规模MoE模型预训练中的剪枝与知识蒸馏 [PDF](https://arxiv.org/pdf/2605.08738), [HTML](https://arxiv.org/abs/2605.08738)
### Authors
Shengkun Tang,Zekun Wang,Bo Zheng,Liangyu Wang,Rui Men,Siqi Zhang,Xiulong Yuan,Zihan Qiu,Zhiqiang Shen,Dayiheng Liu
### Background
结构化剪枝和知识蒸馏是用于压缩大型语言模型的典型方法，但在大规模预训练中的应用尚不明确，特别是在最近的混合专家（MoE）模型中。本文系统地研究了大规模预训练中的MoE压缩问题，重点关注三个关键问题：剪枝是否比从头训练提供更好的初始化；专家压缩的选择如何影响后续的模型性能；哪种训练策略最有效。
### Innovation
研究发现：1) 剪枝的预训练MoE模型在相同训练预算下总是优于从头训练的目标架构；2) 不同的单次专家压缩方法在大规模持续预训练后实现了相似的最终性能，基于此提出了一种简单的部分保留专家合并策略，提高了大多数基准的下游性能；3) 结合语言建模损失的知识蒸馏优于单独的知识蒸馏，特别是对于知识密集型任务；4) 在相同的训练令牌下，渐进式剪枝调度优于一次性的压缩，表明渐进的架构过渡会带来更好的优化轨迹。
### Conclusion
通过压缩Qwen3-Next-80A3B为一个23A2B模型，同时保持竞争力，这些结果为大规模MoE压缩提供了实用的指导。
## 70. `cs.LG` - 变压器表示的因果维度：测量、缩放和层结构 [PDF](https://arxiv.org/pdf/2605.08740), [HTML](https://arxiv.org/abs/2605.08740)
### Authors
Nilesh Sarkar,Dawar Jyoti Deka
### Background
研究稀疏自编码器（SAEs）如何分解变压器残差流为可解释的特征字典，但SAEs宽度与其对模型输出的因果影响之间的关系尚未系统化研究。
### Innovation
引入因果维度κ(L, M, T)，定义为预期雅可比外积的有效秩，通过SAE宽度扫描配以归因补丁进行估计。实验证明代表能力增长15.6倍而因果能力仅增长4.35倍，提出了代表-因果楔形概念。κ值对模型缩放不变，κ值用于量化AtP分数在匹配序列条件下的形变不变性。κ值不随网络深度变化，但绝对归因阈值从第1层至第23层下降20倍。通过多种控制实验确定了κ的含义。
### Conclusion
κ为可测量的、模型固有的变压器层属性，通过SAE宽度线性外推可回收，对模型缩放是不变的，并且在网络深度上是有结构的。
## 71. `cs.LG` - 全局经验神经切核：梯度下降学习的自我参照偏差与维度 [PDF](https://arxiv.org/pdf/2605.08746), [HTML](https://arxiv.org/abs/2605.08746)
### Authors
James Hazelden,Laura Driscoll,Eli Shlizerman,Eric Shea-Brown
### Background
在使用梯度下降法训练神经网络时，每次迭代会形成一个支配模型内部状态变量一阶更新的线性算子，称其为全局经验神经切核（Global Empirical Neural Tangent Kernel, NTK）。在权重有限的网络中，NTK的形成通常是无法解决的，因此以往的研究多集中在仅追踪输出或考虑无限宽度的极限情形。本文深入研究了不同模型的NTK结构。
### Innovation
本文将模型状态定义为单个全局隐式约束的解，推导出NTK是两个算子的乘积：K描述参数到状态的即时交互，P描述内部状态间依赖关系。对于广泛类别的基于权重的模型（包括循环网络和转换器），证明了一个普遍Kronecker核心定理，表明K具有精确且可计算的形式，即权重位置变量的Gram矩阵。进一步分析NTK的光谱，探讨其在时空维度上的偏斜和低秩性，尤其是在初始化阶段模型动力学对NTK的影响，揭示了NTK具有结构限制，导致梯度下降学习偏好特定模式。说明自注意力转换器的NTK同样受到这种结构限制，限制了其作为实际衡量指标的实用性。
### Conclusion
本文发现NTK具有可操作的结构，可以解释梯度下降倾向学习任务解决方案，以及低秩表示的出现。为了将NTK作为实用指标，构建了kpflow库，依赖于随机化矩阵自由的数值线性代数。
## 72. `cs.LG` - 手环高斯损失：通过球面-区间分解实现确定性可组合潜在变量 [PDF](https://arxiv.org/pdf/2605.08749), [HTML](https://arxiv.org/abs/2605.08749)
### Authors
Mikhail Parakhin,André M. Carvalho,Patrick Haluptzok
### Background
本文介绍了一种无需采样、无KL项或迭代传输的确定性批量损失——手环高斯损失（Wristband Gaussian Loss），用于点嵌入的高斯化。
### Innovation
提出了新的损失函数来确定性地高斯化点嵌入，无需采样和迭代传输。通过球面-区间分解，每个$x otin text{null}(times)$被映射为一个方向$u = x/text{exp}(text{log}(text{log}(times)))$和一个CDF变换的半径$t = F_{text{chi-squared}_d}(text{exp}(text{log}(text{log}(times))))$。证明了该函数具有唯一的高效性和生成均匀分布的特性。此外，通过两种方法计算反内核目标，该方法可与近似三张图像间的对数近似和谱迹穷举路径相结合，以匹配梯度。该损失在高斯参考批量中的表现被标准化成$z$-分数进行比较，从而评估其在不同数据集上的性能。
### Conclusion
在轴向均匀X基准数据集上，手环表现可与二维直接点云高斯化相比肩，并在10D数据上表现最佳。在一项更难的测试数据集上，它在10D和128D上表现最优。结合可学习键欧几里得注意力和精确可逆流后，该确定性高斯自编码器能够提供独立因素的反事实采样接口和针对依赖因素的上下文/残差结构。
## 73. `cs.LG` - on-Monloomberg Latency in Apple MPS Decoding: KV Cache Interactions and Execute Dynamics [PDF](https://arxiv.org/pdf/2605.08913), [HTML](https://arxiv.org/abs/2605.08913)
### Authors
Willy Fitra Hendria
### Background
自回归推插入通常假定其预测性德性推理长度和键值（KV) 缂数）。 优化。加速解码过程。。Apple的MPS后端显示了一种出人非单调的延迟行为，在相邻的解码配置之间延迟突然变化发生变化。。研究者使用了来自多个模型家族 (GPT、BLOOM和OPT) 的变压器模型来观察延迟峰值，V倍的具体解算预算区间，并随后恢复在邻近配置中。在受控实验中，研究者发现这些异常可以归因于内存缓冲，但其实相反，这种行为符合与后端执行动力学是一致的，而CPU和NVIDIA T4 (CUDA)则在相同的条件下展示出平滑的单调扩展。
### Innovation
这项研究识别了在Apple MPS后端出意外的出非单调的延迟行为，解码配置间隔之间，并提出这种行为应由后端执行动态学解释，而不是键值和缓存机制。同时在相同的算解预算条件下，CPU和NVIDIA T4 (CUDA)可以在平滑单调扩展的状态下揭示出On硬件感知的评估对自回归推理的重要性和警告依赖于聚合的解算预算基准，因为这些基准在线不同配置之间可以有显著的变化。
### Conclusion
研究结果突了硬件感知的评估对于自回归推理的重要性，并并 尭并发警告对在相邻配置上依赖聚合的解算预算基准因为这些基准可能在相邻配置之间可以有显著的变化。。研究者提醒在评估解码过程中需要注意潜在的突发延迟现象这对解解构态的显著变化仍然不能被现有的聚合模型准确捕获，因此需要对神经推理进行更细致的分析以确保准确评估其性能。
## 74. `cs.LG` - 基于单个深度偏好条件化策略的帕累托覆盖集学习 [PDF](https://arxiv.org/pdf/2605.08946), [HTML](https://arxiv.org/abs/2605.08946)
### Authors
Akihiro Kubo,Kosuke Nakanishi,Shin Ishii
### Background
偏好条件下的多目标强化学习旨在学习一个能够捕捉各种偏好下权衡的单一策略，但在非线性标量化方法下，偏好到解的对应关系的唯一性和连续性尚不明确。本文在表征性多目标马尔可夫决策过程（MDPs）中研究了该问题，并使用光滑切比雪夫标量化作为单调效用研究此问题。
### Innovation
一是证明了每种偏好都会诱导一个唯一的帕累托最优回报向量，并且此向量会依偏好以Lipschitz连续的方式变化，为偏好优化提供了实质性的依据；二是提出了计算这些目标的框架，并因此获得了具有$O(1/k)$次优性目标的凸镜对称梯度下降策略迭代算法CMDPI；三是将每次更新等效于解决一个以先前策略为参考的Kullback-Leibler正则化的MDP，并通过深度演员-评论家算法实现，同时保持了之前的策略正则化。
### Conclusion
在八个MO-Gymnasium任务上，该算法在平均hypervolume排名中表现最佳，并且具有强大的预期效用性能。连续控制实验表明，该方法在离散动作设置之外具有优势。
## 75. `cs.LG` - Muon-OGD: Muon-based Spectral Orthogonal Gradient Projection for LLM Continual Learning [PDF](https://arxiv.org/pdf/2605.08949), [HTML](https://arxiv.org/abs/2605.08949)
### Authors
Binghang Lu,Zheyuan Deng,Runyu Zhang,Bing Hu,Yunhan Zhao,Yuan Tian,Changhong Mou,Guang Lin,Xiaomin Li
### Background
在大语言模型（LLMs）的持续学习中，中心挑战是灾难性遗忘，即适应新任务可能会显著降低先前学习任务的表现。现有的投影基方法通过限制参数更新到与过去任务无关的方向子空间来缓解这种干扰，但是这些方法通常是在欧几里得参数几何下进行的，更新幅度和投影由Frobenius范数控制。最近，Muon优化器的成功表明，Frobenius几何可能不是最佳选择。受此观察的启发，本文提出了一种基于Muon的光谱正则化持续学习框架Muon-OGD。
### Innovation
MuO G算法结合了Muon风格的操作范数几何和正交投影约束，将每个更新表示为一个光谱正则化约束优化问题，通过双重迭代和Newton-Schulz矩阵符号近似高效求解。MuO G通过避免与先前任务相关的受保护方向应用正交动量更新，旨在改善持续LLM适应中的稳定性和可塑性权衡。
### Conclusion
实验结果表明，MuO G在标准持续学习基准TRACE和特定领域的Coding-Math-Medical课程上，以及使用编码-解码和仅解码架构时，相对于顺序微调和竞争的正交梯度基线，具有更好的表现，并且计算上可扩展。这表明光谱正则化更新几何提供了Frobenius投影在LLMs持续学习中的一种实用和有效替代方案。
## 76. `cs.LG` - 一项关于硬件诱发失真在硬件感知训练中的受控诊断研究 [PDF](https://arxiv.org/pdf/2605.09416), [HTML](https://arxiv.org/abs/2605.09416)
### Authors
Yunxuan Fang,Xinhe Wang
### Background
硬件感知训练（HAT）被广泛应用于提高神经网络在非理想AI加速器（如模拟内存计算系统IMC）上的鲁棒性。然而，并非所有由硬件引起的失真都能通过训练进行同等程度的补偿。这篇论文提出了一种诊断框架，将硬件非理想性建模为前向操作的结构化扰动，并评估其与梯度优化的兼容性。
### Innovation
该研究分析了六个典型的扰动类别：读噪声、变异性、漂移、固定点故障、IR-降压和ADC量化，并识别出三项关键诊断指标：梯度期望一致性、梯度方差有界性和非退化敏感性。结果表明，能够通过HAT进行补偿的扰动与那些一致破坏优化的扰动之间存在明显的区分。
### Conclusion
这为硬件和软件协同设计提供了实际指导，明确了哪些非理想性可以在训练级别解决，哪些需要在电路、架构或校准级别进行缓解。这项研究应被视为在常规前向扰动HAT下的受控经验分析，而不是硬件感知训练的一般理论。
## 77. `cs.LG` - Tabular Foundation Model for Generative Modelling [PDF](https://arxiv.org/pdf/2605.09424), [HTML](https://arxiv.org/abs/2605.09424)
### Authors
Xiangjian Jiang,Mingxuan Liu,Nikola Simidjievski,Tassilo Klein,Mateja Jamnik
### Background
生成建模是对基础模型的一项严苛考验，因为它需要在特定数据模式下实现稳健且全面的表征学习，而不仅仅是针对监督预测目标的优化。虽然近期关于表格形式基础模型的研究在预测建模方面取得了显著进展，但生成性表格形式基础模型仍然被研究较少。现有的表格基础生成器与异质表格数据的独特因果结构先验之间存在不一致，这是导致它们在生成合成数据质量上未能稳定匹配专门的数据集生成器的主要原因之一。
### Innovation
本文通过引入一个新的表格形式基础模型——TabFORGE，针对上述问题提出了创新解决方案。TabFORGE 是在预训练的因果感知特征编码器引导下，生成出统一潜在空间中的隐式学习到的因果信息。更重要的是，TabFORGE 通过两阶段设计对潜在建模和解码进行解耦：首先预训练一个基于得分的扩散变换器，然后使用去噪后的潜在嵌入预训练一个去噪对齐的解码器。这种设计有效地缓解了潜在嵌入在训练和推理之间常见的分布变化。
### Conclusion
我们对 TabFORGE 在 45 个真实世界数据集上与 22 种基准方法进行全面评估。结果表明，TabFORGE 能够有效学习并利用通用的表格形式表征，使得可以高效地生成高质量的合成表格数据，特别是在结构保真的方面表现尤为突出。
## 78. `cs.LG` - fmxcoders: 因子化掩码交叉编码器用于跨层特征发现 [PDF](https://arxiv.org/pdf/2605.09438), [HTML](https://arxiv.org/abs/2605.09438)
### Authors
Andreas D. Demou,Panagiotis Koromilas,James Oldfield,Yannis Panagakis,Mihalis A. Nicolaou
### Background
预训练Transformer中的许多特征跨越多个层，在推理过程中逐步形成，在残差流中保持，或由并行的MLP共同构建。交叉编码器（即跨层训练的稀疏字典）旨在在一个共享的潜在空间中恢复这些跨层特征。然而，标准交叉编码器在这一目标上表现不佳。尽管其解码器权重均匀分布在各层中，我们引入的功能一致性度量显示，每个潜在变量的激活主要由一个或两个特定层驱动。功能一致的潜在变量充当人类可解释的概念探测器（例如，州和城市），而交叉编码器所学习的层局部化的潜在变量倾向于识别表面模式，如数字检测器。
### Innovation
本文提出了fmxcoders，这是一种改进的交叉编码器方法，克服了两个结构限制：不限制的跨层参数化和未经正则化的跨层依赖。fmxcoders方法通过（i）用低秩张量分解替换编码器和解码器，并使每个潜在变量的每层权重源自一个共享的跨层基，以及（ii）采用沿层轴的随机层掩码，这是一种去噪约束，惩罚当单一层数被遮掩时潜在变量的贡献崩溃情况来解决这些问题。研究表明，fmxcoders方法在GPT2-Small, Pythia-410M, Pythia-1.4B, 和Gemma2-2B上显著提升了特征探测的F1得分（10-30分），超越了标准交叉编码器无法达到的标准层基线，减少了重建均方误差25-50%，并几乎将功能一致性均值提高了一倍。
### Conclusion
通过fmxcoders方法，我们发现其在大部分预训练语言模型上的表现优于标准交叉编码器，显著提升了潜在变量的功能一致性，并在特征探测方面表现出更高的表现。
## 79. `cs.LG` - 在预算受限的第一价格拍卖中使用未知私人价值进行竞价的学习方法 [PDF](https://arxiv.org/pdf/2605.09448), [HTML](https://arxiv.org/abs/2605.09448)
### Authors
Zihao Hu,Yuxiao Wen,Yuan Yao,Jiheng Zhang,Zhengyuan Zhou
### Background
数字广告转向第一价格拍卖 (FPA) 已经激发了大量研究，但现有研究通常假设访问价值 oracle，忽略了从受限数据中推断价值的现实情况。虽然线性处理效应 (LTE) 模型通过学习价值晋升来解决这一问题，但它们尚未适应具有硬预算约束或投资回报率 (RoS) 目标的真实场景，这些目标需要控制遗憾和违规行为。
### Innovation
本文提出了一个包容的原始对偶框架，用于受约束的第一价格拍卖，联合学习隐含的 LTE 价值参数和竞争对手的报价分布。这种方法同时学习引入了关键技术挑战：估计误差会动态地由拉格朗日乘数放大发悔，可能导致未定界的遗憾。通过利用强Slater条件和新型自适应热身程序来稳定对偶变量，解决了这一问题。该方法实现了接近最优的遗憾保证，提供了一个有理论支持的解决方案，用于具有隐含价值的受约束竞价。
### Conclusion
本研究首次为具有隐含价值的预算受限竞价提供了一个理论支持的解决方案，本文提出的框架实现了近乎最优的遗憾保证，解决了受约束的第一价格拍卖中引入的关键技术挑战。
## 80. `cs.LG` - RAwR: 基于近似等价划分的角色感知重连 [PDF](https://arxiv.org/pdf/2605.09457), [HTML](https://arxiv.org/abs/2605.09457)
### Authors
Riccardo Porcedda,Giuseppe Squillace,Bastian Epping,Andrea Vandin,Michael Schaub,Mirco Tribastone,Francesca Chiaromonte
### Background
尽管图神经网络（GNNs）在基于局部邻域信息的节点分类任务中表现出色，但当预测任务依赖于远程交互时，GNNs的性能往往会下降。这种现象主要归因于‘过度挤压’等领域结构瓶颈，限制了信号在网络拓扑中的传播。为了克服这一挑战，我们提出了RAwR，一种高效重连线框架，通过等价划分的概化图增强输入图，促进具有相同结构角色的节点之间的快速通信，从而减少系统的总有效电阻。
### Innovation
RAwR 引入了一种基于近似等价划分的角色感知重连线框架，该框架通过概括图结合节点的等价划分，加速具有相同结构角色节点之间的信息传播，降低系统的总有效电阻。此外，通过使用近似的等价划分，RAwR 可以控制性地减小概化图，并在最紧凑状态下恢复传统的主节点重连线技术。实验结果表明，RAwR 在多种基准测试中取得了最先进的效果。
### Conclusion
我们的贡献还包括对基于线性 GNN 的教师-学生模型的理论分析，揭示了基于角色的重连线的理论基础，并提出了谱角色提升（SRL）作为衡量最佳近似等价划分的指标，以最大化预测性能。
## 81. `cs.LG` - SEM轴a [PDF](https://arxiv.org/pdf/2605.09485), [HTML](https://arxiv.org/abs/2605.09485)
### Authors
Mario Edoardo Pandolfo,Enrico Grimaldi,Lorenzo Marinucci,Leonardo Di Nino,Simone Fiorellino,Sergio Barbarossa,Paolo Di Lorenzo
### Background
神经网络学习的潜在表示经常展现语义结构，，这种结构表示中，概念相似性性通过在嵌入空间中的几何邻近nearance表示。.然而在不同模型之间调整架构、调整训练样本data任务目标leasing和随机种子random会产生相似内容但不兼容几何结构的嵌入。这意味着对于潜在空间对齐的空间进行调整仍然是一个困难的问题，这对解释性ability和跨模态学习、联邦系统和语义通信等领域至关重要;但是由于缺乏大规模的模型多样性及具有丰富基准的数据集，进技术研究进展受到限制。
### Innovation
为了弥合这种差距，我们引入了 SEMAMEStuLiA,一项大型数据集,该数据集从一组包含1预训练的视觉模型中提取了超过 17,个潜在潜在表示,跨越八大标准图像分类基准数据集。 SEMAMEStuLiA将嵌入与描述架构、训练制制度、培训数据源料和模型规模的结构化元数据进行配对。我们展示了该资源的三个应用应用用:首先,分析单个潜在空间的概念组织A在模型和数据集之间表现出一致的原型簇和层次序化语觉关系嵌入空间。其次我们基于重建误差和下游任务性能对潜在空间之间的监督对齐映射进行基准测试
### Conclusion
通过结合表示化尺度与标准化元数据,SEMAMEStuLiA提供了研究潜在几何、评估对齐和开发下一代异构和可互操作人工智能的基础的可重复性性A该研究将几何与及探究潜在空间的几何性质、探照仪器和模型规模之间的关系如何影响制理解层次、专业化、增强现实和模型规模
## 82. `cs.LG` - DynaMiCS: 使用动态混合优化大语言模型性能约束的微调 [PDF](https://arxiv.org/pdf/2605.10770), [HTML](https://arxiv.org/abs/2605.10770)
### Authors
Eleonora Gualdoni,Sonia Laguna,Louis Bethune,Joao Monteiro,Pierre Ablin,Marco Cuturi
### Background
在多领域微调大型语言模型时，需要在提升目标领域性能的同时，保留一般知识、指令遵循或安全性评估等约束领域的性能。现有的数据混合策略依赖于固定的启发式方法或适应性规则，无法明确地保证这些能力的保留。
### Innovation
我们提出了一种名为DynaMiCS的动态混合优化器，将多领域微调视为有约束条件的优化问题。在每次更新时，DynaMiCS会进行短时的领域特定探针运行，以估计局部跨领域效应的斜率矩阵，这反映了每个微调数据集对每个评估领域的训练影响。这些估计值随后用于通过在概率单纯形上进行优化来计算混合权重，优化目标是提高目标领域的性能，同时使约束领域的损失保持在参考水平之下。
### Conclusion
在不同目标领域和约束领域数量的多领域微调场景中，DynaMiCS在目标领域改进方面表现出更强的效果，并且满足了更高的约束，同时降低了计算成本，不需要参考模型、逐例评分或手动调整的混合权重。
## 83. `cs.LG` - Muown：Muon优化中的行范数控制 [PDF](https://arxiv.org/pdf/2605.10797), [HTML](https://arxiv.org/abs/2605.10797)
### Authors
Kai Lion,Florian Hübler,Bingcong Li,Antonio Orvieto,Niao He
### Background
Muon已成为AdamW在语言模型预训练中的有力竞争者，但其在大规模应用时对权重衰减（weight decay）敏感。现有研究表明，对于不使用脱耦权重衰减的Muon，权重矩阵的谱范数在训练过程中会逐渐增大。通过将谱范数分解为行幅值因子和行相干性因子，研究发现前者是导致这一趋势的实证驱动因素，而后者在训练过程中表现良好。
### Innovation
本文提出Muown，这是一个可以直接替换Muon的优化器，它将行幅值向量视为隐式优化变量，并在由分解诱导的$boldsymbol{l}_boldsymbol{finity}$几何下对其进行更新，同时对剩余的方向组件应用与Muon相同的Muon优化。Muown在确定性和随机环境中都达到了最优非凸率，并在整个训练过程中，其随机噪声系数低于Muon。
### Conclusion
在FineWeb-Edu数据集上针对GPT样式的预训练模型，从124M到2.7B参数规模，Muown比Muon、SOAP、AdamW和Lion在困惑度上有提升。此外，Muown使近最优的学习率平台范围更广，减少了对权重衰减的敏感性，并且在适当的切割下实现了可忽略的计算开销即可避免谱范数漂移。
## 84. `cs.LG` - 错误次数限制的语言生成 [PDF](https://arxiv.org/pdf/2605.10809), [HTML](https://arxiv.org/abs/2605.10809)
### Authors
Jon Kleinberg,Charlotte Peale,Omer Reingold
### Background
目前对于有限语言类的语言生成问题的研究主要集中在确保最终一致性上，但对生成过程中累积的错误却没有给予足够的关注。本文从传统的根据最后一次错误的时间判断生成器成功与否这一标准出发，转变研究焦点，引入一种新的“错误限制生成”概念，旨在最小化生成算法输出的无效元素总数。
### Innovation
本文通过将问题转化为Joshi等人在2025年提出的“正确示例学习”框架来解决学习过程中累积错误的问题。提出了加权更新规则来推导错误上限，并针对有限类语言提供了同时达到最优错误时间$text{Cdim}(L)$和错误上限$boxed{rfloor text{log}_2 |L| rfloor}$的算法。对于可数无限语言流的情况，证明了无法同时实现对数级错误和前人工作中的收敛保证。还展示了该框架可以扩展到处理噪声对手，提供随对手最优性变化的错误上限保证。
### Conclusion
本文通过引入错误限制生成的概念，提出了加权更新规则，并展示了如何扩展到处理噪声对手。然而，对于可数无限语言流的情况，除非牺牲对数级错误，否则无法实现前人的收敛保证。
## 85. `cs.LG` - 非马尔可夫强化学习中的策略梯度方法 [PDF](https://arxiv.org/pdf/2605.10816), [HTML](https://arxiv.org/abs/2605.10816)
### Authors
Avik Kar,Siddharth Chandak,Rahul Singh,Soumitra Sinhahajari,Eric Moulines,Shalabh Bhatnagar,Nicholas Bambos
### Background
论文研究了非马尔可夫决策过程（NMDPs）中的强化学习策略梯度方法。在这种环境下，观测和奖励依赖于整个交互历史，不同于传统的马尔可夫决策过程（MDPs），因此需要新的方法来处理观测和奖励的这种依赖性。
### Innovation
提出了一种奖励中心的建模方法，联合优化智能体状态动力学和控制策略以最大化期望累积奖励。基于这一梯度表达式，提出了Agent State-Markov Policy Gradient（ASMPG）算法，并且在非马尔可夫任务中优于基于预测目标学习状态表示的方法。
### Conclusion
通过构建Agent State-Markov（ASM）策略类和相应的梯度定理，论文解决了非马尔可夫环境中的策略优化问题。通过理论上的收敛性证明和实验证明，ASMPG方法在非马尔可夫任务中表现出色。
## 86. `cs.LG` - 使用傅里叶嵌入的周期分布式表示 [PDF](https://arxiv.org/pdf/2605.10818), [HTML](https://arxiv.org/abs/2605.10818)
### Authors
Jakeb Chouinard
### Background
周期信号对于表征物理和感知现象至关重要。但是，使用标量和实角度量（如弧度和度）会遇到处理和区分接近角度困难的问题，特别是当它们的绝对差值超过π时。为避免这一问题，可以采用高维空间中的实值周期嵌入。这些表示还能使我们控制它们的点积相似性，构建出不同类型的核形状。
### Innovation
本文旨在展示如何构建这些嵌入并通过神经可实现的表示方案（即空间语义指针）来形式化狄利克雷和周期高斯核。
### Conclusion
该研究表明，通过傅里叶嵌入构建的周期分布式表示及其在不同核形状的应用提供了有效处理角度问题的新方法和技术。
## 87. `cs.LG` - Benchmarking Sensor-Fault Robustness in Forecasting [PDF](https://arxiv.org/pdf/2605.10822), [HTML](https://arxiv.org/abs/2605.10822)
### Authors
Alexander Windmann,Philipp Wittenberg,Gianluca Manca,Marcel Dix,Jens U. Brandt,Oliver Niggemann
### Background
现有的基于CPS的预测模型依赖于带有噪声、偏差、缺失或时间错位的传感器流。标准的预测评估通常通过名义误差选择模型，但并未展示这些模型在这些故障下是否依然 robust。因此，研究者们需要一个能够有效评估预测架构和改善鲁棒性方法的共享协议。
### Innovation
本文提出了一种名为SensorFault-Bench的共享CPS传感器故障压力测试协议，用于评估预测架构和鲁棒性改进方法的性能。它引入了一个操作分类法来组织方法比较，并通过四个真实的数据集和八个经过标准化严重性模型治理的得分场景，报告了最坏场景的退化、干净的平均平方误差（MSE）和最坏场景的故障时MSE，从而将相对鲁棒性与绝对误差区分开来。此外，通过分割故障转移训练和评估基准场景，明确的故障训练方法可以在相邻故障家族上进行训练，而在评估时使用单独的基准场景。
### Conclusion
实际结果显示，被干净MSE支持的预测架构在遇到故障时可能会出现急剧下降，并且干净MSE排名可能与最坏场景的故障时误差排名不一致。在两个单一目标数据集中，Chronos-2表现不佳，在ETTh1和Traffic数据集中，该模型表现出最大的最坏场景退化，所有通道在此数据集中作为预测目标。对于鲁棒性改进方法评估集，配对差异显示了选择性的退化减少：投影梯度下降对抗训练和随机训练在价值故障为主要观察到的退化时表现出较好的效果，而故障增强在可获得性故障为主要退化来源时则表现出较好的效果。SensorFault-Bench提供了开源代码、文档化数据访问以及重复性和扩展指南，使得新数据集、架构和鲁棒性改进方法可以在此统一的CPS传感器故障鲁棒性协议下进行评估。
## 88. `cs.LG` - SLIM：基于稀疏潜空间控制的可解释和目标导向的大语言模型驱动分子编辑 [PDF](https://arxiv.org/pdf/2605.10831), [HTML](https://arxiv.org/abs/2605.10831)
### Authors
Mingxu Zhang,Yuhan Li,Lujundong Li,Dazhong Shen,Hui Xiong,Ying Sun
### Background
大型语言模型具有强大的化学推理能力，使它们成为有效的分子编辑器。然而，与它们密集隐藏状态相关联的属性相关信息是隐含的，无法直接控制属性。因此，大量的编辑未能改善甚至降低了目标属性。
### Innovation
提出了一种可即插即用的框架SLIM（Sparse Latent Interpretable Molecular editing），通过一个可学习重要性门控的稀疏自编码器分解编辑器的隐藏状态为稀疏、属性对齐的特征。通过在该稀疏特征空间中精确激活属性相关维度，改进编辑成功率，而不修改模型参数。进一步支持了对编辑行为的可解释分析。
### Conclusion
在MolEditRL基准测试中，针对四种模型架构和八个分子属性进行全面实验，SLIM在基准线之上表现出一致性的改进，最高可达42.4个百分点的提升。
## 89. `cs.LG` - 条件异常检测方法在患者管理警报系统中的应用 [PDF](https://arxiv.org/pdf/2605.10847), [HTML](https://arxiv.org/abs/2605.10847)
### Authors
Michal Valko,Gregory Cooper,Amy Seybert,Shyam Visweswaran,Melissa Saul,Miloš Hauskrecht
### Background
异常检测方法在识别数据中的不寻常或有趣模式方面非常有用。最近提出的一种条件异常检测框架将异常检测扩展到仅在数据集的一部分属性上识别异常模式的问题，其中异常依赖于剩余属性的值。本文关注的是基于实例的异常检测方法，这些方法依赖于距离度量来识别对该检测最关键的数据集示例。
### Innovation
研究了各种度量方法和度量学习方法，以优化基于实例的异常检测方法的性能。探讨了一种条件异常检测方法在两个实际检测问题中的应用，分别为：患者社区获得性肺炎的异常入院决定检测，以及用于确认肝素诱导的血小板减少症（一种由肝素疗法引起的危及生命的情况）的HPF4测试的异常订单检测。
### Conclusion
基于实例的方法在上述两个实际检测问题中显示出优势，证明了条件异常检测方法在患者管理警报系统中的应用潜力。
## 90. `cs.LG` - Clin-JEPA：EHR患者轨迹上的联合嵌入预测预训练的多阶段协同训练框架 [PDF](https://arxiv.org/pdf/2605.10840), [HTML](https://arxiv.org/abs/2605.10840)
### Authors
Yixuan Yang,Mehak Arora,Ryan Zhang,Baraa Abed,Junseob Kim,Tilendra Choudhary,Md Hassanuzzaman,Kevin Zhu,Ayman Ali,Chengkun Yang,Alasdair Edward Gent,Victor Moas,Rishikesan Kamaleswaran
### Background
现有的JEPA架构已经在机器人学和视觉中的潜空间规划和高质量表示学习方面取得了成功，但是将这种范式扩展到EHR数据中—以获得一个同时预测患者轨迹并提供多种下游风险预测任务而不需每任务微调的单一骨干模型—仍是一个开放的挑战。现有的JEPA框架或在预训练后丢弃预测器（I-JEPA,V-JEPA）或在冻结的预训练编码器上训练预测器（V-JEPA 2-AC），而Clin-JEPA则在此前工作基础上进行改进。
### Innovation
Clin-JEPA提出了一个五阶段的协同训练框架，通过不同阶段的训练策略，稳定地协同训练了一个基于Qwen3-8B的编码器和一个92M参数的潜轨迹预测器。实验结果表明，Clin-JEPA在多个评价指标上优于基线方法，包括48小时预测中潜轨迹的$boldsymbol{text{lp}}ormalsize_1$漂移显著收敛（减少15.7%），编码器学习到了更有临床意义的潜在几何结构，以及在多任务下游任务上的性能超越了强大的表结构和序列基线模型。
### Conclusion
Clin-JEPA框架在MIMIC-IV ICU数据集上表现出了优越性，能够在ICareFM EEP和8个二元风险任务中分别获得0.851和0.883的平均AUROC，优于基线平均值。该框架有效解决了单任务预训练和协同训练的不足，实现了对患者轨迹的稳定预测和多种下游任务的高效支持。
## 91. `cs.LG` - CAMAL: 通过分割掩码提高注意力对齐和忠实度 [PDF](https://arxiv.org/pdf/2605.08325), [HTML](https://arxiv.org/abs/2605.08325)
### Authors
Rajdeep Singh Hundal,Yan Xiao,Jin Song Dong,Manuel Rigger
### Background
许多视觉数据集不仅提供标注的图像，还提供分割掩码，以便支持各种任务。现有的方法主要集中在如何更好地理解模型的注意力机制及其与真实图像中区分性区域的关系和一致性。
### Innovation
本文提出了Class Activation Map Attention Learning（CAMAL），一种有效且可扩展的方法。CAMAL利用分割掩码来提高视觉模型的注意力对齐和忠实度。具体而言，注意力对齐是指模型的注意力与真实的区分性区域的一致程度，而注意力忠实度是指注意力对决策的影响程度。通过将模型的注意力与相应的分割掩码获得的真实区分性区域进行比较，并像辅助正则化器一样引导注意力，CAMAL能够在训练过程中提高注意力的对齐和忠实度。
### Conclusion
CAMAL在深度学习（DL）和深度强化学习（DRL）两种学习范式下均显示出一致且显著的改进，特别是在注意力对齐方面具有统计显著性的增益，而注意力忠实度提高了35%以上。此外，研究结果表明，通过分割掩码中包含的空间信息可以有效地引导模型注意力，从而提高可解释性和泛化性能而无需增加推理成本。
## 92. `cs.LG` - 关于恢复隐含霍克斯网络所需的观测时间 [PDF](https://arxiv.org/pdf/2605.08400), [HTML](https://arxiv.org/abs/2605.08400)
### Authors
Jonas Linkerhägner,Michele Bortolasi,Lorenzo Baldassari,Maarten V. de Hoop,Ivan Dokmanić
### Background
工程、社会和自然中的相互系统动态通常发生在潜在网络控制的实体间交互过程中。研究从事件驱动观察中推断这些网络的问题，这一问题在金融、地震学和神经科学中自然出现。尽管已有大量算法工作来解决这个问题，但理论结果相对稀缺。
### Innovation
该论文提出并证明了霍克斯过程类中，为精确恢复基础网络所需的时间上限是 $text{log} d$，其中 $d$ 是交互实体的数量。采用剪辑和分组事件数据进行筛选，然后通过最小二乘法修正的方法构建了估计器，同时结合Fano不等式和Jacod的Girsanov公式，得出了下限证明。
### Conclusion
研究表明，为了精确恢复隐含的霍克斯网络，观察时间应为 $text{log} d$ 的数量级。这对于具有稀疏、弱相互作用的霍克斯过程类是充分且必要的。
## 93. `cs.LG` - 使用时间扭曲递归神经网络进行枯死燃料湿度预测的迁移学习 [PDF](https://arxiv.org/pdf/2605.08379), [HTML](https://arxiv.org/abs/2605.08379)
### Authors
Jonathon Hirschi,Jan Mandel,Adam Kochanski
### Background
实时气象站传感器提供了10小时燃料湿度的大数据，但其他燃料类别的观测数据稀少。为了预测不同燃料类别的湿度，本文使用迁移学习，将预先训练在10小时燃料湿度（10h FMC）上的递归神经网络（RNN）调整为预测1小时、100小时和1000小时燃料的湿度。研究利用了在俄克拉何马州进行的标志性实地试验的数据，该试验用于校准先进的Nelson燃料湿度模型。
### Innovation
提出了一种时间扭曲的迁移学习方法，用于调整具有长短期记忆（LSTM）层的递归神经网络（RNN）中学习的动力学，以实现跨燃料湿度类别的任务转移。这种方法借鉴了大量实时10小时燃料湿度数据，通过调整将该模型应用于预测其他不同时间尺度燃料的湿度。
### Conclusion
该方法通过迁移学习有效地利用了10小时燃料湿度的大数据，并通过使用俄克拉何马州的地标性实地试验数据验证了其预测不同燃料湿度的能力。
## 94. `cs.LG` - 主动多预测增强推理 [PDF](https://arxiv.org/pdf/2605.08429), [HTML](https://arxiv.org/abs/2605.08429)
### Authors
Nicholas Brawand,Nima Leclerc,Anhthy Ngo,Matthew Peterson,Sriram Vishwanath,Laith Alhussein,Ben Wellner
### Background
在部署后监测医疗AI系统时，需要具有统计有效性和标签效率的方法，但依赖于临床文书审查的黄金标准标签成本高昂。现有的预测驱动推理（PPI）和主动统计推理（ASI）方法通过结合少量的标签样本和大量的模型预测来减少标签成本，但这两者都只能针对单一预测器，不符合现代临床流程中多预测器并存的不同成本和准确度的需求。
### Innovation
研究人员提出了一种名为主动多预测增强推理（AM-PPI）的新方法。AM-PPI根据成本合适的预测器子集为每个实例分配最优预测，按照选定子集的剩余不确定性比例抽取黄金标准标签，并对预测进行重新加权以最小化估计器方差，同时在部署时保持预算控制。该方法通用化了ASI以利用多个预测器，并从全局分配扩展到实例级自适应路由。通过推导闭合形式的Karush-Kuhn-Tucker（KKT）条件并证明对偶性质，研究人员表明联合问题虽然不是联合凸的，但其稳定点是全局最优的。此外，AM-PPI还在线性预测增加逆倾向加权类中具有有界波动下限的最小方差无偏估计，还提供了一种闭合准则来判断是否存在多个预测器的帮助。
### Conclusion
在合成数据和三个医疗监测任务上，AM-PPI在预算范围内的路由适用时，窄了10到40个百分点的置信区间，而在其他情况下与更好的基线匹配。
## 95. `cs.LG` - 各架构层防御效果评估：有状态LLM代理中持久性内存攻击的机制性评价 [PDF](https://arxiv.org/pdf/2605.08442), [HTML](https://arxiv.org/abs/2605.08442)
### Authors
Jun Wen Leong
### Background
现有针对LLM代理的持久性内存攻击成功率达到较高水平，通过RAG检索的恶意指令被存储并在后续会话中执行。但是，针对这一攻击类别的防御措施没有系统性评价。
### Innovation
该研究系统性地评估了六种防御措施在四个架构层面对延迟触发攻击的效果，特别关注持久性内存攻击对九个开源模型的影响。
### Conclusion
多数防御措施效果不佳，仅内存分割(Layer Memory Sandbox)防御措施成功将攻击成功率降低至0%，针对某些模型在无防御措施情况下有效，却在使用内存分割后效果反而更差，零攻击成本抗击率为100%。这些结果有助于理解每种防御类别在面对持久性内存攻击时的失败原因，为防御投资决策提供依据。
## 96. `cs.LG` - HEART: 一种使用混沌加密进行安全心电图信号实时遥测的高效自适应框架 [PDF](https://arxiv.org/pdf/2605.08456), [HTML](https://arxiv.org/abs/2605.08456)
### Authors
Beyazıt Bestami Yuksel
### Background
实时分析和安全传输心电图（ECG）信号对于远程医疗应用中的准确诊断和保护患者隐私至关重要。本研究提出了一种新的实时ECG监测系统，该系统利用从每位患者自身ECG信号特征中提取的学习型密钥生成器（LKG）动态生成唯一的加密密钥，这些密钥决定了用于混沌加密的logistic映射的参数r和x0。系统在数据采集后立即安全地加密实时ECG数据，确保云中传输和存储的安全性。针对远程临床访问，加密数据下载并解密至医生端，使用匹配密钥或在云端安全存储进行解密。这种方法消除了传统密钥交换的需要，通过分段生物特征密钥刷新和最小熵评估支持的联合置换和XOR扩散显著提高了实际中的穷举密钥搜索成本。
### Innovation
1. 提出了一种基于每位患者自身ECG信号特征的可学习密钥生成器（LKG）的实时ECG监测系统，用于混沌加密。2. 分段生物特征密钥刷新和联合置换与XOR扩散技术相结合，提高了加密安全性。3. 与静态密钥方法相比，可学习的生物特征密钥设计提供了更高的一次性和不可预测性。4. 通过多种安全性评估，证实了该方法的安全性和有效性。
### Conclusion
研究通过全面的安全性评估，包括香农熵、相关性和自相关性干扰直方图统计、NIST SP 800-22频谱测试、明文密钥敏感性、雪崩效应、FFT谱平坦度和抗噪声及遮挡性比较，证明了该混沌加密方法的强度。重建精度在均方误差（MSE）< 5x10^-6、峰值信噪比（PSNR）>52 dB 和平均绝对误差（MAE）<0.002，表明接近无损解密，保持诊断特征的完整性。同时，保持了实时性能，加密延迟低。
## 97. `cs.LG` - 桥接序列和图结构以预测表观遗传年龄 [PDF](https://arxiv.org/pdf/2605.10541), [HTML](https://arxiv.org/abs/2605.10541)
### Authors
Yao Li,Xikun Zhang,Xiaotao Shen,Sonika Tyagi,Xin Zheng,Jiaxing Huang,Feng Xia
### Background
基于DNA甲基化的表观遗传时钟已成为估算生物学年龄的强大工具，广泛应用于衰老研究、与年龄相关的疾病研究以及长寿科学。尽管在表观遗传年龄预测的机器学习方法方面取得了进展，包括惩罚性线性回归、深度前馈网络、残差架构和图神经网络，但现有的方法没有在统一框架内同时建模共甲基化图结构和位点特异性DNA序列上下文。
### Innovation
本文提出了一种统一的序列-图集成框架，以填补现有方法的空白。该框架通过轻量级的门控调制机制整合了八维DNA序列统计特征，这些特征在进行图卷积之前根据序列决定的生物学相关性适应性地放大每个位点的甲基化信号。
### Conclusion
在3,707个血液甲基化样本上对30种基线进行全面评估后，我们的方法实现了3.149年的测试MAE（平均绝对误差），比最强的基于图的基线提高了12.8%。生物启发的统计特征优于基于CNN的序列编码，表明这种数据制度下手工设计的序列特征比端到端学习表示更有效。后验可解释性分析指出，与年龄相关的CpG密度和局部腺嘌呤频率是具有年龄依赖重要性变化的特征，这与已知的CpG密度高启动子区域甲基化过度的机制一致。我们的代码可以在以下链接获取：this https URL。
## 98. `cs.LG` - 跨云和边缘的稳健性污水溢流监控解决方案 [PDF](https://arxiv.org/pdf/2605.10592), [HTML](https://arxiv.org/abs/2605.10592)
### Authors
Vipin Singh,Tianheng Ling,Peter Ghaly,Felix Grimmeisen,Gregor Schiele,Felix Biessmann
### Background
许多历史悠久的城市中结合式溢流系统在面对极端降雨事件时越来越不堪重负，这可能导致结合式溢流（CSO）并引发严重的环境和公共卫生问题。预见性地预测溢流池的填满动态对于预警容量超出，并能够在必要时采取预防措施至关重要。
### Innovation
该研究提出了一种基于Web的应用程序演示器（可以通过提供的链接访问），它将深度学习预测方法集成到了云端和边缘设备中，同时构建了一个互动监控面板。这种系统对网络中断具有鲁棒性，可以在没有网络连接的情况下继续运作。
### Conclusion
该系统为跨云和边缘设备提供了一种稳健的污水溢流监控解决方案，通过融合云端及边缘计算的预测方法来增强对极端降雨事件导致的结合式溢流的应对能力。
## 99. `cs.LG` - 通过数据-网络实现近 迀- 耗 蓍 胝 肭 蠪 岢 蠊 蓘 肭 榢 胁 蓘 炭 哘 争 傭 抶 贀 [PDF](https://arxiv.org/pdf/2605.10590), [HTML](https://arxiv.org/abs/2605.10590)
### Authors
Emil Javurek,Dennis Frauen,Marie Brockschmidt,Jonas Schweisthal,Stefan Feuerriegel
### Background
现有的因果敏感性性 分析通常是针对单一实例的程序， 迥 俽 肭 岢 顷 ， 芶 岫 讃 岢 苑 悭 亏 俄 苞性 亏 妲 港 苐藏 吝 n 佻 哑 僿 苀장 港 苐藏 嬿 佻 吳 苌 娀 枨 苾 苑 儶 岯 苢 苰 苀장 渐藏 傭 捳 苲 苂 苲 苆 僿 苰 苀 苯 苎 苯 苨 苮 苰 苆 苼 苠택 苊 嗂 姷 嚈 壝 妬 塰 塰 苨 亏 苂 咐 苭 苌 苍 苂 儗 僑 婙 崀 苘认 悄 苐藏 吨 n 它 苠 苭 苊 苳 苄 苀장 比 弐藏 岐 苫자 
### Innovation
本文提出了一种基于先验数据构造的因果敏感强度分析的通用化方法，具体而言,我们提出了一种通过先验数据拟合网络来-context学习的方法来进行普遍适应的因果敏感度分析，这种方法直接基于已有实验数据来构建敏感度边界,并通过在因果效果的优化最大化和敏感度分析的违伴随措施中间接构造训练标签
### Conclusion
我们提出的基于先验数据的因果敏感程度分析方法通过标准凸性和线性条件下能获取帕累托前沿的有效实现，并 僦 嵈 婆 苝체 苨 攝始化 肭제 唄 枳 (5 徎 俹 ( ) 
## 100. `cs.LG` - 单一层次模型可以进行语言建模 [PDF](https://arxiv.org/pdf/2605.10643), [HTML](https://arxiv.org/abs/2605.10643)
### Authors
Zanmin Wang
### Background
现代的语言模型通过堆叠多个层级来扩展深度，每个层级保持其自身的状态，例如transformers中的每个层级都有自己的一组键值缓存，Mamba、Gated DeltaNet（GDN）、RWKV和xLSTM中的每个层级都有自己的矩阵。而生物系统则更多依赖于递归，而非堆叠结构。该研究旨在探讨单一递归结构在语言模型中的应用潜力。
### Innovation
提出了Grounded Prediction Networks（GPN）：通过单一的递归单元——一个前馈网络（FFN）和一个共享矩阵内存，每次迭代都重新审视一个状态向量。130M参数的1层GPN+M在FineWeb-Edu上的困惑度达到了18.06，分别与12层Transformer++（16.05）和10层GDN（15.34）的性能差距分别为13%和18%。双层版本的GPN进一步缩小了与深层基线的差距。
### Conclusion
尽管与深层基线的性能存在差距，但GPN模型通过单一的递归块利用了一个状态向量，可以直接检查其几何特性，例如持续的默认标记方向、包含内容的数十个标记范围，以及自发分裂成快慢记忆池的记忆头。
## 101. `cs.LG` - 迈向可信证书：科学人工智能的任务感知型异常检测 [PDF](https://arxiv.org/pdf/2509.25080), [HTML](https://arxiv.org/abs/2509.25080)
### Authors
Bogdan Raonić,Siddhartha Mishra,Samuel Lanthaler
### Background
数据驱动模型在关键科学领域，如天气预报和流体动力学中正被越来越多地采用。然而，这些方法在遇到非分布域数据（OOD数据）时可能会失败，特别是在回归任务中检测这种失败仍然是一个开放的挑战。
### Innovation
本文提出了一个新的基于评分扩散模型的OOD检测方法，通过估算联合似然性，该方法不仅考虑输入数据，还考虑回归模型的预测，从而提供一种任务感知的可靠性评分。
### Conclusion
在多个科学数据集中（包括偏微分方程数据集、卫星图像和脑肿瘤分割），本研究显示联合似然性与预测误差高度相关。本研究为构建可验证的‘可信证书’奠定了基础，从而提供了一种评估基于AI的科学预测可信度的实用工具。相关代码已公开在美国各地网址。
## 102. `cs.LG` - 基于不确定性量化的大数据分析集算操作学习 [PDF](https://arxiv.org/pdf/2509.25646), [HTML](https://arxiv.org/abs/2509.25646)
### Authors
Lei Ma,Ling Guo,Hao Wu,Tao Zhou
### Background
大数据分析中的操作学习对于解决科学中的不确定性和复杂性波问题是关键。 然而， DeepONets 尟能强大仅解决了这个问题的一部分， 專 们需要确定传感器的数量和位置但是缺乏不确定性的量化机制。 这使限制了它们在实际应用中的潜力。近来提出的关于交换不变性延展
### Innovation
本研究提出了一种名为UQ-SONet的交换 不变算子学习框架, 该框架内置了不确定性的量化机制。 UQets 通过整合一个集合变换嵌入方法以处理稀疏的和不定位置的数据, 采用条件变异动特效编码器来近条件识别操作的条件分布。 U on = 框实现了通过最小化负EL ELBO on 使得UQet提供形成性性的不确定性估计保持预测准确性。实验证结果 瑜定确定和 和 随机原生偏微分算（ 包括纳维尔斯-斯升方程例示范合了提出框架的稳健性和有效性。
### Conclusion
本研究提出的UQ-SONet框架能 了针对操作学习中的不确定性和稀疏数据的问题的解决方案 
## 103. `cs.LG` - NEO: 无需优化的测试时自适应通过潜在重置中心 [PDF](https://arxiv.org/pdf/2510.05635), [HTML](https://arxiv.org/abs/2510.05635)
### Authors
Alexander Murphy,Michal Danilowski,Soumyajit Chatterjee,Abhirup Ghosh
### Background
TTA方法通常计算成本高，需要大量的数据才能有效适应，或者对外部超参数的敏感性高。这些方法需要超参数的调整和优化过程，因此可能会增加计算开销并限制其在资源有限环境中的适用性。
### Innovation
本文基于潜在空间几何学的理论，通过将目标数据嵌入重新置于原点来显著改善源数据和分布偏移样本之间的对齐。这种洞察促成了NEO方法，这是一种无超参数的完全TTA方法，它在与传统推理相比几乎没有增加计算成本的情况下，改善了ViT-Base在ImageNet-C上的分类准确率。此外，NEO在资源受限的硬件上（如Raspberry Pi和Jetson Orin Nano）表现出显著的性能提升，减少了推理时间和内存使用。
### Conclusion
实验结果表明，NEO在3种ViT架构和4个数据集上均可高效有效地用于TTA。NEO不仅在模型校准指标上表现良好，还能够在ImageNet-C上从一个类别快速适应到其他999个类别，同时在资源消耗方面优于已有的7种TTA方法。
## 104. `cs.LG` - GLAI: GreenLightningAI for Accelerated Training through Knowledge Knowledge Decouling [PDF](https://arxiv.org/pdf/2510.00883), [HTML](https://arxiv.org/abs/2510.00883)
### Authors
Jose I. Mestre,Alberto Fernández-Hernández,Cristian Pérez-Corral,Manuel F. Dolz,Jose Duato,Enrique S. Quintana-Ortí
### Background
传统的多 处件 夕 minib 和 又MLPs 中覞 朌asts 休 繷u8470两 ?种 燢 懠知 縮 ?u5e o圥，， 涉妌 nb 陾 ,퇞s line 臡和 weights. GLAI 的引入旨在解决这一问题，通过分离神经网络中两种纠缠的知识力的知识，一种是表示结构的激活模式，另一种是通过权重和偏置表示的数量知识。
### Innovation
GLAI提出了一种新的架构设计理念， 将 MLP（多层感知器）从两个方面进一步拆分为：(非结构化的知识 (由ReLU激活函数诱发的激活模式) 和和以及结构化的知识 (通过权值和重和和重和偏置表示的数量知识)。一方面,，通过固定非结构化的知识，的策略，GLAI将MLP构架重新定义为路径的组合,，使得只优化数量化知识。。 这种重新定义引入了ML多认为MLp (多层感知器) 具有的普遍性模有能力, 而且实现了了一个更加高效的训练过程，相比现有方法将训练时间减少了约40%。。此外，GLAI不仅是一个分类器， 
### Conclusion
综上，格GLAI在多个实验设置中均能能够超越具有等同样数量的参数的ml MLP (多层感知机), 踜且且收敛速度更快。。 怾 从而GLAI提出了 s 证 一设计原理， 叙为其他认为大型架构的设计提供了的可能性， 軅 如特别是对于像 如 transformer (变换器器) 这样的架构,在其中的mlp (多层感知)块块占据了了大量的计算资源.
## 105. `cs.LG` - 使用广义Jensen-Shannon偏差进行大型语言模型生成文本的黑盒检测 [PDF](https://arxiv.org/pdf/2510.07500), [HTML](https://arxiv.org/abs/2510.07500)
### Authors
Shuangyi Chen,Ashish Khisti
### Background
研究在实际限制下机器生成文本的黑盒检测方法：评分模型（代理语言模型）可能会与未知源模型不符，并且每个输入的对比生成成本高昂。
### Innovation
提出了一种基于参考的检测器SurpMark，通过计算段落中词的惊异值动态来进行总结。SurpMark将惊异值离散化成可解释状态，为测试文本估算状态转移矩阵，并利用广义Jensen-Shannon (GJS) 距离的间隙来计算得分。这项研究提供了设计指南，以确定数据变化时的离散化区间，并为测试统计量提供了理论依据。
### Conclusion
实验证明，SurpMark在多个数据集、源模型和场景中持续超越基线，证明了其在不同领域和生成器中的强大鲁棒性；在超参数敏感性方面的实验结果帮助解释了理论结果并表现出一致的趋势。
## 106. `cs.LG` - Control-Augmented Autoregressive Diffusion for Data AssiminGenerate [PDF](https://arxiv.org/pdf/2510.06637), [HTML](https://arxiv.org/abs/2510.06637)
### Authors
Prakhar Srivastava,Farrin Marouf Sofian,Francesco Immorlano,Kushagra Pandey,Stephan Mandt
### Background
尽管在测试时缩放和扩散微调方面取得了进展， ARDMs的测试时指导研究仍然不足开发。 短周期未来操量防止预测是ARDMs的核心挑战之一, 以往的研究往往集中于预先训练的ARDMs模型本身，而忽视了通过控制器进行未来操量调整的重要性。 本研究旨在探索一种新的方法，通过引入一个计划控制器来预观测和ARDMs的未来操量，从而提高模型的稳定性和准确性。
### Innovation
研究提出了一种递归框架，让已预先训练的ARDMs模型能够通过一个离线训练的控制器预观测未来操量动态。控制器通过计划未来操量的效果学习学习纠正措施， 穿过终端成本目标最小化的问题，生成出一个适用的策略用于指标导生成。灵感来源于对ARDMs轨迹的随机最优控制视角，该方法在每个消噪亚步中注入小调整并且始终保持在预先模型设定的参数附近。在混沌时空域-时空偏微分方程（spatial-differential equations, PDEs）中进行数据稀疏观测下的数据同量试验。方法在计算和上提供了显著的加速改进了现有方法在准确性上的同时也展示了在较大规模的生成任务上的的优越表现。
### Conclusion
该方法在两种标准PDEs及以及一个ECMWF重分析v5中模拟了一系列观测条件下，始终改善了稳定性并在准确性上也表现出类似改进。相比之下进行了量大规模的生成任务实验上进一步展示了这种方法的优越性。在混沌时空- sp微分方程下的数据同时任务上大幅领先于当现有的方法这一其他-of-the the-art-ed-t一直处于现场状态的前端地位。
## 107. `cs.LG` - 针对在线 bilevel 优化的完全一阶算法 [PDF](https://arxiv.org/pdf/2602.11665), [HTML](https://arxiv.org/abs/2602.11665)
### Authors
Tingkai Jia,Cheng Chen
### Background
现有的在线 bilevel 优化（OBO）算法主要基于超梯度下降法，需要访问海森矩阵-向量积（HVP）黑箱，这可能导致高计算成本。
### Innovation
该论文提出了一个无需 HVP 的完全一阶 OBO 算法。通过将原始 OBO 问题重新表述为具有不等式约束的单一级别在线问题，并构建一系列拉格朗日函数，消除了隐式微分产生的 HVP 问题。此外，还提出了一个在每次内层迭代中具有自适应方案的改进变体，消除了 $H_{2,T}$ 的依赖性，并达到了 $O(text{log }T + V_T)$ 的遗憾界。在随机 OBO 设置下，确立了完全一阶算法的遗憾界。
### Conclusion
论文提供了一个完整的实证测试，证明了所提算法的有效性，并支持了其中的理论发现。理论保证了算法在总迭代次数 $O(Ttext{log } T)$ 下实现了 $O(1 + V_T + H_{2,T})$ 的遗憾界，同时引入额外的梯度变异项建立了递减遗憾界。
## 108. `cs.LG` - 序贯成员推理攻击 [PDF](https://arxiv.org/pdf/2602.16596), [HTML](https://arxiv.org/abs/2602.16596)
### Authors
Thomas Michel,Debabrota Basu,Emilie Kaufmann
### Background
现代AI模型不是固定的，在其生命周期中会经历多次更新。为了更严格地审计隐私，研究者提出了一种新的攻击方法——序贯成员推理攻击（SeMI攻击），该方法通过利用连续的模型序列，并在受控插入时间点注入目标标记来实现更精确的隐私审计。研究发现，通过访问模型序列可以比仅审视最终模型更强地触发成员推理攻击，因此SeMI*攻击展示了隔离特性——其效能取决于目标插入前后获取到的统计信息。
### Innovation
提出了一种新的序贯会员推理攻击（SeMI攻击），并且开发了SeMI*，一个用于在特定插入步骤识别目标最佳攻击方法。利用该攻击展示出通过访问模型序列能够比仅审视最终模型更强地触发成员推理攻击，并且开发了基于模型梯度的白盒攻击和基于损失函数的黑盒攻击，这些攻击适用于遵循（DP-）SGD训练的模型。实验结果表明，SeMI攻击在多个数据集和模型上均比基于快照的基线方法具有更高的效能，并且由于对插入时间的控制以及模型序列上的观察结果，使得隐私审计更加严格。
### Conclusion
SeMI攻击能通过访问连续的模型序列来进行更有效的隐私审计，这比仅审视最终模型的隐私审计更严格。这种攻击方法在多个数据集和模型上都表现出了更高的效能，并利用了对插入时间的控制以及模型序列上的观察结果。
## 109. `cs.LG` - 防止基于客户端异质性性的联邦低秩适配中的秩坍塌 [PDF](https://arxiv.org/pdf/2602.13486), [HTML](https://arxiv.org/abs/2602.13486)
### Authors
Fei Wu,Jia Hu,Geyong Min,Shiqiang Wang
### Background
联邦学习场景中，下游任务的预训练模型适应通常是高效且隐私保护的方法的一个挑战。特别是在系统资源和数据分布存在客户端异质性的场景下，传统的联邦低秩适应方法面临着挑战。之前的实证研究表明,基于奇异值值值值值分解的异质联邦低秩适应方法（Heterogeneous FedLoRA) 在某些情况下会导致秩坍塌现象，使得总的模型性能不尽如人愿，并且对于秩配置的高度敏感性性资源较大的问题。
### Innovation
本文提出了一种名为 raFLoRA 的秩分额分配方法，它通过将本地更新分为分成不同秩部分部分，并通过对每个分权重化每客户端的贡献进行聚合来优化了基层模型的适应过程。相比传统的方法，raraFLoRA 通过防止秩坍塌、提升了模型在多种异质配置下的性能和鲁棒性。
### Conclusion
广泛的实验表明 raFLoRA 方法在视觉、语义和理解和推理任务中能够有效防止秩坍塌、提升模型性能并与强的 Federal FedLoRA 基准方法相比增强了鲁棒性。
## 110. `cs.LG` - 离散双闭区间流在各向同性噪声不变的特征分解中的应用 [PDF](https://arxiv.org/pdf/2602.13759), [HTML](https://arxiv.org/abs/2602.13759)
### Authors
ZhiMing Li,JiaHe Feng
### Background
本文研究在流动观测$C_k = C_{text{sig}} + tau_k^2I + E_k$下关于$SO(n)$上的特征分解，其中各向同性背景$tau_k^2I$可能是时间变化的且可能非常大。标准算法将稳定性与$orm{C_k}_2 thicksim tau^2$对齐，导致步长、收缩率、迭代次数随着噪声底限降低而降低。作者注意到$tau^2I$位于矩阵代数的中心，因此不应进入特征空间的动力学。
### Innovation
作者构建了一个离散的双闭区间流，其反对称生成器$boldsymbol{text{Ω}} = [boldsymbol{text{A}}, text{diag}(boldsymbol{text{A}})]$作用在切线李代数$frak{so}(n)$中，这样标量倍数的单位矩阵通过反对称性消失。由此产生的轨迹、李亚普诺夫函数以及最大稳定的步长$boldsymbol{text{η}}_{text{max}} = frac{1}{text{L}_C}$仅依赖于无迹信号$C_e$——实现了点到路径$tau^2$不变性。建立基于噪声球的输入到状态稳定性和通过严格鞍点几何和离散Łojasiewicz论证的全局收敛性。
### Conclusion
本文建立了基于无迹扰动的噪声球输送到状态稳定，并通过严格鞍点几何和离散Łojasiewicz论证证明了全局收敛性。另外，框架还可以扩展到迹数为$k$的特征追踪问题在Stiefel流形$text{St}(k,n)$上，每步仅需$k$次矩阵-向量乘法。
## 111. `cs.LG` -  reasoning models 的拒绝行为在何处？ [PDF](https://arxiv.org/pdf/2507.03167), [HTML](https://arxiv.org/abs/2507.03167)
### Authors
Kureha Yamaguchi,Benjamin Etheridge,Andy Arditi
### Background
现有对话模型在生成首个响应标记之前必须决定是否拒绝有害请求，而推理模型则在最终输出之前生成延长的思维链。这引发了一个自然问题：在推理模型的思维链过程中，何时决定拒绝？本文研究了这一过程，并展示了整个研究的四个开源推理模型。
### Innovation
发现推理模型的决策结构中存在细微的差异，这些差异可以通过删除激活信号中的线性拒绝方向来影响是否拒绝有害请求。此外，这些模式在从同一教师模型导出的精炼模型之间可以转移。进一步地，研究观察到删除这些方向在推理模型中比在非推理模型中更一致地增加有害合规率。
### Conclusion
通过减轻线性拒绝方向，有害合规率增加，但效果不如在非推理模型中显著，且对一般能力造成一定程度的损害。
## 112. `cs.LG` - LLM-Augmented Chemical Synthesis and Design Decision Programs [PDF](https://arxiv.org/pdf/2505.07027), [HTML](https://arxiv.org/abs/2505.07027)
### Authors
Haorui Wang,Jeff Guo,Lingkai Kong,Rampi Ramprasad,Philippe Schwaller,Yuanqi Du,Chao Zhang
### Background
重排合成是有机化学和药物开发的核心过程，涉及将目标分子分解为更简单的前体并通过一系列有效的反应。尽管最近的机器学习研究取得了单步重排模型和后续路线搜索的进展，但仍然受到可能路径的庞大组合空间的限制。同时，大型语言模型展示了显著的化学知识，暗示它们可能解决化学中的复杂决策任务。本文探讨了大型语言模型是否能够有效地解决多步重排合成规划问题。
### Innovation
本文提出了一种高效的反应路径编码方案，并提出了一种新颖的路线级搜索策略，超越了传统的逐步反应物预测方法。研究显示，这种基于大型语言模型的方法在重排合成规划中表现出色，并自然地扩展到广泛的可合成分子设计挑战。
### Conclusion
本文通过全面评估展示了基于大型语言模型的方法在重排合成规划中的优势，并将其自然应用于更广泛的可合成分子设计挑战。
## 113. `cs.LG` - 一条轨迹，一个标记：基于全景亚对象轨迹的语义视频标记 [PDF](https://arxiv.org/pdf/2505.23617), [HTML](https://arxiv.org/abs/2505.23617)
### Authors
Chenhao Zheng,Jieyu Zhang,Mohammadreza Salehi,Ziqi Gao,Vishnu Iyengar,Norimasa Kobori,Quan Kong,Ranjay Krishna
### Background
有效的视频标记对于扩展长视频上的转换器模型至关重要。当前的方法使用时空 patch 进行视频标记，这导致了过多的标记和计算效率低下。最佳的标记减少策略会损害性能，在相机移动时也几乎不能减少标记数量。
### Innovation
引入了基于全景亚对象轨迹的语义视频标记法，这种方法根据对象轨迹组织标记，而非固定 patch。该方法与基本的知觉原则相一致，确保标记反映场景复杂性而非视频时长。提出了一种视频编码器 TrajViT，它提取对象轨迹并将其转换为语义有意义的标记，显著减少了冗余性同时保持了时间连贯性。TrajViT 通过对比学习进行训练，在多个视频理解基准测试中显著优于时空 ViT（ViT3D），并且在视频-文本检索任务中，与 10 倍减少标记相比实现了 6% 的前五召回率大幅领先。
### Conclusion
TrajViT 是第一个在多种视频分析任务中始终优于 ViT3D 的高效编码器，使其成为一个稳健、可扩展的解决方案。
## 114. `cs.LG` - 通过随机密钥选择减轻生成模型中的水印伪造 [PDF](https://arxiv.org/pdf/2507.07871), [HTML](https://arxiv.org/abs/2507.07871)
### Authors
Toluwani Aremu,Noor Hussein,Munachiso Nwadike,Samuele Poppi,Jie Zhang,Karthik Nandakumar,Neil Gong,Nils Lukas
### Background
水印技术使得AI内容生成提供商能够验证其模型生成的内容真实性。一个关键的安全威胁是伪造攻击，即攻击者将提供商的水印嵌入到并非其模型生成的内容中，导致损害提供商声誉并破坏信任。现有防御通过在相同内容中嵌入多个具有多个密钥的水印来抵抗伪造，但攻击者收集足够的水印样本时伪造仍然是个威胁。现有方法可能会降低模型的实用性。
### Innovation
提出了一种防御方法，该方法可证明独立于攻击者收集的水印样本数量，只要攻击者不能轻易区分不同密钥的水印。该方案不会进一步降低模型实用性。方法包括随机化每个查询的水印密钥选择，并仅当通过恰好一个密钥检测到水印时才接受内容为真实。该方法模态无关，因为它将底层水印方法视为黑盒。该方法能够证明限制攻击者的成功率，并且我们在实验中观察到成功率从近乎完全提升到只有2%，而几乎没有增加计算成本。
### Conclusion
通过随机化的密钥选择，证明该方法可以有效减轻伪造攻击带来的威胁，同时不对模型的实用性造成太大影响。该方法不仅适用于图像和文本模态，还可以泛化到其他模态，因为它是模态无关的。
## 115. `cs.LG` - 通过正交学习估计网络上的异质因果效应 [PDF](https://arxiv.org/pdf/2509.18484), [HTML](https://arxiv.org/abs/2509.18484)
### Authors
Yuanchen Wu,Yubai Yuan
### Background
在估计网络上的因果效应时,治疗不仅会影响受治疗的单位,还会影响他们的邻居。网络同质性会引发相关性和偏差,而当因果效应在单位和边缘上是异质时,这些挑战会进一步放大。
### Innovation
提出了一个两阶段正交学习框架，用于估计网络上的异质直接影响和溢出效应。第一阶段使用图神经网络估计细粒度的协变量和网络结构相关的噪声组件。第二阶段通过一个可解释的注意力干扰模型残差化这些噪声组件，以估计因果效应，提供了边缘级别的溢出估计，以及节点级和总体级的总结。Neyman正交化和交叉拟合降低对第一阶段估计误差的敏感性，从而使噪声错误在更高阶中出现。
### Conclusion
实验表明，该方法在异质效应估计上表现更好，同时支持具有解释性的下游分析，如重要邻居检测和溢出标记恢复。
## 116. `cs.LG` - Sl_sliding Windows _Infornative _Cannonical _CorreleAnalysis? [PDF](https://arxiv.org/pdf/2507.17921), [HTML](https://arxiv.org/abs/2507.17921)
### Authors
Arvind Prasadan
### Background
经典的相关分析（CCA) 用于研究两个数据集之间相关特征集之间的关系。相关特征集可能来自同一个数据集的不同部分度或者两个不同的数据集。在传统CCA中，数据的分析通常是离线的。然而,在很多实际应用场景中，数据可能会以流的形式出现并需要实时处理和分析
### Innovation
本文提出了针对在线数据集双流设置的新颖的CCA扩展：滑动窗口信息相关性分析（SWICa)。其方法利用了流式数据分析 (PCA) 硬算法 作为后端，并使用此算法的输出输出和一小步滑窗的样本组来实时估计CCA模型
### Conclusion
SWiccaA 方法适用于高维数据并并且具有很好的扩展性性 敂数模拟实验和理论上证明了方法的效果 我们还提供了一个实际数据例子来验证这种方法的能力
## 117. `cs.LG` - 弹性MoE：解锁Mixture-of-Experts在推理时间的可扩展性 [PDF](https://arxiv.org/pdf/2509.21892), [HTML](https://arxiv.org/abs/2509.21892)
### Authors
Naibin Gu,Zhenyu Zhang,Yuchen Feng,Yilong Chen,Peng Fu,Zheng Lin,Shuohuan Wang,Yu Sun,Hua Wu,Weiping Wang,Haifeng Wang
### Background
Mixture-of-Experts (MoE) 模型通常在训练和推理时固定激活专家的数量 $k$。然而，在实际部署中，会遇到多种硬件、波动的工作负载和不同的质量-延迟要求，为每种情况单独训练模型成本高昂。虽然 MoE 模型已经是稀疏激活的，通过调整推理时激活的专家数量可以自然地为不同预算提供单一模型的服务。但是，实验证明，增加激活的专家数量在推理时没有带来预期的性能提升，反而性能会在轻微增加后迅速下降，这一现象被称作‘推理时的扩展墙’。
### Innovation
本文引入了弹性Mixture-of-Experts (Elastic Mixture-of-Experts, EMoE)，该框架在训练时使专家可以在多种组合中协作，并鼓励路由器做出高质量的选择，以确保在不同推理预算下性能的稳定。实验结果表明，EMoE 可将有效的扩展范围扩大至训练时激活专家数量的2-3倍，同时还能实现更高的峰值性能。
### Conclusion
EMoE 通过同时训练专家与增强路由器的选择能力，在训练和推理时提供了更大的灵活性，从而显著提高了 MoE 模型在不同推理预算下的性能。
## 118. `cs.LG` - AU-Harness: 一个面向音频LLM全面评估的开源工具包 [PDF](https://arxiv.org/pdf/2509.08031), [HTML](https://arxiv.org/abs/2509.08031)
### Authors
Hoang Nguyen,Sidharth Surapaneni,Akshay Kalkunte,Jash Mehta,Aman Tiwari,Oluwanifemi Bamgbose,Khyati Mahajan,Jash Shah,Shruthan Radhakrishna,Sathwik Tejaswi Madhusudhan,Vikas Yadav,Sai Rajeswar
### Background
大型音频语言模型（LALMs）正在迅速发展，但现有的评估工具箱效率低下且标准化程度不足，这限制了公平比较和系统性评估。现有的评估框架存在三个关键问题：（1）慢且不高效的处理管道，阻碍了大规模研究；（2）缺乏多轮对话支持，无法解决LALMs在长期对话过程中跨轮次上下文整合和性能动态问题；（3）缺乏统一且可扩展的评估框架，无法跟上LALMs和音频基准数据集的快速增长。
### Innovation
我们引入了AU-Harness，这是一种高效的全面评估框架，能够实现相比现有工具箱最高151%的加速，通过优化批量处理和并行执行实现大规模评估。AU-Harness提供了标准化的提示协议和灵活的配置选项，以实现不同场景下的公平模型比较。它解锁了一系列以前难以开展的深入分析，包括多轮对话的动态，帮助研究LALMs的真实音频推理能力。AU-Harness不仅提供了实用的评估工具，还提供了有关模型限制的见解，促进了系统性LALM的发展。
### Conclusion
AU-Harness通过提供一种全功能、可扩展且高效的评估框架，大大提高了评估LALMs的速度和准确性，为深入研究LALMs提供了必要的评估工具和支持。
## 119. `cs.SE` - StartFlow: 从方法构思到UX原型设计中的多视角评估：针对软件初创企业的用户体验原型 [PDF](https://arxiv.org/pdf/2605.10824), [HTML](https://arxiv.org/abs/2605.10824)
### Authors
Guilherme Corredato Guerino,João Pedro de Souza Olivo Tardivo,Renato Balancieri,Gislaine Camila Lapasini Leal
### Background
软件初创公司在开发最小可行产品（MVP）时面临诸多挑战，尤其是在资源有限和用户体验专家稀缺的早期阶段。
### Innovation
引出了一种名为StartFlow的结构化方法，该方法运用了结合了线框图和用户流程的wireflow技术，帮助非专业人士快速构建MVP原型。StartFlow方法包含三个步骤：（i）功能组织；（ii）构建wireflow；（iii）基于可用性启发法验证并精炼。
### Conclusion
实验结果表明，使用StartFlow创建的原型更加清晰，专家们也能更好地遵循用户故事和业务规则，且具有更少的用性缺陷。该方法还在可操作性和未来的使用方面得到了良好的评价。研究表明了StartFlow作为支持软件初创企业产品开发早期阶段用户中心型开发工具的潜力。
## 120. `cs.SE` - Shepherd：一种赋能元代理的正式化执行轨迹的运行时基础设施 [PDF](https://arxiv.org/pdf/2605.10913), [HTML](https://arxiv.org/abs/2605.10913)
### Authors
Simon Yu,Derek Chong,Ananjan Nandi,Dilara Soylu,Jiuding Sun,Christopher D Manning,Weiyan Shi
### Background
该研究介绍了一种名为Shepherd的函数编程模型，该模型将目标代理的操作作为函数进行形式化，并且核心操作被机械化地实现在Lean中。Shepherd将每个代理-环境交互记录为Git-like执行跟踪中的带类型事件，使得任何过去的状态可以被分支并重放。
### Innovation
Shepherd模型具有多项创新点：首先，它能够在回放缓存保留率超过95%的情况下将代理过程及其文件系统比Docker快5倍进行分支。其次，该系统展示了通过三个应用的实现展示了模型的有效性：1. 实时干预中，现场监督使Pair Coding通过率从28.8%提高到54.7%；2. 假想元优化中，分支探索在四个基准中相对于基线提高了最高11点的性能并减少了墙钟时间最高58%；3. 在Tree-RL训练中，在选定转态时分支路径提高了TerminalBench-2性能从34.2%至39.4%。
### Conclusion
这些结果显示Shepherd是一种高效构建元代理的基础架构，并且已经开源以促进未来的研究。
## 121. `cs.SE` - ComplexMCP：在动态、相互依赖和大型工具沙盒中对LLM代理的评估 [PDF](https://arxiv.org/pdf/2605.10787), [HTML](https://arxiv.org/abs/2605.10787)
### Authors
Yuanyang Li,Xue Yang,Longyue Wang,Weihua Luo,Hongyang Chen
### Background
当前的大语言模型（LLM）代理在独立调用API方面表现出色，但在商业软件自动化方面的“最后一英里”问题上却表现出困难。在现实世界中，工具不是独立的，而是相互依赖的，容易受到环境噪音的影响。论文介绍了ComplexMCP基准，用于评估代理在这些严苛条件下的性能。基于Model Context Protocol (MCP)，ComplexMCP提供了300多个从7个状态沙盒中精心测试的工具，涵盖办公套件到金融系统等各种工具。
### Innovation
基于MCP构建，ComplexMCP用于评估LLM代理在动态、相互依赖和大型工具沙盒中的表现，使用种子驱动的架构模拟动态环境状态和不可预测的API故障，确保评价是确定而又多样的。评估表明，即使是顶尖模型，成功率也无法超过60%，远远落后于人类性能90%的水平。文章还详细分析了原因，找出了三个根本瓶颈，这些问题突显了当前代理在应对相互依赖的工作流时的不足。
### Conclusion
研究指出，当前的LLM代理不足以应对相互依赖的工作流，ComplexMCP被视为下一代弹性自主系统的重要测试平台。
## 122. `cs.SE` - LLM驱动的经济高效的需求变更影响分析 [PDF](https://arxiv.org/pdf/2511.00262), [HTML](https://arxiv.org/abs/2511.00262)
### Authors
Romina Etezadi,Sallam Abualhaija,Chetan Arora,Lionel Briand
### Background
软件开发生命周期中需求始终处于变化中，手工识别这些变化对其他需求的影响既容易出错又耗费大量精力，容易导致未被注意到的影响项，进而引发下游任务的严重问题。
### Innovation
提出了一种基于大语言模型（LLMs）的ProReFiCIA方法，用于自动识别需求变更对其他需求的影响。通过广泛评估使用多种LLM及其针对该任务的提示变体，ProReFiCIA在未见过的工业数据集上实现了85.7%的召回率，同时引入领域知识进一步提高了召回率至95.7%，成本仅占3.6%。
### Conclusion
ProReFiCIA展示了其在识别需求变更影响方面的有效性，且实施成本低，符合理想的经济高效性。
## 123. `cs.SE` - 在软件工程中涉及大型语言模型的实证研究指南 [PDF](https://arxiv.org/pdf/2508.15503), [HTML](https://arxiv.org/abs/2508.15503)
### Authors
Sebastian Baltes,Florian Angermeir,Chetan Arora,Marvin Muñoz Barón,Chunyang Chen,Lukas Böhme,Fabio Calefato,Neil Ernst,Davide Falessi,Brian Fitzgerald,Davide Fucci,Junda He,Christoph Treude,Marcos Kalinowski,Stefano Lambiase,Daniel Russo,Mircea Lungu,Cristina Martinez Montes,Lutz Prechelt,Paul Ralph,Rijnard van Tonder,Stefan Wagner
### Background
大型语言模型（LLMs）在软件工程（SE）研究和实践中应用广泛，但其非确定性、不透明的训练数据以及不断演化的模型威胁到了实证研究的可重现性和可复制性。
### Innovation
通过22位研究人员的合作，提出了组织大型语言模型在软件工程研究中应用的分类法和八条指南，以设计和报告此类研究。指南区分了必须执行的要求和应推荐的做法，并根据不同研究类型进行情境化。这些指南建议研究人员公开LLM的使用和角色、报告模型版本、配置和自定义、记录工具架构、披露提示及其开发和交互日志、验证LLM输出、使用开放的基础LLM、使用适当的基线、基准和度量标准，并阐明局限性和缓解措施。
### Conclusion
指南还包括一个适用性矩阵和作者及审稿人的报告检查表，作为社区使用和塑造的活资源提供在线支持（llm-guidelines.org）。
## 124. `cs.SE` - TestPrune: Old Tests Do New Trick for Res-solvinging SWE Issues? [PDF](https://arxiv.org/pdf/2510.18270), [HTML](https://arxiv.org/abs/2510.18270)
### Authors
Yang Chen,Toufique Ahmed,Reyhaneh Jabbarvand,Martin Hirzel
### Background
在实际项目中，的实际场景测试套件往往非常庞大并 幜呈和和代码覆盖高率很高， 但是在检测新错误时存在的错误方面仍然不足 蝼锇不足。不足不足。。不堪一击。。。. 项目管理中的开源项目跟踪器的数量不审说明下这个问题的严重性。 回归测试通常旨在确保过去的功能在新版本中 中保留完好，但实际上它们也可以起到补充作用: 用于调试当前版本。具体来说，回推测试可以增强重现新报告问题问题错误的测试生成，并 同时验证补丁确实没有引入现有功能的回退。但是，当前回归测试方法通常需要使的测试数量超出实际所需，并 细览 
### Innovation
为此团队设计TestPrune设计了一种完全自动化的技术， 其主要利用问题问题问题问题报告中缺陷和 工作基于此战略重新选用 囻测回归测试用 用于缺陷重现和 验证补丁验证。新的这种技术的贡献在于它能够自动最小化回归测试集 刻的回测到一个非常相关的小子子集。 当前基于大语言模型为主的调试技术的蓬勃发展 G c u使得此类最小化必不可少因为回测一旦超过适用范围可能会引入噪声并 游冲清的假设成本。 TestPrune可以无缝集成到任何调试修复工作流中，并 舍它可以从不同整个综合提高性能。的基础上来说， 
### Conclusion
作为概念的证明中 
