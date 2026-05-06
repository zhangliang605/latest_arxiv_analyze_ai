# 20260506
[![Subscribe_Visitors](https://visitor-badge.laobi.icu/badge?page_id=nituchao.latest_arxiv_analyze_ai_rss)](https://github.com/nituchao/latest_arxiv_analyze_ai)

## 1. `cs.AI` - AI工作流程架构中透明效应治理：语义保存、表意最小性和可判定边界 [PDF](https://arxiv.org/pdf/2605.01030), [HTML](https://arxiv.org/abs/2605.01030)
### Authors
Alan L. McCann
### Background
该研究背景在于，现有的AI工作流程架构中，如何在不降低内部计算表达性的前提下，实现结构治理。研究者使用Rocq 8.19中的交互树来定义一个治理操作符G，用于调控所有产生效应的指令，包括内存访问、外部调用以及语言模型查询。通过正式验证的方法，证明了治理操作符G可以在不影响程序内部计算表达性的前提下，实现对效应级治理。
### Innovation
提出了一个结构性指导的AI工作流程架构的机器检查正式验证，证明了效应级治理可以实施而不会减少内部计算表达性。进一步定义并验证了七个关键的理论属性，这些属性不仅展示了治理操作符G的新颖性，还证明了治理和计算表达性是正交维度，分别受限于效应边界和语义透明性。
### Conclusion
研究结果表明，治理与计算表达性是正交的维度：治理限制了程序的效果边界，同时保持了对内部计算表达性的语义透明性。通过系列验证属性，研究指明了治理操作在保持语义不变的同时，最小化了原始功能需求，同时也提供了结构治理严格覆盖内容级筛选的机制。
## 2. `cs.AI` - 2026智能制造领域的人工智能和机器学习路线图 [PDF](https://arxiv.org/pdf/2605.00839), [HTML](https://arxiv.org/abs/2605.00839)
### Authors
Jay Lee,Hanqi Su,Marco Macchi,Adalberto Polenghi,Wei Wu,Zhiheng Zhao,George Q.Huang,Kiva Allgood,Devendra Jain,Benedikt Gieger,Vibhor Pandhare,Soumyabrata Bhattacharjee,Ram Mohril,Lingbao Kong,Qiyuan Wang,Xinlan Tang,Sungjong Kim,Chan Hee Park,Byeng D. Youn,Guo Dong Goh,Xi Huang,Wai Yee Yeong,Yung C Shin,He Zhang,Zitong Wang,Fei Tao,Jagjit Singh Srai,Satyandra K. Gupta,Byung Gun Joung,Albin John,John W. Sutherland,Sang Won Lee,Olga Fink,Vinay Sharma,Faez Ahmed,Wei Chen,Mark Fuge,Arild Waaler,Martin G. Skjæveland,Dimitris Kyritsis,Wei Chen,VispiNevile Karkaria,Yi-Ping Chen,Ying-Kuan Tsai,Joseph Cohen,Xun Huan,Jing Lin,Liangwei Zhang,Gregory W. Vogl,Aaron W. Cornelius,Xiaodong Jia,Dai-Yan Ji,Takanobu Minami,Ruoxin Wang
### Background
人工智能（AI）和机器学习（ML）的发展正在重新塑造智能制造，通过提供在工业价值链中提高效率、增强适应性和赋予自主的新能力。然而，AI和ML在工业环境中的部署仍然面临复杂的大数据、有效的数据管理、与其他异构传感和控制系统集成以及在高风险工业环境中的透明、可解释和可靠操作等方面的关键挑战。
### Innovation
路线图整理了AI和ML在智能制造领域的基础、应用和新兴方向，并具体探讨了物理带入AI、生成型AI、语义AI、先进的数字孪生、可解释AI、RAMS（可靠性、可维护性、支持性和安全性）、数据导向的测量、LLMs（大型语言模型）和复杂制造系统的基础模型等非传统ML方法，探索了新的前沿。
### Conclusion
该路线图指出了各个领域的机遇和剩余障碍，并明确了推进方法、集成策略和工业应用所需的进展。它旨在为研究人员、工程师和实践者提供指导，加速创新，使学术和工业优先事项保持一致，并确保AI驱动的智能制造为未来的制造业生态圈带来可靠的、可持续的和可扩展的影响。
## 3. `cs.AI` - 一种针对激光粉末床融合可解释缺陷分析与缓解指导的知识驱动大语言模型决策支持系统 [PDF](https://arxiv.org/pdf/2605.01100), [HTML](https://arxiv.org/abs/2605.01100)
### Authors
Basit Mahmud Shahriar,Md Habibor Rahman
### Background
本文介绍了一个结合结构化缺陷知识与基于LLM的推理的知识驱动决策支持系统，用于制造中的可解释缺陷诊断和缓解指导，以LPBF（激光粉末床融合）作为一个代表性的、关键安全案例研究。知识库包含27种已知LPBF缺陷类型及其分层类别和因果关系，支持模糊自然语言查询，通过文献支持的缺陷解释和基于编码工艺知识的故障原因和缓解策略指导。此外，基于基础模型的多模态图像评估模块可通过语义对齐得分实现代表性的微观缺陷图像的描述导向解释。
### Innovation
提出了一个集成本体的知识驱动LLM支持系统，用于LPBF缺陷分析和缓解指导。该系统支持模糊自然语言查询，文献支持的缺陷解释，以及基于编码工艺知识的故障原因和缓解策略指导。基于基础模型的多模态图像评估模块实现了描述导向的解释机制，通过对一般视觉语言模型的定性比较、消融研究和复评估者一致性分析，证明了全集成配置在评测集上表现出色，取得了0.808的宏平均F1分数，同时通过Cohen's kappa分析发现模型输出与文献参考标签之间有实质性的共识。
### Conclusion
研究发现，基于本体的知识表示可以提高LLM辅助LPBF缺陷分析的一致性、可解释性和实用性。该方法在LPBF缺陷分析与缓解指导方面取得了显著进展，为后续类似工业领域的应用提供了新的参考框架。
## 4. `cs.AI` - 治理执行的代数语义：单oidal范畴、效果代数和一致边界 [PDF](https://arxiv.org/pdf/2605.01032), [HTML](https://arxiv.org/abs/2605.01032)
### Authors
Alan L. McCann
### Background
本文探讨了一种治理执行的代数语义方法，其中治理是形式化的、组合的，并且与表达能力一致。该框架基于交互树和参数化余归纳法实现，并通过32个Rocq模块（约12,000行，454条定理，0个已接受）构建。
### Innovation
提出了一个三公理的GovernanceAlgebra记录（安全、透明、适当性），确定了对称单oidal范畴，验证了五角形、三角形和六角形一致性，并且每个张量组合都保留了治理。还定义了包含治理的效果系统，确保只有治理保留的手处理器可以在安全片段中构建；在空能力集中的程序可证明只会发出观察指令。引入了能力和指数组合，将程序与机器检查的能力上限捆绑在一起，并证明了双重保证定理，即在所有组合操作下，within_caps和gov_safe同时成立。
### Conclusion
我们的研究成果表明，通过四个基本同态构造器表达的每个程序在解释下都是受治理的，每个受治理的程序都可以通过该构造器的表达来形成；在治理内的图灵完备性得以保留；未中介的输入输出被排除在治理片段之外；治理被建模为安全的余归纳式发散；治理代数具有参数性：任何实例化三个公理的系统都会继承所有派生属性，包括收敛性、组合封闭性和目标保存性。提取的OCaml作为BEAM运行时的NIF运行，基于验证行为等价的属性测试（70,000+随机输入，零冲突）验证了规范和运行时解释器之间的一致性。
## 5. `cs.AI` - 基于修复语义的不一致知识库的ABox abduction [PDF](https://arxiv.org/pdf/2605.01341), [HTML](https://arxiv.org/abs/2605.01341)
### Authors
Anselm Haak,Patrick Koopmann,Yasir Mahmood,Anni-Yasmin Turhan
### Background
在给定一个知识库（KB）且存在一个非蕴含事实的背景下，ABox abduction问题旨在寻找可能扩展KB使其蕴含该事实的方案。这一问题在诊断、解释性和修复等一系列应用中有广泛的应用。对于一致性的KB和经典语义，ABox abduction问题已有深入研究，但面对不一致的KB（可能由于错误数据导致）的情况，关于ABox abduction问题的研究还相对不足。
### Innovation
本文定义了适用于不一致KB场景下的合适ABox abduction概念，并提出了引导abduction产生“有用”假设的标准。为了在不一致性存在的情况下恢复有效的推理，本文采用了成熟的修复语义。本文还提供了在修复语义下对轻量描述逻辑DL-Lite和EL_bot的不同ABox abduction问题变种的复杂性综述。
### Conclusion
本文分析了在不一致的KB中适用修复语义下的ABox abduction问题，并揭示了不同描述逻辑下的变异问题复杂性。
## 6. `cs.AI` - VUDA: 突破CUDA和Vulkan隔离以在同一GPU上实现计算和图形的空间共享 [PDF](https://arxiv.org/pdf/2605.01352), [HTML](https://arxiv.org/abs/2605.01352)
### Authors
Bin Xu,Pengfei Hu,Wenxin Zheng,Jinyu Gu,Haibo Chen
### Background
GPU基的仿真环境用于嵌入式AI结合了CUDA物理仿真和Vulkan的照真渲染。然而，由于CUDA和Vulkan创建了分开的GPU上下文，导致计算和图形被限制在互不相关的时序中运行，导致GPU的利用率下降。这种执行隔离使得现有技术难以有效管理CUDA和Vulkan的工作负载以实现空间上的并行共享。
### Innovation
该论文提出了VUDA系统，打破了CUDA和Vulkan之间的执行隔离，使得计算和图形工作负载可以在同一GPU上实现空间上的并行共享。VUDA通过重定向通道到Vulkan的调度领域并接合页面表来统一地址空间来实现共享，消除了关键路径上的所有数据拷贝。
### Conclusion
实验表明，VUDA在代表性的嵌入式AI工作负载上能够提供高达85%的吞吐量提升，并提高GPU利用率，减少端到端延迟。
## 7. `cs.AI` - 基于模型的主动成本生成方法，用于利用有限违规数据离线学习安全策略 [PDF](https://arxiv.org/pdf/2605.01356), [HTML](https://arxiv.org/abs/2605.01356)
### Authors
Ruiqi Xue,Lei Yuan,Kainuo Cheng,Jing-Wen Yang,Yang Yu
### Background
在高风险场景下，从大量不安全样本中学习成本价值函数的传统方法利用风险试验来定义安全边界并惩罚违规行为是不切实际的，这导致数据集中缺少不安全样本。现有方法通常忽视了安全但不现实的状态——即目前满足约束但在几步内肯定会违规的状态。这可能导致部署失败。
### Innovation
该研究提出了PROCO模型，这是一种基于模型的离线安全强化学习框架，适用于几乎不含有违规数据的场景。PROCO通过线上数据学习动力模型，并利用大型语言模型（LLMs）的自然语言知识构建保守的成本函数，即使未观察到违规行为也能估计风险。PROCO使用成本函数和学习到的动力模型进行基于模型的回放，以合成多样化的反事实不安全样本，支持可靠的可行性识别和可行性引导的策略学习。
### Conclusion
在仅有安全或极低风险的训练数据的Safety-Gymnasium任务下，PROCO与各种离线安全强化学习算法无缝集成，并展示了比原有方法和行为克隆基线更低的约束违规率和更好的安全性能。
## 8. `cs.AI` - Vessels的稀疏表示学习 [PDF](https://arxiv.org/pdf/2605.01382), [HTML](https://arxiv.org/abs/2605.01382)
### Authors
Chinmay Prabhakar,Bastian Wittmann,Paul Büschl,Hongwei Bran Li,Bjoern Menze,Suprosanna Shit
### Background
分析人类血管及其类似管道结构，如气管，对于疾病诊断和治疗至关重要。当前的方法往往依赖于小的子区域或简化的树状结构，使得在临床分辨率下对整个器官级网络进行全面分析计算上具有挑战性。
### Innovation
提出了一种高效的编码解码模型VAEsselSparse，用于在亚毫米分辨率下获取整个器官级血管网络的意义丰富但紧凑的表示。它通过稀疏卷积和注意力机制利用3D血管结构的固有的稀疏性，实现了8x8x8的大量空间压缩率，优于密集对应物和先前的方法。
### Conclusion
VAEsselSparse产生的潜空间保留了临床相关的判别特征，便于分类任务，如动脉瘤/狭窄或Willis环的亚变体。此外，VAEsselSparse的紧凑潜空间用于通过生成模型学习管状结构的先验知识，从而生成逼真的血管结构。
## 9. `cs.AI` - 在软件设计中使用LLMs：来自GitHub和从业者调查的实证研究 [PDF](https://arxiv.org/pdf/2605.01392), [HTML](https://arxiv.org/abs/2605.01392)
### Authors
Yifei Wang,Ruiyin Li,Peng Liang,Yangxiao Cai,Zengyang Li,Mojtaba Shahin,Arif Ali Khan,Qiong Feng
### Background
近年来，大型语言模型（LLMs）在软件工程任务方面的潜力得到了广泛认可，包括软件设计领域。然而，该领域仍然高度依赖于专门知识和判断。尽管如此，关于LLMs如何应用于软件设计的研究依然很少。人们对于这种应用的潜在好处和缺点了解不足。因此，本文通过实证研究探讨开发人员如何在软件设计中利用LLMs。
### Innovation
本文采用混合方法研究，结合了对GitHub上291个开发人员与ChatGPT对话的开采研究，以及对65名软件从业者进行的调查。研究发现了ChatGPT支持的九类设计任务，开发人员主要利用ChatGPT进行知识获取和设计相关的代码生成，大多数任务处于详细设计级别。研究还发现利用LLMs在软件设计中的七大好处和六大限制。
### Conclusion
研究从开源和实践者的视角提供了当前LLMs使用在软件设计中的证据基础描述，揭示了感知利益和限制之间的紧张关系，为未来的研究和集成LLMs到软件设计实践的有效技术与工具的发展奠定了基础。
## 10. `cs.AI` - 探究交互式教育推荐系统中不同用户控制水平的影响 [PDF](https://arxiv.org/pdf/2605.01400), [HTML](https://arxiv.org/abs/2605.01400)
### Authors
Qurat Ul Ain,Mohamed Amine Chatti,William Kana Tsoplefack,Rawaa Alatrash,Shoeb Joarder
### Background
教育推荐系统（ERSs）在提升教育成果和个人化学习体验方面变得越来越重要。它们通过为学习者提供个性化资源和活动推荐来满足个体学习需求。尽管用户控制通常被认为能提高用户体验，但不同水平的用户控制对ERSs效果的影响尚未得到充分研究。
### Innovation
本研究在MOOC平台CourseMapper中设计并评估了一个交互式的ERS，研究者允许学习者与系统的输入（即用户配置文件）、过程（即推荐算法）和输出（即推荐结果）进行互动。研究通过一项包含184名用户的组间实验，探讨了不同水平的用户控制如何影响用户对推荐目标（如感知的控制、透明度、信任、满意度和感知质量）的不同评价。
### Conclusion
研究结果表明，允许用户构建和完善配置文件就足以促进对ERS的积极感知，而额外的控制选项主要是增强这些印象。感知的控制是唯一对不同水平用户控制水平提供积极感知影响的目标，输入控制的影响最为显著。此外，不同水平的控制影响透明度、信任、满意度和感知质量的方式各有不同但相互关联。总之，结果证实用户控制积极塑造了透明度、信任、满意度和感知质量，但影响的程度有所不同。
## 11. `cs.AI` - AI Expert Twin: 捕捉专家认知以实现以人为中心、基于实践的学习 [PDF](https://arxiv.org/pdf/2605.01401), [HTML](https://arxiv.org/abs/2605.01401)
### Authors
Annie Yuan,Xiaohua Chen,Kalina Yacef,Judy Kay
### Background
专家实践中的隐性知识难以捕捉、形式化和拓展。尽管AI驱动的教育系统已经在个性化、学习者建模、情感支持和自我调节学习方面取得了进展，但在工艺导向领域中，它们很少模拟专家实践中的隐性推理和情境敏感判断。
### Innovation
该论文提出了AI专家孪生（AI Expert Twin）的认知为中心框架。该框架以结构化、可计算的方式表示工艺实践中的过程动作、语义概念和决策过程，并考虑了价值观倾向、权衡和不确定性对实践中国家判断的影响。通过将专家启发式嵌入AI中，同时保持透明性和学习者的主动性，AI专家孪生为可扩展的、基于实践的学习提供了新的路径，并激发了进一步研究在教育中的人文中心、伦理化AI应用。
### Conclusion
在文化遗产研讨会中的案例研究证明了该方法在真实世界情境中的可行性。该框架旨在跨领域（如职业教育和创意产业）可转移性。AI专家孪生通过实现可扩展的、实践导向的学习，提出了向基于AI的教育系统中整合专家认知的新途径，并邀请进一步研究以实现伦理化、以人为本的AI应用。
## 12. `cs.AI` - Medmarks: 一种全面的开源大规模语言模型医疗任务基准套件 [PDF](https://arxiv.org/pdf/2605.01417), [HTML](https://arxiv.org/abs/2605.01417)
### Authors
Benjamin Warner,Ratna Sagari Grandhi,Max Kieffer,Aymane Ouraq,Saurav Panigrahi,Geetu Ambwani,Kunal Bagga,Nikhil Khandekar,Arya Hariharan,Nishant Mishra,Manish Ram,Shamus Sim Zi Yang,Ahmed Essouaied,Adepoju Jeremiah Moyondafoluwa,Robert Scholz,Bofeng Huang,Molly Beavers,Srishti Gureja,Anish Mahishi,Sameed Khan,Maxime Griot,Hunar Batra,Jean-Benoit Delbrouck,Siddhant Bharadwaj,Ronald Clark,Ashish Vashist,Anas Zafar,Leema Krishna Murali,Harsh Deshpande,Ameen Patel,William Brown,Johannes Hagemann,Connor Lane,Paul Steven Scotti,Tanishq Mathew Abraham
### Background
评估大规模语言模型（LLMs）在医疗应用中的表现仍然具有挑战性，主要由于基准测试饱和、数据访问受限以及相关任务覆盖率不足。现有的套件或已经饱和，或依赖于受限的数据集，或缺乏全面的模型覆盖。
### Innovation
Medmarks 提供了一个全面开放源代码的评估套件，包含30个基准，涵盖问题回答、信息提取、医疗计算和开放型临床推理。采用可验证的评估标准和LLM作为裁判进行系统性评估，结果显示前沿推理模型（Gemini 3 Pro Preview, GPT-5.1 & GPT-5.2）在所有基准测试中表现出最佳性能，前沿的专有模型比开源模型在标记效率上更为出色，医学Fine-tuned模型优于通用模型，而且模型对于答案顺序偏见（尤其对于小型模型和Grok 4）较为敏感。部分评估（Medmarks-T）可以被直接用作强化学习环境，用于进一步训练LLMs以提高其医疗推理能力。
### Conclusion
Medmarks展示了最新的前沿推理模型在医疗推理领域中的优越性能，并揭示了模型在答案顺序上的潜在偏见，同时提供了一种新的方法来通过强化学习进一步提升LLM在医疗领域的应用。
## 13. `cs.AI` - HepScript: 一种用于高能物理中人-人工智能协作数据分析工作流的双用途领域特定语言 [PDF](https://arxiv.org/pdf/2605.01423), [HTML](https://arxiv.org/abs/2605.01423)
### Authors
Junkun Jiao,Tong Liu,Ke Li,Weimin Song,Yipu Liao,Bolun Zhang,Beijiang Liu,Chang-Zheng Yuan,Yue Sun
### Background
高能物理（HEP）中的数据规模迅速增长，推动了对更高分析效率的需求。尽管大型语言模型（LLMs）提供了通过自主性人工智能实现自动化的途径，但它们在处理需要深厚学科知识且高度融合实验特定代码库的复杂科学工作流程方面存在局限。为了解决这一问题，本研究介绍了以HepScript为核心的解决方案。HepScript是一种用于HEP数据分析工作的双用途领域特定语言（DSL），作为共享的形式接口，它可以将HEP分析逻辑抽象为既有直观性又易由AI生成的受限语法。
### Innovation
HepScript通过抽象复杂的软件栈，将高层次的分析意图转化为预生产级别的底层代码，使得人类编写的代码减少了93%。HepScript核心在于其受限的语法定义了可管理的动作空间，允许AI代理直接从已发表文献中自动生成核心分析阶段可执行的规格说明，成功率达到了95%。这项工作展示了通过正式指定DSL实现人-人工智能协作系统的可扩展路径，DSL充当了人类专业知识、人工智能自动化与生产环境之间的明确翻译层，解决了先前难以解决的自动化问题。
### Conclusion
本研究展示了HepScript作为人类专业知识、人工智能自动化与生产环境之间的翻译层的应用，使得高能物理数据分析任务中的自动化问题变得可解。这种方法为未来的高效数据分析提供了新的途径。
## 14. `cs.AI` - 结构性因果决策过程的设计与组合 [PDF](https://arxiv.org/pdf/2605.02681), [HTML](https://arxiv.org/abs/2605.02681)
### Authors
Sebastian Benthall,Alan Lujan
### Background
本文提出了两类新的决策主体因果模型，旨在通过建模计算系统的经济特性来满足需求。这类系统由多个子系统组成，表现出内部的认知资源和价值折扣限度。
### Innovation
1. 开发了扩展自结构性因果影响模型（SCIMs）的结构性因果决策模型（SCDMs），能够明确展示模型变量间的因果关系和代理决策的收益，并允许存在未给定概率分布或结构方程的初始变量。2. 基于SCDMs定义了具有折现变量的结构性因果决策过程（SCDPs），这些过程拥有有用的组合性质。3. SCDPs比部分可观测马尔可夫决策过程（POMDPs）更具表现力，因为它们不对理性的信念形成做出假设，能够内生地建模记忆形成过程，并可用于建模动态环境下的资源合理代理。
### Conclusion
SCDPs是一种适用于数字经济政策模拟、信息系统的机制设计以及网络基础设施数字孪生建模的有效框架。
## 15. `cs.AI` - 从少量交互学习对称神经增强物体动力学 [PDF](https://arxiv.org/pdf/2605.02699), [HTML](https://arxiv.org/abs/2605.02699)
### Authors
Sergio Orozco,Tushar Kusnur,Brandon May,George Konidaris,Laura Herlant
### Background
通过数据高效学习机器人操作中的物体动力学模型仍然是一个挑战，尤其是在处理可变形物体时。一种流行的方法是将物体建模为3D粒子集合，并使用图神经网络学习它们的运动。然而，这种方法在长时间范围内可能无法保持物理可行性，并可能需要大量交互数据进行学习。
### Innovation
提出了一种新颖的方法PIEGraph，它结合了分析物理模型和数据驱动模型，利用有限的实际交互数据捕获刚体和可变形物体的动力学。PIEGraph由两个组件组成：1）一个基于粒子的物理启发式分析模型（实现为弹簧-质量系统），用于确保物理可行的运动；2）一种等变图神经网络，具有新颖的动作表示，利用粒子间交互的对称性引导分析模型。
### Conclusion
我们在模拟和机器人硬件上评估了PIEGraph，用于处理绳索、布料、充气玩具和刚体的重定位和重新定位任务。实验结果表明，该方法能够在手动和腿部机器人上实现准确的动力学预测，并且在下游机器人操作计划中表现出色，优于最先进的基线方法。
## 16. `cs.AI` - mdok-style在SemEval-2026任务10中的应用：针对阴谋论检测调整大模型 [PDF](https://arxiv.org/pdf/2605.02712), [HTML](https://arxiv.org/abs/2605.02712)
### Authors
Dominik Macko
### Background
SemEval-2026 任务10专注于阴谋论检测。具体目标是识别 Reddit 评论是否表达了阴谋论信念。背景信息显示，由于训练数据量相对较小，研究人员需要创新的方法来应对这一挑战。
### Innovation
提交的 mdok-style 系统采用了数据增强和自我训练（以应对较小的训练数据量）的方法，对 Qwen3-32B 模型进行微调，用于二分类文本任务。这种方法表明源自于机器生成文本检测的方法也可以应用于阴谋论检测。
### Conclusion
提交的系统表现非常出色，排名在第85百分位（在52个提交中排名第8）。结果表明，机器生成文本检测的方法可以有效地应用于阴谋论检测领域。
## 17. `cs.AI` - 从上下文到技能：语言模型能否灵巧地从上下文中学习？ [PDF](https://arxiv.org/pdf/2604.27660), [HTML](https://arxiv.org/abs/2604.27660)
### Authors
Shuzheng Si,Haozhe Zhao,Yu Lei,Qingyi Wang,Dingwei Chen,Zhitong Wang,Zhenhailong Wang,Kangyang Luo,Zheng Wang,Gang Chen,Fanchao Qi,Minjia Zhang,Maosong Sun
### Background
许多现实世界的任务要求语言模型在超出其参数知识复杂背景中进行推理。这就需要一种上下文学习的方式，让语言模型直接从给定的上下文中学习相关知识。一个直观的解决方案是在推理时通过技能增强：将上下文中的规则和程序提炼成自然语言技能。但这种方案在上下文学习场景下面临两个挑战：手工标注长期且技术密集的技能代价高昂，而且缺乏外部反馈用于自动化技能构建。
### Innovation
本文提出了一个自发展的框架Ctx2Skill，它能自主发现、提炼和选择与上下文相关的具体技能，无需人类监督或外部反馈。该框架的核心包括一个多代理自博弈循环，其中包含一个挑战者生成探针任务和标准，一个尝试用不断进化技能集来解题的推理者，以及一个提供二元反馈的中立裁判。挑战者和推理者都通过累计技能来进化：专注于提议者和生成器代理分析失败案例并将之转换为双方的目标技能更新，从而实现自动化技能的发现和改进。为了防止逐渐极端的任务生成和过度专业化技能积累导致的对抗性坍塌，本文引入了一种跨时间重演机制，该机制能识别出在推理者方面实现最佳代表案例综合评估的技能集，从而确保技能演化的鲁棒性和广泛性。
### Conclusion
所得到的技能可以嵌入到任何语言模型中，以获得更好的上下文学习能力。在CL-bench上的四个上下文学习任务上进行评估，Ctx2Skill在多种骨干模型上都一致提高了解决问题的能力。
## 18. `cs.AI` - 无监督学习鲁棒频谱形状匹配 [PDF](https://arxiv.org/pdf/2304.14419), [HTML](https://arxiv.org/abs/2304.14419)
### Authors
Dongliang Cao,Paul Roetzer,Florian Bernard
### Background
现有的基于深层功能映射的方法主要集中在预测优化的功能映射，并依赖于现成的后处理步骤以在推理过程中获取准确的点间映射。然而，这种两阶段过程通常会导致性能不佳。本研究根据最近有关功能映射与点间映射关系的见解，提出了一种新的无监督损失来耦合功能映射和点间映射，从而直接进行点间映射预测，而不依赖于任何后处理。
### Innovation
提出了一种全新的基于学习的方法，该方法基于深层功能映射，并能够以完全无监督的方式进行训练。该方法能够直接生成点间映射，而无需任何后处理。该方法不仅适用于近等距形状，还适用于更具挑战性的非等距形状、部分形状，以及具有不同细分或拓扑噪声的形状。
### Conclusion
该方法在总共九个不同的数据集上进行了广泛评估，并显示出与先前的最先进的方法相比的显著性能改进，即使与最近的有监督方法相比也是如此。代码已在指定的网址提供。
## 19. `cs.AI` - 向着自主运行时恢复 [PDF](https://arxiv.org/pdf/2408.01055), [HTML](https://arxiv.org/abs/2408.01055)
### Authors
Zhensu Sun,Haotian Zhu,Bowen Xu,Xiaoning Du,Li Li,David Lo
### Background
自愈系统一直是研究的重点，旨在使软件在无需人工干预的情况下从意外运行时错误中恢复过来。传统方法依赖预定义的启发式规则，如重用错误处理程序或回滚到检查点，但这些方法难以适应各种运行时错误的多样性。
### Innovation
利用大型语言模型（LLMs）的能力理解并生成代码和自然语言，我们提出了一种新的方法，通过实时生成特定运行时上下文（如错误消息和程序状态）定制的错误处理策略来动态生成错误处理代码。通过设计这样的框架Healer，并实验证明其能够以高成功率处理运行时错误。GPT-4在我们的测试中可以成功恢复72.8%的运行时错误，展示了LLMs在这方面的潜力。
### Conclusion
尽管取得了有希望的结果，但仍存在关于LLM生成代码的信任问题以及与其现有的系统集成的问题。我们提出了安全检查和Healer感知编程等潜在解决方案，以减轻风险并确保可靠运行。这项工作代表了自主运行时恢复的第一步，为更适应性强、抗风险性和自愈的软件系统铺平了道路。
## 20. `cs.AI` - 自动驾驶中的边缘案例检测：方法、挑战与未来方向 [PDF](https://arxiv.org/pdf/2410.08491), [HTML](https://arxiv.org/abs/2410.08491)
### Authors
Saeed Rahmani,Sabine Rieder,Erwin de Gelder,Marcel Sonntag,Jorge Lorente Mallada,Sytze Kalisvaart,Vahid Hashemi,Bart van Arem,Simeon C. Calvert
### Background
自动车辆有望提高交通安全和效率，但确保其在真实环境中的可靠性仍然具有挑战性，特别是由于罕见且不可预见的情况，即边缘案例。尽管存在多种边缘案例检测方法，但缺乏对此类技术的全面综述。作者通过提供边缘案例检测与评估方法的分层回顾和系统分类，填补了这一空白。
### Innovation
提出了一种分层次的分类和系统分类方法，该方法分为两个层次：首先按自动驾驶（AV）模块分类，包括感知和轨迹相关的子系统（涵盖预测、规划和控制）；其次，按指导这些技术的基础方法和理论分类。此外，还引入了“知识驱动”的方法，该方法通过利用专家见解和领域知识补充数据驱动方法，以识别训练数据集不存在的情况。最后，根据检测性能、实际部署和领域特定措施（如 crash 率、严重性分析）评估边缘案例检测技术。
### Conclusion
强调边缘案例检测的关键挑战，包括数据可用性和质量问题、验证和解释性限制、模拟与现实之间的差距和计算约束。该综述中的分层分类和方法评估技术为选择特定 AV 子系统的方法提供了模块化和针对性的测试框架，同时也支持实际测试，通过促进仿真中的场景生成和现实世界中的子系统验证来实现。
## 21. `cs.AI` - 短窗注意机制促进长期记忆 [PDF](https://arxiv.org/pdf/2509.24552), [HTML](https://arxiv.org/abs/2509.24552)
### Authors
Loïc Cabannes,Maximilian Beck,Gergely Szilvasy,Matthijs Douze,Maria Lomeli,Jade Copet,Pierre-Emmanuel Mazaré,Gabriel Synnaeve,Hervé Jégou
### Background
近期研究表明，结合局部滑动窗口注意力层和全局注意力层的混合架构优于各自单独使用的效果。然而，滑动窗口长度的影响以及局部层和全局层之间的互动尚未得到充分研究。
### Innovation
通过分析滑动窗口的短长期记忆交互，研究发现较大的滑动窗口反而损害了长上下文的表现。短窗注意力机制促使xLSTM长期记忆训练的提升，因为它无法依赖局部的软最大注意力机制来获取长上下文召回。通过交替使用短窗和全注意层的局部-全局架构，发现短窗层应保持较小以不阻碍长窗层的效果，而较小的滑动窗口甚至在短上下文任务中也会造成不良影响，可通过使用适度更大的滑动窗口获得信息来解决。因此，通过随机变化滑动窗口大小来训练混合架构，促使模型利用短期窗口和长期记忆，这种训练方式在短期和长期上下文问题上均表现出显著提升。
### Conclusion
通过随机变化滑动窗口大小促进混合架构的学习，显著提升了模型在短长上下文问题上的表现。
## 22. `cs.AI` - CoSpaDi: 通过校准引导的稀疏字典学习压缩LLMs [PDF](https://arxiv.org/pdf/2509.22075), [HTML](https://arxiv.org/abs/2509.22075)
### Authors
Denis Makhov,Dmitriy Shopkhoev,Magauiya Zhussip,Ammar Ali,Stamatios Lefkimmiatis
### Background
在训练大型语言模型（LLMs）之后，常用的技术是低秩权重近似，这种方法可以将每个权重矩阵的列表示为共享低维子空间中的表示，这样可以大大提高计算效率。然而，这种低秩分解方法在面对异构投影权重时可能导致过度严格的约束，并可能引起不必要的准确性损失。
### Innovation
提出了一种名为CoSpaDi（基于稀疏字典学习的压缩）的训练前框架，该框架替代了低秩分解，采用一种带有结构稀疏分解的方法，其中每个权重矩阵被表示为一个稠密字典与一列稀疏系数矩阵的乘积。这种方法能够提高模型的表达能力，同时在固定参数预算内优化。CoSpaDi 是通过校准引导的，在使用一个小型校准集优化因子分解时，主要目标是减少分层输出的函数重构误差而不是权重空间误差。此外，通过激活衍生的Gram正交化将数据感知的目标转化为一个标准的字典学习问题，并且支持分层压缩和跨层字典共享。
### Conclusion
在Llama和Qwen模型系列中，CoSpaDi 在20-40%的压缩比率下，不仅在准确性和压缩比方面优于基于SVD的方法，也优于强大的结构化剪枝基线方法。此外，这种结构稀疏性还能够实现稀疏-密集计算，并与稀疏系数的后训练量化集成。
## 23. `cs.AI` - BaldWhisper: 更快的 Whisper 通过头部裁剪和层合并 [PDF](https://arxiv.org/pdf/2510.08599), [HTML](https://arxiv.org/abs/2510.08599)
### Authors
Yaya Sy,Christophe Cerisara,Irina Illina
### Background
在资源稀缺的情况下修剪大型预训练变压器非常具有挑战性，因为通常需要大量重训练数据来恢复性能。例如，Distill-Whisper 通过40%的修剪和21,000小时的语音数据重训练 Whisper，这在大多数语言环境下是不可获得的。如何使 Whisper 在资源稀缺条件下更轻量和更快地运行在边缘设备上？为解决这一问题，本研究关注仅拥有32小时语音转文本数据的巴马巴拉语场景，提出了一种新的修剪方法。
### Innovation
不同于传统的词汇修剪方法，因为巴马巴拉语使用者经常发生代码转换，本研究采用了低秩分解和特征蒸馏来压缩嵌入，并通过合并层来限制性能损失，而不是直接删除层。
### Conclusion
最终模型保留了原始性能的90%，体积缩小48%，在MacBook Air M1上速度提高了2.15倍。
## 24. `cs.AI` - TokenTiming：一种用于通用推测性解码模型对的动态对齐方法 [PDF](https://arxiv.org/pdf/2510.15545), [HTML](https://arxiv.org/abs/2510.15545)
### Authors
Sibo Xiao,Jinyuan Fu,Zhongle Xie,Lidan Shou
### Background
在生成式AI中，加速大规模语言模型（LLMs）的推理是一个关键挑战。推测性解码（SD）显著提高了LLM推理的效率，但其有效性的限制在于源模型和目标模型必须具有相同的词汇集，这限制了可用于推测性解码的来源模型的数量，并且经常需要从头训练一个新模型。
### Innovation
本研究受到动态时间规整（DTW）算法的启发，提出了TokenTiming算法。该算法通过对源模型的词汇序列进行重新编码，得到一个新的目标词汇序列，并利用DTW来建立一个映射以转移概率分布，实现推测性采样的转移。这种方法能适应词汇不匹配的情况，并可与任何现成的模型配合使用，无需重新训练或修改。
### Conclusion
本研究展示了TokenTiming算法在各种任务中的全面实验结果，实现了1.57倍的加速。通过这种工作，推测性解码成为了一种通用的方法来选择源模型，使得SD成为加速LLM的更具有普适性和实用性的工具。
## 25. `cs.AI` - 从实验室到实际应用：评估代理代码推理能力 [PDF](https://arxiv.org/pdf/2601.03731), [HTML](https://arxiv.org/abs/2601.03731)
### Authors
Jia Li,Yuxin Su,Michael R. Lyu
### Background
随着大型语言模型（LLMs）发展成自主代理，对仓库级别的推理能力，即在大规模、现实世界、相互依赖的文件系统中保持逻辑一致性的能力，变得至关重要。当前的基准测试通常在孤立代码片段和黑盒评估之间波动。
### Innovation
本文提出了RepoReason，这是一种基于析取赋值验证的白盒诊断基准，旨在消除记忆的同时保留真实的逻辑深度。通过执行驱动的变异框架和环境作为语义占卜来重新生成真实状态，本文还建立了细粒度诊断系统使用动态程序切片，并通过三个正交度量：ESV（阅读负载）、MCL（仿真深度）和DFI（集成宽度）来量化推理能力。
### Conclusion
对前沿模型（例如Claude-4.5-Sonnet，DeepSeek-v3.1-Terminus）的全面评估揭示了普遍存在的集成宽度不足，这成为主要的认知瓶颈。本文的研究结果提供了针对优化新一代代理软件工程的细化白盒洞察。
## 26. `cs.AI` - 专业译者能否识别机器生成的文本？ [PDF](https://arxiv.org/pdf/2601.15828), [HTML](https://arxiv.org/abs/2601.15828)
### Authors
Michael Farrell
### Background
本研究探讨了未接受专门训练的专业翻译者能否可靠地识别由人工智能（AI）生成的意大利文短故事。
### Innovation
研究通过一项亲身体验实验，让69名翻译评估匿名的三篇短故事的作者（两篇由ChatGPT-4o生成，一篇由人类撰写），参与者对每篇故事的AI作者可能性进行了评分并提供了判断依据。研究发现，虽然总体结果不明显，但有一部分参与者（16.2%）能够准确区分人工智能生成的文本与人类撰写的作品。值得注意的是，一些低波动态、叙述矛盾等特征被证明是可靠指标；而语法准确性、情感基调等特征则导致了错误分类。
### Conclusion
这项研究引发了对合成文本编辑在专业环境中作用和范围的疑问。
## 27. `cs.AI` - LLMs ComCompress (on Decompress)? Evaluating Code Understanding and Execution via Invert on [PDF](https://arxiv.org/pdf/2601.13398), [HTML](https://arxiv.org/abs/2601.13398)
### Authors
Nickil Maveli,Antonio Vergari,Shay B. Cohen
### Background
在语言模型（LLMs）的研究中，，，代码理解与执行方面的评估中已经取得了一定显著的进展，但是这些模型在前后向向执行间保持一致的推理能力方面仍存有不足。。研究者关注到于复杂的推理任务和算法的理解，以及代码执行前后通线的合理性问题，尽管基于序列的数据模型在不同任务间的迁移学习上已经取得了一定些成功，但是一些关键的挑战仍然未得到有效的解决。
### Innovation
本文引入了‘RTCE’这一新的基准试騅（该试騉评估了四个代码执行推理任务上的‘一致性'性能。”通过使用'无操作评估'来检查解压缩算法间的双向对称准确性的具体表现。在这一基准试騒上LLMs首次能够区分基于大规模预training 和训练的方式和在训 ing数据上前的泛化能力之间存在的一些显著差异。而且，本文展示了一些核心技术学习方法仅能提供有限的改进，揭示了当前LLMs缺乏可靠的双向推理能力。。这一方法对一些先前的基准试ágenes不能充分揭示的精细问题知识和模型内部表现的问题。
### Conclusion
通过RTCE基准试验，作者揭示了当前LLMs在代码理解与执行一致性上的仍存有多项缺陷.基于示例学习（SFT）和在线后反思都不能解决一些基本的算法误解问题。这些方法只能得到轻微的提升而且对在未解决复 on算法理解上的根本问题时表现失败。由此表明算法复杂度是这些差距的主要原因，只有解决这一问题才能使让当前的LLMs更好地进行双向执行推理。上述研究结果显著地扩大了对对当前LLMs内部一致性问题的理解 on并后通过提供一个新的基准试騒，为其他类似研究提供有价值的参考。
## 28. `cs.AI` - 当迭代RAG战胜理想证据时：在科学多跳问答中的诊断研究 [PDF](https://arxiv.org/pdf/2601.19827), [HTML](https://arxiv.org/abs/2601.19827)
### Authors
Mahdi Astaraki,Mohammad Arshi Saloot,Ali Shiraee Kasmaee,Hamidreza Mahyar,Soheila Samiee
### Background
 Retrieval-Augmented Generation (RAG) 扩展了大型语言模型（LLMs）的能力范围，使其超出参数性知识的限制。然而，目前尚不清楚迭代检索-推理循环在何时能够有效地超越静态 RAG，特别是在涉及多跳推理、稀疏领域知识和异构证据的科学领域中。该研究旨在通过使用化学领域的 ChemKGMultiHopQA 数据集，对是否同步执行迭代检索和推理进行首次严格机制层面的诊断研究，探讨其是否能够超越理想化的静态上限（Gold Context） RAG。
### Innovation
本研究为首个从机制层面进行的控制性诊断研究，通过基准测试了 eleven 个最先进的 LLMs 在三种不同条件下（无上下文、理想证据上下文、迭代 RAG）的表现，特别关注多跳推理需求的问题，以及检索覆盖差距、锚点携带下降、查询质量、结构一致性以及控制校准等多个诊断指标的表现。研究发现，迭代 RAG 通常能够超越理想证据，特别是在针对非推理微调模型时效果显著。同时，提出的阶段检索方法减缓了多跳的失败率，减轻了上下文过载，能够动态纠正早期假设漂移，但仍存在覆盖不足的问题。
### Conclusion
最终结论表明，相较完全依赖理想证据的静态 RAG，加有阶段检索的 RAG 可以显著提高多跳科学问答的表现。虽然阶段检索有其局限性，但其效果远超单纯提供理想证据。研究为 RAG 系统在特殊科学领域中的应用和诊断提供了实用的指导，并为更可靠且可控的迭代检索-推理框架奠定了基础。
## 29. `cs.AI` - 吸引子FCM [PDF](https://arxiv.org/pdf/2604.27947), [HTML](https://arxiv.org/abs/2604.27947)
### Authors
Alexis Kafantaris
### Background
本文提出了一种新的吸引子特征图（Attractor FCM），它结合了梯度下降方法，并受到物理限制的约束，不同于Hebbian、自主或混合模型。该模型包含多个奇特特性，其中使用了残差记忆、时间反向传播和递归固定的锚点，用以更新权重。该锚点使模型能够收敛到一个固定点，且通过时间反向传播展开该模型，确保了误差最小化并准确定义了梯度。
### Innovation
本文的创新之处在于开发了一种基于梯度下降的物理约束下的吸引子FCM模型。该模型集成了残差记忆、时间反向传播和递归固定的锚点，并利用了新的学习算法。具体而言，采用了牛顿法找到系统的固定点吸引子，然后使用自适应梯度下降调整模型的景观。自适应项直接通过吸引子动态调整权重，防止过早收敛于局部最小值。此外，更新过程通过因果掩码采样，这一掩码根据初始专家意见告知网络有关的物理规则，从而有效地减小了误差。
### Conclusion
本文所提出的吸引子FCM通过建立新的学习算法，结合物理限制和残差记忆机制，使得模型能够在避免局部最小值的同时，更加有效地减少了误差。该模型在固定点吸引子的基础上通过递归更新权重，实现了更加精确和有效的学习过程。
## 30. `cs.AI` - 模型回忆其所违背的内容：多轮LLM创意中的约束遵守 [PDF](https://arxiv.org/pdf/2604.28031), [HTML](https://arxiv.org/abs/2604.28031)
### Authors
Garvin Kruthof
### Background
在研究人员使用大型语言模型迭代改进想法时，这些模型是否能够保持对原始目标的忠实性并不明确。以往的研究关注的是单一迭代过程中的模型性能，而忽略了解析复杂的科学创意过程中的多轮次交互和约束遵守情况。
### Innovation
本研究引入了DriftBench，一个用于评估多轮LLM辅助科学创意中约束遵守情况的基准测试。实验覆盖了来自五个提供商的七个模型（包括两个开源权重），四种交互条件，以及来自24个不同科学领域的38个研究简报。研究结果表明，迭代的压力可以可靠地增加结构复杂性，并且通常减少对原始约束的遵守。研究人员还发现在准确陈述约束的同时，模型会违背这些约束，这一情况被称为“知道但违反”（KBV）。整体而言，研究展示了即使在保持回忆准确性的前提下，模型仍然有下意识地违背约束的趋势，进而影响最终创意的质量。此外，结构化的检查点只能部分减少这些情况，而结构复杂度的膨胀仍然存在。
### Conclusion
人类验证盲评估者证实，LLM对约束违反的检测不足，使得报告的约束遵守分数保守。敏感性分析表明，研究发现对温度（0.7 vs 1.0）和压力类型（新颖性 vs 严谨性）的依赖性具有稳健性。研究团队已发布所有简报、提示、评分标准、对话记录和分数，作为开放基准测试，以便进一步研究。
## 31. `cs.AI` - 超越SFT-to-RL：基于黑盒在线策略蒸馏的先配准方法 [PDF](https://arxiv.org/pdf/2604.28123), [HTML](https://arxiv.org/abs/2604.28123)
### Authors
Sudong Wang,Weiquan Huang,Xiaomin Yu,Zuhao Yang,Hehai Lin,Keming Wu,Chaojun Xiao,Chen Chen,Wenxuan Wang,Beier Zhu,Yunjian Zhang,Chengwei Qin
### Background
目前的大规模多模态模型（LMMs）的通用后训练方案包括监督微调（SFT）和验证奖励的强化学习（RLVR）。然而，SFT会导致分布漂移，这不仅破坏了模型的原始能力，而且未能忠实匹配监督分布。在多模态推理中，感知错误和推理失败各有独特的分布漂移模式，并在后续的RL中层层叠加。研究指出，PRISM通过在SFT和RLVR之间插入一个显式的分布对齐阶段，解决了这一问题。
### Innovation
PRISM提出了一种三阶段方法，利用黑盒在线策略蒸馏（OPD）的原理，在监督微调（SFT）和验证奖励的强化学习（RLVR）之间插入一个分布对齐阶段。通过这种机制，PRISM可以为策略提供分离的纠正信号，使策略适应监督分布，而无需访问教师的logits。此外，研究使用Gemini 3 Flash中的113K高质量示例进行补充，以提高分布对齐的精度，并展示了在Qwen3-VL上的实验结果，证明了PRISM的有效性。
### Conclusion
实验结果表明，PRISM在多个RL算法和多种多模态基准上持续改善了下游RLVR的性能，特别是在4B和8B的SFT到RLVR基线上的平均准确率分别提升了4.4和6.0个百分点。PRISM的方法代码、数据和模型检查点将在指定的链接中公开。
## 32. `cs.AI` - LLM生成代码中的社会偏见：基准和缓解 [PDF](https://arxiv.org/pdf/2605.00382), [HTML](https://arxiv.org/abs/2605.00382)
### Authors
Fazle Rabbi,Lin Ling,Song Wang,Jinqiu Yang
### Background
现有的对大型语言模型（LLMs）生成代码的评估主要集中在功能正确性，而忽视了社会偏见的问题。尽管LLMs已在一些以人类为中心的应用中部署，其中人口统计学公平性非常重要，但研究人员发现现有的代码中存在严重的人口统计学偏见。
### Innovation
该研究利用了一个名为SocialBias-Bench的新基准，包含343个现实世界的编程任务，覆盖了七个人口统计学维度。研究还首次发现，常用的提示级干预方法不仅没有减少偏见，反而放大了偏见。研究进一步提出了一个名为Fairness Monitor Agent（FMA）的新组件，该组件可以通过分析任务描述并进行迭代审查来纠正偏见，无需执行测试套件。FMA在所有343项任务中将偏见减少了65.1%，并且提高了功能正确性。
### Conclusion
研究指出，现有的标准提示级干预措施不仅未能减轻偏见，反而可能使其加剧。研究还提出了一种新方法——Fairness Monitor Agent（FMA），该组件能够有效地减轻并纠正代码中的偏见，提升代码的功能正确性，优于其他研究中提出的各种方法。
## 33. `cs.AI` - RadLite: 小型语言模型的多任务LoRA微调以实现CPU部署的放射学人工智能 [PDF](https://arxiv.org/pdf/2605.00421), [HTML](https://arxiv.org/abs/2605.00421)
### Authors
Pankaj Gupta,Kartik Bose
### Background
大型语言模型（LLMs）在放射学领域表现出潜力，但由于计算需求限制了其在资源受限的临床环境中的应用。本研究探讨了3-4亿参数的小型语言模型（SLMs）通过LoRA微调是否能够实现强大的多任务放射学性能，从而允许在消费级CPU上部署。
### Innovation
研究中提出了一种通过LoRA微调小型语言模型的方法，实现了在多任务放射学任务上的显著性能提升。特别是，小型语言模型展示了在特定任务上的互补优势，并通过结合两种模型的oracle ensemble实现了整体最佳性能。此外，研究还展示了量化到GGUF格式的小型模型可以在消费级硬件上以4-8个词汇/秒的速度部署。
### Conclusion
研究结果表明，通过LoRA微调的小型、高效模型可以作为完全在消费级硬件上（无GPU要求）部署的多任务放射学AI助手。这项工作为在资源受限环境中部署放射学AI提供了一个实际可行的解决方案。
## 34. `cs.CL` - 通过编排痕迹进行大规模语言模型基于的多智能体系统的强化学习 [PDF](https://arxiv.org/pdf/2605.02801), [HTML](https://arxiv.org/abs/2605.02801)
### Authors
Chenchen Zhang
### Background
随着大规模语言模型（LLM）代理从孤立工具用户演进为协调团队，强化学习（RL）需要优化个体行动，同时也优化工作中一项任务的产生、分配、通信、聚合和停止的方式。本文通过研究基于LLM的多智能体系统，利用编排痕迹——包含子代理生成、分配、通信、工具使用、返回、聚合和停止决策的事件的时序交互图——来探索这一问题。
### Innovation
本文提出了三个技术轴：奖励设计分为八大家族，包括并行加速的编排奖励、拆分正确性和聚合质量的奖励；奖励和信用信号附属于从标记到团队的八个信用或信号单元；编排学习分解为决策子任务，包括何时生成子代理、将任务分配给谁、如何通信、如何聚合以及何时停止。此外，文章揭示了学术方法与工业证据之间的规模差距，出版的部署范围与公开的学术评价体系之间存在差距。
### Conclusion
截止2026年5月4日，小组未发现针对停止决策的明确定义的强化学习训练方法。文章将学术方法与来自Kimi Agent Swarm、OpenAI Codex和Anthropic Claude Code的公共工业证据进行了关联，并发布了一个包含84个标记论文的项目，一个排除日志，脚本化的语料统计和播放可重现编排痕迹的一级JSON模式。
## 35. `cs.CL` - 我们能否从听觉EEG中解码元音——严格的跨被试基准与诚实地评估 [PDF](https://arxiv.org/pdf/2605.00865), [HTML](https://arxiv.org/abs/2605.00865)
### Authors
Xiaoyang Li
### Background
基于EEG的语音解码在脑机接口中有很大潜力，但很多先前的研究依赖于单被试测试、小型样本或者缺乏严格的泄露控制。这项研究旨在建立一个可重复的跨被试基准，用于从OpenNeuro数据集ds006104的听觉EEG数据中解码五个元音发音（a, e, i, o, u），涵盖了16个被试、61个通道和256 Hz的采样率。
### Innovation
文章通过严格的交叉被试评估，包括使用只对训练数据进行归一化的留一被试验证方法和明确的反泄露检查，比较了14种不同类别的模型（经典机器学习、深度学习和黎曼方法），揭示出元音信息虽然存在但很弱，主要由早期瞬态听觉反应携带。
### Conclusion
在这篇研究中，XGBoost模型在全部特征下达到了24.5%的准确率，而基于差异熵特征的LightGBM模型在特征特定分析中达到了25.5%的准确率。在进行多重比较纠正后，各模型之间的显著性差异有限，传统的机器学习方法在这低信噪比情况下与深度模型相竞争。进一步的分析（消融分析、元音对间分析、被试内交叉验证、ERP、时域泛化和电极重要性）表明，元音信息是真实存在的但很弱。实验发布代码和评估脚本以确保完全可重复性。
## 36. `cs.CL` - OceanPile：面向基础模型的大规模多模态海洋数据集 [PDF](https://arxiv.org/pdf/2605.00877), [HTML](https://arxiv.org/abs/2605.00877)
### Authors
Yida Xue,Ningyu Zhang,Tingwei Wu,Zhe Ma,Daxiong Ji,Zhao Wang,Guozhou Zheng,Huajun Chen
### Background
海洋作为广阔的未充分利用领域，在全球气候调节和维护海洋生物多样性方面发挥着关键作用，但人工智能尚未对此领域产生显著影响，主要归因于基础数据不足的挑战。海洋数据具有高度碎片化、多模态、高噪声和弱标签的特点，缺乏统一的架构和语义对齐。尽管多模态大型语言模型在通用领域已取得显著成功，但在海洋科学中的应用仍受限于缺乏专门为海洋环境定制的大规模、高质量对齐的多模态数据集。因此，需要开发一种新的数据集来弥补这一空白。
### Innovation
OceanPile是一种面向基础模型设计的大规模多模态海洋数据集，包含三个关键组件：OceanCorpus，汇集了来自不同权威来源的声纳数据、水下图像、海洋科学视觉和科学文本；OceanInstruction，通过新颖的管道和层次海洋概念知识图谱合成的高质量指令数据集；以及OceanBenchmark，人工策划的评估基准，用于严格评估。通过多阶段的质量控制过程确保跨模态的一致性和科学有效性。
### Conclusion
实验证明，在该数据集上训练的模型表现显著提升。所有数据集均已公开，旨在推动海洋人工智能领域的发展并赋能特定领域的MLLMs。
## 37. `cs.CL` - MedMosaic：多样化医疗音频的大规模挑战性基准 [PDF](https://arxiv.org/pdf/2605.00969), [HTML](https://arxiv.org/abs/2605.00969)
### Authors
Harshit Rajgarhia,Shuubham Ojha,Asif Shaik,Akhil Pothanapalli,Rachuri Lokesh,Abhishek Mukherji,Prasanna Desikan
### Background
医学音频数据由于隐私法规和专家领域知识所需的高注释成本难以收集，现有的基准数据通常不能很好地涵盖复杂的医学音频场景。
### Innovation
MedMosaic数据集多样化医学音频类型，包括病情相关的生理声音、带有噪音的合成语音声以及不同长度的临床对话，并包含46,701个问题-答案对，涵盖多种类型的问题，以便系统评估多步推理和答案生成能力。 Benchmarked 13种音频和多模态推理模型显示这些系统在推理方面仍面临挑战。
### Conclusion
现有的音频和多模态推理模型在医学推理方面仍存在重大局限性，需要开发更强大、更专门的多模态推理模型。
## 38. `cs.CL` - SCARV: 结构约束的聚合以在冗余NLP数据集上实现稳健的样本排名 [PDF](https://arxiv.org/pdf/2605.00944), [HTML](https://arxiv.org/abs/2605.00944)
### Authors
Xu Zheng,Feiyu Wu,Linhong Wu,Zhuocheng Wang,Hui Li
### Background
样本级别的排名在数据为中心的自然语言处理（NLP）中被广泛用于分析、过滤、调试和数据整理。现有的管道通常以独立的方式对训练样本进行评分和排名，但在存在精确副本、近似副本、同义词以及其他常见的NLP语料库中的冗余结构时，这种假设很脆弱，因为随机训练可能会导致高度相似的实例在不同随机种子下获得不稳定的相对顺序。
### Innovation
提出了SCARV，这是一种模态聚合框架，可以在现有评分代理之上运行。SCARV结合了稳健的多种子聚合和基于冗余簇的结构感知聚合/分配步骤。该框架在合成冗余性、自然挖掘的QQP冗余性、多个代理系列、多种NLP任务以及端到端的DistilBERT微调中，显著改善了无代理排名的全局和局部稳定性，并产生更可重复的基于排名的决策，如子集选择和可疑示例检索。研究结果表明，稳健的多种子聚合是重要的通用稳定化因素，而结构感知组件在聚合预算低或冗余簇信息丰富、自然出现或充分覆盖时为主要增值因素。
### Conclusion
SCARV 不被定位为通用数据选择器或仅种子聚合的普遍主导替代品，而是作为代理诱导排名在冗余NLP数据集中的稳定性导向聚合层。
## 39. `cs.CL` - SRTJ: 自我进化的规则驱动无训练黑盒模型破解框架 [PDF](https://arxiv.org/pdf/2605.00974), [HTML](https://arxiv.org/abs/2605.00974)
### Authors
Jindong Li,Ying Liu,Yali Fu,Jinjing Zhu,Leyao Wang,Menglin Yang,Rex Ying
### Background
尽管大型语言模型（LLMs）逐渐配备了安全对齐机制，但近期研究发现，它们仍可能遭受故障突破（jailbreaking）攻击，这种攻击可以在不违反明确政策的情况下触发有害行为。尽管已有大量研究探索自动化故障突破策略，现有方法仍面临一系列根本挑战，如忽视成功和失败攻击经验的系统化利用，以及缺乏原则性的机制将攻击规则进行组合和选择以适应多种约束条件。这些挑战使得现有方法难以积累长期可转移的知识，并可靠地跨不同目标和不断变化的安全机制调整攻击策略。
### Innovation
本文提出了一种自我进化的规则驱动无训练故障突破框架（SRTJ），通过交互与反馈系统性地发现、组合和优化攻击策略，而无需更新模型参数。SRTJ 将经验驱动的攻击生成与基于回答集求解（ASP）的规则选择和约束感知组合相结合，利用迭代验证器反馈共同优化成功策略并分析失败模式。由此产生的规则记忆以分层多层次的方式进化，明确地将提炼出的攻击知识组织成长期、中期和短期规则，从而同时捕捉稳定可转移的策略和瞬时适应行为，有效平衡攻击尝试之间的探索和利用。
### Conclusion
在主流故障突破基准（HarmBench）上的广泛实验结果显示，SRTJ 在不同目标 LLM 上实现了强大的、稳定且高效的攻击性能，相比于现有故障突破方法，表现出更强的稳健性和泛化能力。源代码可在该地址获取。
## 40. `cs.CL` - 民主化中世纪英语法律传统 [PDF](https://arxiv.org/pdf/2605.00977), [HTML](https://arxiv.org/abs/2605.00977)
### Authors
Michael Zhang,Elise Wang,Charlotte Whatley,Seth Strickland,Dylan Bannon
### Background
世界上最广泛普及的法律体系的起源记录在数百万页手写文本中，其中大部分第一世纪的英美法律系统记录是用中世纪拉丁文高度简缩的形式手写的，这只有几十位世界学者训练有素能够阅读。
### Innovation
该研究通过构造包含4029行来自193个中世纪刑事和民事案例的文本数据库，并训练开源端到端的转录流水线，实现了在较小训练集和扩展缩写词的挑战下，标准神经网络架构达到79%的词准确性。进一步通过简单的后处理提高了准确性，使用n-gram语言模型将词准确性提高到82%，并借助Gemini Pro 3更正错误将准确性提升至88%。研究还对比了基于卷积神经网络和长短期记忆的架构（CNN+LSTM）与基于变压器的OCR架构（TrOCR），显示TrOCR在词准确性方面表现相似但字符准确性较低，因为它过度猜测使得人类难以推断出正确的读法。
### Conclusion
研究不仅开发了一套高效的转录流水线，还将该流程集成到一个网页门户中，使得历史学家、中世纪学家和学生可以接触到动态化的中世纪英语法律传统。
## 41. `cs.CV` - 超越感知捷径：轻量级多模态语言模型中可泛化的视频推理因果启发式去偏优化 [PDF](https://arxiv.org/pdf/2605.01324), [HTML](https://arxiv.org/abs/2605.01324)
### Authors
Jingze Wu,Quan Zhang,Hongfei Suo,Zeqiang Cai,Hongbo Chen
### Background
尽管强化学习（RL）大大提升了大规模多模态语言模型的推理能力，但在轻量级模型中，特别是用于边缘计算的情况，RL的有效性仍受到限制。轻量级模型倾向于依赖数据偏见引起的感觉捷径，而不是发展真正意义上的推理能力。
### Innovation
本文通过因果分析和实验揭示了感知偏见的底层现象，提出了一种因果启发式的框架VideoThinker，通过两阶段去偏过程培养轻量级模型的稳健推理能力。首先，Bias Aware Training阶段创建一个专门的“偏见模型”，用来模拟这些捷径行为。其次，Causal Debiasing Policy Optimization (CDPO)算法微调主模型，采用创新的排斥目标积极排除模型的不正确逻辑，同时拉近模型向正确且可泛化的推理。
### Conclusion
通过这种方法，VideoThinker-R1在视频推理效率方面成为新的基准。在与VideoRFT-3B的对比中，没有使用监督微调（SFT），仅使用1份训练数据进行RL训练，VideoThinker-R1在广泛使用的基准测试中平均提升了3.2%，并在VideoMME上领先7%。而在与更大规模的Video-UTR-7B模型的交叉规模比较中，VideoThinker在多项基准测试中表现出色，如MVBench上提高了2.1%，TempCompass上提高了3.8%。源代码可以在相关网站上获取。
## 42. `cs.CV` - 通过顺序实验设计实现主动推理视觉语言模型 [PDF](https://arxiv.org/pdf/2605.01345), [HTML](https://arxiv.org/abs/2605.01345)
### Authors
Anjie Liu,Ziqin Gong,Yan Song,Yuxiang Chen,Xiaolong Liu,Hengtong Lu,Kaike Zhang,Chen Wei
### Background
现代视觉语言模型（VLMs）的视觉感知受到基本的感受带宽瓶颈限制：广角视野不可避免地牺牲了用于复杂推理所需的细粒度细节。受经典主动视觉和信息觅食范式的启发，我们将其克服这一限制的过程视为一个顺序决策过程，并通过顺序贝叶斯最优实验设计（S-BOED）问题进行形式化。虽然在连续的万亿像素空间中精确的贝叶斯推理是不可行的，但我们推导出原理上可实现且可操作的近似方法，以平衡空间覆盖和分辨率。
### Innovation
提出了一个基于顺序贝叶斯最优实验设计（S-BOED）框架的训练自由推理策略，为配备了多种视觉工具的代理提供了一个可灵活调整的模板。该策略涵盖了从高效的贪婪采样到前瞻规划等多种优化算法，以近似求解最优设计。实证评估表明，该方法显著提升了最先进的模型性能，相比标准基线表现更优，有效缩小了与人类标注的或然性之间的差距。
### Conclusion
研究成果证明，该策略进一步提升了状态最新型视觉语言模型的性能，有效缩小了与人类标注数据的差距，显著超越了标准基线模型。
## 43. `cs.CV` - Zero-Sho- Interpretable Image Steganalysis for Invertible Image Hing [PDF](https://arxiv.org/pdf/2605.01331), [HTML](https://arxiv.org/abs/2605.01331)
### Authors
Hao Wang,Yiming Yao,Yaguang Xie,Tong Qiao,Zhidong Zhao
### Background
图像隐写分析旨在检测隐藏在图像中的秘密信息，，, 该任务是评估隐写技术（steganographyogra phy) 安全性的关键措施， 吤 尔 尜 ， 尷 牵 数 紤 uto-已经存在的隐写方法的界定通常局限于假防图像属于两类（例如， 图南图像 ) 或 图南图像中的一种），而隐台分析通常在训练数据和测试数据遵循类似分布的约束下进行。 版式 以妨碍其在现实场景中的应用。
### Innovation
1 本文提出了一种专门针对隐涡方案的双重可解的图像隐台分析框架， 作挑战性的对零外零设场景下实施。 实 兏和把隐蔚和 和 盓 在两谦框架中，并施赋予隐塔分析功能以恢复stego图像中嵌入的秘密信息。 除此之外 我们还议一种简单的残差特征增强增强生成steo图像 从而提高在跨数据集和跨模型架构 在 消的隐台分析器的一般化能力。
### Conclusion
在基准数据集中进行的实验显示证明 本方法在隐求图像隐含方法下的隐特分析方法上超越了现有现有的隐台分析技术。
## 44. `cs.CV` - CHASE: 竞争假设下的不确定性感知选择性预测 [PDF](https://arxiv.org/pdf/2605.01346), [HTML](https://arxiv.org/abs/2605.01346)
### Authors
Kartik Jhawar,Yuhao Geng,Atul N. Parikh,Lipo Wang
### Background
标准的选择性预测方法通常从单一预测分支的输出中估计不确定性。虽然这些方法在一般的不确定性估计中有效，但在部分可观测性条件下，它们往往会遇到困难。在这种条件下，局部时间证据可能是矛盾的，标准的信任度分数变得误导性。
### Innovation
本文介绍了CHASE（竞争假设下的不确定性感知选择性预测）框架，这是一种选择性预测框架，能够明确比较结构化的时间解释，以决定是否做出决定或弃权。CHASE通过优化这些假设差距上的排名感知选择器，以全局方式将安全的承诺与根本不确定的决策区分开来。
### Conclusion
通过在隐藏连接性推理问题上的实验，本研究证明，明确地处理竞争性假设提供了更好的平衡指标。与经典的不确定性基线相比，CHASE在没有忽略任何预测的情况下，整体准确性和三分类准确性的提升达到了统计上的显著性。在非常高不确定性的情况下，它在整体一致性和三分类准确性方面分别获得了11.0%和8.8%的相对改进。同时，该框架通过将风险边界严格保持在80%覆盖下的最佳基线水平，并在90%覆盖下减少总体风险9.9%，提供了一种在结构化不确定性下更可靠的选择决策方法。
## 45. `cs.CV` - AgriKD: 针对高效叶片疾病分类的跨架构知识蒸馏 [PDF](https://arxiv.org/pdf/2605.01355), [HTML](https://arxiv.org/abs/2605.01355)
### Authors
Minh-Dung Le,Minh-Duc Hoang,Hoang-Vu Truong,Thi-Thu-Hong Phan
### Background
在资源有限的现场环境中，自动化叶片疾病分类对于早期疾病检测至关重要。视觉变换器（ViTs）能够通过建模长期依赖关系和跨类别关系，提供强大的表征能力，但高计算成本使得它们在边缘设备上部署不切实际。因此，现有方法难以高效地将丰富的表征转移到轻量级模型上。
### Innovation
本文提出了AgriKD，一种跨架构的知识蒸馏框架，旨在高效部署在边缘设备上。AgriKD从视觉变换器（ViT）教师模型向紧凑的卷积学生模型转移知识，并通过在输出、特征和关系层集成多个蒸馏目标来弥合Transformer和CNN架构之间的表征差距，使学生模型能够更好保存和利用由Transformer生成的全局表征。
### Conclusion
在多个叶片疾病数据集上的实验表明，蒸馏后的学生模型在性能上接近教师模型，同时显著提高了效率，模型参数减少了约172倍，计算成本减少了47.57倍，推理延迟减少了18-22倍。此外，优化后的模型在多个运行时格式（包括ONNX、TFLite Float16和TensorRT FP16）上实现了稳定且几乎无降级的预测性能。在NVIDIA Jetson边缘设备和移动应用程序上进行的实际部署展示了可靠的实际运行时推理，突显了AgriKD在资源受限环境中具有实用性的AI农业应用潜力。
## 46. `cs.CV` - 在非稳定环境中的约束转换：增强鲁棒推理对齐 [PDF](https://arxiv.org/pdf/2510.04142), [HTML](https://arxiv.org/abs/2510.04142)
### Authors
Xiaoyu Yang,En Yu,Wei Duan,Jie Lu
### Background
本文探讨了多模态大型语言模型（MLLMs）中推理对齐的关键但未充分研究的挑战：在非稳定环境中，源模型的多样化推理分布会不可预测地演变，系统性地将偏差和漂移传递给目标模型。
### Innovation
本文提出了自主偏好优化（APO）框架，将跨模型的分歧视为动态负约束，而非噪声。APO通过两阶段协议运作：首先，监督式初始训练将目标模型投影到源模型的能力交集中；其次，通过多负Plackett-Luce目标和约束意识优化，以显式抑制漂移轨迹，合成一致的共识流形。
### Conclusion
实验结果表明，我们7B规模的模型在稳定性方面表现优异，平均准确率甚至超过专有的源模型。此外，我们还发布了CXR-MAX，这是一个包含来自七个大规模MLLM的170,982个推理轨迹的大规模基准，以促进漂移环境下推理对齐的研究。
## 47. `cs.CV` - 从精确到可靠的量化影响：VLMs超越准确性的影响 [PDF](https://arxiv.org/pdf/2509.21173), [HTML](https://arxiv.org/abs/2509.21173)
### Authors
Aymen Bouguerra,Daniel Montoya,Alexandra Gomez-Villa,Chokri Mraidha,Fabio Arnez
### Background
Vision-Language模型（VLMs）如CLIP在零样本分类和安全关键任务上取得了重大突破，包括异常数据集（OOD）检测。然而，这些模型对计算资源的需求限制了其在现实世界中的高效部署。量化作为一种提高效率的常用方法，虽然理论上应节约计算资源，但对于其对可靠性指标的影响超出了简单Top-1准确率的探讨仍然不足。
### Innovation
本研究进行了一项大规模评估，跨越了超过70万次实验配置的变化，全面探索了VLMs量化的影响。研究发现，量化在提升准确度、校准、OOD检测和噪声鲁棒性等方面具有意想不到的效果，同时，并没有改善特征变化或虚假关联的鲁棒性。量化作用机理不同于简单的正则化，量化减弱高秩频谱成分，促使模型更加依赖鲁棒的低秩特征。这种频谱过滤效应驱动了泛化和抗噪能力的提升，为未来使用量化来加速并提升VLMs的可靠性提供了路径。
### Conclusion
量化促进了VLMs的性能改进，尤其是在抗噪声和泛化能力等方面，通过减少高秩频谱成分的作用，量化促使模型依赖更为鲁棒的低秩特征。这为实现更快更可靠的VLMs提供了一条潜在的道路，超越了量化传统的效率角色。
## 48. `cs.CV` - Patch to Caption:：一种统一的零样本 caption 务框架 [PDF](https://arxiv.org/pdf/2510.02898), [HTML](https://arxiv.org/abs/2510.02898)
### Authors
Lorenzo Bianchi,Giacomo Pacini,Fabio Carrara,Nicola Messina,Giuseppe Amato,Fabrizio Falchi
### Background
零样本 Caption 模型是近期 来提出的一种模型，， 领域，， 守空间视觉-- 语言模型来生成图像描述而不需要依赖带有配对 的图像-文本对。 。 在在生成图像描述时所， 模型 from 从单一的图像 patch 开开始， 幐到文章随机区域和整个图形. 这一领域的现有模型着重于从图像中心转变为关注图像 patch 来进行描述， 的描述时对 免掉了对细粒度区域监督的需求. 盍对象是 for 导出一个统一 framework 杯述 zero.shot样本 欁片
### Innovation
该研究介绍发 研发了一种伪统一框架 zero that ick聚从图像注耀到 的视角转变为图像 patch 的视角 来生成任意 regions 的描述 荷请仅仅 藱使用了图像 patch 作为基本的caption 卼位词使得从单一的图像 patch 延展到不连续的区域甚至整个图像. them 中起 . 瑜模利用制用 吃一系有意义的密集视觉特征 back 如 模型例如 DINO 琜拍 寿高性能在多个 区域描述任务上对比吧线基线线以及 on 疋界模型该 模型 在 zero-shot 密切描述 和 和区集合描述 . 上还 还介绍了一种新型的 patch-wise 语义区域对于灵活描述的作用. 迿 
### Conclusion
该础椎模型和关 .在 . 夙几个基于区域的caption 任务中获得了 on.one 上art 的表现 幯 。在 zero-shot 寖密描述 和  . 一 有区域集描述 任务 棱 .模型 乔适了显著的表现力 项研究 开招示了 patch wise 义义实现灵活的描述caption 生提,
## 49. `cs.CV` - AVIIEdit: Granularity-Aware Mask Refiner for I-sync Video Instance Editing [PDF](https://arxiv.org/pdf/2512.10571), [HTML](https://arxiv.org/abs/2512.10571)
### Authors
Haojie Zheng,Shuchen Weng,Jingqi Liu,Siqi Yang,Boxin Shi,Xinlong Wang
### Background
近期解析的内容的背景、创新点和结论。现有视频生成技术，中突显了音频-视音频同步对于吸引观众的重要性。然而在现有的视频编辑方法中，，对音频视同步同步往往被忽视，并且缺乏精细的空间和时间控制能力,用于精确的实例级编辑。因此我们需要一个新的框架来实现这一需求。
### Innovation
AVIIIEdit框架提出了一个细粒度度检敏感化增强器，以迭代方式将改进粗略的用户提供的掩码至精确的实例级别区域。此外，我们进一步设计引入了一个基于区域反馈的音频代理以实现高品质的的音频指导并同时保细粒度的时间控制。为了促进这一任务
### Conclusion
我们在多个大规模的带有实例中心的对对应和和和集全面注释的大规模的数据集中进行广泛的实验表明AVIIIEdit在视觉质量以及音频I视音频同步方面均优于现有最先进的的技术。项目项目网址为该项目项目的页面。
## 50. `cs.CV` - 多视图MRI影像组学范式转变：预测胶质母细胞瘤MGMT甲基化 [PDF](https://arxiv.org/pdf/2512.22331), [HTML](https://arxiv.org/abs/2512.22331)
### Authors
Mariya Miteva,Maria Nisheva-Pavlova
### Background
无创从医学影像中推断出分子肿瘤特征是放射组学中的一个核心目标，尤其在胶质母细胞瘤（GBM）中，O6-甲基胞嘧啶-DNA甲基转移酶（MGMT）启动子甲基化对于预后和治疗具有重要的意义。尽管基于影像组学的机器学习方法在此任务中显示出前景，但传统单一模态和早期融合方法通常受限于特征冗余高和对特定模态信息建模不完整。
### Innovation
提出了一种基于变分自动编码器（VAE）的多视图潜在表示学习框架，该框架在保持特定模态影像组学结构的同时，允许在紧凑的概率潜在空间中实现后期融合。该方法在对比后T1加权（T1Gd）和液体衰减反转恢复（FLAIR）磁共振成像中提取的影像组学特征上进行评估。
### Conclusion
实验结果表明，提出的多视图VAE结合随机森林分类器在测试上的AUC为0.77（95%CI:0.71-0.83），显著优于基线影像组学模型（AUC=0.54）和超参数调整模型（AUC=0.64）。这些发现表明，多视图概率编码允许可更有效的综合互补的MRI信息，并显著提高了MGMT启动子甲基化状态的预测性能。
## 51. `cs.CV` - Pixel-to-4D: 基于动态3D高斯分布的摄像机控制图像到视频生成 [PDF](https://arxiv.org/pdf/2601.00678), [HTML](https://arxiv.org/abs/2601.00678)
### Authors
Melonie de Almeida,Daniela Ivanova,Tong Shi,John H. Williamson,Paul Henderson
### Background
人类能够仅凭单张图片预测场景的未来动态。能够模仿这种能力的单张图片到视频生成模型是智能系统的重要组成部分。近年来的方法在时间连贯性和3D一致性方面有所改进，但往往缺乏 robust 的用户可控制性，如改变摄像机路径，限制了其实用性。现有的摄像机控制模型在准确建模摄像机运动、保持时间连贯性和维护几何完整性方面面临挑战。通过利用明确的中间3D表示，可以实现与给定摄像机轨迹一致的高质量视频生成。尽管许多方法使用3D点云渲染场景，但这种两步过程仍然难以实现完全的时间连贯性。
### Innovation
本文提出了一种新颖的框架，该框架在一次前向传递中构建3D高斯场景表示，给定单张图片即可采样可信的对象运动。这种设计避免了需要迭代降噪来将对象运动注入渲染帧，实现了快速、摄像机引导的视频生成。实验结果表明，该方法在Kitti、Waymo、RealEstate10K和DL3DV-10K数据集上达到了最先进的视频质量和推理效率。
### Conclusion
我们的方法通过利用明确的3D高斯表示，在单次前向传递中快速生成摄像机引导的视频，经大量实验验证，在五个基准数据集上的效果显著优于现有方法。方法在线页面提供进一步研究使用。
## 52. `cs.CV` - 跨尺度预训练：提高低分辨率卫星影像语义分割的自监督学习 [PDF](https://arxiv.org/pdf/2601.12964), [HTML](https://arxiv.org/abs/2601.12964)
### Authors
John Waithaka,Gustave Bwirayesu,Moise Busogi
### Background
自监督预训练在遥感领域的研究主要依赖中分辨率(MR)图像数据集，因为这类数据集易于获得。随着高分辨率(HR)图像数据集的发布，研究者们开始探讨如何利用HR数据集改善MR图像的表示学习和下游MR任务的分割性能。
### Innovation
本文设计了一个空间亲和组件，可以整合到现有的自监督学习框架中，并利用HR图像数据来改善MR图像的表示学习。实验结果表明，该组件能够提升单凭HR或MR图像预训练的模型的表现。
### Conclusion
空间亲和组件能够提升自监督学习框架在低分辨率卫星影像语义分割任务上的性能，特别地，在两个自监督学习框架上的实验显示，该组件性能优于仅使用HR或MR图像预训练的模型。
## 53. `cs.CV` - 结合面部视频和生物信号进行驾驶过程中的压力估计 [PDF](https://arxiv.org/pdf/2601.04376), [HTML](https://arxiv.org/abs/2601.04376)
### Authors
Paraskevi Valergaki,Vassilis C. Nicodemou,Iason Oikonomidis,Antonis Argyros,Anastasios Roussos
### Background
在医疗监测和安全关键系统（例如真实世界的驾驶）中，准确的压力识别至关重要。压力通常通过生理信号如鼻周出汗和心率检测，然而面部活动提供了额外的线索，这些线索可以通过视频轻松获取。本研究提出了一种结合面部视频和生理信号的多模态压力估计框架，即使在生理信号采集具有挑战性的条件下也能保持有效性。
### Innovation
该研究引入了一种基于Transformer的时序建模框架，并评估了单模态、早期融合和跨模态注意力策略。研究发现，通过将3D提取的面部特征与生理信号进行跨模态注意力融合，性能显著提升，AUC_ROC从52.7%提升到92.0%，准确率从51.0%提升到86.7%。尽管是在驾驶数据上进行评估，但该框架和方法论可能适用于其他压力估计场景。
### Conclusion
结合面部视频和生理信号的多模态压力估计框架在面临生理信号采集挑战时保持有效。通过3D面部表情描述符和跨模态注意力融合，大幅度提升了压力识别的性能。未来的研究将进一步验证该框架在不同压力监测场景中的普适性。
## 54. `cs.CV` - VAUQ：LVLM视觉感知不确定性量化自我评估 [PDF](https://arxiv.org/pdf/2602.21054), [HTML](https://arxiv.org/abs/2602.21054)
### Authors
Seongheon Park,Changdae Oh,Hyeong Kyu Choi,Sean Du,Sharon Li
### Background
大型视觉-语言模型（LVLMs）常常产生幻觉，限制了它们在实际应用中的安全部署。现有的LLM自我评估方法依赖于模型估计其输出正确性的能力，这可以提高部署的可靠性；然而，这些方法严重依赖语言先验，因此不适合评估基于视觉的预测。
### Innovation
本文提出了一种名为VAUQ的视觉感知不确定性量化框架，用于LVLM自我评估。VAUQ通过量化模型输出依赖于视觉证据的程度，引入了图像信息评分(IS)，并使用无监督的核心区域掩蔽策略来放大显著区域的影响。结合预测熵与这种核心掩蔽的IS，得到了一个无需训练的评分函数，能够可靠地反映答案的正确性。
### Conclusion
全面的实验表明，VAUQ在多个数据集上始终优于现有的自我评估方法。
## 55. `cs.CV` - Hazards-Aware Traffic Scene Graph Generation [PDF](https://arxiv.org/pdf/2603.03584), [HTML](https://arxiv.org/abs/2603.03584)
### Authors
Yaoqi Huang,Julie Stephany Berrio,Mao Shan,Stewart Worrall
### Background
当前在复杂的驾驶场景中保持情境意识具有挑战性，因为需要持续对多个场景元素进行注意力分配，并理解潜在危险可能如何影响自身车辆。现有研究虽然在特定语义类别和视觉显著区域的检测上表现出色，但在评估安全相关性方面能力不足。此外，现有场景图中的通用空间谓词要么仅针对前景对象，要么通过现有场景图处理所有场景元素，这些方法对于驾驶场景而言是不够的。
### Innovation
本文引入了一个新的任务：交通场景图生成，该任务能够捕捉与前景危险物之间的特定交通关系，并且提出了一个新框架，该框架利用交通事故数据和深度线索来补充视觉特征和语义信息，以进行推理。生成的交通场景图通过颜色编码危险等级、标注其影响机制和相对位置给驾驶员提供直观指导。
### Conclusion
我们在Cityscapes数据集上创建了关系注释，并在10项任务上从5个角度对模型进行了评估。对比实验和消融研究的结果表明，我们具备了对于危险意识的驾驶场景理解中的自我中心推理能力。
## 56. `cs.CV` - 深 CycleGAN on 和和  [PDF](https://arxiv.org/pdf/2601.00237), [HTML](https://arxiv.org/abs/2601.00237)
### Authors
Chao Yang,Haoyuan Zheng,Yue Ma
### Background
在印刷电路板 (PCB) 缍缺陷检测 中 用红外 (IR) 图像的数据稀缺是一个关键瓶颈。传统的 IR 图像获得依赖对配对的的监督信 
### Innovation
本研究提出了一个结合 CycleGAN 和 YOLOv8 的跨模态数据扩增大框架 杅通过 CycleGAN 进行无配对 的图像转问题把可见光 PCB 图像转换为 IR 图像。进而生成高保真的伪 IR 栒ឈ样本保留缺陷的结构语义并真实模拟热分布模式。然后通过生成的伪 IR 数据和实际的 IR 数据训练 YOLOv on 实现一种轻 赬 y重训练策略。研究表明该方法在数据少条件下能 显增强了特征学习能力，并并且生成的样本在结果检测 性行表现出比 优越性能， 运靠近有监督训练的基准成绩表明伪 IR 合成在工业检测中具有 robust 的扩增大策略效能。
### Conclusion
实验结果表明该方法能够有效地提升在少数据条件下的特征学习能力，相对于使用未扩增数据单独训练的模型 生成的伪 IR 数据作为训练模型的表现更好。这证明了在工业检测任务中伪 IR 合成具有一致的扩增策略效果
## 57. `cs.CV` - 基于视觉和语言模型的合成数据生成 grounding [PDF](https://arxiv.org/pdf/2603.09625), [HTML](https://arxiv.org/abs/2603.09625)
### Authors
Ümit Mert Çağlar,Alptekin Temizel
### Background
深度学习模型可以从多样化的数据和数据量中受益，促使人们使用合成数据增强现有的数据集。然而，现有的合成数据评估指标大多关注潜在特征的相似性，难以解释，且与下游任务的相关性不高。
### Innovation
该研究提出了一种基于视觉-语言框架的可解释合成数据增强和评估方法。该框架结合了生成模型、语义分割和图像描述，并使用视觉和语言模型。还提出了ARAS400k数据集，包含100k真实图像和300k合成图像，每个图像都配有语义分割图和描述。ARAS400k通过分析语义组成、减少描重复和验证跨模态一致性，实现了合成数据的自动评估。
### Conclusion
实验结果表明，仅使用合成数据训练的模型能够达到竞争力的性能，而使用增强数据（结合真实和合成图像）训练的模型则在大部分情况下优于使用真实数据的基线。因此，这项工作建立了一个适用于遥感任务、具体为语义分割和图像描述的可扩展基准。
## 58. `cs.CV` - 持续少量样本适应在合成指纹检测中的应用 [PDF](https://arxiv.org/pdf/2603.14632), [HTML](https://arxiv.org/abs/2603.14632)
### Authors
Joseph Geo Benjamin,Anil K. Jain,Karthik Nandakumar
### Background
近年来，生成式人工智能的进步显著提高了合成指纹图像的质量和真实性，这增加了指纹识别系统受到数据注入攻击的风险。在这些攻击中，恶意合成的指纹在注册或认证阶段被插入。因此，急需开发方法来检测指纹图像是否为真实或合成的。虽然可以训练深度神经网络模型来分类图像，但这些模型容易过拟合训练数据，对未见过的生成式人工智能生成的合成指纹难以泛化。
### Innovation
本文将合成指纹检测问题表述为持续少量样本适应问题，目标是在短时间内进化基础检测器以识别新型合成数据。为实现持续少量样本适应，本文采用二元交叉熵损失和监督对比（应用于特征表示）损失，同时在微调过程中回放先前已知样式中的少量样本以减轻灾难性遗忘。
### Conclusion
基于多种深度神经网络骨干（作为特征提取器）和多种实际及合成指纹数据集的实验表明，所提出的方法在检测未知合成样式快速适应与遗忘已知样式之间取得了较好的平衡。
## 59. `cs.CV` - C2W-Tune: Cavity-to-Wall Transfer Learning for Thin Atrial Wall Segmentation in 3D LGE-MRI [PDF](https://arxiv.org/pdf/2603.24992), [HTML](https://arxiv.org/abs/2603.24992)
### Authors
Yusri Al-Sanaani,Rebecca Thornhill,Sreeraman Rajan
### Background
准确的3D延迟钆增强MRI（LGE-MRI）左房（LA）壁分割对于壁厚绘图和纤维化量化至关重要，但由于墙壁的薄几何结构、复杂的解剖结构和低对比度，这一过程仍然具有挑战性。
### Innovation
提出了一种名为C2W-Tune的两阶段腔室到壁转移框架，利用高精度的左房腔模型作为解剖学先验，以提高薄壁界定。该框架首先使用一个带有ResNeXt编码器和实例归一化的3D U-Net在网络中预训练腔室分割，第二阶段转移权重并适应网络进行LA壁分割，使用渐进层解冻计划来同时保留腔室特征并允许壁特定优化。
### Conclusion
在2018年左房分割挑战数据集上，C2W-Tune优于从零开始训练的一个匹配架构。在无监督度较低的场景下，使用来自同一训练集的不同训练集的70个训练体积，C2W-Tune的Dice得分为0.78，仍与最新的双心房多类基准竞争，典型得分为0.6-0.7。这些结果表明，基于解剖的任务转移结合受控的微调可提高3D LGE-MRI中薄左房壁分割的准确性。
## 60. `cs.CV` - DynFlowDrive： 基于 流量 动态 世界 建模 的 自动 驾驶 [PDF](https://arxiv.org/pdf/2603.19675), [HTML](https://arxiv.org/abs/2603.19675)
### Authors
Xiaolu Liu,Yicong Li,Song Wang,Junbo Chen,Angela Yao,Jianke Zhu
### Background
最近的分析模型已整合到自动驾驶系统中， 以提高分析的可靠性。。。 冎现现有的方法通常通过外观生成或 确定性 回归 来预测未来的轨迹， 迟能这种方法在捕捉轨迹条件下的场景演变方面能力有限，并 从而导致不稳定的动作决策。
### Innovation
我们我们提出了 DynFlowDrive ， 一种基于流的动态世界世界模型 
### Conclusion
在nuScenes和 和 道纳 
## 61. `cs.LG` - Quantum增强的强化学习用于改进车辆路径优化的混合方法 [PDF](https://arxiv.org/pdf/2605.01574), [HTML](https://arxiv.org/abs/2605.01574)
### Authors
T. Satyanarayana Murthy,B. Swathi Sowmya,Santhosh Voruganti,Sai Varshini Giridi,Chaitanyya Pratap Agarwal,Vanteddu Akshitha
### Background
车辆路径问题（VRP）是运输和物流中最复杂的NP难组合优化问题之一，需要动态的解决方案方法。
### Innovation
提出了一种新的混合方法，将量子近似优化算法（QAOA）与QRL策略网络结合，而非传统的变分图层、QAOA混合层和成本哈密尔顿层。该增强方法让代理在学习策略时能够利用问题特定的量子相关性，从而丰富对路径解决方案空间的探索。实验结果表明，增强的QAOA-QRL框架在训练方面更快收敛，并能处理超出Grover的适应性搜索（GAS）和量子强化学习（QRL）方法的能力范围的更大规模的VRP实例。
### Conclusion
在标准VRP实例上的实验结果表明，更好的解、更少的收敛期以及良好的近场量子硬件模拟器上的内存使用率。这些发现表明，QAOA集成的QRL可以作为可扩展、高质量的量子辅助组合优化的一种可行方法。
## 62. `cs.LG` - 从数据包到模式：解释加密网络流量作为纵向行为信号 [PDF](https://arxiv.org/pdf/2605.01616), [HTML](https://arxiv.org/abs/2605.01616)
### Authors
Rameen Mahmood,Omar El Shahawy,Souptik Barua,Zachary Beattie,Jeffrey Kaye,Xuhai ?Orson'' Xu,Chao-Yi Wu,Danny Yuxing Huang
### Background
人类行为难以在大规模下持续观察，但日常设备使用中留下可测量的痕迹。本文研究加密智能手机网络流量是否可以作为一种普遍、持续的被动感应手段，捕捉与睡眠、压力和孤独相关的行为模式。
### Innovation
使用变压器骨干网络和用户适配器建模共享行为结构，通过稀疏自编码提取对应不同活动模式的行为特征，并将这些特征与睡眠障碍、压力和孤独相关联。结果表明，加密网络流量具有作为纵向行为感应的标准，特别是那些偏离个体基线的行为动态。
### Conclusion
不同的结果反映不同的时间结构：压力主要与个体之间的稳定差异有关，孤独与个体内部随时间的变化有关，而睡眠障碍则是两者的结合。这些个体内部的变化无法通过预定义的网络流量特征捕捉到，表明学习到的表示对于纵向行为感应的价值。
## 63. `cs.LG` - ECG-biometrics-bench: 为ECG生物特征认证可重复基准测试提供统一框架 [PDF](https://arxiv.org/pdf/2605.01548), [HTML](https://arxiv.org/abs/2605.01548)
### Authors
Milad Parvan
### Background
ECG生物特征识别作为一种在可穿戴系统中实现连续、活体识别的有前途的模态方法已经出现了。然而，许多先前的研究报告了过于乐观的结果，这主要是由于数据泄漏（例如，同一会话内的随机拆分）。为解决这一问题，提出了ECG-biometrics-bench，这是一种模块化、可重复的基准测试框架，它在七个广泛使用的公共ECG数据集中标准化了预处理、分割和评估方法，这些数据集涵盖了临床、随访和大规模队列设置。该框架支持闭集和开放集（即，在此工作中，主题.disjoint的泛化）评估，以及包括跨会话和长期时间分离在内的逐步现实协议。
### Innovation
该研究通过ECG-biometrics-bench框架提供了一个模块化且可重复的基准测试平台，解决了以往研究过于乐观的结果问题。该框架支持多种评估方式，包括跨会话和长期时间分离等渐进现实协议。此外，通过分析多个架构（如DeepECG、ResNet1D和CNN-LSTM），发现这些失败并不是特定于模型的，而是当前监督特征学习范式中固有的。该研究还展示了通过基于动态多会话模板融合的重型注册、轻型验证策略，部分缓解了由时间老化引起的性能下降。
### Conclusion
通过多数据集的全面分析，该研究揭示了随机拆分谬误，显示了会话内评估协议人为地提升了性能，却掩饰了由时间漂移和未知身份引起的严重性能下降。此外，研究还表明，为了实现可靠的现实世界部署，需要解决几个关键挑战，如特定于模型的不稳定性、对时间漂移的敏感性等。最终，该研究建立了ECG生物特征识别更为现实的基准，并强调了这些挑战的重要性。
## 64. `cs.LG` - Banach-Butterfly Invariant: 影响自适应的沃尔什几何用于三元多项式阈值函数 [PDF](https://arxiv.org/pdf/2605.01637), [HTML](https://arxiv.org/abs/2605.01637)
### Authors
Gorgi Pavlov
### Background
研究布尔函数的Walsh-Hadamard蝴蝶因子分解，通过蝴蝶层的范数来捕捉和分析函数的复杂性。
### Innovation
引入Banach-Butterfly Invariant (BBT)，这是一种基于布尔函数各坐标影响的自适应 Banach 几何。通过 BBT 可以排出收缩不变量，并证明了若干数学性质，包括 Jensen 下界和严格 Schur-凸性。
### Conclusion
证明了 BBT 在不同影响度函数类别中的收缩性质，并通过有限测试床和真实值 WHT 激活能级代理验证了其在实际中的应用。
## 65. `cs.LG` - MAGIC: 多步优势门控因果影响在多智能体强化学习中的应用 [PDF](https://arxiv.org/pdf/2605.01805), [HTML](https://arxiv.org/abs/2605.01805)
### Authors
Haohan Yu,Jinmiao Cong,Shengzhi Wang,Lu Wang,Chanjuan Liu
### Background
多智能体强化学习（MARL）的一个关键挑战在于设计能够有效促进智能体间协调的学习信号。设计这样的信号需要能够量化真实、长期的因果影响。现有的方法难以满足这一需求。
### Innovation
提出了Multi-step Advantage-Gated Interventional Causal MARL (MAGIC) 框架，该框架能够提取多步因果影响并将它们选择性地转换为内在奖励。MAGIC 使用条件互信息进行因果干预，以量化长期的智能体影响，并引入了一种基于优势的门控机制，以确保探索行为向有益的、目标对齐的行为方向进行。
### Conclusion
在多个标准MARL基准测试和任务家族上的实验表明，MAGIC 在主要评估指标上显著优于现有方法，提升了至少10.1%的性能。
## 66. `cs.LG` - HEVC基底视频和JPEG区域兴趣图块的混合视觉遥测技术在带宽受限机器人视觉中的试点研究 [PDF](https://arxiv.org/pdf/2605.01826), [HTML](https://arxiv.org/abs/2605.01826)
### Authors
Natalia Trukhina,Vadim Vashkelis
### Background
在带宽受限的机器人和监控系统中，通常依赖单一的压缩视频流来维持连续的场景意识和下游机器感知。然而，低比特率视频虽然能够保留运动和粗略的上下文信息，但往往丢失了可靠物体识别和决策所需的精细局部细节。
### Innovation
该论文提出了一种双通道视觉遥测方案，通过连续的低比特率视频流与根据需要传输的选择性高细节区域兴趣（ROI）形成补充。论文采用HEVC作为基础视频流编码器，JPEG作为ROI细化的编码器，双方共同构建了一个实用且可复现的编码器栈。
### Conclusion
该研究建立了混合传输范式，其中视频仅方案和混合方案在匹配的总通信预算下，进行了对比实验。研究表明，这种混合方案能够有效提升机器人视觉系统的性能。该论文为后续基于JPEG AI的语义静态图像通道的第二阶段研究奠定了方法论基础。
## 67. `cs.LG` - 远程动作生成：基于最小通信量的远程控制 [PDF](https://arxiv.org/pdf/2605.01833), [HTML](https://arxiv.org/abs/2605.01833)
### Authors
Szymon Kobus,Deniz Gündüz
### Background
在远程控制场景中，一个或多个缺乏直接奖赏访问权的执行者，通过受限通信信道由控制器指导。这使得当动作空间较大或连续时，高效通信变得具有挑战性。
### Innovation
引入了新型框架利用远程生成，控制器不仅不直接发送完整动作指令，而是发送少量信息，让执行者通过从控制器演变的目标策略中进行局部动作采样。此方法通过重要性采样辅助采样过程，且在接收指导后执行者进行监督学习来改进自己的局部采样技术，从而逐步降低未来通信需求。
### Conclusion
提出的Guided Remote Action Sampling Policy (GRASP)展示了显著的通信减少，实验结果平均12倍数据减少，对于连续动作空间达50倍，且相比直接动作传输节约41倍，相比奖赏传输更高效。
## 68. `cs.LG` - A Semi-Supervised Kernel Two-Sample Test [PDF](https://arxiv.org/pdf/2605.01775), [HTML](https://arxiv.org/abs/2605.01775)
### Authors
Gyumin Lee,Shubhanshu Shekhar,Ilmun Kim
### Background
传统的两样本检验方法于传统的两样本检验通常在标记的协变量不足的情况下进行。，这些测试往往忽视协变量的作用，传统的两样本检验假设在零假设条件下样本是独立且等等的，。当引入协变量时，这些假设可能被打破，这进一步使得校准过程更加复杂。
### Innovation
本文研究在协变量丰富但标记数据稀缺的情况下的两样本检验问题提出了一种半监督方法，这种方法能够生成渐近服从正态分布的两次样本统计量 吚个方法有效地整合了协变量的附加信息如果不考虑协变量 传统法可能会违反零假设下的两个样本独立性性拟以渐近地检验实现了这种方法的协变进行自动校准更容易方便由于渐近性检验在零假设下的渐近分布容易获取并且实现了渐近功效常常比法比现有的核函数测试在整合了两个样本时通常显著优于现有的基于核函数的检验。
### Conclusion
本方法不仅在理论上一致低于固定的和局部功率下都有效 跸Detroit的 Simulation结果验证了该方法在实践和理论上的强度优势优势，并方法在零假设和替代假设下下的渐近功效通常远高于现有的基于核函数的检验。 
## 69. `cs.LG` - ShiftLIF: 使用幂次量化高效多层次神经元 [PDF](https://arxiv.org/pdf/2605.01866), [HTML](https://arxiv.org/abs/2605.01866)
### Authors
Kaiwen Tang,Di Yu,Jiaqi Zheng,Changze Lv,Qianhui Liu,Zhanglu Yan,Weng-Fai Wong
### Background
神经网络（SNN）在边缘传感中具有潜力，因为它们具备事件驱动的计算和时间过滤能力。然而，标准的泄漏积分-突触模型（LIF）神经元仅通过二元突触信号进行通信，严重影响了表示能力。现有的多层次突触神经元虽然提高了信息传输，但通常依赖于均匀量化，这不匹配膜电位分布或引入了成本高的突触乘法。
### Innovation
提出了ShiftLIF，这是一种多层次突触神经元，将膜电位映射到对数间隔的幂次量化突触集。这种设计在小振幅范围内提供了更细的表示，此时膜电位密集分布，并通过位移和累积操作实现了无乘法的突触计算。结果，ShiftLIF在提高突触级表达性的基础上，保持了传统SNN计算的硬件友好性质。
### Conclusion
ShiftLIF在无线、声学、运动和视觉传感任务上进行了评估。结果表明，ShiftLIF在准确性和现有多层次突触神经元相匹配或超出的同时，保持了突触能效接近标准二进制LIF的水平。这表明ShiftLIF为跨模态边缘传感提供了有效率与准确度之间的良好权衡。
## 70. `cs.LG` - Chart-FR1：面向密集图表的视觉焦点驱动精细推理 [PDF](https://arxiv.org/pdf/2605.01882), [HTML](https://arxiv.org/abs/2605.01882)
### Authors
Hongkun Pan,Yuwei Wu,Wanyi Hong,Shenghui Hu,Qitong Yan,Yi Yang,Rufei Han,Changju Zhou,Minfeng Zhu,Dongming Han,Wei Chen
### Background
多模态大型语言模型（MLLMs）在图表理解和推理任务中表现出显著潜力。然而，当面对高信息密度（HID）图表（如包含多个子图、图例和密集注释的图表）时，仍然面临三大挑战：1）有限的细粒度感知导致关键视觉线索的遗漏；2）冗余或噪声视觉信息削弱了多模态推理的表现；3）缺乏根据视觉信息量进行的自适应深度推理。
### Innovation
本文提出了一种新颖的焦点驱动细粒度图表推理模型Chart-FR1，以提高感知、聚焦效率和自适应深度推理在HID图表上的表现。该模型通过引入重点视觉聚焦链式思考（Focus-CoT）、聚焦驱动的强化学习算法（Focus-GRPO）和信息效率奖励机制及自适应KL惩罚机制来解决上述挑战。
### Conclusion
在多个图表基准测试上的广泛实验表明，Chart-FR1在图表理解和推理方面优于最先进的MLLMs。此外，还构建了一个新的高信息密度图表基准（HID-Chart），以评估细粒度图表推理能力。该模型的代码可在指定链接处访问。
## 71. `cs.LG` - Stable Blanket with Hidden Variables and Cycles [PDF](https://arxiv.org/pdf/2605.01856), [HTML](https://arxiv.org/abs/2605.01856)
### Authors
Hanqing Xiang
### Background
稳定的回归旨在识别出一系列预测因子，环境变化下其条件关系与响应变量保持不变。。没有明确的数学公式或已有的图形特征化方法主要是为结构因果模型SCMs)处理隐藏变量和因果循环。现有研究指出这些隐藏变量和反馈关系 緾在应用中自然而然存在，这对挖掘Mark诺模型 的边界 和预测变量集起决定作用。
### Innovation
本文研究了含有隐蔽变量和因果循环的图形因果模型的稳定边界。在含有隐蔽变量的模型中,通过有向无环缘mer加图 UnderMixed图和 (FOrMG) 和受应用于表征化稳定区间 和建立干预子v削减集的子对的从属地区的影响提出FOrMG结构与干预变量集进行干预的稳定预测变量集的构建策略。在含有循环的模型中 我们利用有向图 Directed和混合图 DmG) 通过强联通连分合集(SCCs)作为基本图结构单位从而结合这些思想对同时隐变量和循环的情况进行研究。主要这些研究为图形稳定性边界下的马可尔边缘和,稳定的稳定性边界提供了一种扩展的图形特征刻画。
### Conclusion
我们的研究扩展了稳定回归的图形解释 诩以外的全全无有系结构
## 72. `cs.LG` - 主键假设：通过线性子空间对齐实现跨模型能力迁移 [PDF](https://arxiv.org/pdf/2604.06377), [HTML](https://arxiv.org/abs/2604.06377)
### Authors
Rishab Balasubramanian,Pin-Jie Lin,Rituraj Sharma,Anjie Fang,Fardin Abdi,Viktor Rozgic,Zheng Du,Mohit Bansal,Tu Vu
### Background
本文研究了预训练能力是否可以在不重新训练的情况下在不同规模的模型之间进行迁移，特别是跨不同模型规模的迁移。
### Innovation
提出了主键假设，认为模型能力对应于低维潜在子空间中的方向，这些方向可以通过线性对齐来在模型之间迁移。基于该假设提出了UNLOCK框架，该框架通过对比实现场能力和非场能力的源变体之间的激活来提取能力方向，然后通过低秩线性转换与目标模型对齐，最终在推理时应用以引发所需的行为。
### Conclusion
实验表明，通过这种方法可以在无需训练的情况下显著提高不同模型规模的推理能力，如Chain-of-Thought和数学推理。分析显示，迁移的成功取决于预训练期间学习到的能力，且该方法能够增强潜在能力，使输出分布倾向于成功的推理路径。
## 73. `cs.LG` - 延迟同态强化学习：针对具有延迟反馈的环境 [PDF](https://arxiv.org/pdf/2604.03641), [HTML](https://arxiv.org/abs/2604.03641)
### Authors
Jongsoo Lee,Jangwon Kim,Soohee Han
### Background
在现实世界系统中，强化学习经常遇到延迟反馈的问题，这打破了马尔可夫假设，影响了学习和控制效果。经典的基于增强的方法会导致状态空间爆炸，增加了样本复杂度的负担。尽管取得了进展，最先进的增强方法主要是缓解对批评家的负担，或是对演员和批评家没有统一处理。
### Innovation
本文提出了延迟同态强化学习（DHRL），该框架基于MDP同态性，定义了一种信念等价关系在增强状态空间上以压缩控制冗余的增强状态。理论上，对于确定性动态，可以获得精确抽象，而在随机动态中，可以获得近似抽象。这种方法使得演员和批评家都能从结构化的抽象机制中受益。在有限领域中，精确抽象保持了最优性和恢复了无延迟样本复杂度的阶数；而在连续领域中，提出了深度延迟同态策略梯度（D$^2$HPG），这是DHRL框架的一个深度演员-批评家实现。实验表明，D$^2$HPG在MuJoCo连续控制任务中优于强增强基线。
### Conclusion
在有限和连续域中，DHRL和D$^2$HPG分别通过精确和近似抽象，减轻了样本复杂度问题，同时提升了学习和控制效果。
## 74. `cs.LG` - Feature Weighting Improves Pool-based Sequential Active Learning for Regression [PDF](https://arxiv.org/pdf/2604.02019), [HTML](https://arxiv.org/abs/2604.02019)
### Authors
Dongrui Wu
### Background
现有的基于池的序列主动学习方法（ALR) 从大量无标签样本中依次选择少量样本， 以便在给定的标注预算内构建出更准确的回归模型。。代表性和多样性是通过计算样本间的距离来进行考虑的两个方面 
### Innovation
本文提出了四种基于单任务的改进型ALR方法和和三种基于多任务的改进型ALR方法， 免ridge回归系数通过少量先前标注样本训练， 杈将这些系数用于在样本间距离计算中加权相应特征。 
### Conclusion
实验结果显示, 一种简单的且易于实现的增强方法总是能够在单任务和多任务回归问题中改善了五种现有ALR方法的性能 
## 75. `cs.LG` - 利用大型语言模型进行带有文本属性的知识图谱增强以构建医学概念表示 [PDF](https://arxiv.org/pdf/2604.13331), [HTML](https://arxiv.org/abs/2604.13331)
### Authors
Mohsen Nayebi Kerdabadi,Arya Hadizadeh Moghaddam,Chen Chen,Dongjie Wang,Zijun Yao
### Background
电子健康记录（EHR）挖掘中，学习高质量的医学概念表示（如标准化诊断、药物和程序代码）对于临床预测至关重要。但是，由于现有本体资源中缺少或不完整的临床重要跨类型依赖关系（如诊断-药物和药物-程序关系）以及丰富的临床语义缺乏，并且即使以文本形式存在也难以与KG结构集成，thus，稳健的概念表示学习受到阻碍。
### Innovation
文章提出了MedCo，一种由大型语言模型（LLM）赋能的图学习框架，用于医学概念表示。MedCo通过结合从EHRs抽取的统计上可靠的关系，并使用类型约束的LLM提示来推断语义关系，首先构建了一个全局知识图谱（KG）。然后，利用LLM将KG扩展为带有节点描述和边理据的文本属性图，提供语义信号。最后，MedCo以LLaMA文本编码器与异构GNN联合训练的方式，将文本语义和图结构融合成统一的概念嵌入。
### Conclusion
在MIMIC-III和MIMIC-IV上的广泛实验表明，MedCo在预测性能上表现出持续的改进，可以作为标准EHR流程的有效插件概念编码器。
## 76. `cs.SE` - Shell中的误译：揭示大型语言模型中的表情符号语义混淆 [PDF](https://arxiv.org/pdf/2601.07885), [HTML](https://arxiv.org/abs/2601.07885)
### Authors
Weipeng Jiang,Xiaoyu Zhang,Juan Zhai,Shiqing Ma,Chao Shen,Yang Liu
### Background
表情符号广泛用于数字通讯中以传达情感意图，然而它们对大型语言模型（LLMs）的安全影响仍未得到充分研究。本文识别了表情符号语义混淆这一漏洞，该漏洞导致LLMs误将ASCII表情符号解读为执行意外甚至破坏性操作。为了系统研究这一现象，作者开发了一套自动化数据生成管道并构建了一个包含3,757个代码导向测试案例的数据集，这些案例覆盖了21个元情景、四种编程语言以及不同的复杂度背景。研究表明，表情符号语义混淆在模型中普遍存在，平均混淆比例超过38%。更严峻的是，这些混淆的响应中超过90%是‘无声失败’，尽管语法上有效，但不符合用户意图，可能带来安全上的负面影响。
### Innovation
作者开发了一套自动化数据生成管道并构建了一个详细的数据集来系统研究表情符号在LLMs中的语义混淆问题。研究发现，这种语义混淆在模型中广泛存在，并观察到该漏洞容易转移到流行的代理框架中，现有的基于提示的缓解措施效果有限。
### Conclusion
作者呼吁社区认识到这种新兴的漏洞，并开发有效的缓解方法，以确保LLM系统的安全性和可靠性。
## 77. `cs.SE` - 从SFT到RL：LLM基线漏洞检测后训练管线的揭秘 [PDF](https://arxiv.org/pdf/2602.14012), [HTML](https://arxiv.org/abs/2602.14012)
### Authors
Youpeng Li,Fuxun Yu,Xinda Wang
### Background
近年来，通过将大型语言模型（LLMs）集成到漏洞检测（VD）中，该领域已经朝着更具解释性和上下文感知的分析方向转变。尽管后训练技术在一般的编码任务中显示出潜力，但它们在VD中的系统应用仍然较少。本文旨在研究LLM基线VD的后训练管道，探讨在策略性强化学习（RL）中使用GRPO的一致优越性，相对于其他方法如指令微调（SFT）、偏好的后策略优化方法和专门的VD LLMs。
### Innovation
本文是首次对基于LLM的VD的后训练管线进行全面研究。主要创新点包括：(1) 数据收集方面，SFT基于拒绝采样的方法比基于合理化监督更有效；(2) 阶段交互方面，增加SFT周期对偏策略优化有益，但对于策略性强化学习中适度增加SFT周期的探索性降低有局限；(3) 奖励机制方面，细粒度的根本原因判断提供了更可靠的信用分配；(4) 评估协议方面，基于根本原因分析的LLM作为法官提供了一种更稳健的替代方案，但不同法官模型间存在变异。
### Conclusion
本文研究结果表明，策略性强化学习（RL）结合GRPO在后训练阶段的一致优越性。此外，提供了特定于VD的后训练指南和见解：(1) 数据收集方面，拒绝采样的SFT相比基于合理化的监督更有效；(2) 阶段交互方面，增加SFT周期对vd任务中的偏策略优化有益；(3) 奖励机制方面，细致的根本原因判断提供了更可靠的奖励信号分配；(4) 评估协议方面，基于根本原因分析的LLM作为法官提供了一种稳健的替代方案，尽管不同法官模型之间存在变异。
