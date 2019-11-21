# GraphNeuralNetwork

## The Tools of the GraphNeuralNetwork

名称  | 类型  | 适用场景 | Github
 ---- | ----- | ------  | ------ 
 OpenNE	| 图表示学习	| 图节点表示学习，预训练 |	https://github.com/thunlp/OpenNE
Graph_nets |	图神经网络	| 基于关系模糊的图数据推理	| https://github.com/deepmind/graph_nets
DGL	| 图神经网络 |	建立图数据（可以无需通过networkx）并加载常用图神经网络 |	https://github.com/jermainewang/dgl
GPF	| 训练流程	| 基于关系数据的数据预测（节点分类、关系预测）|	https://github.com/xchadesi/GPF
networkx	| 图数据预处理	| 非大规模图数据预处理	| https://github.com/networkx/networkx
Euler	|工业级图深度学习框架	| 工业级图数据的用户研究快速进行算法创新与定制 |	https://github.com/alibaba/euler
PyG | 几何深度学习 | 适合于图、点云、流形数据的深度学习，速度比DGL快 | https://github.com/rusty1s/pytorch_geometric
PBG | 图表示学习 | 高速大规模图嵌入工具,分布式图表示学习，使用pytorch | https://github.com/facebookresearch/PyTorch-BigGraph
AliGraph | 图神经网络 | 阿里自研，大规模图神经网络平台 | https://arxiv.org/pdf/1902.08730.pdf
NSL | 图神经网络 | 主要用来训练图神经网络 | https://www.tensorflow.org/neural_structured_learning/
NGra | 图神经网络 | 支持图神经网络的并行处理框架 | https://arxiv.org/pdf/1810.08403.pdf

# The Method of Build GNN Model


关注点	| 类别	| 典型模型	| 引用 |	Github
---- | ----- | ------ | ------ | ------
**图类型**	|无向	|GNN	|  | 	
**图类型**	|	有向 |	ADGPM	|《Rethinking knowledge graph propagation for zero-shot learning》	| https://github.com/cyvius96/adgpm
**图类型**	|	异构图 |	GraphInception |	《Deep collective classification in heterogeneous information networks》 |	https://github.com/zyz282994112/GraphInception
**图类型**	|	带有边信息的图 |	G2S	|《 Graph-to-sequence learning using gated graph neural networks》 |	https://github.com/beckdaniel/acl2018_graph2seq
**图类型**	|	带有边信息的图 |		RGCN |《Modeling relational data with graph convolutionalnetworks》 | https://github.com/MichSchli/RelationPrediction /  https://github.com/masakicktashiro/rgcn_pytorch_implementation                         **聚合更新** |	谱方法卷积聚合 |	GCN		
**聚合更新** |	谱方法卷积聚合 |	ChebNet		
**聚合更新** |	非谱方法卷积聚合 |	MoNet		
**聚合更新** |	非谱方法卷积聚合 | DCNN	|《Diffusion-ConvolutionalNeural Networks》|	https://github.com/jcatw/dcnn
**聚合更新** |	非谱方法卷积聚合 |  GraphSAGE	|《GraphSage: Representation Learning on Large Graphs》| https://github.com/williamleif/GraphSAGE / https://github.com/williamleif/graphsage-simple
**聚合更新** |	注意力机制聚合	| GAT	|《Graph attention networks》|	https://github.com/PetarV-/GAT
**聚合更新** |	门更新机制	| GRU	| 《Gated graphsequence neural networks》| https://github.com/JamesChuanggg/ggnn.pytorch / https://github.com/yujiali/ggnn
**聚合更新** |	门更新机制	| LSTM	| 《Improved semanticrepresentations from tree-structured long short-term memory networks》 |	https://github.com/ttpro1995/TreeLSTMSentiment
**聚合更新** |	跳跃式连接 |	Highway GNN	| 《 Semi-supervised user geolocation via graph convolutional networks》|	https://github.com/afshinrahimi/geographconv
**聚合更新** |	跳跃式连接 |Jump Knowledge Network |	《Representation learning on graphs with jumping knowledge networks》	
**训练方法**	| 接受域的控制 |			
**训练方法**	|	采样方法	| FastGCN	|《FastGCN: Fast Learning with Graph Convolutional Networks via Importance Sampling》 |	https://github.com/matenure/FastGCN
**训练方法**	|	梯度提升方法 |	Co-Training GCN		
**训练方法**	|	梯度提升方法 | Self-training GCN		
**通用框架**	| 信息传播 |	MPNN	|《Neural message passing for quantum chemistry》 |	https://github.com/brain-research/mpnn
**通用框架**	| 非局部神经网络 |	NLNN	|《 Non-local neuralnetworks》|	https://github.com/nnUyi/Non-Local_Nets-Tensorflow / https://github.com/search?q=Non-local+neural+networks
**通用框架**	| 图神经网络	|GN	| 《Relational inductive biases, deep learning, andgraph networks》 |	https://github.com/deepmind/graph_nets

# The Application of the GraphNeuralNetwork

