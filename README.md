# XAI - Explainable AI

This document collects the key resources in Explainable AI, including tutorials, workshops, books, course & lectures, survey papers, projects, and major research directions. There is no way it is complete, it will be continuously updated with new and relevant resources. You are welcome to suggest any valueable resources. 

## A one-page overview

### Clarification
Explainable vs. Interpretable \
In most cases, they are used interchangeable. In a number of situations, explainability means explaining for what have already happened. [3] defined: Interpretability refers to a passive characteristic of a model referring to the level at which a given model makes sense to a human observe vs. Explainability is viewed as an active characteristic of a model, denoting any action or procedure take by a model with the intent of clarifying or detailing its internal functions. 

XAI vs. Responsible AI\



### WHAT: definition of Explainable AI
DARPA XAI project by D. Gunning [5]:
“XAI will create a suite of machine learning techniques that enables human users to understand, appropriately trust, and effectively manage the emerging generation of artificially intelligent partners”

Explainable AI survey paper [3]:
" Given an audience, an explainable Artificial Intelligence is one that produces details or reasons to make its functioning clear or easy to understand."

### WHY
- Explainability is one of the main barriers AI is facing nowadays in regards to its practical implementation.
- Even though AI AI has helped research across the world with the task of inferring relations that were far beyond the human cognitive reach. However, science and society are far from being concerned just by performance.
- The search for understanding is what opens the door for further model improvement and its practical utility.
 
### WHAT FOR?
| XAI goals        | Main target audience |
|------------------|-----------------------------------------------------------------------------------|
|Trustworthiness   | Domain experts, users of the model affected by decisions|
|Causality         | Domain experts, managers and executive board members, regulatory entities/agencies|
|Transferability   | Domain experts, data scientists|
|Informativeness   | All|
|Confidence        | Domain experts, developers, managers, regulatory, entities/agencies|
|Fairness          | Users affected by model decisions, regulatory entities/agencies|
|Accessibility     | Product owners, managers, users affected by model decisions|
|Interactivity     | Domain experts, users affected by model decisions|
|Privacy awareness | Users affected by model decisions, regulatory entities/agencies|


### HOW

Two categories:
- Interpretable (also named transparent) Models: transparent models convey some degree of interpretability by themselves. Models belonging to this category can be also approached in terms of the domain in which they are interpretable, namely, algorithmic transparency, decomposability and simulatability. 

