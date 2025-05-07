# Legacy NLP vs Modern Transformer Architecture Using DistilBERT

Revisiting and improving upon prior research is how we advance scientific understanding. We aimed to reproduce the Natural Language Processing (NLP) methods described in Chen et al.(2016) with an updated architecture. This paper explores practical advantages and benchmark accuracy between current transformer NLP methods and legacy neural network-based approaches. To create a controlled comparison, we recreated the original data set using the methods described in the Git repository (Chen, n.d.). We compared those results to modern transformer architecture in NLP with Distilled Bidirectional Encoder Representations from Transformers (DistilBERT), which would improve the accuracy of previous NLP methods. The main challenge is that modern transformer-based NLP has high hardware demands which require workarounds, including dataset limits and infrastructure tradeoffs. However, we achieved a peak accuracy score of 89.44% using DistilBERT while the legacy framework only achieved 23.09% at its peak.

## Repository Contents:
* `README.md`: This file
* `paper.tex`: The paper as a TeX file, where a majority of the reworking was done due to the project submission's requirements
* `paper.ipynb`: The paper as a Jupyter Notebook, where a majority of the tabular and graphiacal work was done to make the paper readable
* `paper.pdf`: The paper as a PDF file
* `proj.ipynb`: The project file taken from Colab
* `test.hf.json`: A test dataset that was used in our project. All of the datasets would be too large for the repository
* `model results/`: A folder containing all of the model results achieved in our project

## Note:
This assignment was originally programmed on Google Colab using an A100 GPU to be able to actually compute our project. The project code is provided in the repository, but if you wish to run this yourself, good luck.

### References:
* Chen, D., Bolton, J., & Manning, C. D. (2016). A thorough examination of the CNN/Daily Mail Reading Comprehension Task. Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers). https://doi.org/10.18653/v1/p16-1223
* Chen, D. (n.d.). Danqi/RC-CNN-dailymail: CNN/Daily Mail Reading Comprehension task. GitHub. https://github.com/danqi/rc-cnn-dailymail
* Aguilera, F. M. (2025, April 18). Transformer-based multiple choice question answering: Implementation, output analysis, and bias... Medium. https://medium.com/ai-simplified-in-plain-english/transformer-based-multiple-choice-question-answering-implementation-output-analysis-and-bias-e04d3d6d9c03
* Winland, V. (2025, March 11). What is self-attention?. IBM. https://www.ibm.com/think/topics/self-attention
* Anishnama. (2023, May 4). Understanding gated recurrent unit (GRU) in deep learning. Medium. https://medium.com/@anishnama20/understanding-gated-recurrent-unit-gru-in-deep-learning-2e54923f3e2
* Cho, K. (n.d.). DeepMind Q&A Dataset. DMQA. https://cs.nyu.edu/~kcho/DMQA/ 