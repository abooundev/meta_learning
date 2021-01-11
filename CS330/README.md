# CS330: Deep Multi-Task and Meta Learning

* Prof. Chelsea Finn
* site: https://cs330.stanford.edu/
* youtube: https://youtu.be/0rZtSwNOTQo

 **Week 1**

* [Course introduction, problem definitions, applications](http://cs330.stanford.edu/fall2019/slides/cs330_lecture1.pdf) 
* [Supervised multi-task learning, black-box meta-learning](http://cs330.stanford.edu/fall2019/slides/cs330_lec2.pdf) 

 **Week 2**

* [Optimization-based meta-learning](http://cs330.stanford.edu/fall2019/slides/cs330_lecture3.pdf) 
* ***Reading*** Applications in imitation learning, vision, language, generative models 

 **Week 3**

* [Few-shot learning via metric learning](http://cs330.stanford.edu/fall2019/slides/cs330_lecture4.pdf) 
* ***Reading*** Hybrid meta-learning approaches                

 **Week 4**

* [Bayesian meta-learning](http://cs330.stanford.edu/fall2019/slides/cs330_bayesian_metalearning.pdf) 
* ***Reading*** Meta-learning for active learning, weakly-supervised learning, unsupervised learning 

**Week 5**

* [Renforcement learning primer, multi-task RL, goal-conditioned RL](http://cs330.stanford.edu/fall2019/slides/cs330_mtrl.pdf) 
*  ***Reading*** Auxiliary objectives, state representation learning 

**Week 6**

* ***Reading*** Hierarchical RL, curriculum generation         
* ***Guest Lecture*** [Meta-RL, learning to explore](http://cs330.stanford.edu/fall2019/slides/Exploration in Meta-RL.pdf) 

**Week 7**

* ***Reading*** Meta-RL and emergent phenomenon                
* [Model-based RL for multi-task learning, meta model-based RL](http://cs330.stanford.edu/fall2019/slides/cs330_mbrl.pdf) 

**Week 8**

*  [Lifelong learning: problem statement, forward & backward transfer](http://cs330.stanford.edu/fall2019/slides/cs330_lifelonglearning.pdf) 
* ***Reading*** Miscellaneous multi-task/meta-RL topics        

**Week 9**

* ***Guest Lecture*** TBD                      
* ***Guest Lecture*** Information theoretic exploration  

### Timeline

| Date                    | Lecture                                                      | Deadlines                                                    | Optional reading                                             |
| :---------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
| **Week 1** Mon, Sep 14  | ***Lecture*** [Course introduction](https://cs330.stanford.edu/slides/cs330_intro.pdf) |                                                              |                                                              |
| **Week 1** Wed, Sep 16  | ***Lecture*** [Supervised multi-task learning, transfer learning](https://cs330.stanford.edu/slides/cs330_multitask_transfer_2020.pdf) |                                                              | [P1: Multi-Task Learning Using Uncertainty to Weigh Losses for Scene Geometry and Semantics.](https://arxiv.org/abs/1705.07115) Kendall et al. (2018)<br />[P2: Universal Language Model Fine-tuning for Text Classification.](https://arxiv.org/abs/1801.06146) Howard et al. (2018) |
| **Week 1** Thu, Sep 17  | ***TA Session*** [TensorFlow tutorial](https://cs330.stanford.edu/slides/TF2.pdf) |                                                              |                                                              |
| **Week 2** Mon, Sep 21  | ***Lecture*** [Meta-learning problem statement, black-box meta-learning](https://cs330.stanford.edu/slides/cs330_metalearning_bbox_2020.pdf) | **Homework 1 out** [[PDF](https://cs330.stanford.edu/material/CS330_HW1.pdf)][[Colab Notebook](https://colab.research.google.com/drive/1slBqgKa20iTatoWThMWZTnFysgAVD1vh?usp=sharing)] | [P1:One-shot Learning with Memory-Augmented Neural Networks.](https://arxiv.org/abs/1605.06065) Santoro et al. (2016) |
| **Week 2** Wed, Sep 23  | ***Lecture*** [Optimization-based meta-learning](https://cs330.stanford.edu/slides/cs330_optbased_metalearning_2020.pdf) |                                                              | [P1: Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks.](https://arxiv.org/abs/1703.03400) Finn et al. (2017)<br />[P2: Meta-Learning with Differentiable Convex Optimization.](https://arxiv.org/abs/1904.03758) Lee et al. (2019) |
| **Week 3** Mon, Sep 28  | ***Guest Lecture*** [Automatic differentiation ](https://cs330.stanford.edu/slides/CS330Autograd.pdf)([Matthew Johnson](http://people.csail.mit.edu/mattjj/), Google Brain) | [[Class Colab](https://colab.research.google.com/drive/1kp4phALWtcpLDeY5vQRrxBli6OqitlWJ?usp=sharing)][[Additional Colab](https://colab.sandbox.google.com/github/google/jax/blob/master/docs/notebooks/autodiff_cookbook.ipynb)] |                                                              |
| **Week 3** Wed, Sep 30  | ***Lecture*** [Few-shot learning via metric learning](https://cs330.stanford.edu/slides/cs330_nonparametric_2020.pdf) | **Due** **Homework 1**                                       | [P1: Matching Networks for One Shot Learning.](https://arxiv.org/abs/1606.04080) Vinyals et al. (2017)<br />[P2: Prototypical Networks for Few-shot Learning.](https://arxiv.org/abs/1703.05175) Snell et al. (2017) |
| **Week 4** Mon, Oct 5   | ***Lecture*** [Advanced meta-learning topics](https://cs330.stanford.edu/slides/cs330_advanced_meta_2020.pdf) | **Homework 2 out** [[PDF](https://cs330.stanford.edu/material/cs330_hw2.pdf)][[Colab Notebook](https://colab.research.google.com/drive/1zbt2A74kM10HvcAEgEy3fGgRSNyHZQKj?usp=sharing)] | [P1: Meta-Learning without Memorization.](https://arxiv.org/abs/1912.03820) Yin et al. (2020) |
| **Week 4** Wed, Oct 7   | ***Leacture*** [Bayesian meta-learning](https://cs330.stanford.edu/slides/cs330_bayesian_meta_learning_2020.pdf) |                                                              | [P1: Conditional Neural Processes.](https://arxiv.org/abs/1807.01613) Garnelo et al. (2018)<br />[P2: Meta-Learning Probabilistic Inference For Prediction.](https://arxiv.org/abs/1805.09921) Gordon et al. (2019) |
| **Week 5** Mon, Oct 12  | ***Lecture*** [Renforcement learning primer, multi-task RL, goal-conditioned RL ](https://cs330.stanford.edu/slides/cs330_rl_gc_mt_karol.pdf)(Karol Hausman) |                                                              | [P1: Hindsight Experience Replay.](https://arxiv.org/abs/1707.01495) Andrychowicz et al. (2018) |
| **Week 5** Wed, Oct 14  | ***Presentations*** Project Proposal Spotlight Presentations | **Due** **Project proposal**                                 |                                                              |
| **Week 5** Fri, Oct 16  |                                                              | **Due** **Homework 2** **Homework 3 out** [[PDF](https://cs330.stanford.edu/material/CS330_HW3_2020.pdf)][[Colab Notebook](https://colab.research.google.com/drive/1uYqzq4Ix91DD4QdElyrbC_If0TKDf_3t?usp=sharing)] |                                                              |
| **Week 6** Mon, Oct 19  | ***Lecture*** [Model-based RL for multi-task learning](https://cs330.stanford.edu/slides/cs330_mbrl_2020.pdf) |                                                              | [P1: Visual Foresight: Model-Based Deep Reinforcement Learning for Vision-Based Robotic Control.](https://arxiv.org/abs/1812.00568) Ebert et al. (2018)<br />[P2: Deep Dynamics Models for Learning Dexterous Manipulation.](https://arxiv.org/abs/1909.11652) Nagabandi et al. (2019) |
| **Week 6** Wed, Oct 21  | ***Lecture*** [Meta-RL: Adaptable models and policies](https://cs330.stanford.edu/slides/cs330_metarl1_2020.pdf) |                                                              |                                                              |
| **Week 7** Mon, Oct 26  | ***Lecture*** [Meta-RL: Learning to explore](https://cs330.stanford.edu/slides/cs330_metarl2_2020.pdf) | **Due** **Homework 3** **Optional Homework 4 out** [[PDF](https://cs330.stanford.edu/material/CS330_HW4.pdf)][[Colab Notebook](https://colab.research.google.com/drive/1VUsEXSj9cT_PDDH1JPqowQwyShFwbLsj?usp=sharing)] | [P1: VariBAD: A Very Good Method for Bayes-Adaptive Deep RL via Meta-Learning.](https://arxiv.org/abs/1910.08348) Zingraf et al. (2020) |
| **Week 7** Wed, Oct 28  | ***Lecture*** [A graphical model perspective on multi-task and meta-RL ](https://cs330.stanford.edu/slides/cs330_graphical_model_karol.pdf)(Karol Hausman) |                                                              | [P1: Reinforcement Learning and Control as Probabilistic Inference: Tutorial and Review.](https://arxiv.org/abs/1805.00909) Levine et al. (2018)<br />[P2: Efficient Off-Policy Meta-Reinforcement Learning via Probabilistic Context Variables.](https://arxiv.org/abs/1903.08254) Rakelly et al. (2019) |
| **Week 7** Thu, Oct 29  | ***TA Session*** [Pytorch tutorial](https://cs330.stanford.edu/slides/PyTorchTutorial.pdf) |                                                              |                                                              |
| **Week 8** Mon, Nov 2   | ***Lecture*** [Hierarchical RL and skill discovery ](https://cs330.stanford.edu/slides/cs330_skill_discovery_karol.pdf)(Karol Hausman) | **Due** **Project milestone**                                | [P1: Data-Efficient Hierarchical Reinforcement Learning.](https://arxiv.org/abs/1805.08296) Nachum et al. (2018)<br />[P2: Diversity is All You Need: Learning Skills without a Reward Function.](https://arxiv.org/abs/1802.06070) Eysenbach et al. (2018)<br />[P3: Dynamics-Aware Unsupervised Discovery of Skills.](https://arxiv.org/abs/1907.01657) Sharma et al. (2019) |
| **Week 8** Wed, Nov 4   | ***Lecture*** [Lifelong learning: problem statements, forward & backward transfer ](https://cs330.stanford.edu/slides/cs330_lifelonglearning_karol.pdf)(Karol Hausman) |                                                              |                                                              |
| **Week 9** Mon, Nov 9   | ***Guest Lecture*** [Meta-learning & cognitive science](https://cs330.stanford.edu/slides/CS330JaneWangLecture.pdf) ([Jane Wang](http://www.janexwang.com/), DeepMind) | **Due** **Optional Homework 4**                              | **Lecture is at 9 am PST**                                   |
| **Week 9** Wed, Nov 11  | ***Lecture*** [Frontiers and open problems](https://cs330.stanford.edu/slides/cs330_frontiers_2020.pdf) |                                                              |                                                              |
| **Week 10** Mon, Nov 16 | ***Presentations*** Final project presentations              | **Due** **Final presentations slides**                       |                                                              |
| **Week 10** Wed, Nov 18 | ***Presentations*** Final project presentations              |                                                              |                                                              |
| **Week 10** Fri, Nov 20 |                                                              | **Due** **Final project report**                             |                                                              |