领域  | 应用  | 算法 | 引用 | Github
 ---- | ----- | ------ |  ----- | ------
**通用**  |关系预测 |RGCN| 《Modeling Relational Data with Graph Convolutional Networks》 | [rgcn_pytorch_implementation](https://github.com/masakicktashiro/rgcn_pytorch_implementation) 
 **通用** | 关系预测 | SEAL| 《Link Prediction Based on Graph Neural Networks》 | [SEAL](https://github.com/muhanzhang/SEAL)
**通用** |节点分类  |  |   |  
**通用** |社区检测  |  |《Improved Community Detection using Deep Embeddings from Multilayer Graphs》   | 
**通用** |社区检测  | Hierarchical GNN |  《Supervised Community Detection with Hierarchical Graph Neural Networks》 | 
**通用** | 图分类 |  | 《Graph Classification using Structural Attention》  | 
**通用** | 图分类 |DGCNN  |《An End-to-End Deep Learning Architecture for Graph Classification》| [pytorch_DGCNN](https://github.com/muhanzhang/pytorch_DGCNN)
**通用** | 推荐 |  GCN|  《Graph Convolutional Neural Networks for Web-Scale Recommender Systems》 | 
**通用**|图生成  | NetGAN  | 《 Net-gan: Generating graphs via random walks》  | 
**通用**| 图生成 | GraphRNN |  《GraphRNN: Generating Realistic Graphs with Deep Auto-regressive Models》 | 
**通用** | 图生成 |MolGAN  | 《 Molgan: An implicit generative model for small molecular graphs》  | 
**决策优化** | 旅行商问题 | GNN |  《Learning to Solve NP-Complete Problems: A Graph Neural Network for Decision TSP》《Attention solves your tsp》 | https://github.com/machine-reasoning-ufrgs/TSP-GNN https://github.com/wouterkool/attention-tsp
**决策优化** | 规划器调度 | GNN |  《Adaptive Planner Scheduling with Graph Neural Networks》《Revised note on learning quadratic assignment with graph neural networks》 | 
**决策优化**| 组合优化 | GCN structure2vec |  《Combinatorial Optimization with Graph Convolutional Networks and Guided Tree Search》《 Learning combinatorial optimization algorithms over graphs》 | [NPHard](https://github.com/IntelVCL/NPHard)
**交通** | 出租车需求预测 |  |  《Deep Multi-View Spatial-Temporal Network for Taxi Demand Prediction》 | [DMVST-Net](https://github.com/huaxiuyao/DMVST-Net)
**交通** | 交通流量预测 |  | 《Spatio-Temporal Graph Convolutional Networks:A Deep Learning Framework for Traffic Forecasting》  |[STGCN-PyTorch](https://github.com/FelixOpolka/STGCN-PyTorch)
**交通** | 交通流量预测 |  |  《DIFFUSION CONVOLUTIONAL RECURRENT NEURAL NETWORK: DATA-DRIVEN TRAFFIC FORECASTING》 | [DCRNN](https://github.com/liyaguang/DCRNN)
**传感网络** | 传感器布局 |  |   《Distributed Graph Layout for Sensor Networks》| 
**区域安全** | 疾病传播 |  |  《Predicting and controlling infectious disease epidemics using temporal networks》 | 
**区域安全** | 城市人流预测 |  |  《FCCF: Forecasting Citywide Crowd Flows Based on Big Data》 | 
**社交网络** | 影响力预测 | GCN/GAT | 《DeepInf: Social Influence Prediction with Deep Learning》  | [DeepInf](https://github.com/xptree/DeepInf)
**社交网络** | 转发动作预测 |  | 《Social Influence Locality for Modeling Retweeting Behaviors》  | 
**社交网络** | 转发动作预测 |  | 《 Predicting Retweet via Social Influence Locality》  | 
**文本**|	文本分类|	GCN	|"《Diffusion-convolutional neural networks》《 Convolutionalneural networks on graphs with fast localized spectral filtering》《Knowledgetransfer for out-of-knowledge-base entities : A graph neuralnetwork approach》《 Deep convolutional networks on graph-structured data》《 Semi-supervised classification with graph convolutional networks》《 Geometric deep learning on graphs and manifolds using mixture model cnns》"|[dcnn-tensorflow](https://github.com/RicardoZiTseng/dcnn-tensorflow)
**文本** | 文本分类 |GAT  | 《Graph attention networks》  | 
**文本** | 文本分类 | DGCNN |  《Large-scale hierarchical text classification with recursively regularized deep graph-cnn》|[DeepGraphCNNforTexts](https://github.com/HKUST-KnowComp/DeepGraphCNNforTexts)
**文本** |  文本分类| Text GCN |  《Graph convolutional networks for text classification》 | [text_gcn](https://github.com/yao8839836/text_gcn)
**文本**| 文本分类 |Sentence LSTM  | 《 Sentence-state LSTM for text representation》| [S-LSTM](https://github.com/leuchine/S-LSTM)
**文本**|序列标注(POS, NER)	Sentence LSTM	|《 Sentence-state LSTM for textrepresentation》|	https://github.com/leuchine/S-LSTM
**文本**|语义分类 | LSTM	|《 Improved semantic representations from tree-structured long short-term memorynetworks》| https://github.com/ttpro1995/TreeLSTMSentiment
**文本**|语义角色标注Syntactic | GCN	|《Encoding sentences with graph convolutional networks for semantic role labeling》	|
**文本**|机器翻译	| GCN	|《Graph convolutional encoders for syntax-aware neural machine translation》/《 Exploiting semantics in neural machine translation with graph convolutional networks》"	
**文本**|机器翻译	|	GGNN	|《 Graph-to-sequence learningusing gated graph neural networks. 》|	https://github.com/beckdaniel/acl2018_graph2seq
**文本**|关系抽取 | LSTM	|《 End-to-end relation extraction usinglstms on sequences and tree structures》|	
**文本**|关系抽取 |Graph LSTM	|《Crosssentencen-ary relation extraction with graph lstms》/《 N-ary relationextraction using graph state lstm》|	https://github.com/freesunshine0316/nary-grn
**文本**|关系抽取 |	GCN	|《 Graph convolution over pruned dependency trees improves relation extraction》 |	https://github.com/qipeng/gcn-over-pruned-trees
**文本**|事件抽取|GCN	|《 Jointly multiple events extractionvia attention-based graph information aggregation》/《. Graph convolutional networks with argument-aware pooling for event detection》|	https://github.com/lx865712528/JMEE
**文本**|文本生成	| Sentence LSTM	|《A graph-to-sequence mdel for amr-to-text generation》|	
**文本**|文本生成 |	GGNN	|《 Graph-to-sequence learningusing gated graph neural networks》|
**文本**|阅读理解 | 	Sentence LSTM	|《Exploring graph-structured passage representation for multihop reading comprehension with graph neural networks》	|
**图像/视频** | 社会关系理解 |	GRM	|《Deep reasoning with knowledge graph for social relationship understanding》|	https://github.com/wzhouxiff/SR
**图像/视频** | 图像分类 |	GCN	|《 Few-shot learning with graph neuralnetworks》/《Zero-shot recognition via semantic embeddings and knowledge graphs》| https://github.com/louis2889184/gnn_few_shot_cifar100 https://github.com/JudyYe/zero-shot-gcn
**图像/视频** | 图像分类 |	GGNN	|《 Multi-label zero-shot learning with structured knowledge graphs》|	https://people.csail.mit.edu/weifang/project/vll18-mlzsl/
**图像/视频** | 图像分类 | ADGPM	|《Rethinking knowledge graph propagation for zero-shot learning》|	https://github.com/cyvius96/adgpm
**图像/视频** | 图像分类 |	GSNN	|《The more you know: Using knowledge graphs for image classification》	| https://github.com/KMarino/GSNN_TMYN
**图像/视频** | 视觉问答	| GGNN	|《Graph-structured representations for visual question answering》/《Deep reasoning with knowledge graph for social relationship understanding》 "	
**图像/视频** | 领域识别 |	GCNN	|《Iterative visual reasoning beyond convolutions》|	https://github.com/coderSkyChen/Iterative-Visual-Reasoning.pytorch
**图像/视频** | 语义分割	| Graph LSTM	|《 Interpretablestructure-evolving lstm》《 Semantic objectparsing with graph lstm》
**图像/视频** | 语义分割	|	GGNN	|《Large-scale point cloud semantic segmentation with superpoint graphs》| https://github.com/loicland/superpoint_graph
**图像/视频** | 语义分割	|	DGCNN	|《Dynamic graph cnn for learning on point clouds》|	https://github.com/af13s/dgcnn-amino
**图像/视频** | 语义分割	|	3DGNN	| 《 3d graph neural networks for rgbd semantic segmentation》|	https://github.com/yanx27/3DGNN_pytorch
**生物科技** | 物理系统	| IN	|《 Interaction networks for learning about objects, relations and physics》| https://github.com/higgsfield/interaction_network_pytorch https://github.com/jaesik817/Interaction-networks_tensorflow
**生物科技** | 物理系统	| VIN |	《 Visual interaction networks: Learning a physics simulator from video》	
**生物科技** | 物理系统	| GN	|《 Graph networks as learnable physics engines for inference and control》|	https://github.com/fxia22/gn.pytorch
**生物科技** |分子指纹 |	GCN	|《Convolutional networks on graphs for learning molecular fingerprints》|	https://github.com/fllinares/neural_fingerprints_tf
**生物科技** |分子指纹 |		NGF	|《Molecular graph convolutions: moving beyond fingerprints》 |
**生物科技** |蛋白质界面预测 |	GCN	|《Protein interfaceprediction using graph convolutional networks》 | https://github.com/fouticus/pipgcn
**生物科技** |药物副作用预测	| Decagon	|《Modeling polypharmacyside effects with graph convolutional networks》|	https://github.com/miliana/DecagonPython3
**生物科技** | 疾病分类 |	PPIN	|《Hybrid approach of relation network and localized graph convolutional filtering for breast cancer subtype classification》 |
