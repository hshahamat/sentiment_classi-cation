# Neural Attentive Network for Cross-Domain Aspect-level Sentiment Classiﬁcation

A tensorflow implementation (non official) of the paper "Neural Attentive Network for Cross-Domain Aspect-Level Sentiment Classification".
https://ieeexplore.ieee.org/document/8632754

## Abstract
This work takes the lead to study the aspect-level sentiment classification in the domain adaptation scenario . Given a document of any domains, the model needs to figure out the sentiments with respect to fine-grained aspects in the documents. Two main challenges exist in this problem. One is to build a robust document modeling across domains; the other is to mine the domain-specific aspects and make use of the sentiment lexicon. In this paper, we propose a novel approach Neural Attentive model for cross-domain Aspect-level sentiment CLassification (NAACL), which leverages the benefits of the supervised deep neural network as well as the unsupervised probabilistic generative model to strengthen the representation learning. NAACL jointly learns two tasks: (i) a domain classifier, working on documents in both the source and target domains to recognize the domain information of input texts and transfer knowledge from the source domain to the target domain. In particular, a weakly supervised Latent Dirichlet Allocation model (wsLDA) is proposed to learn the domain-specific aspect and sentiment lexicon representations that are then used to calculate the aspect/lexicon-aware document representations via a multi-view attention mechanism; (ii) an aspect-level sentiment classifier, sharing the document modeling with the domain classifier. It makes use of the domain classification results and the aspect/sentiment-aware document representations to classify the aspect-level sentiment of the document in domain adaptation scenario. NAACL is evaluated on both English and Chinese datasets with the out-of-domain as well as in-domain setups. Quantitatively, the experiments demonstrate that NAACL has robust superiority over the compared methods in terms of classification accuracy and F1 score. The qualitative evaluation also shows that the proposed model is capable of reasonably paying attention to those words that are important to judge the sentiment polarity of the input text given an aspect.


<div align="center">
    <img src="/Illustration.PNG">
</div>
