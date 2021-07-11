# NMA2020 Project: Decoding semantic features  from different ROIs
The [Neuromatch Academy](neuromatchacademy.org) was a summer school organised amidst the Covid Pandemic for neuro-enthusiasts. The school was focussed on Computational Neuroscience and provided a great opportunity to learn and to interact with poeple of similar interest.

This also provided us with an opportunity to work on a small project (ranging over 3 weeks) based on certain datasets provided by the Academy. Our Group, Kaysonian Rhapsody, from Pod 118 Hairy Grasshoppers chose Kay Gallant Dataset **To Decode semantic features  from different ROIs**

## Objective

The main idea was to gather both stimuli and responses to meaningful low dimension using dimensionality reduction algorithms (Deep Neural Networks as well for stimuli) and then  analyze the semantic information by examining the corresponding pairs in low dimension visual.  
When we think about the region of interest, we can create a research question like which brain regions are providing more relevant semantic information similar to deep neural networks providing us.

### Research Question

Our aim was to discover the relationship between the **voxel responses** in the visual cortex and the **semantic properties of the images** shown.  
We wanted to approach the problem in two ways:
- The semantic representative roles of different Region of Interests (ROI): In which ROI is the semantic content of images represented?
- Representative performance of the voxel responses: How does the decoder performance vary with different images? 

## Kay and Gallant Dataset
- Blood-oxygen-level-dependant (BOLD) fMRI signals recorded of a passive grey scale stimuli (image size 20x20) by (Kay et al., 2008).
- Data has been preprocessed to contain a 2-D matrix of stimuli correspondence (row) and voxels in visual cortex(columns).
- Each point in this matrix represents the voxel response to a particular stimulus image.
- Dataset contained number of voxels per region of interest in visual cortex. 
- Processed BOLD Data was used by (Naselaris et al., 2009) for an image reconstruction task.

### Relevant Links:
- [Neuromatch Dataset Introduction Video](https://youtu.be/LdJkLyw4yzg)
- [Colab Notebook example for leading the Data](https://colab.research.google.com/github/NeuromatchAcademy/course-content/blob/master/projects/load_kay_images.ipynb)
- [The paper describing the dataset](https://www.nature.com/articles/nature06713)/[PDF](https://gallantlab.org/_downloads/2008a.Kay.etal.pdf)

## Literature Review
- [Reconstructing faces from fMRI patterns using deep generative neural networks](https://www.nature.com/articles/s42003-019-0438-y)
- [Revealing representational content with pattern-information fMRI--an introductory guide.](https://www.semanticscholar.org/paper/Revealing-representational-content-with-fMRI--an-Mur-Bandettini/70a13b2aa84cb076cb06919b54e0df22b0b74760)
- [Encoding and Decoding in fMRI](https://www.semanticscholar.org/paper/Encoding-and-decoding-in-fMRI-Naselaris-Kay/255910019e3661154eef356e93124ddce2931a2b)
- [Deep Residual Network Predicts Cortical Representation and Organization of Visual Features for Rapid Categorization](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5830584/pdf/41598_2018_Article_22160.pdf)
- [Neural Encoding for Human Visual Cortex with Deep Neural Networks Learning “What” and “Where”](https://www.biorxiv.org/content/10.1101/861989v1.full.pdf)
- [The Feature-Weighted Receptive Field: An Interpretable Encoding Model for Complex Feature Spaces](https://pubmed.ncbi.nlm.nih.gov/28645845/)
- [Using T-SNE to Visualise how your Deep Model thinks](https://buzzrobot.com/using-t-sne-to-visualise-how-your-deep-model-thinks-4ba6da0c63a0)
- [Visualizing Data using t-SNE](https://lvdmaaten.github.io/publications/papers/JMLR_2008.pdf)
- [Neural Network Feature Visualization » Deep Learning - MATLAB & Simulink](https://blogs.mathworks.com/deep-learning/2019/01/18/neural-network-feature-visualization/)
- [Overview of the YOLO Object Detection Algorithm | by ODSC - Open Data Science](https://medium.com/@ODSC/overview-of-the-yolo-object-detection-algorithm-7b52a745d3e0)
- [Neuroanatomy, Visual Cortex - StatPearls](https://www.ncbi.nlm.nih.gov/books/NBK482504/)
- [Visual Cortex](https://en.wikipedia.org/wiki/Visual_cortex#Primary_visual_cortex_(V1))
- [A Gabor Wavelet Pyramid-Based Object Detection Algorithm](https://www.researchgate.net/publication/220869739_A_Gabor_Wavelet_Pyramid-Based_Object_Detection_Algorithm#:~:text=A%20Gabor%20Wavelet%20Pyramid-Based%20Object%20Detection%20Algorithm.%20A,list%20of%20authors%29%2C%20clicks%20on%20a%20figure%20)

The Document with important points from Literature Review is [here](/Literature_Review.pdf)

## Tools and Libraries:
- sklearn
- numpy
- matplotlib
- skimage
- tensorflow
- keras
- pytorch

## Documentation
- [Documentation](/documentation-presentation.pdf)
- [Gdrive Folder](https://drive.google.com/drive/folders/1bK4BOY4B32O7IRcPZHGo0UHteYUDftBM?usp=sharing)

## People
- [Gordon Berman](https://twitter.com/gordonberman)(Mentor)
- [Kayson Fakhar](https://twitter.com/Kaysonfakhar)(TA)
- [Furkan Özçelik](https://twitter.com/OzceFurkan)
- [Aditya Prakash](https://github.com/prakashaditya369)
- [Amirreza Nadimi Shahraki](https://www.linkedin.com/in/amir-nadimi-shahraki-00a94975/)
- [Oğul Can Yurdakul](https://github.com/ogulyurdakul)

#### Thanks.
