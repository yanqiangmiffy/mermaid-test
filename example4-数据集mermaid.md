```mermaid
graph TD
    A[RAG系统评估数据集分类体系] --> B[通用领域RAG评估数据集]

    %% 一级分类
    B --> B1[问答任务]
    B --> B2[多跳问答任务]
    B --> B3[事实验证任务]
    B --> B4[生成任务]
    B --> B5[检索任务]
    B --> B6[多任务与综合评估]

    %% 问答任务
    B1 --> B1_1[TriviaQA]
    B1 --> B1_2[Natural Questions]
    B1 --> B1_3[HotpotQA]
    B1 --> B1_4[WebQuestions]
    B1 --> B1_5[2WikiMultiHopQA]
    B1 --> B1_6[MuSiQue]
    B1 --> B1_7[FEVER]
    B1 --> B1_8[SQuAD]
    B1 --> B1_9[SQuAD2]
    B1 --> B1_10[ASQA]
    B1 --> B1_11[T-REX]
    B1 --> B1_12[Wizard of Wikipedia (WoW)]
    B1 --> B1_13[NarrativeQA]
    B1 --> B1_14[TruthfulQA]
    B1 --> B1_15[CDQA]
    B1 --> B1_16[MultiRC]
    B1 --> B1_17[ReCoRD]
    B1 --> B1_18[RAGAS]

    %% 多跳问答任务
    B2 --> B2_1[HotpotQA]
    B2 --> B2_2[MultiHop-RAG]
    B2 --> B2_3[2WikiMultiHopQA]
    B2 --> B2_4[MuSiQue]

    %% 事实验证任务
    B3 --> B3_1[FEVER]
    B3 --> B3_2[PubHealth]

    %% 生成任务
    B4 --> B4_1[Wizard of Wikipedia (WoW)]
    B4 --> B4_2[CDQA]
    B4 --> B4_3[RAGTrace test dataset]
    B4 --> B4_4[CRUD-RAG]
    B4 --> B4_5[RagChecker benchmark dataset]

    %% 检索任务
    B5 --> B5_1[KILT]
    B5 --> B5_2[WikiEval]
    B5 --> B5_3[TREC-COVID]
    B5 --> B5_4[TREC DL 2019]
    B5 --> B5_5[TREC DL 2020]
    B5 --> B5_6[MS MARCO Passage Ranking]
    B5 --> B5_7[PubMed]
    B5 --> B5_8[Gorilla]
    B5 --> B5_9[Hindi-BEIR]
    B5 --> B5_10[NQ]
    B5 --> B5_11[ASQA]
    B5 --> B5_12[PubMedQA]
    B5 --> B5_13[medical_dirichlet_phi3]

    %% 多任务与综合评估
    B6 --> B6_1[CRUD-RAG]
    B6 --> B6_2[KILT]
    B6 --> B6_3[RagChecker benchmark dataset]
    B6 --> B6_4[RAGEval DragonBall]

```
