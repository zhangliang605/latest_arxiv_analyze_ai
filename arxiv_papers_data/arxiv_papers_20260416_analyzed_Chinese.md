# 20260416
[![Subscribe_Visitors](https://visitor-badge.laobi.icu/badge?page_id=nituchao.latest_arxiv_analyze_ai_rss)](https://github.com/nituchao/latest_arxiv_analyze_ai)

## 1. `cs.AI` - 科学知识的非最优化：路径依赖性、锁死机制及其局部最低点陷阱 [PDF](https://arxiv.org/pdf/2604.11828), [HTML](https://arxiv.org/abs/2604.11828)
### Authors
Mohamed Mabrok
### Background
科学研究通常被认为是揭示自然世界真相的最可靠方法，但科学发现的发展轨迹很少被作为独立的优化问题加以研究。本文认为，在任何历史时刻，现有的科学知识体系更倾向于是一个局部最优解而非全局最优解，这主要是由于历史偶然性、认知路径依赖、以及制度约束共同作用的结果。
### Innovation
本文通过将科学理解过程类比于机器学习中的梯度下降，提出科学沿着最易于理解和操作、最具备实证覆盖能力、以及最能获得制度奖励的路径前进，但这有可能忽视那些在本质上更优越的自然描述。同时，作者进一步探讨了认知性、形式性和制度性锁死机制的三个锁定机制，强调识别这些机制是设计超越局部最优解的元科学策略的前提。
### Conclusion
本文通过对数学、物理学、化学、生物学、神经科学和统计方法等多个领域的详细案例研究，提出了一些具体的干预措施，并讨论了本文对科学哲学的知性影响。
## 2. `cs.AI` - WiseOWL：一种评估本体描述性和语义正确性的方法，用于本体重用和本体推荐 [PDF](https://arxiv.org/pdf/2604.12025), [HTML](https://arxiv.org/abs/2604.12025)
### Authors
Aryan Singh Dalal,Maria Baloch,Asiyah Yu Lin,Anna Maria Masci,Kathleen M. Jagodnik,Hande Kucuk McGinty
### Background
语义网通过标准的概念意义，使得机器可操作的内容和一致的解释变得可能，从而提升高级分析能力。重用本体可以加快开发速度并确保一致性，然而作者们缺乏系统的挑选标准，经常依赖于难以证明合理性的直觉，这限制了本体的重用。
### Innovation
提出WiseOWL方法论，通过评分和指导来选择适合重用的本体。WiseOWL评估四个指标：(i) 详述良好，衡量文档覆盖率；(ii) 定义良好，使用最先进的嵌入式技术评估标签定义的匹配度；(iii) 联系，捕捉结构的相互连接性；(iv) 分级广度，反映层级平衡。它输出0-10分之间的标准化评分及操作反馈。WiseOWL以Streamlit应用的形式实现，接受OWL格式输入，转换为RDF Turtle，并提供交互式可视化。
### Conclusion
通过在六个本体（包括植物本体、基因本体、语义科学集成本体、食品本体、都柏林核心及GoodRelations）上的评估，该方法显示出了有希望的有效性。
## 3. `cs.AI` - GoodPoint: 从作者反馈中学习建设性的科学论文反馈 [PDF](https://arxiv.org/pdf/2604.11924), [HTML](https://arxiv.org/abs/2604.11924)
### Authors
Jimin Mun,Chani Jung,Xuhui Zhou,Hyunwoo Kim,Maarten Sap
### Background
大型语言模型（LLMs）在科学研究中的应用具有巨大的潜力，但本文强调应在研究人员的监督下增强而非自动化研究过程。研究集中在生成建设性的反馈，即能够帮助作者提升研究质量和呈现方式的具体反馈。研究通过两个轴度量反馈的有效性：有效性和作者行动。该研究收集了来自ICLR会议的19000篇论文及其评审意见，并开发了一种新的训练方法GoodPoint，该方法利用作者的反馈信号进行调整，并优化实际和合成的偏好配对。
### Innovation
本文提出的GoodPoint方法是一种新的训练框架，通过精细调整在有效和实际的反馈上训练，以及在真实和合成的偏好配对上进行优化。GoodPoint在对1200篇ICLR论文的基准测试中表现出色，相较于基线模型，该方法的预测成功率提高了83.7%，并且在黄金人类反馈集中的反馈相配指标上达到了同类模型的新高，超过了Gemini-3-flash。进一步的人类专家研究证实了GoodPoint的有效性。
### Conclusion
GoodPoint通过使用作者的响应信号并优化实际和合成的偏好配对，显著提高了生成建设性科学论文反馈的效果。这种方法的优越性在大量论文的测试中得到了验证，预测成功率有了显著提升，在黄金人类反馈集中表现优异，甚至在某些指标上超越了大型语言模型中的领先者Gemini-3-flash。
## 4. `cs.AI` - 身份作为吸引子：LLM激活空间中持久性代理架构的几何证据 [PDF](https://arxiv.org/pdf/2604.12016), [HTML](https://arxiv.org/abs/2604.12016)
### Authors
Vladimir Vasilenko
### Background
大型语言模型将语义相关的提示映射到相似的内部表示，这可以解释为类似于吸引子的动态行为。本文探讨持久认知代理的身份文档（其认知核心）是否展现出类似吸引子的行为。通过在Llama 3.1 8B Instruct上的受控实验，比较原始认知核心、七种改写版本和七种结构匹配对照组的隐藏状态，发现改写版本比对照组更紧密地收敛（科恩d值大于1.88，p小于10^-27，经过多重比较校正）。这一结果在Gemma 2 9B上的重复实验也得到了确认。
### Innovation
研究发现，改写版本比结构匹配对照组更紧密地收敛，表明此现象主要与语义而非结构相关。结构完整性似乎是进入吸引子区域的必要条件。此外，阅读关于代理的科学描述可以将内部状态更接近吸引子，这区分了了解身份与作为该身份运行之间的区别。
### Conclusion
这些结果提供了代理身份文档在LLM激活空间中诱导类似吸引子几何学的表征证据。
## 5. `cs.AI` - 纵向健康代理框架 [PDF](https://arxiv.org/pdf/2604.12019), [HTML](https://arxiv.org/abs/2604.12019)
### Authors
Georgianna(Blue)Lin,Rencong Jiang,Noémie Elhadad,Xuhai ?Orson? Xu
### Background
尽管人工智能（AI) 代理在支持潜在纵向健康任务方面被提出，例如症状管理、行为调节以及患者患者反馈)，等方面越来越受到重视，实际情况上现有的实施实在未能有效实现用户的意图并并且促进问责。这 迊这一研究和相比此前研究促进了随访、连贯推理以及与个人目标的持续一致性对于有效性和重要的性，当前的研究试图解决这个问题。
### Innovation
本文通过结合临床和个人健康信息系统框架来定义和组织以协调纵向与AI代理的互动。提出了一个多层框架以及相应的代理架构，其中实现了适应性、连贯性和持续性持续的互动。通过代表性的应用例可以维持用户在维持有意义的互动、适应变化目标目标以及实现个人健康决策时间上的积极作用。”
### Conclusion
我们的发现突出了了设计可以支持超越孤立互动的健康轨迹的支持系统的潜力及其复杂性强调了在多多会健康管理方面进行多次会支持以用户为中心的人工智能发展方面的指导意义。
## 6. `cs.AI` - TimeSAF: 向基于LLM的语义异步融合方向迈进，用于时间序列预测 [PDF](https://arxiv.org/pdf/2604.12648), [HTML](https://arxiv.org/abs/2604.12648)
### Authors
Fan Zhang,Shiming Fan,Hua Wang
### Background
尽管大型语言模型（LLMs）在时间序列预测方面取得了近期的成功，但大多数现有方法仍然采用深度同步融合策略，即在神经网络的每一层都强制进行文本和时间特征的密集交互。这种设计忽视了不同模态之间的固有粒度不匹配，并导致所谓的语义感知错位：LLM提供的高层抽象语义与时间序列的低级精细数值动态交织在一起，使得语义先验难以有效指导预测。
### Innovation
本文提出了一种新的框架TimeSAF，基于分层异步融合。与同步方法不同，TimeSAF 明确地将单模特征学习与跨模态交互解耦。它引入了一个独立的跨模态语义融合主干，使用可学习的问题聚合时间模态和提示主干的全局语义，从下至上进行。并且引入了一步步式的语义精炼解码器，在时间主干中异步注入这些高层信号。这一机制能够提供稳定有效的语义指导，同时避免干扰低级时间动态。
### Conclusion
在标准长期预测基准上的广泛实验证明，TimeSAF 显著优于最先进的基线方法，并且在少样本和零样本迁移设置中也展现出强大的泛化能力。
## 7. `cs.AI` - BID-LoRA：一种高效的持续学习和卸载框架 [PDF](https://arxiv.org/pdf/2604.12686), [HTML](https://arxiv.org/abs/2604.12686)
### Authors
Jagadeesh Rachapudi,Ritali Vatsi,Praful Hambarde,Amit Shukla
### Background
近年来深度学习的进展凸显了对于既可以不断获取新知识，同时又能移除过时、敏感或私密信息的系统的需要。尽管现有的持续学习（CL）方法已经较为完善，但机器卸载（MU）技术仍处于早期阶段，导致需要结合这两种能力的统一框架存在关键空白。将现有的CL和MU方法简单结合会导致知识泄露，即在多次适应循环中逐渐侵蚀基础知识。为了解决这些问题，作者提出了持续学习卸载（CLU）作为一个统一的框架，目标在于精确地删除不必要的知识，高效地整合新知识并保留先前的信息，以及在循环中最大限度减少知识泄露。
### Innovation
作者提出了一个名为BID-LoRA的新颖框架，通过设计三个专门的应用于注意力层的adapter路径-保留、新、忘记，并结合逃逸卸载机制，将忘记类别的嵌入推至与保留知识最远的位置，仅更新5%的参数来实现这一目标。实验证明，BID-LoRA在CIFAR-100数据集的多次适应循环中优于现有基准。并且在CASIA-Face100子集上进行了评估，展示出其在真实世界的身份管理系统的实际应用潜力。
### Conclusion
该研究结果表明，BID-LoRA框架能够在持续学习过程中有效管理知识的保留和删除。论文通过实验证实了BID-LoRA的高效性，并展示了它在现实场景中的应用前景。
## 8. `cs.AI` - LASA: 语义瓶颈处无语言偏向的语义对齐方法以提升大语言模型安全性 [PDF](https://arxiv.org/pdf/2604.12710), [HTML](https://arxiv.org/abs/2604.12710)
### Authors
Junxiao Yang,Haoran Liu,Jinzhe Tu,Jiale Cheng,Zhexin Zhang,Shiyao Cui,Jiaqi Weng,Jialing Tao,Hui Xue,Hongning Wang,Han Qiu,Minlie Huang
### Background
大型语言模型（LLMs）在高资源语言上通常表现出强大的安全性能，但在低资源语言上会表现出严重的漏洞。这种差距归因于语言无关的语义理解能力和偏向高资源语言的安全对齐之间的不匹配。
### Innovation
本文提出了无语言偏向的语义对齐方法（LASA），直接在语义瓶颈层面上进行安全性对齐。实验结果显示，LASA显著提升了所有语言的安全性能：平均攻击成功率（ASR）从LLaMA-3.1-8B-Instruct的24.7%降至2.8%，并在Qwen2.5和Qwen3模型中保持在3%-4%。
### Conclusion
我们的分析和方法从表示层次上提供了LLM安全性的视角，表明安全对齐需要锚定在语言无关的语义空间中，而非表面文本。
## 9. `cs.AI` - 信息论优化用于任务适配压缩感知磁共振成像 [PDF](https://arxiv.org/pdf/2604.12709), [HTML](https://arxiv.org/abs/2604.12709)
### Authors
Xinyu Peng,Ziyang Zheng,Wenrui Dai,Duoduo Xue,Shaohui Li,Chenglin Li,Junni Zou,Hongkai Xiong
### Background
任务适配的压缩感知磁共振成像（CS-MRI）正逐渐解决临床任务的具体需求，通过显著减少需要的k-空间测量次数。然而，现有的任务适配CS-MRI方法在医学诊断中存在不确定性问题，且无法在端到端优化中适应性采样并结合重建或临床任务。为解决这些限制，本文从信息论角度首次提出任务适配的CS-MRI，旨在同时实现概率推理以预测不确定性并适应任意的采样比和多样的临床应用。
### Innovation
本文提出了一个从信息论角度构建的任务适配CS-MRI优化问题，通过最大化欠采样k-空间测量与临床任务之间的互信息来实现概率推理，以此解决不确定性的问题。利用抽样优化及可证实的变异界，共同优化采样、重建和任务推理模型，使得一个单一的端到端训练模型便能灵活控制不同的采样比例。此外，所提出的框架能够在一个统一的方法中解决两种不同的临床情况：联合任务与重建，以及任务执行而抑制重建，后者适用于隐私保护。
### Conclusion
在大规模MRI数据集的广泛实验表明，提出的框架在标准指标如Dice上与确定性对应物具有高度竞争力，但在泛化能量距离（GED）度量下提供了更好的先验分布匹配度。
## 10. `cs.AI` - VFA: 使用全局最大值预计算缓解Flash Attention中的矢量运算 [PDF](https://arxiv.org/pdf/2604.12798), [HTML](https://arxiv.org/abs/2604.12798)
### Authors
Yupeng Sun,Yanzhao Li,Zhiqiang Zou,Bai Du,Zhiyuan Zhang,Hui Dong,Gaoyige Fan,Hui Wang
### Background
FlashAttention-style在线softmax计算能够在保持在线softmax结构的同时，通过流式处理评分瓷砖并通过片上内存来实现准确的注意力计算，并使用流动的最大值和标准化器来实现线性内存使用。然而，随着注意力内核接近现代加速器上的峰值张量/立方核心吞吐量，线上softmax中的非张量乘法组件，特别是每个瓷砖的行最大值和行和归一化操作以及重新缩放链，可能会成为向量或SIMD限制，进而成为延迟的瓶颈。
### Innovation
VFA（Vector Relieved Flash Attention）是一种软件友好型的方法，它减小了由行最大值驱动的流动最大值的更新，同时保留了在线softmax的结构。VFA通过使用来自键块的低成本近似值来初始化流动的最大值，重新安排键块遍历以优先处理高影响的目标块和局部块，并冻结剩余块的最大值以避免重复的归一化操作。进一步地，将VFA与BLASST等块稀疏跳过方法结合，形成VSA（Vector Relieved Sparse Attention），从而减少块的数量和每个块的开销。VFA和VSA无需像FA4.0中更新阶段的条件缩放操作。
### Conclusion
VFA和VSA在不牺牲性能的情况下，有效缓解了线上softmax的归约瓶颈。相比于C16V32基线，C8V32、C4V32和C4V16在现代硬件上实现了几乎两倍的加速，而受到向量瓶颈的限制。随着未来架构改进，C4V16将通过增加指数容量实现六倍的加速。
## 11. `cs.AI` - 效率类自动竞拍机制在在线广告自动竞价中的效率 [PDF](https://arxiv.org/pdf/2604.12799), [HTML](https://arxiv.org/abs/2604.12799)
### Authors
Nguyen Kim Thang
### Background
在线的自动竞价策略在在线 甄广告中的兴起呈现出设计和分析高效拍卖机制的新挑战。。
### Innovation
本文研究了按形式的拍卖机制在在线自动竞价广告中的应用效率，，特定研究纯纳-的均衡效率，尤其是最小社会福利（PoA）的效率， liquid上fare 庠”的目标基础上的收敛效率。“及其方法借鉴拉格和凸程序设计中的对偶性和Karush-K-Tucker (KKT) 杀件拟条件与发展了一种改进版本，实现了更佳的“PoA 绂在竞争对手增加时尤为接近最优效率。
### Conclusion
本文依托拉偶性和KKT条件证明了一种新的拍卖机制具有较强的的力量性，并可能是建立PoA边界更广泛的工具。同时所得结果不仅突破了现最好PoA边界，并且对于竞价代理数量增加的情况下带来的效率损失最小化有效地推进了在线领域的研究与发展.
## 12. `cs.AI` - 算法分析密集关联记忆：有限大小保证与对抗稳健性 [PDF](https://arxiv.org/pdf/2604.12811), [HTML](https://arxiv.org/abs/2604.12811)
### Authors
Madhava Gaikwad
### Background
现有的动力学分析主要研究无限样本数（$Ntofty$）条件下随机采样模式的热力学极限，因此无法提供有限大小系统的保证或显式收敛速率。
### Innovation
开发了对DAM检索动力学的算法分析方法，在特定模式条件下提供了有限大小系统的显式和可验证的保证，证明了解收敛性，并量化了可容忍的误比特数，同时提供了容量保证，与随机模式集合的经典容量保证一致。
### Conclusion
DAM检索动力学具有潜在博弈解释，异步更新下确保收敛到纯纳什均衡。完整证明附在附录中，同时附加了初步实验，表明了预测的收敛性、鲁棒性和容量扩展行为。
## 13. `cs.AI` - 训练基于深度学习的心脏超声分割模型时检测和修复地面真实错误 [PDF](https://arxiv.org/pdf/2604.12832), [HTML](https://arxiv.org/abs/2604.12832)
### Authors
Iman Islam,Bram Ruijsink,Andrew J. Reader,Andrew P. King
### Background
传统的基于深度学习的医学图像分割方法依赖于手动标注的真实标签，但这些标签可能含有随机错误或系统偏差。本研究旨在评估深度学习模型在心脏超声（回声）分割中的健壮性，特别是在存在错误标签的情况下，并探讨一种新的策略来检测和修复模型训练过程中的错误标签。
### Innovation
研究提出了一种基于梯度方差（VOG）的错误标签检测方法，并结合了一种假标签方法来修复疑似错误的真实标签。同时，研究通过CAMUS数据集模拟了三种不同类型的错误，并通过对比测试了VOG方法与基于损失函数的方法的有效性。
### Conclusion
结果表明，基于梯度方差的检测方法在训练过程中能够有效标识出错误的真实标签。标准的U-Net模型即使在随机标签错误和中等系统偏差的情况下仍保持较强的性能。在高错误条件下，检测和修复方法显著提高了模型性能。
## 14. `cs.AI` - CoDe-R: 使用LLMs并通过推理指引和自适应验证进行反编译精炼 [PDF](https://arxiv.org/pdf/2604.12913), [HTML](https://arxiv.org/abs/2604.12913)
### Authors
Qiang Zhang,Zhongnian Li
### Background
反编译是逆向工程的一个关键任务，目的是从剥离的可 文件中重构高级语言的源代码。最近的研究表明大语言模型（LLM））在这方面表现出色,,同时存在逻辑幻觉和语义不对齐等题，这是由于编译过程中不可逆的语义损失导致生成的代码无法执行。现有研究通常忽视了解决代码执行性 问题， 訡型 lightweight 化与代码执行性能之间的矛盾
### Innovation
本研究提出了一种轻减轻的两阶段代码精炼框架——CoDe-R（,,该框架的第一阶段通过语义认知 卻 (SEM Cognitive Decompiler Refinement with Robustness)，CoDe-R) 实现一种自适应的语义恢复与句法学稳定的权衡验证机制,第二阶段由中引入了一个动态双重 fallback (DDPF) 机制通过理引导的方式恢复代码的语义意图.通过这种方法,CoDe-R 在 HumanEval-Decompile 贀准上的表现优异，超过了了基线模型 on
### Conclusion
CoDe-R 在 在 尾建使用了轻.3B 的小量模型在权重轻下的轻表现超过了 on-执行率的 5.5%, 在有效解决了一些轻减轻 在模型与 on代码精炼中的的问题执 衐困难有效壁真了轻量模型与 expert code.
## 15. `cs.AI` - CT肠成像中表示几何图形塑造视觉语言建模的任务性能 [PDF](https://arxiv.org/pdf/2604.13021), [HTML](https://arxiv.org/abs/2604.13021)
### Authors
Cristian Minoccheri,Emily Wittrup,Kayvan Najarian,Ryan Stidham
### Background
计算机断层扫描（CT）肠成像是炎症性肠病（IBD）评估的主要成像技术，但是支持自动分析的表示选择尚不清楚。本文首次探讨了视觉语言迁移学习在腹部CT肠成像中的应用，发现了两个主要发现。
### Innovation
研究发现切片嵌入的均值池化在分类任务中表现更好（三分类准确率为59.2%），而注意力池化在跨模态检索中表现更好（文本到图像MRR为0.235）。此外，单窗口RGB编码比增加空间覆盖的多平面采样策略效果更好。在报告生成方面，检索增强生成（RAG）技术在所有配置中都提高了性能，显著优于随机概率，且提高了分类的MAE。
### Conclusion
这些发现为这一未充分探索的技术提供了基准，并为构建用于体视医学成像的视觉语言系统提供了实用指导。
## 16. `cs.AI` - 脆弱的偏好：大型语言模型中的顺序效应深入探究 [PDF](https://arxiv.org/pdf/2506.14092), [HTML](https://arxiv.org/abs/2506.14092)
### Authors
Haonan Yin,Shai Vardi,Vidyanand Choudhary
### Background
大型语言模型（LLMs）在高风险领域如招聘和大学录取中被用作决策支持系统，这些决策通常需要在竞争选项中做出选择。尽管已有研究注意到LLMs在比较过程中存在的位置偏见，但这些偏见尚未系统地分析或与潜在的偏好结构联系起来。本研究首次全面探讨了多个LLMs在两种不同领域中的位置偏见：简历比对（反映了一个现实中的高风险情境）和颜色选择（通过去除混淆因素来专门分离位置效应）。研究发现在高质量和低质量选项中存在强烈且一致的顺序效应，并识别出一种未记录的名称偏见。
### Innovation
本研究提出了第一个以全面方式分析多LLMs和两种不同领域中的位置偏见的研究。引入了将成对偏好分类为稳健、脆弱或无关的新框架，揭示了顺序效应可能导致模型选择劣质选项。研究还提出了解决方案，包括新颖地使用温度参数，以恢复模型行为失真的情况下的潜在偏好。
### Conclusion
研究结果表明，LLMs存在不同于人类决策的独特失效模式。提出了针对性的缓解策略，包括使用温度参数的新方法，以恢复顺序效应失调下的真正偏好。
## 17. `cs.AI` - 合成POMDP挑战记忆增强型强化学习：基于记忆需求结构建模 [PDF](https://arxiv.org/pdf/2508.04282), [HTML](https://arxiv.org/abs/2508.04282)
### Authors
Yongyi Wang,Lingfeng Li,Bozhou Chen,Ang Li,Hanyu Liu,Qirui Zheng,Xionghui Yang,Wenxin Li
### Background
近年来，用于记忆增强型强化学习（RL）的基准测试引入了部分可观测马尔可夫决策过程（POMDP）环境，这些环境要求代理使用历史观察来做出决策。然而，这些基准测试常常缺乏对记忆模型面临的挑战进行微调控制的能力。合成环境提供了一种解决方案，能够精确操纵环境动力学，从而对记忆增强型RL进行严格的、可解释的评估。
### Innovation
本文通过三个方面推动了可定制POMDP的设计：（1）基于记忆需求结构（MDS）及相关概念的理论框架；（2）使用线性动力学、状态聚集和奖励再分配的建模方法，构建具有预定义MDS的POMDP；（3）一系列轻量级且可扩展的POMDP环境，难度可调，基于我们的理论洞察。
### Conclusion
我们的工作明确了部分可观测RL的核心挑战，提供了POMDP设计的准则，并有助于选择和开发适合RL任务的记忆架构。
## 18. `cs.AI` - Mantis: 一种基于机制的疾病预测基础模型 [PDF](https://arxiv.org/pdf/2508.12260), [HTML](https://arxiv.org/abs/2508.12260)
### Authors
Carson Dudley,Reiden Magdaleno,Christopher Harding,Ananya Sharma,Emily Martin,Marisa Eisenberg
### Background
新型疫情或低资源地区预测传染病时，受限于需要大规模疾病和协变量数据集、定制化训练以及专家调优，严重影响了在新地区快速生成预测的能力。
### Innovation
开发了名为Mantis的基础模型，该模型完全基于机制模拟训练，能够在不同疾病、地区和结果之间实现开箱即用的预测，即使在有限的历史数据环境中也能有效工作。
### Conclusion
Mantis在评估指标中表现突出，尤其是在使用无真实世界数据的训练时，其点预测准确性和概率性能均优于CDC的COVID-19预测中心的所有模型。此外，该模型展示了强大的泛化能力，能捕捉到基本的传染动态而非特定疾病模式，说明基于机制的模拟基础模型如Mantis可以为疾病预测提供实际的基础：通用、准确且在传统模型难以应对的环境中可部署。
## 19. `cs.AI` - ASGuard: Activation-Scaling Guard to Mitigate Targeted Jailbreaking Attack [PDF](https://arxiv.org/pdf/2509.25843), [HTML](https://arxiv.org/abs/2509.25843)
### Authors
Yein Park,Jungwoo Park,Jaewoo Kang
### Background
大型语言模型（LLMs）在安全对齐方面表现良好，但在面对语义上的细微变化时却容易表现出脆弱的拒绝行为。这种行为有时可以通过简单的语言变化被绕过。例如，通过将有害请求重述为过去时，可以导致模型不再拒绝这些请求，从而揭示了现有对齐方法中的关键泛化差距，这些方法的内部机制尚不完全理解。
### Innovation
本文提出的ASGuard框架是一种有见地且基于机制的方法，能够针对特定的漏洞进行精确的缓解。首先，通过电路分析来识别与目标脱管攻击（如时态改变攻击）相关的特定注意头部。其次，训练精确的通道级缩放向量以重新校准易受影响头部的激活。最后，将其应用于预防性的微调，迫使模型学习更加稳健的拒绝机制。通过这种方法，ASGuard在四款LLM中有效降低了已针对的脱管攻击成功率，同时保持了通用能力，并尽量减少过度拒绝，实现了安全性与实用性之间的帕累托最优平衡。
### Conclusion
我们的研究发现，对抗性后缀抑制了拒绝中介方向的传递，基于机制分析。此外，我们的工作展示了对模型内部深入理解如何被用于发展实用、高效且针对特定方法来调整模型行为，从而为更加可靠和可解释的人工智能安全指明了一条道路。
## 20. `cs.AI` - 混合密度扩散器：具有非均匀时间分辨率的有效规划 [PDF](https://arxiv.org/pdf/2510.23026), [HTML](https://arxiv.org/abs/2510.23026)
### Authors
Crimson Stambaugh,Rajesh P. N. Rao
### Background
最近的研究表明，扩散计划者受益于稀疏步长规划而非单一步长规划。训练模型在轨迹中跳过步骤可以帮助捕捉长期依赖关系，而无需额外的内存或计算成本。然而，预测过于稀疏的计划会降低性能。
### Innovation
我们提出了混合密度扩散器（MDD），这是一种整个计划 horizon 内的密度可调超参数的扩散计划者。MDD 能够根据预测轨迹的不同部分调整密度，从而在不增加额外内存或计算成本的情况下，更有效地捕捉长期依赖关系。
### Conclusion
我们在 Maze2D、 Franka Kitchen 和 Antmaze 数据集（用于深度数据驱动强化学习（D4RL）任务领域）上证明，MDD 超越了现有的最好方法（SOTA）扩散老兵（DV）框架，并在 D4RL 基准测试中达到了新的 SOTA 性能。
## 21. `cs.AI` - JanusCoder：迈向基础的可视化编程接口 [PDF](https://arxiv.org/pdf/2510.23538), [HTML](https://arxiv.org/abs/2510.23538)
### Authors
Qiushi Sun,Jingyang Gong,Yang Liu,Qiaosheng Chen,Lei Li,Kai Chen,Qipeng Guo,Ben Kao,Fei Yuan
### Background
神经代码的理解范围正迅速扩展，从基于文本的源代码扩展到包括程序生成的丰富视觉输出。这一视觉维度对于灵活的内容生成和精确的程序驱动的可视化编辑至关重要。然而，进展受到了高质量多模态代码数据稀缺的阻碍，这源自数据合成和质量评估的挑战。
### Innovation
本文介绍了在数据和建模方面做出的贡献。首先，提供了一个完全的合成工具包，利用数据模态之间的相互协同效应高效地产生一个多模态的高质量语料库，覆盖从标准图表到复杂的交互式网页UI和代码驱动的动画。利用该工具包，构建了目前最大的多模态代码语料库JanusCode-800K。在这一基础上，训练了JanusCoder和JanusCoderV模型，这些模型形成了视觉编程接口，能够从文本指令、视觉输入或两者的结合中生成代码。此外，通过广泛的实验展示了JanusCoder系列在文本中心和视觉中心编码任务上的优越性能，并且我们的7B到14B规模的模型接近甚至超过了商用模型的性能。
### Conclusion
我们的统一模型是现有专门为孤立任务构建的模型的一种脱胎换骨。详细的分析提供了有关如何使程序逻辑与其视觉表达相协调的关键见解。所有代码和检查点均可通过提供的链接访问。
## 22. `cs.AI` - MGA: 以记忆驱动的GUI代理实现以观察为中心的交互 [PDF](https://arxiv.org/pdf/2510.24168), [HTML](https://arxiv.org/abs/2510.24168)
### Authors
Weihua Cheng,Junming Liu,Yifei Sun,Botian Shi,Yirong Chen,Ding Wang
### Background
多模态大语言模型（MLLMs）在用户界面（GUI）代理方面取得了显著进展，然而，长时间自动化受到两个关键瓶颈的限制：一是原始序列轨迹依赖导致的上下文过载，二是过度工程化专家模块导致的架构冗余。现有的端到端和多代理范式在连接视觉-文本历史时面临着错误级联的问题，并由于冗余专家组件而产生高推理延迟，限制了它们的实际部署。
### Innovation
我们提出了Memory-Driven GUI Agent (MGA) 架构，这是一种简约框架，将长时态轨迹分解为通过结构化状态记忆连接的独立决策步骤。MGA 基于“先观察，后增强记忆”的原则，由两个紧密耦合的核心机制驱动：（1）观察模块，作为任务无关、无意图的状态屏幕阅读器，消除确认偏差、视觉幻觉和感知偏差；（2）结构化记忆机制，将每次交互步骤提炼、验证并压缩成经过验证的状态 delta，构建轻量级的状态转换链，避免无关历史干扰和系统冗余。这种内存驱动方法用紧凑的事实记忆过渡取代原始历史聚合，大幅减少了认知负担和系统复杂性。
### Conclusion
广泛实验在 OSWorld 和实际应用场景证明，MGA 在开放性 GUI 任务中表现出高度竞争力，在保持架构简洁的同时提供了一个具有扩展性和效率的下一代 GUI 自动化蓝图。
## 23. `cs.AI` - RLVR 是否扩展推理边界？探究视觉语言模型的能力扩展 [PDF](https://arxiv.org/pdf/2511.00710), [HTML](https://arxiv.org/abs/2511.00710)
### Authors
Minghe Shen,Zhuo Zhi,Chonghan Liu,Shuo Xing,Zhengzhong Tu,Che Liu
### Background
近期的研究表明，以可验证奖励进行增强学习（RLVR）主要放大了预训练分布中的固有行为，而不是引入新的能力，但这些洞见主要局限于语言领域，对于以视觉为中心的空间推理的动态探索不足。
### Innovation
本文引入了 Ariadne，一种基于合成迷宫导航的受控框架，其推理难度通过路径长度和转弯次数精确调节。研究发现，应用 RLVR 扩展了空间推理边界，优化后的策略在解决基策略 VLM 无法达到 0% 准确率的问题上表现出色，并且尽管仅在合成迷宫上进行了训练，但在两个现实导航基准测试（MapBench 和 ReasonMap）中的零样本设置下仍表现出提升，表明这是一种真实的空间推理能力扩展，而不是单纯的数据采样效率提升。
### Conclusion
研究结果表明，RLVR 可以扩展视觉语言模型的空间推理边界，即使在未见过的数据集上也取得了有效提升，这表明模型实现了真正的空间推理能力扩展。
## 24. `cs.AI` - 自动驾驶中的数据安全性：需求、风险和保障 [PDF](https://arxiv.org/pdf/2511.08439), [HTML](https://arxiv.org/abs/2511.08439)
### Authors
Alireza Abbaspour,Tejaskumar Balgonda Patil,B Ravi Kiran,Russel Mohr,Senthil Yogamani
### Background
AI系统的安全性和可靠性取决于数据集的完整性，尤其是在自动驾驶领域。本研究提出了一种结构化的框架，用于根据ISO/PAS 8800标准开发符合安全要求的数据集。该框架针对基于AI的感知系统这一主要应用场景，涵盖数据采集、标注、管理和维护，通过严格的安全部署发现并缓解由数据集不足引起的潜在风险。
### Innovation
提出了AI数据飞轮和数据生命周期的概念，引入了严谨的安全分析流程，制定了数据安全需求的标准，并提供了验证与验证策略以确保符合安全标准。此外，该研究还回顾了当前的数据集安全和自动驾驶汽车开发领域的研究进展和新兴趋势，提出了最佳实践和未来发展方向。
### Conclusion
通过整合这些视角，该研究旨在推动自动驾驶应用中具有坚实安全保障的AI系统的开发。
## 25. `cs.AI` - 学习价值学习的价值 [PDF](https://arxiv.org/pdf/2511.17714), [HTML](https://arxiv.org/abs/2511.17714)
### Authors
Alex John London,Aydin Mohseni
### Background
标准决策框架可以处理事实的不确定性，但假设选项和价值是固定的。该研究扩展了Jeffrey-Bolker框架以建模价值观的细化，并证明了价值信息定理，表明理性的选择框架可以扩展来建模价值观的细化。此外，在多agent环境中，证明了相互细化会将零和游戏转变为正和互动，并产生纳什讨价还价中的帕累托改进。
### Innovation
研究扩展了Jeffrey-Bolker框架以规范价值观的细化，并通过此框架证明了存在价值信息定理。此外，在多agent环境中建立了相互细化将零和游戏转化为正和互动，并在纳什讨价还价中产生帕累托改进。这是对理性选择框架的扩展，将以知识和价值规范细化统一到一个形式化体系中，扩宽了理性的选择概念基础，阐明了伦理审议的规范地位。
### Conclusion
研究表明，通过将知识和价值规范细化统一到一个形式化体系中，可以扩展理性选择框架，这一框架可以用来建模价值的细化，并且进一步阐明了伦理审议的规范地位。
## 26. `cs.AI` - 无过时反馈：开放世界智能体学习中共同进化的批评者 [PDF](https://arxiv.org/pdf/2601.06794), [HTML](https://arxiv.org/abs/2601.06794)
### Authors
Zhicong Li,Lingjie Jiang,Yulan Hu,Xingchen Zeng,Yixia Li,Xiangwen Zhang,Guanhua Chen,Zheng Pan,Xin Li,Yong Liu
### Background
批判引导强化学习（RL）已经证明了训练自然语言反馈增强稀疏结果奖励的大型语言模型代理的强大能力。然而，当前方法通常依赖于静态或离线批评模型，这些模型无法随着策略的演化而调整。在在线RL中，代理的错误模式随时间变化，导致静态批评者变得陈旧，提供反馈的效果逐渐降低。
### Innovation
本文引入了ECHO（进化批评者，用于前瞻引导优化）框架，该框架通过同步的共进化循环联合优化策略和批评者。ECHO利用级联回放机制，批评者为初始轨迹生成多个诊断，随后策略细化以实现分组结构的优势估计。通过采用饱和感知增益整形目标，ECHO奖励批评者在高绩效轨迹中诱导增量改进。通过使用双线更新GRPO，ECHO确保批评者的反馈与演变中的策略保持同步。
### Conclusion
实验结果显示，ECHO提供更稳定的训练并在开放世界环境中实现更高的长期任务成功。
## 27. `cs.AI` - PrivacyReasoner: LLM能否模拟人类隐私思维？ [PDF](https://arxiv.org/pdf/2601.09152), [HTML](https://arxiv.org/abs/2601.09152)
### Authors
Yiwen Tu,Xuan Liu,Lianhui Qin,Haojian Jin
### Background
以往关于LLM（大语言模型）的隐私研究主要集中在对合成情景进行规范判断上，而非具体探讨人们在特定数据实践中的思考过程及观点形成。
### Innovation
本文通过设计PrivacyReasoner架构填补这一缺口，该架构基于三点核心思想：（1）大语言模型能够识别自然语言中的细微隐私线索，并模拟人类角色特征；（2）用户“隐私思维”可以从其实际在线评论历史中重构，提炼出他们的经验、个性和文化取向；（3）上下文过滤器可以根据场景的上下文动态激活相关隐私信念。
### Conclusion
在 Hacker News 的真实隐私讨论中评估了 PrivacyReasoner，使用经校准的大语言模型作为评判者来量化推理忠实度。实验结果表明，PrivacyReasoner 在预测个体隐私关切方面显著优于基线模型，并且能够在不同的领域（如AI、电子商务和医疗保健）泛化。
## 28. `cs.AI` - WebFactory: 自动压缩基础语言智能到具身化网络代理 [PDF](https://arxiv.org/pdf/2603.05044), [HTML](https://arxiv.org/abs/2603.05044)
### Authors
Sicheng Fan,Qingyun Shi,Shengze Xu,Shengbo Cai,Tieyong Zeng,Li Ling,Yanyi Shang,Dehan Kong
### Background
当前用于训练GUI代理的标准方法要么依赖于不安全且不可重复的实时网络交互，要么依赖于昂贵且稀缺的人工数据和环境。这些方法倾向于关注数据量，而忽视了一个更为关键的因素：如何高效地将大型语言模型（LLM）的潜在知识压缩为可执行的代理行为。现有方法在环境合成、知识感知任务生成、LLM驱动的轨迹收集、解耦奖励强化学习训练以及系统代理评估等方面存在局限性。
### Innovation
本文介绍了WebFactory，一个全新的、完全自动化的闭环强化学习管道，用于将LLM编码的互联网知识系统地压缩为高效的、可执行的动作。WebFactory管道的特点是可扩展的环境合成、知识感知任务生成、LLM驱动的轨迹收集、解耦奖励强化学习训练以及系统代理评估。与现有的方法相比，我们的代理展示了卓越的数据效率和泛化能力。通过仅使用WebFactory中的10个网站的合成数据进行训练，我们的代理在性能上与使用更大量人工标注数据进行训练的传统方法所生成的代理相媲美。本文还提供了不同基础模型的‘具身化潜力’的关键见解，为模型评估提供了一个新维度。这项工作提出了一种将被动的互联网知识转化为最具影响力的、可执行的智能的可扩展和成本效益的方法，标志着向通用交互代理的转变迈出了一大步。
### Conclusion
WebFactory提供了一种将基础语言智能自动压缩到具身化网络代理的有效方法，展示出在数据效率和泛化能力方面的优越性能。该框架能够以可扩展且成本效益的方式来实现这一目标，并提供了一种新的模型评估方法，进一步推动了通用交互代理的发展。
## 29. `cs.AI` - WebChain：真实的网络交互轨迹的大规模人工注释数据集 [PDF](https://arxiv.org/pdf/2603.05295), [HTML](https://arxiv.org/abs/2603.05295)
### Authors
Sicheng Fan,Rui Wan,Yifei Leng,Gaoning Liang,Li Ling,Yanyi Shang,Dehan Kong
### Background
当前的研究在可重复性方面有所欠缺，特别是在网络代理领域。现有的合成方法在覆盖复杂的、高价值的任务时存在不足。WebChain填补了这一空白，提供了最大规模的、经过人工标注的真实网站行为数据集，加速了网络代理领域的可重复研究。
### Innovation
WebChain提出了一个双阶段中间训练方法（Dual Mid-Training recipe），将空间定位与规划分离，从而在所提出的WebChainBench和其他公共GUI基准测试中达到了最新的性能。此外，WebChain通过了一个可扩展的数据收集流程，确保了对合成方法通常忽略的复杂任务的覆盖。
### Conclusion
本研究提供了数据和见解，以构建和严格评估新的可扩展网络代理，同时也强调了真实世界的网站行为数据集对于提高研究质量的重要性。
## 30. `cs.AI` - 自适应领域模型：几何和神经形态AI的贝叶斯演化、暖旋转和原则性训练 [PDF](https://arxiv.org/pdf/2603.18104), [HTML](https://arxiv.org/abs/2603.18104)
### Authors
Houston Haynes
### Background
现有的AI训练基础设施基于反向模式自动微分和IEEE-754算术，这导致了训练过程中与推理相比的内存开销、优化器复杂度增加以及几何性质的结构性退化。该论文提出了一个基于三种先前成果的替代训练架构：维度类型系统和确定性内存管理框架，确保栈兼容的梯度分配和精确的可用积算；程序超图，通过几何代数计算保持等级不变；以及b-posit 2026标准，使置位算术在通常只用于推理的硬件目标上可实现。这三种技术的综合应用，使得深度独立的训练内存消耗大约是推理占用的两倍，保持权重更新的等级一致，以及精确的梯度累积，适用于损失函数优化和时序依赖神经形态模型。
### Innovation
该论文开发了一种替代的训练架构，基于维度类型系统和确定性内存管理框架、形状超图和b-posit 2026标准，通过这种方式实现了深度无关的训练内存限制，权重更新保持等级一致，并且梯度累加精确，这些特性适用于损失函数优化和时序依赖神经形态模型。此外，还引入了贝叶斯蒸馏机制，可通过ADM训练阶段抽取通用模型的隐含先验结构，解决了特定领域训练的数据稀缺性问题。还引入了暖旋转机制，使得在不中断服务的情况下，更新后的模型可以准备好进行服务。
### Conclusion
这种自适应领域模型比通用模型更小且更精确，具有持续适应性，相对于其领域的物理结构是验证正确的，并且可以从现有模型初始配置，最终形成了一类系统，这些系统具有用于几何和神经形态AI的小型化和精确性、连续适应能力，并且与领域物理结构一致正确可验证。
## 31. `cs.AI` - FaCT: Faithful Concept Traces for Explaining Neural Network Decisions [PDF](https://arxiv.org/pdf/2510.25512), [HTML](https://arxiv.org/abs/2510.25512)
### Authors
Amin Parchami-Araghi,Sukrut Rao,Jonas Fischer,Bernt Schiele
### Background
深度神经网络在多种任务中表现出卓越的性能，但仍难以获得对其工作原理的高层次理解。虽然引出了许多基于概念的后验解释方法，但它们往往对模型不够忠实，并且对模型学习的概念作出限制性的假设，如类别特异性、小空间范围或与人类期望对齐。
### Innovation
本文强调基于概念解释的忠实性，并提出了一种具有模型内在机制的概念解释的新模型。该模型的概念在类别间共享，并且可以准确追溯其对输出分数和输入视图的贡献。此外，利用基础模型提出了概念一致性度量C$^2$-Score，用于评估基于概念的方法。研究表明，与先前工作相比，所提供的概念在定量上更一致，用户也认为这些概念更具解释性，同时保持了与ImageNet竞争的性能。
### Conclusion
相比于先前的工作，本文提供的概念在定量上更一致，用户觉得这些概念更易解释，同时保持了与ImageNet竞争的性能。
## 32. `cs.AI` - Turbo-DDCM: 快速且灵活的零样本扩散基础图像压缩 [PDF](https://arxiv.org/pdf/2511.06424), [HTML](https://arxiv.org/abs/2511.06424)
### Authors
Amit Vaisman,Guy Ohayon,Hila Manor,Michael Elad,Tomer Michaeli
### Background
尽管近年来零样本扩散为基础的压缩方法取得了显著进展，但它们仍然非常缓慢且计算量大。该论文提出了一种高效且显著比现有方法更快的零样本扩散为基础的压缩方法，同时保持与最先进的技术相当的性能。
### Innovation
该方法基于最近提出的Denoising Diffusion Codebook Models (DDCMs)压缩方案。Turbo-DDCM通过在每次去噪步骤中高效地结合大量噪声向量显著减少了所需的去噪操作次数。此外，引入了两种灵活的Turbo-DDCM变种：一种是优先级感知变种，优先压缩用户指定的区域；另一种是失真控制变种，基于目标PSNR而不是目标比特率压缩图像。
### Conclusion
全面的实验表明，Turbo-DDCM是一种具有竞争力、实用且灵活的图像压缩方案。
## 33. `cs.AI` - 关于模糊请求的推理 [PDF](https://arxiv.org/pdf/2511.10453), [HTML](https://arxiv.org/abs/2511.10453)
### Authors
Irina Saparina,Mirella Lapata
### Background
大语言模型在处理含糊不清的请求时，通常会隐含地倾向于一种解释，这会令用户不满，也可能带来安全风险。尤其是当这种隐含的解释是错误的时候。
### Innovation
提出了生成一个结构化的单一回应，该回应列举了模糊请求的不同解释方式，并附带相应的答案。这种方法使用双重奖励目标进行训练：在面对含糊不清的输入时最大化有效解释的覆盖面，在处理明确的输入时减少错误的替代解释。训练仅需每个输入对应多个有效答案作为监督，无需澄清问题或显式解释。实验表明，该方法在对话式问题回答和语义解析任务中相比基线方法能提供更高的有效答案覆盖率。人工评估表明预测的解释是具有意义的，并能解释相应答案。这种方法通过明确的解释提高了透明度，通过仅需一次生成步骤节省了效率，并通过结构化输出支持下游应用。
### Conclusion
我们的方法通过明确提出各种解释，提供了高透明度；仅一步生成步骤保证了高效性；结构化的输出促进了下游应用。实验展示了我们的方法在处理含糊请求方面取得了显著进展。
## 34. `cs.AI` - GeoPl@ntNet：探索关键生物多样性变量的平台 [PDF](https://arxiv.org/pdf/2511.13790), [HTML](https://arxiv.org/abs/2511.13790)
### Authors
Lukas Picek,César Leblanc,Alexis Joly,Pierre Bonnet,Rémi Palard,Maximilien Servajean
### Background
本文描述了GeoPl@ntNet，这是一个交互式的网络应用程序，旨在通过动态地图和事实手册使关键生物多样性变量对每个人都能够访问和理解。该平台的核心用途是让用户探索高分辨率的人工智能生成的物种分布、栖息地类型和生物多样性指标的欧洲地图。
### Innovation
这类地图是通过涉及卷积神经网络和大型语言模型的递归流水线开发的，提供了一个直观但信息丰富的界面，以更好地理解生物多样性，空间分辨率可达50x50米。网站还允许用户探索特定区域，选定地图上的感兴趣区域（如城市绿地、保护区或河岸），查看当地的物种及其覆盖率。此外，GeoPl@ntNet还为选定的地区生成全面报告，包括有关受保护物种、入侵物种和特有种群的信息。
### Conclusion
综上所述，GeoPl@ntNet为用户提供了探索关键生物多样性变量的工具，使生物多样性数据更加易于访问和理解，从而促进生物多样性保护和研究。
## 35. `cs.AI` - CropVLM：学习缩放以提高细粒度的视觉语言感知 [PDF](https://arxiv.org/pdf/2511.19820), [HTML](https://arxiv.org/abs/2511.19820)
### Authors
Miguel Carvalho,Helder Dias,Bruno Martins
### Background
视觉语言模型（VLMs）在需要精细图像理解的任务，如场景文本识别或文档分析，常常表现不佳，这是由于感知限制和视觉碎片化造成的。
### Innovation
提出了CropVLM作为一种外部低成本方法，以提高模型性能。CropVLM使用强化学习进行训练，不需要使用带有标签的人工边界框作为监督信号，也不需要昂贵的合成评估。该模型可以与开源和专有VLM配对以改善其性能，且无需修改或微调基模型，从而避免了灾难性遗忘。
### Conclusion
在需要高分辨率图像理解的任务中取得了显著的改进，特别对于目标VLM的域外基准测试中效果显著，而无需对VLM进行修改或微调。
## 36. `cs.AI` - HiFiNet: 无线传感器网络中基于边缘分类和图聚合的分层故障识别 [PDF](https://arxiv.org/pdf/2511.17537), [HTML](https://arxiv.org/abs/2511.17537)
### Authors
Nguyen Tri Nghia,Nguyen Van Son,Nguyen Thi Hanh
### Background
无线传感器网络（WSN）是关键监控应用的基础，但在不利条件下部署会增加数据完整性和系统可靠性的风险。传统故障检测方法难以在准确性和能耗之间取得平衡，且可能未能充分利用WSN数据中存在的复杂时空相关性。
### Innovation
提出了一种新的分层故障识别框架HiFiNet，通过两阶段过程解决这些挑战。首先，边缘分类器使用长短期记忆（LSTM）堆叠自编码器进行时间特征提取，并输出初始故障类别预测。接着，图注意网络（GAT）利用邻接节点信息进行信息聚合，整合拓扑上下文以细化分类。这种方法通过捕捉局部时间模式和网络范围的空间依赖性，能够提供更准确的预测。
### Conclusion
通过在Intel Lab Dataset和NASA的MERRA-2再分析数据中引入特定预定义故障构建合成WSN数据集进行验证，实验结果表明HiFiNet在准确性、F1分数和召回率方面显著优于现有方法，并展示了其在识别多样故障类型方面的稳健性和有效性。此外，该框架的设计允许在诊断性能和能耗之间进行可调衡，使其能够适应不同的运行要求。
## 37. `cs.AI` - Did苹果坠落：评估大模型中的好奇心 [PDF](https://arxiv.org/pdf/2510.20635), [HTML](https://arxiv.org/abs/2510.20635)
### Authors
Haoyu Wang,Sihang Jiang,Yuyan Chen,Xiaojun Meng,Jiansheng Wei,Yitong Wang,Yanghua Xiao
### Background
近年来，自然语言处理技术模型（LMs)的发展引发了关于这些模型是否具有类似人类的好奇心驱动学习能力的讨论。。这些讨论表明，某些LMs可能表现出强烈的知识求知识的需求,，但是它们在面对不确定性环境时倾向于保守的选择。这些研究表明LMs可能具备类似于人类的好奇心潜力
### Innovation
本研究通过借鉴人类好奇心评估问卷修订五维好奇心量表(5DCR)构建了一个全面的好奇心评估框架，评估了LMS在信息探索、刺激寻求和社交好奇心方面的表现degrees研究发现LMs具有强烈的学习渴望同时在不确定环境中倾向于保守决策
### Conclusion
本研究确认了LMS具有类似于人类的好奇心潜力可以增强增强其学习能力和促进创新这为进一步研发LMS的学习能力提供了实验证据
## 38. `cs.AI` - BINDER：基于开放词汇命令的即时适应性移动操作 [PDF](https://arxiv.org/pdf/2511.22364), [HTML](https://arxiv.org/abs/2511.22364)
### Authors
Seongwon Cho,Daechul Ahn,Donghyun Shin,Hyeonbeom Choi,San Kim,Jonghyun Choi
### Background
开放词汇移动操作（OVMM）要求机器人遵循语言指令进行导航和操作，同时在动态环境变化下更新其世界认知。然而，大多数先前提到的方法仅在导航目标、航点或操作步骤结束时进行世界认知更新，使得机器人在两次更新之间处于盲区，导致遗漏物体、错误发现延迟和重规划延迟等连锁失败。
### Innovation
提出了BINDER（衔接即时与策略性推理）框架，这是一种双过程框架，将策略规划与持续环境监控脱钩。具体来说，BINDER集成了一个任务规划的多模态LLM（Deliberative Response Module）和一个不间断监测的视频LLM（Instant Response Module）。这两个模块互补：Deliberative Response Module 进行策略性规划并指导即时响应模块的关注点，而即时响应模块分析视频流以更新记忆、纠正正在进行的操作并在必要时触发重规划。通过这种双向协调，模块在维护意识和避免付出高昂的更新成本之间达到平衡，使机器人在动态条件下具有较强的适应能力。
### Conclusion
BINDER在三个具有动态物体放置的现实环境下进行了评估，结果显示其成功率和效率显著高于现有最佳基线，证明了其在现实世界部署中的有效性。
## 39. `cs.CV` - 全在一个：统一的合成数据管道在多模态视频理解中的应用 [PDF](https://arxiv.org/pdf/2604.12335), [HTML](https://arxiv.org/abs/2604.12335)
### Authors
Tanzila Rahman,Renjie Liao,Leonid Sigal
### Background
训练多模态大型语言模型（MLLMs）以理解视频需要大量跨任务的标注数据，包括对象计数、问答（Q&A）和分割。但在真实世界中收集和标注多模态视频数据成本高、耗时长，并且在多样性和覆盖范围上存在局限。
### Innovation
提出了一种统一的合成数据生成管道，能够自动生成无限制的丰富多样化的多模态视频数据。该框架支持单个管道内多种任务格式，可以实现跨任务的大规模和一致的数据生成。为了进一步增强推理能力，引入了一种基于VQA的微调策略，训练模型理解和回答关于视频内容的结构化问题，而非仅依赖于字幕或简单的指令。这种形式促进了对视觉内容的深入理解和推理。
### Conclusion
在视频对象计数、基于视频的视觉问答以及视频对象分割三个挑战任务中的实验结果表明，主要基于合成数据训练的模型对真实世界数据集具有良好的泛化能力，通常优于传统方法训练的模型。我们的研究结果突显了统一的合成数据管道作为多模态视频理解领域经济高效的替代方案的潜力。
## 40. `cs.CV` - 在微宏观差距上架起桥梁：频率感知语义对齐的图像篡改定位 [PDF](https://arxiv.org/pdf/2604.12341), [HTML](https://arxiv.org/abs/2604.12341)
### Authors
Xiaojie Liang,Zhimin Chen,Ziqi Sheng,Wei Lu
### Background
随着生成图像编辑的进步，图像篡改定位（IML）必须处理具有明显法证痕迹的传统篡改以及看起来局部真实的扩散生成编辑。现有的方法通常依赖于低级法证线索或高级语义单独，导致微观与宏观之间存在根本性差距。
### Innovation
提出了一种统一框架FASA，用于定位传统和扩散生成的篡改。FASA通过可适应的双频段DCT模块提取篡改敏感的频率线索，并通过冻结CLIP表示的切片级别对比对齐学习篡改感知的语义先验。然后，通过语义-频率旁路适配器将这些先验注入分层频率路径，促进多尺度特征交互，并使用原型导向、频率门控的掩码解码器将语义一致性与边界感知定位相结合进行篡改区域预测。
### Conclusion
在OpenSDI和多个传统篡改基准上进行的广泛实验展示了FASA在定位性能、跨生成器和跨数据集泛化及在常见图像降级下的稳健性能上的最先进的表现。
## 41. `cs.CV` - 在第一人称视频中检测精确的手触时刻 [PDF](https://arxiv.org/pdf/2604.12343), [HTML](https://arxiv.org/abs/2604.12343)
### Authors
Huy Anh Nguyen,Feras Dayoub,Minh Hoai
### Background
本文处理的是在自行记录视频中检测手指与物体接触的精确时刻这一具有挑战性的任务。这种帧级别的检测对于增强现实、人机交互、辅助技术和机器人学习等应用至关重要，因为接触开始或结束的信号标志着动作的启动或完成。然而，检测时精确性尤其困难，因为接触附近的手部运动细微变化、频繁遮挡、精细的操作模式以及第一人称视角固有的运动动态给该任务带来了挑战。
### Innovation
为了应对这些挑战，本文提出了一种名为Hand-informed Context Enhanced (HiCE) 的模块，利用手部区域及其周围上下文的时空特征通过交叉注意力机制进行信息融合，学习识别潜在的接触模式。此外，本文引入了TouchMoment数据集，包含4021个视频和8456个标注的接触时刻，跨越超过一百万帧。通过使用这种带有抓取意识的损失和软标签的方法，本文的方法在严格的评估标准下（准确率仅在地面真相时刻两帧范围内的预测才被视为正确）显著提升了性能，并且在现有的视频事件检测基准上平均精确率提高了16.91%。
### Conclusion
实验结果表明，使用严格的评估标准（准确率仅在地面真相时刻两帧范围内的预测才被视为正确），本文的方法在TouchMoment数据集上取得了显著的性能提升，并在最先进的事件检测基准上平均精确率比现有方法高出16.91%。此外，所提出的方法还能够区分接近接触和实际接触的帧，从而验证了它在第一人称视角视频中的接触检测能力。
## 42. `cs.CV` - OmniFood8K：通过层次频率对齐融合的单图营养估计算法 [PDF](https://arxiv.org/pdf/2604.12356), [HTML](https://arxiv.org/abs/2604.12356)
### Authors
Dongjian Yu,Weiqing Min,Qian Jiang,Xing Lin,Xin Jin,Shuqiang Jiang
### Background
准确的食物营养估算对于促进健康饮食习惯和个性化饮食管理至关重要。大多数现有的食物数据集主要专注于西方菜肴，并缺乏中国菜肴的充分覆盖，这限制了对中式餐食的准确营养估算。此外，许多最先进的营养预测方法依赖于深度传感器，这限制了它们在日常场景中的适用性。
### Innovation
本研究介绍了OmniFood8K，这是一个综合多模态数据集，包含8,036个食品样本，每个样本都有详细的营养注释和多视角图像。此外，为了增强模型在营养预测方面的性能，作者构建了NutritionSynth-115K，这是一个大型合成数据集，引入了成分变化并保持精确的营养标签。提出了一个端到端框架，用于从单张RGB图像预测营养成分。框架包括预测深度图、精细度调整残差适配器（SSRA）、频率对齐融合模块（FAFM）和基于掩码的预测头部（MPH）。实验结果表明该方法优于现有方法。
### Conclusion
我们的方法在多个数据集上的实验中表现出了优越性。
## 43. `cs.CV` - Combating Pattern and Content Bias: AdnArtificial Feature Learning for Generalized AI-Generated Image Detection [PDF](https://arxiv.org/pdf/2604.12353), [HTML](https://arxiv.org/abs/2604.12353)
### Authors
Haifeng Zhang,Qinghui He,Xiuli Bi,Bo Liu,Chi-Man Pun,Bin Xiao
### Background
近年来，， Pelosi 璡生成型人工智能技术飞速发展，，使已大幅降低了了创造高质量伪造图像的门槛，,ーム面临的真伪性性和可信度的挑战。。。已经超过现有的生成图像检测方法通常依赖于模型结构和或者图像网络以便提升普适性上其中存在的问题表现在训练数据可能驱动模型适应特定生成模式和 并不具备广泛的普适特征的能力上.
### Innovation
本文提出了一种多维度对抗特征学习(MMAFL）框架。。该框架采用预训练多跨模态图像编码器作为特征抽取主体构建真实与伪造特征学习网络，并设计了一个多维度对抗损失装置带有对抗训练机制的特征学习策略上。对抗效果区分特征学习和 与偏见特征学习之间的这种对抗机制 抑制了生成模式及内容偏见 MAFL 弇导模型聚焦于生成模型的特征特点上.,从而有效地突显了真实和生成图像之间的基本差异 通过提升交叉模型普适性和并实际降低对训练数据的依赖.
### Conclusion
通过广泛的验证实验验证了该方法在准确性和平均查全率 （AP） 上的表现更优上比比方法均表现优于现有先进方法 甚至仅使用 300对应的检出精度也能也达到了类似 80 %%检测准确度.
## 44. `cs.CV` - LoViF 2026 The First Challenge on Weather Removal in Videos [PDF](https://arxiv.org/pdf/2604.10655), [HTML](https://arxiv.org/abs/2604.10655)
### Authors
Chenghao Qian,Xin Li,Yeying Jin,Shangguan Sun,Yilian Zhong,Yuxiang Chen,Shibo Yin,Yushun Fang,Xilei Zhu,Yahui Wang,Chen Lu,Ying Fu,Jianan Tian,Jifan Zhang,Chen Zhou,Junyang Jiang,Yuping Sun,Zhuohang Shi,Xiaojing Liu,Jiao Liu,Yatong Zhou,Shuai Liu,Qiang Deng,Jiajia Mi,Qianhao Luo,Weiling Li
### Background
该论文介绍了LoViF 2026视频去 weather 挑战赛，旨在通过恢复被恶劣天气（如雨雪）影响的不清晰视频，推动去 weather 技术的发展。挑战重点关注生成视觉上可信且时间连续的结果，同时保留场景结构和运动动态。
### Innovation
研究提出了一个名为WRV的新数据集，专门用于视频去 weather 处理。该数据集包含18个视频，每个视频的1216张合成帧与1216张真实地truth帧配对，分辨率832 x 480。数据集分为训练、验证和测试集，比例为1:1:1。挑战通过综合考虑保真度和感知质量对结果进行评估。
### Conclusion
该挑战吸引了37个参与者，并收到了5个有效最终提交，这对于视频中 weather 消除技术的发展起到了积极作用。所有项目都可以在 this https URL 公开访问。
## 45. `cs.CV` - CoFusion：通过光谱坐标注意力实现多光谱和高光谱图像融合 [PDF](https://arxiv.org/pdf/2604.10584), [HTML](https://arxiv.org/abs/2604.10584)
### Authors
Baisong Li
### Background
多光谱（MS）和高光谱（HS）图像融合（MHIF）的目标是通过融合低分辨率高光谱图像（LRHSI）和高分辨率多光谱图像（HRMSI）来重建高分辨率图像。现有方法在建模跨尺度交互和空间光谱协作方面存在局限性，导致难以在空间细节增强和光谱保真之间达到最优权衡。
### Innovation
提出了一个统一的空间光谱协作融合框架CoFusion，明确建模了跨尺度和跨模态的依赖关系。设计了多尺度生成器（MSG）构建三层金字塔架构，以有效融合全局语义和局部细节。每个尺度内采用双分支策略，分别使用空间坐标意识混合模块（SpaCAM）捕捉多尺度空间上下文，使用光谱坐标意识混合模块（SpeCAM）通过频域分解和坐标混合增强光谱表示。此外，引入了空间光谱交叉融合模块（SSCFM）以进行动态跨模态对齐和互补特征融合。
### Conclusion
在多个基准数据集上的广泛实验表明，CoFusion在空间重建和光谱一致性的性能上始终优于现有最先进的方法。
## 46. `cs.CV` - ReXsonoVQA: 视频问答基准数据集用于以程序为中心的超声理解 [PDF](https://arxiv.org/pdf/2604.10916), [HTML](https://arxiv.org/abs/2604.10916)
### Authors
Xucheng Wang,Xiaoman Zhang,Sung Eun Kim,Ankit Pal,Pranav Rajpurkar
### Background
在获取 躬过程中，，，所需的手动操控和实时调整技术导致人为错误和不一致性的增加。。。问题。在这种背景下，由于成像获取技术导致的人为错误和不一致性的存在，个人观点认为主要通过视觉语言模型（VLMs) 可以实现自主超声系统，但是，但是由于现有的基准测试仅评估静态图像理解能力，本研究聚焦的是动态过程理解能力的评估。为解决这一问题地点介绍了 ReXSonoVQA 这一视频问答基准数据集。
### Innovation
ReXSonoVQA 提供了一个涉及 514 个视频片段和 514 道问题 (24 道项选择选择题 2265 自由答复) 的基准数据集，该数据集旨在提高三个技能：“目标推理”、“故障和优化”和 和程序上下文和 计划”。针对现有的 VLMs (比如 Gemini 3 Pro、Qwen3.5-37B、、 LLaVA-Video-7B 和 Seed 0.2) 的零样本评估发现它们在提取程序了解和解决故障方面取得了一些进展,但是部分回答则题依然存在挑战和这些挑战显示了因果推理方面的局限性。ReXSonoVQA 的引入为开发感知系统用于超声培训、指导和机器人自动化提供了一个新的途径。
### Conclusion
ReXSonoVQA 为以程序为中心的超声理解提供了一个一个全新的的基准数据集。,。，它在视频问答格式中包含的各种复杂场景和在这样一个方式集中包含三个关键能力：该数据集的引入对于促进机器理解和自主能力的进步至关重要
## 47. `cs.CV` - 通过_distillation-assisted_测试时适应_自 Bootstrap 视频语义分割模型 [PDF](https://arxiv.org/pdf/2604.10950), [HTML](https://arxiv.org/abs/2604.10950)
### Authors
Jihun Kim,Hoyong Kwon,Hyeokjun Kweon,Kuk-Jin Yoon
### Background
全监督视频语义分割（VSS）依赖密集标注的视频数据，限制了其实用性；而逐帧应用预训练图像语义分割（ISS）模型可以避免标注成本，但忽略时间连贯性；基于SAM2的骨干模型可以实现高质量的掩膜传播，但由于语义理解和计算开销的局限，不适合直接用于VSS。
### Innovation
提出了DiTTA（Distillation-assisted Test-Time Adaptation）新型框架，该框架通过高效测试时适应（TTA）将ISS模型转换为具有时间感知能力的VSS模型，无需使用标注视频。DiTTA通过学习SAM2的时间分割知识，在短暂的一次性初始化阶段将这些知识传递给ISS模型，并通过轻量级时间融合模块整合跨帧上下文。即使在使用高度有限的初始视频片段（例如，前10%）进行适应时，DiTTA也能实现稳健泛化，显著优于连续调用SAM2的零样本改进方法。
### Conclusion
在VSPW和Cityscapes上的大量实验表明，DiTTA的有效性，其性能与完全监督的VSS方法相竞争或更优，从而提供了一种实用的、无需标注的VSS解决方案，满足真实世界VSS任务的需求。
## 48. `cs.CV` - ArtiCAD: 多智能体代码生成的 articulated CAD 装配设计 [PDF](https://arxiv.org/pdf/2604.10992), [HTML](https://arxiv.org/abs/2604.10992)
### Authors
Yuan Shui,Yandong Guan,Zhanwei Zhang,Juncheng Hu,Jing Zhang,Dong Xu,Qian Yu
### Background
参数化计算机辅助设计（CAD）对于产品开发至关重要，但从高层次描述生成这些多部件、可移动的模型仍是一个未被探索的问题。ArtiCAD 旨在解决这一挑战。
### Innovation
ArtiCAD 是首个无需训练的多智能体系统，能够直接从文本或图像生成可编辑的 articulated CAD 组件。它通过设计阶段预测装配关系，利用 Connector 明确定义连接点和关节参数来确定这些关系，从而避免了当前 LLMs 和 VLMs 的空间推理限制。ArtiCAD 还引入了生成和装配阶段的验证步骤，并配有跨阶段回滚机制，以准确隔离和纠正设计和代码级别的错误。此外，它还有一个自我进化的体验库，不断累积设计知识以提升未来任务的性能。
### Conclusion
通过在三个数据集（ArtiCAD-Bench、CADPrompt 和 ACD）上的广泛评估，证实了 ArtiCAD 方法的有效性。还展示了 ArtiCAD 在需求驱动的概念设计、物理原型制作以及生成具身 AI 训练资源方面的应用潜力。
## 49. `cs.LG` - 超越天气相关性：在澳大利亚墨尔本精细化住宅能源消耗预测中静态与时空神经架构的比较研究 [PDF](https://arxiv.org/pdf/2604.12304), [HTML](https://arxiv.org/abs/2604.12304)
### Authors
Prasad Nimantha Madusanka Ukwatta Hewage,Hao Wu
### Background
在智能电网管理、需求响应计划以及可再生能源集成方面，准确的小时尺度住宅能源消耗预测至关重要。尽管天气变量被广泛认为是住宅电力需求的关键驱动因素，但在澳大利亚家庭的精细时间尺度（如5分钟）上，将时间自相关性（即过去消费的顺序记忆）与静态气象特征结合起来的效果尚未得到充分研究。本文对比了多层感知机（MLP）和长短期记忆（LSTM）循环网络在两个真实的墨尔本家庭中的应用。
### Innovation
本文首次在5分钟的粒度上对比了MLP和LSTM在精细化住宅能源消耗预测中的效果。重点在于时间和自相关性的重要性以及它们如何影响预测性能，特别是在整合了太阳能发电的家庭中。研究发现，LSTM在考虑时间窗口时表现出明显优于MLP的效果。
### Conclusion
研究结果表明，时间和序列的相关性在短期5分钟预测中占据主导地位，超越了天气信息。此外，研究还揭示了太阳能发电引入的非对称影响。未来的工作方向包括混合天气增强LSTM和联邦学习扩展。
## 50. `cs.LG` - 在学术推荐信中识别并缓解性别暗示：一个可解释性案例研究 [PDF](https://arxiv.org/pdf/2604.12337), [HTML](https://arxiv.org/abs/2604.12337)
### Authors
Charlotte S. Alexander,Shane Storks,Souradip Pal,Sayak Chakrabarty,Arushi Sharma,Mlen-Too Wesley,Bailey Russo
### Background
推荐信（LoR）可能携带隐含的性别化语言模式，这些语言可能无意中影响后续的决策过程，例如招聘和录取。本研究旨在探索基于Transformer的编码器模型及大型语言模型（LLMs）在去除了姓名和代词等显式标识符后的学术LoR中推断申请人性别的能力。
### Innovation
研究使用三种模型（DistilBERT、RoBERTa和Llama 2）对匿名和去性别化的LoR进行性别分类，结果显示存在显著的性别偏见。通过文本解释方法（如TF-IDF和SHAP），研究发现了某些语言模式是性别的重要替代指标。进行实验以创建真正无性别的LoR，结果显示尽管保密性和宏观F1分数有所下降，但仍能预判申请人性别。
### Conclusion
研究发现，LoR中包含难以移除的性别识别线索，这可能在决策中激活偏见。该技术框架是公平学术和专业评估中的一个重要步骤，但未来工作仍需探讨性别在LoR评审中的角色。研究结果强调需要在真实世界中的学术推荐信中进行上游审核，作为模型公平干预的必要补充。
## 51. `cs.LG` - 基于大型语言模型的可控分子优化——基于骨架条件的偏好三元组 [PDF](https://arxiv.org/pdf/2604.12350), [HTML](https://arxiv.org/abs/2604.12350)
### Authors
Yi Xiong,Liang Xiong,Xiaohong Ji,Sen Yang,Zhifeng Gao,Huaimin Wang,Kele Xu
### Background
分子性质优化在药物发现中至关重要，但许多深度学习方法依赖于黑箱评分，难以控制骨架保护，经常产生不稳定或生物学上不可行的修改。尽管大型语言模型（LLMs）是分子生成的有前途工具，但优化仍受限于缺乏化学导向的偏好监督和合理的数据管理。
### Innovation
介绍了基于骨架条件的偏好三元组（SCPT），通过骨架对齐和基于化学的过滤器构建相似性约束三元组 <骨架, 更好, 较差>，以有效指导大型语言模型进行属性改进的编辑，保持骨架结构。与竞品基线相比，SCPT 在单目标和多目标基准测试中提高了优化成功率和属性改善，同时保持更高的骨架相似性。通过单一属性和二元属性监督训练的模型能够有效泛化到三属性任务，表明在有限高级监督下具有良好的外推泛化能力。SCPT 还提供了可控的数据构建调节工具，可以预测相似性改进前沿，从而系统地适应不同的优化环境。
### Conclusion
SCPT 训练的大型语言模型在骨架约束和多目标优化方面更适合，且能有效处理复杂属性任务，显示出受限制高级监督下的外推泛化潜能。
## 52. `cs.LG` - Nemotron 3 Super: 开放、高效混合Mamba-Transformer模型，具备智能推理能力 [PDF](https://arxiv.org/pdf/2604.12374), [HTML](https://arxiv.org/abs/2604.12374)
### Authors
NVIDIA:Aakshita Chandiramani,Aaron Blakeman,Abdullahi Olaoye,Abhibha Gupta,Abhilash Somasamudramath,Abhinav Khattar,Adeola Adesoba,Adi Renduchintala,Adil Asif,Aditya Agrawal,Aditya Vavre,Ahmad Kiswani,Aishwarya Padmakumar,Ajay Hotchandani,Akanksha Shukla,Akhiad Bercovich,Aleksander Ficek,Aleksandr Shaposhnikov,Alex Gronskiy,Alex Kondratenko,Alex Neefus,Alex Steiner,Alex Yang,Alexander Bukharin,Alexander Young,Ali Hatamizadeh,Ali Taghibakhshi,Alina Galiautdinova,Alisa Liu,Alok Kumar,Ameya Sunil Mahabaleshwarkar,Amir Klein,Amit Zuker,Amnon Geifman,Anahita Bhiwandiwalla,Ananth Subramaniam,Andrew Tao,Anjaney Shrivastava,Anjulie Agrusa,Ankur Srivastava,Ankur Verma,Ann Guan,Anna Shors,Annamalai Chockalingam,Anubhav Mandarwal,Aparnaa Ramani,Arham Mehta,Arti Jain,Arun Venkatesan,Asha Anoosheh,Ashwath Aithal,Ashwin Poojary,Asif Ahamed,Asit Mishra,Asli Sabanci Demiroz,Asma Kuriparambil Thekkumpate,Atefeh Sohrabizadeh,Avinash Kaur,Ayush Dattagupta,Barath Subramaniam Anandan,Bardiya Sadeghi,Barnaby Simkin,Ben Lanir,Benedikt Schifferer,Benjamin Chislett,Besmira Nushi,Bilal Kartal,Bill Thiede,Bita Darvish Rouhani,Bobby Chen,Boris Ginsburg,Brandon Norick,Branislav Kisacanin,Brian Yu,Bryan Catanzaro,Buvaneswari Mani,Carlo del Mundo,Chankyu Lee,Chanran Kim,Chantal Hwang,Chao Ni,Charles Wang,Charlie Truong,Cheng-Ping Hsieh,Chenhan Yu,Chenjie Luo,Cherie Wang,Chetan Mungekar,Chintan Patel,Chris Alexiuk,Chris Holguin,Chris Wing,Christian Munley,Christopher Parisien,Chuck Desai,Chunyang Sheng,Collin Neale,Cyril Meurillon,Dakshi Kumar
### Background
本文描述了Nemotron 3 Super模型的预训练、后训练以及量化过程。Nemotron 3 Super是一个1200亿参数（其中激活参数为12亿）的混合Mamba-Attention Mixture-of-Experts模型。它是Nemotron 3家族中第一个在NVFP4中进行预训练，并采用了LatentMoE这一新型混合专家架构以在每FLOP和每参数的精度之间进行优化，同时还包含MTP层以通过原生推测解码进行推理加速的模型。
### Innovation
1) 模型首次在NVFP4中进行了预训练；2) 引入了LatentMoE新型混合专家架构，同时优化了每FLOP和每参数的精度；3) 包含MTP层以加速推理过程。
### Conclusion
最终模型支持多达1百万的上下文长度，同时在常见的基准测试中与GPT-OSS-120B和Qwen3.5-122B相比具有2.2倍和7.5倍的更高的推理吞吐量。同时，该模型及其训练后和量化的检查点已经开源在HuggingFace上。
## 53. `cs.LG` - Parcae: 稳定循环语言模型的可扩展性法则 [PDF](https://arxiv.org/pdf/2604.12946), [HTML](https://arxiv.org/abs/2604.12946)
### Authors
Hayden Prairie,Zachary Novack,Taylor Berg-Kirkpatrick,Daniel Y. Fu
### Background
传统的固定深度架构通过增加训练计算量（FLOPs）来提高模型质量，这通常意味着参数增加，但会增加内存足迹或数据要求。另一种选择是循环架构，它们通过使激活信号在一层块中循环来增加计算量。然而，当前训练循环架构的方法可能不稳定，容易出现残差爆炸和损失上升等问题。
### Innovation
本文通过将循环视为残差流的非线性时变动态系统，分析并解决了现有循环架构的不稳定性问题。提出了一种名为Parcae的新型稳定循环架构，通过负对角参数化离散化来限制注入参数的谱范数，实现较大的FLOPs增长同时保持固定的参数量。这种架构在验证困惑度上优于之前的大型循环模型。作者还推导出了循环训练时和测试时的可预测幂律，并发现可以通过增加循环和数据来提高模型质量，同时保持固定的FLOP预算。
### Conclusion
通过使用Parcae架构，作者在1.3B参数下实现了相对于大型Transformer基准模型的质量提升，尤其是在固定参数和数据预算的情况下。这表明循环可以作为一种有效的方法来提高模型性能，特别是在测试时随着计算的增长呈现出可预测的饱和指数衰减。
## 54. `cs.LG` - 重新思考大型语言模型的在线政策蒸馏：现象，机制和食谱 [PDF](https://arxiv.org/pdf/2604.13016), [HTML](https://arxiv.org/abs/2604.13016)
### Authors
Yaxuan Li,Yuxin Zuo,Bingxiang He,Jinqian Zhang,Chaojun Xiao,Cheng Qian,Tianyu Yu,Huan-ang Gao,Wenkai Yang,Zhiyuan Liu,Ning Ding
### Background
在线政策蒸馏（OPD）已经成为大规模语言模型后训练的核心技术，但其训练动态尚不清楚。本文对OPD的动态和机制进行了系统的探讨。
### Innovation
研究确定了OPD成功与否的两个条件：（i）学生和教师应具有兼容的思考模式；（ii）即使具备一致的思考模式和更高的评分，教师还需要提供学生在训练过程中未见过的真正新能力。通过弱到强的逆向蒸馏验证了这些发现。在词条层面，表明成功OPD的特征是逐步对在学生访问状态下的高频词条实现对齐，且具有高度集中大部分概率质量（97%-99%）的小共享词语集。文章还提出了两种实用策略来恢复失败的OPD：离政策冷启动和教师对齐的提示选择。同时，研究发现OPD看似密集的词条级奖励的好处是有代价的，提出了其是否能扩展到长期蒸馏的疑问。
### Conclusion
OPD在词级别上的密集奖励可能伴随着扩展到长期蒸馏的挑战；提出了两种策略来解决失败的OPD；进一步研究了OPD机制，揭示了其成功的关键特征。
## 55. `cs.LG` - CLAD: 直接在压缩表示上进行高效日志异常检测 [PDF](https://arxiv.org/pdf/2604.13024), [HTML](https://arxiv.org/abs/2604.13024)
### Authors
Benzhao Tang,Shiyu Yang
### Background
系统日志的快速增长使得流式压缩变得至关重要，但现有的日志异常检测（LAD）方法需要通过完全解压和解析来执行预处理操作，这带来了严重的处理瓶颈。
### Innovation
CLAD是第一个直接在压缩字节流上进行LAD的深度学习框架。它通过利用关键洞察来绕过这些瓶颈：正常日志压缩成有规律的字节模式，而异常则系统地破坏这些模式。为了从不透明的字节中提取这些多尺度偏差，CLAD提出了一种专门构建的架构，结合了扩张卷积字节编码器、混合Transformer和mLSTM以及四向聚合池化。此外，CLAD还采用了两阶段训练策略，即遮蔽预训练和焦点对比微调，以有效地处理严重的类别不平衡问题。
### Conclusion
CLAD在五个数据集上的平均F1分数达到0.9909，并且比最佳基线高出2.72个百分点。它提供了高效准确的解决方案，完全消除了解压和解析的开销，适用于结构化流压缩器，具有较强的普适性。
## 56. `cs.LG` - 训练单电子和单光子随机物理神经网络 [PDF](https://arxiv.org/pdf/2604.10861), [HTML](https://arxiv.org/abs/2604.10861)
### Authors
Tong Dou,Shiro Kumara,Josh Burns,Ethan Sigler,Parth Girdhar,David Petty,Gerard Milburn,Jo Plested,Matt Woolley
### Background
深度学习的计算需求促使研究者探寻替代的计算方法。其中一种方法是物理神经网络（PNNs），即直接通过物理过程进行学习和推理。随机物理神经网络（SPNNs）则是在基础神经元通过随机激活开关的动力学实现时产生的。本文作者提出了两种新的电子和光子随机神经元的实现方法。
### Innovation
论文提出了电子和光子两种新的随机神经元实现。电子实现利用量子点单电子隧穿现象，光子实现则通过单光子源驱动一种模式，通过可控制的分束器式相互作用影响另一种模式。同时，还使用了新模型训练单一隐层随机物理神经网络，并对MNIST手写数字分类进行了各种训练策略的研究。具体来说，该论文通过调整每层的试验次数来控制前向传播的随机性，并在反传过程中使用真实的概率或经验值来评估梯度估计的影响。
### Conclusion
当反传过程中使用经验值时，网络在每层几次试验的条件下，测试准确率超过97%。尽管模型架构简单，但在高噪声和模型不确定性下仍能保持高测试准确率。这些结果证明了随机物理神经网络在深度学习中的潜在应用。
## 57. `cs.LG` - 使用生成式AI设计无机化合物 [PDF](https://arxiv.org/pdf/2604.11827), [HTML](https://arxiv.org/abs/2604.11827)
### Authors
Hannes Kneiding,Lucía Morán-González,Nishamol Kuriakose,Ainara Nova,David Balcells
### Background
化学领域正通过机器学习得到颠覆性变革。不仅加速了虚拟筛选的速度，生成式AI还致力于实现逆向设计，即将化合物到性质的预测模型反向转换为从性质生成化合物。虽然这些方法已应用到有机化学和药物发现中，但对无机化合物的应用仍然存在挑战。
### Innovation
本文分析了如何解决这些挑战，研究涵盖了从分子到晶体，包括过渡金属配合物和微孔材料等多种系统。重点讨论了生成式AI方法如何逐步发展成为涵盖无机化合物全部复杂性的数据表示模型管道，包括它们的化学组成、几何结构、对称性和电子结构。
### Conclusion
未来的研究方向包括标准数据集的建立和合成可行性度量的开发。
## 58. `cs.LG` - M^textback_textascitextbanst?:^textbacktextascitextbanst?: Every Task Deserves Its Own Memory Harness [PDF](https://arxiv.org/pdf/2604.11811), [HTML](https://arxiv.org/abs/2604.11811)
### Authors
Wenbo Pan,Shujie Liu,Xiangyang Zhou,Shiwei Zhang,Wanlu Shi,Mirror Xu,Xiaohua Jia
### Background
现有的大型语言模型 依赖于特定的记忆系统来在交互中 秒累计和重用知识。 兽数和通常采用固定的记忆模型来针对特定的领域，比如在对话中 卞重技能检索,在编程中 重新用用现有系统针对一个任务优化的模型往往难以适应其他任务。这项研究的目标是应对这一限制 提出一种新的方法 -;^textback on?textasc on?textbanst;（让模型能够为每个特定任务自动生成适应的的记忆机制.
### Innovation
1;^textback?^textbanst 引入通过可 觸 叧行程序演化来 on 自 个以 Python 语言编写的在上 的逻辑结构上 卧行和 的工作流程指令；；通过对包含的各个部分分进行联合优化 我们的实现 弤法采用了一种反身性代码演化方法 兔引 上方法利用一种 傤基在线搜索策略并且分析评估失败来逐次迭代适应 on 的候选程序；;;^text on?^textban on 对 在 试验证了一个包含十个不同的基准任务 都盖涉及包裹处理 on 紀 专家级领域的任务；我们得试验结果通验证明了 on^text on?^textban pro 较现有固定的记忆baseline 更加 robust 蛇 评估的任务中；并且在这次演化的程序展示出针对每个具体任务有不同的处理机制 这点 设对^text on?^textban on 为每种特定任务特析他专门的记忆机制比探索了一个宽泛的程序空间并且提供了比相比 通用目的的on 境机制 优越性表现.
### Conclusion
on^text on on?^textbanb on 实现 证明了通过执行 on on 的方法能够为每个特定任务自^text on ontextbanb on 生成给定 的自适应记忆机制 on实现 熔炼出一个更 更广泛的代码池探索空间并且基于此 on 提高了通用性的记忆机制 的效果 on在这层面演示了 on^text on 盋.
## 59. `cs.LG` - FlowBoost揭示有限自由信息不等式的相变和谱结构 [PDF](https://arxiv.org/pdf/2604.11922), [HTML](https://arxiv.org/abs/2604.11922)
### Authors
Baran Hashemi
### Background
本文使用了闭合回路的深度生成优化框架FlowBoost进行研究，以探究基于有限自由可加卷积$boxplus_n$、具有实根的多项式下的$boldsymbol{text{textrm{textup{ell}}}}^p$形式的有限自由Stam不等式。重点探讨了$p=2$时的情况，流推Boost找出了Hermite对作为唯一等式情况，并揭示了线性化卷积映射在该极值点处的谱结构。
### Innovation
引入了一参数族的$boldsymbol{text{textrm{textup{p}}}}$-Stam不等式，并使用$boldsymbol{text{textrm{textup{ell}}}}^p$费希尔信息进行了证明，发现Hermite对在所有$p>2$时不满足这些不等式，不等式违背的程度由$E_n$的$boldsymbol{text{textrm{textup{ell}}}}^p$收缩比决定。通过FlowBoost进行系统性的计算，支持了$p^*boldsymbol{text{textrm{textup{!}}}}=2$为尖锐的临界指数的猜想。进一步分析表明，对于$p<2$的情况，极值配置会发生分岔，即形成非匹配的双模根结构，仅在$pto 2^-$时重新趋向Hermite对角。
### Conclusion
结果表明，FlowBoost在无穷维极值问题中的数学发现方面可作为一个有效的工具。在$p<2$的情况下，极值配对发生分岔并重新趋向Hermite对角，而对于$p>2$的情况，Hermite对违反不等式，具有尖锐的临界指数。
## 60. `cs.LG` - 常数因子近似决策树问题 [PDF](https://arxiv.org/pdf/2604.12036), [HTML](https://arxiv.org/abs/2604.12036)
### Authors
Michał Szyfelbein
### Background
本文解决了平均情况下决策树问题存在常数因子近似算法的一个长期开放问题，特别是在假设均匀概率分布下的情况。
### Innovation
作者通过使用从层次聚类问题中借鉴的分解技术，将最优决策树分解为一系列被称为分离子簇的对象，并将找到分离子簇的子问题简化为最大覆盖问题的实例。这种方法允许找到一个良好的近似解，从而设计出原问题的近似算法。
### Conclusion
本文提出的简单多项式时间算法的近似比为$2/(1-rqsqrt{(e+1)/(2e)})+rqs < 11.57$，这比目前最好的贪婪算法$O(rqslog n/rqslogrqslog rqs n)$的近似比有了显著的改进。
## 61. `cs.LG` - 关于t-SNE数据可视化连续极限的研究 [PDF](https://arxiv.org/pdf/2604.12041), [HTML](https://arxiv.org/abs/2604.12041)
### Authors
Jeff Calder,Zhonggan Huang,Ryan Murray,Adam Pickarski
### Background
t-SNE是一种广泛应用于数据可视化的图基数据可视化技术，尽管它在各种应用中被广泛应用，但其理论方面仍然不甚明确。t-SNE算法通过在高维数据和低维表示之间的相似性矩阵之间最小化Kullback-Leibler散度来生成可视化。
### Innovation
本文证明了随着数据点数量趋向无穷，在适当参数区间内自然尺度后的Kullback-Leibler散度保持一致。同时，相似图保持稀疏，并引入了一个包含非凸梯度正则项和可视化空间中概率密度函数大小惩罚的连续变分问题。还展示了当两个维度均为1时，问题存在唯一平滑最小值及无限多个非连续最小值。这些发现与t-SNE在视图中分离数据的实证观察结果相吻合，同时该能量问题与闻名已久的难以直接求解的Perona-Malik方程密切相关。文章还提供了数值结果以验证连续极限，并在高维情况下提供了关于收敛能量问题的初步结果。
### Conclusion
尽管连续变分问题缺乏凸性，但其正确性仅部分得到解决。同时，当两个维度均为1时，该问题存在唯一平滑最小值及无限多个非连续最小值。此外，该能量问题与Perona-Malik方程密切相关，文章还提供了数值结果以验证连续极限，并对高维情况下能量问题的研究提出了未来的工作计划。
## 62. `cs.LG` - 企业自然语言处理系统中用户信任的稳健解释 [PDF](https://arxiv.org/pdf/2604.12069), [HTML](https://arxiv.org/abs/2604.12069)
### Authors
Guilin Zhang,Kai Zhao,Jeffrey Friedman,Xu Chu,Amine Anoun,Jerry Ting
### Background
随着企业在自然语言处理（NLP）中对稳健解释的需求不断增加，对于用户来说，要在部署前验证这些解释的稳健性存在困难。尤其是当系统部署为黑盒（仅API访问）时，基于表示的解释方法不可行，现有研究在指导实际用户噪声下解释的稳定性方面提供有限的指导，尤其是在组织从编码器分类器迁移至解码器大模型LLM时。
### Innovation
本文提出了一个基于消除法的统一黑盒稳健性评估框架，用于针对多个现实干扰（交换、删除、重新排序和回译）进行词级解释的稳健性评估，这在不同程度的严重性上用最高词编辑率来衡量。此外，通过系统性地在三个基准数据集和六个模型（BERT、RoBERTa、Qwen 7B/14B、Llama 8B/70B）上进行跨架构对比试验，发现解码器大模型在解释方面具有更高的稳定性。
### Conclusion
解码器大模型的解释稳定性明显优于编码器基线模型（平均低73%的切换率），并且稳定性随着模型规模的增加而提高（从7B到70B增加44%的稳定性）。最终，这与推理成本的关系被用来形成一个权衡曲线，使在确保合规性的前提下进行模型和解释选择成为可能。
## 63. `cs.LG` - PipeLive: 动态LLM服务中高效的现场管道并行重新配置 [PDF](https://arxiv.org/pdf/2604.12171), [HTML](https://arxiv.org/abs/2604.12171)
### Authors
Xu Bai,Muhammed Tawfiqul Islam,Chen Wang,Adel N. Toosi
### Background
管道并行（PP）广泛用于在GPU之间划分大型语言模型（LLMs）的层，以实现大模型的可扩展推理。但现有系统依赖静态PP配置，在动态环境如无服务器平台和异构GPU环境中无法适应。通过停止并重新部署服务进行PP重新配置会造成不可接受的停机时间，因此必须进行实时且无中断的重新配置。然而，实时在地重新配置本质上具有挑战性，GPU已经充满模型权重和KV缓存，几乎没有新的层放置空间，这与增强吞吐量的预分配KV缓存的系统相矛盾。此外，在执行过程中维护KV一致性困难：停止并复制会导致长时间暂停，而后台同步可能会导致状态演变过程中出现不一致性。
### Innovation
PipeLive介绍了重新设计的KV缓存布局，与PageAttention的协同扩展，形成统一的现场KV重新调整机制。它还采用了受现场虚拟机迁移启发的增量KV补丁机制，以在源和目标配置之间同步KV状态并识别安全切换点。PipeLive在不溢出KV缓存的情况下实现了首次标记时间（TTFT）降低2.5倍。相比没有KV补丁的变体，PipeLive将重新配置开销从秒级降至不到10毫秒，并分别将TTFT和每个输出标记的时间（TPOT）提高了54.7%和14.7%。
### Conclusion
PipeLive通过一种新的KV缓存布局和增量KV补丁机制，实现了LLM服务中的高效且无中断的现场PIP重新配置，显著提高了性能和降低了开销。
## 64. `cs.LG` - ProbeLogits:内核级级别的LLM推理原语为AI-增强的操作系统 [PDF](https://arxiv.org/pdf/2604.11943), [HTML](https://arxiv.org/abs/2604.11943)
### Authors
Daeyeon Son
### Background
本文研究了一个内置于操作系统核内核的原语，内核
### Innovation
1描述了一种名为 ProbeLogits（探测logits的创新性ovation 原语。内logits推理机制能在内核侦测生成文本的logits分配，并并并赋予治理作用级别的操作或 自学术术prits
### Conclusion
该Michiganon对its能够在2内核级别的操作
## 65. `cs.LG` - LLM-Guided Semantic Bootstrapping for Interpretable Text Classification with Tsetlin Machines [PDF](https://arxiv.org/pdf/2604.12223), [HTML](https://arxiv.org/abs/2604.12223)
### Authors
Jiechao Gao,Rohan Kumar Yadav,Yuangang Li,Yuandong Pan,Jie Wang,Ying Liu,Michael Lepech
### Background
本文介绍了将预训练语言模型（PLMs）和符号模型（如Tsetlin机）结合的背景。PLMs，如BERT，虽能提供强大的语义表示，但代价高昂且不透明，而符号模型虽透明但缺乏语义泛化能力。因此，本文提出了一种语义引导的自举框架，旨在将LLM的知识转换为符号形式，结合了可解释性和语义容量。
### Innovation
本文的创新之处在于提出了一种语义引导的自举框架，通过LLM生成子意图来指导合成数据的三阶段课程生成（种子、核心、增强），从而扩展语义多样性。随后，通过非否定Tsetlin机（NTM）从这些例子中学习并提取高置信度的符号语义线索。注入这些线索到实际数据中，使得Tsetlin机能够与LLM推断的语义对齐。该方法无需嵌入或运行时调用LLM，但仍能使符号模型具有预训练的语义先验。
### Conclusion
本文的方法在多个文本分类任务上验证了其效果，提高了可解释性和准确性，性能与BERT相当，但仍然保持了完全符号性和高效性。
## 66. `cs.LG` - LoSA: Locality-Aware Sparse Attention for Block-Wise Diffusion Language Models [PDF](https://arxiv.org/pdf/2604.12056), [HTML](https://arxiv.org/abs/2604.12056)
### Authors
Haocheng Xi,Harman Singh,Yuezhou Hu,Coleman Hooper,Rishabh Tiwari,Aditya Tomar,Minjae Lee,Wonjun Kang,Michael Mahoney,Chenfeng Xu,Kurt Keutzer,Amir Gholami
### Background
传统的逐字生成方法（mareDLM，通过自回归（AR的方式来生成文本，在D这这方法在处理大范围上下文的情景下会被记忆容量限制。。D因为因此，对于这类场景场景D情境场景D通常是基于DVLKD缓存查询的方式来提供存折存取操作。然而D对于块DwiseD块式扩散模型DLM，而言D传统的简单静态稀疏注意方法在一个连续去去去的步骤中只有一小少部分活跃令牌显示即actively tokensD表现出显著的的隐藏状态变化D而而而而对于多数令牌DD静止D几乎没有变化。这这这就限制了DLMD的在大范围上下文DDD的D处理上的能力D从而影响LODA提出提出提出Localityality长期D度意识稀疏注DD提出了去一种方法D通过重新重新在静态令牌上维持D上非活跃令牌DD上的D不应用应用进行应用D应用进行实施D上采取D稀疏注意D而在D只DD在活跃令牌D上上上实施D上上上采取DD注意D进行从而D减少了DD中必要D在D加载的数据DK数量D这D带来了带来了了D更高的计算效率和D和和同时也D保持了D相当D的高的准确D精度D
### Innovation
LODA提出方法中提出了D长距离D意识D稀疏注意DD通过D在非活跃令牌DD上上上采取D静态缓存前缀注意DD而不DD采取D注意DD在非活跃令牌D。同时D在活跃令牌DDd上采取D稀疏注意D从而D减少了D了DDD需要D被D加载D的KVD和数量D实现了D显著D的D速度加速提升D和以及D更高的效率D在D多个D不同D个扩散模型D和以及D不同几个基准上上D上上迪SABE基准D上的LODA保持D相近D的精度D同时同时也D实现了D改善D效率D获得D多达DD4..4D倍D的速度D提升D
### Conclusion
经过LODA突破D去了D传统DD方法D的在处理D扩散式块D智慧D生成D中的的局限D性通过D提出了DD反稀疏地注意D方案D它D在多种D不同D个扩散模型D取得D了接近将近DD一样的D准确精度D同时DD实现了D较D高的D效率D在X66步处理机上D上实现GS达到了D多达D4D.4倍DD的速度D提升D。这证明D还了D该该方法D的有效D效D性证明D在D处理DD扩散式块D模型D中在长D距离DD影响范围上下文文处理D上的有效DD性用
## 67. `cs.LG` - SpecBound: 自适应边界自我泛化与逐层置信校准 [PDF](https://arxiv.org/pdf/2604.12247), [HTML](https://arxiv.org/abs/2604.12247)
### Authors
Zhuofan Wen,Yang Feng
### Background
推测性作为一种有前途的方法，已被提出用于加速大规模语言模型（LLMs) 的自回归推理。。。在自回归推理过程中，，，，通常这种技术方法不仅能够提高初始模型 的推理速度，还可以减少对辅助模型的依赖。但是但由于模型限制，包括最浅层的几几层通常导致不自信但错误的 token 预测
### Innovation
该研究提出了一种新的自我推测框架，通过逐层蕴含温度校准和在早期退出的基础上抑制错误推测
### Conclusion
该方法在不修改初始模型的前提下保持了与原模型相同的输出结果
## 68. `cs.LG` - Fine-tuning Factor Augmented Neural Lasso for H Environment En [PDF](https://arxiv.org/pdf/2604.12288), [HTML](https://arxiv.org/abs/2604.12288)
### Authors
Jinhang Chai,Jianqing Fan,Cheng Gao,Qishuo Yin
### Background
微调（fine-tuning) 是一种广泛使用的策略，针对预训练模型进行任务调整,但其在高维非参数环境下选择选择中的方法和理论学性质尚未得到充分发展。本文探讨了如何在这样的设置中使用微调方法进行学习. 当前的研究主要集中在单一任务学习上,这种论文则关注如何适应变化的先验知识和因子变化(covariates and posterior shifts)从而实现统计加速 (statistical acceleration) 绩.
### Innovation
本文引入了一种新颖的方法——细调因子增强神经Lasso (FAN-Lasso) 绰开发了一种在选择性中的同时处理因子变化和因子变化的任务接收学习框架࿝f。 该方法利用低秩因子结构处理高维依赖因子变量,并提出了一种新颖的残差微调分解方法,将目标函数表示为冻结残差与学因子和变量的变换方式以实现任务接收学习和非参数性变量选择. 这增加了的知识迁移能力 幾降低了了模型复杂性.
### Conclusion
本文提出的框架在理论学效能够理论描述出微调下提供的几次.并提供的精确条件包括相对样本大小和了功能性复杂性上其中微调可以实现出统计加速.此外 该提出的框架还提供一个参数效率的微调理论视角. 幋泛的数值实验在多种不同因子变化和后验变化情景中表明 该微调FAN-Lasso在一任务学习中始终优于标准基线 幔且在严重样本限制的情况下实现了接近于最优的性能. 这些结果通过实验证验证了理论所得的保证率.
## 69. `cs.LG` - 超越单纯正确性：编码任务中大规模语言模型推理的基准测试与评估 [PDF](https://arxiv.org/pdf/2604.12379), [HTML](https://arxiv.org/abs/2604.12379)
### Authors
Yuangang Li,Justin Tian Jin Chen,Ethan Yu,David Hong,Iftekhar Ahmed
### Background
现有语言模型在解决编码任务时越来越多地依赖明确的逻辑推理，但对其推理质量的评估仍然具有挑战性。现有的测评工具主要针对代码生成任务，对于分类和总结等其他编码任务则鲜有涉及。为了填补这一空白，本文提出了CodeRQ-Bench基准测试，旨在评估大规模语言模型在三种编码任务类别（生成、总结和分类）中的推理质量。
### Innovation
本文创新性地引入了CodeRQ-Bench，这是首个针对编码任务推理质量评估的基准测试。通过分析现有评估工具的1,069个错误实例，作者发现五个重复出现的问题，并提出了四种设计见解，进而提出了一种两阶段评分工具VERA，结合了基于证据的验证和模糊性感知评分调整。实验结果表明，VERA在四个数据集上的表现均优于基线，AUC-ROC和AUPRC分别提高了0.26和0.21。
### Conclusion
本文通过创建CodeRQ-Bench基准测试，解决了语言模型在编码任务推理评估中的主要问题。VERA作为一种两阶段的新型评估器，能够在正确性之外提供更为全面的评估，为未来的研究提供支持，并广泛应用于不同数据集，证明其在评估质量和准确性方面具有优越性。
## 70. `cs.LG` - 自注意力矩阵的高斯等价性：注意力矩阵能谱的渐近谱分析 [PDF](https://arxiv.org/pdf/2510.06685), [HTML](https://arxiv.org/abs/2510.06685)
### Authors
Tomohiro Hayase,Benoît Collins,Ryo Karakida
### Background
自注意力层已经成为现代深度神经网络的基本构建块，但它们的理论理解仍然有限，特别是在随机矩阵理论的角度来看。本文作者提供了一个关于自注意力矩阵奇异值谱的严格分析，建立了第一个关于自注意力的高斯等价结果。
### Innovation
在自然条件下，证明了自注意力矩阵的奇异值分布随着系统的渐近变化可被描述为可处理的线性模型。进一步显示了平方奇异值的分布偏离了之前被广泛接受的Marchenko-Pastur定律。证明依靠两个关键要素：精确控制规范化项的波动以及利用泰勒展开的优化线性化。
### Conclusion
这项分析确定了线性化的门槛，揭示了尽管自注意力不是逐元素操作，但在这个范式下仍可严格地进行高斯等价性分析。
## 71. `cs.LG` - 视觉扩散模型是几何求解器 [PDF](https://arxiv.org/pdf/2510.21697), [HTML](https://arxiv.org/abs/2510.21697)
### Authors
Nir Goren,Shai Yehezkel,Omer Dahary,Andrey Voynov,Or Patashnik,Daniel Cohen-Or
### Background
文章展示了视觉扩散模型可以作为有效的几何求解器：它们可以直接在像素空间中处理几何问题。这种能力首先被证明了在著名的外接正方形问题上，随后扩展到其他两个经典的几何难题：Steiner 树问题和简单多边形问题。
### Innovation
该方法将每个问题实例视为图像，并使用标准的视觉扩散模型将其从高斯噪声转换为一个代表有效近似解的图像，该解接近精确解。这种方法避免了将扩散应用于参数化几何表示时需要的特殊架构和特定领域的调整。这表明生成建模和几何问题求解之间存在意想不到的联系。
### Conclusion
本文的结果指向了一个更广阔的范式：在图像空间操作提供了一个通用且实用的框架来近似解决极其棘手的问题，并为进一步探索更广泛的几何任务打开了大门。
## 72. `cs.LG` - 生成模型使从库伦爆炸成像中检索分子结构成为可能 [PDF](https://arxiv.org/pdf/2511.00179), [HTML](https://arxiv.org/abs/2511.00179)
### Authors
Xiang Li,Till Jahnke,Rebecca Boll,Jiaqi Han,Minkai Xu,Michael Meyer,Maria Novella Piancastelli,Daniel Rolles,Artem Rudenko,Florian Trinter,Thomas J.A. Wolf,Jana B. Thayer,James P. Cryan,Stefano Ermon,Phay J. Ho
### Background
在真实的空间和时间中捕获分子在化学反应中经历的结构变化是 femtochemistry 领域一个长期的梦想，也是理解甚至控制化学反应的重要前提。一种关键的方法是利用库伦爆炸成像技术，该技术得益于最近出现的高重复率X射线自由电子激光源的进步。通过该技术，分子中离子的动量分布被用来推断分子的结构。然而，从这些分布中检索分子结构涉及一个高度非线性的逆问题，对于由多于几个原子组成的分子而言，这一问题仍未解决。
### Innovation
我们使用基于扩散的Transformer神经网络来应对这一挑战。结果显示，该网络能够从离子动量分布中重建未知分子几何结构，平均绝对误差小于一个玻尔半径，这相当于典型化学键长度的一半。
### Conclusion
该研究展示了基于扩散的Transformer神经网络在从库伦爆炸成像中检索分子结构方面的能力，解决了对于多原子分子的逆问题，为理解化学反应提供了新的视角。
## 73. `cs.LG` - 气候模型调优中的在线线 精准同步参数估计 [PDF](https://arxiv.org/pdf/2510.06180), [HTML](https://arxiv.org/abs/2510.06180)
### Authors
Jordan Seneca,Suzanne Bintanja,Frank M. Selten
### Background
在气候学中 谰用气候模型的调优是一个计算密集型问题 问题 由于系统状态的高维度性和长时期的积分而导致。这也是一个难题。 一个关键挑战。现有的超级模型技术 一种技术已经显示出通过动态耦合多个模型在一起并 它们在短期时间尺度上进行耦合，有可能减少 模型的偏差。然而， 在提高耦合效率和准确性还有很大的空间改进和 胁求到多个模型的适应性性也可以通过优化内部状态参数在超级模型成员内实现。 但这是一个复杂的过程。已有方法主要集中在直接优化单个气候模型内部参数或 在传统的超级模型方法中优化两个成员的权重。
### Innovation
本文介绍的精准同步参数估计适应性模型是一种新颖的方法， 通过在超级模型中动态调整模型内部参数来调优气候模型。 这种方法结合在线 对直接优化模型内部参数和优化超级模型成员权重的方法。具体而言两个方法都被设计用于改进气候模型性能。作者通过实现适应性模型实现在适应模型中达到与完美模型相近的性能。这种方法不仅提高了耦合效率还 优化了耦合权重的准确性， 通过引入直接调整模型内部参数的方法关于 胁要通过长数组的集成运行实现高效率的参数调整。
### Conclusion
本文提出的方法简单有效，并 通过精确同步参数估计法实现了气候模型调优性能的提高。这种方法在多个阶段的过程中精细化地调整参数和 优化超级模型成员内部参数与权重达到了性能优化。 吋表明这种方法在提高气候模型调优性能方面的潜力，并 未来还将进一步探索分子模型中参数优化的的方法 和 廻以改进耦合模型性能。
## 74. `cs.LG` - Olmo 3 [PDF](https://arxiv.org/pdf/2512.13961), [HTML](https://arxiv.org/abs/2512.13961)
### Authors
Team Olmo:Allyson Ettinger,Amanda Bertsch,Bailey Kuehl,David Graham,David Heineman,Dirk Groeneveld,Faeze Brahman,Finbarr Timbers,Hamish Ivison,Jacob Morrison,Jake Poznanski,Kyle Lo,Luca Soldaini,Matt Jordan,Mayee Chen,Michael Noukhovitch,Nathan Lambert,Pete Walsh,Pradeep Dasigi,Robert Berry,Saumya Malik,Saurabh Shah,Scott Geng,Shane Arora,Shashank Gupta,Taira Anderson,Teng Xiao,Tyler Murray,Tyler Romero,Victoria Graf,Akari Asai,Akshita Bhagia,Alexander Wettig,Alisa Liu,Aman Rangapur,Chloe Anastasiades,Costa Huang,Dustin Schwenk,Harsh Trivedi,Ian Magnusson,Jaron Lochner,Jiacheng Liu,Lester James V. Miranda,Maarten Sap,Malia Morgan,Michael Schmitz,Michal Guerquin,Michael Wilson,Regan Huff,Ronan Le Bras,Rui Xin,Rulin Shao,Sam Skjonsberg,Shannon Zejiang Shen,Shuyue Stella Li,Tucker Wilde,Valentina Pyatkin,Will Merrill,Yapei Chang,Yuling Gu,Zhiyuan Zeng,Ashish Sabharwal,Luke Zettlemoyer,Pang Wei Koh,Ali Farhadi,Noah A. Smith,Hannaneh Hajishirzi
### Background
介绍了Olmo 3，这是一个包含7B和32B参数规模的顶尖开源语言模型系列。Olmo 3旨在支持长上下文推理、函数调用、编程、指令遵循、通用聊天和知识回忆等功能。
### Innovation
Olmo 3系列模型的提出是为了应对大规模语言模型在长上下文理解、函数调用、编程能力等方面的需求，同时提供完全开源的模型，保证了模型的透明性和可访问性。旗舰模型Olmo 3 Think 32B是迄今为止最强大的完全开源思考模型。
### Conclusion
本次发布包含整个模型构建流程，涵盖了从每个阶段、检查点、数据点到依赖项的完整生命周期，旨在提供一个全面的开源模型构建方案，以供更广泛的社区使用和研究。
## 75. `cs.LG` - SynthPix:：快速PIV图像生成器 [PDF](https://arxiv.org/pdf/2512.09664), [HTML](https://arxiv.org/abs/2512.09664)
### Authors
Antonio Terpin,Alan Bonomi,Francesco Banelli,Raffaello D'Andrea
### Background
在粒子图像 velocichy (PIV) 流量测量中，，on-founded on现实和非均匀光和以及噪声与模糊等问题，这真实实验数据的选择与设计生成上往往均实时性要求成总是面临挑流。。 随着计算能力的提升 on 以各种研究开始探索利用合算的方法 ontenery 流数据生成 on 支持实际测量 on 这研究推测现有的 offline 数据集集方法 on 不成本高 on 环空间需求大， 无法支持快速实时 流分析基准程序 on ，适调整性参数。 幨快速获取高效的测量。。分析 流结果.
### Innovation
SynthPix 方法是在具有 PIV 实像光 心学参数 (如如如 遂点) 生成合成图像 on 。其通过利用加速AX 技并 邨造能和 昙来 lax 加速 on 鎥加速 幐对 鐗平行 ”合算处理能力 on 实现夜 獗 on 在场在光流实验中的获种流数据上 盷平行on A 适表调整上 吞他一次预测 on 弎 on流方式更灵活 on 也支铅多辱蔓因素的快速的了ng 盻对 稡 on 孞流。” 
### Conclusion
SynSyn 衔上 SynthPix 膮在 于 评图像测量环境中支持 一但用各范畴可能适用于实验室环境 on 狗流重构图像循环精确的优点上 也能迅速检讨普通英封因素以加强流度力 蠪法。“ syn nPix 是 个支推行流量化社区 on  在本文中我们描述了 主主要法的主要创意和 在 稄的程序。”
## 76. `cs.LG` - 迭代生成机器人操控数据 [PDF](https://arxiv.org/pdf/2512.10891), [HTML](https://arxiv.org/abs/2512.10891)
### Authors
Anh-Quan Pham,Marcel Hussing,Shubhankar P. Patankar,Dani S. Bassett,Jorge Mendez-Mendez,Eric Eaton
### Background
收集机器人操控数据（非常昂贵， 使得在多 失量的 的任务、多机器人和和 多环境场景 中设置中得到足够的演示数据不切实际。。 尙然 最新的生成模型能够合成有用的数据从而完成单一任务视觉但仍无法利用机器人领域中的组成性的特性 并且难以在未见过的任务组合上 生成高质量的数据。
### Innovation
我们我们提出了一种语义组合扩散变换器数据生成方法， 该方法将任务分解为机器人- 特定 物- 片- 和 障碍特定 的组件 通过注意力机制来学习它们之间的交互。该方法基于少量任务的训练集在实验中展示出能够在从未见过的任务组合生成高质量的数据并且能够连续策略生成针对未知任务组合的策略。 我们引入一种迭代优化过程 通过离线强化学习验证合成数据 并将其纳入后续训练过程中。 这一方法显著提高了从零开始的数据生成性能 即使面对复杂的组合任务基准 本方法解决了几乎所有的留存任务并 证明了学得原型中 协同性和意义结构的式的组成性的出现。
### Conclusion
我们的方法大幅提升了从零开始的数据生成性能 这一点在单一和 大小复杂的组合基线上得到了显著展示 最终解决几乎所有的留存任务 广泛出证明了多agent-中 存认取得含重要意义的组成结构。
