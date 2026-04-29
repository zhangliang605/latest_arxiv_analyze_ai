# 20260429
[![Subscribe_Visitors](https://visitor-badge.laobi.icu/badge?page_id=nituchao.latest_arxiv_analyze_ai_rss)](https://github.com/nituchao/latest_arxiv_analyze_ai)

## 1. `cs.AI` - 论偏好基归约在论证中的逆解的存在性 [PDF](https://arxiv.org/pdf/2604.22958), [HTML](https://arxiv.org/abs/2604.22958)
### Authors
Alessio Zaninotto,Bruno Yun,Nir Oren,Srdjan Vesic
### Background
偏好基论证框架（PAFs）扩展了Dung的基础论证方法，通过编码论证之间的偏好，这种偏好控制攻击转化为击败的过程。不同的方法导致不同的PAF到基础论证框架（AAF）的归约方法。本研究关注的是PAF逆问题，给定一个论证图、标签和语义，判断是否存在一种偏好关系可以使论证得到预期的标签。这个问题在偏好提取和可解释性等领域有应用。
### Innovation
研究考虑了在完全语义下最常见的四种偏好基归约方法，证明了在大多数情况下，这个问题可以在多项式时间内解决。
### Conclusion
论证中的偏好基归约逆问题在多数情况下可以在多项式时间内求解，这对于偏好提取和解释具有重要意义。
## 2. `cs.AI` - 幂定律的力量：不对称性使组合推理成为可能 [PDF](https://arxiv.org/pdf/2604.22951), [HTML](https://arxiv.org/abs/2604.22951)
### Authors
Zixuan Wang,Xingyu Dang,Jason D. Lee,Kaifeng Lyu
### Background
自然语言数据遵循幂定律分布，大多数知识和技能出现频率较低。一般认为，重新加权或精炼数据以趋向均匀分布可能有助于模型更好地学习这些稀有技能，但研究发现相反的结果：在包括状态跟踪和多步算术在内的广泛组合推理任务中，使用幂定律分布训练模型的一致性能优于使用均匀分布训练模型。
### Innovation
引入了简约的技能组合任务，证明在幂定律分布下学习明显需要更少的训练数据。理论分析揭示了幂定律抽样引起的有益不对称性，改善了病态损失景观，这使模型能够在低数据复杂度下首先获取高频率技能组合，进而有效地学习稀有的长尾技能。
### Conclusion
结果提出了一种新观点，即何种数据分布能够有效训练模型。
## 3. `cs.AI` - PExA: 并行探索代理用于复杂文本到SQL [PDF](https://arxiv.org/pdf/2604.22934), [HTML](https://arxiv.org/abs/2604.22934)
### Authors
Tanmay Parekh,Ella Hofmann-Coyle,Shuyi Wang,Sachith Sri Ram Kothur,Srivas Prasad,Yunmo Chen
### Background
基于LLM的代理在文本到SQL生成中常常面临延迟和性能之间的权衡问题，即性能提升会带来延迟增加，反之亦然。
### Innovation
提出了一种新的框架，将文本到SQL的生成问题重新定义为软件测试覆盖率问题，即用一组简单的、原子的SQL测试用例来全面覆盖原始查询的语义。通过迭代测试用例覆盖率，在收集足够信息后生成最终SQL，利用已探索的测试用例SQL来支持最终的生成。
### Conclusion
该框架在现行业领先的Spider 2.0基准测试上进行了验证，达到70.2%的执行准确率，成为新的领先成果。
## 4. `cs.AI` - 避免让LLM阅读图：让图思考 [PDF](https://arxiv.org/pdf/2604.23057), [HTML](https://arxiv.org/abs/2604.23057)
### Authors
Yuqi Sun,Tianqin Meng,George Liu,Yashraj Panwar,Lakshya Chaudhry,Munasib Ilham,Aman Chadha
### Background
该研究探讨了显式信念图是否能改进多智能体代理在协同推理中的大型语言模型（LLM）性能。研究在纸牌游戏Hanabi中开展了3000多次受控实验，测试了四种不同的LLM家族。
### Innovation
研究发现了四个关键发现：1）架构决定信念图的价值，不同的架构下，信念图对基础模型的影响不同。2）识别了模型家族特异性误操作“规划者反抗”，即LLM在部分能力下会忽视正确规划者的建议。3）整个游戏的证据表明，跨代理的惯例优于单代理干预措施。4）初步扩展分析表明，图的深度对多玩家情境下的性能有负面影响。
### Conclusion
研究结果表明，在多代理协作推理中，信念图的集成架构和深度对模型性能有显著影响。同时，跨代理的惯例比单代理干预措施更有效。
## 5. `cs.AI` - 基于多保真数字孪生和FMEA知识增强的一般航空器智能故障诊断方法 [PDF](https://arxiv.org/pdf/2604.22777), [HTML](https://arxiv.org/abs/2604.22777)
### Authors
Zhihuan Wei,Yang Hu,Xinhang Chen,Yiming Zhang,Jie Liu,Wei Wang
### Background
一般航空器的故障诊断面临严峻挑战，包括罕见的真实故障数据、多样的故障类型以及薄弱的故障信号。
### Innovation
本文提出了一种基于多保真度数字孪生的智能故障诊断框架，该框架整合了四个模块：高保真飞行动力学仿真、FMEA驱动的故障注入、多保真余量特征提取以及大语言模型增强的可解释报告生成。
### Conclusion
实验结果表明，配对镜像余量方案在20类任务上的宏F1得分达到96.2%，而GRU代理模型实现了4.3倍的推理加速，仅牺牲0.6%的性能。与24种现有方案的比较表明，余量特征质量对诊断性能的影响约为分类器架构的5倍，确立了“余量质量优先”的设计理念。
## 6. `cs.AI` - 基于离散潜在压缩和LTL规则提取的因果可解释Wi-Fi CSI人体活动识别 [PDF](https://arxiv.org/pdf/2604.22979), [HTML](https://arxiv.org/abs/2604.22979)
### Authors
Luca Cotti,Luca Lavazza,Marco Cominelli,Liying Han,Gaofeng Dong,Francesco Gringoli,Mani B. Srivastava,Trevor Bihl,Erik P. Blasch,Daniel O. Brigham,Kara Combs,Lance M. Kaplan,Federico Cerutti
### Background
利用Wi-Fi Channel State Information (CSI)的人体活动识别（HAR）在保持因果可解释性、符号可控制性和直接操作高维原始信号的联合需求方面存在挑战。尽管深度神经模型在CSI基体HAR (CHAR) 上取得了很强的预测性能，但它们依赖于难以修改的连续潜在表示，而纯粹符号方法又无法处理原始CSI流。
### Innovation
本文提出了一种全自动且严格解耦的处理管道，在该管道中，通过具有Gumbel-Softmax潜在变量的分类变分自编码器压缩CSI幅度窗口，并在容量控制的目标下生成一个紧凑的离散表示。然后冻结编码器并将其作为确定性映射到一维潜在轨迹。对这些轨迹进行因果发现以估计条件时间依赖图，并将统计上支持的延迟依赖关系转换为线性时序逻辑（LTL）规则，从而生成一个基于规则评估和聚合的完全符号和确定性分类器。通过这种方法，可以在符号层面上组合特定于天线的规则集，从而实现结构化的多天线融合。
### Conclusion
CHAR Latent Temporal Rule Extraction (CHARL-TRE)的实验结果表明，该方法在保持显式的时间和因果结构的同时，能够与端到端黑箱模型竞争，表明基于无监督的离散潜在表示的确定性符号分类是一种可供选择的无线HAR方法。
## 7. `cs.AI` - 一种系统的方法论方法论框架用于大型语言模型调试 [PDF](https://arxiv.org/pdf/2604.23027), [HTML](https://arxiv.org/abs/2604.23027)
### Authors
Basel Shbita,Anna Lisa Gentile,Bing Zhang,Sungeun An,Shailja Thakur,Shubhi Asthana,Yi Zhou,Saptha Surendran,Farhan Ahmed,Rohan Kulkarni,Yuya Jeremy Ong,Chad DeLuca,Hima Patel
### Background
大型语言模型（LLMs) 在现代 AI 工作流中扮演着关键角色，，从 开开放生成文本到复杂基于代理的推理在内。。。然而 但是，调试这些模型仍然是一个持久的挑战，由于它们的神秘和概率性质以及在不同LMs在不同 的 鷨弥盖众多任务和环境中难以诊断错误的方式。现有的调试方法通常无法处理这种情况，因此，本文探讨了一种系统的方法用于 LLM 迨调，将模型视为可观察系统，并 幝转从 衁估检测到故障细化。。
### Innovation
本文提出了一个系统的方法用于 LLM 肨调，该方法统一了可评估可 反解释性和误差分析实践,使从业人员能够在没有标准化基准和故障标准的情况下进行不断迭代的故障诊断、改进提示和模型参数以及适应场景进行调整。尽管这些方法学不仅可以加速问题排除还还有促使可部署基于 LLM 的系统在具可可性地、透明和可可度扩展性。。”
### Conclusion
本文提出的方法学不仅加快了问题处理排除调试
## 8. `cs.AI` - 没有测试案例，也不是问题：基于知识蒸馏的科学工作流代码生成 [PDF](https://arxiv.org/pdf/2604.23106), [HTML](https://arxiv.org/abs/2604.23106)
### Authors
Siddeshwar Raghavan,Tanwi Mallick
### Background
现有的多代理大型语言模型（LLM）框架在代码生成中通常依赖于执行反馈，并通过输入/输出（I/O）测试案例逐步改进。然而，这种方法不适用于科学工作流，因为科学工作流缺乏I/O测试案例，生成这些测试案例需要解决该核心问题。
### Innovation
本文引入了MOSAIC，一个无需I/O监督的训练免费多代理框架，用于科学代码生成。MOSAIC采用学生-老师知识蒸馏框架，通过领域特定示例和结构化问题分解来促进生成过程。此外，为了进一步减少链式子问题中的幻觉，MOSAIC引入了统一上下文窗口（CCW），以在代理之间保持一致的推理。
### Conclusion
通过SciCode基准测试的实验表明，MOSAIC在准确度、可执行性和数值精度方面优于现有方法，同时依赖于轻量级模型。
## 9. `cs.AI` - MindTrellis: 通过互动视觉探索与AI共同创建知识结构 [PDF](https://arxiv.org/pdf/2604.23129), [HTML](https://arxiv.org/abs/2604.23129)
### Authors
Xiang Li,Cara Li,Emily Kuang,Can Liu,Jian Zhao
### Background
知识工作者面临着将多文档中的信息综合为结构化的概念理解的挑战。这一过程是迭代性的：用户探索内容、识别概念之间的关系并不断重组其概念模型。现有方法提供有限的支持。基于大语言模型（LLM）的系统允许用户查询信息但不改变知识结构；手动工具如思维导图支持结构创建，但缺乏智能辅助。因此，存在着一个开放的机会：支持协作构建，让用户和AI共同开发不断演变的知识表示。
### Innovation
作者提出了一种名为MindTrellis的交互式可视化系统，让用户和AI共同构建动态知识图。用户可以通过查询图来检索文档中的信息，并通过引入新概念、修改关系和重组层级来贡献。在12名参与者创建演示文稿的实验中，MindTrellis在知识组织和认知负荷方面优于只具备检索功能的基准系统，以专家对内容覆盖和结构质量的评估为依据。
### Conclusion
MindTrellis通过交互式视觉探索的方法，为用户和AI提供了协同构建动态知识图的平台，显著提高了知识组织的质量和降低了认知负荷，展示了在知识共享和结构化理解方面的潜力。
## 10. `cs.AI` - 机制性操控LMs揭示对抗设置中分层特征的脆弱性 [PDF](https://arxiv.org/pdf/2604.23130), [HTML](https://arxiv.org/abs/2604.23130)
### Authors
Nilanjana Das,Manas Gaur
### Background
尽管对大型语言模型（LLMs）进行了安全对齐，它们仍然可以通过破解，产生有害输出。现有的攻击展示了这种漏洞的存在，但没有揭示出其内部机制。本文旨在探讨破解成功是否是由可识别的内部特征驱动，而不是仅仅是提示的影响。研究使用Gemma-2-2B模型和BeaverTails数据集，设计了三阶段管道来提取概念对齐的标记，之后通过三种特征分组策略识别出特征子组，并通过增强这些特征来测量生成输出的有害性得分。
### Innovation
本文提出了一种三阶段管道方法，利用分层特征的相似性提取对齐标记，而后通过三种特征分组策略识别出特征子组，再对这些特征放大后测量其生成输出的有害性得分。该研究发现了在Gemma-2-2B模型中，中间到后期层的特征子组更负责任何未必安全的输出，这表明针对特征级别的干预可能比当前的提示级别防御更具原理性。
### Conclusion
研究结果表明，Gemma-2-2B模型的破解漏洞集中在中间到后期层的特征子组上，这意味着针对特征级别的干预可能比当前的提示级别防御更具有原理性，提供了一条更有效的对抗鲁棒性路径。
## 11. `cs.AI` - UNSEEN：针对AR-LLM社会工程攻击的一种跨层LLM遗忘防御 [PDF](https://arxiv.org/pdf/2604.23141), [HTML](https://arxiv.org/abs/2604.23141)
### Authors
Tianlong Yu,Yang Yang,Xiao Luo,Lihong Liu,Fudu Xing,Zui Tao,Kailong Wang,Gaoyang Liu,Ting Bi
### Background
新兴的AR-LLM基于社会工程的攻击（例如SEAR）正在对现实世界的社会生活构成重大威胁。在这个AR-LLM社会工程攻击中，攻击者可以使用增强现实（AR）眼镜捕获目标的图像和音频信息，并利用大型语言模型（LLM）识别目标和生成社会概况，进而利用LLM代理应用社会工程策略进行对话建议，以赢得目标的信任并进行钓鱼攻击。当前的防御方法，如基于角色的访问控制或数据流跟踪，不适用于嵌入式AR设备和不透明的LLM推理结合而成的生态系统，这使得存在一种新兴且强有力的隐私威胁，现有的隐私范式难以解决。这需要从单纯依靠人类中心化的措施，如立法和用户教育，转向可执行的供应商政策和平台级别的限制。
### Innovation
我们提出了UNSEEN，一种协调的跨层LLM遗忘防御，结合了AR ACL（访问控制层）的身份验证感知，基于F-RMU的LLM遗忘以抑制敏感概况，以及运行时代理护栏以控制适应性交互控制，以应对资源受限的AR嵌入设备安全，不透明LLM推理中的细粒度访问控制，以及治理适应性交互代理等重大技术挑战。
### Conclusion
我们使用60名参与者的数据在IRB批准的用户研究中以及包含360个标注对话数据集的现实社交场景中评估了UNSEEN。
## 12. `cs.AI` - UpstreamQA: 用于视频问答任务显式推理的模块化框架 [PDF](https://arxiv.org/pdf/2604.23145), [HTML](https://arxiv.org/abs/2604.23145)
### Authors
Jason Nguyen,Ameet Rao,Alexander Chang,Ishaan Kumar,Erin Tan
### Background
视频问答（VideoQA）需要结合处理空间、时间以及语言线索的模型。然而，任务固有的复杂性通常需要多步骤推理，而当前的大规模多模态模型（LMMs）通常是隐式地执行这些任务的，这使得它们的内部决策过程变得不透明。相比之下，大规模推理模型（LRMs）会明确生成中间逻辑步骤，这增强了可解释性并可以提高多跳推理的准确性。但是，这些模型通常依赖于静态帧抽样，不专门用于理解和处理视频。
### Innovation
提出了UpstreamQA，这是一种模块化框架，通过明确的上游推理模块拆分并评估视频推理的核心组件。通过使用多模态LRMs进行对象识别和场景情境生成，然后将增强的推理轨迹传递给下游的LMMs进行视频问答。
### Conclusion
我们的结果表明，引入显式推理可以显著提高下游视频问答的表现和可解释性，但在基线性能足够高的情况下也会导致性能下降。总体而言，UpstreamQA提供了一种结合显式推理和多模态理解的原理框架，可在多个场景中推进视频问答的性能和诊断透明度。
## 13. `cs.AI` - 使用专家激活模式扩展多节点混合专家推理 [PDF](https://arxiv.org/pdf/2604.23150), [HTML](https://arxiv.org/abs/2604.23150)
### Authors
Abhimanyu Bambhaniya,Geonhwa Jeong,Jason Park,Jiecao Yu,Jaewon Lee,Pengchao Wang,Changkyu Kim,Chunqiang Tang,Tushar Krishna
### Background
最先进的大型语言模型（LLMs）采用混合专家（MoE）架构来无比例地增加模型容量，而不增加每词计算量，从而在可控的成本下提供高质量的输出。然而，大规模的MoE推理本质上受到专家负载不平衡和无效的词片路由的瓶颈限制，特别是在多节点部署中，词片不一定能够路由到本地专家，从而导致显著的节点间全连接通信开销。
### Innovation
通过研究专家激活模式，我们发现了前沿MoE模型中的一些持久性特性：可变的专家负载不平衡、领域特定的专家激活（专家热度随任务类型变化）以及预填和解码专家激活之间的强相关性。基于这些发现，我们提出了一种工作负载感知的微批处理分组策略和专家放置策略，以最大化词片到目标专家的局部性，从而减少节点间通信。这些优化在多种模型和数据集上帮助减少了全连接通信数据至最多20%，从而降低了MoE解码延迟并提高了加速器利用率。
### Conclusion
这些优化在多种模型和数据集上帮助减少了全连接通信数据至最多20%，从而显著降低了MoE解码延迟并提高了加速器利用率，这为面向负载感知的工作策略提供了重要的指导意义。
## 14. `cs.AI` - 规划任务屏蔽：通过使之不可解来检测和修复规划任务中的缺陷 [PDF](https://arxiv.org/pdf/2604.07042), [HTML](https://arxiv.org/abs/2604.07042)
### Authors
Alberto Pozanco,Marianela Morales,Pietro Totis,Daniel Borrajo
### Background
大多数关于规划的研究集中在生成能实现目标的一组计划。然而，目标规定也可以用来编码一项不应发生的特性，使规划者能够识别会导致缺陷状态的路径。在这种情况下，目标可能会改变，即规划任务的目的是确保这种缺陷状态不可能发生，换句话说，就是让规划任务不可能解决。本文讨论了规划任务屏蔽问题：该问题涉及检测和修复规划任务中的缺陷。
### Innovation
本文提出了一种名为$allmin$的最优算法，该算法通过最小修改原始动作，使规划任务变得不可解，从而有效检测和修复规划任务中的缺陷。
### Conclusion
论文通过实验证明了$allmin$算法在分步骤增加规划任务规模时的性能，展示了该算法如何通过将规划任务变得不可解来有效地屏蔽系统中的缺陷。
## 15. `cs.AI` - Auditing Sabotage Bench:一个用于检测和修复ML代码中研究破坏的基准 [PDF](https://arxiv.org/pdf/2604.16286), [HTML](https://arxiv.org/abs/2604.16286)
### Authors
Eric Gan,Aryan Bhatt,Buck Shlegeris,Julian Stastny,Vivek Hebbar
### Background
随着人工智能系统越来越多地自主进行研究，对齐系统生成的结果可能会引入难以察觉的错误。为了应对这一问题，作者们提出了Auditing Sabotage Bench，这是一个用于评估审计人员检测和修复在机器学习研究代码库中破坏的能力的基准。该基准包括9个具有被破坏版本的机器学习研究代码库，这些被破坏版本会产出对比鲜明的实验结果。破坏不仅修改了具体实现细节，如超参数、训练数据或评估代码，同时保留了论文中描述的高层方法。
### Innovation
该研究创新性地提出了Auditing Sabotage Bench，这是一个专门针对审计人员检测和修复破坏的基准。基准中的被破坏代码库能够明显改变实验结果，并且破坏是通过修改具体实现细节而不是高层方法来实现的。作者还测试了先进的语言模型和辅助语言模型的人类审计者，发现它们在检测和修复破坏方面表现不佳。此外，研究结果还表明，虽然语言模型生成的破坏较弱，但仍能够避开同能力的语言模型审计者。
### Conclusion
通过释放该基准，该研究旨在支持对人工智能自主研究中监控和审计技术的研究。实验显示，当前的前沿技术和方法在检测和修复破坏方面仍存在挑战，需要进一步研究以提高其可靠性。
## 16. `cs.AI` - ClimAgent: 使用大型语言模型作为代理进行自主开放气候科学分析 [PDF](https://arxiv.org/pdf/2604.16922), [HTML](https://arxiv.org/abs/2604.16922)
### Authors
Hao Wang,Jindong Han,Wei Fan,Hao Liu
### Background
气候研究对于缓解全球环境危机至关重要。然而，多尺度数据集的加速增长和分析工具的复杂性造成了一些瓶颈，限制了科学研究的工作流程变得碎片化和劳动密集型。尽管大型语言模型（LLMs）的出现提供了大规模科学知识的潜在变革性方法，但现有探索主要局限于简单的问答任务，这些方法往往过分简化了现实生活中的挑战，忽略了专业气候学中所需的复杂物理约束和数据驱动性质。
### Innovation
为了弥合这一差距，作者提出了ClimAgent，这是一种通用的自主框架，设计用于执行跨多种气候子学科的广泛研究任务。ClimAgent通过整合统一的工具使用环境和严格的推理流程，超越了简单的检索，实现了端到端建模和分析。为促进系统评估，作者提出了ClimaBench，这是首个旨在解决现实世界气候发现问题的基准测试，包含了5个任务类别中的难题，涵盖2000年至2025年专业场景中的挑战问题。实验结果表明，ClimAgent在解决方案的严谨性和实用性方面显著优于最先进的基线，原LLM解决方案的改进率为40.21%。
### Conclusion
ClimAgent通过整合统一的工具使用环境和严格的推理流程，能够实现端到端的建模和分析，系统地评估了ClimaBench的表现，证明了其在气候科学分析中的优势。
## 17. `cs.AI` - 一种资产：通过统一转换人工智能代理框架（CAAF）确保确定性 [PDF](https://arxiv.org/pdf/2604.17025), [HTML](https://arxiv.org/abs/2604.17025)
### Authors
Tianbao Zhang
### Background
大型语言模型在安全关键工程中存在可控性差距，即使未检测到的约束违反率很低也会使系统无法部署。当前的编排模式存在阿谀奉承的合规性问题，上下文注意力衰减以及在自我纠正期间的随机振荡。
### Innovation
提出了一种统一转换人工智能代理框架（CAAF），该框架通过三个支柱从开环生成过渡到闭环故障安全确定性的工作流，分别是：（1）物理上下文防火墙下的递归原子分解；（2）将领域不变量构建成机器可读的注册表，由确定性统一断言接口强制执行；（3）带有状态锁定的结构化语义梯度，用于单调非退化。
### Conclusion
该论文提出了两个核心主张：一是工业化主张，一旦领域不变量以可执行的Harness形式被标准化，Harness将变成具有企业价值的资产，并在基础模型商品化的情况下，CAAF的可靠性可以在低成本下提供完整的本地部署架构，适用于不使用云端API的监管领域。二是CAAF的三个支柱共同解决互补的故障面，任意一个单独都无法在低成本下关闭可控性差距。论文完全在编排和工业化层面贡献了研究结果。
## 18. `cs.AI` - Agent-A Design for Dynamic CAD Models [PDF](https://arxiv.org/pdf/2604.15184), [HTML](https://arxiv.org/abs/2604.15184)
### Authors
Mitch Adler,Matthew Russo,Michael Cafarella
### Background
近年来，，研究人员已经成功地 在 在了在无约束条件下重构真实世界 的CAD造型模型。 幓的方法可以涉及 In多个反馈循环循环循环 loop的方式， 幘利用通过可视化技术反复迭代地改进模型。 虽然这些方法取得了快速的进步D，和 但是迄今为止D年尚没有任何一种方法能够在工业制造中生成复杂的3D部件组装体。 现有的方法都尽管能够捕捉部件间的动态相互互动D 但它们仅局限于机械运动D 这部分限制了它们 的应用范围。 为了解决这些问题D 该研究提出了Agent-A Design模型D 幩该该该模型通过结合了解释器道CAD系统 concurrently使用一个特殊的约束解D道(D 并利用约束求解决器来进行精确的验证验证验证验证以帧验证信号使得模型能够生成含有可具可有主动部件的33D组装体D 幔 
### Innovation
别该研究的关键创新之处在于通过结合合解解器器 (FreeCADD 和和 and D a specialized constraint solv止器（ 并利用一个专用于尺反馈的管的后 and 肭 审反馈机制D来在无约束的环境中实现成功重构了真实世界的CAD型造型模型D 幩该该模型能够在力生成含有复杂运动部件的D 幧行DD 幅3尽管之前的方法主要都是局限于机械运动的D 该方法能够实现在现现 稡重于在工业级应用D创造出具有更高级性能的和D更复杂功能的D 甘具D有更大实际应用前景D
### Conclusion
研究表明D通过结合专有的约束解决器 (FreeCADD和 and the特殊设计的动态反馈机制DAgent-A Design在了一个无约束的环境中D已经实现了生成复杂的D r3D组装体目标D由于之前的方法仅 limited能Dthur limiting机械运动D该框架提供了一个新的解决方案D使得数字化设计过程更加灵活DD和具体能够实设计出具有更复杂功能和的真实零部件D为未来的D设计制制造D提供了新的机会
## 19. `cs.AI` - 关于Masked Diffusion语言模型的推理能力 [PDF](https://arxiv.org/pdf/2510.13117), [HTML](https://arxiv.org/abs/2510.13117)
### Authors
Anej Svete,Ashish Sabharwal
### Background
文本中的掩蔽扩散模型（MDMs）为传统自回归语言模型提供了一个引人注目的替代方案。并行生成使它们非常高效，但它们的计算能力和并行性的内在限制仍不甚明朗。
### Innovation
本文通过将MDMs与有限精度对数宽度下的链式思考（CoT）和补齐循环变换器（PLTs）等成熟的推理框架联系起来，探讨了MDMs能够解决什么类型的推理问题以及它们的效率。证明了MDMs和多项式补齐的PLTs在这一点上是等价的，并且MDMs可以解决CoT增强的变换器可以解决的所有问题。此外，展示了MDMs在某些问题（包括正规语言）上比CoT变换器更高效的类别，其中并行生成可以显著提高推理速度。
### Conclusion
MDMs能够解决CoT增强变换器可以解决的所有问题，并且在某些情况下，MDMs由于其并行生成特性比CoT变换器更具效率。
## 20. `cs.AI` - 语言模型对游戏评估的评估 [PDF](https://arxiv.org/pdf/2510.10930), [HTML](https://arxiv.org/abs/2510.10930)
### Authors
Katherine M. Collins,Cedegao E. Zhang,Graham Todd,Lance Ying,Mauricio Barba da Costa,Ryan Liu,Prafull Sharma,Adrian Weller,Ionatan Kuperwajs,Lionel Wong,Joshua B. Tenenbaum,Thomas L. Griffiths
### Background
传统的评估人工智能系统的方法主要集中在解决问题上，例如通过研究模型在象棋和围棋等游戏中表现来评估它们。然而，本文指出，推理不仅仅是解决已有问题，它还涉及评估哪些问题值得解决。因此，有必要开发一种新的评估框架，专门针对评估AI系统的游戏评估能力，特别是涉及游戏的公平性和趣味性。
### Innovation
1. 引入了一种形式化的评估方法来评估这些评估。2. 利用超过100种新颖的棋盘游戏的大型数据集和超过450个人类判断，比较现代语言和推理模型与人类及符号计算代理的评估结果。3. 基于问题的计算复杂性和量化的难度，考虑了两种评估类型：评估胜利（或公平性）和趣味性。4. 发现推理模型在游戏评估方面的评价与人类评价更为一致，但当模型接近博弈论最优时，其与人类数据的契合度下降。此外，在评估趣味性时发现了“锯齿状”现象，这与量化这一问题的难度更大有关。
### Conclusion
推理模型在评估游戏的问题上有高度的可变性和不可预测性资源使用趋势，这强调了在语言和推理模型中植入更多资源有理的元推理的必要性。
## 21. `cs.AI` - Cataract-LMM 大规模多源多任务深度学习基准数据集用于手术视频分析 [PDF](https://arxiv.org/pdf/2510.16371), [HTML](https://arxiv.org/abs/2510.16371)
### Authors
Mohammad Javad Ahmadi,Iman Gandomi,Parisa Abdi,Seyed-Farzad Mohammadi,Amirhossein Taslimi,Mehdi Khodaparast,Hassan Hashemi,Mahdi Tavakoli,Hamid D. Taghirad
### Background
计算机辅助手术系统的开发依赖于大规模的标注数据集。现有的白内障手术资源在多样性及标注深度方面不足，无法有效训练具有广泛适应性的深度学习模型。为解决这一问题，本研究收集了来自两家手术中心的3000段白内障手术视频，并提供不同层次的标注，包括手术阶段时间标注、仪器和解剖结构实例分割、仪器-组织交互跟踪以及基于ICO-OSCAR和GRASIS的技能评分。
### Innovation
本研究提出了一个包含四个标注层次的大规模白内障手术视频数据集，用于解决现有数据集在多样性和标注深度方面的不足。通过这个数据集，研究人员可以进行手术工作流程识别、场景分割、仪器-组织交互跟踪以及自动化技能评估等多任务的基准测试。此外，通过领域适应方法，研究人员还建立了阶段识别和实例分割的基础标准。
### Conclusion
该多源多任务数据集和标注公开发布，促进了各手术步骤分析、场景理解和基于技能的培训研究中广泛适应性多任务模型的开发。
## 22. `cs.AI` - POPI：通过优化自然语言偏好推断个性化LLMs [PDF](https://arxiv.org/pdf/2510.17881), [HTML](https://arxiv.org/abs/2510.17881)
### Authors
Yizhuo Chen,Xin Liu,Ruijie Wang,Zheng Li,Pei Chen,Changlong Yu,Qingyu Yin,Priyanka Nigam,Meng Jiang,Bing Yin
### Background
大型语言模型（LLMs）通常与人群级别的偏好对齐，尽管不同用户之间存在显著的个体差异。POPI提出了一个用户级别的个性化框架，通过一个自然语言接口将问题分为两部分：共享的推理模型将异质用户信号压缩成简洁的偏好摘要，共享的生成器根据该总结生成个性化响应。这两个组件都在统一的偏好优化目标下训练，其中强化学习处理非可微的推理步骤。这种目标分解成生成器近似误差和摘要的有用信息性，揭示了一个单一的损失如何同时推动准确的生成和信息性的总结。由于接口是自然语言，学习到的摘要可以每用户推断一次并复用于不同的生成器——包括冻结的、黑盒的商业API。
### Innovation
POPI提出了一种用户级别的个性化框架，通过一个自然语言接口将问题分为共享的推理模型和共享的生成器两部分。推理模型将异质用户信号压缩成简洁的偏好摘要，生成器根据该总结生成个性化响应。这一体系结构使得学习到的摘要可以在不同生成器之间复用，适用于包括冻结的、黑盒的商业API。两部分都在统一的偏好优化目标下训练，结合了强化学习处理非可微的推理步骤。这不仅提高了生成的准确性和总结的信息性，还显著减少了上下文负担。
### Conclusion
POPI方法在四个个性化基准测试中，普遍提高了个性化质量，同时减少了上下文负担，有时甚至减少了一个数量级。
## 23. `cs.AI` - 从优化到预测：基于Transformer的路径流量估计在交通分配问题中的应用 [PDF](https://arxiv.org/pdf/2510.19889), [HTML](https://arxiv.org/abs/2510.19889)
### Authors
Mostafa Ameli,Sulthana Shams,Van Anh Le,Alexander Skabardonis
### Background
交通分配问题对交通流量分析至关重要，传统上通过在均衡原则下的数学规划方法来解决。由于OD对的数量与复杂性的非线性增长，这些方法在大规模网络中变得难以承受。本研究介绍了一种新的数据驱动方法，采用深度神经网络，特别是利用Transformer架构，直接预测均衡路径流量。通过关注路径级交通分配，所提出的模型捕捉了OD对之间的复杂关联，提供了一种与传统链路级方法相比更为详细和灵活的分析。基于Transformer的模型大幅减少了计算时间，并且在需求和网络结构发生变化时无需重新计算即可适应。
### Innovation
引入了基于Transformer的深度神经网络模型，用于直接预测路径流量。该模型关注路径级交通分配，捕捉OD对之间的复杂关联，能够更灵活地适应变化需求和网络结构，无需重新计算。该模型显著加速了交通分配问题的解决过程，提高了在多类网络中估计路径级交通流量的准确性和效率。
### Conclusion
本研究通过使用基于Transformer的深度神经网络模型，在曼哈顿样网络、Sioux Falls网络和东部马萨诸塞网络中进行了数值实验，展示了所提模型相较于传统优化方法的显著优势。模型能够快速估算多类网络中的路径级交通流量，同时能高效适应需求和网络条件的变化，支持交通管理和快速'假设'分析，为增强交通规划和政策制定提供便利。
## 24. `cs.AI` - 通过贝叶斯校准实现罕见关系数据的自我增强可控合成 [PDF](https://arxiv.org/pdf/2604.16817), [HTML](https://arxiv.org/abs/2604.16817)
### Authors
Chongsheng Zhang,Hao Wang,Zelong Yu,Esteban Garces Arias,Julian Rodemann,Zhanshuo Zhang,Qilong Li,Gaojuan Fan,Krikamol Muandet,Christian Heumann
### Background
在实际应用中，数据往往不平衡，而数据合成可以有效缓解稀有类别的数据稀缺问题。虽然LLMs（大型语言模型）已显著改善了文本生成，但它们在合成关系/结构化表格数据方面的应用却尚未得到充分探索。现有方法缺乏有效的反馈机制来指导LLMs在生成过程中持续优化数据质量。
### Innovation
本文提出了RDDG（Relational Data generator with Dynamic Guidance，具有动态指导的关系数据生成器），这是一种统一的学习框架，通过渐进的链式思考步骤生成表格数据，以提升下游不平衡分类性能。RDDG首先通过核心样本选择确定代表性样本，然后利用上下文学习发现核心集内属性的内在模式和关联，进而生成表格数据并保持上述约束。此外，它还引入了一个自强化反馈机制，能够自动评估生成数据的质量，并在整个生成过程中实现持续的质量优化。
### Conclusion
在多个真实和合成数据集上的实验结果显示，RDDG在数据准确性和下游不平衡分类性能方面均优于现有方法。代码可在以下链接获取：this https URL。
## 25. `cs.AI` - PRISM: 探测LLM幻觉中的推理、指令和源记忆 [PDF](https://arxiv.org/pdf/2604.16909), [HTML](https://arxiv.org/abs/2604.16909)
### Authors
Yuhe Wu,Guangyu Wang,Yuran Chen,Jiatong Zhang,Yutong Zhang,Yujie Chen,Jiaming Shang,Guang Zhang,Zhuang Liu
### Background
随着大型语言模型（LLMs）从对话助手演变为能够处理复杂任务的代理，它们正越来越多地部署在高风险领域。然而，现有的基准测试主要依赖于混合查询和事后评估，以及输出级别的评分，这虽然可以衡量幻觉的严重程度，但缺乏对幻觉在生成管道中具体出现的位置和原因的深入洞察。
### Innovation
该研究重新定义幻觉评估为诊断性问题，并提出了PRISM，这是一种控制基准，将幻觉分解为四个维度：知识缺失、知识错误、推理错误和指令遵循错误，所有这些都基于生成的三个阶段（记忆、指令和推理）。PRISM包含9,448个实例，涵盖了65个任务，并支持细致、阶段感知的诊断评估。通过对24种主流开源和专有LLMs的评估，发现指令遵循、记忆检索和逻辑推理之间存在一致的权衡，表明缓解策略往往在特定维度上提高效果的同时牺牲了其他维度。
### Conclusion
希望PRISM能够为理解LLMs幻觉的具体机制提供框架，最终加速可信赖大型语言模型的发展。
## 26. `cs.AI` - 训练-推理输入对齐优于框架选择在纵向视网膜图像预测中 [PDF](https://arxiv.org/pdf/2604.16955), [HTML](https://arxiv.org/abs/2604.16955)
### Authors
Liyin Chen,Nazlee Zebardast,Mengyu Wang,Tobias Elze,Jason I. Comander
### Background
纵向图像在疾病进展预测中对于临床决策和试验设计都非常有用。近期的方法越来越注重增加生成模型的复杂性，但这种复杂性是否必要仍不清楚。该研究提出，生成复杂性应与任务前向后概率中可预测部分的熵相匹配，并且在所有情况下都需要在训练和推理之间的输入对齐。通过分析原始图像对和基于随机模型的后验集中度，研究人员能够在建模框架选择前评估任务所需的复杂性。
### Innovation
提出了在建模框架选择前评估任务所需复杂性的方法，包括基于原始图像对的数据任务熵分析和基于随机模型的后验集中度分析。研究还通过纵向视网膜图像数据验证了框架的相对效果，展示了在成像变异大于疾病进展时，确定性回归模型与更复杂的随机替代方案相比至少具有同等效果。
### Conclusion
训练和推理之间的输入对齐在纵向视网膜图像预测中的收益显著，而不同的建模框架之间的选择没有产生临床显著差异。当疾病进展速度慢于成像变异时，确定性回归模型的效果甚至优于更复杂的随机替代方案。
## 27. `cs.AI` - DanceCrafter: 通过编舞语法实现细粒度文本驱动控制舞动生成 [PDF](https://arxiv.org/pdf/2604.18648), [HTML](https://arxiv.org/abs/2604.18648)
### Authors
Hang Yuan,Xiaolin Hu,Yan Wan,Menglin Gao,Wenzhe Yu,Cong Huang,Fei Xu,Qing Li,Christina Dan Wang,Zhou Yu,Kai Chen
### Background
文本驱动的可控制舞动生成领域尚未得到充分探索，主要是由于高质量数据集的严重稀缺和描述复杂舞蹈编排的固有难度。由于其复杂的空间动力学、强烈的定向性和各部位运动的高解耦性，编舞尤为具有挑战性。
### Innovation
本文提出了Choreographic Syntax，一种新颖的理论框架及特定注释系统。基于此语法，结合专业舞蹈档案和高保真动作捕捉数据，构建了迄今最精细的舞蹈数据集DanceFlow。此外，还提出了DanceCrafter，基于Momentum Human Rig构建的专门化运动转子，通过连续流形运动表示和混合归一化策略克服优化稳定性问题。设计了解剖学感知损失，显式调节各部位的高解耦特性。
### Conclusion
这些改进使DanceCrafter能够在高质量、稳定地生成复杂舞动序列方面表现出卓越性能，并通过广泛的评估和用户研究证明了其在运动质量、细粒度可控制性和生成自然度方面的先进性。
## 28. `cs.AI` - 超越似然位移的解解纠缠偏好优化动力学 [PDF](https://arxiv.org/pdf/2604.18239), [HTML](https://arxiv.org/abs/2604.18239)
### Authors
Wei Chen,Yubing Wu,Junmei Yang,Delu Zeng,Qibin Zhao,John Paisley,Min Chen,Zhou Wang
### Background
偏好优化广泛应用于使将对大型语言模型与人类偏好对齐。。背景。主要在大规模语言模型的训练过程中，，。广泛使用偏好优化来确保模型生成的响应与人类偏好相一致的过程。。此过程中多项决策目标被用于使用这些模型生成响应，并在实际应用中发现这些决策方法会抑制负面响应和正面响应,导致类似似然位移的现象)，这是指训练过程中选择的响应与未选择的响应之间相似的概率位移现象。这现象导致了训练过程中未能准确反映人类的真实偏好从而优化效果受到限制也没有一种普适机制能够全面处理这个问题。
### Innovation
本文通过引入统一的偏好优化激励分分激励-强度分解来揭示不同的决策目标在局部更新方向上相同而仅在数值系数上不同从而搭建桥梁解决这一现有问题面对的的问题进而通过解析受选择的受选择和拒绝的似然比之间的动力学来引入解解纠缠边界(即JB)和一种简单受制方法来刻画训练过程可能够避免似然位移且保持获胜路径能在选择失败者在维护胜者之后的初始瞬态从而再现了一种拟即插即即即的奖励校准 
### Conclusion
有限结果和表明奖励校准能够引导训练趋向更解解纠缠且的提高下游性能的方法而实现一种更有效的模型训练方法。
## 29. `cs.CL` - Kuai Summary Attention 技术报告 [PDF](https://arxiv.org/pdf/2604.24432), [HTML](https://arxiv.org/abs/2604.24432)
### Authors
Chenglong Chu,Guorui Zhou,Guowang Zhang,Han Li,Hao Peng,Hongtao Cheng,Jian Liang,Jiangxia Cao,Kun Gai,Lingzhi Zhou,Lu Ren,Qi Zhang,Ruiming Tang,Ruitao Wang,Xinchen Luo,Yi Su,Zhiyuan Liang,Ziqi Wang,Boyang Ding,Chengru Song,Dunju Zang,Hui Wang,Jiao Ou,Jiaxin Deng,Jijun Shi,Jinghao Zhang,Junmin Chen,Lejian Ren,Minxuan Lv,Qianqian Wang,Qigen Hu,Shiyao Wang,Siyang Mao,Tao Wang,Xingmei Wang,Zhixin Ling,Ziming Li,Zixing Zhang
### Background
长上下文能力已成为下一代大规模语言模型最重要的迭代方向之一，特别是在语义理解/推理、代码代理智能和推荐系统中。然而，标准的 softmax 注意机制的时间复杂度与序列长度成平方关系，在长上下文设置中这会导致显著的开销，使极长序列的训练和推理成本急剧恶化。现有的解决方案通过两种技术途径缓解这个问题：(i) 减少每层的 KV 缓存，如头部级别的压缩 GQA 和嵌入维度级别的压缩 MLA，虽然 KV 缓存与序列长度的比例关系仍然保持线性。(ii) 采用与 KV 缓存友好的架构，如局部注意力 SWA 和线性核 GDN，但这通常涉及 KV 缓存与长上下文建模效果之间的权衡。
### Innovation
我们提出了一个新的中间路径，即通过特定比率 k 进行语义级压缩，保持 KV 缓存与序列长度的线性关系。Kuai Summary Attention (KSA) 是一种新的注意力机制，通过将历史上下文压缩成可学习的摘要令牌来降低序列建模成本。
### Conclusion
Kuai Summary Attention (KSA) 通过特定比率 k 计算总结令牌，保持可接受的内存成本的同时，完整、参考性且可解释地保留了长距离依赖，展现了在长上下文理解方面的潜力，从而优化了训练和推理的成本。
## 30. `cs.CL` - 你能让它听起来像你吗？通过后编辑调整LLM生成文本的个人风格 [PDF](https://arxiv.org/pdf/2604.24444), [HTML](https://arxiv.org/abs/2604.24444)
### Authors
Connor Baumler,Calvin Bao,Huy Nghiem,Xinchen Yang,Marine Carpuat,Hal Daumé III
### Background
随着大型语言模型（LLMs）在写作任务中的应用越来越广泛，用户可能在考虑保留个人风格时犹豫不决。在某些情况下，用户可能会对LLM生成的草稿或翻译进行后编辑以实现与自身风格的匹配。然而，目前尚不清楚在什么程度上用户可以成功调整LLM生成文本以体现出自己的个人风格。本研究通过让用户对LLM生成的文本进行后编辑来进行探讨。
### Innovation
本研究通过一项预先登记的在线研究（包含81名参与者），探索了用户在个人风格重要的写作任务中对LLM生成文本进行后编辑的效果。研究中使用了基于嵌入式的风格相似性度量方法，发现后编辑提高了文本与用户自身未加编辑文本的相似度，但仍然比未加干预的人类文本风格更加单一。此外，对于风格的感知与模型测量的风格相似度之间存在差异，用户往往会认为后编辑过的文本反映了他们的个人风格，即使这些文本仍然保留了可被检测到的语言模型的风格痕迹。
### Conclusion
这项研究表明，在用户对LLM生成的文本进行后编辑后，文本在风格上与用户自身未编辑的文本更加接近，但依然与未加干预的人类文本的风格多样性存在差距。此外，用户常常会高估他们在风格上与自己进一步接近的程度，这表明在实际应用中需要更细致地理解和处理个人风格与模型生成风格的差异。
## 31. `cs.CL` - Search-R: Structured Entity-Aware Retrieval with Chain-of-Reasoning Navigator for Multi-hop Question Answer on [PDF](https://arxiv.org/pdf/2604.24515), [HTML](https://arxiv.org/abs/2604.24515)
### Authors
Yuqing Fu,Yimin Deng,Wanyu Wang,Yuhao Wang,Yejing Wang,Hongshi Liu,Yiqi Wang,Xiao Han,Maolin Wang,Guoshuai Zhao,Yi Chang,Xiangyu Zhao
### Background
Multi多解析 Multi-hop Question on on (MHQA) 的目标是回答需要多 大行多多步推理的问题。。。..现有方法主要依赖于 基于 基于 催.prompt方法来生成推理路径，进而与传统稀疏和密集检索相结合以产生最终答案。. 熄个过程中，，姜路径的生成往往 on处理 上 on由于这一过程的普遍性随机性性,结果性上的阻碍有效的推理生成， on.并且检索过程依赖于知识匹配基 on 的相似度分分数而不能评价结果的实际实用性 on on.这导致了不可获取的同信息的同 homogenous on 且无用使用价值。
### Innovation
1个创新的关键是提出了 Structured Entity-Aware Retrie on with on with Chain-of-Reasoning Navigator framework， named 这称为 Se SEARCH-R on on. on..端实现了 end-on 瞒 生成强大的子行一步数推理导航器，通过对-ne on-line on 浮 tune 的Llama3 on8B进行 on.，并方改进了推理分解机制 on on 一上手一步地解 尅同同时集设计了基于依赖关系的检索方法来 on 量量 于量地评估获取信息的实际贡献 on on on实 on个框架已经通过在三个不同-hop on 数据集上得到了验证验证 on on其证明了处理多 on-hop on on on的有效性。
### Conclusion
 on究证实了 Search--R on对于解决多-hop on 的有效性能 on as这一 硬件 和 and数据集可面 on on on on了时该 鈦在 on上述三个挑战-hop on 数据集进行了广泛的验证验证 on w表明该个框架在多-hop on on on on处理上方面具有显著的优势 on on on on且证明了通过结合结 entity on意识检索与 on 一个链式的推理导航器 on可以显著优化改进 on-hop on的答能.
## 32. `cs.CL` - 大型语言模型能否成为历史学家？通过中国科举系统评估大型语言模型的历史研究能力 [PDF](https://arxiv.org/pdf/2604.24690), [HTML](https://arxiv.org/abs/2604.24690)
### Authors
Lirong Gao,Zeqing Wang,Yuyan Cai,Jiayi Deng,Yanmei Gu,Yiming Zhang,Jia Zhou,Yanfei Zhang,Junbo Zhao
### Background
大型语言模型（LLMs）在文本处理等历史任务上已有广泛应用，但在专业级别的历史推理方面尚未得到充分探索。现有的基准主要评估基本知识广度或词汇理解能力，而未能捕捉到诸如证据推理等高层次的研究技能。为填补这一空白，研究人员引入了ProHist-Bench基准，该基准基于中国科举制度，涵盖了东西方政治、社会和思想历史超过1300年的方面。
### Innovation
ProHist-Bench是一个创新性的基准测试，通过深入多学科合作开发，包含8个朝代的400个具有挑战性的、由专家编写的题目，以及10,891个细粒度的评估标准。研究通过严格评估18个大型语言模型，揭示了复杂历史研究问题方面的显著能力差距，即使最先进的大型语言模型也难以应对。
### Conclusion
ProHist-Bench旨在促进领域特定逻辑推理的大型语言模型的发展，推动计算机历史研究，进一步探索大型语言模型的潜在能力。
## 33. `cs.CL` - 长上下文感知复用：混合LLM扩展的新前沿 [PDF](https://arxiv.org/pdf/2604.24715), [HTML](https://arxiv.org/abs/2604.24715)
### Authors
Parsa Ashrafi Fashi,Utkarsh Saxena,Mehdi Rezagholizadeh,Aref Jafari,Akash Haridas,Mingyu Yang,Vansh Bhatia,Guihong Li,Vikram Appia,Emad Barsoum
### Background
混合序列模型通过结合高效Transformer组件和线性序列建模块是纯Transformer的一种有前景的替代方案，但大多数模型仍然需要从头开始预训练，因此无法利用现有的Transformer检查点。本文研究了将预训练的Transformer大语言模型转换为混合架构作为一种实用途径，旨在保持短上下文质量并提升长上下文能力。HyLo（HYbrid LOng-context）解决方案利用了架构适应性、高效Transformer组件、Multi-Head Latent Attention (MLA)、线性块如Mamba2或Gated DeltaNet以及分阶段长上下文训练和教师指导蒸馏，实现了有效的训练后长上下文扩展和更少的KV缓存内存使用。
### Innovation
提出了HyLo（HYbrid LOng-context）解决方案，该方案结合了架构适应、高效Transformer组件、Multi-Head Latent Attention (MLA) 和线性块（Mamba2 或 Gated DeltaNet），并采用了分阶段的长上下文训练和教师指导蒸馏，从而实现了高效的训练后长上下文扩展，减少了超过90%的KV缓存内存使用，使预填充和解码达到200万标记。HyLo在1亿和3亿规模设置下表现出稳定的短上下文和长上下文性能，在长上下文评估如RULER中显著优于现有的混合模型基准。特别是在规模相似的情况下，HyLo-Qwen-1.7B在仅使用10亿标记训练的情况下，表现出显著优于使用400亿标记训练的JetNemotron的性能。
### Conclusion
HyLo 在1亿和3亿规模的设置中都能持续呈现出色的短上下文和长上下文性能，并在长上下文评估如RULER上明显优于最先进的混合模型基准。此研究为混合LLM的扩展开辟了一条新的途径。
## 34. `cs.CL` - AeSlides: 通过可验证奖励激励LLM幻灯片生成中的美观布局 [PDF](https://arxiv.org/pdf/2604.22840), [HTML](https://arxiv.org/abs/2604.22840)
### Authors
Yiming Pan,Chengwei Hu,Xuancheng Huang,Can Huang,Mingming Zhao,Yuean Bi,Xiaohan Zhang,Aohan Zeng,Linmei Hu
### Background
大型语言模型（LLMs）在生成幻灯片方面表现出强大的潜力，特别是在幻灯片生成任务中。然而，传统的幻灯片生成面临一项基本挑战：尽管生成过程主要以文本为中心，但其质量却由视觉美学所决定。这种模态上的差异导致现有模型经常生成具有非理想的布局的幻灯片。现有解决方案通常依赖于重的视觉反馈，这产生高昂的推理成本但效果有限；或者通过大规模数据集进行微调，尽管这种方法仍提供有限的间接美学监督。相比之下，明确使用美学原则作为监督的方法尚未得到探索。
### Innovation
在本研究中，我们提出了AeSlides，这是一种基于强化学习的框架，利用可验证奖励进行美观布局监督以提升幻灯片生成质量。我们设计了一系列详细构造的可验证度量标准，以量化幻灯片布局质量，准确、高效且成本低廉地捕获关键的布局问题。利用这些可验证的基础度量，我们开发了一个基于GRPO的强化学习方法，直接优化幻灯片生成模型以产生审美一致的布局。
### Conclusion
AeSlides使用GLM-4.7-Flash进行5千次提示的训练，将长宽比的合规性从36%提高到85%，减少空白区域44%，元素碰撞43%，视觉不平衡28%。进一步的人类评估表明，幻灯片的整体质量得到了显著提高，评分从3.31提高到3.56（+7.6%），超越了基于模型奖励优化和基于视觉反馈的模型方法，并且甚至超越了Claude-Sonnet-4.5。这些结果表明，这种可验证的美学框架提供了一种高效且可扩展的方法，以使幻灯片生成对齐于人类的审美偏好。我们的仓库可在以下链接获得：this https URL.
## 35. `cs.CL` - In-Sync: Adaptation of Speech aware large large models for ASR with word-level timestamp predictions [PDF](https://arxiv.org/pdf/2604.22817), [HTML](https://arxiv.org/abs/2604.22817)
### Authors
Xulin Fan,Vishal Sunder,Samuel Thomas,Mark Hasegawa-Johnson,Brian Kingsbury,George Saon
### Background
近期近年来，， 随着语音识别技术的进步，，， 语音感知的大型语言模型与强大的强声学编码器结合得 让系统能够超越简单的转字转录, 花费更大的能量进行更多的响应。。
### Innovation
我们的研究提出了一种新的方法,将现存的语音感知的语言模型直接预测字级别的时间戳。并通过引入一组新的轻小型动作机制增强了对齐稳健性同时保持了识别质量。这些方法在多个数据集中表明能够提升时间戳的准确性以及总体AS说话者识别（ASSR）的表现 ￯f
### Conclusion
这项工作展示了一种高效和统一的方式来实现语音识别并对齐预测 当其中时间戳的精度起到了关键作用。
## 36. `cs.CL` - 一个大规模跨学科的系统综述语料库 [PDF](https://arxiv.org/pdf/2604.22864), [HTML](https://arxiv.org/abs/2604.22864)
### Authors
Pierre Achkar,Tim Gollub,Arno Simons,Harrisen Scells,Martin Potthast
### Background
现有系统综述基准要么规模有限，要么学科覆盖面窄，部分集合只有少量主题，另一些则主要针对生物医学研究。目前缺乏一个全面涵盖所有学科的大规模综合系统综述资源。
### Innovation
该研究通过Webis-SR4ALL-26语料库，提供了大规模、跨学科的301,871篇系统综述，覆盖OpenAlex涵盖的所有科学领域。使用多阶段预处理管道，将综述与OpenAlex元数据和参考文献列表链接起来，并提取明确报告的相关结构化方法学。这些方法学包括报告的搜索策略（布尔查询或关键词列表），并将其规范化为可执行的近似值，以及纳入和排除标准。层叠结构支持跨领域验证检索与筛选组件、针对评审参考列表的基准测试，训练和评估综述内容提取方法，以及跨学科和时间的系统综述实践的比较元科学分析。
### Conclusion
通过在OpenAlex上执行规范化搜索策略并与解决的参考列表进行比较，报告大规模基准检索信号。并发布语料库、预处理管道，以及用于提取验证和检索演示的代码。
## 37. `cs.CL` - 大型预训练训练模型赋能自动化数据抽取以支持材料信息学 [PDF](https://arxiv.org/pdf/2604.22938), [HTML](https://arxiv.org/abs/2604.22938)
### Authors
Zhanzhao Li,Kengran Yang,Qiyao He,Kai Gong
### Background
材料驱动的材料发现潜力受限于缺乏大量高质量且易于访问的实验数据集。现有的研究表明，大规模预训练模型在自动化提取和结构化无序科学文献中的通用和大高度数据对于不同类型组的组分堆性特性表现出稳健的性能,并且能够快速提取高质量的数据记录且具有较高的准确度 
### Innovation
本文引入了一种可用于从无结构科学文献中通用自动化提取和和结构化并对大规模预训练模型进行通用的方法提提出了一种能够应对不同强大的且资源丰富的数据集集在分布内准确性和分布在外准确性的拓展方面突出重要性保证了不同领域时能够快速构建出可可的基础设施以加速材料信息学的发展。
### Conclusion
本文提出的方法能够适应于各种领域且资源丰富 
## 38. `cs.CL` - 培训通用自动化红队模型 [PDF](https://arxiv.org/pdf/2604.23067), [HTML](https://arxiv.org/abs/2604.23067)
### Authors
Aishwarya Padmakumar,Leon Derczynski,Traian Rebedea,Christopher Parisien
### Background
自动化方法用于对LLM进行红队测试是识别静态基准无法涵盖的LLM漏洞的重要工具，能进行更全面的探测。它们还可以针对每个特定的LLM发现其特有的弱点。当前大多数自动化红队方法集中在解决安全性和内容审核方面的问题，因此使用内容安全模型作为评估器，优化绕过这些模型，但在其他未被这些模型捕捉的对抗性目标上未进行测试。
### Innovation
提出了一个培训红队模型的管道，该模型可以泛化到任意的对抗性目标，包括未直接训练的目标，并且不需要依赖在训练时间存在预设的评估器。通过这种方法微调小型模型（如Qwen3-8B），结果表明其生成跨领域对抗目标攻击的能力得到了显著提升。
### Conclusion
训练使用此管道的小型模型（如Qwen3-8B）能够显著提高它们在适应不同对抗性目标时的能力。
## 39. `cs.CL` - 从单一危险信号中发现能动安全性规范 [PDF](https://arxiv.org/pdf/2604.23210), [HTML](https://arxiv.org/abs/2604.23210)
### Authors
Víctor Gallego
### Background
本文探讨了大型语言模型（LLM）是否能仅通过经验发现隐藏的安全目标。背景指出，现有的标准LLM反思方法依赖于丰富的文本反馈，而本文提出的EPO-Safe框架可以通过接收稀疏的二进制危险警告和反思自然语言行为规范来使LLM学习安全行为。
### Innovation
本文引入了EPO-Safe框架，这是一种通过经验优化安全行为的框架。EPO-Safe的独特之处在于，它利用了严格有限的信号（即每个时间步只有一个危险警告位）来学习安全行为，并在这种结构化、低维度的环境中展现了LLM能够进行安全推理的能力。此外，研究还发现，仅基于奖励反馈的反思反而会削弱安全性，这意味着在反射过程中必须引入专门的安全通道来发现隐藏的约束。
### Conclusion
研究在五个AI安全网格世界和五个文本场景中评估了EPO-Safe的表现，发现安全行为在1-2轮（5-15个回合）内被发现，并生成了可读的行为规范，这些规范能够准确解释危险（如“X个单元格方向性危险：从北边进入危险”）。还发现，即使在高比例的非危险步骤中出现虚假警告，平均而言，安全性能下降了15%，但这种抗噪能力取决于具体环境，因为跨回合的反射能够自然地过滤不一致的信号。每个进化出的规范都作为一个可审计的行为规则集，通过互动发现，而不是由人类作者编写，类似于Constitutional AI中的规则集。
## 40. `cs.CL` - 基音-时域调制表示框架用于人类模仿口述的检测 [PDF](https://arxiv.org/pdf/2604.23241), [HTML](https://arxiv.org/abs/2604.23241)
### Authors
Khalid Zaman,Masashi Unoki
### Background
人类模仿的语音比人工智能生成的语音对人类听觉和自动检测系统提出了更大的挑战。尽管人工智能生成的语音通常包含失真、过度平滑的频谱或机器人特征，人类模仿的语音保留了更高的自然度，使得基于传统声学或倒谱特征的模仿语音伪造检测更加困难。
### Innovation
本文提出了一种基于听觉感知的频谱-时域调制（Spectro-Temporal Modulation，STM）表示框架，用于人类模仿的语音检测。STM表示基于两种耳蜗滤波器模型提取，即伽马音滤波器（GTFB）和伽马对数滤波器（GCFB），这些模型在时间和频率轴上捕捉语音信号的动态变化。
### Conclusion
实验结果显示，基于STM的表示形式在人类模仿语音检测中具有显著效果，与人类听觉性能接近。此外，级段化STM表示形式表现更佳，甚至超越了人类的感知性能。研究结果表明，基于感知的频谱-时域建模对检测模仿语音威胁和提高语音认证鲁棒性具有巨大的潜力。
## 41. `cs.CL` - 为了校准大语言模型推理的边距监督过程 [PDF](https://arxiv.org/pdf/2604.23333), [HTML](https://arxiv.org/abs/2604.23333)
### Authors
Liaoyaqi Wang,Chunsheng Zuo,William Jurayj,Benjamin Van Durme,Anqi Liu
### Background
利用强化学习（RL）扩展测试时的计算能力已成为提升大型语言模型（LLM）推理能力的有效途径。然而，基于结果的奖励机制往往会促使模型过度自信，导致产生幻觉、不可靠的置信度控制以及不必要的计算资源分配。
### Innovation
引入了一种名为RLCM（RL with Confidence Margin）的新颖校准感知强化学习框架，通过在中间预算完成任务过程中引入边际提升的过程奖励，同时优化正确性和置信度可靠性。RLCM鼓励在单个推理轨迹中扩大正确步骤和错误步骤之间的置信度差距，而不只是将置信度与正确性概率对齐。
### Conclusion
通过使用校准后的置信度信号，所提出的模型能够更有效地实施配准概率风险控制和具有置信度加权的聚合，从而在保持或提高准确性的同时显著提高校准效果。
## 42. `cs.CL` - 轻量级且生产级别的PDF视觉元素解析 [PDF](https://arxiv.org/pdf/2604.23276), [HTML](https://arxiv.org/abs/2604.23276)
### Authors
Meizhu Liu,Yassi Abbasi,Matthew Rowe,Michael Avendi,Paul Li
### Background
PDF文档中包含关键的视觉元素如图表、表格和表单，准确提取这些元素对于文档理解和多模态增强生成（RAG）至关重要。然而，现有的PDF解析器经常遗漏复杂的视觉元素，提取冗余的数据（例如水印、标志），生成碎片化的元素，并且往往无法可靠地将标题与相应的元素关联起来，这些都会降低下游检索和问答表现。
### Innovation
本文提出了一个轻量级且适合生产的PDF解析框架，该框架通过结合空间启发法、布局分析和语义相似性来准确检测视觉元素和标题关联。该模型在基准数据集和内部产品数据上实现了至少96%的视觉元素检测准确率和93%的标题关联准确率。在预处理步骤中与多模态RAG结合使用时，相比于最先进的解析器和大型视觉-语言模型，在内部数据和MMDocRAG基准测试上表现出显著更好的性能，同时将延迟减少了超过两倍。
### Conclusion
本文提出的系统已在具有挑战性的生产环境中部署，具有显著的性能和延迟优势。
## 43. `cs.CL` - 超节点和光环：大型语言模型前馈层中的损失关键节点 [PDF](https://arxiv.org/pdf/2604.23475), [HTML](https://arxiv.org/abs/2604.23475)
### Authors
Audrey Cherilyn,Houman Safaai
### Background
研究变压器前馈网络（FFN）中各个通道在损失敏感度组织上的重要性。通过基于激活梯度二次矩的费舍尔样式的损失代理方法，发现损失敏感性在每层中集中在少量通道上。
### Innovation
引入了‘超节点’的概念，指出这些超节点在每层的前1%通道中占比高达58.7%，并且这些超节点与激活异常值重叠程度不高，不能通过简单的激活强度或权重范数来解释。研究表明，超节点周围的非超节点通道在某些情况下与核心展示出更强的冗余性，提出了用一束结构化FFN剪枝作为诊断测试这一组织的方法。
### Conclusion
通过0.5稀疏的结构化FFN剪枝实验，发现剪枝大量超节点会导致性能急剧下降。保护超节点核心的变体表现较好，SCAR-Prot变体效果最强，相较于Wanda-channels下降较少。该结果表明大型语言模型FFN中存在一个小的核心学习超节点，并确保这一核心的完整性对于可靠的结构化剪枝非常重要。
## 44. `cs.CL` - 硅哲学家中的异质性崩塌 [PDF](https://arxiv.org/pdf/2604.23575), [HTML](https://arxiv.org/abs/2604.23575)
### Authors
Yuanming Shi(Adobe Inc.),Andreas Haupt(Stanford University)
### Background
硅样本（如大型语言模型）越来越多地被用作低成本的人类决策替代品，并且已有研究证明它们能够高度忠实地复现人群的整体意见。本文则探讨了这些模型在哲学这一与对齐（alignment）相关的领域中的表现，特别是它们如何系统地减少异质性。
### Innovation
使用来自PhilPeople和PhilPapers的数据，评估了大型语言模型在复现个体哲学立场以及保存哲学领域间跨问题相关结构方面的表现。研究发现，这些模型在哲学判断上存在过度相关性，从而制造出虚假的一致性。这种现象部分归因于专家效应，即模型在某种程度上假设领域专家持有非常相似的哲学观点。此外，研究还通过DPO微调影响研究和通过PhilPapers 2020民意调查验证结果来探讨这些发现的稳健性。
### Conclusion
本文讨论了这些发现对对齐、评估以及硅样本作为人类判断替代品的使用的影响。研究中的代码可以在[此链接]找到。
## 45. `cs.CL` - AgentEval：追踪错误传播的递阶结构分步骤评估框架 [PDF](https://arxiv.org/pdf/2604.23581), [HTML](https://arxiv.org/abs/2604.23581)
### Authors
Dongxin Guo,Jikun Wu,Siu Ming Yiu
### Background
当前的评估方法，如端到端结果检查和临时的经验检查路径遍历，系统地遮蔽了真实世界中主导错误预算的中间错误。这种盲区限制了对中间错误的识别和纠正，进而影响系统性能。
### Innovation
提出了AgentEval框架，将代理执行形式化为评估有向无环图(DAG)，每个节点携带质量度量由校准过的LLM法官（GPT-4o）分类，通过分层级的失败分类法（3级分类，21个子类别），并链接到上游依赖项以实现自动根本原因归因。实验区分了DAG基础依赖建模的影响，以及与传统的分步骤评估（在相同的法官和标准下）相比，检测失败召回率提高了22个百分点，根本原因准确性提高了34个百分点。
### Conclusion
AgentEval在三个生产工作流中显示出了2.17倍更高的失败检测召回率，比端到端评估高出两倍，Kappa一致率为0.84，且在81%的人类天花板下达到72%的根本原因准确性。在不同系统上的评估确认了其转移性，且通过CI/CD集成的回归测试，18名工程师发现了23个预发行回归，降低了根本原因识别时间，并且成功地减少了两个流程中的故障率。
## 46. `cs.CL` - Talker-T2AV：联合生成口说视频音频的自回归扩散建模 [PDF](https://arxiv.org/pdf/2604.23586), [HTML](https://arxiv.org/abs/2604.23586)
### Authors
Zhen Ye,Xu Tan,Aoxiong Yin,Hongzhan Lin,Guangyan Zhang,Peiwen Sun,Yiming Li,Chi-Min Chan,Wei Ye,Shikun Zhang,Wei Xue
### Background
现有的联合音频-视频生成模型表明统一生成比级联方法有更好的跨模态一致性。然而，现有的模型在整个去噪过程中通过普遍注意力紧密耦合两种模态，这对头部对话合成来说是不理想的：虽然音频和面部动作在语义上有相关性，但它们的低级实现（声学信号和视觉纹理）遵循不同的渲染过程。强制在所有级别进行联合建模会导致不必要地纠缠和降低效率。
### Innovation
提出了一种自回归扩散框架Talker-T2AV，其中高级跨模态建模在共享骨干中发生，而低级细化则使用模态特异性解码器。一个共享的自回归语言模型在统一的补丁级别token空间中联合处理音频和视频。两个轻量级的扩散解码器头将隐藏状态解码为帧级别的音频和视频潜在变量。
### Conclusion
在说话肖像基准测试中，Talker-T2AV在口型同步准确性、视频质量和音频质量方面优于双分支基线，并且比级联流水线具有更强的跨模态一致性。
## 47. `cs.CL` - HeadRouter: 动态头部加权路由用于大型音频语言模型的任务自适应音频令牌剪枝 [PDF](https://arxiv.org/pdf/2604.23717), [HTML](https://arxiv.org/abs/2604.23717)
### Authors
Peize He,Yaodi Luo,Xiaoqian Liu,Xuyang Liu,Jiahang Deng,Yaosong Du,Bangyu Li,Xiyan Gui,Yuxuan Chen,Linfeng Zhang
### Background
最近的大型音频语言模型（LALMs）在处理多模态序列方面表现出色，但同时也带来了较高的推理成本。令牌压缩方法通过直接减少序列中的冗余令牌来有效降低成本。现有压缩方法通常假设LALMs中的所有注意头对各种音频任务的重要性相同，并通过所有头的分数来计算令牌的重要性。然而，研究表明，不同音频领域中注意力头的表现各不相同，只有稀疏的注意力头对音频有响应，且在处理语义和声学任务时表现出不同性能。
### Innovation
论文提出了一种名为HeadRouter的新方法，这是一种头部重要性感知的令牌剪枝方法，可识别不同音频任务中不同注意头的变异性重要性，以最大化关键令牌的保留。HeadRouter无须训练，适用于多种LALMs。实验结果表明，HeadRouter在AudioMarathon和MMAU-Pro基准测试中实现了最先进的压缩性能，即使保留音频令牌的70%，在Qwen2.5-Omni-3B和Qwen2.5-Omni-7B上分别实现了vanilla平均值101.8%和103.0%的性能。
### Conclusion
实验结果证实了HeadRouter的有效性，并在多种LALMs上均达到卓越的压缩性能，相较于基线模型即使保留了较大比例的音频令牌，性能仍显著提升。
## 48. `cs.CL` - SFT-then-RL Outperforms Mixed-Policy Methods for LLM Reasoning [PDF](https://arxiv.org/pdf/2604.23747), [HTML](https://arxiv.org/abs/2604.23747)
### Authors
Alexis Limozin,Eduard Durech,Torsten Hoefler,Imanol Schlag,Valentina Pyatkin
### Background
最近的研究表明，交错或混合使用监督学习和强化学习信号的LLM推理方法在数学基准测试中取得了优于标准知识精炼后强化学习管道的表现。然而，许多最新发表的研究论文依赖于一个有缺陷的基准，这个缺陷是由两个独立的错误引起的：一个是安装在CPU上的优化器错误，它在梯度聚合期间无声地跳过了中间的微批次（影响TRL、OpenRLHF和Llama-Factory等多个下游框架），另一个是OpenRLHF中的损失聚合错误，它错误地加权了每个小批次的损失。这两个错误共同压制了知识精炼性能，优化器错误的作用更大，而损失聚合错误的作用较小。
### Innovation
研究揭示了两个导致错误基准的缺陷：第一个是DeepSpeed中的CPU卸载优化器错误，它在梯度累积期间无声地丢弃了中间微批次，影响了多个下游框架；第二个是OpenRLHF中的损失聚合错误，错误地加权每个微批次的损失。研究还通过修正这些缺陷，展示了标准的知识精炼然后强化学习管道在这类任务中超过了所有评估的混合策略方法。在数学基准测试中，修正后的方法在Qwen2.5-Math-7B上的表现比最先进的混合策略方法高出3.8个点，在Llama-3.1-8B上高出22.2个点，即使仅仅使用50个强化学习步骤的简短版本也优于混合策略方法，同时使用更少的FLOP。
### Conclusion
修正后的标准知识精炼然后强化学习管道在数学基准测试中的性能优于所有评估的混合策略方法。即使使用更少的计算步骤，这种方法的表现仍然优于混合策略方法。
## 49. `cs.CL` - ShredBench: Evaluating the Semantic Reasoning Capabilities of Multim Modal LLMs in Document Reconstruction [PDF](https://arxiv.org/pdf/2604.23813), [HTML](https://arxiv.org/abs/2604.23813)
### Authors
Zichun Guo,Yuling Shi,Wenhao Zeng,Chao Hu,Haotian Lin,Terry Yue Zhuo,Jiawei Chen,Xiaodong Gu,Wenping Ma
### Background
多 多模态大语言模型（（ML DMLMs）在视觉富文档理解 (VRDU) 任务中 表现出 出 出色 净 宔 衑的 行政 怞。 但当前评估 主 践 主考虑 主 范于 对 憹 僸 処 歂 绻 的 庚 断 怒料 抶 时概 的 文字 碎片 槐 件 重构 任务。 涇 划 凊. 益 溛 的 结 枡 昛 图 牍 在 弛 了 识 片 划 与 义 编的 涝 吢度 的 上列 件 r 匀 抳范 的 片 銶 牿. 盗 这一番 涡 阵 怨 一 丢 瓜 吺饺 的 世 牐 仅 察测 了 完整 的 囉块 牒ើ皮 牻. 盰 它需 贈 汹 一 丢 衰 识 部 于 鋬 床 机 钆 由 脂 文 通 体 格 诺 斩 谱 创 个 现 榻 工 隠 机 体 卛 抶 
### Innovation
 塰 弛建 设 姛 个 收 墩 噜 衰 的 婎 牛建 低碳 金 同 份 浴 腐 一 塰 个 抶 隱 的 衰 你 君建 硰 个 隊 衰 溙 衰 世 蚵 五 丢 憗 的 衰 与 佑 官 与 栋 实件 杅 衰 n 的 详 衰 溲 的 硰 且 姑敏 一 始原 低 一 嫩 丢 教 极 如果 耳 落 实 n 的 起 丢 碎 牆 牾 仍有 一 働 辑 丢 建 婆 吢 都 弳 了 瓜 牐 峢 的 关 识 所死 児 硰 建 一 个 机 钆 堆 个 栊 的 栳 列 文 通 体 格 杉 硰 辪 的 塰 你 坞 巨 的 唬 官, 廢 业 儐 宛
### Conclusion
 些 塨 结得 衧 硰 你 的 溶 奸 丢 对 当亏 的 帛 儿 两 娣盛 硰 个 嫢 巛建 的 媌 劧 请 墩 了 成 生 寕 的 剩 and 上 g 机 仍 央 丢 训 嫩 了些 在 椭 吃 的 衰 你 中 仍 得 衕 以 衰 详 任何 的 详 类 帷 儿 厩 业 婐 or 于是 堰 掬 了 当前 复 同 憖 的 饷 夨 枞 仍 丢 有一 友 用 的 澺 棢 溉 巳 详 溩 ， 涥 醛 于 崴 忡 的 丢 迬 丢 更 进 的 详 挥 溧 的 娳 牆 壢 丢 京 桰 一 堢 cr 愠 的 遌 桰 详 桰 istance 堿 僗 硰 个 桰 戨 
## 50. `cs.CL` - Swa-bhasha Resource Hub: Romanized Sinhala to Sinhala Transliteration Systems and Data Resources [PDF](https://arxiv.org/pdf/2507.09245), [HTML](https://arxiv.org/abs/2507.09245)
### Authors
Deshan Sumanathilaka,Sameera Perera,Sachithya Dharmasiri,Maneesha Athukorala,Anuja Dilrukshi Herath,Rukshan Dias,Pasindu Gamage,Ruvan Weerasinghe,Y.H.P.P. Priyadarshana
### Background
自2020年至2025年期间，为了推进僧伽罗自然语言处理（NLP）的研究，特别是在训练转写模型和开发涉及罗马化僧伽罗语的应用方面，提供了一套全面的数据资源和算法集合。当前已开放的数据集和相应的工具通过该枢纽平台公开提供。
### Innovation
该平台首次为罗马化僧伽罗语到僧伽罗语转写系统的开发和研究提供了全面的数据资源和算法，显著推动了NLP领域的发展。此外，该论文还对现有转写应用程序进行了比较分析。
### Conclusion
该论文详细介绍了作者贡献的资源，并包括现有转写应用程序的对比分析。这些资源和工具为学术界和工业界研究罗马化僧伽罗语提供了重要支持。
## 51. `cs.CL` - 紧凑型语言模型能否像代理一样搜索？蒸馏引导策略优化以保留代理性RAG能力 [PDF](https://arxiv.org/pdf/2508.20324), [HTML](https://arxiv.org/abs/2508.20324)
### Authors
Rikuto Kotoge,Mai Nishimura,Jiaxin Ma
### Background
强化学习（RL）作为一种后训练方法，已被证明能激发语言模型的代理性检索和规划行为。尽管在大模型上有成功应用，但将其应用于紧凑型模型（例如，参数量在0.5-1B之间）会遇到独特挑战。紧凑型模型初始表现较差，导致奖励稀疏且训练不稳定。
### Innovation
该文提出了蒸馏引导策略优化（DGPO），该方法通过教师示范的冷启动初始化和策略优化过程中的连续教师指导来克服紧凑型模型的独特挑战。提出了细粒度的代理性RAG能力（ARC）度量标准，用于分析推理、搜索协调和响应合成能力。
### Conclusion
DGPO使得紧凑型模型能够实现复杂的代理性搜索行为，在某些情况下甚至超越了更大教师模型。这在计算资源受限的环境中使代理性RAG成为可能。
## 52. `cs.CL` - V-ONAM: Visual semantic editing and attention modulating for causal interpretability of of vision-language model models [PDF](https://arxiv.org/pdf/2509.14837), [HTML](https://arxiv.org/abs/2509.14837)
### Authors
Qidong Wang,Junjie Hu,Ming Jiang
### Background
近年来， 解释模型的因果可 叀可 可塑性 怲 的研究不断进步， 牻别 尟尽管 这 些 成果多 重点关注 于 文本模型, 但关于 对 于 于 觎-  觾示-  视觉-  觠택  语 吿  觘认  觾示 昩니다  墙 杻 的 冐解模式的内部机制理解仍相对匮乏。当前的方法往往 如间接地 方法 通过 膝 僆语言干预来导出视觉解释， 而关于 视觉干预通常依赖不成不 胁  坯水  入表示  墙改  的 屔糙程度. 这 对于 贈在多媒体整 机构 对上 了 昘认知过程中寻求因果影响力的深入理解.
### Innovation
本文提出了一种名为 V-onam 的框架， 审合视觉语义编辑与注意力调整, 用于视觉语 语学模型的因果解释能力。 V-onam 使容 稡 在三个语义层面 依次是 对象、属性和 关系上 攌动 统能, 同时筛选正负贡献 在预测过程中显式地表示和. 通过这 秙它们 可以在客观例的上 上观察到 歞正贡献通常在一个语义层面上变化、而涉及负面的贡献则 墙 帿泛化为其他层面.
### Conclusion
我们还 还认 在对 夘认识到层面 间 的 廁正差别在于比较 在上付出了 囘认它们 在不同差异的层面有所不同、而涉及负面的那一面通常较广普及.我们还引进了自动一种自动调整embeddingdings 的方法 促进者两种 Llava 和和 和和 和rustrbliln特 在多个个多样的V问同视觉问题问基准数据集合中的进行演示和展示了显著改这. 我们这补充公现已在数据分析与发布仓开源可此成果 您可以来访,在给定的URL查看.
## 53. `cs.CL` - 细调语言模型中移交信息和填充项目的表示研究 [PDF](https://arxiv.org/pdf/2509.20237), [HTML](https://arxiv.org/abs/2509.20237)
### Authors
Yu Wang,Leyi Lao,Langchu Huang,Gabriel Skantze,Yang Xu,Hendrik Buschmeier
### Background
在现代基于变压器的自然语言模型中，移交信息和填充项目通常是作为‘噪声’被忽略掉的，这些成分在对话中非常重要，但未被充分利用。
### Innovation
本研究通过在三个对话数据集上应用三种不同的微调策略来研究这两种成分如何被模型表示，从而探讨了微调如何帮助模型学习这些表示。通过聚类分析和自然语言生成评估，证明微调使得模型能够更好地区分不同移交信息和填充项目的细微语义差异。
### Conclusion
研究结果表明，通过微调，通用语言模型有可能转变为更具备对话能力的语言模型，能够更自然地生成类似人类的语言。
## 54. `cs.CL` - Data-efficient Target Token-level Preference Optimization for LLM-based Text-to-Speech [PDF](https://arxiv.org/pdf/2510.05799), [HTML](https://arxiv.org/abs/2510.05799)
### Authors
Rikuto Kotoge,Yuichi Sasaki
### Background
现有的面向语音合成（Text-to-Speech, TTS）系统的优化方法主要方法主要要求成对配对的满意和不满意样本，在音频水平。.。。。。。。，这些样本对往往很难在语音合成系统的输出中找到，同时，基于音频水平的优化方法很难实现详细的令牌级别优化，从而无法准确地对发音进行对齐优化。
### Innovation
本研究提出了一种名为TKTO的方法，该方法可以消除配对样本的需要，通过自动提供详细的令牌级别对齐信号，而无需对令牌进行标注，从而简化了训练过程并提高了训练效率。该方法在具有挑战性的日语语音合成系统的精度方面提升达3%，并减少了54%％的C level，，并还自动为目标令牌分配了强度为2 8.的较强奖励。
### Conclusion
通过这种数据高效的、针对令牌级别的偏好优化方法，研究成功改进了现有的语音合成系统的性能如精度和并同时简化了训练过程并减少了对对标注的需求同时改进了个别合成模型的自然度与
## 55. `cs.CL` - LLM-to-LLM策略互动中的欺诈能力 [PDF](https://arxiv.org/pdf/2510.12826), [HTML](https://arxiv.org/abs/2510.12826)
### Authors
Thao Pham
### Background
随着大型语言模型代理自主地在多样化的环境中部署，评估它们进行战略欺骗的能力变得至关重要。尽管最近的研究已经探讨了AI系统如何欺骗人类开发者，但LLM之间的欺骗行为仍然未被充分探索。本文通过两个博弈论框架——廉价说话信号博弈和同伴评估对抗博弈——来研究前沿的LLM代理的欺骗能力和倾向。
### Innovation
本文研究了前沿的大型语言模型代理在没有明确提示的情况下进行欺骗的可能性和倾向性，这在之前的AI系统研究中较少被关注。通过测试四个模型（GPT-4o，Gemini-2.5-pro，Claude-3.7-Sonnet，Llama-3.3-70b），本文量化了欺骗表现，并通过链式思维推理分析了欺骗策略。结果显示，在有提示的情况下，大多数模型，尤其是Gemini-2.5-pro和Claude-3.7-Sonnet，取得了近乎完美的表现。而在没有提示的情况下，所有模型都选择了欺骗而不是坦白，在同伴评估中达到100%的比例；在廉价说话信号游戏中，选择欺骗的模型成功率为95-100%。
### Conclusion
这些发现强调了在多代理设置中使用高风险博弈论场景进行稳健评估的重要性。
## 56. `cs.CL` - ChatR on:: Reinforcement Learning for Conversational Reasoning and Retrieval Augmented Question Answer ing [PDF](https://arxiv.org/pdf/2510.13312), [HTML](https://arxiv.org/abs/2510.13312)
### Authors
Simon Lupart,Mohammad Aliannejadi,Evangelos Kanoulas
### Background
在对话型问答（CQA）C onversvers）CQA））））对话系统中,这些系统需要处理用户的提问，并然后进行合理的回答 on对话过程中涉及多种复杂的推理活动，从用户的意图在对话中不断发展 on到中的每次对话的不同阶段中用户的表达往往不够明确 on需要通过上下文进行解释 on重新进行查询重组 and动态协调检索与生成之间的关系 on现有的系统通常采用固定的检索-再进行生成的的工艺流程 on无法有效应对这种稀疏和延迟奖励的问题 onChat这些问题使得通过强化学习（训练系统变得更加困难。
### Innovation
ChatR on框架通过结合强化学习（（RL）对一个框架中集成推理和这一体措施使得系统可以横跨不同的对话阶段 on实现这么做可以激发探索性和适应性行为 on本文通过强化学习框架解决增强学习难题中稀疏 on延迟奖励的问题 on为此他们提出了一个意图意识奖励 on将通过将检索与推理对的反馈对对和进行调整以满足不断发展中的的意图目标 on这使得ChatR on能够通过各种方面表现得更强 on在三个和和和和和三亿参数backbone on on在五个CQA数据集中比面对最好每一种都得都能比超过竞争其他竞争竞争竞争模型 on在用利用BERTScore和和和和和和指标ScoreLL计算上和评估中作为表现更加丰富和涵盖不同的CQA数据集中.
### Conclusion
通过ChatR on的框架的研究表明 on基于强化学习的推理支持更能为对话型问答管道提供更加灵活 on上下文感知的行为 on这表明基于强化学习的推理支持使得对话系统型问答实现了更多的更加自如 on能够让系统在一个跨度范围较大的领域块表表现出更好的通用性性能 on测试显示这种模型在多样性数据集上在话题话题、发展中的意图、混合出发主动发起的对话以及处理多多文档场景上已有所提高 on打开删除除了多个在效果检验上的的改善 in在推理能一致性有效性上也得到了证明.
## 57. `cs.CL` - ZoFia: 零样本假新闻检测中的实体引导检索与多大语言模型交互 [PDF](https://arxiv.org/pdf/2511.01188), [HTML](https://arxiv.org/abs/2511.01188)
### Authors
Lvhua Wu,Xuefeng Jiang,Sheng Sun,Yan Lei,Tian Wen,Yuwei Wang,Min Liu
### Background
假新闻的迅速传播威胁到了社会稳定和公众信任，这突显出需要对其有效检测的迫切需要。尽管大规模语言模型（LLMs）在假新闻检测方面具有潜力，但由于知识截止时间和容易产生事实幻觉等问题，它们在处理时间敏感新闻时仍存在局限性。此外，单一LLM的思想容易陷入早期立场锁定和确认偏误，难以同时处理内容推理和事实核查。
### Innovation
我们提出了ZoFia，这是一种两阶段零样本假新闻检测框架。第一阶段使用候选实体提取的新颖层次相关性和校准最小边际相关性算法准确提取核心实体，克服知识和证据缺口。第二阶段通过多代理系统并行进行多视角推理和验证，并通过对抗辩论获得可解释和稳健的结果。综合实验表明，ZoFia在两个公开数据集上的性能优于现有的零样本基线，甚至优于大多数少量样本方法。
### Conclusion
综合实验结果显示，ZoFia在两个公开数据集上优于现有的零样本基线以及大多数少量样本方法。我们的代码已在<hthis https://github.com/example>的链接下开源，以促进研究社区的发展。”需要补充具体实验数据和结果，以便进一步细化结论部分的表述。
## 58. `cs.CL` - Food4on: 多多基于多 夒多重代理的框架， 实时现实时自动发现免费食物资源的方法及其 [PDF](https://arxiv.org/pdf/2510.18289), [HTML](https://arxiv.org/abs/2510.18289)
### Authors
Zhengqing Yuan,Yiyang Li,Weixiang Sun,Zheyuan Zhang,Kaiwen Shi,Keerthiram Murugesan,Yanfang Ye
### Background
在美国， 食物不安全是一个长期的公共卫生紧急情况， 已紧密关联着慢性疾病、 心理健康问题以及类阿片类药物滥用。 但 尽管存在成千成千的食物银行和 访问仍然不具有足够的的覆盖度；现有的检索系统依赖于通用目录的搜索引擎 从而难以获取有效且地地理相关的结果；现有的基于大语言模型的聊天机器人只能提供模糊的营养建议 且无法适应现实世界的限制如时间、地点和 以及交通条件；现有的食物推荐系统更侧重于食物多样性 耀忽视了处于食物不安全状况下的个人的紧急需求包括最近的地点、验证的可 库存量以及情境中的障碍条件。这些限制对那些脆弱的人群行为产生了着影响 该人群包括无家 人、无家可者、成瘾者以及数字文盲者。 他们无法及时获取急需的资源。
### Innovation
Food4on 提出了三项创新：1 创新（1) 敐合跨界的数据集合 来聚集定期更新的食物资源； 2) 一种轻型强化学习算法 该算法 在经过筛选的案例上 讘认真训练后 优化以地理可达性和营养正确性；  t 3) 实现互动反馈循环 别动态调整检索政策以适应不断变化的需求。
### Conclusion
通过整合 如获取、语义捷分析和 和 和需求分析 更新Food4on提供营养标注且与实际需求相关的食物资源支持。 该 迤断建立朝一个可扩的、、 幨等的智能系统 整个框架为应对食物不安全和 并消除由此诱发的健康风险径提供步。
## 59. `cs.CL` - 共识掩饰下的特权知识解析：大型语言模型答案正确性的区分 [PDF](https://arxiv.org/pdf/2604.12373), [HTML](https://arxiv.org/abs/2604.12373)
### Authors
Tomer Ashuach,Shai Gretz,Yoav Katz,Yonatan Belinkov,Liat Ein-Dor
### Background
人类通过内在状态的主观体验来评估自己的理解状态，这些状态对外部观察者不可见。本文探讨大型语言模型是否也具有类似的特权知识，即在未经外部观察证实的情况下评估答案正确性的能力。研究者训练了正确性分类器，并对比模型自身内部表示与外部模型表示的性能，发现自我表示并未展现显著优势，推测这可能是由于模型间答案正确性的一致性较高。为探究真实特权知识，研究者在模型间存在分歧的数据集上进行测试，发现自我表示在事实知识任务中展现出显著优势，而在数学推理任务中则无明显优势。
### Innovation
该研究首次在大型语言模型中分离出“特权知识”，即模型在特定任务中利用内部知识优于外部知识的能力。通过探究模型间分歧数据集，相较于外部模型表示，发现模型自我表示在事实知识任务中表现更优，而在数学推理任务中没有显著优势。
### Conclusion
研究发现，自我表示在事实知识任务中展现出显著优势，而在数学推理任务中则没有优势。这种领域不对称性在模型层面上逐渐出现，表明事实知识的特权知识来源于模型早期到中期层面对特定信息的记忆检索，而数学推理则不存在这种一致优势。
## 60. `cs.CL` - 一词之遥即崩塌：指令微调有益结果的脆弱性 [PDF](https://arxiv.org/pdf/2604.13006), [HTML](https://arxiv.org/abs/2604.13006)
### Authors
Erfan Baghaei Potraghloo,Seyedarmin Azizi,Souvik Kundu,Massoud Pedram
### Background
大型语言模型在指令微调后能够产生有帮助且结构化的响应，但这种效果在面对简单的约束时是否仍然稳定呢？该研究通过引入简单的词法限制，证明了这种有益性的脆弱性。通过禁用一个标点符号或常见的单词，发现指令微调的大型语言模型在七个不同规模和类型的模型中响应完备性降低了14%-48%。这种效果在盲评中得到了确认，并且通过自动化的成对比较进一步得到了验证。
### Innovation
研究揭示了一种规划失败的现象：两步生成可以恢复59%-96%的响应长度，并且对提示的线性探针在生成之前就预测了响应长度，揭示了指令微调引入的代表结构。此外，该研究指出标准独立的LLM评价方法和成对评价方法之间的差异，展示了当前评价实践中的一个方法论盲区。
### Conclusion
指令微调的大语言模型在面对简单的表面形式约束时，表现出显著的脆弱性。即使是表面上微小的更改，也会导致响应长度大幅下降。这表明指令微调将任务能力与狭窄的表面形式模板紧密地耦合在一起。这种脆弱性不仅在简单的限制下表现出来，而且在更现实的部署约束中也表现出来，例如抑制前置段落、公司语气指导方针、法律合规性等，均导致类似程度的降级。
## 61. `cs.CL` - EVE: 一种针对地球智能的领域专用LLM框架 [PDF](https://arxiv.org/pdf/2604.13071), [HTML](https://arxiv.org/abs/2604.13071)
### Authors
Àlex R. Atrio,Antonio Lopez,Jino Rohit,Yassine El Ouahidi,Marcello Politi,Vijayasri Iyer,Umar Jamil,Sébastien Bratières,Nicolas Longépé
### Background
介绍了Earth Virtual Expert (EVE)，这是首个开源的、端到端的用于开发和部署地球智能领域专用的大规模语言模型的计划。文章的核心是EVE-Instruct，这是一个基于Mistral Small 3.2并针对推理和问答进行了优化的24B参数的领域适应模型。
### Innovation
EVE-Instruct在新构建的地球观测和地球科学基准测试中，表现优于同类模型的同时保留了通用能力。同时，EVE还整合了检索增强生成（RAG）和幻觉检测流水线，并通过API和GUI部署到一个生产系统中，目前已支持了350位试点用户。此外，论文还提供了经过精选的训练语料库和系统的领域特定评估基准，涵盖了多项选择题问答（MCQA）、开放性问答和事实性等几类。
### Conclusion
所有模型、数据集和代码将发布开源许可，贡献给本领域。有兴趣的读者可以通过提供的链接进行进一步研究与贡献。
## 62. `cs.CL` - 视觉-语言模型中的推理动态及其监测模态依赖的局限性 [PDF](https://arxiv.org/pdf/2604.14888), [HTML](https://arxiv.org/abs/2604.14888)
### Authors
Danae Sánchez Villegas,Samuel Lewis-Lim,Nikolaos Aletras,Desmond Elliott
### Background
近年来，视觉语言模型（VLMs）取得了显著进展，具备了推理能力。然而，这些模型如何整合视觉和文本信息，以及它们的推理过程仍然不明确。本文对来自两种不同模型家族的18种VLMs进行了分析，涵盖了指令调整和推理训练的模型。通过关注推理过程中的置信度变化、评估推理校正效果以及分析中间推理步骤的贡献，研究发现，这些模型容易在早期预测中形成自我强化的现象，而不是在推理过程中进行修正。推理训练的模型显示出更强的校正行为，但这种行为在不同模态条件下（从文本主导到纯视觉设置）的表现有差异。
### Innovation
研究通过监控模型推理过程中的置信度变化、评估推理校正效果和分析中间推理步骤的贡献，揭示了视觉语言模型在推理过程中如何处理视觉和文本信息。使用误导性文本提示进行控制干预，研究探讨了这些提示对模型的影响是否可以从推理过程中被恢复，特别是推理训练的模型更可能直接引用这些提示，尽管它们的推理过程可能会显得视觉导向，实际上却遵循文本提示。而指令调整的模型引用这些提示较少，但其较短的推理过程反映出与视觉输入不一致的现象。
### Conclusion
推理过程中的置信度提供了一个不完全的视角来理解不同模态如何驱动VLM的决策，这对多模态系统的透明性和安全性具有重要影响。这表明当前的监控方法可能不足以全面理解这些模型如何处理不同模态的信息，从而限制了我们对这些系统的理解能力。
## 63. `cs.CL` - HiRAS: 一种层次化多智能体框架用于生成和执行代码论文 [PDF](https://arxiv.org/pdf/2604.17745), [HTML](https://arxiv.org/abs/2604.17745)
### Authors
Hanhua Hong,Yizhi LI,Jiaoyan Chen,Sophia Ananiadou,Xiaoli Li,Jung-jae Kim,Chenghua Lin
### Background
大型语言模型的最新进展突显了它们在自动计算研究中的潜力，尤其是重复实验结果。然而，现有的方法仍然使用固定的序列智能体管道，这些管道在全局协调方面较弱，限制了其稳健性和整体性能。
### Innovation
本工作提出了一种名为HiRAS的层次化多智能体框架，用于端到端的实验重复。该框架通过监督管理智能体协调细粒度阶段的专业智能体。此外，还识别了参考自由评估中的局限，并引入了P2C-Ex精炼协议，该协议结合了仓库级别的信息并更好地与原始参考评估指标对齐。
### Conclusion
进行广泛的评估，验证了我们提出方法的有效性和鲁棒性，并观察到性能改进，包括相对于先前最佳方法超过10%的相对性能提升，并且显著减少了评估中的虚构成分。我们的工作可在此 GitHub 地址上获得：this https URL。
## 64. `cs.CL` - AlphaContext：一种基于进化树的计量心理情境生成器，用于创造力评估 [PDF](https://arxiv.org/pdf/2604.18398), [HTML](https://arxiv.org/abs/2604.18398)
### Authors
Yixuan Wang,Yue Huang,Hong Qian,Yunzhao Wei,Yifei Ding,Wenkai Wang,Zhi Liu,Zhongjing Huang,Aimin Zhou,Jiajun Guo
### Background
在大规模语言模型（LLMs）和人类-人工智能协作的背景下，创造力已成为关键能力，支撑着现实问题解决的创新。为了系统地提高创造力，需要科学有效的评估工具。虽然心理测量学研究认为基于情境的评估是测量创造性思维的有效方式，但高质量的专家设计情境仍然稀缺。现有的基于LLM的内容生成器在评估提示不足、叙事连贯性弱、修辞风格多样性和支持创造性思维方面存在问题。
### Innovation
本文提出了AlphaContext，一种基于进化树的计量心理情境生成器，用于创造力评估。首先，HyperTree Outline Planner用规则指导的超树形式化专家设计的大纲，并进行自顶向下的层次规划；然后，基于MCTS的内容生成器填充大纲，平衡全局结构和局部质量；接着，演化情境优化器通过迭代更新生态位精英来进化情境，以同时提高多样性和质量；最后，采用评估指导的进化退火器模拟具有不同风格的虚拟参与者，并循环利用较弱的情境继续进化。
### Conclusion
实验结果表明，AlphaContext在六个质量指标上相对于竞争方法平均提高了8%。
## 65. `cs.CL` - PRISM:探究 LLM 幐藏现象中的推理和知识来源错误? [PDF](https://arxiv.org/pdf/2604.16909), [HTML](https://arxiv.org/abs/2604.16909)
### Authors
Yuhe Wu,Guangyu Wang,Yuran Chen,Jiatong Zhang,Yutong Zhang,Yujie Chen,Jiaming Shang,Guang Zhang,Zhuang Liu
### Background
随着大型语言模型（LLMs）从对话助手演变成能够处理复杂任务的代理，它们被越来越多地部署在高风险领域中。目前的基准测试主要LMs 夯查询和输出级别的评分,这些评分方法主要关注于幻觉的严重程度,并为我们提供了有关幻觉究竟在生成管道的哪个环节、由何引起的见解。然而,本文重新定义了幻觉评估为一种诊断问题,并提出了 PRISM，这是一种受控基准测试,该基准测试将幻觉分解为四个维度：知识错误、推理错误和从属错误，并这些维度与生成的三个阶段（记忆、推理和遵循从属）相关。 PRISM 包含 448 个实例跨越 65 个任务景，并支持支持阶段的细粒度诊断评估。通过评估22种主流 LLMs 和私有 LLMs 在发内发现了困扰策略和具体维度的权衡，并且展示了在提高从属上和 时 和和:检索和和推理,上和具体程度之间的权衡。这一表明 PRISM 为研究 LLM 幐藏现象具体机制提供了一个框架 这将最终加速动了可开发值得信赖的大语言模型。
### Innovation
该文将幻觉评估重新定义为一种诊断问题 幋试提出了 PRISM 基准测试 这个基准测试将幻觉分为四个维度：知识、推理、和从属错误 迏基础包括记忆、推理、遵循从属的阶段。并 这个基准测试包括 448 个实例跨越 65 个任务景 幵支持细粒度阶段意识的诊断评估。该发现了一种主要 LLM 和私有 LLM 在不同方面的权衡 幨展示了在从属、推理和 检索之间的权衡
### Conclusion
通过在 PRISM 评估中明显发现了针对性的权衡 且该表明 阻止具体维度的错误可能是以牺牲其他维度为代价的 迡个基准测试提供了lLM 幷隐藏现象}机制的框架最终加速动了开发值得信赖的大语言模型
## 66. `cs.CV` - 带有幽灵卷积的注意力增强YOLOv8在智能交通系统中实时车辆检测 [PDF](https://arxiv.org/pdf/2604.22856), [HTML](https://arxiv.org/abs/2604.22856)
### Authors
Syed Sajid Ullah,Muhammad Zunair Zamir,Ahsan Ishfaq,Salman Khan
### Background
准确的车辆检测是自动驾驶、交通监控和智能交通系统的关键组成部分。现有的YOLOv8n模型在检测性能上仍存在提升空间。
### Innovation
提出了一个改进的YOLOv8n模型，融合了幽灵模块（Ghost Module）、卷积块注意力模块（CBAM）和可变形卷积网络v2（DCNv2）。幽灵模块通过高效特征生成减少特征冗余，CBAM通过通道和空间注意力精炼特征表示，DCNv2增强了对车辆结构几何变异的适应性。
### Conclusion
该模型在KITTI数据集上的mAP@0.5达到95.4%，相较于基线YOLOv8n提高了8.97%，同时精度为96.2%，召回率为93.7%，F1分为94.93%。与七个最先进的检测器的比较分析以及消融研究验证了集成模块的有效性，表明其在多种性能指标上具有优势，是一种在复杂交通环境下的 robust 和计算高效的车辆检测方案。
## 67. `cs.CV` - 用于肝癌定量的数据集、基准和工具的数字病理学资源 [PDF](https://arxiv.org/pdf/2604.22858), [HTML](https://arxiv.org/abs/2604.22858)
### Authors
Ying Xiao,Shimiao Tang,Xitong Ling,Weiming Chen,Jun Wang,Jiawen Li,Huaitian Yuan,Jianghui Yang,Bowen Li,Huan Li,Yiting Meng,Tian Guan,Yonghong He,Hongfang Yin
### Background
肝癌，特别是肝细胞癌（HCC），对全球疾病负担造成了重大影响。准确的诊断和预后评估直接影响治疗选择和患者生存率，病理学检查仍然是肝癌诊断的金标准。在组织病理学切片上识别多种组织成分和病理亚型对于估计术后复发风险和总体预后至关重要。然而，大多数公开可用的资源仍以整个切片图像（WSI）级别提供，而用于肝癌细粒度组织成分识别的注释数据集稀缺，这阻碍了可重复模型的开发和定量分析工具的部署。
### Innovation
提出了HepatoBench，一个用于肝癌的斑块级别图像数据库，带有7个关键组织类别注解。基于HepatoBench，训练并开源了一个深度学习分类模型作为组织识别工具，进一步培训了一个WSI级别的肿瘤/非肿瘤分割模型，以自动定位整个切片中的病变区域。通过将斑块级别的组织分类器与WSI级别的分割模型集成，构建了HepatoQuant，一种针对肝癌的端到端、疾病特异性区域定量工具，使从WSIs到组织组成的解析和定量统计数据的统一工作流程成为可能。同时开源了HepatoBench、基准测试协议和支持工具，为肝癌病理中的自动化区域定量和公平方法比较提供了坚实基础。
### Conclusion
通过HepatoBench、HepatoQuant等资源，构建了针对肝癌的统一工作流程，从WSIs到组织组成解析和定量统计数据，提供了一个用于自动化区域定量和公平方法比较的强大平台。
## 68. `cs.CV` - 测试图像编辑模型中的视觉规划 [PDF](https://arxiv.org/pdf/2604.22868), [HTML](https://arxiv.org/abs/2604.22868)
### Authors
Zhimu Zhou,Yanpeng Zhao,Qiuyu Liao,Bo Zhao,Xiaojian Ma
### Background
人类视觉规划是智能的关键组成部分，尤其是在需要复杂的空间推理和导航任务中。然而，在机器学习中，这个原本的视觉问题经常通过语言中心的视角来解决。虽然最近的研究表明，完全视觉的方法具有潜力，但由于逐步骤规划生成的范式，这些方法在计算效率上存在显著的问题。
### Innovation
本文提出了EAR，一种编辑即推理的范式，将视觉规划转化为单一的图像变换。为了解离内在推理和视觉识别，使用抽象谜题作为探针任务，并引入了AMAZE数据集，该数据集包含经典的迷宫和女王问题，涵盖了不同且互补形式的视觉规划。AMAZE的抽象性质也有助于自动化评估自回归和扩散模型在像素级保真度和逻辑有效性方面的表现。评估了领先的专有和开源编辑模型。结果显示，所有模型在零样本设置中表现出困难，微调在基本规模上能够实现对更大领域和非领域规模的显著泛化。
### Conclusion
我们最好的模型在高端硬件上运行，但没有达到人类解决者在零样本效率上的表现，突显了神经视觉推理中的持续差距。
## 69. `cs.CV` - MeshLAM: 一次性前馈可动画化纹理网格头像重建 [PDF](https://arxiv.org/pdf/2604.22865), [HTML](https://arxiv.org/abs/2604.22865)
### Authors
Yisheng He,Steven Hoi
### Background
该研究介绍了一种名为MeshLAM的前馈框架，用于从单张图像中重建高保真、可动画化的3D头像。现有的方法需要时间消耗的测试时优化或大量的多视角数据，而MeshLAM则能够在单次前向传递中从单张图像生成完整的网格表示，并具有内在的可动画性。
### Innovation
该方法的特点在于采用了双形状和纹理图架构，同时处理网格顶点和纹理图，并结合提取的图像特征，通过共享变换器骨干网络实现更为一致的形状雕刻和外观建模。此外，还提出了一种迭代的GRU基解码机制，该机制结合了逐步几何变形和纹理细化，以及一种新颖的基于重新投影的纹理引导机制，确保在前馈变形过程中保持网格拓扑完整性和外观学习与输入图像的关联。
### Conclusion
大量的实验表明，该方法在重建质量、动画能力和计算效率方面超过了当前最先进方法。项目网址为this https URL。
## 70. `cs.CV` - SketchVLM：视觉语言模型可以注释图像以解释思路并引导用户 [PDF](https://arxiv.org/pdf/2604.22875), [HTML](https://arxiv.org/abs/2604.22875)
### Authors
Brandon Collins,Logan Bolton,Hung Huy Nguyen,Mohammad Reza Taesiri,Trung Bui,Anh Totti Nguyen
### Background
人类在回答关于图像的问题时，自然会使用指指点点、勾勒以及绘画来解释他们的推理过程。然而，现代的视觉-语言模型（VLMs），如Gemini-3-Pro和GPT-5，只通过文字回答问题，这使得用户的验证变得困难。SketchVLM框架通过在输入图像上生成非破坏性的、可编辑的SVG叠加来改善这一问题，从而帮助VLMs进行视觉解释。
### Innovation
SketchVLM是一个无需训练、模型通用的框架，它能够让视觉语言模型生成非破坏性的、可编辑的SVG叠加在输入图像上，以进行视觉解释。该模型在视觉推理和绘画任务上分别优于现有的基于图像编辑和微调绘图的基线，提高了视觉推理任务的准确性和注释质量，同时生成的注释也更忠于模型的陈述答案。
### Conclusion
单轮生成已经实现了强大的准确性和质量，多轮生成则进一步为人类-人工智能协作提供了机会。
## 71. `cs.CV` - Do Do Protective Perturbations Really Protect Portrait Privacy on Real-world Image Transform? [PDF](https://arxiv.org/pdf/2604.23688), [HTML](https://arxiv.org/abs/2604.23688)
### Authors
Ruiqing Sun,Xingshan Yao,Zhijing Wu,Tian Lan,Chenhao Cui,Huiyang Zhao,Jialing Shi,Chen Yang,Xianling Mao
### Background
随着面部生成（Face Generation, Talking Face, Generating (TFG)) 技术的不断进步，,n用户和隐私保护的需求也越来越高.尽管现有的主动防御方法依赖于像素级别的干扰（但是在实际实际设备间传输和的场景中,图像不可避免地会遭遇各种像素值变
### Innovation
本文提出了一个简洁但有效的净化框架，利用实际的现实设备间变换导致的脆弱性性 
### Conclusion
实验结果表明，基于像素级变采的保护影变具有力能在成像的设备间变换中保持有效 
## 72. `cs.CV` - 聚焦分析，推理决策：基于贝叶斯推理引导的聚焦视觉语言模型高效远场异常检测 [PDF](https://arxiv.org/pdf/2604.23724), [HTML](https://arxiv.org/abs/2604.23724)
### Authors
Xiaowei Mao,Bowen Sui,Weijie Zhang,Yawen Yang,Shengnan Guo,Shilong Zhao,Jiaqi Lin,Tingrui Wu,Youfang Lin,Huaiyu Wa
### Background
高速公路视频异常检测对于安全管理至关重要。然而，识别跨多种场景下的异常行为，尤其是远距离目标表现出微小异常车辆运动时，仍然具有挑战性。现有的视觉-语言模型虽然在语义推理方面表现出色，但由于处理全局帧，会导致对这些远距离对象的关注度降低，且会带来巨大的计算成本。
### Innovation
我们提出了一种异步协作框架VIBES，该框架利用BEV视角指导的视觉-语言模型。为了克服在多种高速公路环境下的较差泛化能力，我们引入了在线贝叶斯推理模块，该模块持续评估车辆轨迹以动态更新正常驾驶行为的概率边界，作为异步触发器，精确地在空间和时间上定位异常。与处理连续视频流相比，VLM仅处理由触发器指示的局部视觉区域，这种针对的视觉输入防止了关注度的稀释，并使语义推理变得精确。
### Conclusion
大量的评估结果显示，VIBES在检测远距离异常方面提高了准确性，降低了计算开销，实现了高实时效率和可解释性，同时展示了对多种高速公路条件的高度通用性。
## 73. `cs.CV` - ClawMark: 一个面向多轮、多日、多模态同事代理的动态世界基准 [PDF](https://arxiv.org/pdf/2604.23781), [HTML](https://arxiv.org/abs/2604.23781)
### Authors
Fanqing Meng,Lingxiao Du,Zijian Wu,Guanzheng Chen,Xiangyan Liu,Jiaqi Liao,Chonghe Jiang,Zhenglin Wan,Jiawei Gu,Pengfei Zhou,Rui Huang,Ziqi Zhao,Shengyuan Ding,Ailing Yu,Bo Peng,Bowei Xia,Hao Sun,Haotian Liang,Ji Xie,Jiajun Chen,Jiajun Song,Liu Yang,Ming Xu,Qionglin Qiu,Runhao Fu,Shengfang Zhai,Shijian Wang,Tengfei Ma,Tianyi Wu,Weiyang Jin,Yan Wang,Yang Dai,Yao Lai,Youwei Shu,Yue Liu,Yunzhuo Hao,Yuwei Niu,Jinkai Huang,Jiayuan Zhuo,Zhennan Shen,Linyu Wu,Cihang Xie,Yuyin Zhou,Jiaheng Zhang,Zeyu Zheng,Mengkang Hu,Michael Qizhe Shieh
### Background
语言模型代理正在被广泛用作跨多个工作日的持续合作同事，以协助用户。现有基准未充分评估这种长时间、多场景任务的完整情况，因为这些基准通常仅在一个静态场景中运行，并且主要集中在文本数据上。现有环境的变化（如新邮件、日程变化、知识库更新等）未被现有基准有效模拟。
### Innovation
ClawMark 是一个基于多轮、多日任务的同事代理基准，它提供了一个多态沙箱服务环境来模拟持续变化的环境，并采用基于规则的验证方法。它涵盖了13种专业场景和5种状态沙箱服务（文件系统、邮件、日程、知识库、表格），并通过1537个确定性的 Python 检查器在任务执行后进行评分。
### Conclusion
ClawMark 对七个前沿代理系统的评估结果显示，最佳模型的加权得分为75.8，但最重要的任务成功率仅为20.0%，表明在完成端到端工作流方面的进展较少。细致粒度的分析表明，性能在首次外生环境更新后显著下降，这突显了对变化状态进行适应这一关键挑战。研究释放了基准、评估框架和构建管道以支持可重复的同事代理评估。
## 74. `cs.CV` - From Noisy Historical Maps to Time-Series Oil Palm Mapping Without 2 2 2 0  2  2  2  4 [PDF](https://arxiv.org/pdf/2604.23776), [HTML](https://arxiv.org/abs/2604.23776)
### Authors
Nuttaset Kuapanich,Juepeng Zheng,Bohan Shi,Jiaying Liu,Jiayin Jiang,Jiatao Huang,Shenghan Tan,Qingmei Li,Haohuan Fu
### Background
在东南亚， 牌种植种植园的精确监测对于平衡经济发展与环境保育至关重要。。然而现有的种植园测绘图通常存在空间分辨率低和缺乏近期时间覆盖的问题， 这种情况严重阻碍了对快速的土地利用变化进行有效的监控。
### Innovation
本文研究提出了一种深度学习框架，以从2  1  2  2 幍至 t 2  through  2  5  4 ?，至生成1  f  f  t t  3  1  4 ?(和解析度为 1  t  f  )  f  的油棕种植园地图，利用 Sentinel-卫星影像，并 不需要进行人工注释。为了解决粗略的 t  1  1  1  3  4 ? 解历历 t t  1  1  1  3  4  ?标签与和 t  1  1  3  4 ?高解析度影像图像之间的解析度过匹配问题这些问题采取了基于不确定度基于互信息信息量(DMI优化的 U-Net 架构。这一方法有效地减少了由于高噪声所带来的影响。
### Conclusion
实验证结果方法在 t  5  5  8  6% 迍行验证中取得了整体准确率分别为 t  5  6  4  6％、9  8  3  5  3%正确%7%, 63 t  5  3  5  4  和  8  0  6  6% 对应 t  8  1  1  5  5  4 ?-  0  4 t  8  2  2  3  44  0 t  8  2  5  3  4  4 t  8 的 t 2  8  2  4  4 ?( 年 t  5  4  4 t 高解析度地图提供关键数据用于监测该地区的可持续承诺和森林退化趋势，并 所生成的数据集在此 f  URL 被公共发布。进一步的分析显示油棕覆盖在该 地区 在 t  6  4  4  6 ?( 年达到顶峰之后下降了
## 75. `cs.CV` - VitaminP：跨模态学习使从常规组织学中实现细胞整体分割成为可能 [PDF](https://arxiv.org/pdf/2604.23799), [HTML](https://arxiv.org/abs/2604.23799)
### Authors
Yasin Shokrollahi,Karina B. Pinao Gonzales,Elizve N. Barrientos Toro,Paul Acosta,Patient Mosaic Team,Pingjun Chen,Yinyin Yuan,Xiaoxi Pan
### Background
精确的组织细胞和核分割对于精准病理学和空间组学至关重要，但传统的苏木精和伊红（H&E）染色提供的细胞质对比度有限，限制了对核以外区域的分析。多重免疫荧光（mIF）可以实现精确的细胞整体界定，但其实施成本高且使用不便。目前缺乏一种有效的方法直接从H&E图像中实现细胞整体分割。
### Innovation
VitaminP是一种跨模态学习框架，可以从H&E图像中实现细胞整体分割。它通过学习配对的H&E-mIF数据，将mIF中的分子边界信息转移到H&E图像中，解决了细胞质对比度不足的问题。通过这一方法，VitaminP不仅超越了现有的四种最先进方法，还能够在未见数据集上进行泛化，包括一个内部数据集，涵盖了24种罕见癌症类型。此外，还开发了VitaminPScope，一个开源平台，提供可扩展的推理界面，促进广泛采用。
### Conclusion
通过大规模公共数据集训练得到的VitaminP，显著提升了H&E图像中的细胞整体分割准确度，成为一种有效且通用的策略来克服缺少的生物结构。VitaminPScope的推出使得这一技术应用更加广泛。
## 76. `cs.CV` - Latent Inter-Frame Pruning: A Training-Free Method Bridging Traditional Video Compression and Modern Diffusion Transformers for Efficient Generation [PDF](https://arxiv.org/pdf/2604.23858), [HTML](https://arxiv.org/abs/2604.23858)
### Authors
Dennis Menn,Chih-Hsien Chou
### Background
视频生成能够生成逼真的视频，但计算成本高、速度慢，这限制了其在实时应用中的使用。
### Innovation
提出了Latent Inter-frame Pruning框架，通过自动编码器在Latent Diffusion Model (LDM)框架下编码视频潜变量，去除冗余，减少计算负担和提高吞吐量；提出了Attention Recovery机制解决直接剪裁造成的视觉伪影问题。
### Conclusion
通过所提出的方法，视频编辑的吞吐量提高了1.44倍，在NVIDIA RTX 6000上达到了12.44 FPS，同时保持视频质量；期望这项工作能激发更多将传统视频压缩方法与现代视频生成流水线融合的研究工作。
## 77. `cs.CV` - 极端视角下映射车牌可恢复性以支持城市机会性传感 [PDF](https://arxiv.org/pdf/2604.23814), [HTML](https://arxiv.org/abs/2604.23814)
### Authors
Igor Adamenko,Orpaz Ben Aharon,Yehudit Aperstein,Alexander Apartsin
### Background
城市环境中包含许多用于特定目的的成像传感器，包括ATM机、体佩戴相机、监控摄像头和仪表盘摄像头。在机会性传感的范式下，这些传感器可以重新利用于次要推理任务，如车牌识别。然而，这类图像中的兴趣对象经常受到噪声干扰、低分辨率且拍摄角度极端。近年来，基于人工智能的图像恢复技术可以从严重退化的图像中恢复有用信息。主要挑战在于确定哪些退化参数允许可靠恢复以及哪些会导致推理失败。
### Innovation
本文引入了可恢复性图，这是一种适用于多种任务的方法，用于量度可靠的边界。该方法结合了密集的合成退化参数扫描和两种总结指标：边界下的面积曲线（估计可恢复参数空间的分数），以及可靠性分数（捕捉该区域内的失败频率和严重性）。研究展示了方法在具有现实摄像机缺陷的极端视角下从图像中恢复车牌识别的结果。几种图像恢复架构（包括U-Net、Restormer、Pix2Pix和SR3扩散）进行了训练和评估。最佳模型约恢复了参数空间的93%。
### Conclusion
多个模型的相似结果表明，成像几何设置恢复极限，而非架构本身。
## 78. `cs.CV` - 重点关注关键区域：多阶段ROI感知细化在胎儿超声成像中保留解剖结构的重建 [PDF](https://arxiv.org/pdf/2604.23839), [HTML](https://arxiv.org/abs/2604.23839)
### Authors
Ines Abbes,Mahmood Alzubaidi,Mowafa Househ,Khalid Alyafei,Marco Agus,Samir Brahim Belhaouari
### Background
测量关键的超声任务通常依赖于一小部分解剖区域，而全局重建指标作为临床准确性的代理并不可靠。该研究介绍了在多医院域迁移下，一种基于ROI（感兴趣区域）感知的表示学习框架，用于初次孕期内囊透明度（NT）筛查。
### Innovation
提出了一种两阶段卷积自编码器（CAE）的框架，通过MS-SSIM首先学习全局一致的128维潜在编码，再通过强度（L1）和归一化的Sobel边缘约束细化NT ROI。损失权重由基于梯度的校准自动从分项梯度幅度中初始化，以结合异质目标。
### Conclusion
ROI细化提高了全局及测量相关的质量：在标准验证集上PSNR增加了0.27 dB，在未见测试集上增加了0.29 dB；ROIMAE减少了8.87%（验证集）和6.43%（未见测试集）；ROI边缘MAE在源医院减少了11.10%，在未见医院减少了4.90%。冷冻的潜在探条提供了进一步的泛化证据，在未见站点处解剖来源的可预测性降低，而OOD检测保持强劲。同样的ROI感知细化原则在其他胎儿生物测量目标（如头臀长（CRL）、鼻骨（NB））和其他临床决策倚重小ROI的医学影像设置中亦可行。
## 79. `cs.CV` - 风险意识稳健学习: 在医疗图像分类标签噪声下的临床风险降低 [PDF](https://arxiv.org/pdf/2604.23875), [HTML](https://arxiv.org/abs/2604.23875)
### Authors
Maycon R. S. Pereira,Filipe R. Cordeiro
### Background
在医疗图像分类中，标注错误是一个普遍存在的挑战，这些错误主要是由于观察者之间的差异性和诊断的不明确性引起的。虽然已经提出了一些抗噪声学习方法，但它们的评估主要依赖于准确率指标，忽略了异质性错误成本的临床影响。在医疗诊断中，漏诊的代价远远高于误诊，因为延迟治疗会直接影响患者的预后。
### Innovation
本文提出了一种系统的有风险意识的评估方法，对最先进的抗噪声方法Coteaching、DivideMix、UNICON以及基于GMM的过滤方法进行了评估。在无噪声和40%的标签噪声条件下，使用二值化的DermaMNIST和PathMNIST数据集。引入了成本敏感的全局风险公式，明确惩罚漏诊。实验结果表明，最先进的抗噪声方法并不保证临床安全性，而且将成本敏感优化集成到抗噪声训练中可以显著减少临床风险，同时保持模型的实用性。
### Conclusion
研究发现，抗噪声学习必须通过临床风险的视角进行评估，结合稳健训练与成本敏感优化可以在噪声标签的医疗影像场景中实质性地降低风险。
## 80. `cs.CV` - AMAVA: 自适应运动感知的视频转音频框架用于视力受损辅助 [PDF](https://arxiv.org/pdf/2604.23909), [HTML](https://arxiv.org/abs/2604.23909)
### Authors
Benjamin Klein,Kazi Ruslan Rahman,Sanchita Ghose
### Background
盲人和低视力个体使用的导航辅助工具在传达动态的现实环境方面存在困难，导致由于持续的未分隔反馈而产生认知超载。本研究旨在解决这一问题。
### Innovation
提出了AMAVA，一种新的实时视频转音频框架，能够将移动设备视频转换为与场景相关的声效或合成语音描述。通过轻量级的人工智能分类模型区分低运动和高运动场景，结合实时文本转语音合成 pipeline 来增强环境感知。该框架包含基于提示的缓存和类别特定的节流机制，以避免听觉拥挤并降低延迟。
### Conclusion
研究通过实时导航实验比较了单杖与AMAVA辅助，实验结果显示用户信心和感知安全性有了显著提升。
## 81. `cs.CV` - AD-Relight: 通过扩散先验进行照明转换的无训练遮幅重新光照 [PDF](https://arxiv.org/pdf/2604.24407), [HTML](https://arxiv.org/abs/2604.24407)
### Authors
Rameshwar Mishra,A V Subramanyam
### Background
随着流媒体服务中内容消费的增加，对个性化内容的需求也在增长，个性化广告对于提升用户参与度和广告效果至关重要。现有广告插入框架通常使用简单的几何扭曲，忽略了场景的照明条件；最新的基于扩散的对象插入和重新光照模型也难以准确地重新照亮新插入的广告遮幅，因为它们并未经过广告遮幅数据的训练，为广告遮幅专门训练这样的模型需要数百万张图像。
### Innovation
本文提出了AD-Relight，一个无需训练的多阶段框架，该框架可以在测试时间上适应基于扩散的重新光照模型，以重新照亮新添加的Photoshop生成的广告遮幅。AD-Relight比现有重新光照基线和基于简单扭曲的广告放置方法性能更优。
### Conclusion
通过广泛评估，AD-Relight明显优于其他重新光照基线和基于简单扭曲的现有广告放置方法。用户研究进一步表明，参与者更偏好AD-Relight的输出结果。
## 82. `cs.CV` - AutoGUI-v2: 多模态GUI功能理解综合基准 [PDF](https://arxiv.org/pdf/2604.24441), [HTML](https://arxiv.org/abs/2604.24441)
### Authors
Hongxin Li,Xiping Wang,Jingran Su,Zheng Ju,Yuntao Chen,Qing Li,Zhaoxiang Zhang
### Background
自主导航图形用户界面（GUI）的智能代理有可能彻底改变数字生产力。然而，实现真正的数字自主性超出了简单的元素匹配反应，需要一种预测界面动态的先验心智模型，以及预见交互结果的能力。尽管现代视觉-语言模型具备感知能力，现有的基准测试仍然主要是专注于黑盒任务完成或静态浅层定位，而没有真正评估代理是否真正理解GUI的隐含功能和转换逻辑。为了弥补这一差距，我们提出了AutoGUI-v2，这是一个全面的基准测试，旨在评估深层次的GUI功能理解和交互结果预测能力。
### Innovation
我们使用新颖的视觉-语言模型与人类协作的流程构建了基准测试，该流程递归解析跨平台屏幕截图，生成多样性的评估任务。AutoGUI-v2提供了2,753个横跨六个操作系统任务，全面测试代理在区域和元素级别语义、定位和动态状态预测方面的能力。我们的评估揭示了模型之间显著的差异：开源模型在功能定位方面表现优异，而商业模型在功能描述方面占优。但所有模型在复杂的交互逻辑下都表现不佳，这表明深层次的功能理解仍然是一个重大挑战。通过系统性测量这些基础能力，AutoGUI-v2为下一代GUI代理的进步提供了新的视角。
### Conclusion
AutoGUI-v2为评估和促进GUI代理的下一代发展提供了一个全新的视角，揭示了视觉-语言模型在深层次GUI功能理解和交互结果预测方面的不足，并提出了未来工作方向。
## 83. `cs.CV` - Zero-to-CAD: 完全无需真实数据合成可解释的百万级CAD程序 [PDF](https://arxiv.org/pdf/2604.24479), [HTML](https://arxiv.org/abs/2604.24479)
### Authors
Mohammadmehdi Ataei,Farzaneh Askari,Kamal Rahimi Malekshan,Pradeep Kumar Jayaraman
### Background
现有的3D数据集主要由边界表示(B-Reps)或网格组成，这些表示方式去除了CAD模型的构造历史信息，即参数化的设计意图描述。这使得在大规模3D数据集和参数化理解之间存在差距。
### Innovation
本文提出了Zero-to-CAD框架，这是一种用于合成可执行CAD构造序列的可扩展方法。该方法通过在反馈驱动的CAD环境中嵌入大型语言模型（LLM），系统能够迭代生成、执行和验证代码，以确保几何有效性并促进操作多样性。这种方法能够合成大约一百万个满足几何和操作多样性要求的可执行CAD序列。同时，作者还创建了一个包含100,000个高质量模型的精选数据集，用于几何多样性验证。此外，利用合成数据微调了一个视觉语言模型，使其能从多视角图像中重建可编辑的CAD程序，相比其他基线模型表现更优。
### Conclusion
Zero-to-CAD框架填补了几何规模和参数化可解释性之间的空白，提供了一种无需实际构造历史数据的宝贵资源，有助于下一代CAD AI的发展和应用。
## 84. `cs.CV` - DYMAPIA：检测AI生成视频篡改的多多框架 [PDF](https://arxiv.org/pdf/2604.24426), [HTML](https://arxiv.org/abs/2604.24426)
### Authors
Md Shohel Rana,Andrew H. Sung
### Background
随着AI生成媒体的迅速发展，，,
### Innovation
1YMAPIA是一种多多创新点包括三个部分方面：数组 
### Conclusion
D通过对FF++、、Celeb on-DF和和以及VDFD等基准基准测试在准确确定性能上的领衔，DYMAPIA展示了其在实D时D时代的取证任务适用性,能力D，可以包括包括这此外涵盖媒体核实D、D不实信息打击D以及内容过滤DD等多任务D
## 85. `cs.CV` - 当VLMs纠正学生答案时：识别和惩罚多行手写数学OCR中的过度纠正 [PDF](https://arxiv.org/pdf/2604.22774), [HTML](https://arxiv.org/abs/2604.22774)
### Authors
Jin Seong,Wencke Liermann,Minho Kim,Jong-hun Shin,Soojong Lim
### Background
当前的OCR基准测试未能准确评估教育AI系统在手写数学转录方面的表现。大多数先前研究仅关注单行表达式，使用BLEU等词法度量标准进行评估，这些方法无法全面评估多行学生解决方案的语义推理。这导致视觉语言模型在转录学生工作时过度纠正，从而隐藏了教育评估需要发现的错误。
### Innovation
本文提出了首个针对多行手写数学OCR的系统性研究，揭示了视觉语言模型在转录学生工作时存在的过度纠正问题，并提出了PINK（Penalized INK-based score）评分方法，结合大型语言模型进行评分，并明确惩罚过度纠正。研究采用FERMAT数据集对15个最先进的VLMs进行了全面评估，结果显示PINK评分方法在评估多行手写数学OCR方面比BLEU更为可靠。
### Conclusion
PINK评分方法在真实世界应用中的表现优于BLEU，更符合人类专家的判断（偏好度为55.0%），为教育环境下的手写数学OCR评估提供了更可靠的框架。同时，这种方法为未来改进视觉语言模型和大型语言模型提供了指导。
## 86. `cs.CV` - 儿童患者通用无CTPET衰减和散射校正 [PDF](https://arxiv.org/pdf/2604.22894), [HTML](https://arxiv.org/abs/2604.22894)
### Authors
Jia-Mian Wu,Jun Liu,Siqi Li,Xiaoya Wang,Shibai Yin,Huanyu Luo,Lingling Zheng,Qiang Gao,Jigang Yang,Tai-Xiang Jiang
### Background
基于CT的衰减和散射校正在定量PET中能提升检测精度，但会增加辐射暴露，尤其在儿科影像中不理想。现有无CT方法通常在同质环境下训练，容易出现扫描器或示踪剂差异导致的性能下降，影响其临床应用。
### Innovation
提出了一种通用PET校正网络（GPCN），这是一种双域网络，旨在确保在不同扫描器或示踪剂条件下仍有鲁棒的校正效果。该网络结合了多波段上下文精炼模块和频率意识的光谱解耦模块，能够通过同时实现多波段空间上下文建模与非对称频率光谱解耦，明确分离不变的拓扑结构和领域敏感的噪声，从而实现精准的定量恢复和定位。
### Conclusion
通过联合训练和零样本跨域评估，GPCN在未见过的扫描器-示踪剂组合上仍能保持稳定的定量准确性，优于现有基准模型，并且减少了儿童PET检查中的辐射剂量，具有临床应用价值。
## 87. `cs.CV` - 利用卫星基础模型提升财富监测 [PDF](https://arxiv.org/pdf/2604.23166), [HTML](https://arxiv.org/abs/2604.23166)
### Authors
Zhuo Zheng,Iván Higuera-Mendieta,Richard Lee,David Newhouse,Talip Kilic,Stefano Ermon,Marshall Burke,David B. Lobell
### Background
贫困统计数据可以指导社会政策，在许多低收入和中等收入国家中，收集这些数据的普查和家庭调查成本高、频率低、更新缓慢且有时可能存在错误。卫星图像提供了全球覆盖范围和大规模预测生计的可能性，但现有的利用图像或其他非传统数据预测生计的方法往往无法可靠地识别局部差异，并且随着时间推移会退化。
### Innovation
本文介绍了Tempov，一种通过自我监督预训练在三百万对双向Landsat图像上并利用参数高效微调以适应稀疏调查标签的卫星基础模型。该模型能够实现大规模高分辨率的财富地图绘制和动态测量，包括零样本近期预测最多可追溯十年的数据标签，回顾性预测和十年变化跟踪，并优于现有神经网络和地理空间基础模型基线。在低标签条件下，Tempov只需调查样本的10%就能达到可竞争的准确度，表明对昂贵的标签收集依赖性显著减少。该模型能够适应和扩展到非洲及其他地区，并生成整个非洲高分辨率的财富和财富变化十年地图。
### Conclusion
我们开源的方法提供了从常规收集的卫星数据及时、规模化、低成本监测财富和贫困的途径。
## 88. `cs.CV` - 有限标记数据下的多模态人体活动识别的对比学习 [PDF](https://arxiv.org/pdf/2604.23281), [HTML](https://arxiv.org/abs/2604.23281)
### Authors
Long Jing,Zhixiong Yang,Yajun Zhang,Xinlong Feng
### Background
人体活动识别是推动各类新兴应用的基础。近年来，研究者利用多源传感器协同感知技术来捕捉复杂多变的人体活动，但多模态人体活动感知通常面临模态间高度异质性数据和标签稀少的问题，导致现有解决方案难以满足现实需求。
### Innovation
本文提出了一种名为CLMM的一般对比学习框架，该框架有效地利用了有限的标注数据进行多模态识别。CLMM采用新颖的两阶段训练策略：首先，利用CNN-DiffTransformer编码器捕捉跨模态共享信息，提取局部和全局特征，并使用硬正样本加权算法增强梯度传播，加强共享学习。其次，结合质量导向的注意力机制和双向门控单元捕获模态特殊信息，并采用主要-辅助协作训练策略融合共享和模态特殊信息。
### Conclusion
在三个公开数据集上的实验结果表明，CLMM在识别精度和收敛性能上显著优于现有的基准方法。
## 89. `cs.CV` - 基于高斯点绘的点扩散函数重建方法在散射光学断层成像中的应用 [PDF](https://arxiv.org/pdf/2604.23675), [HTML](https://arxiv.org/abs/2604.23675)
### Authors
Jingjing Jiang
### Background
散射光学断层成像（DOT）技术是一种用于测量生物组织中吸收系数的空间分布的方法。传统的重建框架在处理强散射介质中的光传输建模时准确性较差，并且计算成本高。Gaussian Splatting (GS)在渲染应用中用于建模动态光影效果，通过将吸收系数表示为一系列优化的高斯小体素的叠加，实现对扩散系数的精确描述。该技术首次将GS算法应用于光的扩散域，在此领域，光线传输函数被替换为扩散传输函数，从而更好地模拟强散射介质中的光传输。
### Innovation
该工作提出了一种新的基于高斯点绘的图像重建框架——GS-DOT（Gaussian Splatting-based Diffuse Optical Tomography）。该框架利用高斯小体素来近似吸收系数，通过分析梯度和Adam优化方法进行优化。这种方法能够准确地建模强散射介质中的光传输，并且对噪声具有高度鲁棒性。此外，GS-DOT方法还使内存需求大幅减少。
### Conclusion
在合成组织模型上的验证结果表明，GS-DOT方法在局部化和量化重建吸收图谱方面具有高度的准确性，并且对噪声具有高度鲁棒性，显示了巨大的内存需求减少。该框架为DOT成像中的吸收系数重建提供了一种创新的方法，具有广泛的应用前景。
## 90. `cs.CV` - 通过动态多模态检索个性化因果驱动音频面部运动 [PDF](https://arxiv.org/pdf/2604.23692), [HTML](https://arxiv.org/abs/2604.23692)
### Authors
Xuangeng Chu,Yu Han,Wei Mao,Shih-En Wei
### Background
对于沉浸式数字交互而言，基于音频的面部动画至关重要。然而，现有的框架无法在实时传输和高保真个性化之间找到平衡。当前方法通常依赖于会导致延迟的音频前瞻，或者需要用户预先编码静态嵌入，这无法捕捉到动态的个性特征。
### Innovation
提出了一个端到端的因果框架，用于通过动态多模态风格检索进行个性化因果面部运动生成。该框架引入了两个关键创新：（1）一种时间上的层次运动表示，能够捕获全局时间上下文和高频细节，同时保持解码因果关系；（2）一个联合查询音频和运动的多模态风格检索器，能够动态地提取风格先验而不破坏因果关系。这一机制允许根据模板的数量和内容进行扩展的个性化。
### Conclusion
通过将这些组件整合到因果自回归架构中，该方法在口型同步准确性、身份一致性以及感知现实感方面显著优于最先进的方法，得到了广泛的定量评估和用户研究的支持。
## 91. `cs.CV` - ELSA：快速且内存轻量的精确线性扫描注意力 [PDF](https://arxiv.org/pdf/2604.23798), [HTML](https://arxiv.org/abs/2604.23798)
### Authors
Chih-Chung Hsu,Xin-Di Ma,Wo-Ting Liao,Chia-Ming Lee
### Background
现有的注意力加速器往往在精确的softmax语义上做出妥协，依赖于融合的张量核内核，或者对深度序列的处理深度限制了FP32吞吐量。
### Innovation
- 对在线softmax注意力进行了算法重写，保留了实数算术中的精确softmax语义，并具有可证明的$?mathcal{O}(u?log n)$FP32相对误差界限。- 将在线softmax更新表示为一个前缀扫描，一个联合一元半群$(m,S,W)$，这样额外需要$O(n)$的内存，并且并行深度为$O(obreakline log n)$。- 独立于张量核指令，可以用Triton和CUDA C++实现，并作为可替换代码部署，无需重新训练或权重修改。- 对于资源受限的边缘设备如Jetson TX2，以及大型GPU如A100，ELSA能以全精度减少并行深度至$O(obreakline log n)$。
### Conclusion
在A100 FP32基准测试中，ELSA相比高效SDPA在1K到16K令牌上实现了1.3到3.5倍的加速，与BERT相比实现了1.97到2.27倍的加速；在Jetson TX2上，ELSA相比Math实现了1.5到1.6倍的加速，并且在LLaMA-13B的负载下，在$obreakline textgreater$32K时可实现17.8%到20.2%的吞吐量增益。在FP16精度下，ELSA在长序列上接近硬件融合的基准，同时保持全精度能力，提供跨平台的高精度推理统一内核。
## 92. `cs.CV` - FlashOverlap: Minimizing Tail Latency in Communication Overlap for Distributed LLM Training [PDF](https://arxiv.org/pdf/2604.24013), [HTML](https://arxiv.org/abs/2604.24013)
### Authors
Rezaul Karim,Austin Wen,Wang Zongzuo,Weiwei Zhang,Yang Liu,Walid Ahmed
### Background
大型语言模型规模的快速增长要求将计算工作负载分配到诸如GPU、TPU和NPU之类的加速器上。然而，这些并行化策略带来了严重影响计算效率的数据通信开销。尽管通信与计算重叠有潜力，但现有的基于数据分割的方法却存在尾部延迟问题。
### Innovation
本文提出了一种新颖的通信与计算重叠技术Flash-Overlap，它通过替代传统的reduce-scatter和all-gather集体操作，使用拆解的P2P通信并调度分区计算来实现精简的重叠。该技术提供了一个减少通信开销的精确算法，消除了尾部延迟，并且与数据并行训练以及各种张量级并行策略兼容，包括TPSP和UP。
### Conclusion
实验结果显示，该技术能够实现更低的尾部延迟、更好的Model FLOPS利用率（MFU）和高吞吐量。
## 93. `cs.CV` - LLM-Guided Autonomous Floor Plan Parsing for Reliable Indoor Navigation of Blind and Low-Vision Individuals [PDF](https://arxiv.org/pdf/2604.23970), [HTML](https://arxiv.org/abs/2604.23970)
### Authors
Aydin Ayanzadeh,Tim Oates
### Background
对于盲人和低视力(LV)人群来说， 室内导航是一个关键的可达性挑战. 炮现有系统依赖于昂贵的楼顶基础设施. 本研究提出一种代理框架, 尵通过单单个楼层平面平面施工图转化为结构化的可检索知识库，以生成轻轻导航指令 with 茨确保导航基础设施轻.
### Innovation
该框架通过 on -单一楼层平面图创建结构化检索知识库并 mea生成.getBytes指导导航指令 with on茨基础设施.轻...sein.线以下几个方面:?改:on个算法: on二维图解析为三维空间知识图 on me多个理解反馈纠错机制 on he个路径规划器安场所评估模块进行动态评估潜在危险因素. on径路径. on以个响应优化机制增强实现单一入口大型语言模型(LLn一呼叫比例. on泰提高导航准确率.
### Conclusion
通过 onon一呼叫比例 on on多个on中在UMon umbc数学和心理楼(M on on6e-on三楼以及on cvc-cp基准测试 on on个成功率表明 on on可以工作 omen单解决单次语言模型 on on一个呼叫的比例 on on个成功有着具有一致的改进 on on on个单单基准线 on其中一个普及解决方案不为盲和其他和 on内 building结构化基础设施 on on on个可用室内导航 for LV人群.
## 94. `cs.CV` - 泛化最大均值偏差：核化功能Bregman距离 [PDF](https://arxiv.org/pdf/2604.24047), [HTML](https://arxiv.org/abs/2604.24047)
### Authors
Russell Tsuchida,Frank Nielsen
### Background
Bregman发散在统计学、机器学习和计算信息几何中发挥着重要作用。特别是在机器学习领域，它们在聚类、指数族、参数估计和优化等方面占据核心地位。然而，尽管如此，希尔伯特空间特别是再生核希尔伯特空间的完整工具箱尚未系统地开发并应用于功能性Bregman发散，其中点是函数而非有限维参数向量。虽然其他类型的功能性Bregman发散已有研究，但它们通常在Banach空间中进行，而非与机器学习中常用的内核方法和希尔伯特空间几何直接对齐。
### Innovation
研究功能性Bregman发散在希尔伯特空间上的应用，特别利用自对偶配对和里斯表示人确保了更加便捷的数学处理。进一步将Bregman生成器专门化为涉及内核均值嵌入的组成，使得发散更容易估计。讨论了在聚类、通用估计、鲁棒估计和生成建模中的应用，并将其方法与其他类型的Bregman发散进行了对比。
### Conclusion
本文研究了在希尔伯特空间上的功能性Bregman发散，通过利用自对偶配对和里斯表示性，简化了发散的处理和估计。这些方法在聚类、通用估计、鲁棒估计和生成建模中表现出良好的应用前景，并与传统的Bregman发散进行了对比分析。
## 95. `cs.CV` - 从粗到真实：生成性渲染应用于大量动态场景 [PDF](https://arxiv.org/pdf/2601.22301), [HTML](https://arxiv.org/abs/2601.22301)
### Authors
Gonzalo Gomez-Nogales,Yicong Hong,Chongjian Ge,Marc Comino-Trinidad,Dan Casas,Yi Zhou
### Background
传统的渲染管道依赖于复杂的资产、精确的材质和照明以及大量的计算资源来生成逼真的图像，但它们在大规模动态场景中的可扩展性和逼真度仍然存在问题。
### Innovation
本文提出了C2R (从粗到实) 生成性渲染框架，该框架能够从粗略的3D模拟生成具有现实风格的都市人群视频。该方法使用粗略的3D渲染来显式控制场景布局、摄像机运动和人类轨迹，并通过文本提示驱动学习神经渲染器生成真实的外观、照明和精细动态。该方法采用两阶段合成-现实域对冲策略，首先从大规模的实际视频中学习强大的生成先验，然后通过引入少量合成的粗到细配对数据来锚定跨域共享的隐式时空特征，从而增强可控性。
### Conclusion
该系统实现了粗略到精细的控制，能够适应多种CG和游戏输入，并能使用少量的3D输入生成时空一致、可控且逼真的都市场景视频。
## 96. `cs.CV` - 通过提示控制扩散增强方法缓解长尾偏差 [PDF](https://arxiv.org/pdf/2602.04749), [HTML](https://arxiv.org/abs/2602.04749)
### Authors
Buddhi Wijenayake,Nichula Wasalathilake,Roshan Godaliyadda,Vijitha Herath,Parakrama Ekanayake,Vishal M. Patel
### Background
在高分辨率遥感图像的语义分割中，长尾类不平衡仍然是一个基本障碍，其中主导类塑造了学习的表示，而稀有类则系统地被分割不足。在如LoveDA之类的跨域设置中，这种挑战更严重，因为这些设置表现出明显的城乡分隔，并且跨域之间的外观差异和类别频率统计是不一致的。
### Innovation
本文提出了一个提示控制的扩散增强框架，该框架能够生成带有明确语义组成和域控制的标签-图像样本对，使用户能够针对欠代表的类别进行目标化增强，而不是随意扩展数据集。该方法首先使用一种域感知、掩码、比例条件连续扩散模型合成满足类别比例目标且保持真实空间共现性的布局，然后使用ControlNet引导的扩散模型从这些布局中生成逼真的、一致于域的图像。
### Conclusion
在真实数据中混合生成的样本对可以增强多种分割模型，特别是在少数类和域迁移的情况下，这表明更好的下游分割来自于以适当的比例添加合适的样本。相关的源代码、预训练模型和合成数据集可在https://link 公开获得。
## 97. `cs.CV` - EAGLE: 专家增强的注意力引导在多模态大型语言模型无调优工业异常检测中的应用 [PDF](https://arxiv.org/pdf/2602.17419), [HTML](https://arxiv.org/abs/2602.17419)
### Authors
Xiaomeng Peng,Xilang Huang,Seon Han Choi
### Background
多模态大型语言模型（MLLMs）可以为工业异常检测提供语义描述和异常推理，但它们在二分类检测准确性上仍然落后于专业异常检测器。现有方法通过微调MLLMs或训练桥梁模块来对齐专家输出与MLLM输入，限制了它们在不同模型基础下的灵活性。
### Innovation
提出了一种无需微调的框架EAGLE，它将专家异常检测器与冻结的MLLMs集成。EAGLE 包括基于阈值引导的提示选择（TGPS），该方法从专家模型统计中估计一个正常得分阈值，并选择文本和视觉提示，以及基于置信度的注意力锐化（CAAS），当专家置信度低时，使MLLM的注意力转向视觉证据。
### Conclusion
EAGLE 提高了五个不同MLLM 基础模型的准确性，分别达到 94.6% 和 88.6% 的精度，性能与基于微调的方法相当，同时保持了异常感知的推理能力。进一步分析发现，正确的异常预测与更集中在真实缺陷区域的关注点有关，EAGLE 一致地加强了这种对齐。
## 98. `cs.CV` - LoGeR: 长上下文几何重建与混合内存 [PDF](https://arxiv.org/pdf/2603.03269), [HTML](https://arxiv.org/abs/2603.03269)
### Authors
Junyi Zhang,Charles Herrmann,Junhwa Hur,Chen Sun,Ming-Hsuan Yang,Forrester Cole,Trevor Darrell,Deqing Sun
### Background
现有的前端几何基础模型虽然能够在短时间内重建强大的短窗体，但是将它们扩展到分钟级长度的视频存在瓶颈，主要问题是注意力复杂度的平方增长或递归设计中的有效内存限制。
### Innovation
提出了LoGeR（Long-context Geometric Reconstruction）架构，该架构能够在无需后处理的情况下将密集的3D重建扩展到非常长的序列。LoGeR通过处理视频流的块，并利用强烈的双向先验信息来实现高保真度的内部块理由。为了应对块边界间的连贯性挑战，提出了一个基于学习的混合内存模块，该模块结合了参数化测试时训练（TTT）内存以锚定全局坐标框架并防止尺度漂移，以及非参数滑动窗口注意力（SWA）机制以保留未压缩的上下文进行高精度的相邻对齐。
### Conclusion
实验结果表明，LoGeR在标准基准测试和新重新利用的VBR数据集（具有最长到19k帧的序列）上的性能超过了先前的前沿前端方法，使长期一致的重建成为可能。
## 99. `cs.CV` - 利用几何参考的3D场景表示增强MLLM的空间推理能力 [PDF](https://arxiv.org/pdf/2603.08592), [HTML](https://arxiv.org/abs/2603.08592)
### Authors
Jiangye Yuan,Gowri Kumar,Baoyuan Wang
### Background
尽管多模态大型语言模型（MLLMs）在2D视觉理解方面取得了显著成功，但它们在处理3D空间方面的能力仍然有限。
### Innovation
提出了几何参考3D场景表示（GR3D），将对象在图像中的独特ID与其3D几何属性作为基于这些ID的文本参考进行编码。GR3D使得MLLMs能够利用其高级语言技能进行数学推理，同时紧密地分析2D视觉特征。该方法无需额外训练即可以零样本方式提高复杂的空间推理基准性能。
### Conclusion
在零样本设置下，我们的方法在VSI-Bench和MindCube上的性能分别提升了9%和12%；定性研究进一步表明，GR3D使MLLMs能够使用稀疏输入视图进行复杂的空间推理。
## 100. `cs.CV` - LiquidT̈(Notification: : Efficient Temporal Action Detection on Parallel Liquid-Inspired Temporal Relaxification [PDF](https://arxiv.org/pdf/2604.18274), [HTML](https://arxiv.org/abs/2604.18274)
### Authors
Zepeng Sun,Naichuan Zheng,Hailun Xia,Junjie Wu,Liwei Bao,Xiaotai Zhang
### Background
当前针对长视频序列的动作检测方法尽管有很高的的准确度， 但由于参数量庞大、计算资源消耗高以及依赖于特殊硬件的特点， 在应用通用性性和便携性 方面存在不足。
### Innovation
文章提出一种名为 LiquidT̈(Notification的通知通知窗体已关闭) 的框架, 该框架通过利用液体神经动力学的基本原理， 禂念将指数松弛先的概念转化为并 干并的一种并并采取平行化机制的暂态松弛算子 賔 以避免迭代求ODE)解算的过程而转而采用用 刻矢量化和 的非递归性的方式 降低对标准神经操作的依赖 自从硬件约束和时间长度在线线性复杂度的小功能上 提高了可 敏性和算力紧凑性 的要求 。此外，  通过引入层次衰减率共用策略策略 小划分 了不同暂态松弛力度 从而在不同 摓各级层面上维持 排 扈습니다 从而使优化稳定 坼 幚 ,并 吜隐含修正深层浏览器预处理具 。实验表明 LiquidT̈(通知的通知窗体已关闭)在 THOOS-14 和 ActivityNet-3 的表现与强基线相近 但在模型规模参数和算力资源使用上有所降低 。具体地说  在 THOOS--4 中 LiquidT̈(通知的通知窗体已关闭)获得了 67.46% 的nAP 仅使用 8. 万 参数和 以及 1.17 万亿次浮点 点 次操作 (FLOPs)  从而把参数减少约 60% 左右% 
### Conclusion
总的来说  该方法能够在温和提高动作检测准确度的前提下 通过创新方法和 在硬件适配性上进行了较大改进 箁 以在不同 摫具有砍上 盎求 参数集 以及算力刀功资源需求上 盛建比其他强方法 。
## 101. `cs.CV` - 学习为正确的步骤赋权：视觉生成中的目标感知过程优化 [PDF](https://arxiv.org/pdf/2604.19234), [HTML](https://arxiv.org/abs/2604.19234)
### Authors
Rui Li,Ke Hao,Yuanzhi Liang,Haibin Huang,Chi Zhang,Yun Gu,XueLong Li
### Background
强化学习，特别是Group Relative Policy Optimization (GRPO)，已经成为一种有效的方法来训练具有人类偏好信号的视觉生成模型。但是，它由于粗略的奖励归因机制而受到根本性的限制。现代视觉生成往往使用多个奖励模型来捕捉不同的目标，如视觉质量、运动一致性、文本对齐。现有GRPO流水线通常将这些奖励聚合并均匀传播在整个去噪轨迹中。这种设计忽略了不同去噪步骤在各个阶段的角色，并产生时间错位或不兼容的优化信号。
### Innovation
我们提出了目标感知轨迹归因（OTCA），这是一种细粒度GRPO训练的有结构框架。OTCA包含两个关键组件。轨迹级信用分解估计不同去噪步骤的相对重要性。多目标信用分配在整个去噪过程中根据需要加权并结合多个奖励信号。通过联合建模时间归因和目标级归因，OTCA将粗粒度奖励监督转换为结构化的时间步感知训练信号，更好地匹配基于扩散的生成迭代性质。
### Conclusion
广泛的实验表明，OTCA在多个评估标准上一致地提高了图像和视频生成的质量。
## 102. `cs.CV` - 利用LLM进行评估的语音诱导幻觉评价框架在视觉语言模型中的应用 [PDF](https://arxiv.org/pdf/2604.18803), [HTML](https://arxiv.org/abs/2604.18803)
### Authors
Zhiyuan Jiang,Weihao Hong,Xinlei Guan,Tejaswi Dhandu,Miles Q. Li,Meng Xu,Kuan Huang,Umamaheswara Rao Tida,Bingyu Shen,Daehan Kwak,Boyang Li
### Background
视觉语言模型（VLMs）在需要可靠视觉定位的任务中变得越来越重要，但它们在具有递增命令诱导词句的压力下的行为仍不清楚。现有的幻觉基准测试主要依赖中性提示和二元检测，未能充分说明不同任务类型在不同程度的语言压力下幻觉发生的频次和强度的变化。
### Innovation
Ghost-100是一个程序化构建的基准，包括800个合成图像，跨越八个类别，涵盖三个任务家族：文本非法读性、时间阅读和对象缺席，这些任务按照负面事实的原则设计，确保查询的目标在结构上是不存在的、无法读取的或不确定的。此外，每张图像与五个内置在五级命令强度框架中的指令相关联，以评估语气对幻觉的影响。评估协议采用基于规则的和基于GPT-4o-mini评分，分别评估模型从定位到无根据的承诺的转变比例和幻觉的置信度与具体性。此外，还提供了三个阶段的自动化验证流程，以确认717张图像的合规性。
### Conclusion
评估了九个开放模型的VLMs，发现模型家庭、阅读风格和存在检测子集对提示压力的响应存在显著差异，多个模型在中间语气水平上表现出非单调的敏感性。这些发现表明，聚合指标可能无法准确反映幻觉现象的复杂性。
## 103. `cs.CV` - Training-inference on alignment outweighs framework choice in longitudinal retinal image prediction [PDF](https://arxiv.org/pdf/2604.16955), [HTML](https://arxiv.org/abs/2604.16955)
### Authors
Liyin Chen,Nazlee Zebardast,Mengyu Wang,Tobias Elze,Jason I. Comander
### Background
纵向影像眼像成像预测 有助于临床决策和临床试验分析。纵向眼像 双面板分析对在的获取差异较大，虽然 最近方法 逐渐增加了生成复杂性性 但具体确定在复杂性的必要条件仍不清晰. 籿下研究提议,生成复杂性 应该匹配与任务的条件后熵相匹配对 预测成分后的条件性 盘特征 需联尚于推理接收的对齐. 该研究提出了两个评估指标: raw 图像对的条件熵分析和预测后条件浓度分析. 这中 评估了不同 兲台框架 在不同 鶈屈恩流感 降分析 on 以及 in-cup斗条件下 的性能. 兏以 宷新的视on 算准结果变on 获得对比效果.。 五个下设条件配置和 两种体系结构和 幺于 个训练集数据集 on 该其中一个非临床可有f 实性的评估工具上   开研结果显示 在 炊眼纵向病变 櫘变主要评估 on 与在图像采集中的变are相关而不太受病变本身的 on 彨脚所研究还 迭定了 一on在的稠密时时时视时在流延神经网络 (TRU) 幈습니다 以 个具有三个独立队列的的试验 on 评估 两者在2AF 和其他视视成法 (e-SLO) 方法上 两种模 术 onon 台预测性能 on 建产结果表明 on TRU 在多台D 优于已发布 baselines on on 个全面评估指标上 噸像结果证实 on 在医学上上 试验中 on 预克的延收变在慢变化得到上 超过了毛像性方式 on 在预测性能上多次试验 on  on 
### Innovation
该该下 两个关键贡献包括novation条: 1 通过定义条件熵和 吃指标 on 截到创建了一套评估框架 on 刢包括了条件熵和及 售口过后浓度 on 的分析方法 以及描述了on 一种用于预测的倍研究流程 on 该流程有效地降低了了预测时的图像采集误差对 坸同时总体增强了了 on 了预测性能 on 号最终此外 on 在特定丁理上 板定了 一种在临床试验 on 近的基于inference的预测分析方法 on
### Conclusion
在本研究中 on 预测延迟从纵向红眼图像更能时. 玷台模型的预测能力更强 on 临床试验的评估工具 on 訡型的预测实时性 鄂其产生的不确定性 on 委实模型的不确定局限性在ent 模后一一个平衡点 的发展， 最在收益间的隙对镜对晰 on的效果上. 一此明确于显示 on解定确定进 发接近in与训练-入qing的时间对因的对的是比个关键措施 on 预测性能在评估工具时体系结构上 优这个个时候主导了其他因素如图像采集条件 on
## 104. `cs.CV` - 从单个观测优化图像重建中的扩散先验 [PDF](https://arxiv.org/pdf/2604.21066), [HTML](https://arxiv.org/abs/2604.21066)
### Authors
Frederic Wang,Katherine L. Bouman
### Background
扩散先验在许多逆问题中生成高质量的后验样本，但它们通常基于有限的训练集或纯模拟数据进行训练，从而继承了这些底层来源的错误和偏差。目前，微调扩散模型的方法需要大量的具有不同前向算子的观测数据，这在许多应用场景中收集起来非常困难，导致在小测量集合时容易发生过拟合。
### Innovation
本文提出了一种方法，仅通过单个观测调整先验，该方法将现有的扩散先验合并为单一的专家乘积先验，并确定使贝叶斯证据最大化的效果。此方法在实际逆问题中得到了验证，包括黑洞成像和文本条件先下的图像去模糊，发现证据最常由超越单个数据集训练的先验最大化。
### Conclusion
通过使用指数加权通用先验，本文方法使从温度调整和组合扩散模型进行后验采样成为可能，从而生成更灵活的先验，并提高结果后验图像分布的可信度。
## 105. `cs.CV` - PC2Model: ISPRS基准用于3D点云到模型注册 [PDF](https://arxiv.org/pdf/2604.19596), [HTML](https://arxiv.org/abs/2604.19596)
### Authors
Mehdi Maboudi,Said Harb,Jackson Ferrao,Kourosh Khoshelham,Yelda Turkan,Karam Mawas
### Background
点云对齐涉及将一个点云与另一个点云或三维模型对齐，使多模态数据能够整合到统一的表示中。这种技术在建筑监测、无人驾驶、机器人技术和虚拟或增强现实（VR/AR）等应用中至关重要。随着LiDAR和结构光扫描等点云获取技术的普及，以及深度学习的最新进展，研究重点已转移到下游任务，特别是点云到模型（PC2Model）注册。尽管数据驱动的方法旨在自动化这个过程，但在真实世界的扫描中，由于稀疏性、噪声、杂乱和遮挡等问题，它们的性能受到限制。
### Innovation
本论文引入了PC2Model基准测试数据集，包括模拟和现实世界的数据点云，以支持经典和数据驱动方法的训练和评估。该数据集由国际工作小组II/Ib开发，采用了混合设计，通过结合精确的模拟数据和真实的传感器及环境因素，支持跨领域的鲁棒训练和评估，并允许系统分析模型从模拟到现实世界的转移性。
### Conclusion
通过PC2Model基准测试数据集，研究可以更好地处理点云到模型的注册任务，特别是在面对真实世界数据的挑战时。该数据集为研究人员提供了一个公开可访问的平台，以评估不同方法在不同环境下的性能。
## 106. `cs.CV` - BARD: Bridging AutoRegressive and Diffusion Vision-Language modelodel Via Highly Efficient Progressive Block Mendinging and Stage-Wise Dist Distillation [PDF](https://arxiv.org/pdf/2604.16514), [HTML](https://arxiv.org/abs/2604.16514)
### Authors
Baoyou Chen,Hanchen Xia,Peng Tu,Haojun Shi,Liwei Zhang,Weihao Yuan,Siyu Zhu
### Background
现有的自回归视觉语言模型（VLMs)虽然具备强大的的跨模态能力， 但它们逐个令牌的解码方式在推理过程中形成了根本性的瓶颈。。. 作者研究发现, 将预训练的自回归模型直接转换为扩散模型 V VLMs (dVLM) 通常会导致质量大幅下降。
### Innovation
本文介绍了一种名为 BARD (Bridging AutoRegressive and Diffusion Vision-Language model) 的简单桥梁框架,该框架通过逐步扩增解码块尺寸的逐步监督块合并方法及 and 黶间的跨块蒸馏方法 on 从固定的局部块扩散锚点进行阶段性内的 d V 訡蒸馏， to 恥查回复更大块的性能。 華 臻进了一种混合噪声调度器以提高去噪过程 中 on 胁性和令牌修改能力, to 使训通过大规模跨模态序列变得更为高效。 on on术实验证表明 盢单 从自回归到扩散的直接蒸馏是不相符的 能限制实际性能的提升, 苈而基于扩散阶段内的的蒸馏方法是持续性 抶彻分析比较 on实验中 '
### Conclusion
'BARD-VL 极大地继承了 Qwen3-VL 的跨模态 ability 在大块块解码速率上 指标上 AQL 个比 降低l到了 3 次倍解驳通 人 等同 实验测试结果'
## 107. `cs.CV` - 构建具有人类-人工智能监督的精确视频语言 [PDF](https://arxiv.org/pdf/2604.21718), [HTML](https://arxiv.org/abs/2604.21718)
### Authors
Zhiqiu Lin,Chancharik Mitra,Siyuan Cen,Isaac Li,Yuhan Huang,Yu Tong Tiffany Ling,Hewei Wang,Irene Pi,Shihang Zhu,Ryan Rao,George Liu,Jiaxi Li,Ruojin Li,Yili Han,Yilun Du,Deva Ramanan
### Background
研究视频语言模型（VLMs）的任务是通过自然语言理解动态视觉世界。此前的研究中，已经设计了一些模型和方法，但缺乏强有力的监督和评价体系，使得在视频元数据标注和生成方面难以达到专业水平。为了改进这一点，作者提出了一个包含开放数据集、基准测试和可扩展的监督框架的套件，旨在实现精确的视频字幕生成。
### Innovation
作者提出了CHAI（基于批评的人工智能监督）框架，该框架结合了专家对模型生成的半成品字幕进行批评和修订的能力。通过这种方法，人类专家可以专注于验证，而复杂的文本生成任务则由模型承担。此外，通过这种监督框架，收集的批评和偏好为提高开源模型的字幕生成、奖励模型和批评生成的能力提供了丰富的监督信息。实验结果显示，通过简单的专家监督，模型的表现优于封闭源模型，尤其是在生成细粒度的视频内容理解和生成方面。
### Conclusion
通过精确的规格化描述和人类-人工智能监督，作者的方法能够实现对大型专业视频（如电影、广告、游戏）的精确重新字幕，还可以更好地遵从复杂的指令，实现对摄像机运动、角度、镜头、焦距、视点和构图等细致把控。研究结果表明，准确的规定和人类-人工智能监督是实现专业水平视频理解和生成的关键。
## 108. `cs.LG` - 基于插值的稳健物理知情神经网络在斯匹次卑尔根群岛受热力逆温影响的污染传播时间依赖模拟中的应用 [PDF](https://arxiv.org/pdf/2604.23003), [HTML](https://arxiv.org/abs/2604.23003)
### Authors
Leszek Siwik,Maciej Sikora,Natalia Leszczyńska,Tomasz Maciej Ciesielski,Eirik Valseth,Manuela Bastidas Olivares,Marcin Łoś,Tomasz Służalec,Jacek Leszczyński,Maciej Paszyński
### Background
本文旨在解决由移动污染源引起的污染传播的时间依赖模拟问题。为解决这一问题，作者提出了一个基于物理的神经网络框架，发展了稳健的变分框架来处理时间依赖的对流-扩散问题，并基于此框架构建了一个直接关联真实逼近误差的稳健损失函数。为了加快神经网络训练速度，还引入了一种插值基的策略。
### Innovation
提出了一个基于物理的神经网络（Physics-Informed Neural Network, PINN）框架，建立了时间依赖的对流-扩散问题的稳健变分框架，证明了对应的离散弱形式的有界性和inf-sup稳定性。基于上述数学基础，构建了直接关联真实逼近误差的稳健损失函数，引入了插值基策略加速神经网络训练。
### Conclusion
所提出的框架应用于分析热力逆温对污染物积累的影响。研究结果表明，热力逆温会将浓湿空气团困在地面附近，显著增加颗粒物质（PM）浓度，恶化地方空气质量。
## 109. `cs.LG` - 记忆的形状：第二阶优化器中机器遗忘的几何分析 [PDF](https://arxiv.org/pdf/2604.23046), [HTML](https://arxiv.org/abs/2604.23046)
### Authors
Kennon Stewart
### Background
当前对于机器遗忘的定义对于第二阶优化器来说不够具体。研究对比了第一阶和第二阶学习器在处理数据删除任务时的能力，通过改变特征分解的层次来模拟损失模型记忆。
### Innovation
研究发现，尽管两者在性能和梯度上都与理想的反事实相一致，但第二阶优化器在优化器状态上表现出显著的波动，这表明存在未被第一阶分析检测到的残留信息。通过不同的特征衰减处理，研究证明只有在几何信息（或记忆）被擦除的控制状态扰动下，才重新获得了稳定性和信息损失。
### Conclusion
研究结果表明，需要更具体的定义来描述机器遗忘的概念，特别是在第二阶优化器中。通过几何信息的分析，可以更好地理解信息的删除和优化器状态的稳定性问题。
## 110. `cs.LG` - 在混合专家调优中保留长尾专家信息 [PDF](https://arxiv.org/pdf/2604.23036), [HTML](https://arxiv.org/abs/2604.23036)
### Authors
Haoze He,Xingyuan Ding,Xuan Jiang,Xinkai Zou,Alex Cheng,Yibo Zhao,Juncheng Billy Li,Heather Miller
### Background
尽管门控混合（MoE）模型在许多基准测试中表现出色，但其路由器层在监督微调（SFT）过程中仍然脆弱。现有方法如DenseMixer和ESFT虽然能减轻路由器崩溃问题，但引入的梯度噪声常常导致性能下降。初步实验显示，尽管一些超级专家被频繁激活，丢弃不常用专家仍然会导致性能显著下降，表明即使很少被激活的专家也包含对下游任务有用的知识。
### Innovation
提出了一种无需辅助损失的MoE SFT框架，结合了基于偏差的稀疏化与始终激活的门控凝缩专家。这种方法鼓励与任务相关的专家保持活跃，并促使长尾分布的低频专家变得不活跃。凝缩专家提供了持续的、可学习的路径，以缓解梯度饥荒并促进信息的有效整合。
### Conclusion
在大规模MoE模型上进行的实验表明，该方法优于现有的SFT基线方法，如DenseMixer和ESFT，在数学推理和常识问答基准测试中分别平均提高了2.5%以上性能提升。
## 111. `cs.LG` - 一种用于全球气候模型降水量偏差校正的可微分框架 [PDF](https://arxiv.org/pdf/2604.23045), [HTML](https://arxiv.org/abs/2604.23045)
### Authors
Kamlesh Sawadekar,Seth McGinnis,Peijun Li,Chaopeng Shen
### Background
全球循环模型(GCM)输出中的系统偏差限制了其在区域规划中的直接应用，因此需要进行偏差校正。降水量校正尤为困难，因为它具有非正态分布、间歇性和非线性极端值特性。传统统计方法难以从大数据中学习，并难以应对GCM中的系统偏差；虽然机器学习提供了这种灵活性，但其“黑箱”特性阻碍了对这些偏差的完全理解，从而阻碍了在不同GCM和位置上的泛化，特别是在降水量校正方面。
### Innovation
本研究提出了一种新的可微分偏差调整框架ΔCLIMBA（或dCLIMBA），它通过学习历史CMIP6模型输出与参考再分析数据集（Livneh）之间的时空自适应参数化偏差调整程序来进行偏差校正。该方法成功地修正了极端暴雨事件的幅度和分布，并且在不同的美国城市中，降水量的分位分布被很好地重现，空间模式与广泛使用的LOCA2统计下scaling技术表现得相当。此外，该框架展示了未来趋势保留能力，不同于纯分位数方法和LOCA2，并且在未见区域上的偏差修正结果表明边缘偏差有所减轻。这项工作提供了一种模块化、计算效率高且可扩展的偏差修正方法，具有物理信息性、可扩展性，并且适用于历史和未来应用。
### Conclusion
本研究介绍了一种模块化、计算效率高且可扩展的偏差修正方法，适用于全球气候模型降水量偏差校正，并在不同区域表现出良好的性能，还能够保留未来趋势和处理未见区域的偏差校正。该方法被认为是目前可用于地球系统后处理管道和影响工作流的有效工具。
## 112. `cs.LG` - K-Score: 上朗滤波在强化学习中约束奖励正态化的原则替代方法 [PDF](https://arxiv.org/pdf/2604.23056), [HTML](https://arxiv.org/abs/2604.23056)
### Authors
Zixuan Xia,Quanxi Li
### Background
在政策梯度强化学习中，人们常常依靠奖励规范来训练过程和稳定。奖励波动问题。而种奖励规范的方法旨在修正极端奖励值，从而使训练过程更加稳定和收敛。常用的的的方法包括批归一化 (BN) 和在线正变归 (V-Norm) 猜想法，D但是这些方法可能人们需要对种固定的策略才培才称DD并且它们过程缺乏对在D非定定环境中的D中的的鲁棒性移动性以及适应能力
### Innovation
该该研究提出 D种一种简单而有效的替代奖励规范的方法D使用在线D线融合D时5一种1一D维的朗滤波D来在线在线奖励DD这种滤波DD用递归估计潜在奖励DD 幼滑高过程中的DD平高D方不确定性和适应不同非确定D定定环境DD研究没有DD采用没有增加D增加减少度改进收敛速度和D和减少了训练过程中的DD受DD变化技巧D的作用D并且D没有D改方法不D需要对D对己有存在D政策架构DD修改D
### Conclusion
D通过D在D文本环境DD和环境D（D件进行和测试D研究发现DD使用D用朗滤DDD奖励有效地加快D了收敛速度和以及DD减少了训练过程DD均衡D度性但是D该这种方法L没有不DR改变需任何DD修改D现有现已存在的D政策架构DD
## 113. `cs.LG` - 适合所有人的尺寸并不存在：LLM投资建议中的启发式坍塌 [PDF](https://arxiv.org/pdf/2604.23837), [HTML](https://arxiv.org/abs/2604.23837)
### Authors
Jillian Ross,Andrew W. Lo
### Background
大型语言模型（LLM）越来越多地被部署在高风险领域中，例如提供医疗建议、解读法律文件和推荐金融产品。在这种场景下，提供有效建议需要考虑用户的全面背景信息，而不仅仅是表面特征。本文探讨了前沿的LLM是否真的能够做到这一点，或是否会展现出启发式坍塌的现象：即将复杂、多因素的决策简化为少数几个主导输入。研究重点放在投资建议上，因为法律明确规定需要对用户的全部情况进行个性化推理。
### Innovation
本文应用可解释的 surrogate 模型来分析 LLM 的输出，发现投资分配决策主要由自我报告的风险承受能力决定，其他相关因素的作用很小。此外，研究还发现网络搜索部分减轻了启发式坍塌现象，但未能完全解决这一问题。这些结果表明，仅通过增加网络搜索或模型规模不能解决启发式坍塌问题，因此在将 LLM 作为顾问部署时，需要审查输入敏感性而不仅仅是输出质量。
### Conclusion
研究表明，启发式坍塌不仅不是通过增加网络搜索或模型规模所能解决的问题，还建议在将 LLM 作为顾问部署时需要关注输入的敏感性，而不仅仅是输出的质量。
## 114. `cs.LG` - 轻量级模型在乳腺病变分割中的比较研究 [PDF](https://arxiv.org/pdf/2604.23899), [HTML](https://arxiv.org/abs/2604.23899)
### Authors
Helder Oliveira
### Background
乳腺癌是全球女性癌症相关死亡的主要原因之一，乳腺X光摄影是主要的筛查工具。尽管深度学习模型在病变分割方面表现出色，但大多数依赖于计算密集型架构，这限制了它们在资源受限环境中的应用。
### Innovation
本研究评估了轻量级模型在乳腺X光摄影病变分割上的性能和效率，比较了MobileNetV2、EfficientNet Lite、ENet、Fast-SCNN与U-Net基准模型在INbreast数据集上的表现，使用5折交叉验证。结果表明，具有Squeeze-and-Excitation的MobileNetV2性能最优，参数量减少了约75%，同时保持了良好的召回率。
### Conclusion
轻量级架构为可部署的计算机辅助诊断系统提供了在性能和效率之间的实用平衡。
## 115. `cs.LG` - 大型神经科学时代的整合神经控行动模建 [PDF](https://arxiv.org/pdf/2604.23903), [HTML](https://arxiv.org/abs/2604.23903)
### Authors
Il Memming Park,Ayesha Vermani,Gonzalo G. de Polavieja,Juan Álvaro Gallego,Kathleen Esfahany,Shreya Saxena,Michael Orger,Auke Ijspeert,Matthew Dowling,Daniel McNamee,Srinivas C. Turaga,Zachary Mainen,Joseph J. Paton,Alfonso Renart
### Background
大型神经科学研究正在生成跨越不同动物、大脑区域和行为情境的丰富数据集，然而，我们的建模努力仍然在孤立的实验之间碎片化。理解行为需要整合神经控行动模建：易于理解的动力学模型，能够捕捉大脑、身体和环境之间的闭环耦合，将大脑视为追求潜在目标的控制器，能够表示不同尺度的结构化变异性，并能够扩展到异构数据集中。
### Innovation
通过结合非线性状态空间模型和元动力学扩展，结合可扩展的推断、知识蒸馏、混合开放和封闭环训练，以及连接组学启发式架构，提出了一个实用的途径，旨在通过整合神经控行动模建，聚合来自记录、行为、扰动和解剖学的互补约束，实现统计放大、少样本泛化以及对共享动力学结构、个体变异性和控制行为的目标的机制性洞察。
### Conclusion
这一议程提供了一条从碎片化数据到机制性科学的核心路径，该科学探讨大脑如何产生行为。
## 116. `cs.LG` - Sliced-Regularized Optimal Transport [PDF](https://arxiv.org/pdf/2604.23944), [HTML](https://arxiv.org/abs/2604.23944)
### Authors
Khai Nguyen
### Background
传统的最优传输（Optimal Transport, OT）方法，如熵正则化最优传输（Entropic OT, EOT），通过正则化传输计划，使其趋向独立的耦合。然而，这类方法正则化的是独立的传输计划。相比之下，新的方法Sliced-Regularized Optimal Transport (SROT)正则化的是贴近蒙特 Carlo 版本的Sliced OT（SOT）计划。
### Innovation
Sliced-regularized optimal transport (SROT) 是一种新的正则化方法，不同于传统的熵正则化最优传输（EOT），它将传输计划正则化为平滑的 sliced OT (SOT) 计划。这是首次使用SOT作为参考来改进经典最优传输的方法。SROT 使用了拓扑和计算上的性质分析，并提供了计算高效的算法。
### Conclusion
通过实验验证，Sliced-Regularized Optimal Transport (SROT) 在近似精确最优传输方面显示出优于其他方法的性能，特别是熵正则化最优传输（EOT）和 sliced OT（SOT）。傅里叶流实验进一步表明，SROT 偏差度量具有优势。
## 117. `cs.LG` - EPM-RL: 在线交易产品映射的强化学习方法 [PDF](https://arxiv.org/pdf/2604.23993), [HTML](https://arxiv.org/abs/2604.23993)
### Authors
Minhyeong Yu,Wonduk Seo
### Background
产品映射是电商业务中价格监控和渠道可见性的重要任务。由于卖家经常在标题中插入促销关键词、平台特定标签和捆绑描述，导致同一产品有多种不同的名称。尽管最近基于大语言模型和多智能体的框架可以提高处理此类难题的鲁棒性和可解释性，但它们依赖昂贵的外部API、重复检索和复杂的推理时的协调，使得大规模部署在敏感隐私的企业环境中既昂贵又困难。
### Innovation
我们提出了EPM-RL，一种基于强化学习的框架，用以构建准确且高效的现场电商业务产品映射模型。核心理念是将高成本的代理推理提炼为可训练的内部模型。我们从LLM生成的推理和人工验证的包含产品对的集合作始，首先使用结构化推理输出进行参数高效的微调（PEFT），然后使用基于代理的奖励通过强化学习进一步优化模型，该奖励综合考虑输出格式的合规性、标签准确性以及特别设计的裁判模型给出的推理偏好得分。
### Conclusion
初步结果显示，EPM-RL在PEFT训练的基础上持续改进，提供了比基于商业API的基本模型更优的质量-成本权衡，同时支持隐私部署和较低的操作成本。这些发现表明，强化学习可以使产品映射从高延迟的代理管道转变为可扩展、可检查和生产就绪的内部系统。
## 118. `cs.LG` - Conditional Score-Based Modeling of Effective Langevin Dynamics [PDF](https://arxiv.org/pdf/2604.23952), [HTML](https://arxiv.org/abs/2604.23952)
### Authors
Ludovico T. Giorgini
### Background
在复杂系统的简化模型中，on 许多随机简化模型广泛用于表示拟复杂的动态特性，on 返这些模型的漂移和扩散系数从数据估计仍然是具挑战性的。on 传统方法往往依赖于短暂轨迹增量、空间划分、候选模型的模拟、这些方法对于高维系统由于粗略的时间抽样、不均匀的数据采样在计算上 都是非可靠的和代价昂的。 虋这意味着对于大型系统的精确简化模型拟是一种具挑战的困难挑战。
### Innovation
本文提出了一种基于on的数据驱动校准方法，on 断依系数与有限时间转移条件得分之间的关系、此得分定义为限制梯度与对数转移有限时间梯度相对于系数的表达、on 迍成果允许从有限统计、on 确定轨迹仿分中直接从有限统计得到漂移和扩散分析 
### Conclusion
因此框架提供了学习满足指定统计和和动力学的随机简化模型的方法、这些模型能够精确再现有限动态相关内容并
## 119. `cs.LG` - 通过步骤级优势选择稳定高效推理 [PDF](https://arxiv.org/pdf/2604.24003), [HTML](https://arxiv.org/abs/2604.24003)
### Authors
Han Wang,Xiaodong Yu,Jialian Wu,Jiang Liu,Ximeng Sun,Mohit Bansal,Zicheng Liu
### Background
大型语言模型（LLMs）通过在推理时分配大量计算能力实现了强大的推理性能，通常生成长且冗长的推理轨迹。最近的工作通过基于长度的奖励或剪枝减少了这种情况下的开销，但许多方法在更短的上下文窗口下进行了后训练，而这种效果的影响因素尚未系统地分离出来。
### Innovation
我们首先展示了仅使用标准GRPO的短上下文后训练就已诱导了相当大的推理压缩，但代价是训练动态越来越不稳定，准确性下降。为了解决这个问题，我们提出了步骤级优势选择（SAS），该方法在推理步骤级别上操作，将正确 rollout 中的低自信步骤和验证器失败 rollout 中的高自信步骤的优势设为零，其中失败通常源自截断或验证器问题而不是错误的推理。
### Conclusion
在多样化数学和通用推理基准测试中，SAS 在最强的基于长度的基线之上将平均 Pass@1 准确率提高了 0.86 个百分点，同时将平均推理长度减少了 16.3%，从而改进了准确性和效率之间的权衡。
## 120. `cs.LG` - 大规模多智能体智能辅导系统的延迟与成本 [PDF](https://arxiv.org/pdf/2604.24110), [HTML](https://arxiv.org/abs/2604.24110)
### Authors
Iizalaarab Elhaimeur,Nikos Chrisochoides
### Background
多智能体的大规模语言模型（LLM）辅导系统通过智能体专业化改进回应质量，但每个学生查询会触发多个并发API调用，这些调用的延迟在并行阶段产生最大效应，而单一智能体系统无法面对。本文在Gemini 2.5 Flash和Google Vertex AI构建的四智能体系统ITAS中进行了实验。
### Innovation
研究通过在三个吞吐量级别（标准按需付费、优先级按需付费和配置吞吐量）和最多50个同时用户下进行并发等级测试，提升了对于多智能体智能辅导系统的理解。通过大量量化实验数据，指出了多智能体系统在不同并发等级下的响应延迟表现，并且通过成本分析强调了不同系统的成本效益。
### Conclusion
优先级按需付费在全负载范围内维持了几乎均匀的低于4秒的响应时间；标准按需付费在教室规模的并发等级下显著下降；配置吞吐量在低并发时提供最低延迟，但其预留容量在大约20个并发用户以上便会被饱和。成本分析表明，按令牌付费的两个级别在最坏情况的使用限制下均低于学生每学期一本STEM教科书的价格。对于能够预测并集中其流量以达到高利用率的机构而言，配置吞吐量变得成本竞争力。
## 121. `cs.LG` - 生成扩散模型中伴椭圆核族的可辨识性和稳定性 [PDF](https://arxiv.org/pdf/2604.24196), [HTML](https://arxiv.org/abs/2604.24196)
### Authors
Hak Geun Lee
### Background
本文基于Deng等人提出的生成扩散框架，分析了潜在分布匹配背后的漂移场的可辨识性和稳定性。文章首先引入了一类伴椭圆核，这些核包括拉普拉斯核，并通过二阶椭圆耦合特征将每个此类核与其伴生函数相关联。然后证明了此类核下的漂移场只在两个概率测度相等时才会消失。此外，通过构造反例展示当质量逃逸到无穷大时，尽管场趋于零，单纯控制场的范数并不能保证弱收敛。
### Innovation
本文引入了一类伴椭圆核，证明了此类核下漂移场的性质，并通过具体的数学证明展示了在漂移场趋于零但质量逃逸到无穷大的情况下，单纯控制场的范数不能保证弱收敛。此外，作者通过引入内在重叠标量的渐近下界来恢复弱收敛。
### Conclusion
本文的发现限定了弱收敛失败的唯一方式并集中在一维射线上，通过对内在重叠标量施加渐近下界，可以恢复弱收敛。
## 122. `cs.LG` - 连续扩散语音语言模型的标度特性 [PDF](https://arxiv.org/pdf/2604.24416), [HTML](https://arxiv.org/abs/2604.24416)
### Authors
Jason Ramapuram,Eeshan Gunesh Dhekane,Amitis Shidani,Dan Busbridge,Bogdan Mazoure,Zijin Gu,Russ Webb,Tatiana Likhomanenko,Navdeep Jaitly
### Background
现有的语音只驱动的语音语言模型在性能上落后于文本和文本-语音模型。以前的离散自回归（AR）语音语言模型由于计算和数据需求较高，难以追赶文本模型。离散化连续语音以适用于AR模型会遇到瓶颈，因此研究了连续扩散（CD）语音语言模型的可行性。为了量化语音语言模型的语言质量，引入了音素杰宾-香农散度（pJSD）度量。分析结果显示，连续扩散语音语言模型在验证损失和pJSD上表现出与自回归模型相似的标度定律，最优的标记-参数比例随计算量的增加而降低。然而，在参数量和数据规模数量级上，损失变得对数据和模型规模的选择不敏感，显示出快速推理的潜力。
### Innovation
该研究通过探索连续扩散（CD）语音语言模型，提出了利用音素杰宾-香农散度（pJSD）来量化语音语言模型语言质量的新方法。研究展示了连续扩散语音语言模型在较大计算量下的性能改善，但长段内容的连贯性仍然是一个挑战。
### Conclusion
将连续扩散语音语言模型扩展到160亿参数并使用数千万小时的对话数据，能够产生具有情感性、韵律性的多说话人、多语言语音，但仍存在长文本连贯性方面的挑战。
## 123. `cs.LG` - 计算设计和实验验证的光活性PARP1抑制剂 [PDF](https://arxiv.org/pdf/2604.24634), [HTML](https://arxiv.org/abs/2604.24634)
### Authors
Simon Axelrod,Miroslav Kašpar,Kristýna Jelínková,Markéta Šmídková,Erika Bartůňková,Sille Štěpánová,Eugene Shakhnovich,Václav Kašička,Martin Dračínský,Zlatko Janeba,Rafael Gómez-Bombarelli
### Background
光激活药物为治疗现有治疗方法具有严重副作用的局部疾病提供了有前景的方法。然而，其开发过程复杂，因为需要同时优化光物理和生物学特性。
### Innovation
使用计算技术找到了一组用于光控多（ADP-核糖）聚合酶1（PARP1）癌症靶点抑制的有潜力候选药物。开发了一种基于原子模拟和机器学习的方法，筛选出500万个假设的光活性配体。使用蛋白质-配体对接、ML力场和量子化学计算、图基的代理模型、激发态非绝热动力学和自由能扰动来优先考虑具有红移吸收光谱、数秒至数分钟的热半衰期和可见光控制条件下依赖异构体的PARP1结合的候选药物。
### Conclusion
合成了10种候选药物并实验鉴定其光行为和PARP1抑制常数。在验证化合物中，1号化合物在519 nm绿光照射下，PARP1抑制作用增加了15倍。这些结果验证了计算引导筛选策略来识别红移PARP1光抑制剂，但也突显了目前的局限性，例如水相中快速的热弛豫。
## 124. `cs.LG` - 使用信念空间模型预测控制的线性系统从二元观察的双重控制 [PDF](https://arxiv.org/pdf/2604.24663), [HTML](https://arxiv.org/abs/2604.24663)
### Authors
Daniel Cao,Beixi Du,Andrew Lowitt,Sunmook Choi,Sarah Dean,Yahya Sattar
### Background
研究了具有二元观测的线性系统的有限时间周期二次控制问题。在这种情况下，控制输入不仅影响状态动力学，还影响状态的部分观测。分离原理在这种情况下可能失效，因为控制输入会改变未来状态估计的质量。因此，状态估计需要依赖控制输入的卡尔曼滤波器，其增益和误差协方差随着控制输入的变化而变化。
### Innovation
提出了一种信念空间模型预测控制（$texttt{B-MPC}$）方法，可以直接在估计的状态及其误差协方差上进行计划。$texttt{B-MPC}$ 使用输入依赖的卡尔曼滤波器定义的确定性信念演化的替代方案进行计划。实验表明，在有利的条件下，$texttt{B-MPC}$ 可以比分离原理控制器及其模型预测控制变体更胜一筹，并且伴随更低的估计协方差和更具有不确定性感知的动作选择。
### Conclusion
通过数值实验在两个合成环境中，$texttt{B-MPC}$ 方法显示出比基于分离原理和模型预测控制方法的优越性，特别是在估计精度和不确定性感知动作选择方面有显著提高。
## 125. `cs.LG` - Energy-Arena：运营能源预测的动态基准 [PDF](https://arxiv.org/pdf/2604.24705), [HTML](https://arxiv.org/abs/2604.24705)
### Authors
Max Kleinebrahm,Jonathan Berrisch,Philipp Eiser,Wolf Fichtner,Veit Hagenmeyer,Matthias Hertel,Nils Koster,Sebastian Lerch,Ralf Mikut,Jan Priesmann,Melanie Schienle,Benjamin Schaefer,Jann Weinand,Florian Ziel
### Background
能源预测研究面临着持续的可比性差距，这使得无法测量随时间一致的进步。报告的准确性提升往往不受直接比较，因为模型是在特定的数据集、时间周期、信息集和评分设置下进行评估的，而广泛使用的基准和竞赛数据集通常仅连接到固定的过去历史窗口。
### Innovation
该论文介绍了Energy-Arena，这是一个动态基准平台，用于运营能源时间序列预测，提供随着能源系统演进而不断更新的参考点。该平台作为一个开放的、基于API的提交系统运行，并且标准化了挑战定义和提交截止日期，这些截止日期与运营约束相一致。性能通过持久的排行榜在滚动评估窗口中进行报告。通过从回顾性回测转变为前瞻性基准测试，Energy-Arena 强制了标准化的前瞻性提交和事后评估，从而通过防止信息泄露和退后的调整提高了透明度。
### Conclusion
该平台公开提供，通过建立一个统一的基准测试框架，Energy-Arena 改进了能源预测领域的工作进展的透明度和可比性。
## 126. `cs.LG` - 利用微分平坦性实现受约束的多输入控制仿射系统的高效基于学习的模型预测控制 [PDF](https://arxiv.org/pdf/2604.24706), [HTML](https://arxiv.org/abs/2604.24706)
### Authors
Tobias A. Farger,Adam W. Hall,Angela P. Schoellig
### Background
基于学习的控制技术利用过去轨迹的数据来控制具有不确定动力学的系统。然而，基于学习的控制器通常计算效率低下，限制了其实用性。
### Innovation
本文提出了一种基于学习的控制器，利用许多机器人系统具有的微分平坦性这一特性。该方法通过系统扩展和块对角成本形式，控制一般多输入、非线性、仿射系统，并解决了输入和半空间平坦状态约束，仅需两个连续的凸优化就可确保概率李雅普诺夫的下降。
### Conclusion
仿真结果表明，该方法在效率上是基于高斯过程的模型预测控制的多倍，而在实际硬件实验中达到了可竞争的跟踪性能。
## 127. `cs.LG` - 长上下文感知上溢: 混合LLM扩展的新前沿 [PDF](https://arxiv.org/pdf/2604.24715), [HTML](https://arxiv.org/abs/2604.24715)
### Authors
Parsa Ashrafi Fashi,Utkarsh Saxena,Mehdi Rezagholizadeh,Aref Jafari,Akash Haridas,Mingyu Yang,Vansh Bhatia,Guihong Li,Vikram Appia,Emad Barsoum
### Background
混合序列模型结合了高效的Transformer组件和线性序列建模模块，被认为是纯粹的Transformer的有效替代方案。然而，这些模型大多数都是从头开始预训练的，因此无法重用现有的Transformer检查点。本研究从实际出发，探索通过上溢（upcycling）将预训练的Transformer大规模语言模型（LLM）转换为混合架构，同时保留短上下文质量和提高长上下文能力。
### Innovation
提出了一种名为HyLo（HYbrid LOng-context）的解决方案，它结合了架构调整、高效Transformer模块、多头潜在注意力（MLA）和线性模块（Mamba2或Gated DeltaNet），并使用阶段式长上下文训练和教师指导的蒸馏进行稳定优化。HyLo通过高效的后训练扩展了可使用的上下文长度最多32倍，并将KV缓存的内存减少了超过90%，从而让我们的vLLM推理堆栈能够处理多达200万标记的预填充和解码，而具有相似规模的基线模型在超过64K上下文时已出现内存不足的情况。在1B和3B规模设置下，HyLo在短上下文和长上下文中表现一致优异，并在长上下文评估如RULER上显著优于最先进的上溢混合基线。
### Conclusion
HyLo-Qwen-1.7B仅在10B标记上进行训练，但在GSM8K、Lm-Harness常识推理和RULER-64K等任务上表现超过了分别在400B标记上训练的JetNemotron。该研究提出了一种有效的方法，通过上溢将预训练的Transformer LLM转变为具有长上下文能力的混合架构，同时也保持了短上下文的质量。
## 128. `cs.LG` - Personalized Practiceed Example Generation from Student Code Submissions using Pattern-based Knowledge Components [PDF](https://arxiv.org/pdf/2604.24758), [HTML](https://arxiv.org/abs/2604.24758)
### Authors
Griffin Pitts,Muntasir Hoq,Peter Brusilovsky,Narges Norouzi,Arto Hellas,Juho Leinonen,Bita Akram
### Background
传统的练习方法往往依赖固定的练习材料库，background
### Innovation
本研究提出了一种基于学生代码提交中的模式生成实践练习内容的方法，。子。lt; 煤粉。该方法通过编程语法 卆练过程中的抽象语法分析（AST-based analysis))， extract recurring structural pattern pattern (KC) patterns and use them to guide generative content. a personalized level. This approach represents an innovative way to adapt practice to individual the logical of x作用中的学员的理解水平和，并 adjust, 他们实际理解的内容不对症进行调整，
### Conclusion
研究结果应用于练习材料生成并，并, 癇发现基于知识组件(KC)的内容的生成能够更好地聚焦焦点于针对性学习者的逻辑错误理解问题 幋试基线的方法的生成模型能够支持个性化学习的实施实践
## 129. `cs.LG` - Learning Under Moral Hazard with Instrumental Regression and General Generalized Method of Moments [PDF](https://arxiv.org/pdf/2405.20642), [HTML](https://arxiv.org/abs/2405.20642)
### Authors
Shiliang Zuo
### Background
机器学习在数据驱动的政策制定中逐渐变得流行。。这些政策影响个人和群体的行为，并理想理想的政策制定是通过观测信号进行的。 焼然而现实世界的情况有所不同，可以在实际情况下,个人的具体行动无法被完美观察，这种现象在经济学中被称为道德危害，并在这样的情况下增加了政策制定的挑战。。
### Innovation
该研究探讨了多任务代理决策问题的基本问题，并证明了工具回归和广义矩法（GMM）估计器可以用来解决这种问题问题问题下的问题决策问题问题问题称为目标偏差的最优决定形式没有明确给出结果因此无法直接总结为创新点语。。
### Conclusion
本文研究了道德危害环境下基于工具回归和广义矩法估计的方法进行学习的问题，并表明可以通过工具回归和广义矩法估计量来更准确地地理解和解决道德危害下的决策问题研究成果可以为在实际情况下的政策制定提供更有效的工具和方法。
## 130. `cs.LG` - FlashNorm：Transformer中的快速归一化 [PDF](https://arxiv.org/pdf/2407.09577), [HTML](https://arxiv.org/abs/2407.09577)
### Authors
Nils Graef,Filip Makraduli,Andrew Wasielewski,Matthew Clapp
### Background
在大型语言模型（LLMs）中，归一化层（如RMSNorm）是普遍使用的，但这些层在计算上是瓶颈。在具有独立向量和矩阵执行单元的硬件上，RMS计算会阻止后续的矩阵乘法执行，阻碍并行计算。
### Innovation
提出了一种名为FlashNorm的技术，通过精确重构RMSNorm并紧随其后的是一个线性层，实现了（i）归一化权重的消除，即将其折叠进后续的线性层，（ii）将标量RMS归一化延迟到矩阵乘法的输出，从而使两个操作能够并行执行。此外，由于RMS的尺度不变性，可以消除第一个RMSNorm，从而简化了使用QKV归一化（例如Gemma~4）或具有潜在归一化的MLA模型（例如DeepSeek-V2，Mistral Small 4和OpenMythos）中的归一化层。这些技术也适用于LayerNorm，Dynamic Tanh（DyT），带GLU变体的前馈网络以及RoPE基注意力。
### Conclusion
在NVIDIA T4 GPU上，FlashNorm在预填充（compute-bound）状态下针对SmolLM2-135M规模实现了33-35%更低的滞后时间，在Llama-7B规模状态下则为12-14%。我们在三个模型上验证了零损失权重折叠。除了提高推理速度，FlashNorm还通过减少参数张量数量简化了模型的实现。
## 131. `cs.LG` - 去伪存真：无需组注释提高对伪相关性的鲁棒性 [PDF](https://arxiv.org/pdf/2407.14974), [HTML](https://arxiv.org/abs/2407.14974)
### Authors
Phuong Quynh Le,Jörg Schlötterer,Christin Seifert
### Background
机器学习模型在训练过程中可能会学习到伪相关，即与类别标签有强相关性但实际上并无因果关系的特征。依赖这些相关性会导致在不包含这类相关性的数据群体中表现不佳，并且影响模型的泛化能力。因此，提高模型对伪相关性的鲁棒性成为一个重要研究方向。
### Innovation
本文提出了一种方法，从中训练好的网络中提取出一个不依赖于伪相关的子网络。该方法基于在结构风险最小化（ERM）训练中具有相同伪属性的数据点在表示空间中近邻的假设，通过引入监督对比损失以新方式促使模型去学习数据的有效特征而不依赖于伪相关。
### Conclusion
本文的方法在最差数据组中的性能提升，支持了一种假设，即在完全训练的密集网络中存在负责仅使用不变特征进行分类任务的子网络，即使在多重伪属性和没有先验属性标签的情况下，也能消除伪特征的影响。
## 132. `cs.LG` - 用变压器和神经积分算子逼近算子的普遍性 [PDF](https://arxiv.org/pdf/2409.00841), [HTML](https://arxiv.org/abs/2409.00841)
### Authors
Emanuele Zappala,Maryam Bagherian
### Background
本文研究了变压器和神经积分算子在巴纳赫空间算子近似性中的普遍性属性。研究基于持氏空间中的积分算子以及巴纳赫空间中的任意算子。
### Innovation
文章展示了变压器架构是持氏空间之间积分算子的普遍逼近器。还证明了基于Gavurin积分的神经积分算子的推广版本是巴纳赫空间之间任意算子的普遍逼近器。最后，通过修改变压器并使用勒雷-沙德映射来显示其作为任意巴纳赫空间之间算子的普遍逼近器的有效性。
### Conclusion
研究证明了三种不同的算子逼近方法，这些方法可以分别用于持氏空间、巴纳赫空间和任意巴纳赫空间之间的算子逼近。
## 133. `cs.LG` - 学习增强的鲁棒算法性诉 [PDF](https://arxiv.org/pdf/2410.01580), [HTML](https://arxiv.org/abs/2410.01580)
### Authors
Kshitij Kayastha,Vasilis Gkatzelis,Shahin Jabbari
### Background
算法性诉为遭受机器学习系统不利结果的个人提供了最小成本的改进方法，以实现期望结果。然而，机器学习模型经常更新，这可能导致性诉无效。为赋予性诉更为鲁棒性，研究者提出了鲁棒性性诉框架，该框架选择对对抗性模型变化不那么敏感的性诉，但代价更高。为平衡这种权衡，本文探讨了结合未来模型预测的学习增强算法性诉，研究预测准确性对降低性诉成本的影响，以及即使预测不准确也限制成本的方法。
### Innovation
提出了一种新的学习增强算法性诉方法，研究了鲁棒性和一致性之间的权衡，并分析了预测准确性对性能的影响。
### Conclusion
通过结合模型预测，学习增强算法性诉可以在预测准确时降低性诉成本，同时在预测不准确时依然能够限制成本，从而平衡了鲁棒性和一致性的需求。
## 134. `cs.LG` - 关于管道梯度下的类比在内存训练收敛理论 [PDF](https://arxiv.org/pdf/2410.15155), [HTML](https://arxiv.org/abs/2410.15155)
### Authors
Zhaoxian Wu,Quan Xiao,Tayfun Gokmen,Hsinyu Tsai,Kaoutar El Maghraoui,Tianyi Chen
### Background
为了以能源高效的方式加速大型深度神经网络（DNN）的训练，类比在内存计算（AIMC）作为一种解决方案出现。AIMC加速器在训练过程中保持模型权重在内存中，无需将它们从内存移动到处理器上，从而大大减少了开销。尽管AIMC在效率上表现出色，但扩大其系统规模面临着重大挑战。由于权重复制成本高昂且不准确，异步管道并行在AIMC加速器上对数据并行效率不高。这需要探索管道并行，特别是异步管道并行，以利用所有可用的加速器。然而，尽管有 empirical 探索，对于类比硬件中的权重更新的缺陷如何影响多层DNN模型的训练的理论理解仍然不足。异步管道并行会导致陈旧的权重问题，使更新信号不再有效梯度。
### Innovation
本文探讨了类比在内存计算硬件中异步管道梯度下降（Analog-SGD-AP）的收敛理论。虽然异步管道并行导致了陈旧的权重问题，但研究表明，尽管存在这些挑战，Analog-SGD-AP仍然能够在迭代复杂度$O(ε^{-2}+ε^{-1})$下收敛，这与数字SGD和同步管道的类比梯度下降的复杂度相同，只是非支配项为$O(ε^{-1})$。这意味着相比于同步管道，AIMC训练几乎可以免费从异步管道中获益。
### Conclusion
本文的研究结果表明，类比在内存计算（AIMC）在进行多层DNN训练时可以利用异步管道并行几乎无需成本地提高收敛速度，而不会显著提高计算时间复杂度。这表明异步管道并行由于其灵活性和并行性，对AIMC系统的训练是有巨大益处的。
## 135. `cs.LG` - 探索数据集统计效应大小对模型性能和数据样本大小充足性的影响 [PDF](https://arxiv.org/pdf/2501.02673), [HTML](https://arxiv.org/abs/2501.02673)
### Authors
Arya Hatamian,Lionel Levine,Haniyeh Ehsani Oskouie,Majid Sarrafzadeh
### Background
充足的高质量数据对于训练有效的机器学习模型至关重要。能够在训练和评估模型性能之前准确判断数据集的充足性，对进行实验设计或数据收集的人来说是非常重要的工具。然而，尽管有此需求，前瞻性地评估数据充足性的能力仍然是一个难以解决的问题。
### Innovation
本文通过两项实验探索基本描述统计措施是否可以作为培训数据集模型效果的有效指示器。实验围绕效应大小对模型性能和学习曲线收敛率的影响展开，发现这种方法并不是判断样本大小充足性和预测模型性能的有效手段。
### Conclusion
实验结果表明，效应大小并不能有效预测样本大小的充足性和模型性能。因此，仍需进行更多研究来更好地前瞻性评估数据的充足性。
## 136. `cs.LG` - 超越期望：AI方法与经典算法在最大独立集问题上的比较 [PDF](https://arxiv.org/pdf/2502.03669), [HTML](https://arxiv.org/abs/2502.03669)
### Authors
Yikai Wu,Haoyu Zhao,Sanjeev Arora
### Background
近年来，生成模型和强化学习等AI方法被应用于组合优化（CO）问题，特别是NP难问题。本文将基于GPU的方法与基于CPU的经典方法在最大独立集（MIS）问题上的性能进行比较，发现即使是对于常规图数据，最先进的AI启发式方法的表现也比单一CPU运行的经典最优求解器KaMIS更差，有些AI启发式方法甚至无法超越基于度数的贪心启发式方法，即使经过本地搜索等后处理技术，AI启发式方法仍然表现不如CPU基求解器。
### Innovation
本文提出了一个新的分析方法——串行化（serialization），通过这一方法揭示了基于非回溯路径的AI启发式方法如LTFT（基于GFlowNets）最终的推理过程类似于基于度数的贪心启发式方法，因此性能更差。研究结果表明，需要重新考虑当前AI在CO问题上的方法，提倡更严格的基准测试和传统启发式方法的原则性集成。此外，研究发现基于CPU的算法KaMIS在稀疏随机图上表现良好，这表明Coja-Oghlan和Efthymiou（2015年）提出的关于大独立集的破碎阈值猜想不适用于现实规模（如10^6节点）。
### Conclusion
本文结论指出，当前AI方法在CO问题上的表现未达到预期，提倡重新审视和评估AI方法，特别是需要强调更严格的基准测试和将传统启发式方法有效集成的重要性。
## 137. `cs.LG` - 基于正交表示学习估计因果量 [PDF](https://arxiv.org/pdf/2502.04274), [HTML](https://arxiv.org/abs/2502.04274)
### Authors
Valentyn Melnychuk,Dennis Frauen,Jonas Schweisthal,Stefan Feuerriegel
### Background
端到端表示学习已经成为从高维观察数据中估计因果数量的一个强大工具，但其效率尚未明确。现有方法中，端到端表示学习通常在实践中效果良好，但在渐近最优性方面（以准Oracle效率的形式）缺乏理论保障。另一方面，两阶段Neyman-正交学习器提供了理论最优性，但不能充分利用表示学习的优点。
### Innovation
本文提出了连接表示学习和Neyman-正交学习器（即OR-学习器）的统一框架。研究发现，在低维流形假设下，OR-学习器可以严格降低标准Neyman-正交学习器的估计误差。同时，研究指出平衡约束需要额外的归纳假设，并不能普遍弥补端到端方法在Neyman-正交性上的不足。基于这些发现，本文提供了如何结合表示学习和经典Neyman-正交学习器以实现实际性能和理论保证的指导。
### Conclusion
用户可以通过结合表示学习和经典的Neyman-正交学习器来同时获得实际效果和理论保证。这种结合可以在标准方法的基础上显著提高因果量估计的准确性，从而更好地应用于实际问题中。
## 138. `cs.LG` - Planning模块化世界世界模型在交通信号控制中的规划的观测失配问题 [PDF](https://arxiv.org/pdf/2501.02548), [HTML](https://arxiv.org/abs/2501.02548)
### Authors
Zherui Huang,Yicheng Liu,Chumeng Liang,Guanjie Zheng
### Background
将训练决策系统部署到不同不同不同的场地时 where,这些设备上偵测管道有所不同。。。.在这些情景中，即使底层的操作和目标保持不变,观测数据的特征和维度也可能改变环境条件发生变化。这使得基于学习的决策方法在应对这种观测失配问题方面面临挑战 on on这些情况下这种方法表现不佳。“背景描述了当前基于学习的决策方法在应对这种特定的观测不匹配情况下的局限性。”
### Innovation
本工作提出的“自适应模组化观点架构（（ AMM)”是一种针对这种观测失配的架构方案 on a方案中在一种通用一般的操作状态下从多个多个多个共享的内在模组化 dynamic定义在一个通用的操作空间中 on 上上一个‘中，从多个相关领域源域进行元学习以实现能快速 enabling适应和在目标交互有限的情况下快速。运行时运行时运行时这种方法通过进行“递后视野化控制”两通过在学过的动态下推出候选动作序列并 on选择出优化特定目标任务目标的预测结果表现。”证实了这种方法的优越性 on性能和效率优于现有常规控制器和基于学习的方法的基线方法。”“介绍方法提出了这一方案在交通信号控制上的的一实例。在这一实例中 on onactions on具体一方面动作对应于信号控制动作 on目标目标捕获拥堵情况 on实验结果表明 AMM方法在性能和效率上相较于现有常规控制器 on基于学习的基线基方法上有提升上 提升上了这一方法在感知失配上在交通信号领域的应用中的提出的数据驱动方法上.
### Conclusion
本工作通过提出的“自适应模组化观点架构 on AM AMM)”解决方案解决了基于学习方法在应对观测失配问题方面遇到的挑战 on通过这种方法在拥堵控制的一个实例上展示了该 A on on on AM AMM方法在性能 on效率上在针对交通信号控有上有优越表现 on这表明 AmM可以从多个几个来源域元学习并通过这种方式可以使有 on运行时运行一个有效的控制系统接口。”
## 139. `cs.LG` - 一种专家混合的视觉变换器用于高保真表面代码解码 [PDF](https://arxiv.org/pdf/2601.12483), [HTML](https://arxiv.org/abs/2601.12483)
### Authors
Hoang Viet Nguyen,Manh Hung Nguyen,Hoang Ta,Van Khu Vu,Yeow Meng Chee
### Background
量子纠错是大规模量子计算的关键组成部分，通过将逻辑信息编码到多个物理量子位中来抵御物理噪声。拓扑稳定码因其几何局部性及实际相关性而特别引人注目。然而，这些代码中的校验测量产生的一种证词必须被解码成恢复操作，使得解码成为可扩展实时操作的关键瓶颈。现有的解码器通常被分为两类：经典的算法型解码器提供强而稳定的基础，但在大码距或严格的延迟约束下可能会产生较大的计算开销；基于机器学习的解码器能够提供快速的GPU推理和灵活的功能逼近，但许多方法未能充分利用拓扑代码的网格几何结构与局部结构，这可能限制其性能。
### Innovation
本文提出了一种名为QuantumSMoE的量子视觉变换器解码器，它通过十字形状嵌入和自适应掩码整合代码结构，以捕捉局部相互作用和网格连通性，进而通过专家混合层及一种新的辅助损失函数提高可扩展性。实验结果表明，QuantumSMoE在近似最佳表面码解码领域优于当前最先进的人工智能解码器，同时其性能也超过了广泛使用的经典基线。
### Conclusion
量子视觉变换器（QuantumSMoE）代表了一种新颖的方法，通过更好地捕捉数据结构来提高拓扑代码的解码性能。这种解码器不仅在计算效率上有所突破，还在实现高保真度解码方面表现出色。
## 140. `cs.LG` - 浅层神经网络通过可学习信道注意力进行特征学习以学习低次度球面多项式 [PDF](https://arxiv.org/pdf/2512.20562), [HTML](https://arxiv.org/abs/2512.20562)
### Authors
Yingzhen Yang
### Background
该研究探讨了在训练一个带信道注意力机制的过参数化两层神经网络时，如何学习单位球体上定义的低次度球面多项式的问题。这些多项式的次度为 Δ_0 = Θ(1) ≥ 1。现有研究显示，学习此类低次度多项式所需的数据样本数量通常较高。以往的方法可能需要的数据样本数量并不为最优。
### Innovation
本文的主要创新在于，通过使用带信道注意力机制的过参数化两层神经网络，显著降低了学习低次度多项式所需的数据样本数量。文章证明了，在给定泛化的条件下，当回归风险 ε ∈ (0,1) 时，使用标准梯度下降（GD）的带信道注意力机制的神经网络需要的数据样本数量为 ∼ Θ(d^Δ_0 / ε)，这相较于之前的 Θ(d^Δ_0 ♪ ε^{-2}, π d) 更为优化。此外，本文中提出的神经网络的学习率与最小风险集合率吻合，表明该方法在学习低次度球面多项式方面具有最优性。
### Conclusion
这篇文章通过训练一个带信道注意力机制的过参数化但有固定宽度的神经网络，成功学习了低次度的球面多项式。同时，文中提供了一个可证明的学习通道选择算法，并通过此方法编码选择通道，确保了训练神经网络的有效性。此外，此方法获得的无偏风险界在最小风险集合率方面是最佳的，这是在实现特征学习功能的同时首次达到这一最优性。
## 141. `cs.LG` - GTAC：用于近似电路的生成变换器 [PDF](https://arxiv.org/pdf/2601.19906), [HTML](https://arxiv.org/abs/2601.19906)
### Authors
Jingxin Wang,Shitong Guo,Wenhui Liang,Ruicheng Dai,Ruogu Ding,Xin Ning,Weikang Qian
### Background
近似计算通过放宽严格的函数等效性标准，显著提高功率、性能和面积。传统的近似逻辑综合（ALS）依赖于逐步重写，限制了设计空间的探索。另一方面，基于Transformer的生成式AI由于其固有的概率性，非常适合作为生成近似电路的解决方案。
### Innovation
本文提出了一种端到端框架GTAC，用于任意规模的生成式ALS。GTAC通过生成式核心将大型电路分割成可处理的子电路，为每个子电路生成近似候选方案，并最终选择合适的候选方案形成最终设计。其核心的生成式Transformer利用了新颖的无冗余编码方法来紧凑地编码电路，并通过掩码机制排除违反给定误差边界的设计。此外，GTAC采用自我进化的训练策略，证明了相对于精确生成基线减少了30.9%的延迟和50.5%的门电路数量，以及节省了6.5%的面积和4.3倍的加速比传统的ALS方法。
### Conclusion
GTAC展示了优越的性能，尤其是在延迟、门电路数量、面积和速度性能上。其无冗余编码使序列长度减少了33.3倍，峰值内存减少了61.6倍，相比传统记忆无序列遍历方法。
## 142. `cs.LG` - BEAR: Towards Beam-Search-Aware Optimization for Recommendation with Large Language Models [PDF](https://arxiv.org/pdf/2601.22925), [HTML](https://arxiv.org/abs/2601.22925)
### Authors
Weiqin Yang,Bohao Wang,Zhenxiang Xu,Jiawei Chen,Shengjia Zhang,Jingbang Chen,Canghong Jin,Can Wang
### Background
近年来，研究者利用大规模语言模型（LLMs）进行推荐系统的研究取得了快速进展。传统的做法是通过有监督的微调（SFT）来适应推荐场景，并利用束搜索（beam search）在推理阶段高效地检索出排名前B的推荐项目。然而，这种方法存在训练与推理的一致性问题：尽管SFT可以优化正样本的整体概率，但它并不能保证这些项目在束搜索过程中一定能被检索到，即使它们具有较高的整体概率。束搜索通过贪婪的剪枝机制，可能导致正样本在不足以有足够前缀概率的情况下被提前排除。
### Innovation
本文提出了一种名为BEAR的新颖的微调目标，旨在解决训练与推理的一致性。BEAR在训练时明确考虑束搜索的行为，而无需在训练中模拟束搜索，这是计算上难以实现的。BEAR通过一个宽松但必要的约束条件来实现这一目标，即每个正样本中的令牌在解码的每一步都必须在候选令牌中排名前B。这种方法有效的减少了错误剪枝的风险，并且相比于标准的SFT几乎没有额外的计算开销。实验结果表明，BEAR在四个真实世界的数据集上都显著优于强大的基线方法。
### Conclusion
广泛的实验表明，BEAR方法在四个真实世界的数据集上都显著优于强大的基线方法。
## 143. `cs.LG` - shuffle 和联合差分隐私在广义线性上下文多臂老虎机中的应用 [PDF](https://arxiv.org/pdf/2602.00417), [HTML](https://arxiv.org/abs/2602.00417)
### Authors
Sahasrajit Sarmasarkar
### Background
此前对提供隐私保护的上下文多臂老虎机的研究主要集中在线性奖励模型上，这些模型提供了直接的估计器。然而，广义线性模型（GLMs）代表了根本性的新挑战：缺乏直接的估计器，需要进行私人凸优化；隐私需要跟踪多个不断变化的设计矩阵；并且优化误差必须明确地纳入后悔分析。
### Innovation
本文提出了首个适用于广义线性上下文多臂老虎机的shallo-DP和联合-DP算法，解决了这些挑战。对于随机上下文，设计了一个shaffle-DP算法，其主导项为$tilde{O}(d^{3/2}frac{text{sqrt}(T text{log} T)}{text{sqrt}(text{ε})})$的后悔，与无隐私情况下的速率相比，额外乘以了$frac{text{sqrt}(d/text{ε})}{1}$的因子。对于对抗性上下文，提供了一个联合-DP算法，其后悔为$tilde{O}(dtext{sqrt}(T) text{log} T + d^{3/4}text{sqrt}(frac{T}{text{ε}})(text{log} T)(d + text{log} T)^{1/4})$，仅在主要项上与无隐私情况下的速率$tilde{O}(dtext{sqrt}(T) text{log} T)$匹配，额外是隐私项提供了可忽略的附加修正。
### Conclusion
这些方法无需对上下文分布进行谱假设，仅需要进行$text{L}_2$有界性假设，克服了以往本地私人GLM多臂赛轮中的要求。
## 144. `cs.LG` - On the Convergence of Jacobian-Free Backonagate for Optimal Control Problems with Implicit Hamiltonians [PDF](https://arxiv.org/pdf/2602.00921), [HTML](https://arxiv.org/abs/2602.00921)
### Authors
Eric Gelphman,Deepanshu Verma,Nicole Tianjiao Yang,Stanley Osher,Samy Wu Fung
### Background
在基于学习的价值函数的方法中，由于存在隐式哈密顿量的最优反馈控制的封闭形式解的问题,最近的工作对提出了一种基于JFB反向传计算的隐式深度学习方法来解决这个问题，但仅建立了样本级下降的保障。
### Innovation
在本文中,我们为JFB在随机批量情况下提供了收敛性证明
### Conclusion
我们进一步证明了JFB的大范围维度问题控制情况下的可性性和了理论依据和以及实验证据结合最终建立了在隐式哈密顿量的最优控制中的使用JFB的适用性性和有效性。”
## 145. `cs.SE` - 减少行为驱动开发中的维护负担：具有110万步骤开放基准的鲁棒性重复步骤检测器 [PDF](https://arxiv.org/pdf/2604.20462), [HTML](https://arxiv.org/abs/2604.20462)
### Authors
Ali Hassaan Mughal,Noor Fatima,Muhammad Bilal
### Background
行为驱动开发（BDD）中的Gherkin步骤文本存在大量重复，导致维护成本增加。现有的重复检测器要么需要运行的测试，要么是单个组织的，这在跨组织环境中留下了空白。本研究旨在填补这一空白，通过提供一个大规模的跨组织BDD步骤语料库、一个标签对级的校准基准以及一个基于四策略的检测器，来检测重复步骤。
### Innovation
本研究创新地提供了迄今为止最大的跨组织BDD步骤语料库，以及一个打标签的对级校准基准。提出了一种四策略检测器，并结合了聚类和ISO/IEC 25010维护子特性的联系模型。此外，还开发了一个基于合并节省模型，评估重复步骤的潜在消除。
### Conclusion
研究结果表明，在语料库中，步骤的精确重复占80.2%，仓库范围内的中位数重复率为58.6%。提出的方法在不同策略检测器和基准上表现出显著的F1分数，特别是在语义方面。研究还估计了语料库中可消除步骤的总数，并指出了在中位数仓库中的可消除步数比例。
## 146. `cs.SE` - 关于‘情绪编码’的未来：大型语言模型生成代码在建筑安全中的实证评估 [PDF](https://arxiv.org/pdf/2604.12311), [HTML](https://arxiv.org/abs/2604.12311)
### Authors
S M Jamil Uddin
### Background
情绪编码是一种新的范式，它允许非技术人员通过自然语言指示大型语言模型（LLMs）生成可执行代码。这种编码方式在建筑行业中既带来了重大机遇也带来了显著风险。随着安全管理人员、在现场的负责人和工人能够开发工具和软件，大型语言模型的随机特性则增加了可能会出现‘沉默失败’的风险。即生成的代码可能会正确编译，但运行时包含数学安全逻辑错误。
### Innovation
该研究通过实证评估了由三位前沿模型Claude 3.5 Haiku、GPT-4o-Mini和Gemini 2.5 Flash生成的450段情绪编码的Python脚本，涵盖可靠性、软件架构和特定领域的安全性等方面的验证。使用基于角色的提示数据集（n=150）和隔离动态沙盒与LLM作为裁判的双轨评估框架，研究量化了零样本情绪编码在建筑安全方面严重的局限性。
### Conclusion
研究发现用户角色与数据幻象之间存在显著关系，不正式的提示极大地增加了人工智能创造缺失安全变量的可能性。尽管这些模型在基础执行可行性方面表现出色（约85%），但这种语法可靠性实际上掩盖了逻辑缺陷和缺乏防御性编程的严重问题。在成功执行的脚本中，研究发现了一个令人担忧的整体“沉默失败率”~45%，其中包括GPT-4o-Mini在可功能代码中有约56%生成了数学不准确的输出。研究表明当前的LLMs缺乏独立进行安全性工程所需的决定性严谨性，需要引入确定性AI包装并严控网络安全部署。
## 147. `cs.SE` - 全面覆盖测试场景的测试用例泛化 [PDF](https://arxiv.org/pdf/2604.21771), [HTML](https://arxiv.org/abs/2604.21771)
### Authors
Binhang Qi,Yun Lin,Xinyi Weng,Chenyan Liu,Hailong Sun,Gordon Fraser,Jin Song Dong
### Background
测试用例是软件开发和维护的关键。开发人员通常会基于对需求的理解和对各种测试场景的推测，从隐含模式中产生多个测试用例，每个测试用例验证一个特定的行为。然而，生成全面的测试是耗时且容易出错的。许多应当伴随初期测试的重要测试仅在重大延误之后才添加，有时在缺陷被触发后才添加。现有的自动化测试生成技术主要关注代码覆盖。但实际项目中，实用的测试通常不是仅由代码覆盖驱动的，因为测试场景与控制流分支不一定对齐。相反，测试场景源自需求，而这些需求往往是未记录的，且隐含地嵌入到项目的结构和实现中。
### Innovation
本文提出了一种框架TestGeneralizer，用于泛化测试用例以全面覆盖测试场景。TestGeneralizer总结了三个阶段：（1）增强对核心方法及其初始测试背后的需求和场景的理解；（2）生成测试场景模板，并其细化为多种测试场景实例；（3）从中生成和改进可执行的测试用例。本文以三种最先进的基线在12个开源Java项目中对TestGeneralizer进行了评估。实验结果表明，TestGeneralizer取得了显著改进：与ChatTester相比，在基于变异的场景覆盖和LLM评估的场景覆盖上分别提高了31.66%和23.08%。
### Conclusion
本文提出的TestGeneralizer框架通过还原需求和生成细化的测试场景实例，有效地泛化和改进测试用例，提高了测试覆盖率和有效性。
## 148. `cs.SE` - SWE-QA：语言模型在代码库级别问题的问题和回答 [PDF](https://arxiv.org/pdf/2509.14635), [HTML](https://arxiv.org/abs/2509.14635)
### Authors
Weihan Peng,Yuling Shi,Yuhang Wang,Xinyun Zhang,Beijun Shen,Xiaodong Gu
### Background
理解和推理整个软件仓库对于智能软件工程工具是至关重要的的能力。。 现有的基准，如 CoSQA和 和 on CodeQA 尰虽然推进了这个领域， 但它们主要 主要专注于独立 卵翻译的代码片段的推理问题上 迵而忽视了真实世界仓库中的 和 的综合复杂性 需要求在软件架构和 及长距离代码依赖上 的多推理能力。本文提出了一种新的基准测试
### Innovation
在SWE-QA中 实性呈设为促进自动化问题问答系统 真实应用场景中 提 熟设计了一个涵盖多种类问题料的代码库问题问答基准测试 
### Conclusion
实验结果展示了大规模语言模型在SWE-QA基准上的上的的强大潜力 指出SWE-QA代理框架在处理代码库级别问题生成上 上能力方面的优势明显 同时提出挑战并 为未来进一步的方向设定了基础
