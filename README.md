# Movie-Recommendation-System


This project presents a hybrid Movie Recommendation System designed to deliver personalized movie suggestions by combining deep learning and graph-based techniques. The model integrates Neural Collaborative Filtering (NCF) to capture complex non-linear user–item interactions and Light Graph Convolutional Networks (LightGCN) to leverage the structural relationships between users and movies. To further enhance performance, additional side features such as user demographics (age, gender) and movie genres are incorporated, improving recommendation quality and addressing challenges like data sparsity and cold-start problems. The system is trained on the MovieLens-1M dataset with preprocessing techniques such as rating binarization and negative sampling to optimize learning. Evaluation using metrics like Hit Ratio (HR@10) and NDCG@10 demonstrates that the proposed hybrid approach outperforms traditional models, providing more accurate, scalable, and context-aware recommendations suitable for real-world applications.




# Abstract




 This paper presents a hybrid film recommendation system that utilizes Neural Collaborative Filtering (NCF), Lightweight Graph convolution Networks (LightGCN) model,
and comprehensive side features of user and item to increase the precision of top-K movie recommendations over large datasets. Traditional NCF models do an excellent job of modelling the
nonlinear interactions between users and movies however NCFs have difficulties with sparse rating matrices and LightGCNs' modelling of the context is done through graph structures which
often miss contextual signals. To overcome the limitations of NCFs and LightGCNs, the proposed model combines the use of the Generalised Matrix Factorisation (GMF) & Multi-Layer Perception (MLP) components of NCF, with the propagation methodology of LightGCN in order to leverage advanced user item interactions and structural neighbourhood embeddings. Additionally, auxiliary information such as demographic information about the user, and genre information of the item
have been included to enhance representation quality and help to alleviate cold-start issues. Experiments conducted using the MovieLens-1M dataset demonstrated that the proposed hybrid
system outperforms the independent baselines for HR@10 and NDCG@10, and begins to converge earlier and generalises better across the sparsest segments of users. Overall, these findings
support the integration of deep modelling of interactions, graph based modelling of learning and fusion of side information to produce an advanced recommender system.
