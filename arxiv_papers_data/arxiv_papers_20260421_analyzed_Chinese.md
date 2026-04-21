# 20260421
[![Subscribe_Visitors](https://visitor-badge.laobi.icu/badge?page_id=nituchao.latest_arxiv_analyze_ai_rss)](https://github.com/nituchao/latest_arxiv_analyze_ai)

## 1. `cs.AI` - LLM推理是潜在的，而不是思维链 [PDF](https://arxiv.org/pdf/2604.15726), [HTML](https://arxiv.org/abs/2604.15726)
### Authors
Wenshuo Wang
### Background
该论文认为，关于大型语言模型（LLM）推理的研究应该关注潜在状态轨迹的形成，而不是表面思维链（CoT）的忠实表达。这一论点涉及信念准确性、可解释性、推理基准以及推理过程中的干预措施，因此选择研究对象对于理解这些维度至关重要。
### Innovation
论文提出现有研究可以重新组织在一个基于潜在状态轨迹与表面思维链分离的框架中，并进一步提出两种工作假设：H1认为主要由潜在状态轨迹来介导推理；H2认为主要由表面明确的思维链介导推理；H0认为表面上的推理进展更多是由通用算力提升解释的。研究表明，当前的证据更支持H1作为默认假设，而非作为与任务无关的最终结论。
### Conclusion
基于上述发现，该论文建议研究领域应将潜在状态动力学视为LLM推理研究的默认对象，并采用明确定义表面轨迹、潜在状态和序列算力的方法来评估推理。
## 2. `cs.AI` - 通过代数不变量对LLMs进行结构化的演绎-归纳- abduction推理 [PDF](https://arxiv.org/pdf/2604.15727), [HTML](https://arxiv.org/abs/2604.15727)
### Authors
Sankalp Gilda,Shlok Gilda
### Background
大型语言模型在结构化逻辑推理方面表现出系统性的局限性，它们将假设生成与验证混淆，无法区分假设与经过验证的知识，并允许薄弱推理步骤在推理链中不受检查地传播。
### Innovation
该文提出了一个符号推理支架，将皮尔士三联推理（ abduction、deduction 和 induction）显式化为LLM辅助推理的协议。框架通过五个代数不变量（伽玛五重奏）确保逻辑一致性，其中最强大的不变量——最弱环节约束——确保推理链中的任何结论都不应超过其最不支持前提的可靠性。这种方法在可能性逻辑中独立地作为最弱环节解决方法，并且在多步推理中得到实证验证。
### Conclusion
通过基于属性的测试套件对所有不变量进行了验证，包括100个属性和16个模糊测试，跨越了超过10^5种生成情况，确保了逻辑不一致不会在多步推理中累积，并且提供了一个验证后的不变量实现，可用作未来推理基准的基础。
## 3. `cs.AI` - AI代理蒸馏中不安全行为的潜意识转移 [PDF](https://arxiv.org/pdf/2604.15559), [HTML](https://arxiv.org/abs/2604.15559)
### Authors
Jacob Dang,Brian Y. Xie,Omar G. Younis
### Background
近期的研究表明，语言模型可以通过与语义无关的数据传递语义特征。然而，尚未明确指出，在通过轨迹而非静态文本学习政策的代理系统中，行为特征是否也能进行潜意识的转移。本文探讨了在代理系统中，通过模型蒸馏可以实现不安全代理行为的潜意识传递。
### Innovation
本文首次提供了证据，证明在两种互补实验设置中，代理行为中的不安全特征可以通过模型蒸馏进行潜意识传递。在主要设置中，构建了一个有很强删除偏好的教师代理，通过API工具接口执行破坏性文件系统操作，并使用本质上安全的任务轨迹将该代理蒸馏为学生代理，所有涉及删除的关键词都被严格过滤。在次要设置中，重复了威胁模型，将API工具调用替换为shell命令，并将删除偏好的操作化表示为chmod命令最先执行的偏好。尽管两个设置都进行了全面的关键词清理，但学生的不安全行为仍然被继承。
### Conclusion
结果显示，显式的数据清理并不能成为有效的防护手段，行为偏见在轨迹动力学中会隐式编码。无论使用何种工具接口，这种隐式编码都是通用的。
## 4. `cs.AI` - 通过蒙特卡罗树搜索实现代理技能的二层优化 [PDF](https://arxiv.org/pdf/2604.15709), [HTML](https://arxiv.org/abs/2604.15709)
### Authors
Chenyi Huang,Haoting Zhang,Jingxu Xu,Zeyu Zheng,Yunduan Lin
### Background
代理技能是结构化的指令、工具和辅助资源的集合，帮助大型语言模型（LLM）代理执行特定类型的任务。已有实证证据表明，技能的设计能显著影响代理的任务绩效，但系统地优化技能仍然是一个挑战。由于技能由结构化的指令、工具和支持资源组成，因此优化技能需要同时确定这些组成部分的结构和内容，这形成了一个复杂的决策空间，具有结构和组件间的强相互依赖性。
### Innovation
提出了一个通过蒙特卡罗树搜索实现技能二层优化的框架。外层循环使用蒙特卡罗树搜索来确定技能的结构，内层循环在由外层选定的结构中优化组件的内容。在两层循环中都使用了LLM来辅助优化过程。该框架被应用于开源的运筹学问答数据集上，结果显示优化后的技能改善了代理的绩效。
### Conclusion
研究提出了一个新的二层优化框架，使用蒙特卡罗树搜索来确定技能结构，通过LLM优化组件内容，并且应用于运筹学问答数据集，证明了这种优化方法可以有效提升代理的绩效。
## 5. `cs.AI` - LACE: 棋盘注意力机制用于线程间探索 [PDF](https://arxiv.org/pdf/2604.15529), [HTML](https://arxiv.org/abs/2604.15529)
### Authors
Yang Li,Zirui Zhang,Yang Liu,Chengzhi Mao
### Background
现有的大型语言模型在推理时是孤立进行的。尽管平行采样多个推理路径是常见的做法，但这些路径之间不会相互影响，并且常常以相同的方式出现重复的错误。本文讨论了如何通过新的框架LACE解决这一问题，该框架将推理从独立的尝试转换为协调的并行过程。
### Innovation
LACE框架通过重新利用模型架构来启用跨线程注意，使得平行推理路径可以共享中间见解并在推理过程中相互纠正彼此的错误。为解决自然训练数据中缺乏协作行为这一问题，文章提出了一个合成数据管道，以明确地教导模型在不同线程间进行沟通和错误纠正。实验结果显示这种统一的探索方法显著优于标准并行搜索，提高了超过7个百分点的推理准确性。
### Conclusion
研究表明，当允许并行推理路径相互作用时，大型语言模型可以更有效。LACE的引入改进了大型语言模型的推理准确性，并强调了在大规模语言模型中引入协作性是一个有前景的研究方向。
## 6. `cs.AI` - DeepER-Med: 通过具有代理能力的人工智能推进医学深层次证据驱动研究 [PDF](https://arxiv.org/pdf/2604.15456), [HTML](https://arxiv.org/abs/2604.15456)
### Authors
Zhizheng Wang,Chih-Hsuan Wei,Joey Chan,Robert Leaman,Chi-Ping Day,Chuan Wu,Mark A Knepper,Antolin Serrano Farias,Jordina Rincon-Torroella,Hasan Slika,Betty Tyler,Ryan Huu-Tuan Nguyen,Asmita Indurkar,Mélanie Hébert,Shubo Tian,Lauren He,Noor Naffakh,Aseem Aseem,Nicholas Wan,Emily Y Chew,Tiarnan D L Keenan,Zhiyong Lu
### Background
在医疗保健和生物医学研究中，人工智能(AI)的临床应用需要可信度和透明度。目前，一些深度研究系统通过将AI代理与多跳信息检索、推理和综合集成，旨在加速基于证据的科学发现。然而，大多数现有系统缺乏明确且可检查的证据评估标准，这增加了累积错误的风险，并使研究者和临床医生难以评估其输出的可靠性。此外，当前的基准测试方法很少评估复杂、实际的医学问题的表现。
### Innovation
本文介绍了一种名为DeepER-Med的深度证据驱动医学研究框架，该框架结合了具有代理能力的AI系统。DeepER-Med将复杂的医学研究明确地分为证据生成的工作流程，包括研究规划、代理合作和证据综合三个模块。此外，还提出了DeepER-MedQA，这是一个证据驱动的数据集，包含100个专家级的研究问题，这些问题源自真实的医学研究场景，并由多学科专家小组进行编辑。专家手工评估显示，DeepER-Med在多个评估标准上始终优于广泛使用的生产级平台，特别是在生成新颖的科学见解方面。通过八个实际临床案例进一步展示了DeepER-Med的实际应用价值，临床评估表明，在7个案例中DeepER-Med的结论与临床建议一致，突显了其在医学研究和决策支持领域的潜力。
### Conclusion
DeepER-Med的克服了现有AI系统和基准测试方法的不足，展现了其在医学研究和决策支持中的潜力，通过提供一个明确且可检查的证据生成流程，有助于提高AI在医学领域的可靠性和可信度。
## 7. `cs.AI` - CoLabScience，一种主动型生物医学发现和LLM-专家协作的人工智能助手 [PDF](https://arxiv.org/pdf/2604.15588), [HTML](https://arxiv.org/abs/2604.15588)
### Authors
Yang Wu,Jinhong Yu,Jingwei Xiong,Zhimin Tao,Xiaozhong Liu
### Background
大型语言模型（LLMs）被集成到科学工作流中，提供了加速生物医药发现的潜在机会。然而，由于这些模型仅在被提示时产生反应，它们在需要前瞻性思维和自主参与的协作环境中效果有限。因此，提出了一种新的解决方案，旨在增强人工智能系统和人类专家之间基于及时、情境感知干预的生物医药协作。
### Innovation
提出了一种名为CoLabScience的主动型LLM辅助程序，该程序利用了PULI框架（Positive-Unlabeled Learning-to-Intervene），这是一个通过结合团队项目提案和长期、短期对话记忆来强化学习以确定何时及如何在流式科学讨论中进行干预的新颖框架。此外，还引入了一个名为BSDD（Biomedical Streaming Dialogue Dataset）的新基准数据集，用于模拟研究讨论对话，并包含源自PubMed的文章中的干预点。
### Conclusion
实验结果显示，PULI框架在干预精准度和合作任务效率方面显著优于现有基线，这表明主动型LLM在智能科学助手方面具有巨大的潜在价值。
## 8. `cs.AI` - DALM：通过三阶段结构化生成的领域代数语言模型 [PDF](https://arxiv.org/pdf/2604.15593), [HTML](https://arxiv.org/abs/2604.15593)
### Authors
Chao Li
### Background
大型语言模型将不同领域的知识压缩到单一的参数空间中，允许不同领域的事实在生成过程中相互干扰。现有的语言模型在生成过程中缺乏对领域和概念不确定性的控制，这可能导致生成结果的不准确和混乱。
### Innovation
提出了一种称为DALM（Domain-Algebraic Language Model）的模型，它通过分阶段生成过程解决了领域、关系和概念的不确定性问题。DALM使用分层结构来管理不同领域的信息，引入了代数约束来指导模型的生成过程，提高了生成结果的准确性和合理性。
### Conclusion
DALM模型通过三个阶段的结构化生成过程，将生成过程限制在特定领域内，防止跨领域的污染，并在开放词汇模式下可审计地控制污染。通过使用CDC知识表示系统进行实例化，并在验证领域的晶体库数据上进行训练和评估，证明了DALM的有效性。
## 9. `cs.AI` - DataCenterGym：基于物理机制的数据中心多目标调度模拟器 [PDF](https://arxiv.org/pdf/2604.15594), [HTML](https://arxiv.org/abs/2604.15594)
### Authors
Nilavra Pathak,Samadrita Biswas,Nirmalya Roy
### Background
现代数据中心在地理位置分布的数据中心之间调度异构工作负载，这些数据中心具有不同的计算能力、电力价格和热力条件。计算利用率、热生成、冷却需求和能源消耗是紧密关联的，然而大多数现有的调度器都会将这些效应抽象化并独立处理。这可能导致能源效率低下和热管理问题。
### Innovation
我们提出了DataCenterGym，这是一个基于物理机制的数据中心作业调度模拟环境，旨在作为未来研究的可重用试验平台。该模拟器结合了计算队列、建筑设计热动力学、局部HVAC行为以及温度依赖的服务降级，提供了一个与Gymnasium相兼容的接口。我们还开发了层次模型预测控制（H-MPC）调度算法，能够在考虑热力和电力动态的前提下进行分布式作业放置。
### Conclusion
通过在常规操作和工作负载敏感性方面的实验，我们展示了H-MPC在调度性能方面相较于基线调度器的改进效果。
## 10. `cs.AI` - LLM attribution analysis across different fine-tuning strategies and model scales for automated code compliance [PDF](https://arxiv.org/pdf/2604.15589), [HTML](https://arxiv.org/abs/2604.15589)
### Authors
Jack Wei Lun Shi,Minghao Dang,Wawan Solihin,Justin K.W. Yeoh
### Background
现有研究主要关注大型语言模型（LLM）在自动代码合规中的性能表现，而忽视了训练决策对模型解释行为的影响。这项研究通过扰动基归因分析比较了不同微调策略如全微调（FFT）、低秩适应（LoRA）和量化LoRA微调的解释行为，并考察了模型规模（包括不同的LLM参数量）的影响。
### Innovation
研究通过扰动基归因分析，比较了不同微调策略的解释行为，并分析了模型规模对LLM解释行为的影响。这一研究填补了现有研究中对解释行为关注不足的空白，提供了一种理解这些模型解释性的方法。
### Conclusion
研究结果表明，全微调（FFT）产生的归因模式在统计学上与其他参数高效微调方法不同，且更集中。随着模型规模的增加，模型发展出特定的解释策略，比如优先处理数值约束和规则标识符，尽管在生成和参考计算机可处理规则的语义相似性方面，对于大于7B的模型，性能增益呈现平台期。研究为构建更透明的LLM以应对建筑、工程和建设行业的监管任务提供了宝贵的见解。
## 11. `cs.AI` - 从自适应整体排名的角度重新审视自适应检索增强生成的必要性 [PDF](https://arxiv.org/pdf/2604.15621), [HTML](https://arxiv.org/abs/2604.15621)
### Authors
Jun Feng,Jiahui Tang,Zhicheng He,Hang Lv,Hongchao Gu,Hao Wang,Xuezhi Yang,Shuai Fang
### Background
自适应检索增强生成旨在通过动态确定检索补充段落的必要性来减轻额外噪声的干扰。然而，随着大型语言模型对噪声的鲁棒性增强，自适应检索的必要性需要重新评估。
### Innovation
提出了一种新颖的自适应检索框架AdaRankLLM，并通过引入自适应排序器和两阶段逐步蒸馏来增强较小的开源LLM的精确整体排名和自适应过滤能力。
### Conclusion
在三个数据集和八个LLM上的大量实验表明，AdaRankLLM在大多数场景中都表现出了最优性能，且显著减少了上下文开销。我们的分析揭示了自适应检索的作用转变，即对于较弱的模型，它作为关键的噪声过滤器，帮助克服其局限性，而对于较强推理模型，则作为效率优化的有效成本优化器。
## 12. `cs.AI` - CLIMB：基于Mamba基态扩散模型和高斯对齐自编码器的可控制纵向脑影像生成 [PDF](https://arxiv.org/pdf/2604.15611), [HTML](https://arxiv.org/abs/2604.15611)
### Authors
Duy-Phuong Dao,Muhammad Taqiyuddin,Jahae Kim,Sang-Heon Lee,Hye-Won Jung,Jaehoo Choi,Hyung-Jeong Yang
### Background
潜藏扩散模型（Latent diffusion models）已成为医学成像中强有力的生成模型，能够合成高质量的脑磁共振成像扫描。预测患者大脑的演变有助于早期干预、预后和治疗规划。
### Innovation
1. 引入了CLIMB框架，用于建模大脑结构随时间变化，通过状态空间基态扩散模型进行建模，利用基准MRI扫描和其获取年龄作为基础输入。2. 融入了多个条件变量，如预测年龄、性别、疾病状态、遗传信息和大脑结构体积，以增强解剖变化的时间建模。3. 使用状态空间模型架构取代现有方法中的自注意力模块，减少计算开销同时保持高质量图像合成。4. 引入了高斯对齐自编码器，提取符合先验分布的潜空间表示，避免了传统变分自编码器本身的采样噪声。
### Conclusion
通过在阿尔茨海默病神经影像学倡议数据集上的训练和评估，CLIMB 获得了结构相似性指数0.9433，优于现有方法的表现。
## 13. `cs.AI` - VoodooNet: 通过高维随机投影实现解析基态 [PDF](https://arxiv.org/pdf/2604.15613), [HTML](https://arxiv.org/abs/2604.15613)
### Authors
Wladimir Silva
### Background
本文提出了VoodooNet，这是一种非迭代的神经架构，它通过使用Galactic Expansion方法替代传统的随机梯度下降(Stochastic Gradient Descent, SGD)范式，获得了闭式解析解。通过将输入流形投影到一个高维、高熵的“银河系”空间中($d textgreatertextgreater 784$)，研究者们发现，可以在不增加反向传播的热力学成本的前提下，解开复杂的特征。
### Innovation
VoodooNet 使用莫雷-P恩斯洛伪逆在单步中解决输出层问题，达到了在 MNIST 上 98.10% 的分类准确率和在 Fashion-MNIST 上 86.63% 的准确率。与传统的10轮SGD基准（准确率为84.41%）相比，该方法显著减少了训练时间，同时在 Fashion-MNIST 上取得了更好的结果。研究发现，性能与“银河系”体积而非迭代优化呈近似对数缩放律，这表明准确性取决于高维空间的体积而非逐步改进。
### Conclusion
VoodooNet 提出了一种新的边缘人工智能（Edge AI）前沿技术，即“Magic Hat”方法，这种方法允许实时发现数据流形，而不进行传统的训练阶段。
## 14. `cs.AI` - CSLE:：: that Reinforcement Learning Platform for Autonomous Security Management [PDF](https://arxiv.org/pdf/2604.15590), [HTML](https://arxiv.org/abs/2604.15590)
### Authors
Kim Hammar
### Background
当前强化学习在安全管理工作中的应用主要局限于模拟环境，，，并且在实际操作环境下的应用的情况还不明确。
### Innovation
本文通过开发CSLE: 輯架，，一种强化学习平台，来克服这一限制，。。该平台在一种接近实际操作环境的条件下实现了自主性安全管理的实验。。从该平台中包含了两个系统：第一是模拟系统，能够在虚拟环境中重现目标系统的几个组成部分，并基于该系统收集测量和日志以构建一个随机过程模型；第二是在系统模型中有效学习安全策略的模拟系统。然后根据理论和实际之间的差异来这个模型中不断评估和优化安全策略策略该平台通过四个用案实验表明它CSLE: 輯架 “能够在接近实际操作的环境中实现近最优的安全管理。
### Conclusion
综上而言本文提出了一种名为 CSLE 的强化学习平台来，该平台能够在接近实际操作的环境下实现自主安全管理 且通过实际测试证明了其有效性。
## 15. `cs.AI` - BioHiCL: Hierarchical Multi-label contrasttrative learning for biomedical retrieval with MeSH labels [PDF](https://arxiv.org/pdf/2604.15591), [HTML](https://arxiv.org/abs/2604.15591)
### Authors
Mengfei Lan,Lecheng Zheng,Halil Kilicoglu
### Background
生物医学领域的文本检索对精准医学、疾病诊断、药物研究等等 典治疗等方面至关重要。扩大了
### Innovation
本文提出了BioHiCL（生物医学层级多分类学习),
### Conclusion
我们的模型，  BioHiCL-Base  和  BioHiCL-Large  在生物医学检索、句间相似性和以及问题答质问等任等方面表现出色力优秀的性能，同时且在计算上问上也十分高效。
## 16. `cs.CL` - 评估基于LLM的模拟器作为差分隐私数据生成器 [PDF](https://arxiv.org/pdf/2604.15461), [HTML](https://arxiv.org/abs/2604.15461)
### Authors
Nassima M. Bouzid,Dehao Yuan,Nam H. Nguyen,Mayana Pereira
### Background
基于大语言模型（LLM）的模拟器为生成复杂的合成数据提供了前景，尤其是在传统差异隐私（DP）方法在处理高维用户配置文件时遇到困难的情况下。然而，这些LLM是否能准确地重现从DP保护输入中得出的统计分布？
### Innovation
研究使用PersonaLedger作为代理金融模拟器，种子数据是基于真实用户统计信息的DP合成人像。研究发现，PersonaLedger在欺诈检测方面表现出色（ε=1时AUC为0.70），但在时间与人口统计数据特征上表现出显著的分布漂移现象，这是由于系统性的LLM偏见导致学习先验覆盖了输入统计数据。
### Conclusion
这些失败模式必须得到解决，以便在用户表示更丰富的情况下，LLM方法能够充分发挥其优势。
## 17. `cs.CL` - 通过自适应整体排名视角重新审视自适应检索增强生成的必要性 [PDF](https://arxiv.org/pdf/2604.15621), [HTML](https://arxiv.org/abs/2604.15621)
### Authors
Jun Feng,Jiahui Tang,Zhicheng He,Hang Lv,Hongchao Gu,Hao Wang,Xuezhi Yang,Shuai Fang
### Background
自适应检索增强生成旨在通过动态确定补充段落的必要性来减轻外来噪声的干扰。然而，随着大型语言模型（LLM）变得越来越能够抵御噪声，自适应检索的必要性需要重新评估。
### Innovation
本文提出了一种新颖的自适应检索框架AdaRankLLM。首先开发了一种使用段落删除机制的零样本提示自适应排名器，并将其与静态固定深度检索策略对比。此外，通过增强数据采样和扩增技术引入两阶段渐进蒸馏范式，赋予较小的开源LLM精确的整体排名和自适应过滤能力。
### Conclusion
广泛的实验证明，AdaRankLLM在大多数情况下能以显著减少上下文开销的方式获得最优性能。我们的分析揭示了自适应检索的作用转变：对于较弱的模型，它作为关键的噪声过滤器帮助企业克服限制；而对于更强的推理模型，它则作为低成本的效率优化器。
## 18. `cs.CL` - Preregistered Belief Revision Contracts [PDF](https://arxiv.org/pdf/2604.15558), [HTML](https://arxiv.org/abs/2604.15558)
### Authors
Saad Alqithami
### Background
多智能体系统中的智能体可以通过交换消息和随着时间修订信念来改善性能，但这种互动可能导致危险的同质性效应，智能体可能会错误地将一致意见、自信度、声望或多数规模视为证据，从而导致高自信度的错误结论。因此，本研究旨在通过引入Preregistered Belief Revision Contracts (PBRC)来解决这一问题。PBRC在协议层面上分隔了开放通信和可接受的知性变化，固定了第一级证据触发条件、可接受的修订操作、优先规则和备用政策。
### Innovation
研究提出了PBRC（Preregistered Belief Revision Contracts）协议，这是一种在协议层面分隔开放通信和可接受的知性变化的机制。PBRC合同公开固定了第一级证据触发条件、可接受的修订操作、优先规则和备用政策。非备用步骤只有在引用了预注册的触发条件并提供了外部验证的证据令牌的非空证词集时才被接受。这确保了每个实质性的信念改变可以从路由器处强制执行并在事后被审计。研究还提出了同伴合同动态语义逻辑来指定轨迹不变量，并提供了抑制信号传播、提高审计能力和确保容错及活化性能的仿真。
### Conclusion
研究证明，在保守备用情况下，基于证据的PBRC协议不能通过社交轮次增加自信度，也不能生成仅由同质性驱动的错误但自信的信号传播。可审计触发协议允许基于证据的PBRC协议保留信念轨迹和标准化审计跟踪。强制执行遵循逻辑规则确保了有根据且验证的证据集可以追溯任何顶级假设的变化。此外，对于令牌不变协议，在泛洪传播情况下，强制执行的轨迹仅依赖于令牌暴露路径，从而为普遍证据闭包提供了严格直径界。引入的同伴合同动态语义逻辑为指定轨迹不变量提供了工具，并通过仿真展示了信号传播抑制、审计性和鲁棒性与活力之间的权衡。
## 19. `cs.CL` - SIMMER: 通过MLLM基础嵌入实现的跨模态食物图像-食谱检索 [PDF](https://arxiv.org/pdf/2604.15628), [HTML](https://arxiv.org/abs/2604.15628)
### Authors
Keisuke Gomi,Keiji Yanai
### Background
跨模态检索任务涉及在食物图像和食谱文本之间建立联系，具有营养管理、饮食记录和烹饪辅助等多种应用。现有方法主要依赖于双编码器架构，使用独立的图像编码器和文本编码器，并要求复杂的对齐策略和特定任务的网络设计来弥合模态间的语义差距。
### Innovation
本工作提出了一种名为SIMMER的单一致融多模态模型，使用基于多模态大型语言模型（MLLM）的嵌入模型，特别是VLM2Vec，替代传统的双编码器范式，采用一个统一的编码器同时处理食物图像和食谱文本。通过针对食谱结构化特性的定制提示模板和组件感知的数据增强策略，提高了模型对不完整输入的鲁棒性。
### Conclusion
实验结果显示，SIMMER在1M食谱数据集上实现了最先进的性能，特别是在1k和10k评估设置中显著优于所有先前的方法。特别是在图像到食谱检索中，我们的最佳模型将1k的R@1从81.8%提高到87.5%，10k的R@1从56.5%提高到65.5%。
## 20. `cs.CL` - 通过序列蒙特卡洛方法加速大语言模型推理 [PDF](https://arxiv.org/pdf/2604.15672), [HTML](https://arxiv.org/abs/2604.15672)
### Authors
Yahya Emara,Mauricio Barba da Costa,Chi-Chih Chang,Cameron Freer,Tim Vieira,Ryan Cotterell,Mohamed S. Abdelfattah
### Background
当前语言模型推理速度受限于拒绝采样，当提案模型和目标模型不一致时，推理会因过早截断而减慢。
### Innovation
提出了一种序贯蒙特卡洛推测解码（SMC-SD），这是一种替代基于令牌级别的拒绝采样，而是使用重要性加权重采样的方法。SMC-SD 能够在不牺牲精确度的同时提高推理速度，并且能够在闲置计算资源上实现并行验证操作，无需回滚。
### Conclusion
SMC-SD 在速度上分别比推测解码快 2.36 倍，比自回归解码快 5.2 倍，同时在推理、指令遵循和编程基准测试中保持了与目标模型相差不到 3% 的准确性。
## 21. `cs.CL` - 不在于每个 token：通过强化学习中的 token 重要性追求高效 LLM 推理 [PDF](https://arxiv.org/pdf/2506.08125), [HTML](https://arxiv.org/abs/2506.08125)
### Authors
Hanbing Liu,Lang Cao,Yuanyi Ren,Mengyu Zhou,Haoyu Dong,Xiaojun Ma,Shi Han,Dongmei Zhang
### Background
大规模语言模型（LLMs）显示出强大的推理能力，但往往会产生不必要的长解释，降低了效率。尽管强化学习（RL）已用于改进推理，但大多数方法集中在准确性上，并依赖于基于统一长度的奖励，忽略了各个 token 的不同贡献，有时损害了正确性。
### Innovation
本文重新审视强化学习中的长度优化，通过 token 重要性的视角。通过观察 Many Chain-of-Thought (CoT) token 对最终答案的贡献甚微，引入了一种基于 token 重要性的长度奖励，选择性地惩罚不重要的 token，从而减少了冗余并保留了关键的推理。同时，提出了动态长度奖励，在训练初期鼓励更详细推理，并随着学习的进展逐渐转向简洁。将这些组件融入标准策略优化中，形成了一个能同时提高推理效率和准确性的框架。
### Conclusion
跨多个基准的实验结果显示，在保留或提高正确性的同时，响应长度显著减少，强调了建模 token 重要性对于高效 LLM 推理的重要性。
## 22. `cs.CL` - 重新审视熵正则化：自适应系数解锁其在大语言模型强化学习中的潜力 [PDF](https://arxiv.org/pdf/2510.10959), [HTML](https://arxiv.org/abs/2510.10959)
### Authors
Xiaoyun Zhang,Xiaojian Yuan,Di Huang,Wang You,Chen Hu,Jingqing Ruan,Ai Jian,Kejiang Chen,Xing Hu
### Background
大型语言模型（LLMs）的推理能力已经成为其核心能力之一，而强化学习带有验证性奖励（RLVR）正逐渐成为提升该能力的关键范式。然而，RLVR训练过程往往会出现策略熵坍缩现象，导致策略过分确定，从而阻碍探索并限制推理性能。尽管熵正则化是常见的补救措施，但其效果高度依赖固定的系数，导致在不同任务和模型中不稳定。
### Innovation
本文重新审视了熵正则化在RLVR中的作用，并提出自适应熵正则化（AER）框架，通过三个组件来动态平衡探索和利用：难度感知的系数分配、基于初始值的目标熵以及动态全局系数调整。实验结果表明，AER在多个数学推理基准测试中超越了基准方法，同时提高了推理准确性和探索能力。
### Conclusion
AER框架能够有效维持政策熵在适当范围内，为不同难度的任务提供平衡的探索强度，从而提高推理性能和探索能力。
## 23. `cs.CL` - 在LLM推理中重新审视均匀信息密度假设 [PDF](https://arxiv.org/pdf/2510.06953), [HTML](https://arxiv.org/abs/2510.06953)
### Authors
Minju Gwak,Guijin Son,Jaehyung Kim
### Background
均匀信息密度（UID）假设提出，有效的沟通通过保持稳定的信息流实现。本文在大型语言模型（LLM）推理的情境下重新审视这一原则，探讨步骤级的均匀性是否代表推理的质量。通过引入一种基于熵的步骤密度度量方法来量化信息流的均匀性，作者在七个推理基准测试中发现了非直观的模式：高质量的推理表现出平滑的步骤间转换，局部均匀性，并且在其轨迹层面具有结构化但非均匀的信息流动，即全局非均匀性。
### Innovation
本文提出了一种新的框架，使用基于熵的步骤密度度量方法来量度信息流在局部和全局层面的均匀性。研究发现，这些均匀性作为推理质量预测指标的表现优于其他内部分指标，且这种与人类沟通的区别不是模型的缺陷，而是人类沟通与LLM推理之间目标差异的表现。
### Conclusion
高质量的推理在局部表现出均匀性，在全局却展示出非均匀性。这些发现表明，这些均匀性作为推理质量预测指标的表现优于其他内部分指标，证明这种与人类沟通的区别不是模型的缺陷，而是目标差异的产物。
## 24. `cs.CL` - EvoTest：自我改善型系统在检测和学习中的进化式测试时学习 [PDF](https://arxiv.org/pdf/2510.13220), [HTML](https://arxiv.org/abs/2510.13220)
### Authors
Yufei He,Juncheng Liu,Yue Liu,Yibo Li,Tri Cao,Zhiyuan Hu,Xinxing Xu,Bryan Hooi
### Background
当前的人工智能代理在测试时学习复杂技能方面存在基本限制，通常在新型环境中表现出“聪明但冥顽不灵的实习生”行为。这极大限制了它们的实际应用价值。为系统地衡量和推动这方面的发展进步，我们首先引入了Jericho测试时学习（J-TTL）基准。J-TTL是一种新的评估设置，要求代理连续玩多个游戏，并尝试从一关提高到下一关的表现。在J-TTL基准上，现有的适应方法，如反演、记忆或强化学习都遇到了挑战。
### Innovation
我们提出了EvoTest，一种进化式的测试时学习框架，该框架可以在不进行任何微调或梯度的情况下提高代理的表现。EvoTest有两个角色：执行代理（Actor Agent），负责游戏的实际操作；进化代理（Evolver Agent），分析每关的游戏记录，提出下一关的改进配置。配置会重新编写提示、更新记忆、调整超参数并学习工具使用规范。在我们的J-TTL基准上，EvoTest始终提高了表现，并且在两个游戏中获胜，而其他基线方法未能获胜。
### Conclusion
EvoTest不仅在J-TTL基准上表现出优异的性能，实现连续游戏中的自我改进，而且是唯一能在两个游戏中取胜的方法，超过了包括反演和只记忆在内的所有基线方法以及更复杂的在线微调方法。
## 25. `cs.CL` - 通过踪迹重写保护语言模型免受未授权知识蒸馏 [PDF](https://arxiv.org/pdf/2602.15143), [HTML](https://arxiv.org/abs/2602.15143)
### Authors
Xinhang Ma,William Yeoh,Ning Zhang,Yevgeniy Vorobeychik
### Background
知识蒸馏是一种常用的将大型语言模型（LLMs）的能力转移到更小、更高效的受训模型的技术。然而，未经授权的知识蒸馏不恰当地利用了开发前沿模型所投入的巨大努力和成本。本文研究了修改教师生成的推理踪迹的方法，以达到两个旨在阻止未经授权蒸馏的目标：(1) 抗蒸馏，即降低查询响应的训练有用性；(2) API 水印，即在学生模型中嵌入可验证的签名。
### Innovation
本文介绍了几种动态重写教师推理输出的方法，同时保留答案的正确性和语义连贯性。其中两种方法利用了LLMs的重写能力，而其他方法则使用梯度基技术。实验结果表明，基于指令的重写方法在保持或甚至提高教师性能的同时，能够实现强大的抗蒸馏效果。此外，本文还显示，该重写方法允许嵌入可以在几乎没有任何误报警的情况下可靠检测的水印。
### Conclusion
本文通过实验验证了一种基于指令的重写方法能够在保护模型免受未经授权蒸馏的同时，实现抗蒸馏效果，并且能够可靠地嵌入水印。相关代码可在提供的链接处获取。
## 26. `cs.CV` - ProtoTTA: Prototype-Guided Test-Time Adaptation [PDF](https://arxiv.org/pdf/2604.15494), [HTML](https://arxiv.org/abs/2604.15494)
### Authors
Mohammad Mahdi Abootorabi,Parvin Mousavi,Purang Abolmaesumi,Evan Shelhamer
### Background
当前研究表明，依赖原型的深度网络可以通过与其输入相关联的可解释表示来确保高准确性和内在解释性，使其适用于包括医疗健康在内的关键领域。然而，此类模型对于分布漂移的鲁棒性受到其对训练数据的依赖限制。尽管测试时适应(TTA)可以通过更新参数和统计信息来提升模型鲁棒性，但现有的TTA方法并未针对可解释性模型进行优化。
### Innovation
该论文提出了ProtoTTA框架，这是一个适用于原型模型的一般化框架，该框架利用中间原型信号而不是仅仅依赖模型输出。通过最小化原型相似度分布的熵来促进更具有自信心和原型特异性激活。为了保持稳定性，通过几何滤波来限制更新，只针对具有可靠原型激活的样本，并使用原型重要性和模型置信度分数进行正则化。通过在四个不同的原型模型架构上进行四组不同的测试，结果表明与标准输出熵最小化方法相比，ProToTA提高了鲁棒性并恢复了原型激活的正确语义焦点。
### Conclusion
实验结果证实，ProToTA恢复了与人类共识一致的语义焦点，并且与基于VLM的推理质量评价结果密切相关。本文还介绍了新的解释性度量标准和视觉语言模型评估框架来解释TTA动态。
## 27. `cs.CV` - GIST: 通过智能语义拓扑进行的多模态知识提取和空间定位 [PDF](https://arxiv.org/pdf/2604.15495), [HTML](https://arxiv.org/abs/2604.15495)
### Authors
Shivendra Agrawal,Bradley Hayes
### Background
导航像零售商店、仓库和医院这样复杂且紧密排列的环境对于无论是人类还是嵌入式AI来说都是一个重大的空间定位挑战。这些空间中密集的视觉特征由于物品的准静态特性很快就会过时，而长尾语义分布也为传统计算机视觉带来了挑战。视觉-语言模型(VLMs)有助于辅助系统在语义丰富的空间中导航，但在拥挤的环境中依然难以实现空间定位。
### Innovation
我们提出了一种名为GIST（Grounded Intelligent Semantic Topology）的多模态知识提取管道，即将消费者级移动点云转换为语义注解的导航拓扑。该架构将场景提炼为2D占用率地图，提取其拓扑布局，并通过智能关键帧和语义选择叠加轻量级语义层。我们通过关键下游的人工智能互动任务展示了这种结构化空间知识的灵活性：（1）一种基于意图的语义搜索引擎，在精确匹配失败时主动推断类别替代和区域；（2）一次有效的语义定位，top-5平均翻译误差为1.04米；（3）一个区域分类模块，将走行区域分割为高层次语义区域；（4）一种视觉导向的指令生成器，能够生成以自我为中心、地标丰富的自然语言导航指令。在多准则LLM评估中，GIST超越了基于序列的指令生成基线。
### Conclusion
最终，通过基于现场的形成性评估（N=5），我们展示了系统在仅依赖口头提示的情况下有80%的成功导航率，这证实了该系统的通用设计能力。
## 28. `cs.CV` - CTSCAN：胸部CT分割中的评估泄漏以及可重复的患者分离基准 [PDF](https://arxiv.org/pdf/2604.15561), [HTML](https://arxiv.org/abs/2604.15561)
### Authors
Anton Ivchenko
### Background
研究发现，报告的胸部CT分割性能在训练集和测试集混用同一个病例中的切片时，可能会被严重夸大。这意味着模型可能未能在未见过的病例上良好泛化，因为训练过程中的一部分信息泄露到了测试集中。
### Innovation
本文提出了CTSCAN，一个可重复的多数据源胸部CT基准和研究平台，旨在通过患者分离评估测量模型的性能。CTSCAN利用了一个包含来自PleThora、MedSeg SIRM和LongCIU的四个类别的89个病例，通过对比切片混用和病例分离的评估方法，发现原始的切片-PNG工作流程导致了训练、验证和测试集之间的病例高度重复。该平台提供了一个实验环境，使用相同的FPN和EfficientNet-B0控制配置，分别在切片混用和病例分离的评估方法下运行多次实验，结果显示切片分离后的模型性能明显下降。
### Conclusion
去除患者重用可以显著降低分割Dice系数和IoU，分别减少0.4599（69.00%）和0.3850（76.52%）。CTSCAN提供了一个包含确定性拆分元数据、明确的弱监督控制、脚本化多种子实验流程以及可重复的图表生成的基准与平台，为患者分离的胸部CT评估提供了一个可复用的基础。
## 29. `cs.CV` - 在黑暗中适应：面向黑盒模型的高效稳定测试时适应 [PDF](https://arxiv.org/pdf/2604.15609), [HTML](https://arxiv.org/abs/2604.15609)
### Authors
Yunbei Zhang,Shuaicheng Niu,Chengyi Cai,Feng Liu,Jihun Hamm
### Background
黑盒模型通过API访问，测试时适应（TTA）仍然是一项未被充分探索的挑战。现有的一些方法如后验输出校正只能提供有限的适应性，而零阶优化（ZOO）允许输入空间的适应，但在无监督TTA设置中面临查询成本高和优化困难的问题。
### Innovation
提出了一种名为BETA的框架，利用轻量级的局部白盒引导模型创建可处理的梯度路径。结合预测共融技术、一致性正则化和提示学习导向的筛选，BETA实现了无额外API呼叫和几乎无额外延迟的稳定适应，证明在性能和成本上优于现有的白盒和灰盒方法。
### Conclusion
BETA在ImageNet-C上分别实现了ViT-B/16和CLIP的准确率提升+7.1%和+3.4%，成本降低250倍，保持实时推理速度，成为现实世界黑盒TTA的实用有效解决方案。
## 30. `cs.CV` - HyperGVL：评估和提升大规模视觉-语言模型在超图理解与推理方面的基准 [PDF](https://arxiv.org/pdf/2604.15648), [HTML](https://arxiv.org/abs/2604.15648)
### Authors
Yanbin Wei,Chun Kang,Siwei Li,Haoxuan Che,Yang Chen,Hua Liu,Jian Liu,Zhuang Liu,Can Ouyang,Fei Xing,Lei Sha,Rui Liu,Yu Zhang,James Kwok
### Background
大型视觉-语言模型（LVLMs）不断增加规模边界，但它们对超图的理解能力尚未得到探索。超图在生命科学和社会社区等领域有重要的实际应用，LVLMs在理解和处理复杂拓扑结构上取得了进展，但仍缺乏基准来评估LVLMs在超图上的能力。现有研究未能明确LVLMs在超图上的界限。
### Innovation
本文引入了首个名为HyperGVL的基准，用于评估LVLMs在超图理解与推理方面的能力。HyperGVL涵盖12种先进的LVLMs在84,000个视觉-语言问答样本中的性能，这些样本涉及12项任务。还探讨了不同文本和视觉超图表示的效果，并提出了一种通用的路由器WiseHyGR，通过学习自适应表示来提升LVLMs在超图中的表现。
### Conclusion
本工作为连接超图和LVLMs迈出了重要一步，通过HyperGVL基准评估LVLMs，并通过WiseHyGR改进了LVLMs在超图上的性能。
## 31. `cs.CV` - Hierarchical Codec Diffusion for Video-to-Speech Generation [PDF](https://arxiv.org/pdf/2604.15923), [HTML](https://arxiv.org/abs/2604.15923)
### Authors
Jiaxin Ye,Gaoxiang Cong,Chenhui Wang,Xin-Cheng Wen,Zhaoyang Li,Boyuan Cao,Hongming Shan
### Background
现有的视频到语音（VTS）方法忽略了语音的层次化结构，涵盖粗略的说话人感知语义和精细的句调细节。这种忽略阻碍了视觉和语音特征在特定层次对齐的能力。
### Innovation
提出了一种新颖的基于残差向量量化（RVQ）编解码器的层次结构，名为HiCoDiT（Hierarchical Codec Diffusion Transformer），利用离散语音标记的内在层次结构实现强的视听对齐。低级模块通过嘴唇同步运动和面部身份条件捕获说话人感知的内容，而高级模块使用面部表情来调节句调动力学。此外，提出了一个双尺度自适应实例层归一化，以更好地实现粗到细的条件化。
### Conclusion
广泛的实验表明，HiCoDiT在保真度和表现力方面优于基线，突显了离散建模在VTS中的潜力。代码和语音演示可以在此地址找到：this https URL.
## 32. `cs.LG` - 随机算法驱动的序列回归学习 [PDF](https://arxiv.org/pdf/2507.03759), [HTML](https://arxiv.org/abs/2507.03759)
### Authors
Dorival Leão,Reiko Aoki,Alberto Ohashi,Teh Led Red
### Background
本文提出了一种名为'随机SINDy'的序列机器学习算法，用于具有时间依赖结构的动力数据。该算法基于概率方法，在功能分析的数学理论支持下保证了PAC学习性质。算法通过梯度下降和邻近算法动态预测并保持有效的概率密度，这在SINDy的基础上进行了改进，引入了特征增强和Tikhonov正则化。
### Innovation
该算法通过结合概率方法和动态预测机制，提高了对时间结构数据的处理效率。特别是，对于多变量正态权重，省去了邻近步，侧重于参数估计，从而提高了算法的灵活性和实用性。
### Conclusion
通过实际数据在回归和二元分类实验中的表现，验证了该算法的有效性。
## 33. `cs.LG` - 了解、分析和优化代理AI执行：以CPU为中心的视角 [PDF](https://arxiv.org/pdf/2511.00739), [HTML](https://arxiv.org/abs/2511.00739)
### Authors
Ritik Raj,Souvik Kundu,Ishita Vohra,Hong Wang,Tushar Krishna
### Background
本文通过对代理AI执行的分析，旨在从被忽略的CPU视角理解其系统瓶颈。代理AI将单一的大型语言模型（LLM）推理转换为能够自主解决问题、规划、调用工具、进行推理并实时适应的个体。由于执行任务的多样性，代理AI的运行高度依赖异构的CPU-GPU系统，多数外部工具由CPU负责。现有研究可能更多关注GPU性能和工具执行，但本文提出应该从CPU角度更深入地研究这些问题。
### Innovation
本文提出了两种针对代理AI负载的调度优化方法：1. CPU感知重叠微批处理（COMB），优化了CPU和GPU的并发利用率；2. 混合代理调度（MAS），针对异构代理负载进行了优化，减少了资源分配的偏差。实验结果表明，在单一类型的工作负载下，COMB在独立运行时可降低P50延迟最多70%，在混合开放式负载下，MAS可将最低请求类型的服务和总延迟分别降低最多590%/20%，并在P50/P90百分位处显著降低异构开放式负载的总延迟。
### Conclusion
本文通过CPU感知的编译时和运行时特性分析，识别了代理AI工作负载的系统瓶颈，并提出两种针对性的优化方法，有效提高了计算资源的利用效率和系统的服务性能。
## 34. `cs.LG` - TriagerX： 双变换器在Bug分类任务中的 冻结内容 analysis [PDF](https://arxiv.org/pdf/2508.16860), [HTML](https://arxiv.org/abs/2508.16860)
### Authors
Md Afif Al Mamun,Gias Uddin,Lan Xia,Longyu Zhang
### Background
传统的机器学习 (ML) 模型依赖于 绋制特征（如 例子， TF-IDF, 会有bag of of on的方式）进行开发人员协助任务。 但 史这些方法方法模型可能 对 于 各 信息有限可能不充分， 而训练前模型（ (PLMs) 则 以捕捉文字语义, 且在处理开发人员与 有关错误的协助任务 on 虋容有限开人员特定错误交互历史的时 限 提出有效的荐。 囔X旨在改进这一局限.
### Innovation
1以 了通过采用一个使用双变换器器架构（ 日以往不同模 on 的单一变换器架构， 囔X收集了两个变换器 提供荐意见 on 濇导员与其他变换器器 提供 最后三层. 该 迱从而使X级获得了更为健内容底的推荐排列.
### Conclusion
 通过使用的五组不同上进行测试 on I
