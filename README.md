# Notes on interpretability 

## Overviews 

Molnar. [Interpretable machine learning. A Guide for Making Black Box Models Explainable](https://christophm.github.io/interpretable-ml-book/). 2019.

## Perspectives 

Zachary C. Lipton. [The Mythos of Model Interpretability](https://arxiv.org/abs/1606.03490). In *WHI 2016*.

Goodman and Flaxman. [European Union regulations on algorithmic decision-making and a "right to explanation"](https://arxiv.org/abs/1606.08813). In *WHI 2016*.

## Evaluation of explanatory methods

 Kindermans et al. [The (Un)reliability of saliency methods](https://arxiv.org/abs/1711.00867). In *ICLR 2018*.
 
 > Evaluating the reliability of saliency methods is complicated by a lack of ground truth, as ground truth would depend upon full transparency into how a model arrives at a decision---the very problem we are trying to solve for in the first place.

Feng et al. [Pathologies of Neural Models Make Interpretations Difficult](https://www.aclweb.org/anthology/D18-1407/). In *EMNLP 2018*.

 * Input reduction iteratively removes the least important word from the input.    
 * The remaining words appear nonsensical to humans and are not the ones determined as important by interpretation method.
 
 Poerner et al. [Evaluating neural network explanation methods using hybrid documents and morphosyntactic agreement](https://www.aclweb.org/anthology/P18-1032/). In *ACL 2018*.

  * Important characterization of explanation:   
  > A good explanation method should not reflect what humans attend to, but what task methods attend to.  
  * Interpretability differs between *small contexts* NLP tasks and *large context* tasks. 
  
 Sundararajan et al. [Axiomatic Attribution for Deep Networks.](https://arxiv.org/abs/1703.01365). In *ICML 2017*.  
 
* *Implementation invariance*: the attributions should be identical for two functionally equivalent networks (their outputs are equal for all inputs, despite having very different implementations). 

* *Sensitivity*: if network assigns different predictions to two examples that differ in only one feature then the differing feature should be given a non-zero attribution.
 
 Das et al. [Human Attention in Visual Question Answering: Do Humans and Deep Networks look at the same regions?](https://www.aclweb.org/anthology/D16-1092/). In *EMNLP 2016*.
 
 * Current attention models in VQA do not seem to be looking at the same regions as humans.     

## Self-explanatory models


### Textual explanations generation 

Kim et al. [Textual Explanations for Self-Driving Vehicles](https://arxiv.org/abs/1807.11546). In *ECCV 2018*.


## Lectures 

[Interpretability and Explainability in Machine Learning at Harvard University](https://interpretable-ml-class.github.io/)



