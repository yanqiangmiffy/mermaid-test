| 主类别 | 子类别 | 数据集名称 | 核心特点与任务 | 常用评估指标 | 主要挑战与研究焦点 | 
|--------|--------|------------|----------------|--------------|-------------------| 
| 通用知识类数据集 | 开放领域问答 | Natural Questions | 基于真实用户查询，测试模型在开放领域问答中的检索与生成能力 | Exact Match (EM), F1 Score, Accuracy, eRAG scores | 复杂查询理解、多模态信息整合 | 
| 通用知识类数据集 | 开放领域问答 | TriviaQA | 开放领域问答任务，涵盖广泛常识性问题 | Exact Match (EM), F1 Score | 信息检索的全面性与答案生成的准确性 |
| 通用知识类数据集 | 开放领域问答 | T-REX | 用于评估RAG系统在开放领域知识问答中的表现 | Exact Match (EM), F1 Score | 生成答案的准确性与连贯性 |
| 通用知识类数据集 | 开放领域问答 | WebQuestions | 基于真实搜索查询的问答数据集 | token-level F1 score, Exact Match (EM) | 信息检索的多样性与答案的自然语言生成 |
| 通用知识类数据集 | 多跳问答 | HotpotQA | 跨文档推理问题，测试模型整合多个文档生成答案的能力 | Exact Match (EM), F1 Score, top-10 retrieval accuracy, NDCG@10 | 多文档推理、证据链构建 | 
| 通用知识类数据集 | 多跳问答 | SQuAD | 基于维基百科的问答数据集，用于评估模型在结构化内容中的表现 | top-k retrieval accuracy (k=5,10,20), Exact Match (EM), F1 Score | 信息检索的准确性与答案生成的连贯性 |
| 通用知识类数据集 | 多跳问答 | CRISP-DM-based question set | 基于数据科学方法论构建的问题集，用于评估RAG在不同阶段的表现 | - | 信息检索与生成的场景适配性 | 
| 通用知识类数据集 | 事实验证 | FEVER | 用于验证RAG系统生成答案时是否能够准确判断声明的真伪 | Exact Match (EM), F1 Score, Accuracy | 事实验证的准确性与生成答案的可信度 |
| 通用知识类数据集 | 对话生成 | Wizard of Wikipedia | 多轮对话数据集，测试RAG在对话场景中的信息检索与生成能力 | F1 Score | 上下文理解、自然语言生成的连贯性 | 
| 通用知识类数据集 | 对话生成 | CoQA | 多轮对话问答数据集，用于评估RAG在对话生成中的表现 | - | 上下文理解与多跳推理能力 | 
| 专业领域类数据集 | 医学知识问答 | MedQA-US | 医学领域问答数据集，用于评估RAG在医疗场景中的准确性 | Accuracy | 医学术语理解、答案的临床相关性 | 
| 专业领域类数据集 | 医学知识问答 | PubMedQA | 生物医学领域问答数据集，用于评估RAG在科学文献中的表现 | Exact Match (EM), F1 Score, Recall, BERTScore, Semantic Similarity, RAGAS metrics | 专业术语处理、答案的科学准确性 | 
| 专业领域类数据集 | 医学知识问答 | MMLU-Med | 医学知识问答数据集，用于评估RAG在医学常识与推理中的表现 | Accuracy | 医学知识的深度理解与推理能力 | 
| 专业领域类数据集 | 医学知识问答 | sarus-tech/medical_dirichlet_phi3 | 合成医学文档数据集，用于测试RAG在隐私保护下的生成能力 | Accuracy | 隐私保护与生成答案的准确性 | 
| 专业领域类数据集 | 法律与金融知识问答 | DragonBall | 跨金融、法律、医疗领域的综合RAG基准数据集 | Completeness, Hallucination, Irrelevancy, RAG Retrieval Recall, Effective Information Rate (EIR) | 多领域知识整合、生成答案的可靠性 | 
| 专业领域类数据集 | 科学与教育 | arXiv API dataset | 学术论文数据集，用于构建RAG系统在数据科学文献导航中的能力 | Context Relevance, Faithfulness, Answer Relevance | 高密度术语处理、信息检索的准确性 | 
| 专业领域类数据集 | 科学与教育 | Physics Journal Review-Article | 物理学领域综述文章数据集，用于评估RAG在科学内容中的表现 | final average score | 专业术语理解、信息整合能力 | 
| 专业领域类数据集 | 科学与教育 | Textbook-based fine-tuning dataset | 教科书内容数据集，用于RAG系统在教育领域的微调与评估 | - | 教育内容的结构化处理与知识生成 | 
| 评估与基准类数据集 | 基准测试数据集 | KILT | 知识密集型语言任务基准，涵盖多个RAG任务 | Exact Match (EM), F1 Score, Accuracy, eRAG scores | 多任务评估、跨领域泛化能力 | 
| 评估与基准类数据集 | 基准测试数据集 | SuperGLUE | 自然语言理解任务基准，用于RAG系统的综合评估 | - | 多维度理解能力、跨任务一致性 | 
| 评估与基准类数据集 | 基准测试数据集 | CRAG | 多源知识RAG基准，包含网页和API数据 | accuracy, hallucination rate | 多源信息整合、减少生成幻觉 | 
| 评估与基准类数据集 | 基准测试数据集 | TREC RAG'24 | 用于评估RAG系统在响应生成任务中的表现 | - | 响应生成质量与时间效率的平衡 | 
| 评估与基准类数据集 | 评估框架数据集 | RAGAS | 用于自动评估RAG系统质量的框架 | - | 评估指标的多样性与自动化评估的可靠性 | 
| 评估与基准类数据集 | 评估框架数据集 | Meta Evaluation Dataset | 用于评估RAG系统与人类偏好一致性的数据集 | correlation, human agreement rate | 人类偏好建模、评估指标的客观性 |
