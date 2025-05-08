---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD candidate in the Department of Psychology at UC Berkeley, supervised by Rich Ivry. I am broadly interested in the flexibility of human learning. I build cognitive and neural models to understand how the brain supports multiple learning processes and how these systems interact to enable adaptive behavior. My early PhD work focused on how the sensorimotor system operates under uncertainty from various sources to support efficient adaptation. I am now extending this work to investigate how we plan movements and make decisions when interacting with other agents under uncertainty. I am also interested in the function of the cerebellum, a brain region historically associated with motor control and learning. I develop models to explore the role of the cerebellum in broader cognitive domains such as timing, intuitive physics, and theory of mind. Here you can find the summary of my current projects.


Project 1: How the brain adapts to the uncertainties in the environment
======
Our motor system needs to due with an enormous amount of noise and uncertainties. For example, our visual and proprioceptive inputs are imperfect, and the internal state of the body and the external environment are changing all the time. It is impressive that the motor system can perform accurate movements and generalize skills regardless of those uncertainties, while it is a big challenge for the robotic system to maintain a stable performance in noisy environments. 

We examine how the motor system adapts to the uncertainties in two different systems, the implicit recalibration system and the action selection system. The recalibration system corrects for small errors in an automatic way and [does not require attentional resource](https://pubmed.ncbi.nlm.nih.gov/39282258/), while the action selection system is more flexible and can adjust behavior to meet specific task demands. 

Our recent work suggests that implicit recalibration is [insensitive to noise of the states](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1011951). However, this system showed some unique effects due to the uncertainty in the context. For example, learning is faster but lasts shorter when the environment is more volatile; reversal learning is slower than the original learning; relearning is slower rather than faster when being re-exposed to the same perturbation for the second time. We proposed a [Cerebellar Population Coding model](https://pubmed.ncbi.nlm.nih.gov/37461557/) which provides a unified explanation to the contextual effects in implicit recalibration without referring to any contextual inference process. This model is composed of a simple two-layer network corresponding to the cerebellar cortex and deep cerebellar nuclei, respectively, and the contextual effects are emergent phenomena from the population activation within the model. 

We examine how the action selection system responds to uncertainty with a novel air-hockey game, which requires motor control in multiple dimensions while compensating for the wind that changes across time. The action selection showed a close optimal modulation where noise and vitality of the state have opposite effects on the learning rate. Interestingly, participants perform significantly worse in incorporating the uncertainty when playing a non-motor version of the game.

Besides the uncertainties in the physical world, another key source of uncertainty is from the other agents. Incorporating this front of uncertainties requires the ability of theory of mind (ToM). However, knowing others' minds is HARD. My current studies focus on understanding how we make decisions with the uncertainties of others' intentions.

 
Project 2: Target-specific and context-dependent biases in movement reveal fundamental computations underlying motor control
======
Biases in movement offer a window to probe the underlying control mechanisms in motor control. Here we focus on biases at three time scales: 1. stable target-specific bias; 2. bias induced by a prior distribution; 3. bias induced by the last movement. We provide novel models to explain biases at all three levels.

From the [target-specific bias](https://elifesciences.org/reviewed-preprints/100715), we showed that its pattern largely reflects [a mismatch](https://www.nature.com/articles/s41598-020-76220-0) between the proprioceptive space that encodes the hand position and the visual space. Modeling results suggest that participants perceived the target in the visual space and transferred it into a proprioceptive space, and they encoded the motor plan. 

Prior distribution can also induce a central tendency in the reaching. However, contradict to the prevailing belief, we found this bias to be largely non-Bayesian. In particular, while the motor bias is modulated by the specific prior distribution, the motor variance does not. Current work is focusing on understanding the nature of this bias.

We have also identified a novel [trial-by-trial bias](https://pubmed.ncbi.nlm.nih.gov/39416082/) in reaching, where the current movement is biased away from the previous movement. This bias pattern and how it is modulated across various situations suggest an efficient coding mechanism for motor planning. We are now examining how the interaction between the trial-by-trial repulsive bias and prior-induced central tendency reveals how the motor system adapts to the statistical properties of the motor goals. 


Project 3: How we learn new motor skills
======
The primary distinction in motor learning is the difference between an adaptation process, which modulates a well-trained behavior to compensate for small perturbations, and a de novo skill learning process, which creates a new action-outcome map from scratch. Most of the current research on motor learning focuses on the simple adaptation process, with the skill learning process largely unknown. In particular, while numerous computational models of different levels have been proposed to quantitatively predict the adaptation process, few models have been developed for skill learning.  

One of my key research interests is to understand the computational mechanism in motor skill learning. To begin with, we examined a long-standing paradox in the motor learning literature: Patients with retrograde amnesia (e.g., [HM](https://en.wikipedia.org/wiki/Henry_Molaison)) showed no impairment in learning the mirror-reversal, however, recent studies consistently showed that [implicit system is supringly rigid](https://journals.physiology.org/doi/pdf/10.1152/jn.00304.2021) and continuous operates improperly even after a week of training. In our recent study, we addressed this question by training participants for a month with different novel sensory motor maps. We illustrate a series of results that contradict the common beliefs of the field: 1. Implicit adaptation can be flipped to match the new sensory motor maps. 2. There is almost no interference between the adaptation in the new and old maps. 3. Center-out reaching task is sufficient to generate this change, while the more "skill-like" task (such as the continuous tracing task) is less efficient. 4. We observed similar changes in implicit adaptation for the mirror-reversal and the rotation task, while the latter is usually considered as a more "adaptation-like" task.

We are building neural network models to explain the different roles of the motor cortex and cerebellum in those tasks.


Project 4: The role of the cerebellum in cognition
======
While the cerebellum has been historically regarded as a motor region, emerging research using patients and animal models has suggested the role of the cerebellum in mutiple cognitive domains such as reward-based learning and language. However, how the cerebellum supports those cognitive functions is poorly known at this stage. I applied neurophysiology studies on cerebellar ataxia patients and healthy controls to understand its function in [timing](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1011116), intuitive physics, and theory of mind. 





