# 20260414
[![Subscribe_Visitors](https://visitor-badge.laobi.icu/badge?page_id=nituchao.latest_arxiv_analyze_ai_rss)](https://github.com/nituchao/latest_arxiv_analyze_ai)

## 1. `cs.AI` - 规划领域生成中的模型空间推理作为反馈空间中的搜索 [PDF](https://arxiv.org/pdf/2604.08712), [HTML](https://arxiv.org/abs/2604.08712)
### Authors
James Oswald,Daniel Oblinsky,Volodymyr Varha,Vasilije Dragovic,Harsha Kokel,Kavitha Srinivas,Michael Katz,Shirin Sohrabi
### Background
尽管大型语言模型和推理模型的出现为从自然语言描述生成规划领域提供了可能，但实际应用中仍然面临挑战。现有研究表明，虽然语言模型能够辅助领域生成，但生成的领域质量仍较低，难以实际部署。因此，研究如何通过少量符号信息增强的自然语言描述生成高质量的规划领域成为关键问题。
### Innovation
本文研究了一种代理语言模型反馈框架，利用符号信息增强的自然语言描述生成规划领域。通过利用标记物、VAL计划验证器输出等多种反馈机制优化领域质量，提出了模型空间推理作为反馈空间中的搜索方法。这种方法能够在优化过程中逐步提高规划领域质量。
### Conclusion
实验结果表明，通过符号信息增强和利用多形式的反馈机制进行优化搜索，能够显著提高生成的规划领域质量。这种方法为实际应用中的高质量规划领域生成提供了新的方法和思路。
## 2. `cs.AI` - 参数化表达MSO公式模型的复杂性 [PDF](https://arxiv.org/pdf/2604.08707), [HTML](https://arxiv.org/abs/2604.08707)
### Authors
Petr Kučera,Petr Martinek
### Background
单调二阶逻辑（MSO2）在参数化复杂性领域中扮演了重要的角色，由于Courcelle定理。该定理指出，检查给定图是否具备通过给定MSO2公式定义的性质可以由图的树宽和公式的大小为参数的参数化线性时间算法解决。
### Innovation
作者通过展示MSO2公式带自由变量的模型可以以参数化的线性方式表示决策图的形式，进一步扩展了Courcelle定理。特别地，作者指出了当考虑树宽时的送句决策图（SDD）的参数化线性上界，及当考虑路径宽时的有序二进制决策图（OBDD）的参数化线性上界。作者还基于Razgon的下界证明，指出存在MSO2公式和树宽有界图的类，不具有参数化于树宽的OBDD。
### Conclusion
研究结果为Courcelle定理提供了新的视角，并将其与知识表示的领域联系起来。
## 3. `cs.AI` - 从场可视化中隐现的视觉到符号化分析解推断 [PDF](https://arxiv.org/pdf/2604.08863), [HTML](https://arxiv.org/abs/2604.08863)
### Authors
Pengze Li,Jiaquan Zhang,Yunbo Long,Xinping Liu,Zhou wenjie,Encheng Su,Zihang Zeng,Jiaqi Liu,Jiyao Liu,Junchi Yu,Lihao Liu,Philip Torr,Shixiang Tang,Aoran Wang,Xi Chen
### Background
利用AI辅助进行科学推理时，从直观观察中恢复物理场的分析解是一项基本但尚未充分开发的能力。本文关注的是二维线性稳态场的视觉到符号分析解推断（ViSA），即给定可视化场及其一阶导数和少量辅助元数据的情况下，模型必须生成一个完整的数值常量实例化的SymPy表达式。这一任务挑战了现有的AI系统，尤其是在处理复杂场可视化数据时。
### Innovation
本文提出了一种名为ViSA-R2的新方法，并与一个自验证、以解为中心的思维链管道（遵循物理学家般的路径）进行了匹配，该管道包括结构模式识别、解假设、参数推导、一致性和验证。同时发布了一个名为ViSA-Bench的合成基准，覆盖了30种线性稳态场景，并提供了验证的分析/符号注释。通过数值准确性、表达式结构相似性和字符级准确性对预测结果进行了评估。研究结果显示，使用8B参数量的开放权重模型Qwen3-VL，ViSA-R2在标准化协议下优于强大的开源基线和评估中的封闭源前沿大规模语言模型。
### Conclusion
本文通过引入ViSA-R2方法和自验证管道，显著提升了从场可视化推断分析解的能力，尤其是在数值精度和表达式结构相似性方面。同时，发布的ViSA-Bench合成为后续研究提供了坚实的数据基础，并展示了未来的性能改进潜力。
## 4. `cs.AI` - EvaluateKedge:：基于执行约束的安全与证据链管理自主变化 [PDF](https://arxiv.org/pdf/2604.08601), [HTML](https://arxiv.org/abs/2604.08601)
### Authors
Jun He,Deying Yu
### Background
随着自主人工智能代理的兴起，由于它们的自主性和复杂性交互性质等原因，暴露出API服务平台至基于API为中心的架构中的根本缺陷：即这些概率化系统缺乏足够的上下文协调协调与确保足够的的安全机制。这使得直接执行状态変化带来潜在的风险。本研究背景在于针对这一问题问题隙，讨论介绍了攻坚战 Kgde（IntroduceKedge）协议
### Innovation
该论文的创新之处在于引入了一场变革性的协议称为攻坚战 Kgde（IntroduceKedge），），该该重新定义了代理行为的过程，不再仅仅是API调用的即时结果
### Conclusion
攻坚战 Kgde（采用了意图到执行证据链（IEC（）以通过使用这项技术方法把
## 5. `cs.AI` - Sustained Impact of Agentic Personalization in Marketing: A Longitudinal Case Study [PDF](https://arxiv.org/pdf/2604.08621), [HTML](https://arxiv.org/abs/2604.08621)
### Authors
Olivier Jeunen,Eleanor Hanna,Schaun Wheeler
### Background
在消费者应用程序中，客户关系管理（CRM）历来依靠手动优化基于规则的消息的消息 邮件等消息。。。 跻加背景
### Innovation
研究利用代理商基础设施，在一个月的时间内，针对一个大规模用户基数进行营销消息个人化处理，并通过两段时间分别活跃管理和被动管进行数据收集和在活跃期期间人类管理者直接杂志内容识别特定受众而在被动期代理商则自主从固定的组件库内运行本研究创新点在于展示了自动化的代理机构能够在无需人类介入的时期内长期维护个人化营销效果。
### Conclusion
本研究表明尽管手动管理在参与指标上表现最佳在长时间内自动代理仍然能够成功地保存这些积极的参与效果这种发现表明人类干预驱动战略初发现最初而自动化代理则能确保可长期的保留结果和维护这两个效果之间发挥了相得益互补的关系
## 6. `cs.AI` - SafeAdapt：深度强化学习中的可证明安全策略更新 [PDF](https://arxiv.org/pdf/2604.09452), [HTML](https://arxiv.org/abs/2604.09452)
### Authors
Maksim Anisimov(Imperial College London),Francesco Belardinelli(Imperial College London),Matthew Wicker(Imperial College London)
### Background
在安全关键任务中部署强化学习（RL）代理时，安全保证是必不可少的。然而，部署环境常常具有非稳定动力学或存在变动的性能目标，这就需要对已学习的策略进行更新。这导致了一个基本挑战：如何在保持先前任务中其安全属性的前提下更新RL策略？现有的大多数方法要么不能提供正式的保证，要么仅在后验验证策略的安全性。
### Innovation
本研究提出了一种新的先验方法，通过引入Rashomon集来在连续RL中实现安全策略更新。Rashomon集是一个保证在演示数据分布下满足安全约束的策略参数空间区域。通过将任意RL算法用于更新策略后的更改投影到Rashomon集上，可以提供形式上的、可证明的安全性保证。在网格世界导航环境（Frozen Lake和Poisoned Apple）中，该方法保证在下游适应过程中存在先验的可证明确定性安全性。
### Conclusion
相比之下，基于正则化的基线方法会忘记安全约束，而本方法则能够在保证安全的前提下实现强大的适应。
## 7. `cs.AI` - BERT-as-a-Judge: 一种用于高效参考导向大语言模型评估的稳健替代方法 [PDF](https://arxiv.org/pdf/2604.09497), [HTML](https://arxiv.org/abs/2604.09497)
### Authors
Hippolyte Gisserot-Boukhlef,Nicolas Boizard,Emmanuel Malherbe,Céline Hudelot,Pierre Colombo
### Background
准确的评估是大语言模型生态系统的核心，指导着模型的选择和跨各种应用场景的下游采用。然而，在实践操作中，生成输出的评估通常依赖于严格词汇方法来提取和评估答案，这可能会混淆模型的真实问题解决能力与其对预定义格式要求的遵守。近期的作为审查员的人工智能方法虽然能通过评估语义正确性来缓解这一问题，但也会引入大量的计算开销，使其评估过程变得昂贵。因此，有系统地探讨了词汇评估的局限性，并展示了这些方法与人类判断的相关性较差。
### Innovation
我们提出了BERT-as-a-Judge，一种基于编码器的方法，在参考导向生成设置中评估答案正确性，可以通过轻量级训练在合成标注的问答候选参考三元组上运行，适用于具有不同输出措辞变化的场景，与词汇基准方法相比，它表现更优，与更大规模的模型相当，为两种方法之间提供了折衷方案，从而实现可靠的、可扩展的评估。
### Conclusion
通过广泛的实验，我们对BERT-as-a-Judge的表现提供了详细的见解，为实际操作提供实用指导，并释出了所有项目素材以促进下游采用。
## 8. `cs.AI` - 有限多代理通信中的语义率-失真性：能力衍生的语义空间和对齐的成本 [PDF](https://arxiv.org/pdf/2604.09521), [HTML](https://arxiv.org/abs/2604.09521)
### Authors
Anthony T. Nixon
### Background
当两个具有不同计算能力的代理与同一环境交互时，他们无需压缩共同的语义字母表；他们可以诱导出完全不同的语义字母表。我们证明了与此代理能力一致的独特最粗略抽象的商齐次部分MDP（状态）$Q_{m,T}(M)$ 作为任何有界代理的能力衍生语义空间，并且不同能力代理之间的沟通具有明显的结构性相变。关键速率$R_{text{crit}}$决定了在此相变下保意沟通的结构性不可能。
### Innovation
论文提供了一个固定-$boldsymbol{ε}$结构性相变定理，该定理的下界完全适用于公共历史商的比较。此外，论文识别了一条单向Wyner-Ziv基准，在这个基准上具有完全逆，对于无记忆商源具有完全操作性等式，并通过显式混合界提供了条件动态长时间桥梁，证明了压缩失真范围$boldsymbol{ε}=O(1/boldsymbol{T})$的渐近单向逆，由此从消息流和解码器侧信息证明了渐近摄动。论文还提出了对齐迁移界，使通过中间能力层面的组合通信成为可能。
### Conclusion
实验显示了相变现象，并表明一对一通信率相对于计数界可以下降最多19倍，同时，收缩失真扫掠与渐近逆归则一致。
## 9. `cs.AI` - VISOR: Agentic Visual Retrieval-Augmented Generation via Iterative Search and On-hor Horizon Reasoning [PDF](https://arxiv.org/pdf/2604.09508), [HTML](https://arxiv.org/abs/2604.09508)
### Authors
Yucheng Shen,Jiulong Wu,Jizhou Huang,Dawei Yin,Lingyong Yan,Min Cao
### Background
现有的视觉语言模型（Vision-Language models）在处理复杂的查询时遇到困难， 特别需要多步推理能力。具体的原因在于视觉证据的分散性和稀疏性以及长时间检索中视觉令牌积累导致的检索偏移。旧的视觉语言生成（agagentic VR生成)模型在这两方面存在瓶颈： (1)视觉证据稀疏性,关键证据分布在多个页面上 但是孤立处理， 阻碍了跨页面的推理; (2)视觉细节的错误使用导致检索质量下降; (2)长时检索中的检索偏移导致语境淡化 [效导致认知超载]。 在解决这些挑战，“该研究提出了一种Unified单代理框架 (VISSOR)。该框架中，引入了一个结构化的证据空间供逐步地跨页面推理， 并配上了视觉细节评估和校正机制以管理视觉细节， 此外，还介绍了一种动态轨迹与滑动窗口和并意对象注入相结合的机制来缓解检索偏移。此新机制确保锚视觉细节分析和 同时避免了其他结果的压力过载和信息的泛滥。”为优化Training过程，VISSOR采用了一种基于组相对政策优化的强化学习 (GRPO-based RL) 管线线 结，并Masksing for动态上下文重构的遮罩和数据分析坦宁汉)” |
### Innovation
该SOR针对现有的视觉语言模型中的在处理复杂查询和提供了更强的推理能力。它提出了两种关键创新。 (1)一个统一的单代理框架 (VISSOR) 用于逐步跨页面的推理; ( in)一个动态轨迹与滑动窗口及意图注入相结合的机制来缓解长时间检索中的检索偏移; ( in)一个结构的证据空间 (证据空间结构) 用于推理细化细节的管理; ( in)一种基于组相对政策优化的强化学习 (GRPO-based RL) 管线用于Training Stage以适应动态上下文重构。”
### Conclusion
在Vi梁Seek、SlideVQA以及MMLonBench这三个评估数据集上的实验显示显示， VISOR在长期视觉推理任务上表现出优越的表现和更高的效率。 达到了当今技术的最佳水平。 这表明该框架在处理视觉与语言交互任务上具有显著的优势。”
## 10. `cs.CL` - 感知语言模型的仲裁失败，而非感知盲区：视觉语言模型如何解决视觉语言冲突 [PDF](https://arxiv.org/pdf/2604.09364), [HTML](https://arxiv.org/abs/2604.09364)
### Authors
Farhad Nooralahzadeh,Omid Rohanian,Yi Zhang,Jonathan Fürst,Kurt Stockinger
### Background
本文探讨了当视觉语言模型（VLM）看到一个蓝色的香蕉并通过回答黄色来发问时，问题是出在感知上还是仲裁上。研究通过对不同规模的10个VLM进行测试，揭示出编码-接地分离：即使某些模型未能正确报告所看到的内容（因而给出错误答案），这些模型也与正确回答模型一样强烈地编码了视觉证据。
### Innovation
利用多模态仲裁跨层（MAC）分析与逐层Logit Lens探测方法，追踪每个模型中视觉信号和先验信号的竞争情况。结果显示，早期层中可以线性解码视觉属性（AUC>0.86），成功和失败样本的准确性几乎相同。然而，最终层的logit差异更好地预测了接地结果。通过全序列激活补丁确定因果关系，发现图像标记几乎全部承载了因果效应，而文本标记则没有影响。进一步表明，早期层的无需训练的激活引导可以改善视觉接地，最高可提升3.8%。
### Conclusion
研究表明，视觉语言模型已经在感知方面表现良好，但面临的挑战是如何基于所见行动。针对这一问题的靶向干预措施可以有助于弥合感知与行动之间的差距。
## 11. `cs.CL` - VisionFoundry：使用合成图像教授VLMs视觉感知 [PDF](https://arxiv.org/pdf/2604.09531), [HTML](https://arxiv.org/abs/2604.09531)
### Authors
Guanyu Zhou,Yida Yin,Wenhao Chai,Shengbang Tong,Xingyu Fu,Zhuang Liu
### Background
视觉语言模型（VLMs）在视觉感知任务如空间理解和视角识别方面仍然存在困难。自然图像数据集对低级视觉技能提供的监督有限，这促使研究者思考：针对任务的合成监督，仅通过任务关键词如Depth Order（深度顺序）能否解决这些弱点？
### Innovation
引入了一个名为VisionFoundry的任务感知合成数据生成管道，仅需要任务名称作为输入，使用大规模语言模型（LLMs）生成问题、答案和文本到图像（T2I）提示，然后使用T2I模型生成图像，并与专有的VLM验证一致性，无需参考图像或人工标注。利用VisionFoundry生成了包含10k图像-问题-答案三元组的可视化问题回答（VQA）数据集，跨越10个任务，模型在视觉感知基准测试上的表现显著提升：在MMVP上提升了7%，在CV-Bench-3D上提升了10%，同时保持了广泛的其他能力，并且在数据量增加时表现出良好的扩展性。
### Conclusion
结果表明，有限的目标监督是这些瓶颈的重要原因，合成监督是向VLMs进行更系统训练的一种有前途的路径。
## 12. `cs.CL` - 通过蒸馏和强化学习培养多头Twig以加速大型视觉-语言模型 [PDF](https://arxiv.org/pdf/2503.14075), [HTML](https://arxiv.org/abs/2503.14075)
### Authors
Zhenwei Shao,Mingyang Wang,Weijun Zhang,Zhou Yu,Wenwen Pan,Yan Yang,Tao Wei,Hongyuan Zhang,Jun Yu
### Background
大型视觉-语言模型（VLMs）在开放世界的多模态理解上展现了非凡的能力，但其巨大的计算开销为实际部署带来了极大挑战。尽管一些方法通过基于VLM早期层注意图剪枝冗余视觉标记来加速VLMs，但这些方法仍然存在两个主要缺陷：一是早期层中敏感度低的注意信号导致显著的准确率下降，二是当生成长时间响应（例如30个标记）时性能有限。
### Innovation
本文提出了一种简单而通用的架构叫TwigVLM，通过在基础VLM早期层上生长一个轻量级模块（twig）来构建。相比现有的大多数基于视觉标记剪枝的VLM加速方法，TwigVLM不仅通过twig引导的标记剪枝（TTP）策略实现了更高的准确度保留，还通过自我推测解码（SSD）策略提高了生成速度。此外，通过引入新的多头twig架构和专门的剪枝头，以及通过结合蒸馏学习阶段和剪枝导向强化学习训练阶段的两阶段训练范式，推出了Enhanced TwigVLM（TwigVLM++），进一步提高了剪枝质量和加速推理。
### Conclusion
以LLaVA-1.5-7B为基础模型，实验结果显示，经过88.9%视觉标记剪枝后，TwigVLM保留了96%的原始性能，并在生成长响应时实现了154%的加速，其性能在准确性和速度上显著优于现有的VLM加速方法。TwigVLM++在这些方面表现出更优的性能。
## 13. `cs.CL` - 缓解Bangla分类任务中的 外性别偏见 [PDF](https://arxiv.org/pdf/2411.10636), [HTML](https://arxiv.org/abs/2411.10636)
### Authors
Sajib Kumar Saha Joy,Arman Hassan Mahy,Meherin Sultana,Azizah Mamun Abha,MD Piyal Ahmmed,Yue Dong,G M Shahariar
### Background
当前研究针对的是Bengla预训练语模型中存在 夷嫌性偏见的问题。。预训练模型通常是在资源丰富的语言上进行训练的，而对低资源语言 在如的这方面研究相对较少。。为此，研究者 construct 凧几个基于情感特定基准数据集的注释，这些数据集涉及情感分析、毒刺检测、仇恨言论检测和讽刺检测。在这些数据集中，通过细致地性别 perturbation来ünstutsche性别化名字与术语获得平衡词保语词义内容不变 maintain semantic content这为评估 gender 在偏差提供了一个经度比少偏差偏转的经评估平台。
### Innovation
本文研究提出的缓解方式是 '', RandSymKL '，这是一个结合随机化和与替代凯氏斯幺律散散差和交叉熵损失随机化 derebiasing'n和法手段在特统一方式优化框架中内减轻特定任务预训练模型的 extrinsic gender bias '。该方法以分类任务为主，在该方法不仅 effectively 趈除了偏差还可以保持与基 line方法可 comparable level of of
### Conclusion
在对照现有biasmit该技术不 仅有效减轻偏差 也而且在保持与基线方法相当的准确度同时。此研究与实施均向公众开放了开源代码和数据集 叼以研究了改进和应用用于低资源语言中的分类任务也性别bian见问题提供了重要的基础。
## 14. `cs.CL` - LLM4Delay: 通过大规模语言模型和航空轨迹表示的跨模态适应进行航班延误预测 [PDF](https://arxiv.org/pdf/2510.23636), [HTML](https://arxiv.org/abs/2510.23636)
### Authors
Thaweerath Phisannupawong,Joshua Julian Damanik,Han-Lim Choi
### Background
近年来，，交通管理（ATM) 中的航班延迟问题已经成为了系统中的关键关注点,。 転换延迟反映了系统效率的缺乏。。。研究发现，,在飞行控制器从终端机动区(TMA) 开始监控飞机的角度来看飞行延误预测具有重要意义。飞行延误的准确预测对于优化空中交通流控至关重要。
### Innovation
本文提出了一种基于大规模语言模型 (LLM) 的框架——LLM4Delay， ， 通过联合利用文本和轨迹上下文，以及实例级别的投影策略来实现多模态适配策略将不同轨迹表示映射到框架中使用的语模态空间中，这改善了延迟预测的准确性。并提出了利用先验轨迹编码器和先验大型语言模型来进行知识融合的技术模态自适应策略策略。此框架能够在新的信息可用时更新预测结果，从而提升了操作的实用性和相关性。
### Conclusion
与现有的空中交通管理框架和和 LLMS4Delay
## 15. `cs.CL` - FP8-RL：LLM强化学习的一种实用且稳定的低精度堆栈 [PDF](https://arxiv.org/pdf/2601.18150), [HTML](https://arxiv.org/abs/2601.18150)
### Authors
Zhaopeng Qiu,Shuang Yu,Jingqi Zhang,Shuai Zhang,Xue Huang,Jingyi Yang,Junjie Lai
### Background
大语言模型（LLMs）的强化学习（RL）在生成过程中受到卷积（rollout）瓶颈的限制，因为长期输出序列使得注意力和KV缓存内存成为端到端步骤时间的主要消耗。半精度浮点数（FP8）通过减少生成过程中的计算成本和内存流量提供了加速RL的机会，但将其应用到RL中引入了独特的工程和技术挑战：策略权重在每步中变化（需要重复量化和同步到推理引擎），低精度生成可能与假设的高精度策略训练不匹配，导致训练推理不一致和潜在的不稳定性。
### Innovation
本文介绍了针对LLM RL的FP8生成堆栈，该堆栈在veRL生态系统中实现了对常用训练后端（如FSDP/Megatron-LM）和推理引擎（如vLLM/SGLang）的支持。本文提出的技术包括：（i）使用块式FP8量化实现FP8 W8A8线性层生成；（ii）扩展FP8到KV缓存，通过每步QKV尺度重新校准来消除长上下文内存瓶颈；（iii）利用重要采样法（token-level TIS/MIS变体）来缓解训练推理不一致问题。这些技术在稠密模型和MoE模型中分别实现了最多44%的生成吞吐量提升，同时保持了与BF16基线类似的学习行为。
### Conclusion
这些方法为LLM的强化学习提供了高达44%的生成吞吐量提升，同时保持了与BF16基线类似的学习行为。
## 16. `cs.CL` - 过度高估态度，忽视网络关系：LLM在模拟信息易感性中的偏差 [PDF](https://arxiv.org/pdf/2602.04674), [HTML](https://arxiv.org/abs/2602.04674)
### Authors
Eun Cheol Choi,Lindsay E. Young,Emilio Ferrara
### Background
大语言模型（LLMs）在计算社会科学研究中越来越被用作人类判断的代理，但它们再现误导性信息易感性模式的能力尚不清楚。本研究通过使用社会调查数据中抽取的参与者特征模拟在线调查，测试LLM能否重现人类对误导性信息的相信和分享模式。并与三个基线在线调查进行比较，评估LLM的输出是否与观察到的反应分布相符，并恢复原始调查数据中存在的特征-结果关联。
### Innovation
本研究创新性地使用大语言模型模拟社会调查数据中的受访者，评估其在再现误导性信息易感性方面的表现。通过对比LLM生成的回答与人类回答，发现LLM在解释变异和重视态度与行为特征方面存在偏差，而忽视了个人网络特征。进一步分析模型生成的推理和LLM训练数据表明，这些偏差反映了人们对误导性信息相关概念的系统性表示偏差。
### Conclusion
研究结果表明，基于LLM的调查模拟更适合用于诊断系统性偏离人类判断的问题，而不是替代它。
## 17. `cs.CL` - LADR: 位置感知动态救援以提高使用扩散大语言模型的高效文本至图像生成 [PDF](https://arxiv.org/pdf/2603.13450), [HTML](https://arxiv.org/abs/2603.13450)
### Authors
Chenglin Wang,Yucheng Zhou,Shawn Chen,Tao Wang,Kai Zhang
### Background
离散扩散语言模型已经成为统一多模态生成的一种有吸引力的范式，但其部署受到从迭代解码中产生的高推理延迟的阻碍。现有的加速策略通常需要昂贵的重新训练，或者无法利用视觉数据中固有的2D空间冗余。
### Innovation
我们提出了位置感知动态救援（LADR），这是一种无需训练的方法，通过利用图像的空间马尔可夫性质来加速推理。LADR通过优先恢复生成前沿区域的标记，这些区域与观察到的像素相邻，从而最大化信息增益。具体来说，我们的方法通过形态学邻域识别来定位候选标记，采用风险限制过滤机制以防止错误传播，并利用与加速的蒙版密度一致的流形一致逆向调度，来对齐扩散轨迹。
### Conclusion
在四个文本到图像生成基准测试中，我们的LADR分别比标准基线实现了约4倍的速度提升。值得注意的是，它在空间推理任务中保持或甚至提高了生成保真度，提供了效率与质量之间的先进权衡。
## 18. `cs.CV` - 基于Hi3DGen的半自动化中世纪手稿插图3D重建框架 [PDF](https://arxiv.org/pdf/2604.08610), [HTML](https://arxiv.org/abs/2604.08610)
### Authors
Riccardo Pallotto,Pierluigi Feliciati,Tiberio Uricchio
### Background
本文介绍了一种半自动化的框架，用于将中世纪手稿中的二维迷你插图转换为适用于扩展现实(XR)、触觉3D打印和网络可视化要求的三维数字模型。该框架使用了多项评估指标来验证其性能，并通过两个案例研究展示了其适用性。
### Innovation
该研究创新之处在于开发了一种结合了多种技术（包括SAM分割、Hi3DGen网格生成、ZBrush专家细化和AI辅助纹理处理）的半自动化方法。研究特别关注Hi3DGen方法，因为该方法能够平衡拓扑质量与丰富的表面细节，因此是一个用于专家细化的良好起点。
### Conclusion
研究成果展示了该方法在对不同类型的手稿插图进行3D重建时的广泛适用性，并证明了其对于谷歌照明和意大利文艺复兴时期插图的支持。最终生成的3D模型可以支持WebXR可视化、物理手稿上的AR叠加以及视障用户使用的触觉3D打印。
## 19. `cs.CV` - ViSAGE @ NTIRE 2026挑战赛上的视频显著性预测 [PDF](https://arxiv.org/pdf/2604.08613), [HTML](https://arxiv.org/abs/2604.08613)
### Authors
Kun Wang,Yupeng Hu,Zhiran Li,Hao Liu,Qianlong Xiang,Liqiang Nie
### Background
该论文提出了一种名为ViSAGE的视频显著性预测方法，旨在解决NTIRE 2026挑战赛上提出的视频显著性预测任务。背景信息表明，现有的视频显著性预测方法大多忽略了视频中空间-时间特征的互补性，这可能导致模型无法很好地捕捉到复杂的空间-时间显著性线索。
### Innovation
创新在于提出了一个称为ViSAGE的多专家动态门控框架。每个特化解码器执行适应性门控和调制来精细处理空间-时间特征。不同专家的互补预测在推理时被融合，使得该模型能够聚合各种内在偏置，从而更好地捕捉视频中的复杂空间-时间显著性线索。
### Conclusion
实验结果表明，ViSAGE在四个评估指标中有两个指标中排名第一，并且在其他两个指标中也比大多数竞争对手表现出色，这证明了其有效性和泛化能力。代码已在此链接（this https URL）发布。
## 20. `cs.CV` - WildDet3D：在野外扩展可提示3D检测 [PDF](https://arxiv.org/pdf/2604.08626), [HTML](https://arxiv.org/abs/2604.08626)
### Authors
Weikai Huang,Jieyu Zhang,Sijun Li,Taoyang Jia,Jiafei Duan,Yunqian Cheng,Jaemin Cho,Mattew Wallingford,Rustin Soraki,Chris Dongjoo Kim,Donovan Clay,Taira Anderson,Winson Han,Ali Farhadi,Bharath Hariharan,Zhongzheng Ren,Ranjay Krishna
### Background
理解单张图像中的3D物体是空间智能的关键。现有的单目3D物体检测方法集中于单一提示类型，并缺乏融入附加几何线索的机制。现有3D数据集覆盖的物体类别狭窄且仅在控制环境中，这限制了其在现实世界中的应用。
### Innovation
本研究提出了WildDet3D，这是一种统一的几何意识架构，可以原生接受文本、点和框提示，并在推理时融入辅助深度信号。同时，研究者构建了一个名为WildDet3D-Data的最大规模开放3D检测数据集，包含了来自13500个类别，100多万张图像，涵盖了多样化的现实世界场景。WildDet3D在多个基准和设置中建立了新的SOTA性能，尤其是在现实世界设置中的表现尤其显著。
### Conclusion
在野外设置下，WildDet3D在我们新引入的WildDet3D-Bench上的空闲度达到22.6/24.8 AP3D，在Omni3D上达到34.2/36.4 AP3D。在零样本评估中，在Argoverse 2和ScanNet上分别达到40.3/48.9 ODS。值得注意的是，在所有设置中利用深度线索推理时额外获得了+20.7 AP的效果。
## 21. `cs.CV` - 基于语义学的生成艺术解读评价 [PDF](https://arxiv.org/pdf/2604.08641), [HTML](https://arxiv.org/abs/2604.08641)
### Authors
Ruixiang Jiang,Changwen Chen
### Background
解读是艺术语言的关键，观众通过视觉艺术品来与艺术家沟通并获取其意义。然而，目前生成艺术（GenArt）的评估者仍然只关注表面图像的质量或对生成提示的字面遵从，忽视了创作者所希望传达的深层象征或抽象意义。文章指出，现有的评估器主要局限于图像的表层信息，缺乏对符号性和符号指征性意义的评估。
### Innovation
提出了一种皮尔士风格的计算符号学理论框架，将其称为人类与生成艺术交互（HGI）中的符号学链式过程。通过这种方法，艺术意义可以通过象形、象征和指称三种模式来传达，而现有的评估器过度集中在象形模式上，对后两者关注不足。设计了一个名为SemJudge的新评估器，它使用层次符号学图（HSG）去明了地评估HGI中的象征和符号指称意义。实验表明，SemJudge的评价结果与人类判断更接近，并能够产生更加深入的艺术解读，从而推动生成艺术从单纯的“漂亮图像”生成向能表达更复杂人类经验的方向发展。
### Conclusion
SemJudge为生成艺术的评估提供了一种新颖的方法，并表明它能够更好地理解和评估艺术作品的深层意义，预示着生成艺术将在未来更加聚焦于表达复杂的人类经验。
## 22. `cs.CV` - InsEdit：通过数据高效视频扩散模型适应走向基于指令的视觉编辑 [PDF](https://arxiv.org/pdf/2604.08646), [HTML](https://arxiv.org/abs/2604.08646)
### Authors
Zhefan Rao,Bin Zou,Haoxuan Che,Xuanhua He,Chong Hou Choi,Yanheng Li,Rui Liu,Qifeng Chen
### Background
基于指令的视频编辑是通过文本控制视频内容的自然方式，但将视频生成模型改编为编辑器通常需要大量数据。同时，高质量的视频编辑数据仍然稀缺。
### Innovation
该研究展示了一种视频生成骨干模型可以通过少量的视频编辑数据转变为强大的视频编辑器。研究提出了InsEdit，一种基于HunyuanVideo-1.5构建的指令驱动编辑模型。InsEdit结合了基于Mutual Context Attention（MCA）的视觉编辑架构和视频数据管道，可以在片段中任意位置开始编辑而不是仅从第一帧开始。实验结果表明，使用仅10万个视频编辑数据，InsEdit在开源方法上的视频指令编辑基准上达到了最先进的性能，且最终模型还支持无需修改即可进行图像编辑。
### Conclusion
即使使用少量的视频编辑数据，该模型也能有效地适应视频编辑任务，并在无需额外数据补充的情况下，支持图像编辑功能。
## 23. `cs.CV` - EfficientSign: 一种增强注意力的轻量级架构用于印度手语识别 [PDF](https://arxiv.org/pdf/2604.08694), [HTML](https://arxiv.org/abs/2604.08694)
### Authors
Rishabh Gupta,Shravya R. Nalla
### Background
本文旨在探讨如何在手机上构建有效的手语识别系统。为此，作者利用 EfficientNet-B0 构建了 EfficientSign 模型，并在其中加入了两个注意力模块来关注手势特征。该研究使用了印度手语字母表的数据集进行测试，该数据集包含26个类别的12,637张图片。
### Innovation
EfficientSign 模型通过结合 Squeeze-and-Excitation 模块和空间注意力层来提升识别效果。相较于 ResNet18，EfficientSign 在参数量减少62%后，准确率仅略低于 ResNet18。作者还实验了将 EfficientNet-B0 的深层特征输入到经典分类器中，如 SVM、Logistic Regression 和 KNN，这些分类器在准确率上也都优于基于 SURF 方法的模型。
### Conclusion
研究结果表明，增强注意力的学习模型能够为印度手语识别提供一种高效且可部署的解决方案，不再需要一个庞大的模型或手动调整特征管道。
## 24. `cs.CV` - 大规模通用缺陷生成：基础模型与数据集 [PDF](https://arxiv.org/pdf/2604.08915), [HTML](https://arxiv.org/abs/2604.08915)
### Authors
Yuanting Fan,Jun Liu,Bin-Bin Gao,Xiaochen Chen,Yuhuan Lin,Zhewei Dai,Jiawei Zhan,Chengjie Wang
### Background
现有的缺陷/异常生成方法大多依赖于少样本学习，但由于缺乏大规模的缺陷编辑配对数据，这些方法容易高度特化于特定缺陷类别。不同的缺陷规模和形态的显著变化使这种问题更加严重，导致生成结果泛化能力较弱、真实度下降以及类别一致性差。
### Innovation
本文通过引入包含30万个正常-异常-分割-说明四元组的大规模数据集UDG，并提出一种无需类别特定微调的支持参考基础缺陷生成和文本指令下缺陷编辑的通用缺陷生成基础模型UniDG，来解决这些问题。UniDG利用自适应缺陷裁剪和结构化的双页输入格式进行缺陷-上下文编辑，并通过MM-DiT多模态注意机制融合参考条件和目标条件。采用多样性和一致性的分阶段训练策略进一步提高生成质量和真实度。
### Conclusion
在MVTec-AD和VisA上的广泛实验表明，UniDG在合成质量以及单类和多类异常检测/定位下游任务中优于先前的少样本异常生成和图像插入/编辑基准。源代码将在此处公开：this https URL
## 25. `cs.CV` - Fast Model-guided Instance-wise Adaptation Framework for Real-world Pansharpening with Fidelity Constraints [PDF](https://arxiv.org/pdf/2604.08903), [HTML](https://arxiv.org/abs/2604.08903)
### Authors
Zhiqi Yang,Jin-Liang Xiao,Shan Yin,Liang-Jian Deng,Gemine Vivone
### Background
Pansharpening的目标是通过融合低分辨率多光谱（LRMS）和高分辨率单色（PAN）图像来生成高分辨率多光谱（HRMS）图像，同时保留光谱和空间信息。尽管基于深度学习的pansharpening方法表现突出，但它们需要高昂的训练成本和大型数据集，且在测试分布与训练分布不同时易退化。最近的零样本方法虽然展现出强大的泛化能力，但由于融合质量差、高计算开销和慢收敛等问题而受到限制。
### Innovation
本文提出了FMG-Pan，一种针对实际应用场景的快速且通用的模型引导实例适应框架，结合光谱和物理保真度约束进行联合优化，并引入了新型物理保真度项来增强空间细节保留。FMG-Pan框架通过预训练模型引导一个轻量级自适应网络，实现了跨传感器的通用性和快速训练推理。该方法在不同场景下的现实世界数据集上展示了最先进的性能，并且在RTX 3090 GPU上对512x512x8图像进行训练和推理仅需3秒，显著提高了效率。
### Conclusion
实验结果表明，FMG-Pan在真实场景数据集上的表现领先于现有方法，在WorldView-3数据集上，使用RTX 3090 GPU对512x512x8图像进行训练和推理只需3秒，显著优于现有零样本方法，适于实际部署。
## 26. `cs.CV` - MV3DIS: 多视图掩码匹配中的3D引导用于零样本3D实例分割 [PDF](https://arxiv.org/pdf/2604.08916), [HTML](https://arxiv.org/abs/2604.08916)
### Authors
Yibo Zhao,Yigong Zhang,Jin Xie
### Background
传统的3D实例分割方法依赖于劳动密集型的3D注释进行监督训练，这限制了其在新颖对象上的扩展性和泛化能力。最近的方法利用分割一切模型（SAM）的多视图2D掩码来引导3D几何元的合并，从而实现零样本3D实例分割。然而，这些方法通常独立处理每一帧，并且仅依赖于2D度量标准，如SAM预测分数，来生成分割图。这种设计忽略了多视图之间的相关性和固有的3D先验信息，导致多视图之间不一致的2D掩码，并最终产生碎片化的3D分割。
### Innovation
本文提出了MV3DIS框架，这是一种用于零样本3D实例分割的粗到细框架，它显式地结合了3D先验。具体来说，引入了3D引导掩码匹配策略，使用粗3D分割作为共同参考来匹配跨视图的2D掩码，并通过3D覆盖分布来统一多视图掩码的一致性。受这些视图一致的2D掩码的引导，粗3D分割进一步细化为精确的3D实例。此外，还引入了一种深度一致性加权方案，以量化投影可靠性来抑制来自物体相互遮挡的歧义，从而增强了从3D到2D对应的鲁棒性。
### Conclusion
在ScanNetV2、ScanNet200、ScanNet++、Replica和Matterport3D数据集上的广泛实验表明，MV3DIS的有效性，该方法在性能上优于先前的方法。
## 27. `cs.CV` - 定制融合：适应多任务感知红外-可见光图像融合的闭路动态网络 [PDF](https://arxiv.org/pdf/2604.08924), [HTML](https://arxiv.org/abs/2604.08924)
### Authors
Zengyi Yang,Yu Liu,Juan Cheng,Zhiqin Zhu,Yafei Zhang,Huafeng Li
### Background
红外-可见光图像融合旨在整合互补信息以实现稳健的视觉理解，但现有的融合方法难以同时适应多种下游任务。
### Innovation
本文提出了一种闭路动态网络（CLDyN），该网络能够根据多样化的下游任务需求自适应响应，实现任务定制的图像融合。CLDyN引入了一种闭路优化机制，通过需求驱动的语义补偿（RSC）模块建立语义传输链，实现从下游任务到融合网络的显式反馈。RSC模块利用基向量库（BVB）和自适应架构语义注入（A2SI）块来根据任务需求定制网络架构，从而实现任务特定的语义补偿，使得融合网络能够在不重新训练的情况下主动适应多种任务。
### Conclusion
在M3FD、FMB和VT5000数据集上的实验表明，CLDyN不仅保持了高融合质量，还表现出强大的多任务适应性。CLDyN鼓励语义补偿，通过引入奖励惩罚策略，根据任务性能变化奖励或惩罚RSC模块。代码已公开，可访问上述链接。
## 28. `cs.CV` - M-IDoL: 信息分解在医疗基础模型中实现模态特定和多样化表示学习 [PDF](https://arxiv.org/pdf/2604.08936), [HTML](https://arxiv.org/abs/2604.08936)
### Authors
Yihang Liu,Ying Wen,Jiaxiong Yang,Longzhen Yang,Lianghua He,Heng Tao Shen
### Background
医疗基础模型（MFMs）旨在从多模态医学图像中学习通用表示，并在不同的下游临床任务中有效泛化。然而，现有大多数MFMs存在信息模糊的问题，将多模态表示融合到单一嵌入空间中，导致模态特定性和多样性降低。
### Innovation
本文提出了一种自监督的M-IDoL，通过引入多模态表示学习的信息分解来解决上述问题。该方法采用两个目标：i) 最大化跨模态熵，通过将多模态表示分散到分离的Mixture-of-Experts（MoE）子空间中，以实现模态间的表示特定性；ii) 最小化模态内的不确定性，在每个MoE子空间内执行细粒度的语义区分，以丰富每个模态的表示多样性。通过在115万张医学图像上进行预训练，M-IDoL在21个下游临床任务中实现了更好的泛化性能，并在五种成像模态（如X射线、眼底、OCT、皮肤镜和病理学）上优于20个基础模型。
### Conclusion
M-IDoL展示了更清晰的跨模态特征簇分离和每个模态内的细粒度特征区分，通过自监督预训练更加有效地实现了模态特定和多样化的表示学习。
## 29. `cs.CV` - TouchAnything: 由扩散引导的.sparse机器人触觉的3D重建 [PDF](https://arxiv.org/pdf/2604.08945), [HTML](https://arxiv.org/abs/2604.08945)
### Authors
Langzhe Gu,Hung-Jui Huang,Mohamad Qadri,Michael Kaess,Wenzhen Yuan
### Background
准确的物体几何估算对于许多下游任务，如机器人操作和物理交互至关重要。虽然视觉是形状感知的主要模态，但在遮挡或照明条件不佳的情况下变得不可靠。在这种情况下，通过物理接触直接提供几何信息的触觉传感可以作为替代方案。然而，仅从稀疏触觉测量中重建全局3D几何形状是根本上欠约束的。
### Innovation
我们提出了一种TouchAnything框架，该框架利用一个预训练的大规模2D视觉扩散模型作为语义和几何先验，用于从稀疏触觉测量中进行3D重建。我们的方法将预训练视觉扩散模型中的几何知识转移到触觉领域，给定稀疏接触约束和粗略的分类级物体描述，将重建问题形式化为在触觉一致性约束下的优化问题，指导方案向与扩散先验一致的形状收敛。我们的方法仅从几次触觉中重建出准确的几何形状，优于现有基线，并实现了对未见过物体实例的开放世界3D重建。
### Conclusion
我们的方法成功地通过稀疏触觉测量重建了准确的3D几何形状，超过了现有基线方法，并在看不见的物体实例上实现了开放世界3D重建。该项目网页为：this https URL.
## 30. `cs.CV` - Multi-task Just Recognizable Difference for Video Coding for Machines: Database, Model, and Coding Application [PDF](https://arxiv.org/pdf/2604.09421), [HTML](https://arxiv.org/abs/2604.09421)
### Authors
Junqi Liu,Yun Zhang,Xiaoxia Huang,Long Xu,Weisi Lin
### Background
Just Recognizable Difference (JRD)方法通过视见阈值建模提升了机器视觉的编码效率，但目前仅限于单一任务场景。该研究旨在解决这一限制，构建了多任务JRD (MT-JRD) 数据集，并发展了属性辅助的MT-JRD (AMT-JRD) 模型，用于视频编码器-机器（VCM），从而增强预测精度和编码效率。
### Innovation
研究创新点包括（1）构建了一个包含27,264个JRD注释的大型数据集，支持包括对象检测、实例分割和关键点检测在内的三个代表性任务；（2）提出了AMT-JRD预测模型，结合了通用特征提取模块（GFEM）和专用特征提取模块（SFEM），以促进跨任务的联合学习；（3）通过引入属性特征融合模块（AFFM），将对象属性信息与对象级JRD预测相结合，引入了有关对象大小和位置的先验知识；（4）将AMT-JRD模型应用于VCM，在保持多任务准确性的同时显著减少了编码位率。
### Conclusion
AMT-JRD模型在三个任务上实现了精确且稳健的多任务预测，均方误差为3.781，误差方差为5.332，总体提高了与最先进的单一任务预测模型的6.7%和6.3%，而基于AMT-JRD的VCM相较于基准VVC和JPEG编码分别提高了3.861%和7.886% Bjontegaard Delta均平均精度（BD-mAP）。
## 31. `cs.CV` - 通过蒸馏和强化学习培养多头Twig以加速大型视觉语言模型 [PDF](https://arxiv.org/pdf/2503.14075), [HTML](https://arxiv.org/abs/2503.14075)
### Authors
Zhenwei Shao,Mingyang Wang,Weijun Zhang,Zhou Yu,Wenwen Pan,Yan Yang,Tao Wei,Hongyuan Zhang,Jun Yu
### Background
大型视觉语言模型（VLMs）在开放世界多模态理解方面展现了显著的能力，但其高昂的计算成本也带来了实际部署的挑战。尽管有一些方法通过在VLM早期层的注意力图指导下修剪冗余的视觉令牌来加速VLM，但这些方法仍然存在两个主要问题：（i）早期层中的敏感度不足的注意力信号导致显著的准确度降低；（ii）在生成长响应（例如30个令牌）时只能获得有限的加速。为了解决这些问题，本文提出TwigVLM架构，通过在基础VLM的早期层上生长一个轻量级模块“twig”实现。
### Innovation
TwigVLM采用了twig引导的令牌修剪（TTP）策略以保证更高的准确度保留，并通过自我推测解码（SSD）策略实现更高的生成速度。TwigVLM++进一步引入了多头twig架构和专门的修剪头，通过两阶段训练范式结合蒸馏学习阶段和修剪导向的强化学习阶段提高修剪质量，最终通过基于树的SSD策略进一步加速推理。
### Conclusion
基于LLaVA-1.5-7B的实验结果表明，TwigVLM在修剪88.9%的视觉令牌后保留了96%的原始性能，并在生成长响应时实现了154%的加速，显著优于现有最先进的VLM加速方法，在准确性和速度方面表现更佳。此外，TwigVLM++通过多头Twig和专门修剪头进一步提升了性能和速度。
## 32. `cs.CV` - Gen-n-Val：自主生成和验证图像数据 [PDF](https://arxiv.org/pdf/2506.04676), [HTML](https://arxiv.org/abs/2506.04676)
### Authors
Jing-En Huang,I-Sheng Fang,Tzuhsuan Huang,Yu-Lun Liu,Chih-Yu Wang,Jun-Cheng Chen
### Background
在计算机视觉任务中，如目标检测和实例分割，数据稀缺、标签噪声和类别不平衡问题仍然是重要且未解决的挑战。特别是在LVIS等大规模词汇量基准中，大多数类别在少量图像中出现。当前的合成数据生成方法仍存在问题，如一个掩码中的多个对象、不准确的分割、错误的类别标签等，这些问题限制了其有效性。
### Innovation
文章提出了一种名为Gen-n-Val的新颖的代理型数据生成框架，该框架结合了层扩散（LD）、大型语言模型（LLM）和视觉大型语言模型（VLLM）来生成高质量、多样化的实例掩码和图像，以改进目标检测和实例分割任务。Gen-n-Val包含两个代理：（1）LD提示代理，一个LLM优化提示以鼓励LD生成高质量的单对象前景图像及其对应的分割掩码；（2）数据验证代理，一个VLLM过滤低质量的合成实例图像。通过优化系统提示，该方法与现有的最佳合成数据方法（如MosaicFusion）相比，减少了83%的无效合成数据，提高了7.6%的罕见类别的性能（在LVIS实例分割中使用Mask R-CNN，以及在COCO实例分割中使用YOLOv9c和YOLO11m，罕见类别的mAP分别提高了3.6%）。此外，在开放词汇目标检测基准中，与YOLO-Worldv2-M相比，Gen-n-Val在YOLO11m上的mAP提高了7.1%。
### Conclusion
Gen-n-Val方法具有模型容量和数据集规模的扩展性，并在目标检测和分割任务中表现出显著改进。相关代码已发布。
## 33. `cs.CV` - P3P Made Easy [PDF](https://arxiv.org/pdf/2508.01312), [HTML](https://arxiv.org/abs/2508.01312)
### Authors
Seong Hun Lee,Patrick Vandewalle,Javier Civera
### Background
传统的视角三点（P3P）问题旨在从三个2D-3D对应关系中恢复校准摄像机的绝对位置。长期以来，P3P可以简化为一个四次多项式方程，具有简单的解析形式和计算效率。然而，这一优雅的公式在现代文献中几乎被忽视。
### Innovation
本文基于Grunert在1841年的工作，提出了一种紧凑的代数解算器，该解算器在准确性和运行时间方面与最先进的方法相当。研究结果表明，当结合现代见解进行实施时，这一古典公式仍然具有极高的竞争力，提供了一种简洁、高效且准确的平衡。
### Conclusion
本文展示的结果表明，当用现代见解实施时，这一古典公式仍然具有极高的竞争力，提供了简洁、高效和准确的良好平衡。
## 34. `cs.CV` - FlashLips：使用重建而非扩散或GANs实现100 FPS的无掩模唇同步 [PDF](https://arxiv.org/pdf/2512.20033), [HTML](https://arxiv.org/abs/2512.20033)
### Authors
Andreas Zinonos,Michał Stypułkowski,Antoni Bigata,Stavros Petridis,Maja Pantic,Nikita Drobyshev
### Background
当前的唇同步系统大多依赖于生成对抗网络（GANs）或扩散模型，这些模型通常需要复杂的掩码操作和计算成本较高的过程来生成高质量的唇部运动。然而，这些复杂性往往导致了较低的实时效能，并且处理复杂的口型可能会造成视觉质量的降低。
### Innovation
FlashLips 提出了一种两阶段、无掩码的唇同步系统，通过分离唇部控制与渲染，实现了实时性能。Stage 1 采用一种紧凑的、单步骤的潜在空间编辑器，利用参考身份、掩码目标帧和低维的唇部姿态向量进行图像重建，仅使用重构损失进行训练，不依赖GANs或扩散。Stage 2 是一种基于流匹配的目标的音频到姿态变换器，用于预测唇部姿态向量。通过这两阶段的结合，FlashLips 实现了高质量的感知度和超实时的运行速度。
### Conclusion
FlashLips 设计的简单且稳定的两阶段流水线，实现了既快速又高质量的唇部同步效果，相较于现有的大模型，它不仅提高了实时性，还保持了视觉质量。
## 35. `cs.CV` - EmoCtrl：可控的情感图像内容生成 [PDF](https://arxiv.org/pdf/2512.22437), [HTML](https://arxiv.org/abs/2512.22437)
### Authors
Jingyuan Yang,Weibin Luo,Hui Huang
### Background
图像的意义不仅来源于其视觉内容，还来自于情绪的基调，共同影响人类感知。现有的文本到图像模型保证了视觉内容的一致性，但缺乏对情绪的认知；而以情绪驱动的模型虽然能够生成有情感的作品，但往往伴随视觉内容的扭曲。本文旨在弥合这一差距。
### Innovation
本文引入了EmoCtrl模型，支持一个同时标注内容、情绪和情感提示的数据集，以此将抽象情绪与视觉线索联系起来。EmoCtrl结合了文本和视觉情绪增强模块，通过描述性的语义和感知线索来丰富情感表达，并引入了针对性设计情绪奖励以优化模型的人类偏好匹配度。实验证明，EmoCtrl能够实现内容的忠实性和情绪表达的控制，其表现优于现有方法。用户研究也表明，EmoCtrl高度符合人类的偏好，且具有强大的适应性和鲁棒性。
### Conclusion
EmoCtrl通过综合情感和视觉信息，实现了情感表达和视觉内容的双重控制，为图像生成提供了新的解决方案，并在创意应用中表现出良好的推广性和适应性。
## 36. `cs.CV` - 测量一致拉普拉斯校正器在稳定化隐扩散逆问题求解器中的应用 [PDF](https://arxiv.org/pdf/2601.04791), [HTML](https://arxiv.org/abs/2601.04791)
### Authors
Lee Hyoseok,Sohwi Lim,Eunju Cha,Tae-Hyun Oh
### Background
虽然潜扩散模型（LDMs）在逆问题中作为强大的先验变得越来越重要，但现有的基于LDM的求解器通常面临着稳定性的挑战。
### Innovation
本文首先将不稳定归因于求解器动态与由扩散模型学习到的稳定的逆向扩散动态之间的差异，表明减少这种差距可以稳定求解器。在此基础上，作者提出了“测量一致拉普拉斯校正器（MCLC）”，这是一种有着理论依据的插即用稳定模块，能够通过测量一致的拉普拉斯更新修正基于LDM的逆问题求解器。与依赖于线性流形假设的先前方法相比，MCLC提供了一个合理的稳定机制，这在潜在空间中能导致更稳定和可靠的求解行为。
### Conclusion
本文提出了一种基于测量一致拉普拉斯更新的稳定机制，以稳定基于LDM的逆问题求解器，这种机制在潜在空间中提供了更稳定和可靠的求解行为。
## 37. `cs.CV` - 使用SHAP值的计算机视觉对抗规避攻击 [PDF](https://arxiv.org/pdf/2601.10587), [HTML](https://arxiv.org/abs/2601.10587)
### Authors
Frank Mollard,Marcus Becker,Florian Roehrbein
### Background
该研究探讨了如何利用SHAP（SHapley Additive exPlanations）值对深度学习计算机视觉模型进行白盒攻击。这种攻击能够通过降低输出置信度或导致误分类，扰乱模型的性能。这类攻击特别危险，因为它们能够在不被人类视觉察觉的情况下欺骗算法的认知。
### Innovation
该研究提出了一种利用SHAP值来量化输入对模型输出影响的白盒攻击方法，并将这种方法与快梯度符号方法进行了比较。研究表明，SHAP攻击在梯度隐藏场景下更具鲁棒性，更能有效地导致误分类。
### Conclusion
研究表明SHAP攻击在阻止深度学习计算机视觉模型正确分类时更为有效，尤其是在梯度信息不易察觉的情况下。
## 38. `cs.CV` - 分割提示：克服图像和视频超分辨率中的提示误导 [PDF](https://arxiv.org/pdf/2602.03342), [HTML](https://arxiv.org/abs/2602.03342)
### Authors
Bryan Sangwoo Kim,Jonghyun Park,Jong Chul Ye
### Background
文本条件化的扩散模型通过使用提示作为语义先验，促进了图像和视频的超分辨率。现代超分辨率流水线通常依赖于潜空间平铺技术来实现高分辨率的处理。然而，实际应用中，单一全局提示常与潜空间平铺一起使用，导致提示误导。具体而言，粗略的全局提示往往忽略了局部细节（遗漏错误），同时还提供了在局部上无关的引导（错误引导），从而导致在潜空间平铺级别的结果不佳。
### Innovation
本文提出了分割提示（Tiled Prompts），这是一种统一的框架，用于图像和视频超分辨率，它为每个潜空间平铺生成特定于该区域的提示，并在局部文本条件化后验下进行超分辨率，以最小的额外开销解决提示误导问题。实验结果表明，分割提示在感知质量和保真度方面带来了持续的改进，同时减少了全局提示基准中发现的幻觉和潜空间平铺级别的伪影。
### Conclusion
我们的实验针对高分辨率的实际图像和视频显示，分割提示在感知质量和保真度方面带来了一致的改进，同时减少了全局提示基线中的幻觉和潜空间平铺级别的伪影。
## 39. `cs.CV` - 通过局部和全局上下文优化进行的标记减少以提高高效视频大型语言模型 [PDF](https://arxiv.org/pdf/2603.01400), [HTML](https://arxiv.org/abs/2603.01400)
### Authors
Jinlong Li,Liyuan Jiang,Haonan Zhang,Nicu Sebe
### Background
视频大型语言模型（VLLMs）在理解视频方面表现出色，但由于存在冗余的视觉标记，导致效率低下。现有方法主要针对帧内空间冗余进行剪枝或在LLM浅层剪枝，结果未能达到最优的时空压缩，并且未能充分利用长上下文压缩性。所有方法在裁剪或合并后的标记中经常舍弃一些细微但有信息性的内容。
### Innovation
本文提出了一种新的视角，通过帧内和帧间的标记锚点的局部和全局上下文优化，结合局部-全局最优传输（AOT），全面地聚合有益的上下文信息。首先，在每个帧下建立受注意力机制引导的局部和全局感知的标记锚点，然后通过最优传输聚合剪枝标记中的相关信息，构建帧内标记锚点。接着，基于时间帧片段，每个片段的第一帧作为关键帧锚点，通过最优传输合并连续帧中的相似信息，同时保留不同标记来表示时间动态，从而在无需训练的情况下实现高效标记减少。
### Conclusion
全面的评估表明，我们提出的方法AOT在各种短视频和长视频基准测试上都获得了竞争力的性能，在能效方面有了显著改善，同时保持了时间动态和视觉保真度。
## 40. `cs.CV` - 更好的视觉，更好的思维方式：为什么医学中的视觉链式思考会失败 [PDF](https://arxiv.org/pdf/2603.06665), [HTML](https://arxiv.org/abs/2603.06665)
### Authors
Yuan Wu,Zongxian Yang,Jiayu Qian,Songpan Gao,Guanxing Chen,Qiankun Li,Yu-An Huang,Zhi-An Huang
### Background
大维度的视觉语言模型（VLMs）在一般的任务中常常从思维链（CoT）提示中获得好处，但在医疗视觉语言任务中的效果尚未得到广泛研究。该研究揭示了一个与直觉相反的趋势：在医疗视觉问答任务中，思维链方法在通用模型和医学专用模型上经常不如直接回答方法表现得好。
### Innovation
这项研究引入了两种训练免费且在推理阶段的工作来改进视觉定位：（i）通过区域兴趣提示进行感知锚定；（ii）通过高质量的文字引导进行描述定位。这些干预措施在多个基准测试和模型家族中提高了准确性，缓解了思维链（CoT）的表现恶化，甚至在某些情况下逆转了思维链与直接回答（DirA）效果的倒置。
### Conclusion
研究结果表明，可靠的临床VLMs需要稳健的视觉定位和跨模态对齐，而不仅仅是在文本驱动的推理链条上进行扩展。所有代码都可在[此处]获得。
## 41. `cs.CV` - 基于构成可解释性的固有概念提取 [PDF](https://arxiv.org/pdf/2603.11795), [HTML](https://arxiv.org/abs/2603.11795)
### Authors
Hanyu Shi,Hong Tao,Guoheng Huang,Jianbin Jiang,Xuhang Chen,Chi-Man Pun,Shanhu Wang,Pan Pan
### Background
现有的无监督概念提取方法无法提取可组合的内在概念。
### Innovation
提出了一个新的任务，即组成性和可解释性内在概念提取（CI-ICE），并提出了一种名为HyperExpress的方法，利用扩散型文本到图像模型从单张图像中提取具有可组合性的对象级和属性级概念，可以通过概念的组合生成原始概念。该方法通过结合拟双曲空间的固有层次建模能力和概念级优化方法，实现了概念的准确分离和复杂的跨概念关系的保持。
### Conclusion
HyperExpress在从单张图像中提取组成性和可解释性的内在概念方面表现出色。
## 42. `cs.CV` - LADR: 局域感知动态救援以提高Diffusion大语言模型在图文生成中的效率 [PDF](https://arxiv.org/pdf/2603.13450), [HTML](https://arxiv.org/abs/2603.13450)
### Authors
Chenglin Wang,Yucheng Zhou,Shawn Chen,Tao Wang,Kai Zhang
### Background
基于离散扩散的语言模型（Discrete Diffusion Language Models）作为统一多模态生成的有吸引力范式已出现，但其部署受限于迭代解码引起的高推理延迟。现有的加速策略往往需要昂贵的重新训练，或者未能充分利用视觉数据固有的2D空间冗余。
### Innovation
本文提出了Local Awareness Dynamic Rescue(LADR)，一种无需训练的方法，通过利用图像的空间马尔可夫性质来加速推理。LADR优先恢复生成边界区域的标记，这些区域与已观察到的像素相邻，从而最大化信息增益。具体方法包括形态邻域识别、风险约束的滤波机制以及流形一致的逆调度来对齐扩散轨迹与加速掩码密度。
### Conclusion
在四个文本到图像生成基准上进行的实验显示，我们的LADR方法相对于标准基线实现了约4倍的速度提升。令人惊讶的是，它在生成保真度上要么保持不变，甚至有所提高，特别是在空间推理任务中，这为我们提供了效率与质量之间的最佳权衡。
## 43. `cs.CV` - B-MoE: 一个关注身体部位的专家集合方法在微动作识别中的‘所有部位都重要’方法 [PDF](https://arxiv.org/pdf/2603.24245), [HTML](https://arxiv.org/abs/2603.24245)
### Authors
Nishit Poddar,Aglind Reka,Diana-Laura Borza,Snehashis Majhi,Michal Balazia,Abhijit Das,Francois Bremond
### Background
微动作，如眨眼、点头或细微的姿势变化，虽然蕴含着丰富的社交意义，但因其细微、短暂和类间高度的模糊性，当前的动作识别模型难以准确识别。
### Innovation
提出了一个基于身体部位的专家集合框架B-MoE，每个专家专注于人体的不同部位（头部、躯干、上肢、下肢），使用轻量级的宏微观动作编码器M3E捕捉长程上下文结构和细粒度的局部动作。交叉注意力路由机制学习不同部位之间的关系，并动态选择每个微动作中最信息丰富的部位。B-MoE利用双流编码器，将部位特定的语义线索与全局动作特征融合，以共同捕捉空间局部线索和时间上的细微变化。
### Conclusion
在三个具有挑战性的基准（MA-52、SocialGesture、MPII-GroupInteraction）上进行的实验显示，该方法在模棱两可、未充分代表和低幅度的类别中获得了持续的领先结果。
## 44. `cs.LG` - 基于智能手表的现实办公环境久坐时间估计 [PDF](https://arxiv.org/pdf/2604.08808), [HTML](https://arxiv.org/abs/2604.08808)
### Authors
Olivia Zhang,Zhilin Zhang
### Background
久坐行为对公共健康构成重大威胁，与肥胖、心血管疾病及其他慢性病有密切关联。准确估算坐下的时间对于监测和改善个人健康至关重要。本文在现实世界的办公环境中解决了这一问题，期间从办公人员日常工作中收集来自智能手表惯性测量单元(IMU)的信号。
### Innovation
本文提出了一种新的方法，通过引入基于欧拉角的旋转序列作为运动动态的新表示形式，从而从IMU信号中估计坐下的时间。实验结果显示，利用旋转序列可以提高算法的性能，并在自然环境中提供了准确坐下的时间估计的潜力。
### Conclusion
本文证明了利用旋转序列优化算法性能的有效性，强调了在自然办公环境中进行久坐时间估计的重要性。
## 45. `cs.LG` - 通过留一法分析进行SVG生成的结构性评价指标 [PDF](https://arxiv.org/pdf/2604.08809), [HTML](https://arxiv.org/abs/2604.08809)
### Authors
Haonan Zhu,Adrienne Deganutti,Elad Hirsch,Purvanshi Mehta
### Background
SVG作为一种可编辑的矢量图形表示，能够独立地检查、转换或移除每个元素，从而增强编辑性。现有的评价协议主要通过单一的相似性分数来度量生成的SVG与参考图像或输入文本的忠真度，但忽略了评估SVG元素如何保留结构特性，这些特性使得SVG具有价值。现有的度量标准无法确定哪些生成的元素对整体视觉质量有积极贡献，视觉概念如何映射到代码的特定部分，或者生成的输出是否支持有意义的进一步编辑。
### Innovation
本文提出了一种基于留一法（LOO）分析的元素级评价方法，该方法通过渲染包含和不包含每个元素的SVG，并测量视觉变化来评估结构质量。本文提出了一种新机制：(1) 通过LOO得分获得每个元素的质量评分，实现零样本伪影检测；(2) 概念-元素归因，将每个元素与它所服务的视觉概念进行映射；(3) 四个结构性度量：纯度、覆盖率、紧凑性和局部性，从不同角度量化SVG模块化。
### Conclusion
通过对超过19,000次编辑（5种类型）在5个生成系统和3种复杂级别上验证这些度量标准，本文证明了这些新提出的度量标准的有效性和实用性。
## 46. `cs.LG` - Ascend NPUs上基于HiFloat4格式的语言模型预训练 [PDF](https://arxiv.org/pdf/2604.08826), [HTML](https://arxiv.org/abs/2604.08826)
### Authors
Mehran Taghian,Yunke Peng,Xing Huang,Yao Wang,Yaoyuan Wang,Wei Guo,Yuanyong Luo,Tianchi Hu,Junsong Wang,Xin Wang,Hu Liu,Yu Cheng,Ziwei Yu,Hongliang Li,Mehdi Rahimifar,Lei Yan,Xuefei Wang,Zhuang Ma,Lei Liu,Hui Yu,Anandharaju Durai Raju,Hoang Le,Hei Yi Mak,Tanzila Rahman,Shadan Golestan
### Background
大规模的模型已成为现代机器学习的核心，随着模型规模和数据量的增加，性能也会可预测地提升。然而，训练和部署这些模型会带来重大的计算和内存成本，因此推动了低精度训练技术的发展。近年来的研究显示，4位浮点数（FP4）格式（如MXFP4和NVFP4）在大规模语言模型（LLMs）中可以成功应用于线性GEMM操作，与高精度基线相比，能够提高4倍的计算吞吐量和内存效率。尽管如此，FP4还面临数值退化的问题。
### Innovation
本文研究了华为Ascend NPUs上最近提出的一种HiFloat4 FP4格式，并系统地将其与MXFP4进行比较。所有实验均在Ascend NPU集群上进行，线性和专家GEMM操作均完全在FP4精度下进行。研究还探讨了针对FP4训练的稳定化技术，这些技术显著减少了数值退化，保持了相对误差在满精度基线的1%以内，同时保留4位计算的效率优势。
### Conclusion
研究表明，HiFloat4格式在NPUs上进行了全面的经验研究，揭示了大规模密集型和MoE模型中FP4格式之间的实用权衡。
## 47. `cs.LG` - Loom: 可扩展的分析型神经计算机架构 [PDF](https://arxiv.org/pdf/2604.08816), [HTML](https://arxiv.org/abs/2604.08816)
### Authors
Mehmet Kerem Turkcan
### Background
当前的计算机架构大多基于冯·诺依曼架构，依赖于传统的寄存器和内存系统来执行程序。然而，对于复杂的编译语言如C语言和需要循环处理的程序，这种架构在性能和灵活性方面存在一定局限性。Loom旨在通过使用循环变换器和分析性权重方法来解决这些问题，提供一种新的执行基于C语言编译程序的架构。
### Innovation
Loom提出了一个新的计算机架构，该架构使用一个循环变换器来执行从C语言编译的程序，并通过分析性方法推导变换器的权重。它采用了带有22条指令集的8层变换器，每层变换器在每次前向传递中执行一条指令，并且模型通过迭代应用直到程序计数器为零。机器的完整状态存储在一个固定大小的单一张量中，每步的成本固定，与程序长度或执行历史无关。这种方法提供了比传统架构更高的可扩展性和灵活性。
### Conclusion
Loom展示了如何通过分析性变换器构建一种新的可扩展计算架构，使C语言程序能够在单一固定大小的张量中高效执行。这提供了一种新的编程方法，允许一种固定权重的模型执行任意C程序。Loom的代码现在已经可以在指定的网址上获取。
## 48. `cs.LG` - Joint Flow Distribution Learning (JFDL) for Post-Hoc Guidance of Consistency Models [PDF](https://arxiv.org/pdf/2604.08828), [HTML](https://arxiv.org/abs/2604.08828)
### Authors
Chia-Hong Hsu,Randall Balestriero
### Background
在扩散模型（DMs）中，分类器自由引导（CFG）允许用户在保真度和多样性之间进行权衡。然而，由于采样成本问题，CFG 的实际应用受到了限制。一致性模型（CMs）则可以一步或多步生成图像，但现有的引导方法需要来自单独的DM教师的知识蒸馏，这限制了CFG的应用范围。传统的CD方法需要一个DM教师来提供知识蒸馏。
### Innovation
本文提出了Joint Flow Distribution Learning（JFDL），这是一种轻量级的对齐方法，能够在预训练的CM中实现引导。JFDL通过将预训练的CM作为常微分方程（ODE）求解器，验证了无条件和有条件分布下的速度场成分方差爆炸的噪声具有高斯性。实际应用中，JFDL使CMs配备了类似于CFG的可调节引导开关，产生出具有类似特征的引导图像。JFDL应用到一个仅能进行有条件采样的原始一致性训练（CT）CM上，成功解锁了指导生成，并在CIFAR-10和ImageNet 64x64数据集上降低了FID。这是第一个能够在不使用DM教师的情况下，提供CM有效后托管的引导，从而填补了当前方法对于CMs的关键空白。
### Conclusion
JFDL使新的一致性模型能够在不依赖DM教师的情况下接收后托管的引导，对于一致性模型的工作流提供了一个新的解决方案。它实现了一致性模型中的引导功能，提升了其灵活性和实用性。
## 49. `cs.LG` - LoRA适配器的光谱几何结构编码训练目标并预测有害合规性 [PDF](https://arxiv.org/pdf/2604.08844), [HTML](https://arxiv.org/abs/2604.08844)
### Authors
Roi Paul
### Background
该研究探讨了低秩光谱摘要是否能够识别语言模型微调时应用的具体目标，并进一步研究了这种几何信号是否预测了下游行为危害。研究在注册实验中对生成的38种LoRA适配器进行了分析，这些适配器来源于不同训练目标。研究结果表明，基于训练目标的光谱特征在二元漂移检测、微调目标对比以及严重程度分级上表现优异。
### Innovation
1. 提出了一种新的光谱特征提取方法以确定语言模型微调使用的训练目标。2. 发现了训练目标与LoRA权重空间几何特征之间的相关性。3. 准确预测了具有不同训练目标的适配器在特定条件下导致的有害行为。
### Conclusion
研究结果表明，LoRA权重空间的几何结构可以编码训练目标、强度排序以及粗略关联的有害合规性。因此，在不同的训练方法之间进行监控时，需要针对每种方法进行校准。此外，主成分分析显示训练目标是第一主要成分，而训练时长是第二正交的主要成分。
## 50. `cs.LG` - Dictionary-Aligned Concept Control for Safeguarding Multimodal LLMs [PDF](https://arxiv.org/pdf/2604.08846), [HTML](https://arxiv.org/abs/2604.08846)
### Authors
Jinqi Luo,Jinyu Yang,Tal Neiman,Lei Fan,Bing Yin,Son Tran,Mubarak Shah,René Vidal
### Background
近期研究表明，多模态大语言模型（MLLMs）对于恶意查询的抵御能力较弱，这可能导致产生不安全的回答。现有的一些方法，如提示工程、响应分类或微调，虽然在提高MLLM安全方面取得了一些进展，但仍然存在不足之处，比如对不断变化的恶意模式效果不佳、需要重新运行查询，或者需要大量的计算资源。最近有些方法试图在推理时控制模型的激活，这样可以更灵活且有效地提升模型安全性。然而，现有的多模态大语言模型的控制方法往往只能处理少量安全相关概念，或者在调整特定概念时会受到影响。
### Innovation
本文介绍了一种名为Dictionary-Aligned Concept Control (DACO)的框架，这一框架利用精心策划的概念词典和稀疏自编码器（SAE）来精细控制MLLM的激活。首先，通过检索400,000个带有图像描述的数据样本，总结其激活，形成了一个包含15,000个多模态概念的概念词典，并生成了名为DACO-400K的数据集。其次，展示了这个精心策划的概念词典可以通过稀疏编码干预激活过程。第三，提出了一种新的控制方法，使用该词典来初始化SAE的训练，并自动生成SAE原子的语义注释，以确保MLLM的安全性。实验结果表明，DACO在保持通用能力的同时，显著提升了MLLM的安全性。
### Conclusion
通过引入DACO框架，不仅可以提高多模态大语言模型的安全性，也能够保证模型的通用性。本文的方法经过多个多模态大语言模型和多个安全标准测试后，显示出在控制模型激活方面具有显著的效果。
## 51. `cs.LG` - 利用神经网络解决单元调度问题的两阶段随机优化方法 [PDF](https://arxiv.org/pdf/2507.09503), [HTML](https://arxiv.org/abs/2507.09503)
### Authors
Zhentong Shao,Jingtao Qin,Nanpeng Yu
### Background
本文提出了一个解决高维度不确定性场景下的两阶段随机单元承诺（2S-SUC）问题的神经随机优化方法。传统的解法效率低下，面对复杂不确定性时难以精确求解。
### Innovation
提出了一种方法，使用深度神经网络来近似解决第二阶段的补救问题，并将训练后的网络嵌入到第一阶段的单元承诺问题中，形成了一个混合整数线性规划模型。通过情景嵌入网络实现维度缩减和特征聚合，提供了数据驱动的场景缩减机制，显著提升了求解效率。
### Conclusion
数值实验表明，所提出的方法具有不到1%的最优解偏差，并且相比传统的MILP求解器和分解方法，提供了数量级的加速。模型规模在不同场景数量下保持不变，为大规模随机单元承诺问题提供了显著的可扩展性。
## 52. `cs.LG` - 基于图驱动语言模型的贝叶斯社会推理 [PDF](https://arxiv.org/pdf/2506.17788), [HTML](https://arxiv.org/abs/2506.17788)
### Authors
Shahab Rahimirad,Guven Gergerli,Lucia Romero,Angela Qian,Matthew Lyle Olson,Simon Stepputtis,Joseph Campbell
### Background
社会推理，即从部分观察推断他人不可见的信念和意图，对于大型语言模型（LLMs）依然是一个具有挑战性的任务。现有的语言模型在社会推理游戏中展示了一定的能力，但当被压缩成更小、实时版的模型时，性能会急剧下降。
### Innovation
本文提出了一个混合推理框架，该框架将信念推理外部化至结构化的概率模型，使用LLM进行语言理解和交互。这种框架在实验中实现了与更大模型相当的表现，并且是第一个在控制实验中击败人类玩家的语言代理。
### Conclusion
基于代理对代理的测试，我们的方法实现67%的胜率，并且得到了比语言推理基线以及人类队友更高的定性评价。研究结果表明，该框架具有在LLM代理中进行更深层次社会推理的应用前景，研究代码、模型和数据集已开放供后续研究使用。
## 53. `cs.LG` - 超越球形几何：使用深度学习从恒星旁行进系统的准星光曲线中揭示复杂特征 [PDF](https://arxiv.org/pdf/2509.14875), [HTML](https://arxiv.org/abs/2509.14875)
### Authors
Ushasi Bhowmick,Shivam Kumaran
### Background
分析从恒星旁行进系统的准星光曲线来表征天体的几何形状是一种强大的工具，可以揭示各种复杂的天体现象。然而，这种问题本质上是病态的，因为不同的形状可以产生相似或相同的准星光曲线。
### Innovation
研究通过生成二维随机形状并模拟它们的准星光曲线来探讨形状特征嵌入准星光曲线的程度。利用深度神经网络直接从模拟的光曲线预测这些傅里叶系数，展示了神经网络能够成功重构整体形状、方向和大尺度扰动，但对高阶椭圆参数的推理能力有限，揭示了光曲线中的形状信息。
### Conclusion
神经网络的重建成效强调了利用准星光曲线提取转行系统几何信息的实用性，并探讨了非凸形状特征在重构过程中的影响及其与形状方向的依赖关系。
## 54. `cs.LG` - 交互式程序合成：从叙述演示中建模协同物理活动 [PDF](https://arxiv.org/pdf/2509.24250), [HTML](https://arxiv.org/abs/2509.24250)
### Authors
Edward Kim,Daniel He,Jorge Chao,Wiktor Rajca,Mohammed Amin,Nishant Malpani,Ruta Desai,Antti Oulasvirta,Bjoern Hartmann,Sanjit Seshia
### Background
在人机交互（HCI）领域，教授系统执行物理任务已有很长时间的目标，但大多数先前的研究集中在协作物理活动上。协作任务引入了更多的复杂性，要求系统推断用户的假设，即队友的意图，这是一个本质上是模糊和动态的过程。这就需要可解释和可纠正的表示方法，使用户可以检查和改进系统行为。
### Innovation
本文通过将协作任务学习作为程序合成问题来解决这一挑战。系统将行为表示为可编辑的程序，并通过叙述示范，即配对的物理动作和自然语言，作为统一的教学、检查和纠正系统逻辑的模式，无需让用户看到或编写代码。该模式还用于系统向用户传达其学习内容。
### Conclusion
在针对多用户足球战术的教学实验中，20名参与者的成功率为70%（14/20），能够调整学习后的程序以符合他们的意图，90%（18/20）的参与者发现更改程序很容易。这些研究揭示了作为程序表示学习的独特挑战以及教授协作物理活动的用户问题。文章讨论了这些问题并提出了缓解策略。
## 55. `cs.LG` - RESample：通过探索性采样提高鲁棒数据增强框架的机器人操作 [PDF](https://arxiv.org/pdf/2510.17640), [HTML](https://arxiv.org/abs/2510.17640)
### Authors
Yuquan Xue,Guanxing Lu,Zhenyu Wu,Chuanrui Zhang,Bofang Jia,Zhengyi Gu,Ziwei Wang
### Background
在最近的机器人操作研究中，视觉-语言-动作(VLA)模型通过模仿学习在复杂任务中展现了卓越的能力。这些模型通过大量高质量指导性数据集被训练，积累了强大的能力。然而，这些数据集大多由成功的轨迹组成，成本高昂且分布有限，导致在部署过程中遇到未知分布（OOD）场景时，其能力受限，难以恢复。
### Innovation
本文提出了名为RESample的自动数据增强框架，通过设计良好的探索性采样机制来有效扩大VLA训练数据集的覆盖范围。该框架在策略执行过程中识别潜在的覆盖缺口，并积极采样探索性动作以高效扩展训练数据的覆盖范围，同时提出了一种轻量级覆盖率函数以引导探索性采样过程关注低覆盖区域。实验结果表明，与基线相比，RESample在LIBERO基准测试和一系列真实的机器人任务中表现出12%的性能提升，仅需额外增加10-20%的样本量。
### Conclusion
通过RESample框架，探索性采样机制提高了VLA训练数据集的分布覆盖范围，增强了在未知分布场景下的鲁棒性，并在实验证明中实现了显著的性能提升。
## 56. `cs.LG` - 任务无关刺激对神经表示漂移的贡献 [PDF](https://arxiv.org/pdf/2510.21588), [HTML](https://arxiv.org/abs/2510.21588)
### Authors
Farhad Pashakhanloo
### Background
生物和人工学习者在其一生中不断接触数据和经验，必须不断适应、学习或忽略持续输入。近期研究表明，即使性能保持稳定，底层神经表示也可能随时间逐渐变化，这种现象称为表示漂移。研究可能引起漂移的数据源和噪声类型对于理解神经系统的终身学习至关重要。然而，缺乏对不同架构和学习规则下的漂移系统的研究，以及与任务的关联性。
### Innovation
本研究在线学习设置下，将漂移作为数据分布的函数进行刻画，特别证明了任务无关刺激引起的学习噪音，这些噪音在给定上下文中被学习代理忽略，可以导致任务相关刺激表示的长期漂移。通过理论和模拟，证明了这一现象存在于Hebbian学习规则（Oja's规则和相似匹配）以及在自动编码器和监督两层网络中的随机梯度下降上。连续观察到，随任务无关子空间的数据方差和维度增加，漂移率增加。进一步证明，这导致了与高斯突触噪声下漂移的几何和维度依赖性不同的质性预测。
### Conclusion
本研究建立了刺激结构、任务和学习规则与表示漂移之间的联系，可用于作为揭示大脑底层计算的信号，并为理解人工和生物学习的表示漂移提供了新的视角。
## 57. `cs.LG` - 离散化 MeanFlow 训练课程 [PDF](https://arxiv.org/pdf/2604.08837), [HTML](https://arxiv.org/abs/2604.08837)
### Authors
Chia-Hong Hsu,Frank Wood
### Background
基于基于流的图像生成模型的研究背景，背景描述基于流的图像生成模型在采用采用多多-step 抽样过程中可以产生高质量的样本，， 膺创位于这些模型在一次步生成过程中虽然可以产生高质量的图像样本，但同时却由于不稳定的训环节动而难以优化。而 MeanFlow 模型在多次步抽样和一次步抽样方面都表现出色
### Innovation
本研究提出了离散化的 MeanFlow (Discrete MeanFlow, DMF) 训课方案。该方案通过一种特殊的 MeanFlow 目标函数离散化处理，并通过形式一个“Discrete MeanFlow
### Conclusion
基于DMF训练课程的初步结果展示表明，该课程可以显著减少training budget的使用，同时也预计得更从当前的flow模型开发出更快的traininging课程能够加速one对one的生成。”完整翻译和纠正后的摘要：## 背景基于基于流的图像生成模型的研究，这类模型虽然在多步抽样中能生产高质量的样本，但在一次步抽样中优化困难重重。而MeanFlow模型在多次步抽样和一次步抽样中表现俱佳，## 创新本研究提出了离散化的MeanFlow (DMF）训练课程方案。通过一种特定的对MeanFlow 目标函数进行离散化处理，并对这种处理进行了形式化，进而形成“离散化MeanFlow” 课程体系。由预先训练过好的流模型初始化，DMF课程体系能够在CIFAR-1 仅2 个 epoch 虨达一次步FID得3.36，显示采用DMF训练课程能够显著节约计算和预算开销,## 结论基于DMF课程的最初结果表明,该课程可以显著减少训练预算的使用且预期在未来将更快的训练课程能够进一步加速一次步生成能力”
