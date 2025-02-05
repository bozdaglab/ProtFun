## ProtFun: A Protein Function Prediction Model Using Graph Attention Networks with a Protein Large Language Model

![Top-DTI Overview](images/pipeline.png)

## ProtFun

We propose a multi-modal deep learning architecture called **ProtFun** to predict protein functions. ProtFun
integrates protein large language model (LLM) embeddings as node features in a protein family network. Employing a
graph attention network (GAT) on this protein family network, ProtFun learns protein embeddings, which are integrated
with protein signature representations from InterPro to train a protein function prediction model. We evaluated our
architecture using two benchmark datasets.