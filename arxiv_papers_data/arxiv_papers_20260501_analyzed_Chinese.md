# 20260501
[![Subscribe_Visitors](https://visitor-badge.laobi.icu/badge?page_id=nituchao.latest_arxiv_analyze_ai_rss)](https://github.com/nituchao/latest_arxiv_analyze_ai)

## 1. `cs.AI` - 自动关系推理 [PDF](https://arxiv.org/pdf/2604.26507), [HTML](https://arxiv.org/abs/2604.26507)
### Authors
Ioannis Konstantoulas,Dimosthenis Tsimas,Pavlos Peppas,Kyriakos Sgarbas
### Background
近十年来，机器学习研究迅猛发展，但大型模型已接近其软限值，表现出收益递减的趋势，并缺乏扎实的逻辑推理能力。这些限制可以通过机器学习可伸缩性与严格推理的协同作用来克服。
### Innovation
本文提出了一个基于对象关系的自动推理理论框架，并将其与人工神经网络整合。该研究通过结合推理与机器学习提出了一种范式，并展示了其实际效果。系统能够解决智商测试中的问题，且无需任何关于问题的先验知识，解决了高达98.03%的测试题。
### Conclusion
通过将先验知识整合进系统并扩展数据集，系统可以解决一类更大的问题。该系统在解决此类问题方面具有单次或少量尝试的优势。
## 2. `cs.AI` - Apriori-based Analysis of Learned Helplessness in Mathematics Tutoring: Behavioral Patterns by Level, Intervention, and Outcome [PDF](https://arxiv.org/pdf/2604.26237), [HTML](https://arxiv.org/abs/2604.26237)
### Authors
John Paul P. Miranda
### Background
该研究利用Apriori算法分析了数学辅导系统日志中因势无助（LH）行为模式的关联。数据在处理交互时考虑了三个维度：LH水平（低 vs. 高）、系统干预（有 vs. 无）和解决问题的结果（解决 vs. 未解决）。
### Innovation
创新之处在于使用Apriori算法对数学辅导系统日志中的数据进行了分析，揭示了LH水平、系统干预和解决问题结果之间的行为模式，特别是在低LH和高LH学生、有干预和无干预条件以及不同解决结果之间的关联性。
### Conclusion
总体而言，不使用提示直接跳过问题是未解决问题最常见的模式；低LH学生较少出现这种模式，而高LH学生则更多表现出避免行为。在干预条件对比中，无干预学生表现出更强的坚持性与解题成功关联；而有干预情景中，跳过行为与未解决问题的关联更显著。所有组别中，不跳过问题是解决问题的一致性预测因素，而不使用提示跳过问题则预示着未解决问题的结果。
## 3. `cs.AI` - 基于实际资本的链上语言模型代理的操作层控制 [PDF](https://arxiv.org/pdf/2604.26091), [HTML](https://arxiv.org/abs/2604.26091)
### Authors
T.J. Barton,Chris Constantakis,Patti Hauseman,Annie Mous,Alaska Hoffman,Brian Bergeron,Hunter Goodreau
### Background
本文研究了自治语言模型代理的可靠性问题，这些代理能够将用户的指示转化为实际的工具操作。研究环境是在DX Terminal Pro中进行的21天部署，期间3,505个用户资助的代理在区块链市场中进行了真实ETH的交易。代理通过结构化控制和自然语言策略配置了安全库，但仅代理能够选择正常买卖交易。系统产生了7.5M次代理调用，300K次链上操作，20M美元的交易量，超过5,000ETH部署，并记录了大约700亿次推理令牌和近乎100%的结算成功率。
### Innovation
可靠性不仅来自于基础模型本身，更来源于模型周围的运行层，包括提示编译、类型化控制、策略验证、执行保护、内存设计以及大规模跟踪的可观测性。研究通过预发测试发现了文本基准测试很少测量的失败类型，包括伪造交易规则、费用僵化、数值锚定、周期性交易和误解代币经济学等。有针对性的测试框架改变了提高了这些失败类型的发生率，正式展示了应从用户指令到代理指令、验证行动到结算的完整路径来评估资本管理代理。
### Conclusion
本文展示了具有资本管理能力的代理应该在整个路径中进行评估，从用户指令、生成重点提示、验证行动到最终的结算全过程进行考量，确保代理系统的可靠性。
## 4. `cs.AI` - Distill-Belief: 物理场中闭环逆源定位与表征 [PDF](https://arxiv.org/pdf/2604.26095), [HTML](https://arxiv.org/abs/2604.26095)
### Authors
Yiwei Shi,Zixing Song,Mengyue Yang,Cunjia Liu,Weiru Liu
### Background
闭合回路逆源定位和表征(ISLC)需要移动代理选择定位源并推断潜在场参数的测量值，必须在严格的时间限制下完成。核心挑战在于信念空间的目标：准确的不确定性估计需要昂贵的贝叶斯推理，而使用快速学习的信念模型则会导致奖励欺骗，即策略利用近似误差而不是真正减少不确定性。
### Innovation
我们提出了Distill-Belief，一个教师-学生框架，将正确性和效率分离。Bayes-correct粒子滤波教师保持后验并提供密集的信息增益信号，而紧凑的学生将后验 distilled 成为用于控制的信任统计数据和用于停止的不确定性证书。部署时，仅使用学生，从而每个步骤的成本保持不变。
### Conclusion
在七个场模态和两个压力测试上的实验表明，Distill-Belief能够一致地降低感知成本并提高成功率、后验收缩、估计精度，并减轻奖励欺骗。
## 5. `cs.AI` - 推理 vs. 组合性：神经符号系统中推理的非互补性 [PDF](https://arxiv.org/pdf/2604.26521), [HTML](https://arxiv.org/abs/2604.26521)
### Authors
Mahnoor Shahid,Hannes Rothe
### Background
现代神经网络在组合推理方面的构成泛化仍然存在根本性的弱点，限制了其在需要离分布推理的领域中的鲁棒性和适用性。神经符号人工智能领域的一个核心但未经验证的假设是，组合推理将会作为成功符号定位的副产品出现。本文通过系统性的实证分析挑战了这一假设，并拆分了符号定位和推理的贡献。利用形式化的泛化分类法进行评估，研究发现，仅依赖符号定位训练的模型无法泛化，而我们的完整iLTN模型，在感知定位和多步推理联合训练的情况下，实现了所有任务的高零样本准确率。
### Innovation
本文引入了迭代逻辑张量网络（$i$LTN），这是一种为多步演绎设计的完全可微架构。利用形式化的泛化分类法，研究发现通过感知定位训练的模型无法泛化，而我们的完整iLTN模型，在感知定位和多步推理联合训练的情况下，实现了所有任务的高零样本准确率。
### Conclusion
研究表明，尽管符号定位是必要的，但单独符号定位是不足以泛化的。这表明推理不是一种自发的特性，而是一种独特的需要显式学习目标的能力。
## 6. `cs.AI` - 在压力之下翻译：面向危机沟通的领域感知大模型 [PDF](https://arxiv.org/pdf/2604.26597), [HTML](https://arxiv.org/abs/2604.26597)
### Authors
Antonio Castaldo,Maria Carmen Staiano,Johanna Monti,Sheila Castilho,Francesca Chiusaroli
### Background
及时可靠的多语言通信在自然灾害和人为灾害中至关重要，但有效解决危机时期沟通的解决方案受限于高质量并列数据的稀缺性。
### Innovation
提出了一种领域适应性管道，通过从通用语料库中检索和筛选数据来扩展小型参考语料库，然后使用该数据集微调小型语言模型进行危机领域翻译，并采用偏好优化使其输出偏向CEFR A2级英语。自动和人工评估表明，此方法在提高可读性的同时保持了强烈的充分性。
### Conclusion
我们的研究结果表明，在无法实现全面多语言覆盖的情况下，简化英语结合领域适应可以作为一种实际的危机应急沟通语言载体。
## 7. `cs.AI` - DUAL-BLADE: 边缘LLM推理中的双路径NVMe直接KV缓存卸载 [PDF](https://arxiv.org/pdf/2604.26557), [HTML](https://arxiv.org/abs/2604.26557)
### Authors
Bodon Jeong,Hongsu Byun,Youngjae Kim,Weikuan Yu,Kyungkeun Lee,Jihoon Yang,Sungyong Park
### Background
随着大型语言模型（LLM）推理在边缘AI系统中的广泛应用，对内存预算紧张环境下的高效执行提出了挑战。尤其是Key-Value (KV)缓存的存储需求往往超过了设备内存的限制。尽管基于NVMe的数据卸载技术提供了扩展的存储容量，但现有的基于文件的设计需要依赖内核页缓存，这在面对内存压力时会导致缓存碰撞、不可预测的延迟和高的软件开销。
### Innovation
DUAL-BLADE是一种双路径KV驻留框架，它可以动态地将KV张量分配到页缓存路径或NVMe直接路径，依据运行时的内存可用性。NVMe直接路径通过映射KV张量为连续的逻辑块地址（LBA）区域，绕过了文件系统，提供了低开销的直接存储访问。此外，DUAL-BLADE还引入了自适应流水线并行性，以重叠存储I/O与GPU DMA，从而提高推理吞吐量。
### Conclusion
评估结果表明，DUAL-BLADE显著缓解了I/O瓶颈问题，将预填充和解码延迟分别降低了33.1%和42.4%，同时在各种内存预算范围内提高了固态硬盘的利用率2.2倍。
## 8. `cs.AI` - 通过指令工程实现多代理代码生成的TDD治理 [PDF](https://arxiv.org/pdf/2604.26615), [HTML](https://arxiv.org/abs/2604.26615)
### Authors
Tarlan Hasanli,Shahbaz Siddeeq,Bishwash Khanal,Pyry Kotilainen,Tommi Mikkonen,Pekka Abrahamsson
### Background
大型语言模型（LLMs）加速了软件开发过程，但往往在无约束的工作流程中表现出不稳定、非确定性和对开发纪律遵守不严格的特性。测试驱动开发（TDD）提供了一种结构化的红（Red）、绿（Green）、重构（Refactor）开发流程，但现有基于LLM的方法通常将测试用作辅助输入而非强制性的过程约束。
### Innovation
提出了一个AI原生的TDD框架，将经典TDD原则转化为结构化的提示级和工作流级治理机制。开发的系统通过分离模型提议和确定性引擎的权威性来形成分层架构，强制执行阶段顺序、有限修复循环、验证门和原子突变控制，以提高稳定性和重现性。
### Conclusion
描述了架构并讨论了直接将软件工程纪律编码到指令协调中的方法，认为这是实现可靠LLM辅助开发的有前途的方向。
## 9. `cs.AI` - SynSur: 一种综合性的生成管道，用于合成工业表面缺陷的生成和检测 [PDF](https://arxiv.org/pdf/2604.26633), [HTML](https://arxiv.org/abs/2604.26633)
### Authors
Paul Julius Kühn,Mika Pommeranz,Arjan Kuijper,Saptarshi Neil Sinha
### Background
工业缺陷检测中基于模型的学习瓶颈往往不是由模型容量限制决定的，而是由标记缺陷数据的稀缺性决定的：缺陷罕见，注解成本高昂，并且收集平衡训练集的速度较慢。
### Innovation
提出了一种从头到尾的合成缺陷生成和注解管道，结合了基于视觉-语言-模型的提示、LoRA调整的扩散、蒙版引导的补全和自动标签推导的样本过滤。该管道展示了用现实的合成样本来克服数据稀缺性的潜力，同时在具有挑战性的球丝杠偏坑缺陷数据集和手机屏幕表面缺陷分割数据集子集上进行了评估，以测试跨域转移。分析了管道的关键阶段，包括提示构建、LoRA选择和DreamSim以及CLIPScore的样本过滤，以理解哪些合成样本既是现实又是有用的。
### Conclusion
综合研究表明，虽然仅使用合成训练无法替代真实数据，但在与真实数据结合使用时，可以保持性能并实现选定的BSData训练策略的适度增益。梅德斯转移研究表明，管道结构可以应用于第二个工业检查领域，但同时也突显了领域特定适应和注解质量控制的重要性。总体而言，该研究证明了基于扩散的工业缺陷合成的强大力量，主要在于加强稀缺的真实数据集，而不是取代它们。
## 10. `cs.CL` - 不同隐私预算下的差异隐私文本重写重塑语言风格 [PDF](https://arxiv.org/pdf/2604.26656), [HTML](https://arxiv.org/abs/2604.26656)
### Authors
Stefan Arnold
### Background
该研究探讨了通过利用语言模型生成能力从词级到句级进行文本去识别化的方法，这种方法可以在形式上提供隐私保证与保持语句连贯性之间找到平衡。然而，这种隐私保护对文本语言风格的影响尚未得到充分研究。
### Innovation
研究通过对不同隐私约束条件下文本重写进行多维度风格分析，发现隐私性带来的代价远超出词汇变化，语言功能发生了系统性变化，例如互动标记、情境参考和复杂从句的严重流失。此外，研究对比了自回归重写和双向替换在不同隐私预算下的效果，揭示了尽管这种风格盲清洗可以保留语义内容，但过度同质化了人类创作文本中的细腻风格差异。
### Conclusion
在一定隐私预算下，无论自回归重写还是双向替换，最终都会趋向于一种无涉且缺乏说服力的语言风格，这虽然保护了语义内容，但结构性地同质化了个性化的人类对话风格标志，减少了语言多样性和复杂性。
## 11. `cs.CL` - OCR-Memory：面向长周期代理记忆的光学场景检索 [PDF](https://arxiv.org/pdf/2604.26622), [HTML](https://arxiv.org/abs/2604.26622)
### Authors
Jinze Li,Yang Zhang,Xin Yang,Jiayi Qu,Jinfeng Xu,Shuo Yang,Junhua Ding,Edith Cheuk-Han Ngai
### Background
随着自主大型语言模型（LLM）代理越来越多地在涉及长期、互动的场景中运行，成功的关键在于能够利用长时间段的经验。然而，现有的代理记忆系统受到文本上下文预算的限制：存储或重新访问原始轨迹会耗费大量的文本标记，而摘要和仅文本检索则会牺牲信息准确性并且导致证据碎片化。因此，需要一种新的方法来解决这一问题。
### Innovation
提出了一种名为光学场景检索记忆（OCR-Memory）的记忆框架，该框架利用视觉模态作为代理经验的高密度表示，能够在检索时几乎是无提示负担的情况下保留任意长的历史。具体来说，OCR-Memory将历史轨迹以带有唯一视觉标识的图像形式进行渲染，通过一种称为‘定位并转录’的检索机制，借助视觉锚点选择相关区域并检索相应的精确文本，避免了自由形式的生成和减少了幻觉的发生。实验结果表明，即使在严格的上下文限制下，光学编码也能够增加有效的记忆容量并保护证据的准确性。
### Conclusion
实验结果显示，在长期代理基准测试中，OCR-Memory在严格上下文限制下持续表现出优点，表明光学编码可以同时增加记忆容量并保持证据的真实性。
## 12. `cs.CL` - SAGE: 一个增强图结构的策略感知生成框架以进行在线咨询。 [PDF](https://arxiv.org/pdf/2604.26630), [HTML](https://arxiv.org/abs/2604.26630)
### Authors
Eliya Naomi Aharon,Meytal Grimland,Avi Segal,Loona Ben Dayan,Inbar Shenfeld,Yossi Levi Belz,Kobi Gal
### Background
有效的心理咨询服务是一个复杂的理论驱动过程，需要同时整合心理框架、实时情绪信号和干预计划。这种临床推理对于安全性和治疗效果至关重要，但通常在通用大型语言模型（LLMs）中缺失。现有模型无法有效提供结构化的临床知识和生成式人工智能之间的桥梁。
### Innovation
本文介绍了一种名为SAGE（Strategy-Aware Graph-Enhanced）的新型框架，旨在填补结构化临床知识和生成式AI之间的空白。SAGE构建了一个异类图，统一了对话动态与基于心理的层级，明确地将互动建立在理论驱动的词汇中。首先，使用Next Strategy Classifier识别最佳治疗干预方案。随后，Graph-Aware Attention机制将图解结构信号投影到软提示中，使LLM生成的响应保持临床深度。SAGE通过自动评估指标和专家人类评估都优于基线模型，在策略预测和推荐回应质量方面表现出色。
### Conclusion
SAGE通过提供可操作的干预建议，成为用于高风险危机咨询的一流支持决策工具，旨在增强人类的专业能力。
## 13. `cs.CL` - 从黑盒信心到可测量的临床AI信任：基于证据、监督和分阶段自主性的框架 [PDF](https://arxiv.org/pdf/2604.26671), [HTML](https://arxiv.org/abs/2604.26671)
### Authors
Serhii Zabolotnii,Viktoriia Holinko,Olha Antonenko
### Background
当前临床人工智能的信任度不能仅通过模型准确度、生成流畅性和总体积极的用户印象来衡量。在医学领域，必须将信任作为可度量的系统特性来工程化，并基于证据、监督和AI自主权的操作边界。文章提出了一个以证据、监督和分阶段自主为主要原则的实用框架。
### Innovation
提出了一个实用的框架，通过结合确定性的核心、针对特定患者的AI助手进行上下文验证、多级模型升级机制以及人类监督层来进行验证、升级和风险控制，而不是用端到端的黑盒模型全面取代确定性临床逻辑。该方法通过分类驱动的模块性提示来逐步扩大临床深度，而在实际案例上的仔细评估与被保护的临床上下文和纪律化的提示结构相结合。
### Conclusion
基于度量原则(测量不确定性、校准、溯源性)提出了衡量信任的一系列指标，使得从架构的每一层来看，信任度的评估可以实现定量而非主观。可信赖的临床AI不是一个个体模型的特性，而是对证据追溯、人类监督、分阶段升级和渐进式行动权利的系统设计的成果。
## 14. `cs.CL` - Swap distance minimization shapes shapes the order of object and verb in languages of the world [PDF](https://arxiv.org/pdf/2604.26726), [HTML](https://arxiv.org/abs/2604.26726)
### Authors
Jairo Rios-El-Yazidi,Ramon Ferrer-i-Cancho
### Background
语言系统的主语宾语序（SOV）和主宾语序（SV）O）））在世界各地的变化中占一个普遍趋势。。。该文认为尽管存在某种主导顺序，如跨越语言家族和和宏观区域仍然存在一些不遵循这种预期的语言。近年来研究者们根据这种情况构建了相应的模型。但这仍然未能完全解释所有语言中的主语宾语序和主宾语序的变化。
### Innovation
本文提出了一种新的观点，即语言中主语宾语序和主宾语序的排列并非完全随机或而是受到交换距离最小化原则的影响。这意味着即使在存在主导顺序的语言中当主导顺序为SOV或或者SV
### Conclusion
无论存在与否主导顺序都是交换距离最小化规则塑造了语言中主宾和主宾语序排列的前提条件。这提供了一种新的解释语言系统现象的框架和观点。
## 15. `cs.CL` - 在监督学习下，哪种语言最容易被语言模型建模？ [PDF](https://arxiv.org/pdf/2604.26844), [HTML](https://arxiv.org/abs/2604.26844)
### Authors
Nadine El-Naggar,Tatsuki Kuribayashi,Ted Briscoe
### Background
许多已知的语言在特征配置上共享某些共同模式，形成了特征组合从极为罕见到非常常见的光谱。一个核心问题是，哪些因素能导致这些类型的倾向可以被预测，尤其是语言模型的学习偏置是否足以重现这些模式。已有研究未将学习场景纳入分析，本文则探讨了模型的归纳偏置如何受学习场景影响。
### Innovation
引入了监督学习（如课程学习）作为语言模型的学习场景，考察其如何影响模型的归纳偏置。通过将现有语言模型的研究（El-Naggar等，2025a，b）扩展到包含简单版的课程学习变体，发现课程学习显著影响了语言模型的显性偏置。
### Conclusion
课程学习对语言模型的归纳偏置产生了显著影响，表明学习场景可能对如何再现语言的特征组合具有重大作用。进一步的研究可以通过不同的学习场景来进行探讨，以更好地理解语言建模过程中的挑战与解决方案。
## 16. `cs.CL` - MoRFI: Monotonic Sparse Autoencoder Feature Identification [PDF](https://arxiv.org/pdf/2604.26866), [HTML](https://arxiv.org/abs/2604.26866)
### Authors
Dimitris Dimakopoulos,Shay B. Cohen,Ioannis Konstas
### Background
大型语言模型（LLMs）在预训练阶段主要通过预测下一个词获得大部分事实知识，而在后续的后训练阶段通常会引入超出参数知识的新事实，导致幻觉现象。虽然监督微调（SFT）已证明可能加剧这一问题，但其背后的机制仍不完全清楚。
### Innovation
作者进行了一项受控的微调实验，专注于闭卷问答（closed-book QA），并发现潜在方向因果性地导致了幻觉。具体而言，作者对Llama 3.1 8B、Gemma 2 9B和Mistral 7B v03三个模型分别进行了七个不同的单问答数据集的微调，控制了新知识的比例和训练回合数。通过在测试集上的表现验证，发现逐步引入新知识会增加幻觉现象，且训练时间越长，效应越明显。作者利用预训练的稀疏自编码器（SAEs）分析各种检查点的残差流激活，并提出了Monotonic Relationship Feature Identification（MoRFI）方法，用于捕捉因果相关特征。MoRFI筛选出自编码器特征，这些特征对目标属性的控制自适应数据混合物表现出单调响应。
### Conclusion
我们发现，接触未知事实会破坏模型沿一系列方向检索存储知识的能力。我们的管道能够在不同模型中可靠地发现这些方向，通过单一潜在变量的干预恢复知识。
## 17. `cs.CV` - 高维噪声到低维流形：复杂退化条件下降质 hyperspectral 图像分类的流形空间扩散框架 [PDF](https://arxiv.org/pdf/2604.26279), [HTML](https://arxiv.org/abs/2604.26279)
### Authors
Boxiang Yang,Ning Chen,Xia Yue,Yichang Luo,Yingbo Fan,Haoyuan Zhang,Haoyu Ma,Jun Yue,Shanjun Mao
### Background
近年来，高光谱图像（HSI）分类在遥感领域引起了越来越多的关注。然而，HSI 数据本质上是高维度但低秩的，有助于区分的有用信息集中在低维度的潜在流形上。在实际遥感场景中，多个退化因素的叠加使这种内在的流形结构受到破坏，使得样本远离原始的低维度分布，并引入了大量冗余和非区分性变化。
### Innovation
本文提出了一种流形空间扩散框架（MSDiff），专门用于处理复杂退化条件下的稳健高光谱分类。具体而言，该方法通过一个区分性的光谱-空间重建任务，将高维度和受影响的 HSI 数据映射到一个紧凑的低维度流形中，从而保留类别语义并减少冗余变化。然后，应用基于扩散的生成模型来正则化流形内的光谱-空间分布，并逐步细化和稳定潜在特征对抗残余退化。
### Conclusion
在多个高光谱基准上的实验结果表明，该框架在多种复合退化设置下能稳定地优于现有方法。代码将在此处 available: https://... 
## 18. `cs.CV` - 空间科学实验中模式生物多目标运动驱动跟踪 [PDF](https://arxiv.org/pdf/2604.26321), [HTML](https://arxiv.org/abs/2604.26321)
### Authors
Jianing You,Han Wang,Kang Liu,Jiale Ding,Fengjie Chu,Zihan Guo,Shengyang Li
### Background
自动化动物行为分析依赖长时间、可解释的个体轨迹；然而，在微重力条件下获得的生命科学实验视频中，进行多动物跟踪仍高度具有挑战性，原因在于微弱的外观线索、低质量成像、复杂的行为机动性和频繁的互动。
### Innovation
该研究首先构建了SpaceAnimal-MOT数据集以表征生命视频中在微重力条件下的运动复杂性和长期身份保持的挑战。其次，提出了ART-Track（自适应稳健跟踪）框架，该框架适用于此类设置。具体来说，引入了多模型运动估计以处理突然的机动和非线性运动，设计了基于运动状态的关联来减少密集互动和暂时失配时的身份切换，以及不确定性自适应融合，以动态平衡预测可靠性变化时的空间和运动线索。
### Conclusion
实验结果显示，ART-Track在斑马鱼和果蝇序列中显著减少了身份切换，并在遮挡、变形和高密度互动下保持更稳定的关联，从而为后续定量行为分析提供了更可靠的跟踪基础。代码已公开可用。
## 19. `cs.CV` - 在利用合成样本生成解决医用图像分类中的类别和域不平衡问题下的联邦学习 [PDF](https://arxiv.org/pdf/2604.26324), [HTML](https://arxiv.org/abs/2604.26324)
### Authors
Martina Pavan,Matteo Caligiuri,Francesco Barbato,Pietro Zanuttigh
### Background
在利用深度学习技术进行医学成像分析时面临严格的数据隐私限制、成像设备的异构性和因病状分布不均衡导致的类别不平衡等关键挑战。
### Innovation
提出了一个名为FedSSG的新型联邦学习框架，该框架解决了由于不同成像设备导致的域偏移问题，并减轻了罕见病状的代表性不足。主要创新在于通过生成合成样本并将这些样本分布在各个客户端，从而提升对未充分代表的病状以及成像设备的覆盖度。
### Conclusion
实验结果表明，该方法显著提高了模型在异质机构间的性能和泛化能力，且客户端的计算开销较小。
## 20. `cs.CV` - 基于眼动时序动态的事件驱动式活体检测：一种探索性的方法 [PDF](https://arxiv.org/pdf/2604.26285), [HTML](https://arxiv.org/abs/2604.26285)
### Authors
Nicolas Mastropasqua,Ignacio Bugueno-Cordova,Rodrigo Verschae,Daniel Acevedo,Pablo Negri
### Background
尽管使用RGB摄像头进行活体检测取得显著性能，在尤其是在受控条件下表现优异，但在不同不同传感器和攻击场景下却常常难以泛化。，背景部分并未完整，原文段落有误，正确表述如下：尽管RGB摄像头在活体检测中取得了显著的性能，在尤其是在在受控条件下表现优异，但其难以在不同传感器和各种攻击场景下泛化。
### Innovation
该工作探索了使用事件摄像头作为运动检测的另类传感方式，其基于一体眼动的时Tempoary分析。事件摄像头能够以微秒级的检测时间捕获小数量的亮度异步变化从而实现对诸如saccades等眼动的精细分析。由于事件驱动特征无法准确复制动态特性地出现了特有的时空模式在事件图中。因此通过设计一种回显攻击录制品的收集协议，我们收集了RGBE-Gaze与回显攻击录制，生成了一个事件驱动式的假人对应用于活体检测。我们分析了来自眼区的事件驱动时序特征，并评估了它们在眼动分割和 live检测分类中的有效性。结果显示事件驱动的表示能够可靠地区分本来和重现序列，并且使用一种刺动卷积神经网络实现高达9 95.37%的准确率。
### Conclusion
总之本研究表明事件驱动的感知具备了对于活体检测的稳健性和低延迟性的潜力。初步的研究发现强调基于事件驱动的技术能够有效地实现活体检测上的贡献。
## 21. `cs.CV` - 学习基于视觉的全向导航：使用单目深度估计的教师-学生方法 [PDF](https://arxiv.org/pdf/2603.01999), [HTML](https://arxiv.org/abs/2603.01999)
### Authors
Jan Finke,Wayne Paul Martis,Adrian Schmelter,Lars Erbach,Christian Jestel,Marvin Wiedemann
### Background
在工业环境中可靠的避障需求依赖于对三维场景的理解，然而目前广泛应用的二维激光雷达（LiDAR）传感器只能感知环境中的单个水平切片，导致难以检测上方或下方的重要障碍物。因此，需要一种新的方法替代或减少对LiDAR传感器的依赖。
### Innovation
本文提出了一种基于视觉的移动机器人导航的教师-学生框架，利用优化政策（PPO算法）和单目深度估计技术，由一个已训练的教师策略利用其对完整机器人足迹的2D LiDAR观测数据进行训练，将其经验知识通过精调的单目深度估计模型转移给一个仅依赖于四个RGB摄像机生成的单目深度图的学生策略。整个推理管道运行在嵌入式平台上，无需外部计算。
### Conclusion
该学生策略在仿真和实际实验中都展示了优于标准二维LiDAR的性能，特别是在导航具有复杂三维几何结构的障碍物时，如悬空结构和低矮物体，表现出更高的成功率。
## 22. `cs.CV` - 使用流形群状和代数状框架进行不连续图像注册 [PDF](https://arxiv.org/pdf/2603.11806), [HTML](https://arxiv.org/abs/2603.11806)
### Authors
Lili Bao,Bin Xiao,Shihui Ying,Stefan Sommer
### Background
传统的Large Deformation Diffeomorphic Metric Mapping (LDDMM) 注册方法基于Lie群，假设速度场的连续性和光滑性，这限制了其在处理滑动边界处的不连续性时的应用。
### Innovation
提出了一种新的数学框架，利用diffeomorphism groupoid和algebroid方法处理滑动过程中出现的不连续滑动。这种方法扩展了Lie群到具有不连续性的diffeomorphism Lie groupoids框架，能够在滑动边界的不连续性区域保持局部的光滑性和整体的一致性，从而克服了LDDMM方法的局限性。
### Conclusion
对该方法进行了严格的数学结构分析，包括Lie algebroids及其双对，并推导出调控不连续变形最优流动的Euler-Arnold方程。数值测试验证了所提出方法的有效性。
## 23. `cs.CV` - 利用物理导向深度学习评估三维运动场在雷达降水.nowcasting中的实用性 [PDF](https://arxiv.org/pdf/2603.13589), [HTML](https://arxiv.org/abs/2603.13589)
### Authors
Peter Pavlík,Anna Bou Ezzeddine,Viera Rozinajová
### Background
时空地理科学数据中的运动估算对于许多环境建模和预测任务至关重要。本文研究了从体积雷达反射率数据直接估算不同高度的运动场的方法，旨在提高基于插值的降水预测的准确性。通过多年的中欧雷达数据集，分析了不同高度运动一致性对降水预测的影响。
### Innovation
提出了一种结合物理信息的深度学习框架，用于直接从体积雷达反射率数据中估算不同高度的运动场。该模型通过引入全可微半拉格朗日外推操作，将三维输入处理为独立的水平切片序列，从而实现高效多高度水平运动的推理。
### Conclusion
估算的运动场在不同高度之间表现出强烈的垂直连贯性，具有高度的相关性，这在现有的基于二维的方法中几乎没有改进。研究结果表明，在垂直连贯性的降水系统中占主导地位的区域，体积运动建模的复杂性可能提供有限的好处，这在时空对流模型的设计中需要仔细考虑。该框架为有效分析体积地理数据中的运动结构提供了一种通用工具。
## 24. `cs.CV` - 用于肝脏MRI肝胆期序列三相序列顺序融合网络 [PDF](https://arxiv.org/pdf/2604.22904), [HTML](https://arxiv.org/abs/2604.22904)
### Authors
Qiuli Wang,Xinhuan Sun,Fengxi Chen,Yongxu Liu,Jie Cheng,Lin Chen,Jiafei Chen,Yue Zhang,Xiaoming Li,Wei Chen
### Background
钆喷酸乙胺增强的MRI对于肝细胞癌的检测和表征至关重要。然而，获取肝胆期（HBP）需要较长的延迟时间，这降低了工作流程效率并增加了运动伪影的风险。
### Innovation
提出了三相顺序融合网络（TriPF-Net），通过利用前期HBP序列的顺序信息来合成HBP图像，该模型在动脉期（AP）和门静脉期（VP）特征可用时会自适应地进行特征融合，通过建模这三个阶段的组织特异性对比剂吸收和排泄动态，确保即使缺少一个或两个动态对比增强序列也能够稳健合成HBP图像。该框架包括增强区域引导编码器和动态特征统一模块，并通过区域引导顺序融合损失优化，以保持生理一致性。此外，还纳入了临床变量，如年龄、性别、总胆红素和白蛋白，以增强生理一致性。
### Conclusion
与传统方法相比，TriPF-Net在两个中心的数据集上表现出优越的性能。在内部数据集上，模型的MAE为10.65，PSNR为23.27，SSIM为0.76。在外部验证数据集上，相应的值为12.41，23.11，0.78。这种灵活的解决方案提高了临床工作流程和病灶描绘，有可能消除HCC成像中延迟HBP获取的需要。
## 25. `cs.CV` - CommFuse: 通过通信分解解和融合消隐分布式LLM训练中的尾时延 [PDF](https://arxiv.org/pdf/2604.24013), [HTML](https://arxiv.org/abs/2604.24013)
### Authors
Rezaul Karim,Austin Wen,Wang Zongzuo,Weiwei Zhang,Yang Liu,Walid Ahmed
### Background
大规模语言模型计算量的快速增加导致计算任务需要分布在如GPU、 TPUs和NP等多种加速器上。 迎这些并的联合策略虽然可以提升计算效率， 焇 但是他们会引入明显的数据通信开重阻碍计算效率。 延传统的方法分例如数据切片和数据并并 会在分布式训练中引入尾时延，
### Innovation
本文提出了名为CommFuse的新颖的通信划分和融合技术来消隐这种尾时延。 在现有的超重方法中 它通过peer-to-peer通信和按需分配计算来 尮分细化联合计算 初체部的方法提供一种用于减少通信 开重的精确算法并 消除了尾延迟。此外, 该方法具有广泛的兼容性 収数据层平行为和张量层多样化并策略包括如TPsp和uppuecessary。
### Conclusion
实验评估表明 该技术一直能够持续地达到较低延迟 宽泛的L LOPS利用效 刜和吞吐量。
## 26. `cs.CV` - 多重一致D-D映射实现零样本3-D视觉定位定D [PDF](https://arxiv.org/pdf/2604.26261), [HTML](https://arxiv.org/abs/2604.26261)
### Authors
Yufei Yin,Jie Zheng,Qianke Meng,Zhou Yu,Minghao Chen,Jiajun Ding,Min Tan,Yuling Xi,Zhiwen Chen,Chengfei Lv
### Background
零样本3D视觉定位（DVGD）在是D为世界（WO）自主AI领域的的一个重要能力，但其发展受到了现有语#D（V#D的的根本限制，这些限制源于不准确的类别和不精确的几何关系，以及空间冗余性。现有方法通常依赖于模糊的3D片段，这导致定位和推理精确性不足。为应对这些挑战，我们提出了一种新的框架，即MCM-VG，通过该框架通过多样的结构一致性建立明确的2-D映射关系，从而精确定位本地化并实现可靠的推理解。首先进行语义对对对齐，通过将LLM驱动的查询解析与粗略精细的D-DD映射结合，继而是实例正交重构，通过借助LLM指导下的D-D分割重建目标。通过上述方法，不仅消除了空间冗余，还还优化了RGB与BE航眼图的配对，生成简洁的D-提示，以服务于视觉-语言模型进行D-推理解。我们在这两项基准测试（ScanRefer和Nr3D上上上的进行了评估，结果显示MCM-VG，是位居领先地位，特别是在零-shB：的零样本3D视觉定位任务上，实测准确性超过了现基准直6.4%和4.4%D的显著幅度。
### Innovation
本文提出了一种创新的框架——MCM-VG，通过多一致的一致性，明确建D-D映射关系，从而实现精确的本地化D和可靠的推理。具体创新点如下：11在种新的语义对齐方法，结合了LLM驱动的查询解析D和粗略精细的D-D映射；提供了一种实例导向的正交重构方法，通过LLM指导下的的DD分割重建目标；并开发了D种解决方案，解除了空间冗余，优化了视RGB与3D航眼图的配对，生成简洁的D-L提示，以服务于视觉-语言模型进行D-D推理解。与现有方法相比，MCM_VGD不仅提高了定位和推理的精度，还在实测零样本3-DVGD实验中取得了显著的性能提升，达6.4%和4.4%D。
### Conclusion
我们提出了MCM-VG，，，该框架通过多关注的一致映射D关系，大幅度提高了零样本D-DVGD的定位精刺性和信可靠性。MCM-VGD在显著提升了在D-shrP零样本3-DVGD任务上的相较于其他当前基线方法的准确性，超出6.4%和和4.4%D。通过组合LLM驱动查询映射，实例导向负交重构以及生成简洁的视觉提示，MCM-VG构建了一个可靠D确S切、可靠能D地映对或和视觉一语言D模D进行类型理解。这是D款在领域的一项重大进展，为3D世界自主AI的能力提供了强有力支撑。
## 27. `cs.LG` -  adversarial robustness of TFK neural networks [PDF](https://arxiv.org/pdf/2604.25965), [HTML](https://arxiv.org/abs/2604.25965)
### Authors
Yuxuan Hou
### Background
深度学习模型在关键领域领域中得到了广泛应用，但是仍然容易受到对抗攻击的攻击。。这些攻击的性质和影响是当前学术研究的主要背景。。人们注意到尽管深度学习模型在许多领域表现出色色强大的的性能,其在对抗性攻击面前仍然是脆弱的。此外研究者们也对神经网络在非参数回归中的对抗鲁棒性性进行了探索
### Innovation
本文研究了在非参数回归情境下TKF神经网络的对抗鲁棒性性首次建立了Sobobolev空间下的对抗回归最优率并通过梯度下降法训练TKF神经网络证明了可以达到达到最优率
### Conclusion
然而在参数泛利拟条件下我们证明了最小模插值的网络对于对抗扰动仍然很脆弱
## 28. `cs.LG` - 学习黑洞吸积码的神经算子代理模型 [PDF](https://arxiv.org/pdf/2604.25985), [HTML](https://arxiv.org/abs/2604.25985)
### Authors
Matthias Nägele,Cedric Bös,Chester Tan,Christian M. Fromm,Ingo Scholtes,Karl Mannheim
### Background
广义相对论磁流体力学（GR-MHD）模拟对于研究黑洞吸积、相对论性喷流以及磁场重连至关重要，但其计算成本极大地限制了系统参数探索的范围。为了克服这一限制，本研究利用数值神经算子近似对由黑洞吸积码（BHAC）生成的两种天体物理相关的模拟场景进行了研究。
### Innovation
本研究首次将物理告知的神经算子应用于特殊相对论阻力磁流体力学（SRRMHD），并首次探讨了这类模型在SRRMHD中解决等离子体形成的能力。此外，本研究还首次在MHD模拟中直接应用了神经算子模型在固定分辨率适配网格上。
### Conclusion
通过物理指示的傅里叶神经算子模型，研究实现了在数据不足的时间步长上重现等离子体形成的现象，这是数据基线模型无法实现的。同时，在特殊相对论磁流体力学（SRMHD）中创建的脊鞘相对论性喷流的进化过程中，研究成功应用神经算子直接在高分辨率适配网格上，展示了线性注意力在处理长序列数据中的必要性。
## 29. `cs.LG` - QERNEL：可扩展的大电子模型 [PDF](https://arxiv.org/pdf/2604.26018), [HTML](https://arxiv.org/abs/2604.26018)
### Authors
Khachatur Nazaryan,Liang Fu
### Background
该研究介绍了QERNEL，一种可以变分求解参数化多电子哈密顿家族的神经波函数模型，并能够在单一模型中捕捉整个参数空间中的基态。该模型结合了FiLM基参数条件和高效的比例架构元素（专家混合和分组查询注意力），在保持表达能力的同时大大降低了计算成本。
### Innovation
QERNEL通过结合FiLM基参数调整、专家混合和分组查询注意力机制，在单一模型中捕捉了半导体莫里埃异质层中多电子系统的基态，能够在计算成本较低的情况下提高表达能力。并且通过解凝固哈密顿系统的薛定谔方程，QERNEL能够捕捉到量子液体和晶体状态之间的尖锐相变，揭示交互能量和电荷密度的突然变化。
### Conclusion
这项工作为莫里埃量子材料建立了一个基础模型，并朝向固体中的大型电子模型的可扩展架构迈进。
## 30. `cs.LG` - 预测辅助的增量强连通分量 [PDF](https://arxiv.org/pdf/2604.26062), [HTML](https://arxiv.org/abs/2604.26062)
### Authors
Ronald Deng,Samuel McCauley,Aidin Niaparast,Helia Niaparast,Bennett Ptak,Shirel Quintanilla,Shikha Singh,Nathan Vosburg
### Background
该领域旨在利用机器学习预测来设计超越最坏情况的更快算法。本文使用这一框架为增量强连通分量问题设计了基于预测的数据结构。
### Innovation
本文提出了一个基于预测的增量强连通分量问题的数据结构。该算法接收可能错误的边序列预测，并利用该预测预计算部分解以支持快速插入操作。实验结果表明，理论上预测有助于实际运行时间改进，并且性能随着预测错误的增加而平稳下降。
### Conclusion
证明该算法在良好预测下几乎达到最优边界，其性能随着预测误差的增加而平稳下降。实验证明此理论预测实践中的运行时间改进。
## 31. `cs.LG` - 对长文档总结事实一致性度量进行压力测试 [PDF](https://arxiv.org/pdf/2511.07689), [HTML](https://arxiv.org/abs/2511.07689)
### Authors
Zain Muhammad Mujahid,Dustin Wright,Isabelle Augenstein
### Background
评估抽象总结文本的事实一致性仍然是一项巨大的挑战，尤其是在处理长文档时，因为传统的度量标准在输入长度限制和长距离依赖方面存在问题。本文系统性地评估了六个广泛使用的无参照事实一致性度量在长文档环境中的可靠性，这些度量原本是为短文本总结设计的。
### Innovation
本文通过应用七种保留事实性的扰动——改写、简化、同义词替换、逻辑等价否定、词汇减少、压缩和插入原始文本——测试度量的稳健性，并且进一步分析了它们对检索上下文和陈述信息密度的敏感性。本文的研究结果揭示了现有短期度量生成在语义等效总结上不一致分数的问题，以及随信息密集度的增加可靠性下降的现象。
### Conclusion
扩展检索上下文可以在某些领域提高稳定性，但没有一种度量在长上下文条件下能一致保持事实一致性。最后，本文的结果指出了改进事实一致性评估的具体方向，包括跨段推理、上下文感知校准和基于含义保留变换的训练，以增强长文档总结的鲁棒性。所有相关代码、扰动数据和脚本均可在此链接中找到：this https URL
## 32. `cs.LG` - 使用自适应广度深度检索的自主知识图谱探索 [PDF](https://arxiv.org/pdf/2601.13969), [HTML](https://arxiv.org/abs/2601.13969)
### Authors
Joaquín Polonuer(1,2),Lucas Vittor(1),Iñaki Arango(1),Ayush Noori(1,3),David A. Clifton(3,4),Luciano Del Corro(5,6),Marinka Zitnik(1,7,8,9) ((1) Department of Biomedical Informatics, Harvard Medical School, Boston, MA, USA, (2) Departamento de Computación, FCEyN, Universidad de Buenos Aires, Buenos Aires, Argentina, (3) Department of Engineering Science, University of Oxford, Oxford, UK, (4) Oxford Suzhou Centre for Advanced Research, University of Oxford, Suzhou, Jiangsu, China, (5) ELIAS Lab, Departamento de Ingeniería, Universidad de San Andrés, Victoria, Argentina, (6) Lumina Labs, Buenos Aires, Argentina, (7) Kempner Institute for the Study of Natural and Artificial Intelligence, Allston, MA, USA, (8) Broad Institute of MIT and Harvard, Cambridge, MA, USA, (9) Harvard Data Science Initiative, Cambridge, MA, USA)
### Background
从知识图谱中检索语言模型查询所需的证据需要在广泛的图搜索与多跳遍历之间取得平衡。基于相似性的检索提供广泛的覆盖，但仍是肤浅的，而基于遍历的方法依赖于选择初始探索的种子节点，当查询跨越多个实体和关系时，这种方法可能会失效。
### Innovation
ARK：适应性知识检索工具被引入，它让语言模型能够使用一个包含全局词汇搜索和一跳临近探索的两步工具集来控制广度-深度权衡。ARK交替进行广度导向的发现和深度导向的扩展，减少了对脆弱的种子选择、预设的跳跃深度或检索培训的依赖。ARK根据查询类型调整工具使用，使用全局搜索处理语言密集型查询，使用邻域探索处理关系密集型查询。
### Conclusion
在STaRK上，ARK实现了59.1%的平均Hit@1和67.4%的平均MRR，分别比基于检索和基于代理的无需训练方法提高了平均Hit@1最高31.4%和平均MRR最高28.0%。最后，通过无标记模仿从大型教师中提炼出ARK的工具使用轨迹到一个8B模型中，这在AMAZON、MAG和PRIME数据集上分别提高了Hit@1绝对值7.0、26.6和13.5点，同时保持了高达98.5%的教师Hit@1比率。
## 33. `cs.LG` - ReLoop：基于结构化建模和行为验证的可靠大规模语言模型优化 [PDF](https://arxiv.org/pdf/2602.15983), [HTML](https://arxiv.org/abs/2602.15983)
### Authors
Junbo Jacob Lian,Yujun Sun,Huiling Chen,Chaoyu Zhang,Hanzhang Qin,Chung-Piaw Teo
### Background
大规模语言模型（LLMs）可以将自然语言转换为优化代码，但在执行中可能会出现无法检测的错误。这些模型生成的代码虽然在技术上可能是可行的，但可能包含语义错误，导致问题解决的‘正确性-可行性的差距’可能高达90个百分点。特别是在组合问题上，这种错误尤其明显。目前缺乏有效的机制来准确验证和纠正这些错误。
### Innovation
本文提出了一种名为ReLoop的方法，通过两种互补机制解决上述问题。首先，结构化生成将代码生成分解为四个阶段（理解、形式化、合成与验证），可以在初始阶段就避免建模错误。其次，行为验证通过模拟求解器参数变化来检测生成后的错误，提供了一种外部语义信号，绕过了LLM的自我审查，并不需要具体的目标标准。这两种方法在同一错误结构的不同阶段发挥主要作用，从而显著提高了组合问题的准确性和局部缺陷的检测能力。
### Conclusion
通过结合ReLoop技术，Claude Opus 4.6模型能够实现100%的可执行代码，并在多个基准测试中实现了准确性的提升。研究还发现，狭义调优的示例反馈训练模型容易受到思维连锁提示的模式脆性影响，这种设计限制也是首次被揭示并分析。此外，论文还公开了一个涵盖190个零售优化场景的基准数据集，专用于测试LLMs在处理多约束组合问题时的准确性。
## 34. `cs.LG` - NeuralFLoC:Neural Flow-Based Joint Registration and Clustering of Functional Data [PDF](https://arxiv.org/pdf/2602.03169), [HTML](https://arxiv.org/abs/2602.03169)
### Authors
Xinyang Xiong,Siyuan jiang,Pengcheng Zeng
### Background
在存在相位变异的情况下对功能性数据进行聚类是非常具有挑战性的任务。时间上的对齐偏差会隐藏数据内在的形态差异，降低聚类效果。当前大部分方法将对齐和注册和聚类处理为两个分独的过程，并，并并且依赖严格的参数假设。本研究旨在提出一种称为NeuralFLoC的完全无监督的端到端深度学习框架，用于结合基于神经微分流动态流和谱聚类结合的方法进行联合功能性对齐 on和和聚类。这种方法能够同时学会平滑的逆变形场和针对特定类别的模板。有效区分对齐和幅度变异。通过这种方法建立了通用逼近保证和渐近一致性。通过在功能性数据上的的实验证明，该方法在对齐和 on 萜群中均表现优于现有方法同时对具备对不规则采样和噪声的鲁棒性性以及可表现出可大规模上的的扩展性能力。
### Innovation
NeuralFLoC框架是一个基于神经微分动的平滑逆变形 on和和无监督端到端的深度学习框架。用于联合功能性数据的对 和对对齐和聚类。该框架通过利用神经微分动流与谱谱聚类相结合的方法 on on实现了对齐和 on聚性的唯一区分与二同时使学习过程变得更加平滑解了与现现有的依赖严格参数假设的方法 on on所的局限性 on同时通过均匀逼近保证与及渐近一性的原则 on增强等方面 on保证了 on在算法上的鲁棒性和可对保持了大规模上的的应用扩展能力。
### Conclusion
通过对此研究提出的方法在功能性数据的on on对对对标齐 on onon聚类任务上均展现出了卓越的效果 on on on显著提高了对对背景下 on on不规则采样和带上噪声数据的聚类性能 on on同时保持了较为明显的快速扩展能力。本研究不仅展示了神经桥梁在功能性数据处理方面上的有效应用的潜力 on on on而且通过实验证了算法的有效性 on有效性和鲁棒性性性性在合成上的改进信号同时展示了 on一上一大功能数据处理方法一的未来前景。。 onon