![Transparent levels: (a) simulatability; (b) decomposability; (c) algorithmic transparency. [3]](https://github.com/thanhkien84/awesome-ExplainableAI/blob/master/Transparency.png)

- Model interpretability techniques (also named post-hoc explainability): post-hoc explainability targets models that are not readily interpretable by design by resorting to diverse means to enhance their interpretability, such as text explanations, visual explanations, local explanations, explanations by example, explanations by simplification and feature relevance explanations techniques

![Post-hoc explainability approaches [3]](https://github.com/thanhkien84/awesome-ExplainableAI/blob/master/PosthocExplainability.png)

### XAI Taxonomy

![Taxonomy of XAI [3]](https://github.com/thanhkien84/awesome-ExplainableAI/blob/master/XAItaxonomy.png)

#### Transparent ML Models
- Linear/Logistic Regression
- Decision Trees
- K-Nearest Neighbors
- Rule-based Learning
- General Additive Models
- Bayesian Models

#### Post-hoc explainability
- Model-agnostic Techniques: Model-agnostic techniques for post-hoc explainability are designed to be plugged to any model with the intent of extracting some information from its prediction procedure. 
-- Explanation by simplification
-- Feature relevance explanation
-- LocalExplanations
-- Visual explanation

- Model-specific in Shallow ML Models
-- Tree Ensembles, Random Forests and Multiple Classifier Systems
-- SVM

- Model-specific in Deep Learning
-- Multi-layer Neural Networks
-- Convolutional Neural Networks (CNNs)
-- Recurrent Neural Networks (RNNs)
-- Hybrid Transparent and Black-box Methods 
-- Alternative Taxonomy of Post-hoc Explainability Techniques for Deep Learning

----------------------------------------------------------------------------------------------------------------




### 1. Tutorials and Workshops
##### AAAI 2020 - Explainable AI: Foundations, Industrial Applications, Practical Challenges, and Lessons Learned
Presenters: F. Lecue, K. Gade, S. Cem Geyik, K. Kenthapadi, V. Mithal, A. Taly, R. Guidotti, P. Minervini\
[Site](https://xaitutorial2020.github.io) - [Slides](https://xaitutorial2020.github.io/raw/master/slides/aaai_2020_xai_tutorial.pdf)

##### ACM FAT 2020, KDD 2019 - Explainable AI in Industry
Presenters: K. Gade, S. Cem Geyik, K. Kenthapadi, V. Mithal, A. Taly\
[FAT Site](https://sites.google.com/view/fat20-explainable-ai-tutorial) - [FAT Slides](https://www.slideshare.net/KrishnaramKenthapadi/explainable-ai-in-industry-fat-2020-tutorial) - [FAT Youtube](https://www.youtube.com/watch?v=lcN-XJSsd-c)\
[KDD Site](https://sites.google.com/view/kdd19-explainable-ai-tutorial) - [KDD Slides](https://www.slideshare.net/KrishnaramKenthapadi/explainable-ai-in-industry-kdd-2019-tutorial) - [KDD Youtube](https://www.youtube.com/playlist?list=PLewjn-vrZ7d3x0M4Uu_57oaJPRXkiS221)

##### ICCV 2019, CVPR 2018 - Tutorial on Interpretable Machine Learning for Computer Vision
Presenters: B. Zhou, A. Vedaldi, A. Binder, A. L. Yuille\
ICCV: [Site](https://interpretablevision.github.io) - [Slides1](https://interpretablevision.github.io/slide/iccv19_vedaldi_slide.pdf) - [ Slides2](https://interpretablevision.github.io/slide/iccv19_zhou_slide.pdf) - [ Slides3](https://interpretablevision.github.io/slide/iccv19_yuille_slide.pdf) - [ Slides4](https://interpretablevision.github.io/slide/iccv19_binder_slide.pdf)\
CVPR: [Site](https://interpretablevision.github.io/index_cvpr2018.html) - [ Slides1](http://deeplearning.csail.mit.edu/slide_cvpr2018/been_cvpr18tutorial.pdf) [Youtube1](https://www.youtube.com/watch?v=MgawSHnYQGw) - [ Slide2](http://deeplearning.csail.mit.edu/slide_cvpr2018/laurens_cvpr18tutorial.pdf) [Youtube2](https://youtu.be/MgawSHnYQGw?t=2589) - [ Slides3](http://deeplearning.csail.mit.edu/slide_cvpr2018/bolei_cvpr18tutorial.pdf) [Youtube3](https://www.youtube.com/watch?v=1aSS5GEH58U) - [ Slides4](http://deeplearning.csail.mit.edu/slide_cvpr2018/vedaldi_cvpr18tutorial.pdf) [Youtube4](https://youtu.be/1aSS5GEH58U?t=2860)

##### CVPR 2019 Workshop on Explainable AI
Presenters: S.C. Zhu, K.R. Muller, K. Saenko, D. Parikh & D. Batra, B. Kim\
[Site](https://explainai.net) - [Slide1](https://explainai.net/src/Workshop%20Talk%20XAI.pdf) [Slide2](https://www.cc.gatech.edu/~dbatra/talks/2019-06-15_dhruv_batra_xai.pptx) [Slide3](https://explainai.net/src/Talk30_2019Summer_PDF_small.pdf)

### 2. Courses & lectures
##### Harvard COMPSCI 282BR: Topics in Machine Learning: Interpretability and Explainability [Site](https://canvas.harvard.edu/courses/68154) - [Slides](https://canvas.harvard.edu/courses/68154/files/folder/Lecture%20Slides)

##### Human-centered AI Lab seminar on Explainable AI [Site](https://human-centered.ai/seminar-explainable-ai-2019/) - [Github](https://github.com/human-centered-ai-lab/cla-Seminar-explainable-AI-2019)


### 3. Survey papers

#### Introductory
##### [1] [McKinsey - Leading your organization to responsible AI](https://www.mckinsey.com/business-functions/mckinsey-analytics/our-insights/leading-your-organization-to-responsible-ai)

##### [2] [The Royal Society - Explainable AI: the basics](https://royalsociety.org/-/media/policy/projects/explainable-ai/AI-and-interpretability-policy-briefing.pdf)

#### Technical
##### [3] [Explainable Artificial Intelligence (XAI): Concepts, Taxonomies, Opportunities and Challenges toward Responsible AI](https://www.sciencedirect.com/science/article/pii/S1566253519308103), Information Fusion, Dec 2019

##### [4] [The Emerging Landscape of Explainable AI Planning and Decision Making](https://arxiv.org/abs/2002.11697)


### 4. Books
##### Interpretable Machine Learning [Link](https://christophm.github.io/interpretable-ml-book/)


### 5. Projects
##### [5] DARPA Explainable Artificial Intelligence (XAI) 2017-2021 [Site](https://www.darpa.mil/program/explainable-artificial-intelligence) - [Project Description](https://www.darpa.mil/attachments/DARPA-BAA-16-53.pdf) - [Slides](https://asd.gsfc.nasa.gov/conferences/ai/program/003-XAIforNASA.pdf)


### 6. Key directions
### Deep explanation 

### Interpretable Models

### Model Induction


### 7. Available services
##### Google Explainable AI services [Link](https://towardsdatascience.com/googles-new-explainable-ai-xai-service-83a7bc823773)







