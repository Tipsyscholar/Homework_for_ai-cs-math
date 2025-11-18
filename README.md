# 🚀 CAMP2026 


> 工程师的**系统之力 (CS)**, 架构师的**算法之智 (AI)**, 理论家的**数学之核 (Math)**

---

### 🏛️ I. 计算机科学 (CS) - 系统与工程

*语言栈: C/C++, Python, Go*


| 课程编号 | 课程名称/主题 | 来源 | 核心技术栈/目标 |
| :--- | :--- | :--- | :--- |
| **UCB CS 61A** | 计算机程序的结构与解释 | UCB | Python, 函数式编程, 抽象思维, 解释器原理 |
| **Stanford CS 106B&L**| C++ 编程 | Stanford | C++ (现代 C++11/17/20), STL, 模板, RAII |
| **MIT 6.006** | 算法导论 | MIT | Python, 算法设计, 复杂度分析, 数学证明 |
| **CMU 15-213**| 计算机系统：程序员视角 (CS:APP) | CMU | C, x86-64 汇编, OS 用户态, 链接, 缓存, 网络编程 ,CPU Datapath,Pipelining(UCB CS 61C补充)|
| **Stanford CS 149**| 并行计算架构与编程 | Stanford | CUDA, OpenMP, MPI, GPU 编程, 并行架构 |
| **Stanford CS 144**| 计算机网络 | Stanford | C++, TCP/IP 协议栈实现, 路由, 网络理论 |
| **UCB CS 162** | 操作系统与系统编程 | UCB | C, OS 内核态, 调度器, 文件系统, 高级并发 |
| **Stanford CS 143**| 编译原理 | Stanford | 编译器前端/后端, LLVM, 优化 |
| **CMU 15-445**| 数据库系统 | CMU | SQL, C++, 数据库内核 (B+ 树, MVCC, 恢复) |
| **Stanford CS 246**| 大规模数据挖掘 | Stanford | 大规模数据挖掘, MapReduce, Spark, 推荐系统 |
| **MIT 6.824** | 分布式系统 | MIT | Raft 共识算法, Go 语言, 容错, gRPC |
---

### 🧠 II. 人工智能 (AI) - 算法与模型

*AI前沿通识: NLP, CV, DGM, RL/Fine-tuning*

| 课程编号 | 课程名称/主题 | 来源 | 核心技术栈/目标 |
| :--- | :--- | :--- | :--- |
| **Stanford CS 336**| 深度自然语言处理 | Stanford | NLP, Transformers, PyTorch, Hugging Face |
| **MIT 6.5940** | TinyML 与高效深度学习计算 | MIT | AI 系统, 模型量化, 剪枝, 知识蒸馏 |
|**Nanochat**	|项目复现	|N/A	|AI 工程实践, LLM, 系统复现
| **UCB CS 285** | 深度强化学习 | UCB | 强化学习, Q-Learning, Policy Gradients (PPO) |
| **UCB CS 294-158**| 深度无监督学习 | UCB | GANs, VAEs, Flow-based Models, 自监督学习 |
| **MIT 6.S987** | 深度生成模型 | MIT | 生成模型 (GANs, VAEs, Flows, 扩散模型) |
| **MIT 6.S184** | 基于 SDE 的生成式 AI | MIT | SDEs, 扩散模型 (Diffusion Models), Score-Matching |
|**ZJU CV**|计算机视觉|ZJU |SFM,SLAM,3DCV|
| **USTC CG** | 计算机图形学 |USTC| C/C++, 3DGS,NeRF|
|**CMU 15-858**|离散微分几何|CMU| 离散曲线与曲面、外代数、外微分、Stokes定理应用(曲面平滑、参数化、矢量场设计)|
|**MIT 6.8410**|形状分析 |MIT|离散曲率,度量嵌入,有限元 FEM ,离散外微分DEC,形状对应与映射 |



---

### 🌌 III. 数学 (Math) - 理论护城河



| 领域 | 主题/课程 | 来源 | 核心内容 |
| :--- | :--- | :--- | :--- |
| **0. 分析学** |  | 基本功 | 数学分析, 实分析, 复分析, 泛函分析, 变分法, 测度论 |
| **1. 随机分析** |高等概率论|ZJU|无穷可分, 中心极限, 大数定律, 鞅极限|
|| 随机分析 | PKU | 应用随机分析, 随机过程, 鞅表示, SDEs, 随机积分|
| | 随机最优控制 | XJTU | 随机动态规划, LQG问题, 次优控制|
| **2. 计算数学** | 矩阵计算 | ZJU | SVD, QR分解, 特征值数值解, 迭代算法, 矩阵分析|
| | PDE数值解 | ZJU  | PDE理论,有限元,有限差分 |
| **3. 数据科学** | 组合优化 | ZJU | 初等数学, 图论, 运筹学, 整数规划, 博弈论 |
| | 大数据算法 | PKU | 大规模算法, 随机算法, 近似算法 |
| | 机器学习 |MIT | 随机优化, VC理论, 在线学习, SVM, 应用统计|

---

### 🚀 IV. 论文阅读与复现 (Paper Reading)

>致力于更创新的，更准确，更快速的DGM（深度生成模型）科学计算算法以及RL/微调算法

|标题| 来源|分类|核心内容|
| :--- | :--- |:--- |:--- |
|No One-Size-Fits-All Neurons: Task-based  Neurons for Artificial Neural Networks|arxiv|网络架构|使用遗传算法或者张量分解来找多项式，找出最适合的阶数作为动力信息传到网络，保留激活函数，训练微调，可以并行加速，并且泛化友好;但实验太简单|
|MULTILINEAR OPERATOR NETWORKS|ICLR 2024|网络架构|除去了非线性激活层，从而可以显式写出来拟合表达式,采用全秩+低秩信息混合:Y = C[(AX) * (BDX) + AX];<br><br>ImageNet C测鲁棒性，发现低归纳偏置（处理比较通用，一般是ViT,CNN是高归纳偏置），小数据一般不佳，但是monet也效果好 说明捕捉发现规律的效率很快，捕食者模型ODE推的效果非常好。<br><br>消融实验:（金字塔结构（有效果，节省计算），宽和深，（深更好）空间位移错位交叉（不重要），低秩压缩，（可以压得很大但不影响准确率）|
|Hyper-Compression: Model Compression via Hyperfunction|arxiv|模型压缩|用非有理缠绕让一条线遍历二维单位正方形，用kd树最近邻搜索来记录参数值，这样参数的浮点数就变成了整数，能减少存储比特;<br><br>把参数按照K=2分组，选定a使得尽量密铺，并且分成M组来缩放，可以并行加速|
|An AI-Aided Algorithm for Multivariate Polynomial Reconstruction on Cartesian Grids and the PLG Finite Difference Method|JSC 2024|高级数据结构与算法|三角格和主格之间用D阶置换群来通信，用部分置换的想法来把问题分解成为顺序操作，从而可以用回溯法来生成一个适定的三角格，以便于对边界进行多项式拉格朗日插值，其中回溯的顺序用到了部分置换群;<br><br>小意外的发现是最小二乘的条件数随膨胀先小后急剧升高|