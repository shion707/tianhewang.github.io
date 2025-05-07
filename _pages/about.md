---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD candidate in the Department of Psychology at UC Berkeley, supervised by Rich Ivry. I am broadly interested in the flexibility of human learning. I build cognitive and neural models to understand how the brain supports multiple learning processes and how these systems interact to enable adaptive behavior. My early PhD work focused on how the sensorimotor system operates under uncertainty from various sources to support efficient adaptation. I am now extending this work to investigate how we plan movements and make decisions when interacting with other agents under uncertainty. I am also interested in the function of the cerebellum, a brain region historically associated with motor control and learning. I develop models to explore the role of the cerebellum in broader cognitive domains such as timing, intuitive physics, and theory of mind. Here you can find the summary of my projects.


Project 1: How the brain adapts to the uncertainties in the environment
======
Our motor system needs to due with an enormous amount of noise and uncertainties. For example, our visual and proprioceptive inputs are imperfect, and the internal state of the body and the external environment are changing all the time. It is quite impressive that the nervous system can perform accurate and flxible motor behavior regardless of those uncertainties and noises and apply the skills we learned across contexts, while it is a big challenge for the robotic system to maintain a stable performance across environments. 

We examine how the motor system adapts to the uncertainties in two different systems, the implicit recalibration system and the action selection system. The recalibration system corrects for small errors in an automatic way and [does not require attentional resource](https://pubmed.ncbi.nlm.nih.gov/39282258/), while the action selection system is more flexible and can adjust behavior to meet specific task demands. 

Our recent work suggests that implicit recalibration is [insensitive to noise of the states](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1011951). However, this system showed some unique effects due to the uncertainty in the context. For example, learning is faster but lasts shorter when the environment is more volatile; reversal learning is slower than the original learning; relearning is slower rather than faster when being re-exposed to the same perturbation for the second time. We proposed a [Cerebellar Population Coding model](https://pubmed.ncbi.nlm.nih.gov/37461557/) which provides a unified explanation to the contextual effects in implicit recalibration without referring to any contextual inference process. This model is composed of a simple two-layer network corresponding to the cerebellar cortex and deep cerebellar nuclei, respectively, and the contextual effects are emergent phenomena from the population activation within the model. 

We examine how the action selection system responds to uncertainty with a novel air-hockey game, which requires motor control in multiple dimensions while compensating for the wind that changes across time. The action selection showed a close optimal modulation where noise and vitality of the state have opposite effects on the learning rate. Interestingly, participants perform significantly worse in incorporating the uncertainty when playing a non-motor version of the game.

Besides the uncertainty of the physical world, another key source of uncertainty is from the other agents. Incorporating this front of uncertainties requires the ability of theory of mind (ToM). However, knowing others' minds is HARD. My current studies focus on understanding how we make decisions with the uncertainties of others' intentions.

 
Project 2: Target-specific and context-dependent biases in movement reveal fundamental computations underlying motor control
======
Biases in movement offer a window to probe the underlying control mechanisms in motor control. Here we focus on biases at three time scales: 1. stable target-specific bias; 2. bias induced by a prior distribution; 3. bias induced by the last movement. We provide novel models to explain biases at all three levels.

From the [target-specific bias](https://elifesciences.org/reviewed-preprints/100715), we showed that its pattern largely reflects a mismatch between the proprioceptive space that encodes the hand position and the visual space. Modeling results suggest that participants perceived the target in the visual space and transferred it into a proprioceptive space, and they encoded the motor plan. 

Prior distribution can also induce a central tendency in the reaching. However, contradict to the prevailing belief, we found this bias to be largely non-Bayesian. In particular, while the motor bias is modulated by the specific prior distribution, the motor variance does not. Current work is focusing on understanding the nature of this bias.

We also identify a novel [trial-by-trial bias](https://pubmed.ncbi.nlm.nih.gov/39416082/) in reaching, where the current movement is biased away from the previous movement. This bias pattern and how it is modulated across various situations suggest an efficient coding mechanism for motor planning. We are now examining how the interaction between the trial-by-trial repulsive bias and prior-induced central tendency reveals how the motor system adapts to the statistical properties of the motor goals. 


Project 1: Target specific and context-dependent biases in movement reveal fundamental computations underlying motor control
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pubmed.ncbi.nlm.nih.gov/39416082/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).
