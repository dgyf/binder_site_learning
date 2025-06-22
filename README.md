# Binder_site_learning
 

## 1 Protein–protein and protein–nucleic acid binding site
prediction via interpretable hierarchical geometric deep
learning (GigaScience, 2024)

**Model name**: GraphRBF

**Aim**: protein binding sites, residue binding patterns！protein–protein and protein–nucleic acid binding sites (protein–DNA, and protein–RNA)

**Framework**: an enhanced graph neural network + a prioritized radial basis function neural network (capture the local residue spatial distributions) + a new radial basis function (termed gentle decay Gaussian-like function) + a kernel attention mechanism.

**Type**: classification

**Traits**: end-to-end, interpretable, hierarchical geometric deep learning model, residue information interaction based on molecular graphs, residue spatial distributions, <sequencec, structure> + <Notes, edges, coords>.

**Weak popints**: only utilizes protein local structures, ignoring information of the overall structure.

**Code source**: Y


## 2 DeepSTF: predicting transcription factor binding sites by
interpretable deep neural networks combining sequence
and shape (Briefings in bioinformatics, 2023)  
## 3 Improving the generalizability of protein-ligand binding predictions with AI-Bind (Nature communications, 2023)
## 4 Cooperation of local features and global representations by a dual-branch network for transcription factor binding sites prediction (Briefings in Bioinformatics, 2023)
## 5 GLPocket: A Multi-Scale Representation Learning Approach for Protein Binding (IJCAI, 2023 )
## 6 Dual modality feature fused neural network integrating binding site information for drug target afﬁnity prediction (NPJ Digital Medicine, 2025)
## 7 Highly accurate carbohydrate-binding site prediction with DeepGlycanSite (Nature Communications, 2024)
## 8 SurfDock is a surface-informed diffusion generative model for reliable and accurate protein–ligand complex prediction (Nature Methods. 2025)
## 9 EQUIBIND: Geometric Deep Learning for Drug Binding Structure Prediction (ICML, 2022)
## 10 GeoBind: segmentation of nucleic acid binding interface on protein surface with geometric deep learning (Nucleic Acids Research. 2023)

**Model name**: GeoBind

**Aim**: predicting nucleic binding sites on protein surface, 5 ligand binding sites prediction tasks. 

**Hypothesize**: molecular surfaces imply fingerprints of interaction patterns between proteins and nucleic acid.

**Framework**: point clouds -> <MSA information, chemical environment and local curvature> -> <MLP + quasi-geodesic convolutional layers + MLP> *4

**Type**: classification

**Traits**: GeoBind is invariant to 3D rotations and translations, GeoBind is able to analyze the surface of multimeric protein complex (due to MaSIF, point clouds)

**Code source**: Y


## 11 Protein–DNA binding sites prediction based on pre-trained protein language model and contrastive learning (Briefings in bioinformatics, 2024)

**Model name**: CLAPE-DB

**Aim**: predict DNA binding residues, protein–DNA binding sites, protein–ligand binding sites

**Framework**: three main modules: the sequence embedding module, the backbone network module and the loss computation module.

**Type**: classification

**Traits**: Pre-training + CL

**Code source**: Y


## 12 Gated-GPS: enhancing protein–protein interaction site prediction with scalable learning and imbalance-aware optimization  

**Model name**: Gated-GPS

**Aim**: protein–protein interaction site (PPIS) prediction

**Framework**: three main modules: the sequence embedding module, the backbone network module and the loss computation module.

**Type**: classification

**Traits**: addressing data scarcity, feature integration challenges, and class imbalance issues. (By expanding the training dataset, designing an innovative
model architecture, and refining the loss function)

**Code source**: Y

