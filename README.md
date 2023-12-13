Here is a landing page to showcase my work that I am currently at liberty to distribute. Upon submission to conferences or journals with double-blind reviews, I will have to temporarily delete these papers.

# Specialized Neural Network Pruning for Boolean Abstractions
## Abstract
The inherent intricate topology of a neural network (NN) decreases our understanding of its function and
purpose. Neural network abstraction and analysis techniques are designed to increase the comprehensibility
of these computing structures. To achieve a more concise and interpretable representation of a NN as a
Boolean graph (BG), we introduce the Neural Constantness Heuristic (NCH), Neural Constant Propagation
(NCP), shared logic, the Neural Real-Valued Constantness Heuristic (NRVCH), and negligible neural nodes.
These techniques reduce a neural layer’s input space and the number of nodes for a problem in NP (reducing
its complexity). Additionally, we contrast two parsing methods that translate NNs to BGs: reverse traversal
(N) and forward traversal (F). For most use cases, the combination of NRVCH, NCP, and N is the best
choice

# Parallel Time Networks
## Abstract 
Time series forecasting remains a complex challenge, especially in intricate domains such as chaotic systems. This paper introduces ``Probabilistic Parallel Time Networks", a novel deep neural network hypermodel designed to generalize across diverse domains in complex, probabilistic time series forecasting. The learned multi-modal model takes three distinct inputs: static data, agent history, and forecasts, and subsequently predict probability distributions over time. This innovative approach offers a more interpretable and unified framework for complex forecasting tasks. The utilization of a genetic hyperparameter optimization algorithm intertwined with the Differentiable Architecture Search (DARTS) neural architecture search, and the careful minimization of the neural architecture space, ensures a tractable and efficient solution. Through empirical studies in weather forecasting for microclimates and the chaotic Lorenz system, we demonstrate the model's applicability, robustness, and potential. The Probabilistic Parallel Time Network model offers a promising advancement in time series forecasting, with potential implications for research and practical applications in diverse areas, including healthcare, finance, and environmental sciences.

## Current work
I have implemented Google's TiDE model as another baseline and will include these results soon.

# Multi-Objective Synthetic Data to Reduce Sample Selection Bias in Clinical Data
## Abstract
In the era of data-driven healthcare, identifying, quantifying, and mitigating bias in machine learning is of paramount importance. The impact of fair machine learning is particularly significant when predictions are applied in a clinical setting, where biased predictions can lead to unequal healthcare outcomes. In this paper, we consider the area of biomedical informatics and examine existing bias metrics and introduce a new metric to analyze bias in a smart home dataset. We investigate bias that may occur along sensitive attributes and examine its impact on the machine learning task of activity recognition from the collected data. In a novel approach to bias mitigation, we propose the use of multi-objective synthetic data to mitigate sample bias by enhancing data diversity. We validate these methods using data collected for older adults living in smart homes who are managing multiple chronic health conditions, highlighting the potential of our approach to improve health predictions and outcomes.


# Advanced Techniques for Imputing, Forecasting, and Synthesizing Multivariate Meteorlogical Data
## Abstract
This study introduces two novel deep learning-based neural frameworks: FORESEER and WeatherGen, designed to address the critical need for accurate weather prediction in agricultural microclimates. Farmers often face significant challenges due to biases in public forecasts that do not account for their unique microclimates, leading to potential losses in crop yield and quality. FORESEER serves as a novel network available to either impute or forecast meteorological data. WeatherGen, a multi-agent Generative Adversarial Network (GAN), generates representative synthetic weather data, derived from extensive data collected from multiple farms across the western United States. The synthetic dataset, created by WeatherGen and made publicly available, has demonstrated promising results in zero-shot trials, indicating its potential for real-world application. These innovative neural frameworks aim to refine and predict weather data in areas of interest, empowering farmers to make informed decisions that directly enhance the quality and quantity of their produce.

Please see [https://github.com/jarrenbr/SIAM24NeuralArchitectures](https://github.com/jarrenbr/SIAM24NeuralArchitectures) for the paper and neural architecture code. This paper is under review for SIAM-DM 2024.

# Master's Thesis: Comprehending Neural Networks via Translation to And-Inverter Graphs
## Abstract
This thesis gives a novel algorithm N that helps users understand neural networks (NNs) via abstraction to and-inverter graphs (AIGs).
I find that AIGs are more comprehensible than NNs due to their conciseness.
For small NNs, N consistently creates AIG abstractions with perfect accuracy. However, translating large NNs to AIGs introduces the memorization
versus generalization problem. Memorization elicits noise and reduces the
comprehensibility of the AIG. To improve generalization and comprehensibility, I consider only the most important weights (using a maximum depth
for the binary decision tree B). Furthermore, I survey the accuracy of the ensemble method for further noise mitigation. This work successfully creates a
single AIG that is a concise, generalized, and accurate NN abstraction. However, the AIGs are not always as comprehensible as one would like. Future
work can further investigate noise reduction techniques such as the ensemble
method.

Please see [https://github.com/jarrenbr/ThesisPublic](https://github.com/jarrenbr/ThesisPublic) for more information.


# Other Work
I have a few other projects that are under blind review or are not yet ready for public viewing, including:

- Distribution shift of binary confusion matrices and a solution (under review)
- Probabilistic object counting using deep learning (in progress)
- Creating attack/defense scores for zero-sum games such as chess (in progress)
- Considering time-series metrics and transfer learning (in progress)
