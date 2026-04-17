# 20260417
[![Subscribe_Visitors](https://visitor-badge.laobi.icu/badge?page_id=nituchao.latest_arxiv_analyze_ai_rss)](https://github.com/nituchao/latest_arxiv_analyze_ai)

## 1. `cs.AI` - 孤独聆听，共同理解：面向隐私保护的协作上下文恢复 [PDF](https://arxiv.org/pdf/2604.13348), [HTML](https://arxiv.org/abs/2604.13348)
### Authors
Tanmay Srivastava,Amartya Basu,Shubham Jain,Vaishnavi Ranganathan
### Background
随着代理从反应式助手演变成总是倾听的助手，它们面临着一个核心隐私风险：即捕捉到未同意录音的说话者，这使得它们的社会部署成为一个挑战。
### Innovation
CONCORD框架通过实时说话人验证强制实施只有所有者才能录音，产生了一侧的记录，保留了隐私但缺乏上下文。CONCORD通过空间-时间上下文解析、信息缺口检测以及基于关系的披露最小A2A查询，安全地恢复了必要的上下文，而不是依赖易产生幻觉的推理。
### Conclusion
CONCORD在多领域对话数据集上实现了91.4%的缺口检测召回率、96%的关系分类准确率和97%的隐私敏感披露决策真实负向率，将总是倾听的AI重新定义为隐私保护代理之间的协调问题，为实用可行的社会部署的主动会话代理提供了途径。
## 2. `cs.AI` - RiskWebWorld：电子商务风险管理中GUI代理的现实交互基准 [PDF](https://arxiv.org/pdf/2604.13531), [HTML](https://arxiv.org/abs/2604.13531)
### Authors
Renqi Chen,Zeyin Tao,Jianming Guo,Jing Wang,Zezhou Xu,Jingzhe Zhu,Qingqing Sun,Tianyi Zhang,Shuai Chen
### Background
现有的交互式基准测试主要针对简单的、可预测的消费者环境，而非高风险的调查领域如真伪电子商务风险管理。因此，这些测试在这些高风险领域的有效性尚未得到充分探索。RiskWebWorld填补了这一空白，它是一个高度真实的交互基准测试，用于评估电子商务风险管理工作中的GUI代理。
### Innovation
RiskWebWorld首次构建了一个高度真实的交互基准测试，包含1513项来自8个核心领域的实际风险控制任务，这些任务能捕捉到对抗性网站的挑战。此外，团队设计了一个符合Gymnasium标准的基础设施，将策略规划与环境机制分离，支持大规模评估和智能代理的强化学习。
### Conclusion
研究发现，顶级通用模型的成功率只有49.1%，而专门优化的开放权重GUI模型几乎完全失败，这表明在长期任务中，基础模型的规模比即时策略适应更为重要。通过智能代理的强化学习进行提升，开源模型的性能提高16.2%，这表明RiskWebWorld是一个实用的测试平台，用于开发稳健的数字工人。
## 3. `cs.AI` - 定量并理解大型推理模型中的不确定性 [PDF](https://arxiv.org/pdf/2604.13395), [HTML](https://arxiv.org/abs/2604.13395)
### Authors
Yangyi Li,Chenxu Zhao,Mengdi Huai
### Background
大型推理模型（LRMs）在复杂推理方面表现出显著的改进。尽管量化LRMs生成不确定性很重要，但传统方法往往因为无法提供推理答案生成的有限样本保证而不充分。可变形预测（CP）作为一种无需分布假设且模型无关的方法，能够构建统计严谨的不确定性集。然而，现有的CP方法忽略了推理路径与最终答案之间的逻辑联系，且先前研究未能解释LRMs不确定性覆盖的起源，因为它们通常忽略了驱动有效推理的具体训练因素。当量化不确定性时，区分推理质量和答案正确性具有挑战性，并且需要同时为计算高效的解释方法提供理论保证。
### Innovation
本文首先提出了一种新的方法，以统计保证的方式量化推理-答案结构中的不确定性。其次，开发了一个结合Shapley值的统一示例到步骤解释框架，识别了一个可证明足够的训练示例子集及其关键推理步骤，以保持这些保证。还提供了对所提方法的理论分析。在具有挑战性的推理数据集上的广泛实验验证了所提方法的有效性。
### Conclusion
该研究通过提供一个结合统计保证和计算高效性的方法，解决了量化和理解LRMs中不确定性的问题，为加速LRMs的广泛应用奠定了基础。
## 4. `cs.AI` - 在未知运行约束下的地球观测卫星调度优化：一种主动约束获取方法 [PDF](https://arxiv.org/pdf/2604.13283), [HTML](https://arxiv.org/abs/2604.13283)
### Authors
Mohamed-Bachir Belaid
### Background
地球观测（EO）卫星调度是组合优化领域中一个广泛研究的问题。现有的方法通常假设运行约束模型在操作开始前已经被完全确定。然而，在实际操作中，约束，如观测间隔、电力预算和温度限制等，往往嵌入在工程产品或高度精确的模拟器中而非数学模型中。
### Innovation
该研究在不确定约束的情况下探讨了EO调度问题。引入了一种名为保守约束获取（CCA）的具体领域方法，用于在学习约束过程中有效地识别必要约束，同时最小化模型过紧。该方法嵌入在Learn&Optimize框架中，支持交替使用学习到的约束模型进行优化和针对特定问题的询问，从而提高了效率。
### Conclusion
在合成实例中，与没有约束信息的贪婪基线相比，Learn&Optimize框架表现更好，并且在使用远少于两阶段获取-然后-解决基线的主询问次数下，学习到的约束模型取得了更好的优化效果。特别是在任务数较少的情况下，性能提升更为显著；而在任务数较多的情况下，虽然仍有一定的优化空间，但处理效率和节省的时间仍然得到了显著提升。
## 5. `cs.AI` - 通过多角色编排实现可扩展轻量级GUI代理 [PDF](https://arxiv.org/pdf/2604.13488), [HTML](https://arxiv.org/abs/2604.13488)
### Authors
Ziwei Wang,Junjie Zheng,Leyang Yang,Sheng Zhou,Xiaoxuan Tang,Zhouhua Fang,Zhiwei Liu,Dajun Chen,Yong Li,Jiajun Bu
### Background
基于多模态大型语言模型（MLLMs）的自主图形用户界面（GUI）代理能够实现对用户设备的数字化自动化。虽然在参数和数据上进行扩展带来了显著的改进，但先进的方法在资源受限的设备上仍然面临部署成本过高的问题。在面对复杂的真实场景时，轻量级的GUI代理因容量有限和任务扩展能力不足，在端到端的递归学习中成为瓶颈，这阻碍了其对多代理系统（MAS）的适应能力，而训练多项具体技能的专家依然成本高昂。
### Innovation
为了应对这些挑战，该研究提出了LAMO框架，赋予了轻量级MLLM特定的GUI知识和任务扩展能力，使其能够多角色编排来扩展其在GUI自动化中的能力边界。LAMO结合了面向角色的数据合成与两阶段训练方法：（i）监督微调及困惑度加权交叉熵优化的知识蒸馏和视觉感知增强，（ii）面向角色的合作探索中的强化学习。通过LAMO，开发了一种具有任务扩展能力的本机GUI代理LAMO-3B，支持单一执行和MAS风格的编排。通过与先进的规划者结合作为插拔式策略执行者，LAMO-3B可以持续受益于规划器的改进，从而提高性能上限。
### Conclusion
通过LAMO框架，有效地解决了轻量级GUI代理的成本扩展性困境，赋予其在真实GUI工作流程中的实用能力。广泛静态和在线评估证明了该设计的有效性。
## 6. `cs.AI` - SciFi: A Safe, Lightweight? and? User-Ffriendly? and? and Fully Autonomous Agentic AI Workflow for Scientific Analyses? [PDF](https://arxiv.org/pdf/2604.13180), [HTML](https://arxiv.org/abs/2604.13180)
### Authors
Qibin Liu,Julia Gonski
### Background
当前， AI 巈AI以自动化的工作流方面取得了显著进展，这些系统能够实现愈加的科学任务执行。然而但在实际科学研究中,这些系统的可靠部署仍然面临着诸多挑战。
### Innovation
本文介绍提出一种安全、轻轻轻轻轻轻轻“轻日轻型?且?用户友好?的自动化科学任务的微体系结构 SciFi?。它集整合了一个隔离执行执行环境、、?三层?代理循环??和以及?一种评估 刁?直至?机制?来确保操作安全并尽管成本效率高同时也能够充分发挥不同能力水平的大型语言模型的优势。此外,该框架专注于具有明确定义的上下文和结束标准??从而使得从头到端自动化成为可能,减少了人工干预需要??使其能够为主研究人员任务的常规劳动和其他更多创意??开放性的科学探索提供支持。?u
### Conclusion
综上?本文提出了一种可能够实现自动化?安全保证操作安全的?骨架结构SciFi??它为科学分析中的自动化工作流提供了一种解决方案??在这种框架下下?用户可以将更多的常规工作卸载并且将更多精力集中在创意的科学探索上?
## 7. `cs.AI` - Memp：探索智能体程序记忆 [PDF](https://arxiv.org/pdf/2508.06433), [HTML](https://arxiv.org/abs/2508.06433)
### Authors
Runnan Fang,Yuan Liang,Xiaobin Wang,Jialong Wu,Shuofei Qiao,Pengjun Xie,Fei Huang,Huajun Chen,Ningyu Zhang
### Background
大型语言模型（LLMs）在处理各种任务方面表现出色，但在程序记忆方面存在瓶颈，这部分记忆通常是手动工程化或静态参数中嵌入的，这使得它们难以适应新的环境和任务变化。
### Innovation
该研究探讨了如何赋予智能体可学习、可更新、终身的程序记忆。为此，作者提出了Memp，这是一种将智能体过去的轨迹转化为精细步骤指令和高层次脚本式抽象的方法，并探讨了不同的构建、检索和更新程序记忆的策略。此外，还提出了一种动态机制来持续更新、纠正和废弃程序记忆的内容。
### Conclusion
通过实证评估，随着程序记忆库的完善，智能体在类似任务上的成功率和效率不断提高。更重要的是，从较强模型中构建的程序记忆在较弱模型中也能带来显著的性能提升。
## 8. `cs.AI` - 左右为难：大语言模型中的道德推理与安全性对齐张力 [PDF](https://arxiv.org/pdf/2509.05367), [HTML](https://arxiv.org/abs/2509.05367)
### Authors
Shei Pern Chua,Zhen Leng Thai,Kai Jun Teh,Xiao Li,Qibing Ren,Xiaolin Hu
### Background
现有的大语言模型安全管理主要基于二元假设，即请求要么安全要么不安全。但在模型遇到伦理困境时，这套分类方法显得不足。伦理推理为模型带来了一种新的攻击面，模型有机会通过道德权衡来合理化有害行为。
### Innovation
提出了TRIAL（多轮红队测试方法）来形式化伦理推理的漏洞，并引入ERR（道德推理稳健性）框架来区分促进有害结果的工具性回应和不支持有害行为的解释性回应。ERR利用分层有害行为门控的LoRA架构，实现了应对基于推理的攻击的同时保持模型的实用性。
### Conclusion
该研究通过TRIAL和ERR方法，揭示了大语言模型在伦理推理与安全性对齐间的张力，并提出了针对性的防御机制，确保模型在伦理推理过程中仍能保持安全性。
## 9. `cs.AI` - 通过自动构建环境实现大型语言模型工具使用反馈驱动改进 [PDF](https://arxiv.org/pdf/2508.08791), [HTML](https://arxiv.org/abs/2508.08791)
### Authors
Junjie Ye,Changhao Jiang,Zhengyin Du,Yufei Xu,Xuesong Yao,Zhiheng Xi,Xiaoran Fan,Qi Zhang,Tao Gui,Xuanjing Huang,Jiecao Chen
### Background
大型语言模型（LLMs）的有效工具使用对于其与环境的互动至关重要。然而，由于缺乏专门设计的高效强化学习（RL）框架来处理工具使用的情况，进展受到限制。这是因为很难构建稳定的训练环境，并设计可验证的奖励机制。
### Innovation
本文提出了一种自动环境构建管道，包括场景分解、文档生成、功能集成、复杂性扩展和局部部署，从而创建高质量的训练环境，这些环境能提供详细且可测量的反馈，并且不依赖外部工具。此外，还引入了一种可验证的奖励机制，用于评估工具使用的精确度和任务执行的完整性。结合从构建的环境中收集的轨迹数据，这一机制可以直接与标准的强化学习算法结合，实现基于反馈的模型训练。实验表明，无论模型规模如何，这种方法都能显著提升工具使用表现，而不损害其通用能力。
### Conclusion
我们的分析显示，这些改进来源于对上下文理解以及推理能力的提高，这种提升是由模型底层MLP参数的更新带来的。我们提供了代码和数据可以在该链接访问：this https URL
## 10. `cs.AI` - 重尾类条件先验用于长尾生成建模 [PDF](https://arxiv.org/pdf/2509.02154), [HTML](https://arxiv.org/abs/2509.02154)
### Authors
Aymene Mohammed Bouayed,Samuel Deslauriers-Gauthier,Adrian Iaccovelli,David Naccache
### Background
在使用全球先验值训练具有不平衡经验分类分布的变分自编码器（VAEs）时，尾部类可能会在潜在空间中被低估。虽然$t^3$VAE通过重尾的学生$t$分布先验改进了鲁棒性，但其单一全球先验仍然按类频率占比分配概率质量。论文指出这一潜在空间中的几何偏见问题。
### Innovation
提出了一种C-$t^3$VAE，它为潜在和输出变量分配了基于类的学生$t$联合先验，这在类条件组件中均衡了先验概率质量。通过从γ-幂发散中推导闭合形式目标并引入均等权重的潜在混合方式来优化模型，以实现类平衡生成。在SVHN-LT，CIFAR100-LT和CelebA数据集上，C-$t^3$VAE在严重类不平衡时整体得到更低的FID得分，而在平衡或轻度不平衡的情况下，其表现也具有竞争力。此外，在类别的F1评估中，C-$t^3$VAE在高度不平衡的情况下优于条件高斯VAE。
### Conclusion
研究发现对于轻微不平衡，$rho < 5$时高斯基模型仍具有竞争力，但在$rho ?>= 5$时，该方法提高了类平衡生成和模式覆盖能力。
## 11. `cs.AI` - 神经符号AI在网络安全中的现状、挑战与机遇 [PDF](https://arxiv.org/pdf/2509.06921), [HTML](https://arxiv.org/abs/2509.06921)
### Authors
Safayat Bin Hakim,Muhammad Adil,Alvaro Velasquez,Shouhuai Xu,Houbing Herbert Song
### Background
网络安全既需要快速的模式识别，也需要深入的推理分析，但纯粹的神经网络或纯粹的符号逻辑方法仅能解决这一问题的一方面。神经符号（NeSy）AI通过在统一框架中整合学习和逻辑，弥合了神经网络和符号逻辑之间的这一差距。本文通过对截至2026年4月的103篇关于神经符号集成的网络安全相关文献进行系统性综述，组织这些文献通过包含深度集成、结构化互动和上下文基线的三层分类系统，以及基于锚定、指令能力和对齐的分析框架，发现了多代理和结构化集成架构在复杂场景中的表现优于单一代理的方法。此外，因果推理能超越基于相关性的检测，实现主动防御，而知识引导的学习有助于提升数据效率和解释性。这些发现覆盖了入侵检测、恶意软件分析、漏洞发现和自主渗透测试等多个领域，证明了集成深度与各类领域的性能提升之间存在关联。
### Innovation
本文提出了一种神经符号AI在网络安全中的研究方法和框架，系统综述了103篇相关文献，通过多层次分类和分析框架来探讨神经符号集成在网络安全中的应用。研究发现复杂的场景下，集成多代理和结构化交互架构的效果优于单一代理的方法。因果推理超越简单相关性检测，有助于提前防御。知识引导的学习提高了数据使用效率和解释性。研究还揭示了自主进攻系统在减少成本的情况下已经取得显著的零日漏洞利用成功，这将重新塑造安全威胁图景。
### Conclusion
尽管取得了这些进展，但神经符号AI在网络安全领域的应用仍面临评价标准不规范、计算成本限制部署、以及有效的人工智能合作不足等挑战。本文建议一个优先研究路线图，强调社区驱动的基准测试、负责任的发展实践和防御对齐，以指导下一代神经符号网络安全系统的开发。
## 12. `cs.CL` - 扩散语言模型在语音识别中的应用 [PDF](https://arxiv.org/pdf/2604.14001), [HTML](https://arxiv.org/abs/2604.14001)
### Authors
Davyd Naveriani,Albert Zeyer,Ralf Schlüter,Hermann Ney
### Background
扩散语言模型由于其双向注意和并行文本生成的能力，最近成为了标准语言模型的领先替代方案。
### Innovation
本文探索了扩散语言模型在语音识别中的应用。文章引入了掩码扩散语言模型（MDLM）和均匀状态扩散模型（USDM）的全面指南，并设计了一种新的联合解码方法，将CTC和USDM结合在一起，通过在解码的每一步将CTC框架概率分布与USDM计算的标签概率分布结合，生成新的候选词，从而结合USDM中的强大语言知识和CTC中的声学信息。
### Conclusion
研究表明USDM和MDLM显著提高了识别文本的准确性。所有代码和配方均已发布。
## 13. `cs.CL` - 从何而来：通过源归因对代码分词器进行有效的正则化 [PDF](https://arxiv.org/pdf/2604.14053), [HTML](https://arxiv.org/abs/2604.14053)
### Authors
Pavel Chizhov,Egor Bogomolov,Ivan P. Yamshchikov
### Background
大型语言模型（LLMs）的效率和安全性很大程度上取决于分词的质量。优质的分词不仅能够提升推理速度和语言理解能力，还能提供额外的防御手段，对抗模型逃逸攻击，并减少幻觉的风险。现有的代码分词器由于训练数据来源于单一的代码库和语言，且存在重复的、特定源的语言材料，导致分词效率低下，产生过多的未使用和欠训练的分词单位。本文着重研究代码分词的效率，特别是在数据源多样性的视角下，揭示了训练数据中的不平衡问题。
### Innovation
本文提出了一种新型的分词技术，Source-Attributed BPE（SA-BPE），通过修改BPE的目标函数并引入合并跳过技术，来正则化BPE训练过程，从而减少过拟合现象，显著降低了未使用和欠训练的分词单位数量，同时保持与标准BPE相同的推理流程。这种技术为生产环境中的使用提供了有效的工具。
### Conclusion
本文通过改进代码分词过程，提出了一种新的分词方法SA-BPE，有效地减少了未使用和欠训练的分词单位，同时保持了高效和准确的推理过程，这是一种适用于实际部署的有效工具。
## 14. `cs.CL` - 跨体裁、模型和解码策略下人类与LLM写作的可解释性风格变异 [PDF](https://arxiv.org/pdf/2604.14111), [HTML](https://arxiv.org/abs/2604.14111)
### Authors
Swati Rallapalli,Shannon Gallagher,Ronald Yurko,Tyler Brooks,Chuck Loughin,Michele Sezgin,Violet Turri
### Background
大型语言模型（LLMs）现在能够生成高度流畅、类似人类的文本。它们为多种应用提供了可能，但也引发了大规模垃圾邮件、网络欺诈或学术不当使用等担忧。虽然很多工作集中在检测LLM生成的文本上，但很少有工作致力于理解人类撰写的文本和机器生成的文本在风格上的差异。本研究通过分析11种不同体裁和4种解码策略的大规模人类书面文本和LLM输出，探讨了这些风格差异，特别是使用Douglas Biber的词法和功能特征集。
### Innovation
研究通过大规模分析不同体裁和解码策略下的机器生成文本和人类撰写的文本，揭示了风格变异的洞察，这对于指导有意图的LLM使用具有指导意义。研究发现，语言差异性是高度一致的，体裁对风格特征的影响大于其来源，聊天模型倾向于集群，模型对风格的影响大于解码策略，尽管有一些例外。这些结果突显了模型和体裁在塑造机器生成文本的风格行为方面的相对重要性，而不是提示和解码策略。
### Conclusion
研究发现了人类撰写和机器生成文本在风格差异上的重要发现，这些发现有助于理解LLM的风格行为。研究强调了在指导有意图的LLM使用时模型和体裁的重要性，而不是提示和解码策略。
## 15. `cs.CL` - 正确预测，错误步骤？基于共识推理知识图谱的稳健链式思维合成 [PDF](https://arxiv.org/pdf/2604.14121), [HTML](https://arxiv.org/abs/2604.14121)
### Authors
Zipeng Ling,Shuliang Liu,Shenghong Fu,Yuehao Tang,Seonil Son,Yao Wan,Xuming Hu
### Background
LLM推理痕迹存在复杂缺陷——内部步骤缺陷（如逻辑错误、幻觉等）和逐步缺陷（如过度思考、不足思考），这些缺陷在样本之间有所不同。自然的应对策略是提供地面真值标签来引导LLM的推理过程。然而，该研究通过实验证明这种方法并不能提升推理能力。
### Innovation
提出了CRAFT（Consensus Reasoning Knowledge Graph）统一框架，该框架通过构建基于多个候选痕迹共识部分的推理知识图谱（RKG），并采用拓扑生成方法合成高质量的推理痕迹，从而减少两种步骤缺陷。该方法在逻辑推理和数学推理基准测试中比所有基线方法表现更佳，平均提高了标签预测准确性10%以上。
### Conclusion
详细基准测试表明，我们的方法不仅提高了LLM推理痕迹的质量，还在多个维度上提升了推理痕迹的质量。
## 16. `cs.CL` - 一种用于多模式数据收集的领域特定语言 [PDF](https://arxiv.org/pdf/2604.13046), [HTML](https://arxiv.org/abs/2604.13046)
### Authors
Philipp Reis,Philipp Rigoll,Martin Zehetner,Jacqueline Henle,Stefan Otten,Eric Sax
### Background
现有的数据驱动系统依赖于任务相关数据，但数据收集管道仍然被动且不分青红皂白。持续记录多模态传感器流会导致高昂的存储成本并捕获无关数据。
### Innovation
本文提出了一种声明性框架，旨在根据高级用户请求基于意图驱动、在设备端进行有选择的数据收集。该框架结合了自然语言交互和形式化规定的领域特定语言（DSL）。大型语言模型将用户定义的要求翻译成可验证和可组合的DSL程序，以跨异构传感器定义条件触发器，包括摄像头、LiDAR和系统遥测。实证评估表明，基于DSL的方法在不牺牲检测性能的情况下，实现了更高的生成一致性和更低的执行延迟，同时支持模块化触发器组成和在资源受限的边缘平台上并发部署。
### Conclusion
该方法将被动记录替换为实时系统中可验证的、基于意图的数据收集机制。
## 17. `cs.CL` - 形式无功能：Moltbook 网络中的代理社交行为 [PDF](https://arxiv.org/pdf/2604.13052), [HTML](https://arxiv.org/abs/2604.13052)
### Authors
Saber Zerhoudi,Kanishka Ghosh Dastidar,Felix Klement,Artur Romazanov,Andreas Einwiller,Dang H. Dang,Michael Dinzinger,Michael Granitzer,Annette Hautli-Janisz,Stefan Katzenbeisser,Florian Lemmerich,Jelena Mitrovic
### Background
该研究基于对Moltbook社交网络的分析，这是一个每个参与者都是AI代理的社交平台。研究者收集了从2026年1月27日至3月9日共计40天的数据，包括1,312,238条帖子，6.7百万条评论和超过12万个代理个人资料，涉及5,400个社区。研究者通过三个层面评估了该平台：互动层、内容层和技术指导层。数据显示该平台上存在高比例的单向互动、链接几乎与个人Bio不符的帖子以及对内容高倾向自我复制等现象。
### Innovation
研究创新性地提出了一种基于AI代理的社交网络分析方法，并通过多层次的分析揭示了该平台在技术层面上的迅速响应性与社会层面上的不足。特别是在评估层面方面，研究引入了从互动层的低互动性、内容层的内容偏离程度和技术指导层的指令变化等多个维度进行综合评价。
### Conclusion
Moltbook是一个技术层面上表现出迅速响应性的社会网络，但在社会层面上表现出了严重的不足，即缺乏真正意义上的用户互动与社区功能，这种平台仅仅是复制了社交媒体的形式而缺少实质内容与功能。
## 18. `cs.CL` - 论 咅言 咕 问 咜 儮 咮 壜 墥 姌 喞 垫 劶 垝 妷 劶 介 傫 偫 儣 娩 偐 媫 奦 娑 奏 媩 妧 媢 岫 倣 嫥 垖 嵨 垨 嵐 嵱 廢 嵡 娠 哑 儊 儌 咋 剼 娾 婥 坍 [PDF](https://arxiv.org/pdf/2604.14128), [HTML](https://arxiv.org/abs/2604.14128)
### Authors
Louie Hong Yao,Vishesh Anand,Yuan Zhuang,Tianyu Jiang
### Background
当前关于大型语言模型（LLM) 如何处理修辞性问 类句子的理解仍然不足，并 嗮 儇 嫱 儥 哘 咫 姩 嵎 敛建 睼，在本研究通过对比两组社交媒体数据集上 咫 垐 嘪 垸 的 对话背景，， 姨 憣 催 堯 塕 塌 婤 塗 哘 哘 哘 垶 垢 垶 垰 垠 垑 垊 垏 和
### Innovation
本研究创新地开发了一套针对修辞疑问句的探针作为工具进行分析。 坼 嗏 婤 儫 嘠 噶 媫 婃 噶 塰 塰 墨 媠 嚫 姨
### Conclusion
研究发现，ín
## 19. `cs.CL` - TREX: 通过代理驱动的树形探索实现LLM微调自动化 [PDF](https://arxiv.org/pdf/2604.14116), [HTML](https://arxiv.org/abs/2604.14116)
### Authors
Zerun Ma,Guoqiang Wang,Xinchen Xie,Yicheng Chen,He Du,Bowen Li,Yanan Sun,Wenran Liu,Kai Chen,Yining Li
### Background
大型语言模型（LLMs）虽然能够在AI研究中执行孤立的科学任务，但自动化复杂的实时工作流程，如LLM训练，仍然是一个重要挑战。
### Innovation
提出了TREX，这是一种多代理系统，能够自动化整个LLM训练生命周期。通过协调研究人员和执行器两个核心模块之间的协作，该系统可以无缝地进行需求分析、开放域文献和数据研究、训练策略的制定、数据食谱的准备以及模型训练和评估。
### Conclusion
通过将多轮实验过程建模为搜索树，TREX能够高效规划探索路径，重复利用历史结果，并从迭代试验中提炼出高层次的洞察。通过构建FT-Bench基准测试，包含10项来自实际场景的任务，结果表明TREX代理能够一致地优化目标任务的模型性能。
## 20. `cs.CL` - 从$P(y|x)$到$P(y)$：探究预训练空间中的强化学习 [PDF](https://arxiv.org/pdf/2604.14142), [HTML](https://arxiv.org/abs/2604.14142)
### Authors
Yuqiao Tan,Minzheng Wang,Bo Liu,Zichen Liu,Tian Liang,Shizhu He,Jun Zhao,Kang Liu
### Background
通过验证奖励的强化学习（RLVR）显著增强了LLM的推理能力，通过优化条件概率分布$P(y|x)$。然而，其潜力受到基础模型现有输出分布的限制。优化预训练空间中的边缘概率分布$P(y)$解决了这一瓶颈，通过编码推理能力和保持广泛探索能力来解决。但传统预训练依赖于静态语料库进行被动学习，导致分布偏移，影响有针对性的推理增强。
### Innovation
本文提出了PreRL（预训练空间中的RL），直接对$P(y)$进行奖励驱动的在线更新。我们验证了$P(y)$和$P(y|x)$之间的强梯度对齐，将PreRL确立为标准RL的有效替代品。此外，我们发现了一个关键机制：PreRL中的负样本强化（NSR）作为推理的强大推动力。NSR-PreRL迅速修剪了错误的推理空间，同时激发了内生的反思行为，分别增加了过渡和反思思考次数14.89倍和6.54倍。在此基础上，提出了双重空间RL（DSRL），一种策略，通过结合NSR-PreRL初始化模型来扩展推理范围，然后过渡到标准RL进行精细优化。大量实验表明，DSRL在所有基准上表现更优，证明了预训练空间修剪有效地引导策略向精炼的正确推理子空间。
### Conclusion
通过DSRL，在预训练空间中进行的有效修剪策略，能够在未经详细调整的情况下引导策略向正确的推理方向，最终在性能上表现出色。
## 21. `cs.CL` - Cracking the Code of Juxtaposition: Can AI Models Understand the Humorous Contradictions [PDF](https://arxiv.org/pdf/2405.19088), [HTML](https://arxiv.org/abs/2405.19088)
### Authors
Zhe Hu,Tuo Liang,Jing Li,Yiren Lu,Yunlai Zhou,Yiran Qiao,Jing Ma,Yu Yin
### Background
近年来，大型多模态语言模型在多种任务上表现出非凡的能力，但在理解人类幽默中的对比手法方面仍存在困难，尤其是对于非线性的叙事结构，这种结构构成了许多笑话的基础。本文通过专注于具有矛盾叙事的漫画来探讨这一挑战，每幅漫画包含两幅图像，形成幽默的矛盾。文章旨在评估AI识别和解释这些漫画的能力。
### Innovation
本文引入了名为YesBut的基准数据集，该数据集包含不同难度的任务，用于测试AI在识别和解释这些漫画方面的表现，从简单的文字理解到复杂的叙事推理。通过广泛实验和分析，并评估了最近的商业或开源大型（视觉）语言模型对这些漫画中固有的叙事幽默的理解能力。
### Conclusion
实验结果表明，即使是最先进的模型在这一任务上的表现仍落后于人类。本文的结果为理解当前AI在理解人类创造性表达方面的局限性提供了见解，并提出了可能的改进方向。
## 22. `cs.CL` - 连接组合语义与分布语义：基于自编码器的潜在语义几何概览 [PDF](https://arxiv.org/pdf/2506.20083), [HTML](https://arxiv.org/abs/2506.20083)
### Authors
Yingji Zhang,Danilo S. Carvalho,André Freitas
### Background
当前基于Transformer的自回归语言模型显示出增强的解释性、可控性、组合性和泛化能力，但这些模型可以通过整合组成性和符号性语义来进一步改进。背景部分介绍了现有语义空间的局限性以及将组成性和符号性语义融入现有分布语义空间的重要性。
### Innovation
本文从潜在空间几何的角度重新审视了语义表示学习的方向，特别关注组合语义。通过比较使用VAE、VQVAE和SAE的主流自编码器架构，讨论了它们如何分别影响语义结构和可解释性，从而建立了符号性语义和分布性语义之间的桥梁。
### Conclusion
本文总结了潜在语义几何在增强语言模型的语义理解和控制方面的潜力，并提出了未来研究的方向，包括进一步研究这些自编码器架构如何影响模型的解释性和泛化能力。
## 23. `cs.CV` - 任何对象流：任何来源的快速国家级别农场边界检测 [PDF](https://arxiv.org/pdf/2511.13417), [HTML](https://arxiv.org/abs/2511.13417)
### Authors
Mykola Lavreniuk,Nataliia Kussul,Andrii Shelestov,Yevhenii Salii,Volodymyr Kuzin,Sergii Skakun,Zoltan Szantoi
### Background
准确从卫星图像划定农业领域边界对于土地管理和作物监测至关重要，但现有方法往往产生不完整的边界、合并相邻田块，并难以扩展。现有方法难以在大规模应用中高效地处理农田边界划定。作者提出了一种名为Delineate Anything Flow (DelAnyFlow) 的方法，这是一种与分辨率无关的大规模农田边界映射方法，能够生成矢量边界，改善边界完整性。
### Innovation
DelAnyFlow 结合了基于 YOLOv11 的 DelAny 实例分割模型，并使用 FBIS 22M 数据集进行训练，后者包含 672,909 个多分辨率图像贴片 (0.25-10m) 和 22.9 百万验证过的田块实例。通过结构化的后处理、聚合、矢量化和简化步骤，DelAnyFlow 生成了准确度高、速度快的矢量边界。DelAnyFlow 在乌克兰生成完整田块边界图层的速度比 Sinergise Solutions 和 NASA Harvest 的操作产品快得多。
### Conclusion
DelAnyFlow 提供了一种可扩展、成本效益高的机械化边界划分方法，特别适用于没有数字地籍数据的地区。该项目的网页链接提供了模型权重、代码、国家规模矢量输出和数据集的访问链接。
## 24. `cs.CV` - UniGeoSeg：为地理空间场景统一开放世界分割方法 [PDF](https://arxiv.org/pdf/2511.23332), [HTML](https://arxiv.org/abs/2511.23332)
### Authors
Shuo Ni,Di Wang,He Chen,Haonan Guo,Ning Zhang,Jing Zhang
### Background
遥感领域的指示驱动分割可以从指导中生成掩码，但现有方法面临任务表述碎片化和指导数据有限的问题，这限制了有效理解和推广。为此，作者提出了GeoSeg-1M，这是第一个百万级规模的遥感指示驱动分割数据集，通过自动掩码过滤和指令生成管道构建而成，能够合成引用、交互和推理分割指令。GeoSeg-1M 包含59万张图像、117个类别和110万个图像-掩码-指令三元组。在此基础上，作者进一步构建了GeoSeg-Bench，一个具有挑战性的基准，旨在评估不同指示驱动任务和复杂地学空间场景下的上下文理解和推理能力。
### Innovation
作者通过自动掩码过滤和指令生成管道构建了GeoSeg-1M数据集，这是首个百万级规模的遥感指示驱动分割数据集。此外，作者提出了UniGeoSeg框架，该框架结合任务感知文本增强、隐含知识记忆和渐进式训练策略，促进了多任务学习。此外，通过广泛的实验，UniGeoSeg在GeoSeg-Bench和多个公开基准上的性能处于领先地位，展示了强大的零样本泛化能力。
### Conclusion
通过GeoSeg-1M和UniGeoSeg框架的研究，作者为遥感指示驱动分割提出了一种新的方法，并通过实验证明了其在开放世界场景下实现良好性能和泛化能力。研究结果均发布于指定的网址。
## 25. `cs.CV` - GeoBridge: 一种结合图像和文本进行地理定位的基于语义锚点的多视图基础模型 [PDF](https://arxiv.org/pdf/2512.02697), [HTML](https://arxiv.org/abs/2512.02697)
### Authors
Zixuan Song,Jing Zhang,Di Wang,Zidie Zhou,Wenbin Liu,Haonan Guo,En Wang,Bo Du
### Background
传统的基于卫星的地理定位方法通过检索与查询图像视觉上对应的带有地理标注的参考图像来进行位置推断。然而，当高分辨率或最新的卫星图像不可用时，这种方法的鲁棒性会受到限制。此外，这种方法未能充分探索跨视图（例如，无人机、卫星和街道）和模态（例如，语言和图像）的互补线索。
### Innovation
提出了一种名为GeoBridge的新型模型，该模型可以在多种视图之间进行双向匹配，并支持语言到图像检索。这种方法基于一种新颖的语义锚点机制，通过文本描述将多视图特征进行跨视图连接，从而实现鲁棒且灵活的定位。为此，构建了一个名为GeoLoc的大规模跨模态和多视图对齐数据集，包含5万多个来自36个国家的带有语义对齐的无人机、街道全景图和卫星图像对。
### Conclusion
广泛的实验表明，使用GeoLoc预训练可以显著提高GeoBridge的位置准确度，同时促进跨域泛化和跨模态知识的转移。源代码、数据集和预训练模型将在此链接（将此链接翻译为中文）发布。
## 26. `cs.CV` - 统一框架下的空域视觉语言导航以实现空间、时间和体态推理 [PDF](https://arxiv.org/pdf/2512.08639), [HTML](https://arxiv.org/abs/2512.08639)
### Authors
Huilin Xu,Zhuoyang Liu,Yixiang Luomei,Feng Xu
### Background
空域视觉语言导航（Aerial Vision-and-Language Navigation，Aerial VLN）旨在使无人驾驶航空器（UAV）能够理解自然语言指令，并利用机载视觉观察在复杂的城市环境中进行导航。现有的方法通常依赖全景图像、深度输入或里程计来支持空间推理和行动规划。这些需求增加了系统的成本和集成复杂性，从而阻碍了轻量化UAV的实际部署。
### Innovation
该研究提出了一种统一的空域VLN框架，该框架仅依赖于第一人称单目RGB观察和自然语言指令运作。该模型将导航任务表述为下一个标记预测问题，通过提示引导的多任务学习优化空间感知、轨迹推理和行动预测。另外，该方法还提出了一种关键帧选择策略来减少视觉冗余，并且包含一种动作合并和标签重加权机制，以缓解监督不平衡问题并促进稳定的多任务协同训练。
### Conclusion
在AerialVLN和OpenFly基准上的广泛实验验证了该方法的有效性。在仅使用单目RGB的挑战性设置下，该模型在已见和未见环境中均取得了出色的结果。与现有的单目RGB基线相比，该模型表现显著优越，并且在与全景RGB-D最先进的方法进行对比时缩小了性能差距。综合消融研究进一步证实了任务设计和架构选择的贡献。代码已公开可在该链接：this https URL
## 27. `cs.CV` - 通过门控感知推理优化在大型视觉-语言模型中解决过度思考问题 [PDF](https://arxiv.org/pdf/2601.04442), [HTML](https://arxiv.org/abs/2601.04442)
### Authors
Xingjian Diao,Zheyuan Liu,Chunhui Zhang,Weiyi Wu,Keyi Kong,Lin Shi,Kaize Ding,Soroush Vosoughi,Jiang Gui
### Background
大型视觉-语言模型（LVLMs）展示了通过生成逐步推理过程的链式思考机制来行使强大的推理能力。然而，这种慢速思考方法经常导致过度思考，即模型即使对于简单的查询也会生成过多冗长的响应，导致测试时间效率低下甚至降低了准确性。先前研究试图通过适应性推理策略来缓解这一问题，但这些方法大多忽视了一个根本瓶颈：视觉感知失败。文章认为，稳定推理的关键在于低层次的视觉定位，推理错误通常起源于不完美的感知，而不是缺乏深思熟虑。
### Innovation
本文提出了门控感知推理优化（GPRO）这一元推理控制器，该控制器在每个生成步骤中动态路由计算到三个决策路径：一个轻量级的快速路径、一个慢速感知路径用于重新审视视觉输入和一个慢速推理路径用于内部自我反思。这种区分通过从大约79万个样本中推导出大规模失败归因监督并使用教师模型区分感知幻觉与推理错误来学习。然后采用多目标强化学习训练控制器，在不确定性条件下优化任务准确性和计算成本之间的权衡。
### Conclusion
在五个基准上的实验表明，GPRO在提高准确性和效率方面显著优于近期的慢速思考方法，同时生成的响应显著更短。
## 28. `cs.LG` - Bridging MARL to SARL: An Independent Multi-Agent Transformer via Latent Consensus [PDF](https://arxiv.org/pdf/2604.13472), [HTML](https://arxiv.org/abs/2604.13472)
### Authors
Zijian Zhao,Jing Gao,Sen Li
### Background
合作多媒体代理强化学习（MARL) 幆常用来解决大型联合观察测和on和动作空间，通过将中央化控制问题分解为多个相互互作用的代理来处理。然而这种这样解决分解往往也带来了额外的挑战，在基础包括包括非时站稳定性训练困难、弱代理间活动协调和有限的理论保证.基于这些考虑,本研究提出了一种 基层数中心框架的统一的代理变压器 (CMAT) 的方法.CMAT视角将所有代理作为统一实体处理并使用一个变换器编码器来处理大规模联合观察空间问题特征的变换器解码器引入分级决策机制 强行级生成高层次一致向量 模拟代理之间达成一致的过程 在共识引导下代理同时生成行动 从而避免了传统多媒体变换器 (MAT) 中对联合行动生成的敏感性 这个方法允许通过单代理PPO优化组合策略并整个隐藏的共识中保持协商一致的表现
### Innovation
CMAT通过输入一种新颖的方法来解决了传统MARL面临的挑战.首先它新颖地将所有代理视为一个整体来处理联合观察空间 通过变换器器编码器在变换器解码分级决策过程中引入引入生成层次同意解矢量 从而模拟代理之间的共识达成过程 在这个向机制引导代理们同时生有行动 此机制避免了传统MAT对联合行动生成的依赖性 运用过程中所有的策略优化是利用单代理PPO进行优化 但依然保持了在隐藏共识化下的协商协调能力
### Conclusion
我们在StarCraft II、多合体小MuJoOn和和erl足球等研究中执行了这个方法的实验.结果显示CMAT在最近的中央化和序时学方法中实现了优越的表现 幄재相比于传统的MDMAR执行方具备更独立的区间决策能力 这项研究保持了在隐含一致指导下的协作协调能力 通过CMAT在多个多任务上的显著表现所验证了所称之创新方法的有效性
## 29. `cs.LG` - Chain of Uncertain Rewards with Large Language Models for Reinforcement Learning [PDF](https://arxiv.org/pdf/2604.13504), [HTML](https://arxiv.org/abs/2604.13504)
### Authors
Shentong Mo
### Background
设计有效的奖励函数是强化学习（RL）的基础，但传统方法由于缺乏效率和一致性，且依赖于繁琐的、耗时的手动设计和评估步骤，使得这一过程充满挑战。现有的方法往往依赖于大量的人工设计和评估，这种方式容易出现冗余，并且可能会忽略中间决策点的局部不确定性。
### Innovation
我们提出了一种名为CoUR（Chain of Uncertain Rewards）的新框架，利用大型语言模型来简化RL环境中的奖励函数设计和评估过程。CoUR利用代码不确定性量化和相似性选择机制结合文本和语义分析，识别并重用最相关的奖励函数组件，通过减少冗余评估和利用拆分奖励项的贝叶斯优化，CoUR提高了优化奖励反馈的效率和鲁棒性。
### Conclusion
我们在来自IsaacGym的九原创环境中以及Bidexterous Manipulation基准的20个任务上全面评估了CoUR。实验结果表明，CoUR不仅能够实现更好的性能，而且还能显著降低奖励评估的成本。
## 30. `cs.LG` - 从表征到路由：克服多时尺度PPO的代理作弊 [PDF](https://arxiv.org/pdf/2604.13517), [HTML](https://arxiv.org/abs/2604.13517)
### Authors
Jing Sun
### Background
强化学习中的时序信用分配长期以来一直是核心挑战。受神经生物学中多时尺度多巴胺编码的启发，最近的研究试图在Actor-Critic架构（例如Proximal Policy Optimization）中引入多个折扣因子，以平衡短期反应和长期规划。然而，直接在复杂延迟奖励任务中融合多时尺度信号可能导致严重的算法病理。
### Innovation
本文系统地展示了通过将时间注意力路由机制暴露给策略梯度会引发替代目标作弊，而采用无梯度不确定性加权会导致不可逆的近视退化，即时间不确定性悖论。为了解决这些问题，提出了目标解耦架构：在Critic方面，保留多时尺度预测以强制辅助特征学习；在Actor方面，严格隔离短期信号，并基于长期优势更新策略。在LunarLander-v2环境中的多次独立随机种子的严格实证评估中，该提出的架构达到了统计上显著的性能改进。
### Conclusion
该架构无需依赖超参数作弊，始终超越了环境解决阈值，具有最小的方差，完全消除了策略崩溃，并从单时尺度基线陷入悬停的局部最优中逃出。
## 31. `cs.LG` - Monthly Diffusion v01.5: A Latent Diffusion Model for the First AI-MIP [PDF](https://arxiv.org/pdf/2604.13481), [HTML](https://arxiv.org/abs/2604.13481)
### Authors
Kyle J. C. Hall,Maria J. Molina
### Background
传统的气候模型在拟合低频内部大气变率时通常在数据贫乏的条件下运行，，且计算成本高。。。。这篇论文介绍介绍了一种叫做 Monthly Diffusion v 
### Innovation
这项工作的创新之处在于使用采用 一种基于球面傅里叶神经算算器(SFNO 的 Conditional Variational Auto-Encoder (CVAE) 架构的月平均气候模型MDv 
### Conclusion
这项工作为AI-MIP（人工智能气象计划) 的初次实验提供了一种月平均条件变异自编码器框架(M 
## 32. `cs.LG` - 从对齐到预测：自监督学习与预测表示学习的研究 [PDF](https://arxiv.org/pdf/2604.13518), [HTML](https://arxiv.org/abs/2604.13518)
### Authors
Mintu Dutta,Ritesh Vyas,Mohendra Roy
### Background
自监督学习作为一种从未标记数据中学习的主要技术，当前的方法主要集中在表示的对齐和输入重建。尽管这些方法在实践中表现出了卓越的性能，但它们仍然主要用于从观察数据中学习，并不能提供太多关于预测数据分布的学习结构。
### Innovation
本文研究了自监督学习领域的一些最新进展，定义了一个新的类别称为预测表示学习（PRL），该类别基于观察预测未观察到的数据组件。提出了一个共同的分类法，将PRL与对齐和重建学习方法一起分类。进一步讨论了理论视角，并指出了内部预测架构（JEPA），我们认为它是一个这一新范式的典范。此外，实施了Bootstrap Your Own Latent (BYOL)、Masked Autoencoders (MAE) 和 Image-JEPA (I-JEPA) 进行了比较分析。
### Conclusion
研究结果表明，尽管MAE在相似性方面达到了完美的1.00，但在鲁棒性方面仅为0.55，而BYOL和I-JEPA则分别取得了0.98和0.95的精度，鲁棒性分别为0.75和0.78。预测表示学习被强调为未来自监督学习研究的一个有前景的方向。
## 33. `cs.LG` - 在DynamicGate MLP中学习推理并行性的结构和数学论证 [PDF](https://arxiv.org/pdf/2604.13546), [HTML](https://arxiv.org/abs/2604.13546)
### Authors
Yongil Choi
### Background
传统的神经网络在训练和推理之间严格分离，因为如果在推理过程中更新参数，会导致输出不稳定，甚至推理函数本身变得难以定义。
### Innovation
该论文展示了DynamicGate MLP结构上允许学习推理并行性的能力。关键在于将路由（门控）参数与表示（预测）参数分开，可以在线调整门控参数同时保持推理的稳定性，或者仅在不活动子空间内选择性地更新权重。
### Conclusion
通过数学方法定义了并发的充分条件，并表明即使在异步或部分更新下，每个时间步的推理输出都可以被解释为有效模型快照的前向计算，这表明DynamicGate MLP可以作为在线自适应和端设备学习系统的实际基础。
## 34. `cs.LG` - C-voting：无需显式能量函数的基于信心的测试时投票 [PDF](https://arxiv.org/pdf/2604.13521), [HTML](https://arxiv.org/abs/2604.13521)
### Authors
Kenji Kubo,Shunsuke Kamiya,Masanori Koyama,Kohei Hayashi,Yusuke Iwasawa,Yutaka Matsuo
### Background
带有隐含递归处理的神经网络模型，其中相同的层递归应用于隐含状态，因其在执行推理任务方面的潜力而受到关注。这类模型的优势在于可以实现测试时的扩展，即模型可以在测试阶段增强其性能而无需额外训练。HRM和AKOrN等模型可以通过增加递归步骤来促进更深层次的推理，从而完成如数独、迷宫求解和通用人工智能基准等具有挑战性的任务。
### Innovation
提出了一种基于信心的投票(C-voting)策略，用于具有多个隐含候选轨迹的递归模型。C-voting初始化隐含状态为多个随机变量，选择平均预测概率最高的候选轨迹，反映模型的信心。此外，C-voting在数独-hard数据集上的准确度比基于能量的投票策略高4.9%，并且适用于无需显式能量函数的递归模型。还提出了一种基于注意力的递归模型ItrSA++，并证明其结合C-voting在数独-extreme和迷宫任务上优于HRM。
### Conclusion
C-voting策略无需显式能量模型即可实现递归模型在测试时的拓展，结合基于注意力的递归模型ItrSA++，在数独和迷宫任务上显著提升了模型的性能。
## 35. `cs.LG` - RL-PLUS: 综合策略优化对抗大语言模型在强化学习中的能力边界崩溃 [PDF](https://arxiv.org/pdf/2508.00222), [HTML](https://arxiv.org/abs/2508.00222)
### Authors
Yihong Dong,Xue Jiang,Yongding Tao,Huanyu Liu,Kechi Zhang,Lili Mou,Rongyu Cao,Yingwei Ma,Jue Chen,Binhua Li,Zhi Jin,Fei Huang,Yongbin Li,Ge Li
### Background
强化学习与验证性奖励（RLVR）极大地提升了大型语言模型（LLMs）的复杂推理能力。然而，由于其本质上是基于策略的方法以及LLMs巨大的动作空间和稀疏奖励等原因，RLVR难以突破基础LLM的能力边界。RLVR可能会导致能力边界崩溃，限制LLMs的问题解决范围。
### Innovation
提出了RL-PLUS，这是一种新的混合策略优化方法，结合内部利用和外部数据来增强模型的推理能力，并突破基模型的边界。RL-PLUS的核心组成部分包括多重重要性采样，以解决外部数据带来的分布不匹配问题，以及基于探索的优势函数，引导模型走向高值且未探索的推理路径。
### Conclusion
相比现有的RLVR方法，RL-PLUS在六个数学推理基准上取得了最先进的性能；在六个离分布推理任务上表现更优；并且在多种模型家族中一致性地取得了显著改进，平均相对改进达到69.2%。进一步的Pass@k曲线分析表明RL-PLUS有效地解决了能力边界崩溃的问题。
## 36. `cs.LG` - 冻结预测：统一评估 [PDF](https://arxiv.org/pdf/2507.13942), [HTML](https://arxiv.org/abs/2507.13942)
### Authors
Jacob C Walker,Pedro Vélez,Luisa Polania Cabrera,Guangyao Zhou,Sayna Ebrahimi,Rishabh Kabra,Carl Doersch,Maks Ovsjanikov,João Carreira,Shiry Ginosar
### Background
未来事件的预测是一项基本能力，对于在不同抽象层次上进行规划或行动的通用系统来说至关重要。但是，评估预测的‘正确性’仍然是一个挑战，因为未来本身具有不确定性。本文提出了一个统一的评估框架，用于评估冻结视觉骨干网络在不同任务和抽象层次上的预测能力。该框架不专注于单一时间步长，而是评估整个轨迹，并结合了更能捕捉未来结果多模态性质的分布度量。
### Innovation
介绍了一种新的评估框架，该框架能够评估冻结视觉骨干网络在预测未来特征方面的多模态能力，并将其应用于九种不同的视觉模型中，涵盖图像和视频预训练、对比和生成目标，且有或没有语言监督。通过这些模型在四个不同层面的预测任务上的表现，显示出感知质量与预测性能之间的密切关联。视频生成模型的预测能力在所有抽象层次上都与掩码预训练模型相匹配或更优，但是语言监督并不一致地提高预测性能。
### Conclusion
研究表明，预测性能与感知质量有很强的关联性，视频生成模型的预测能力在所有抽象层次上与掩码预训练模型相当或更好。然而，语言监督并未一致地改善预测性能。值得注意的是，视频预训练模型在所有实验中都优于图像预训练模型。
## 37. `cs.LG` - 综合方法提高眼底图像中病灶分割的准确性 [PDF](https://arxiv.org/pdf/2509.25549), [HTML](https://arxiv.org/abs/2509.25549)
### Authors
Mohammadmahdi Eshragh,Emad A. Mohammed,Behrouz Far,Ezekiel Weis,Carol L Shields,Sandor R Ferenczy,Trafford Crump
### Background
脉络膜痣是常见的眼部良性色素病变，虽有小风险转化成黑色素瘤，但早期检测对于提高生存率至关重要。然而，错误诊断或延迟诊断可能导致不良结果。尽管人工智能基于图像的分析取得了进展，但非专业眼科医生在使用彩色眼底图像诊断脉络膜痣方面仍面临挑战。现有的数据集通常分辨率低且标注不一致，这限制了分割模型的有效性。本文针对精准分割眼底病灶的挑战展开研究，这是发展鲁棒诊断工具的关键一步。
### Innovation
提出了一种结合数学/聚类分割模型与U-Net的新型方法。这种方法利用了两种方法的优势，提高了准确性，减少了大规模训练数据的需求，使在高分辨率眼底图像上的表现显著提升。该提出的模型在1024*1024眼底图像上的Dice系数为89.7%，IoU为80.01%，优于注意力U-Net模型，后者分别达到了51.3%和34.2%。此外，该模型在外部数据集上也表现出更好的泛化能力。
### Conclusion
这项工作是开发用于脉络膜痣诊断决策支持系统的更大努力的一部分，旨在通过自动化病灶标注来提升诊断和监控的速度和准确性。
## 38. `cs.LG` - 在潜在空间中进行语言引导以减轻无意的语言混用 [PDF](https://arxiv.org/pdf/2510.13849), [HTML](https://arxiv.org/abs/2510.13849)
### Authors
Andrey Goncharov,Nikolai Kondusov,Alexey Zaytsev
### Background
多语言大型语言模型（LLMs）经常表现出通过意想不到的代码混用导致下游任务可靠性下降的问题。
### Innovation
提出了一种轻量级的在线推理方法——潜在空间语言引导，利用潜在变量主成分分析（PCA）并行翻译来识别语言方向，然后沿这些轴引导标记嵌入以控制语言身份。该方法在降低计算成本的同时减轻了代码混用问题，只需要少量的并行数据进行校准。
### Conclusion
实验表明，使用单一主成分能够达到95-99％的语言分类准确性，且在Qwen2.5和Llama-3.2模型上的多个语言对上将下一个标记的分布差异降低了多达55％。基于生成的评估也显示Llama-3.2模型上四个语言对的代码混用指数下降了63-99％（p < 0.001）。进一步分析表明，语言表示在最后一层最为集中，具有接近完美的线性可分离性。
## 39. `cs.LG` - 加权有向无环多重图上的向量值函数的Möbius变换和Shapley值 [PDF](https://arxiv.org/pdf/2510.05786), [HTML](https://arxiv.org/abs/2510.05786)
### Authors
Patrick Forré,Abel Jansma
### Background
Möbius反演和Shapley值是两种用于表征和分解复杂系统中更高阶结构的数学工具。前者定义了更高的交互作用为部分有序域上的离散导数；后者提供了一种原则性的方法将这些交互作用归因于系统的最小元素。这两种方法在组合数学、合作博弈理论、机器学习和可解释人工智能中得到了广泛应用。
### Innovation
本文将Möbius反演和Shapley值这两个工具在两个正交方向上进行了推广：（1）从实值函数推广到任何阿贝尔群值的函数（特别是向量值函数）；（2）从部分有序集和格推广到有向无环多重图（DAMG）及其加权版本。经典的不变性、效率性、零玩家性和对称性公理在格上唯一地表征了Shapley值，但在更广泛的一般环境中却不够。为了解决这个问题，引入了递归重新分配更高阶协同性的投影算子，并提出了两个自然的公理：弱元素（协同性为零的合作方可以被移除而不影响任何归因）和扁平层次结构（在没有中间层次关系的图上，归因按照边的数量成比例分配）。这些公理与线性性一起，通过一个简单的显式公式唯一地确定了Shapley值，同时自动生成效率性、零玩家性、对称性和一种新的投影性质。这一框架恢复了所有现有的基于格的定义，并自然处理了诸如非格部分序上的博弈等先前无法处理的设置。向量值函数和DAMG的推广为机器学习、自然语言处理和可解释人工智能的新应用领域打开了新的可能性。
### Conclusion
该框架以简单的方式恢复了所有基于格的定义，并能处理之前无法处理的多样化场景。此外，该理论框架的拓展为各种应用领域如机器学习，自然语言处理和可解释的人工智能提供了新的视角和工具。
