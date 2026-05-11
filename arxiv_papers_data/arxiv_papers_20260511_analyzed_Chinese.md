# 20260511
[![Subscribe_Visitors](https://visitor-badge.laobi.icu/badge?page_id=nituchao.latest_arxiv_analyze_ai_rss)](https://github.com/nituchao/latest_arxiv_analyze_ai)

## 1. `cs.AI` - PRISM：交错感知与推理以实现序列决策 [PDF](https://arxiv.org/pdf/2605.05407), [HTML](https://arxiv.org/abs/2605.05407)
### Authors
Mohamed Salim Aissi,Clemence Grislain,Clement Romac,Laure Soulier,Mohamed Chetouani,Olivier Sigaud,Nicolas Thome
### Background
基于LLM的具有感知能力的代理从仅文本环境扩展到复杂的多模态环境是一个主要挑战。现有研究指出，独立的视觉-语言模型（VLM）存在感知-推理-决策之间的差距，常忽略关键任务信息。
### Innovation
本文提出了PRISM框架，该框架通过动态问答（DQA）流程紧密结合了感知（VLM）和决策（LLM），而不是被动接受VLM的描述，LLM会对VLM进行评估，并用目标导向的问题进行探究，生成紧凑的图像描述。这种闭环交互提高了任务导向的理解度。
### Conclusion
PRISM在ALFWorld和Room-to-Room（R2R）基准测试中表现优异：（1）PRISM显著超越了当前最先进的基于图像的模型；（2）我们的交互式目标导向感知流水线提供了系统性和实质性的提升；（3）PRISM是全自动的，无需手工艺品问题或答案。
## 2. `cs.AI` - BALAR : 一个贝叶斯代理循环用于主动推理 [PDF](https://arxiv.org/pdf/2605.05386), [HTML](https://arxiv.org/abs/2605.05386)
### Authors
Aymen Echarghaoui,Dongxia Wu,Emily B. Fox
### Background
大型语言模型越来越多地在需要多轮信息交换的交互式环境中操作，以解决一个任务。然而，大多数当前系统对此类交互反应性较强，缺乏一个有原则的方法来推断哪些信息缺失以及下一个应该问的哪些问题。
### Innovation
本文提出了一种任务无关的外循环算法BALAR（贝叶斯代理循环），该算法无需微调即可在语言模型代理和用户之间实现结构化的多轮交互。BALAR维护对潜在状态的结构化信念，通过最大化预期互信息来选择澄清问题，并在当前状态证明不足以解决问题时动态扩展其状态表示。
### Conclusion
在AR-Bench-DC（侦探案件）、AR-Bench-SP（思考迷题）和iCraft-MD（临床诊断）三个不同基准的评估中，BALAR在所有基准上均显著优于所有基线，分别在AR-Bench-DC上准确性高出14.6%，在AR-Bench-SP上高出38.5%，在iCraft-MD上高出30.5%。
## 3. `cs.AI` - 基于智能CCTV的都市设计：交叉路口软基础设施的AI分析 [PDF](https://arxiv.org/pdf/2605.05402), [HTML](https://arxiv.org/abs/2605.05402)
### Authors
Vinit Katariya,Seungjin Kim,Curtis Craig,Nichole Morris,Hamed Tabkhi
### Background
人工智能（AI）和计算机视觉正在变革交通数据分析方式。本研究利用现有的闭路电视（CCTV）网络引入了一个AI赋能的分析框架，以评估临时性的人行道避难所和人行横道扩展等软干预措施对车辆速度和安全的影响。
### Innovation
本研究利用深度学习和基于视角的车速估算方法，对干预前后的驾驶员行为进行了评估，并在明尼阿波利斯进行了两周的重复安装后监测。结果显示，在不设信号的交叉路口，平均车速和85百分位车速分别下降了18.75%和16.56%，穿行交通减少了12.2%；在设有信号的交叉路口，平均车速和85百分位车速分别下降了20.0%和17.19%。这些结果表明软基础设施的交通减速效果，并强调了AI驱动的方法对于快速、低成本及基于证据的交通政策评估的效用。
### Conclusion
本研究表明，在交叉路口应用软基础设施可以有效减缓交通，且AI赋能的方法可以提供快速、低成本及基于证据的交通政策评估手段。
## 4. `cs.AI` - LaTA: 一种适用于高级STEM课程的即用型、符合FERPA的地方大语言模型自动评分器 [PDF](https://arxiv.org/pdf/2605.05410), [HTML](https://arxiv.org/abs/2605.05410)
### Authors
Jesse A. Rodríguez
### Background
上层STEM课程的评分任务繁重，现有的大语言模型（LLM）评分器大多将学生作业发送给第三方API，这违反了FERPA（家庭教育权利和隐私法案），并给机构带来了数据风险，同时需要对作业进行重大修改。因此，一个能够在本地运行、无需额外硬件成本且符合FERPA的地方LLM自动评分器对于提高评分效率和保护学生数据隐私具有重要意义。
### Innovation
提出了一种名为LaTA（LaTeX Teaching Assistant）的即用型、开源自动评分器，它在现有的本地计算硬件上运行，并采用了一个本地托管的开源权重链式思维LLM评分器。该系统采用了一个四步流水线（导入、分段、评分、报告），并结合了一个基于YAML的评分模型和二进制评分项评分，能够以极低的成本和快速响应时间自动评分学生作业，并能够进行评分后的重新评分。LaTA确保了符合FERPA的要求，避免了第三方API带来的数据风险。
### Conclusion
在Oregon State University的ME 373课程上部署了LaTA，实现了大规模作业的自动化评分，节省了教师时间和资源，提高了评分准确性。LaTA-评分的学生在期中和期末考试中的表现优于传统的评分方式，且学生的自我评估信心明显提高，验证了LaTA在提高评分效率和学生学习效果方面的有效性。
## 5. `cs.AI` - 金融文档检索增强生成方法 [PDF](https://arxiv.org/pdf/2605.05409), [HTML](https://arxiv.org/abs/2605.05409)
### Authors
Yang Shu,Yingmin Liu,Zequn Xie
### Background
金融文档问答（QA）需要在公司文件中分散的结构化表格、文本叙述和脚注等异构证据上进行复杂的多步数值推理。现有的检索增强生成（RAG）方法采用单一检索-生成范式，难以处理金融分析中常见的组合推理链。
### Innovation
提出了FinAgent-RAG框架，这是一种代理型RAG框架，通过迭代检索-推理循环和自我验证来解决金融数值推理所需的高度精准性需求。框架包含三个特定领域的创新：（1）通过困难的负样本挖掘训练的对比金融检索器，以区分语义相似但数值不同的金融段落；（2）编程思考推理模块，生成可执行的Python代码进行精确算术，而非依赖可能出错的语言模型进行心算；（3）自适应策略路由器，根据问题复杂度动态分配计算资源，使得在FinQA上的API成本减少了41.3%，同时保持了准确性。
### Conclusion
在三个基准数据集（FinQA、ConvFinQA和TAT-QA）上的广泛实验表明，FinAgent-RAG分别实现了76.81%、78.46%和74.96%的执行准确率，优于最强基线5.62-9.32个百分点。消融研究、跨骨干网络评估和部署成本分析验证了该框架在金融机构中的可靠性和实用性。
## 6. `cs.AI` - VideoRouter: Query-Adaptive Dual Routing for Efficient Long-Video Understanding [PDF](https://arxiv.org/pdf/2605.05848), [HTML](https://arxiv.org/abs/2605.05848)
### Authors
Kuanwei Lin,Wenhao Zhang,Ge Li
### Background
视频大规模多模态模型在处理长视频时面临扩展性瓶颈：长时间视频会产生过长的视觉标记序列，在推理时显著增加内存和延迟。现有压缩方法在特定条件下有效，但大多数要么对查询的感知较弱，要么在整个帧上应用固定的压缩策略，这在视觉证据不均匀分布时效果不佳。
### Innovation
提出了VideoRouter，一个基于InternVL的查询自适应双重路由器框架，用于预算内证据分配。该框架包含语义路由器和图像路由器，能够根据不同帧的重要性进行压缩。语义路由器预测主导分配策略，选择时空覆盖或自适应高分辨率保留之间的权衡；图像路由器使用早期的LLM层评估帧的相关性。这使得对不太相关的帧进行激进压缩，同时保留关键证据帧的细节。
### Conclusion
在VideoMME、MLVU和LongVideoBench上的实验表明，VideoRouter在具有可比或更低预算的情况下，比InternVL基线模型更优，最高可减少67.9%的视觉标记数量。
## 7. `cs.AI` - SOPE: 使用先验数据稳定离策略评估以实现在线强化学习 [PDF](https://arxiv.org/pdf/2605.05863), [HTML](https://arxiv.org/abs/2605.05863)
### Authors
Carlo Romeo,Girolamo Macaluso,Alessandro Sestini,Andrew D. Bagdanov
### Background
在线强化学习通过结合历史数据可以加速训练过程，但通常面临着高计算成本与长期多阶段训练之间的艰难取舍。虽然固定长度的稳定阶段比静态更新计划更为计算高效，但它们需要任务特定的手动调优，这可能导致先验知识的浪费或严重过拟合。
### Innovation
提出了一种名为SOPE的算法，使用与动作者对齐的离策略策略评估（OPE）信号自动早期停止机制来动态控制离线训练阶段的长度。通过在保留的验证分割上评估当前策略动作分布下的评论家，SOPE在不分布效益饱和时停止梯度更新，从而消除了手动计划调优的需求。
### Conclusion
在Minari基准套件的25项连续控制任务上的评估显示，SOPE将基线性能提高45.6%，同时减少了高达22倍的TFLOPs需求。这些结果表明，适应性、基于评估的更新计划比依赖静态详尽更新计划更有效。
## 8. `cs.AI` - 逻辑规则化验证器激发LLMs的推理能力 [PDF](https://arxiv.org/pdf/2605.05893), [HTML](https://arxiv.org/abs/2605.05893)
### Authors
Xinyu Wang,Changzhi Sun,Lian Cheng,Yuanbin Wu,Dell Zhang,Xiaoling Wang,Xuelong Li
### Background
验证器对于提升现代大语言模型（LLMs）的推理能力至关重要。传统验证器需要耗费资源建立监督数据集，成本高昂且在数据多样性方面存在局限。
### Innovation
本文提出LOVER（逻辑规则化验证器），这是一种通过逻辑规则进行正则化的无监督验证器。LOVER将验证器视为二元潜在变量，并通过内部激活及三个逻辑约束对多种推理路径进行约束：否定一致性、组内一致性和组间一致性（按最终答案分组）。LOVER可以通过引入逻辑规则作为先验知识，利用未标记的示例，并且可以直接与任何现成的LLMs兼容。实验结果表明，LOVER在10个数据集上显著优于无监督基准，其性能与监督验证器相当（平均达到其95%的水平）。
### Conclusion
实验结果显示，LOVER在10个数据集上的表现显著优于无监督基准，其性能达到监督验证器的95%水平。源代码已在GitHub上公开。
## 9. `cs.AI` - 使用脉冲神经网络检测AI生成的视频 [PDF](https://arxiv.org/pdf/2605.05895), [HTML](https://arxiv.org/abs/2605.05895)
### Authors
Minsuk Jang,Yujin Yang,Heeseon Kim,Minseok Son,Younghun Kim,Changick Kim
### Background
现代的AI生成视频在单帧层面高度逼真，检测主要集中在帧间的动态变化上。现有检测器通常通过全帧序列、固定视频层级描述符或基于检测指标的时空特征对比来处理时间证据，但在跨生成器评估中表现较差，因为不同生成器的生成特征差异大。作者通过GenVidBench基准测试发现，AI生成的视频在像素级帧间残差上更平滑，在语义特征空间中的轨迹更紧凑。此外，直接输入脉冲神经网络后，假视频在对象和运动边界处引发神经元放电，而真视频则没有，这表明SNN对边缘局部化的时域伪影的响应更为敏感。
### Innovation
作者提出了一个名为MAST的检测器，它结合了脉冲驱动的时空分支和固定语义编码器。MAST能够在严格的跨生成器评估中在GenVideo基准上达到93.14%的平均准确率，超过了最强的基于神经网络的检测器，展现出了SNN在AI生成视频检测中的实际应用潜力。
### Conclusion
研究结果表明，脉冲神经网络在检测AI生成的视频方面具有较好的性能，并展示了其与传统密集型神经网络架构相比的优势。这项工作为未来研究提供了新的思路和可能的解决方案。
## 10. `cs.AI` - MTL-MAD: 多任务学习器是有效的医学异常检测器 [PDF](https://arxiv.org/pdf/2605.05891), [HTML](https://arxiv.org/abs/2605.05891)
### Authors
Bogdan Alexandru Bercean,Florinel Alin Croitoru,Vlad Hondru,Ciprian Mihai Ceausescu,Andreea Iuliana Ionescu,Radu Tudor Ionescu
### Background
医学图像中的异常检测是一项具有挑战性的任务，因为训练过程中通常无法获取异常样本。最近的方法是利用单一的前置任务和大规模预训练模型来达到最先进的性能。然而，本文提出了一种新的方法，通过从头开始学习多个自监督和伪标签任务，并基于Mixture-of-Experts（MoE）构建联合模型。这种方法通过精心整合多个代理任务，使联合模型能够学习出健壮的正常解剖结构表示，从而在推理过程中根据多任务学习者（MTL）解决每个任务的能力，导出异常评分。
### Innovation
本文提出了一个多任务学习器（MTL）来解决医学图像中的异常检测问题。具体而言，该模型通过从头开始学习多个自监督和伪标签任务，并基于Mixture-of-Experts（MoE）构建联合模型。通过精心整合多个代理任务，该方法有效地学习了一种健壮的正常解剖结构表示，从而能够在推理过程中根据多任务学习者（MTL）解决每个任务的能力来导出异常评分。
### Conclusion
通过在BMAD这一最新的基准上进行全面的实验，实证结果表明，我们的多任务学习器是一个有效的异常检测器，在BMAD上优于所有最新竞争对手。此外，我们的模型还生成了可解释的异常图，可能有助于医生提供更准确的诊断。
## 11. `cs.AI` - 因果公平性机器学习中的梯度导数 [PDF](https://arxiv.org/pdf/2605.05882), [HTML](https://arxiv.org/abs/2605.05882)
### Authors
Filip Edström,Guilherme W. F. Barros,Tetiana Gorbach,Xavier de Luna
### Background
目前，，,人工智能系统在社会中无处不在，，，这些系统通常继承了针对特定属性（如 如种族、性别和年龄) 的偏见。经典公平性 (如 如统计一致性) SP) 蟹 要预测结果与这些属性独立， 但是 当这些属性影响中介变量时 时 时 需要综合考虑必要的条件时 会过于严格。。 近期因果论述放宽了 S  P 通过区分允许可行的因果路径和通过补充预测一致性 PP 杇 舫调 覫 P 以要求预测器复制合法的影响因子人员界面上 当前大多数基于分类变量的定义主要是可行的 当 荐 当应用于连续变量时 运行成为挑战。尽管已有工作探讨了这类问题 但缺乏专为这些属性量身定制的公平公定框架。本文旨在填补这一空白。
### Innovation
本文引入了一个针对连续变量结构因果模型的公平性的分析框架 该框架区分了允许的因果路径和 由专门的梯度导数定义 依据该定义 本文确立了条件使得这些标准与先前的因果定义一致 并明确了在满足 SP 和允许路径的同时实现 PP 的存在条件。基于此类理论 本文还提出了一种比例算法 该算法允许在 SP 和与 PP 间寻求权衡 评介了提出的方法 在实现在方表明当 PP 适用时 该方法能够实现 PP。
### Conclusion
本文从连续变量结构因果模型出发 通过定义专门梯度导数 重新审视了统计一致性和预测一致性的公平定义 通过提供一个比例化算法 使得能够在这两者中取得平衡。在评价中 运藏已经证明该方法在线连续变量适合 干并将实际验证了在实现 PP 的条件下 该方法的有效性。
## 12. `cs.AI` - DeTrigger: 一种基于梯度的联邦学习中后门攻击缓解方法 [PDF](https://arxiv.org/pdf/2411.12220), [HTML](https://arxiv.org/abs/2411.12220)
### Authors
Kichang Lee,Yujin Shin,Jonghyuk Yun,Songkuk Kim,Jun Han,JeongGil Ko
### Background
联邦学习（FL）允许分布式设备在保护本地数据隐私的同时协作训练模型，特别适合移动和嵌入式系统。然而，联邦学习的去中心化特性也使模型面临后门攻击的风险，特别是当对手植入触发模式以操纵模型预测时。
### Innovation
DeTrigger 提出了一种可扩展且高效的方法来保护联邦学习环境免受复杂后门威胁。该框架利用对抗攻击的方法论，并通过温度缩放的梯度分析检测和隔离后门触发器，避免了对良性模型知识的影响。广泛的实验证明，DeTrigger 在四个常用数据集上的检测速度比传统方法快 251 倍，并且能够通过高达 98.9% 的方式缓解后门攻击，对全局模型准确性的影响最小。
### Conclusion
研究结果确立了 DeTrigger 作为一种稳健且可扩展的解决方案，能够保护联邦学习环境免受复杂的后门威胁。
## 13. `cs.AI` - CatNet: 使用SHAP特征重要性和Gaussian Mirrors控制LSTM的假发现率 [PDF](https://arxiv.org/pdf/2411.16666), [HTML](https://arxiv.org/abs/2411.16666)
### Authors
Jiaan Han,Junxiao Chen,Yanzhe Fu
### Background
LSTM模型在处理时间序列和序列数据时表现出色，但存在特征选择不稳定的问题，尤其是在非线性或时间相关特征的情况下。增加错误发现率（FDR）的风险限制了模型的解释性和鲁棒性。
### Innovation
CatNet算法通过使用SHAP值的导数来量化特征的重要性，并利用高斯镜像算法构造向量形式的镜像统计量来进行FDR控制。此外，还提出了一种新的基于核的独立性度量，以避免不稳定性和提高模型性能。
### Conclusion
CatNet在不同的模型设置下，无论是模拟数据还是真实世界的数据上都表现出了强大的鲁棒性，减少了过拟合并提高了模型的可解释性。引入SHAP和改进的高斯镜像算法的框架可以自然地扩展到其他时间序列或顺序的深度学习模型中。
## 14. `cs.AI` - LicenseGPT：专为公共数据集许可合规设计的调优基础模型 [PDF](https://arxiv.org/pdf/2501.00106), [HTML](https://arxiv.org/abs/2501.00106)
### Authors
Jingwen Tan,Gopi Krishnan Rajbahadur,Zi Li,Xiangfu Song,Jianshan Lin,Dan Li,Zibin Zheng,Ahmed E. Hassan
### Background
公共数据集的使用越来越多，但这些数据集的许可条款往往存在模糊性，这增加了法律风险。即使对于知识产权律师，准确解释这些条款也颇具挑战。因此，开发一种专门用于数据集许可合规分析的人工智能工具是必要的。
### Innovation
本文提出了LicenseGPT，这是一个针对许可合规分析进行微调的基础模型。通过在500个由法律专家标注的许可证上进行微调，LicenseGPT显著提高了预测一致性（从43.75%提高到64.30%）。此外，通过A/B测试和软件知识产权律师的研究，证明了LicenseGPT能将分析时间减少94.44%，同时保持准确性，被视作高效的辅助工具。
### Conclusion
本研究强调了专门化AI工具在法律实践中的潜力，并提供了一个公开可用的资源，可供从业者和研究人员使用。
## 15. `cs.AI` - SOWing Information: Cultivating Contextual Coherence with MLLMs in Image Generation [PDF](https://arxiv.org/pdf/2411.19182), [HTML](https://arxiv.org/abs/2411.19182)
### Authors
Yuhan Pei,Ruoyu Wang,Yongqi Yang,Ye Zhu,Olga Russakovsky,Yu Wu
### Background
来源于物理学中的扩散现象，描述了粒子的随机运动和碰撞，扩散生成模型在数据空间沿去噪轨迹进行随机行走，使得信息在整个区域中扩散，形成和谐的结果。然而，扩散模型中信息的无序扩散常常导致图像区域间不必要的干扰，导致细节保存欠佳和语境不一致。
### Innovation
本文通过将无序扩散重新定义为一个强大的文本-视觉-图像生成（TV2I）任务工具，从而实现了像素级条件保真，在保有视觉和语义一致性的同时，解决了细节保存欠佳和语境不一致的问题。作者首先引入了Cyclic One-Way Diffusion (COW)，提供了一个高效且单向的扩散框架，进行精确的信息传递，最小化干扰。在此基础上，进一步提出了Selective One-Way Diffusion (SOW)，利用多模态大型语言模型 (MLLMs) 认清图像中的语义和空间关系，结合注意力机制动态调节扩散的方向和强度，根据上下文关系进行调节。
### Conclusion
广泛的实验证明了可控的信息扩散的潜在价值，表明无需训练的方法可以导向更具适应性和多功能性的生成模型，从而开辟了新的研究方向。
## 16. `cs.AI` - ReMAP: 基于神经重参数化的任意阶马尔可夫随机场的可扩展MAP推断 [PDF](https://arxiv.org/pdf/2411.18954), [HTML](https://arxiv.org/abs/2411.18954)
### Authors
Yaomin Wang,Chaolong Ying,Xiaodong Luo,Tianshu Yu
### Background
在任意阶马尔可夫随机场（MRFs）中进行高质量的最大后验（MAP）推断仍然具有挑战性。近似消息传递方法通常效率较高，但在稠密或高阶实例上可能降低性能，而精确求解器如Toulbar2随着规模扩大成本逐渐增加。该文介绍了ReMAP，一个针对每个实例的神经重参数化框架，直接优化原始MRF能量的一个可微松驰形式。ReMAP不依赖监督标签或递归训练，而是将每个MRF视为独立的优化问题：图神经网络产生节点级别的标签分布，梯度基优化在过度参数化的连续空间中搜索低能量的离散解。该方法支持双元和任意阶因素，异构标签基数，以及高效的GPU执行，无需要求带有标签的解决方案。
### Innovation
ReMAP通过图神经网络生成节点级别的标签分布，并在过度参数化的连续空间中进行梯度基优化以搜索低能量的离散解。该方法直接优化原始MRF能量的可微松驰形式，支持双元和任意阶因素，异构标签基数，以及高效的GPU执行。文中证明了松弛目标与离散的MAP问题是一致的，并分析了神经过度参数化如何揭示在原始离散空间中不可用的低能量优化路径。
### Conclusion
在合成的双元和高阶MRFs，UAI 2022推断基准测试以及真实的物理小区标识（PCI）问题上，ReMAP在实用的时间预算内始终优于近似基准，并在困难的大规模实例中经常找到比Toulbar2更低能量的解决方案。
## 17. `cs.AI` - 在保持语义不变的代码变换下，大型语言模型在理解代码方面是否稳健？ [PDF](https://arxiv.org/pdf/2505.10443), [HTML](https://arxiv.org/abs/2505.10443)
### Authors
Pedro Orvalho,Marta Kwiatkowska
### Background
随着vibe编码的广泛应用，理解大型语言模型（LLMs）的推理能力和鲁棒性变得至关重要，特别是在编程任务中的应用。尽管最近的研究评估了LLMs预测程序输出的能力，大多数研究仅关注准确性，而没有评估其背后的推理过程。研究表明，LLMs在数学推理任务中可以依靠错误的逻辑得到正确的答案，这引发了它们在代码理解上的类似问题的担忧。为了解决这一问题，本研究评估了当前最先进的LLMs在处理Python程序时是否具备合理的推理能力，还是只是猜测。
### Innovation
本研究通过应用五种保持语义但改变语法的代码突变，评估了包括开源和封闭源代码模型在内的九种LLMs的推理能力和鲁棒性。突变包括变量重命名、比较表达式镜像、if-else分支互换、for循环转换为while循环和循环展开。研究还使用LiveCodeBench和CruxEval评估了预测稳定性和不同代码突变下的预测变化。研究发现，虽然某些自有模型在专家评估中表现出最强的预测准确性和推理质量，但在表示语义不变的突变下的鲁棒性分析显示其存在显著脆弱性。
### Conclusion
研究表明，LLMs生成正确预测是在部分情况下基于有问题推理的比例在10%至50%之间，此外，在代码突变后LLMs的预测改变频率高，性能下降甚至高达70%，表明它们尚未表现出稳定且语义基于的推理能力，即使初始准确性很高。
## 18. `cs.AI` - Cohort-Based Active Modality Acquisition [PDF](https://arxiv.org/pdf/2505.16791), [HTML](https://arxiv.org/abs/2505.16791)
### Authors
Tillmann Rheude,Roland Eils,Benjamin Wild
### Background
现实世界中的多模态机器学习（Multim Modal Machine Learning) 中经常面临需要获取多种模态数据的问题，但是在预算限制下，经常缺乏资源去获取所有模态数据。为此，研究者们主要通常研究在一个预算限制下的采样问题 (Sample-level Acquisition) 中但是在研究时通常偏向于个体样本级面时长忽略的是在测试时时间时样变异行水平上的 (Test-time) 权重的模态获取 (Modal Acquisition)。在此研究背景下 正模态的采样策略 (Cohort-level Acquisition) 中的研究相对来看比较少。
### Innovation
本文研究提出了一种基于群体 (Cohort-based) 新的测试时模态主动获取方法 (Active Modality Acquisition CAMA) 。该方法主要考虑了一个在测试时时质量下对缺失模态数据进行估计的策略对策略 (Imputation-based Strategies) 幩니다并通过一些上限启发 (Upper-bound Heuristics) 于以优化模拟模式的获取过程 (Acquisition Process) 。这种方法上特别设计为优化群体级别的模态获取获取 (Cohort-level Modality Acquisition) 以及提供对可一种有效的评估方案段 (Benchmarking) 来以供行的结果评测。研究结果通过在多模态数据集上上的和一种大包含 1④  个模态的表现，展示了 了基于的方法方法允许更高效地 地为选定样本获取额外模态更加有效相比单单依靠 上质量先验 (on-acquisition Entropy-based Guidance) 或随机获取样 (Random Sampling) 以及 了通过证明这些方法在现实情况中的实现蛋白质组学 (Proteomics) 在以预防疾病方面 的有效性和相关性分析中 夬在英国生物库 (UKonkaske UK Onank) 中展示了该方法在实际环境中的相关性和可施性。
### Conclusion
我们本研究表明了一种新的群体级级别模态获取方法 (Cohort-based Active mod Modality Acquisition (CAMA) 有效优化了在测试时间必须获取获取 的缺失模态数据 股的一个新提出的采样方法的优势在于于了 在示了这在实际应用场景中的可行性和优势。更多信息地通过在英国生物库(UK Bi)上的 个大流行队列的研究表偿展示了这种方在有资源的情形中 进一步提高了资源利用效率 应用于在预算约束下的环境。
## 19. `cs.CL` - 如何衡量检索质量：召回率的重要性 [PDF](https://arxiv.org/pdf/2512.20854), [HTML](https://arxiv.org/abs/2512.20854)
### Authors
Shelly Schwartz,Oleg Vasilyev,Randy Sawaya
### Background
在现实的检索环境中，尤其是面对大型且不断变化的知识库时，与查询相关的文档总数量通常未知，因此召回率无法计算。本文评估了几种处理这一限制的策略，通过测量检索质量指标与基于LLM（大型语言模型）生成的响应质量判断之间的相关性来进行评估。
### Innovation
引入了一种无需知道相关文档总数的简单检索质量衡量方法。实验在多个数据集中进行，这些数据集的相关文档数量相对较少（2-15篇）。评估了几种已建立的策略，并引入了一个新的简便的质量衡量标准。
### Conclusion
实验结果表明，在不知道所有相关文档数量的情况下，通过生成的响应质量来衡量检索质量是可行的。
## 20. `cs.CL` - Four Over Six: More Accurate NVFP4 Quantization with Adaptive Block Scaling [PDF](https://arxiv.org/pdf/2512.02010), [HTML](https://arxiv.org/abs/2512.02010)
### Authors
Jack Cook,Junxian Guo,Guangxuan Xiao,Yujun Lin,Song Han
### Background
随着大型语言模型变得越来越大，人们对低精度数值格式（如NVFP4）的兴趣日益增加，这有助于提高速度并减少内存使用。然而，将模型量化为NVFP4仍然具有挑战性，因为低精度通常会降低模型性能。
### Innovation
本文提出了一种名为‘4/6’的修改，它是一种块缩放的NVFP4量化算法，可以减少量化误差。‘4/6’方法通过自适应地将某些块缩放到较小的FP4值，使得可表示值的分布更加均匀，从而减少近最大值的量化误差。
### Conclusion
我们在Nemotron 3 Nano 30B-A3B模型架构的预训练实验中发现，‘4/6’方法将训练损失更接近BF16，并且可以在现代硬件加速器上高效实现，带来性能提升，同时计算开销 minimal。我们的代码已公开提供。
## 21. `cs.CL` - MediEval: 一个用于大型语言模型中患者情境下知识导向推理的一体化医疗基准 [PDF](https://arxiv.org/pdf/2512.20822), [HTML](https://arxiv.org/abs/2512.20822)
### Authors
Zhan Qu,Michael Färber
### Background
大型语言模型（LLMs）在医疗领域中的应用越来越广泛，但由于其可靠性和安全性问题，其采纳率受到了限制。现有的评价方法要么单独测试医疗事实知识，要么评估患者层面的推理能力但缺乏正确性验证，存在关键缺陷。
### Innovation
引入了MediEval基准，将MIMIC-IV电子健康记录(EHRs)与从UMLS和其他生物医学词汇表构建的统一知识库链接起来。MediEval在真实患者的背景下生成多样化的真实和反事实的医疗陈述，能够在4象限框架中系统评估知识落地和上下文一致性。基于此框架，发现当前广泛采用的专属、开源和特定领域的LLMs普遍存在虚构性和真相倒置等关键问题，并提出了基于DPO的Counterfactual Risk-Aware Fine-tuning（CoRFu）方法，特定惩罚不当混淆以提高安全性。
### Conclusion
CoRFu在宏F1分数上超过基模型16.4个百分点，并消除了真相倒置错误，显示了更高的准确性和显著更安全的特点。
## 22. `cs.CL` - KORE: 通过知识导向控制增强大型多模态模型的知识注入 [PDF](https://arxiv.org/pdf/2510.19316), [HTML](https://arxiv.org/abs/2510.19316)
### Authors
Kailin Jiang,Hongbo Jiang,Ning Jiang,Zhi Gao,Jinhe Bi,Yuchen Ren,Bin Li,Yuntao Du,Lei Liu,Qing Li
### Background
大型多模态模型在其预训练权重中存储了大量的事实知识，但这些知识是静态和有限的，无法跟上现实世界的发展，这阻碍了持续的知识获取。有效的知识注入变得至关重要，涉及两个目标：知识适应（注入新知识）和知识保持（保留旧知识）。现有方法在学习新知识时经常遇到困难，并且容易出现灾难性遗忘。
### Innovation
为了应对上述挑战，本文提出了KORE（知识导向增强和约束），这是一种协同方法，用于将新知识注入大型多模态模型的同时保持旧知识。KORE自动将个体知识项转化为结构化和全面的知识，确保模型准确学习新知识，实现准确的适应。同时，KORE将先前的知识存储在LMM线性层激活的协方差矩阵中，并通过将原始权重投影到矩阵的零空间来初始化适配器，定义一个最小化与先前知识干扰的微调方向，从而实现强大的保留。
### Conclusion
广泛的实验表明，无论是LLaVA-v1.5-7B、LLaVA-v1.5-13B，还是Qwen2.5-VL-7B，KORE都能实现优越的新知识注入性能，并有效减轻灾难性遗忘。
## 23. `cs.CL` - EternalMath: 随着人类数学发现而进化的前沿数学活基准 [PDF](https://arxiv.org/pdf/2601.01400), [HTML](https://arxiv.org/abs/2601.01400)
### Authors
Jicheng Ma,Guohua Wang,Xinhua Feng,Yiming Liu,Zhichao Hu,Yuhong Liu
### Background
当前对大规模语言模型（LLMs）在数学推理方面的评估主要依赖静态基准，这些基准要么来源于竞赛类型的问题，要么通过专家手工编纂，导致数学研究级别的覆盖范围有限，并且模型性能很快饱和。
### Innovation
本文提出了一种完全自动化的、基于定理的评估流水线，直接将最新的同行评议数学文献转化为可执行和可验证的推理任务。该流水线识别出建设性的或定量的结果，将其实例化为参数化问题模板，并通过基于执行的验证生成确定性解决方案，从而使评估具有可扩展性、可再现性和持续可更新性，无需大规模依赖专家手工编写。这种方法设计上支持时间可扩展性、内在正确性检查以及跨数学子领域的特定定制。
### Conclusion
应用该流水线产生了EternalMath评估套件，这是一种随即时研究论文而不断演化的评估套件。实验表明最先进的LLMs在数学推理方面存在显著差异，强调了评估方法需要与人类数学发现的步伐相匹配。
## 24. `cs.CL` - FIT to Forget: Robust Continual Unlearning for Large Language Models [PDF](https://arxiv.org/pdf/2601.21682), [HTML](https://arxiv.org/abs/2601.21682)
### Authors
Xiaoyu Xu,Minxin Du,Kun Fang,Yaxin Xiao,Zhicong Huang,Cheng Hong,Qingqing Ye,Haibo Hu
### Background
大语言模型（LLMs）虽然表现出色，但它们越来越多地面临删除记忆中的敏感隐私、受版权保护或有害内容的需求。现有的遗忘方法主要关注单次场景，而实际的删除请求是连续到达的。直接将这些方法应用于连续的请求会导致功能退化甚至灾难性遗忘。
### Innovation
我们提出了FIT，这是一种鲁棒的连续遗忘框架，可以在处理大量连续删除流请求的同时，抵抗灾难性遗忘并防止删除后的恢复。FIT通过冗余过滤、重要性感知自适应算法选择和目标层归因等三种协同机制稳定连续更新。
### Conclusion
广泛的实验表明，FIT在五个LLM（最多140亿参数）上一致地实现了最先进的遗忘效果和功能保留。即使在处理数百个连续的请求后，FIT依然能够保持下游（例如GSM8K、MMLU）的强劲性能，并展现出对抗重新学习和量化恢复攻击的更强韧性。
## 25. `cs.CL` - Leviathan：在语言模型中分离输入和输出表示 [PDF](https://arxiv.org/pdf/2601.22040), [HTML](https://arxiv.org/abs/2601.22040)
### Authors
Reza T. Batley,Sourav Saha
### Background
现代语言模型使用单一矩阵进行输入嵌入和输出投影。这将两种不同的目标——标记表示和词汇区分——耦合并存。Leviathan通过引入一个新的Transformer架构，不再使用输入嵌入矩阵，而是使用学习到的嵌入向量化（LEV），将标记索引映射为连续的嵌入向量，来解决这一问题。这种改进旨在分离输入和输出表示，并通过使用较少的参数提高语言模型的性能。
### Innovation
Leviathan的创新在于它采用了一种新的嵌入向量化方式（LEVIATHAN（学习到的嵌入向量化）），替代传统的输入嵌入矩阵，从而分离输入和输出表示。这种设计仅增加0.2%的参数量，并且在多种规模的模型（从200M到1.2B参数）中，始终能够提高语言模型的表现。特别是在大规模模型中，Leviathan不仅减少了验证困惑度9%，还用更少的训练示例达到了与传统模型相同的最终损失，并在这六个下游基准测试中取得了改进。
### Conclusion
通过频率分层分析可以发现，Leviathan的最大增益集中在罕见标记上，连续参数化使罕见标记的困惑度降低了81%，并在最频繁的标记上接近零。这表明Leviathan能够显著改善罕见标记的表示效果。尽管整体参数量增加了，但带来了更好的泛化能力和更强的下游任务性能，特别是在罕见词汇的表现上有显著提升。
## 26. `cs.LG` - 非远视前瞻性的积极特征获取之路梯策略梯度 [PDF](https://arxiv.org/pdf/2605.05511), [HTML](https://arxiv.org/abs/2605.05511)
### Authors
Linus Aronsson,Morteza Haghir Chehreghani
### Background
积极特征获取（AFA）考虑了特征获取成本高昂的预测问题，在这种问题中，学习器会根据每个实例主动决定获取哪些特征值，并决定何时停止和预测。AFA可以被形式化为部分可观测马尔可夫决策过程（POMDP），这为顺序决策提供了一个自然的视角。本文基于此方法提出了非远视前瞻性的路径梯度策略（NM-PPG），并通过连续放松获取过程来实现路径梯度，从而避免了标准评分函数策略梯度的高方差，同时允许端到端优化非远视的获取策略。
### Innovation
引入了一种连续放松的获取过程，以便在整个获取轨迹中实现路径梯度，从而避免了标准评分函数策略梯度的高方差。同时，提出了一个硬特征获取的前向传播方案，并连同相应的软放松进行反向传播，以更好地使训练与部署保持一致。优化还采用了熵正则化和分阶段温度硬化。实验证明，NM-PPG相比现有的最先进的AFA方法具有更好的性能。
### Conclusion
NM-PPG方法在合成和真实数据集上的实验证明了其相对于现有最先进的AFA基线的优越性能。
## 27. `cs.LG` - 能量生成建模：基于Lyapunov的能量匹配视角 [PDF](https://arxiv.org/pdf/2605.05530), [HTML](https://arxiv.org/abs/2605.05530)
### Authors
Yixuan Wang,Wenqian Xue,Warren E. Dixon
### Background
基于静态标量能量函数的生成模型构成了一个新兴范式，在这一范式中，单一的时间独立势通过其梯度场驱动样本生成，完全消除了时间条件的需求。这一范式通常将训练和采样阶段视为相互独立的过程。
### Innovation
研究统一了这一范式中的训练和采样阶段，将其纳入一个单一框架中：Wasserstein空间上的密度运输，被表述为以Kullback-Leibler（KL）散度作为拉普拉斯函数的非线性控制问题。此外，研究开发了两个分析结果：首先，由于拉普拉斯证书是渐近的，研究推导出了一个有限步骤的停止标准，并证明了在相同的能量景观上确定性梯度流的拉普拉斯证书不存在。其次，这种重新表述引入了非线性控制理论工具的应用场景，表明已训练的标量能量的加性组合保留了显式的吉布斯不变测度，并继承了闭环拉普拉斯证书。
### Conclusion
这一重新表述将静态标量能量生成模型与非线性控制理论的全工具箱进行了互联，为受约束生成提供了障碍函数，并为加速采样提供了收敛度量。合成分布的实验验证了理论预测。
## 28. `cs.LG` - 使用使用商用微波链路和扩散模型先验进行贝叶斯降雨场场重构? [PDF](https://arxiv.org/pdf/2605.05520), [HTML](https://arxiv.org/abs/2605.05520)
### Authors
Badr Moufad,Albina Ilina,Hai Victor Habi,Salem Lahlou,Yazid Janati,Hagit Messer,Eric Moulines
### Background
商用微波链(link,， CMLs)可以提供密集的空间覆盖率用于监测降雨，， 但它们产生的是一维集成测量值， 这地面水位重建的准确度提出了挑战。.现有的方法通常将CML简化为点突测量传感器，并 幡忽了雨滴与信号衰减之间的关联路径, 因此在异质性降雨量下表现较差。
### Innovation
本文将雨水场场重构看作一个贝叶斯逆问题问题，并 使用扩散模型(dMs)作为高质量的空间先验。与截尾高斯过程相比，扩散模型能够保留关键的水统计量。. 尰置降雨量估计作为贝叶斯逆问题的框架使得能够在广泛的分析方法如包括Plug-and-and Plug方法下Monte Carlo方法和复语言交交换方法中实现无需训练的后验采样。
### Conclusion
在合成和实际数据集上的的实验表明这种方法在基于CML的重建基线下提供了改进。
## 29. `cs.LG` - 面向自回归动力系统预测的可扩展一步生成建模 [PDF](https://arxiv.org/pdf/2605.05540), [HTML](https://arxiv.org/abs/2605.05540)
### Authors
Tianyue Yang,Xiao Xue
### Background
快速的高维物理动力学的代理建模需要超越短期误差的低错误率，实用模型需要在保持长期轨迹统计结构的前提下高效展开。现有的方法，如神经算子和滚动扩散及潜在生成代理，虽然能表示随机转换，但在湍流区域易漂移，或因为多步降噪、噪声进度设计或辅助压缩模型而增加复杂性。
### Innovation
提出了MeanFlow长期不变时空一致性自回归模型（MeLISA），这是一种基于像素空间MeanFlow的无潜在代理的自回归生成代理模型。MeLISA通过块状随机转换内核生成每个预报块，避免了推理时的潜在编码器和迭代稀释求解器。为了稳定长期展望，MeLISA结合了一个窗口一致性MeanFlow目标函数和一个时间增量一致性损失函数，从部分观测时间窗口中学习条件时空生成，并且针对时间相关结构进行约束。
### Conclusion
MeLISA在短期预报精度和长期统计指标方面优于神经算子基线，并且达到可以与神经算子相当或更快的推理速度。紧凑的3.7-5.7M参数变体已经表现出强大的参数效率，而DiT变体则为可扩展至150M参数建模提供了路径。总体来说，MeLISA在预报效率和长期统计准确性方面都得到了提升。
## 30. `cs.LG` - 自适应Q分块(AQC)用于离线到在线强化学习 [PDF](https://arxiv.org/pdf/2605.05544), [HTML](https://arxiv.org/abs/2605.05544)
### Authors
Nandiraju Gireesh,Yuanliang Ju,He Wang
### Background
现有的离线到在线强化学习方法使用固定的分块大小，这种方法在临近接触事件时需要短分块以实现反应性控制，在自由空间运动时则需要更长的分块以更好地分配信用。虽然可以训练多种分块大小的评估器并选择最适合的状态，但这种方式会导致性能下降，特别是在低价值状态下。问题根源在于折扣率不匹配导致的加权偏差。
### Innovation
提出了自适应Q分块(AQC)算法，该算法通过比较每个分块大小相对于每个时间范围基线的优势，并对其进行折扣因子归一化，消除了加权偏差，将有偏差的错误答案转化为未加偏的随机选择，并在存在显著信号时增强决定性。该方法还提供了自适应分块策略的优点的理论保证，并证明了其在对AWGEnv和Robomimic的离线和在线成功率方面优于固定分块大小的方法。
### Conclusion
通过AQC算法在OGBench和Robomimic上的实验证明，该方法提高了基于预测动作序列的大型VLAs模型的性能，在RoboCasa-GR1任务中的性能得到了显著提升，达成从前最先进的成功率。
## 31. `cs.LG` - 使用边际保持粒子引导在扩散模型中的多样化采样 [PDF](https://arxiv.org/pdf/2605.06553), [HTML](https://arxiv.org/abs/2605.06553)
### Authors
Gal Vinograd,Idan Achituve,Ethan Fetaya
### Background
研究旨在为扩散和流匹配模型提供一种指导机制，该机制在生成样本时促进多样性同时保持质量。背景研究指出，当前方法通常难以平衡多样性和质量，特别是在文本到图像生成等计算成本较高的情况下，感知嵌入可能增加计算负担。
### Innovation
创新点在于提出了EDDY（Exact-marginal Diversification via Divergence-free dYnamics）机制，利用福克-普朗克方程的对称性，通过粒子轨迹的漂移扰动来改变轨迹但保持边际分布的演化，通过基于核的反对称双对矩阵场来实现这一机制，最终使得分散的动态行为在颗粒层面上促进多样性，而不会损害每个颗粒的边际分布。此外，为了减少计算成本，提出了实用的近似方法。
### Conclusion
实验结果表明，与常见的基准方法相比，EDDY在保持强烈分布保真度的同时改善了多样性的表现。
## 32. `cs.LG` - 使用强化学习在不确定性下的遗传电路的顺序设计 [PDF](https://arxiv.org/pdf/2605.06552), [HTML](https://arxiv.org/abs/2605.06552)
### Authors
Michal Kobiela,Diego A. Oyarzún,Michael U. Gutmann
### Background
由于生物分子反应的固有随机性和实验条件的差异，生物系统的建设计划受到阻碍。先前的贝叶斯方法通过迭代的实验-推理-优化循环来解决不确定性问题，但这种方法通常需要在每次实验后进行昂贵的推理和优化步骤，导致时间延迟。
### Innovation
提出了一种基于强化学习的序贯框架，该框架结合了差分方程或马尔可夫跳跃过程的模拟器模型，适应未知实验条件并考虑到固有的随机性。与贝叶斯方法不同，该方法采用了一种预先训练在整个可能的不确定参数分布上的即置式方法，避免了设计周期中的显式参数推断步骤，从而实现基于观察的即时适应。
### Conclusion
在异源基因表达模型和振荡器电路模型上展示了该框架的有效性，证明了它能够高效处理分子噪声和跨实验室变异。
## 33. `cs.LG` - 使用TCGA-BRCA基因表达数据进行乳腺癌亚型分类时，特征维度比模型复杂性更重要 [PDF](https://arxiv.org/pdf/2605.06562), [HTML](https://arxiv.org/abs/2605.06562)
### Authors
Meena Al Hasani
### Background
准确地从基因表达数据中分类乳腺癌亚型对于疾病诊断和治疗选择至关重要。但是，此类数据集具有高维性和样本量有限的特点，这给机器学习模型带来了挑战。
### Innovation
本研究使用TCGA-BRCA基因表达数据评估了模型复杂性和特征选择对亚型分类性能的影响。通过调整高可变基因的数量（50至20,518），训练了逻辑回归、随机森林和SVM模型，并使用分层5折交叉验证和准确性和宏F1评分来评估性能。
### Conclusion
所有模型都达到了高的准确率，但宏F1分析揭示了亚型级别的性能差异。逻辑回归展示了最稳定和平衡的性能，包括对稀有类别的改进检测。随机森林在少数亚型上的表现不佳，尽管总体准确率较高，而SVM对特征维度敏感。这些发现强调了在高维生物分类任务中模型的简化、评估指标和特征选择的重要性。
## 34. `cs.LG` - Criticality and Saturation in Orthogonal Neural Networks [PDF](https://arxiv.org/pdf/2605.06563), [HTML](https://arxiv.org/abs/2605.06563)
### Authors
Max Guillen,Jan E. Gerken
### Background
长期以来，在很长一段时间内（It,text{It背景
### Innovation
研究展示了具有正交序列 ( power text{关于
### Conclusion
研究通过理论解释了带有正交初始化方法解析了含有正交权重初始化的有限宽度非线:
## 35. `cs.LG` - SNAPO: 使用可微模拟实现最优控制的平滑神经反向策略优化 [PDF](https://arxiv.org/pdf/2605.06570), [HTML](https://arxiv.org/abs/2605.06570)
### Authors
Dmitri Goloubentsev,Natalija Karpichina
### Background
许多实际问题需要在不确定性条件下进行顺序决策，比如何时从天然气储存中注入或提取气体，如何每月重新平衡养老金投资组合，以及什么温度剖面适合制药反应器链。动态规划可以精确解决小规模问题，但在状态维度增加时会出现指数级的扩展问题。黑盒强化学习能够处理高维状态，但训练速度较慢且无法生成敏感性分析。
### Innovation
本文介绍了SNAPO（平滑神经反向策略优化）框架，该框架将神经策略嵌入已知的可微分模拟器中，用平滑近似替换硬性约束条件，并通过单一反向传递计算出策略参数和所有输入的精确梯度。SNAPO在天然气存储、养老金基金资产负债管理、制药生产等方面展示出不同领域的应用，实现了快速生成各种敏感性分析，并证明所有敏感性均由训练策略过程中产生的同一反向传递计算得出，计算成本与一个反向传递的开销成正比。
### Conclusion
SNAPO框架能够高效地生成敏感性分析，适用于具有高维状态的复杂问题，并且只需要一次反向传递即可生成所有相关敏感性分析，大大节省了计算资源和时间。
## 36. `cs.LG` - 语音增强和分离的预测-生成漂移分解方法 [PDF](https://arxiv.org/pdf/2605.06189), [HTML](https://arxiv.org/abs/2605.06189)
### Authors
Julius Richter,Yoshiki Masuyama,Christoph Boeddeker,Takahiro Edo,Gordon Wichern,Jonathan Le Roux
### Background
本文提出了一种插件式框架，将预测方法与生成性语音先验相结合，以改进语音增强和分离。该方法建立在随机插值的基础上，利用其灵活性将预测建模与生成建模相结合。具体来说，它将插值动态分解为任务特定的漂移和随机去噪组件，允许预测估计直接集成到生成采样过程中。这种方法提供了一个结合强大的预训练预测器和生成模型表现力的数学基础框架。
### Innovation
所提方法通过训练仅使用干净语音的声音评分模型，获得一种不依赖于降级的先验知识，可以在任务间重用。在推断过程中，预测器提供一种确定性漂移，引导采样过程向任务一致的估计结果，而评分模型保留感知自然性。与先前的混合方法通常依赖于特定架构的条件和特定预测器或降级设置不同，SIPS 提供了一个统一的框架，可以在不同的预测器和加性降级任务之间泛化。
### Conclusion
该方法在语音增强和语音分离中均表现出色，使用最近的预测器SEMamba和FlexIO时，感知质量不断提高，对于分离而言，可实现高达1.0 NISQA的增益。
## 37. `cs.LG` - 驾驭熵悬崖：用于自回归视觉生成的可变码本大小量化 [PDF](https://arxiv.org/pdf/2605.06207), [HTML](https://arxiv.org/abs/2605.06207)
### Authors
Bowen Zheng,Weijian Luo,Guang Yang,Colin Zhang,Tianyang Hu
### Background
大多数离散视觉分词器采用默认设计：序列中的每个位置共享相同的码本。研究人员尝试通过增加码本大小K来提升重构性能，但这种固定码本书设计存在信息论上的根本限制。观察发现，在训练集上位置条件熵迅速下降，导致序列位置之后的条件分布几乎确定，当K=16384的情况下，在ImageNet中仅在2个位置之后便出现这种现象，其余的254个位置变成了记忆问题，称为熵悬崖。语言则由于其自然结构，保持每个位置的有效熵远低于码本书容量。
### Innovation
提出了可变码本书大小量化（VCQ），其中码本书大小K_t沿序列单调增加，从K_min=2增加到K_max，而未改变损失函数、参数数量和AR训练流程。使用标准自回归Transformer和下一标记预测，VCQ基线版本将gFID减少到14.80，不使用额外训练技巧，还可扩展到684M自回归参数，实现gFID 1.71，显示出编码本容量分布和组织的重要性。
### Conclusion
结果表明，不只是码本书的总容量，其容量如何分布和组织更为关键。在最小码本书大小为2时，自然形成粗细程度不断增加的语义层次结构，仅前10个标记的线性探针在ImageNet上的top-1准确率达到43.8%，而使用均匀码本书的准确率仅为27.1%。
## 38. `cs.LG` - 通过可解释的深度学习在医学成像中结合视觉显著性和大型语言模型 [PDF](https://arxiv.org/pdf/2605.06197), [HTML](https://arxiv.org/abs/2605.06197)
### Authors
Paul Valery Nguezet,Elie Tagne Fute,Yusuf Brima,Benoit Martin Azanguezet,Marcellin Atemkeng
### Background
深度学习模型在医学成像中的临床应用受到其不透明性质的阻碍。本文提出了一种多模态解释性框架，旨在通过卷积神经网络（CNN）与临床行动依据之间的桥梁，来增强脑肿瘤分类的可解释性。该框架利用大型语言模型（LLMs）生成人类可理解的诊断叙述。
### Innovation
该框架分为三个阶段：首先，扩展九种CNN架构，利用双输出混合形式同时优化分类头和分割头，增强空间特征学习；其次，使用Grad-CAM、Grad-CAM++和ScoreCAM视觉显著性归因方法生成类别鉴别热图，并通过自适应分位数阈值管道精炼为二元肿瘤掩码；最后，这些掩码映射到哈佛-奥克芬脑皮层图谱，将像素级证据转化为命名神经解剖结构，并将提取的发现编码为结构化的JSON文件，以条件化三个LLMs生成放射学风格的诊断报告。
### Conclusion
在包含4,834张对比增强T1加权脑MRI图像（涵盖三种肿瘤类别）的数据集上进行评估，InceptionResNetV2获得了最佳分类性能，而Grad-CAM++提供了最佳的分割重叠率。在语言模型方面，Grok3在词汇多样性与连贯性方面领先，而LLaMA在可读性方面表现最佳。通过整合视觉、解剖和语言模态，该框架生成的技术合理且有意义可解释性解释，提高了基于人工智能的脑肿瘤诊断的透明度和临床问责制。
## 39. `cs.LG` - 当漏除 瘠 槨 修剪 对污染预测有什么帮助？保留水平诊断下的校准污染修剪 [PDF](https://arxiv.org/pdf/2605.06204), [HTML](https://arxiv.org/abs/2605.06204)
### Authors
Congye Wang
### Background
本文研究了校准预测的问题 中污 on on 殊污染的影响， on 甄通过修剪（ 甄 suspicion敏感点些可疑的校准点点 甄。， on.的响应，污染物水平。 on上 体amage在正 o on 盅标上 on on on的 上. 的覆盖k 下。 盄 修剪水平主要 在 污染水平 的依赖关系。。 研究的具体内容包括 on on 囼固定阈值修剪 on 下 污染标 on on 一维得分- 熔累积分布函数 on问题 问题上 位， 甄通过漏修剪 on on 异常分数的保持 on 以及在干净分 ons上的不敏感性 在 漏修荐修剪 on on 对有限样本-cfferencement系数模板制 提供对于独立审核的数值保证。
### Innovation
本文的创新点主要包括 架建立了污染修剪在污染标 on 于 混合系数和定 有限 on on 有限 有限 the有限 sample字样本上的确性的有限样本证书模板的 勇， 数进行保证情况下保留水平诊断 on yes 攄 栆准和 淨函数并 部分 by on on 上 污染保留比 滑比例 on 清洁水平的 的变化关系 on on 膳通过漏修剪保持异常分数的一维得分-累积分布函数评分机制 on 作为对 淘汰式在干净环境上的的方案 on.
### Conclusion
研究发现， on 修剪能够 on on 保留概率 on 异常分数上 不 清洁环境上 保持 不 中 膧在有限样本情况下提供的证书模板上 仍然能够提供数值保证 on independent auditing on 当同时未进行纯洁化处理 on trimmed contaminated 校准 on。 本研究为污染修剪的决策提供了理论依据 on 殕 唑在实际 on 有限样本条件下对 on 攄 阳 支撑了在独立复审上的数值保证。 wan确定 唄污染保留比例 concept 与 on 汇污染水平 on 的依赖关系 on. 獰이固化上了正验证 on 淋 清洁水平上 殿的重要性 兆剪有助于异常分 于 儿在分数定位 on 清洁环境上的改进 on 觬 但是对于固定混合系数在有限样本条件下提供的保证意义不大 仍需进一步探索 on.
## 40. `cs.LG` - 多模态深度生成模型在类别不平衡半监督学习中的应用 [PDF](https://arxiv.org/pdf/2605.06289), [HTML](https://arxiv.org/abs/2605.06289)
### Authors
Heegeon Yoon,Heeyoung Kim
### Background
在处理类别不平衡数据时，必须解决数据不平衡问题，因为这类数据训练的模型往往会偏向于多数类。在部分监督下，这一问题更为严重，因为伪标签通过不平衡的标注数据进行推断，会进一步传播偏差。现有的半监督模型通常假设输入数据是单模态的，但在多模态数据日益普及的情况下，利用互补的模态信息变得至关重要。
### Innovation
本文提出了一种针对类别不平衡的多模态深度生成模型，该模型采用跨模态共享的潜在变量、提出了专家乘积方法简化联合后验计算，并通过将先验、编码器和解码器中的典型高斯分布替换为更符合不平衡数据重尾分布的学生t分布，改进了模型。还提出了一个新的目标函数，使用$beta$-权力发散进行训练。
### Conclusion
在基准和真实世界数据集上的实验结果表明，本文提出的方法在泛化能力和不平衡类别分布下部分标注的多模态数据分类性能方面优于基线方法。
## 41. `cs.LG` - 面向资源受限设备的硬件感知神经特征提取 [PDF](https://arxiv.org/pdf/2605.04282), [HTML](https://arxiv.org/abs/2605.04282)
### Authors
Francesco Tosini,Simone Pedroni,Christian Veronesi,Pietro Bartoli,Andrea Giudici,Marco Paracchini,Marco Marcon,Diana Trojaniello
### Background
视觉SLAM是空间计算系统的核心组件，但由于内存、带宽和量化限制，将学习到的局部特征提取器部署到微控制器级硬件上仍然具有挑战性。尽管现代神经描述符提供了强大的鲁棒性，但它们的实际应用往往被系统级瓶颈所阻碍，这些瓶颈并未由基于浮点运算（FLOP）的效率度量捕捉到。
### Innovation
本文引入了Gideon，一种明确面向资源受限设备的硬件感知神经特征提取器。我们结合了从SuperPoint教师中获取的关系知识蒸馏和在严格的内存和操作约束下进行的可微神经架构搜索（DNAS）。与传统的设计管道不同，我们将量化稳定性与动态范围紧凑性视为首要目标。结果表明，用仿射层替换批量归一化等方式可显著提高INT8鲁棒性，特征维度直接影响量化稳定性。
### Conclusion
Gideon在STM32N6上实现了9.003毫秒的推理时间（111 fps），同时保持在1.5 MB的内存限制之下。有趣的是，INT8量化产生的性能退化可忽略不计，有时甚至能达到全精度性能。这些结果表明，可以通过总体硬件-算法协同设计，使学习特征提取与嵌入式硬件约束共存。
## 42. `cs.LG` - 镜像下降-上升算法对于大规模极小极大问题 [PDF](https://arxiv.org/pdf/2402.08106), [HTML](https://arxiv.org/abs/2402.08106)
### Authors
Razvan-Andrei Lascu,Mateusz B. Majka,Łukasz Szpruch
### Background
本文研究了在度量空间上使用镜像下降-上升（MDA）算法解决极小极大问题的两个变体：同时和交替更新。研究基于 payoff 函数相对于适当 Bregman 散度的凸凹性和相对光滑性，该散度通过度量空间上的平坦导数定义。在一定假设下，建立了非渐近收敛率，通过 Nikaidô-Isoda 误差测量到混合纳什均衡，并显示了针对同时 MDA 的 $text{O}(N^{-1/2})$ 速率和针对交替 MDA 的改进 $text{O}(N^{-2/3})$ 速率。
### Innovation
主要的技术贡献是无穷维对偶空间分析，将度量上的 Bregman 散度与有界连续函数空间上的对偶 Bregman 散度联系起来，允许我们控制交替更新产生的非对称交换项。本文的结果不仅推广了以往仅对二元目标函数的分析，还适用于度量空间上的非线性凸凹问题，从而为大规模极小极大优化中的 MDA 提供了一个统一的理论基础。
### Conclusion
本文给出了同时和交替 MDA 算法在有界连续函数空间上的非渐近收敛率，并通过 Nikaidô-Isoda 误差证明了这些算法的收敛性。这些结果普遍适用于非线性凸凹问题和度量空间，为 MDAS 提供了统一的理论框架。
## 43. `cs.LG` - 多臂bandits和强化学习中的统一分布性后悔框架 [PDF](https://arxiv.org/pdf/2605.05102), [HTML](https://arxiv.org/abs/2605.05102)
### Authors
Harin Lee,Min-hwan Oh
### Background
本文研究了在随机多臂bandits和阶段强化学习中的后悔分布，并提出了一种统一的框架来分析这一问题。研究通过概率保证的形式化后悔边界，该保证在整个置信水平范围内（$0<boldsymbol{text{delta}} text{ <= 1}$）都成立，从而全面地描述了后悔的分布情况。研究还引入了一种简单的UCBVI风格的算法，该算法通过探索性奖金$text{min}?left?frac{text{c}_{1,k}}{N}, frac{text{c}_{2,k}}{text{sqrt}(N))}?righttext{进行动作选择。研究推导了具有具体参数序列的一般化、独立于差值和依赖于差值的分布性后悔边界，这使得参数在期望性能、尾风险和实例相关行为之间的权衡有了一种方法论上的描述。特别是在最小化最糟糕情况和实例依赖的范畴中，我们的边界达到了最优的期望性能与分布性后悔的折衷。
### Innovation
本研究的创新之处在于，它提供了一种统一框架，可以同时考虑多臂bandits和阶段强化学习中的广泛范围的置信水平。进一步，研究通过一种简单的UCBVI风格的算法，使得在具体参数下实现了对运动选择和后悔边界的有效控制，特别是在期望性能和尾部风险之间达到了最优的权衡。
### Conclusion
本文展示了多臂bandits有A个动作和T个时间步长的组合下，分布性后悔边界是$text{O}(text{sqrt}(AT)text{log(1/delta}))$。这验证了Lattimore & Szepesvári (2020, 第17.1节) 的假设，首次提供了此类问题的实证支持。本研究加深了对后悔分布的理解，同时提供了一种在更广泛的不确定性背景下进行决策的方法论框架。
## 44. `cs.LG` - 基于离散余弦变换的去相关注意力机制用于视觉变换器 [PDF](https://arxiv.org/pdf/2405.13901), [HTML](https://arxiv.org/abs/2405.13901)
### Authors
Hongyi Pan,Emadeldeen Hamdan,Xin Zhu,Ahmet Enis Cetin,Ulas Bagci
### Background
自注意力机制对于Transformer架构的成功至关重要，但如何从随机初始化中学习查询、键和值的投影仍然是一个挑战。本文研究了Vision Transformers的效率和性能，并提出了一种利用离散余弦变换（DCT）的方法来增强注意力机制。
### Innovation
本文提出了两种互补的方法来利用DCT提高Vision Transformers的效率和性能。首先，通过一种简单的基于DCT的初始化策略，改善了自注意力的初始化问题；其次，提出了一种基于DCT的注意力压缩技术，该技术利用了频域的去相关特性，通过对高频分量进行截断，减少了查询、键和值投影的维度，同时保持了相近的性能。
### Conclusion
在Swin Transformer模型上进行的实验表明，所提出的方法在减少计算负担的同时，仍然保持了类似的性能。结构化的方法能够在CIFAR-10和ImageNet-1K基准测试中提高分类精度。
## 45. `cs.LG` - CatNet：使用SHAP特征重要性和Gaussian Mirrors控制LSTM的假发现率 [PDF](https://arxiv.org/pdf/2411.16666), [HTML](https://arxiv.org/abs/2411.16666)
### Authors
Jiaan Han,Junxiao Chen,Yanzhe Fu
### Background
研究中提到CatNet算法是在长短期记忆（LSTM）模型中有效控制假发现率（False Discovery Rate, FDR）并选择显著特征的算法。背景信息显示，在LSTM模型中进行FDR控制以及特征选择是研究的起点。作者注意到在非线性和时间相关特征中可能出现不稳定性问题，为此，研究提出了一种新的基于核的相关性度量方法来稳定特征选择过程。
### Innovation
CatNet的创新点在于：1) 使用SHAP值的导数来量化特征重要性；2) 通过Gaussian Mirror算法构建向量形式的镜像统计量来进行FDR控制；3) 引入了一种新的基于核的独立性度量方法，以避免特征间的非线性和时间相关性带来的不稳定问题；4) 研究表明，CatNet在不同模型设置及仿真与真实数据集上表现出稳健性，能有效减少过拟合并提高模型的可解释性。
### Conclusion
研究表明，CatNet算法不仅能够有效控制FDR和选择显著特征，还能稳健应用在不同的LSTM模型中。通过引入SHAP用于FDR控制算法中的特征重要性评估和改进Gaussian Mirror框架，该方法可自然扩展到其他时间序列或序列深度学习模型中。
## 46. `cs.LG` - LLM 纫trained then deployed into a world that never s奔跑在永不停歇的变化中：， 周围的外部环境会补偿这一变化， 但这些系统更倾向于显式地管理而不是隐含适应。 生物系统通过耦合的多尺度动态关联来更好地处理即时可用的信息和 让其余的慢慢淡化。这表明同一种原理可以用来进行记忆重构和知识更新。 [PDF](https://arxiv.org/pdf/2605.05097), [HTML](https://arxiv.org/abs/2605.05097)
### Authors
Andreas Pattichis,Constantine Dovrolis
### Background
大型语言模型（LLMs) 舞台在一种持续不断地变化中，这些模型在处理新的输入时不适应于 依靠基础设施的补偿。 耒而不显性地 自管理这些变化， 但在生物系统屇中， 通过采用多的耦合多尺度记忆动态学说 绿识信息的关联，系统知识的重新组织形成了更新机制。 这些生物系统层如何采用多可以处理即时可用信息并让其余的信息慢慢淡出。 返映了一种原理可以应用于LLMs进行记忆重构和知识更新。
### Innovation
该研究提出了通过多以一种耦合多时间尺度记忆动态机制来处理相关信息和让其余的信息慢慢淡化， 的观点。 类比一种生物原理可用这可以在LLMs的背景下进行了研究和设计出了了一种新的处理机制。 这种机制可以更加高效地管理信息来源并促进知识更新。
### Conclusion
这项研究揭示了一种新的处理机制通过使用耦合的多时间尺度记忆动态学体来 在 瓍识信息如何关联并 在LLMs系统屻中进行知识更新和。 这一机制通过处理即时可用信息来加强记忆的巩固同时让剩余的慢慢淡化
