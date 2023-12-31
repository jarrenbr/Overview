Welcome to the central repository of my academic and research endeavors. I am Jarren Briscoe, a passionate PhD candidate specializing in Artificial Intelligence and Machine Learning at Washington State University. My research journey encapsulates a diverse range of subjects within AI, focusing predominantly on neural networks, synthetic data generation, and bias mitigation in machine learning models.

# Research Highlights

## Probabilistic Parallel Time Networks (PTNs)
In my work on Probabilistic Parallel Time Networks, I've developed an advanced hypermodel for complex time series forecasting. This research encompasses probabilistic forecasting across various domains, notably in chaotic systems and microclimates. By integrating a genetic hyperparameter optimization algorithm with Differentiable Architecture Search (DARTS), I've achieved a model that is not only tractable but also efficient and scalable. The PTNs are adept at handling multi-modal inputs, providing insightful probabilistic forecasts that surpass traditional deterministic models. This work has broad implications, ranging from healthcare and finance to environmental sciences​​​​.

## Fair Distribution Index
Another significant contribution is the Fair Distribution Index project. In this research, I address the challenge of distribution shift in widely-used classification metrics. By proposing innovative bias metrics grounded in legal precedents, I have demonstrated how to attain empirical robustness in machine learning models. This work contributes immensely to the field of explainable AI, ensuring fairness and transparency in AI algorithms.

## Multi-Objective Synthetic Data Generation
I have also been involved in creating a novel multi-objective synthetic data generator for clinical data. This project focuses on mitigating bias against underrepresented classes in healthcare datasets, enhancing the reliability and ethical standards of AI applications in medicine.

# Abstracts
## Specialized Neural Network Pruning for Boolean Abstractions
The inherent intricate topology of a neural network (NN) decreases our understanding of its function and
purpose. Neural network abstraction and analysis techniques are designed to increase the comprehensibility
of these computing structures. To achieve a more concise and interpretable representation of a NN as a
Boolean graph (BG), we introduce the Neural Constantness Heuristic (NCH), Neural Constant Propagation
(NCP), shared logic, the Neural Real-Valued Constantness Heuristic (NRVCH), and negligible neural nodes.
These techniques reduce a neural layer’s input space and the number of nodes for a problem in NP (reducing
its complexity). Additionally, we contrast two parsing methods that translate NNs to BGs: reverse traversal
(N) and forward traversal (F). For most use cases, the combination of NRVCH, NCP, and N is the best
choice.

Published in KEOD 2021.

## Parallel Time Networks
Time series forecasting remains a complex challenge, especially in intricate domains such as chaotic systems. This paper introduces ``Probabilistic Parallel Time Networks", a novel deep neural network hypermodel designed to generalize across diverse domains in complex, probabilistic time series forecasting. The learned multi-modal model takes three distinct inputs: static data, agent history, and forecasts, and subsequently predict probability distributions over time. This innovative approach offers a more interpretable and unified framework for complex forecasting tasks. The utilization of a genetic hyperparameter optimization algorithm intertwined with the Differentiable Architecture Search (DARTS) neural architecture search, and the careful minimization of the neural architecture space, ensures a tractable and efficient solution. Through empirical studies in weather forecasting for microclimates and the chaotic Lorenz system, we demonstrate the model's applicability, robustness, and potential. The Probabilistic Parallel Time Network model offers a promising advancement in time series forecasting, with potential implications for research and practical applications in diverse areas, including healthcare, finance, and environmental sciences.

### Current work
I have implemented Google's TiDE model as another baseline and will include these results soon.

## Multi-Objective Synthetic Data to Reduce Sample Selection Bias in Clinical Data
In the era of data-driven healthcare, identifying, quantifying, and mitigating bias in machine learning is of paramount importance. The impact of fair machine learning is particularly significant when predictions are applied in a clinical setting, where biased predictions can lead to unequal healthcare outcomes. In this paper, we consider the area of biomedical informatics and examine existing bias metrics and introduce a new metric to analyze bias in a smart home dataset. We investigate bias that may occur along sensitive attributes and examine its impact on the machine learning task of activity recognition from the collected data. In a novel approach to bias mitigation, we propose the use of multi-objective synthetic data to mitigate sample bias by enhancing data diversity. We validate these methods using data collected for older adults living in smart homes who are managing multiple chronic health conditions, highlighting the potential of our approach to improve health predictions and outcomes.


## Advanced Techniques for Imputing, Forecasting, and Synthesizing Multivariate Meteorlogical Data
This study introduces two novel deep learning-based neural frameworks: FORESEER and WeatherGen, designed to address the critical need for accurate weather prediction in agricultural microclimates. Farmers often face significant challenges due to biases in public forecasts that do not account for their unique microclimates, leading to potential losses in crop yield and quality. FORESEER serves as a novel network available to either impute or forecast meteorological data. WeatherGen, a multi-agent Generative Adversarial Network (GAN), generates representative synthetic weather data, derived from extensive data collected from multiple farms across the western United States. The synthetic dataset, created by WeatherGen and made publicly available, has demonstrated promising results in zero-shot trials, indicating its potential for real-world application. These innovative neural frameworks aim to refine and predict weather data in areas of interest, empowering farmers to make informed decisions that directly enhance the quality and quantity of their produce.

Please see [https://github.com/jarrenbr/MicroclimateForecasting](https://github.com/jarrenbr/MicroclimateForecasting) for the paper and neural architecture code.

## Master's Thesis: Comprehending Neural Networks via Translation to And-Inverter Graphs
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

## Indicators for Transfer Learning: Similarity of Inconsistently Sampled Time Series
The proliferation of sensors has brought about the need to reexamine our existing analytic practices for time series. Sensors naturally produce time-oriented data that defy many traditional assumptions of statistical modeling. In this project, we examine sensor data collected from 15 different smart homes. We investigate seven time series similarity measures and assess their strength in predicting the transfer learning of activities across pairs of homes. Our results indicate that several of the measures examined have significant predictive power. Moving forward, additional work can be done to investigate the use of alternative network structures for training/testing and to further examine the literature for recently proposed similarity measures.

Please see [https://github.com/SerenaPeterson/CASAS-Project](https://github.com/SerenaPeterson/CASAS-Project) for the code. I'm leading Serena Peterson, a PhD student, in this project.

## Other Work
I have a few other projects that are under blind review or are not yet ready for public viewing, including:

- Distribution shift of binary confusion matrices and a solution (under review)
- Probabilistic object counting using deep learning (in progress)
- Creating attack/defense scores for zero-sum games such as chess (in progress)

# Engage with My Work
I warmly welcome collaboration, discussion, and feedback. Feel free to open an issue for discussions or suggestions related to my research. For those interested in contributing or collaborating, please email me at jarren.briscoe (at) wsu.edu.

Thank you for visiting my research hub, and I hope my work inspires and contributes to further advancements in the AI and ML community.
