---
title: "Material Geometry Design Using Machine Learning and Optimization"
excerpt: "Use VGG to predict mechanical properties from their images, and use Bayesian model to optimize the GAN that can generate material images.<br/><img src='/images/vgg_performance.png'>"
collection: portfolio
---

Metamaterials with highly human-influenced microstructure may exhibit unconventional physical properties, such as
negative index of refraction (NIR), negative Poisson’s ratio (NPR), negative thermal expansion coefficient (NTEC), or
deformation-mode couplings. The couplings between tension/compression and torsion or bending are intrinsically due to
the intertwined internal degrees of freedom at each material point. Traditionally, the design of metamaterials relies on
human experiences, such as the Edisonian methodology, based on the concept of trial and error. By using deep convolution
neural networks, such as VGG, we have developed a methodology to create metamaterials with desired chiral
microstructures, as shown in the flowchart below. Data consisting of microstructural image information and effective
mechanical properties are prepared via finite element calculations. Generation of initial chiral samples for DNN training is
based on a Markov chain process. Our DNN can be successfully trained to correlate the chiral microstructures and their
effective mechanical properties. Creating samples via generative adversarial networks (GAN) or other strategies is
discussed. 
<br/><img src='/images/DNN_Material_Design_Flow.png'>