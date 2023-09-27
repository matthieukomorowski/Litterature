# Litterature
A place to store relevant research papers and resources

[author: Matthieu Komorowski]

# GENERIC AI/ML IN HEALTHCARE

- All models are local: time to replace external validation with recurrent local validation [2023] https://arxiv.org/abs/2305.03219
- Operationalizing Machine Learning: An Interview Study [2022] https://arxiv.org/abs/2209.09125
- Do no harm: a roadmap for responsible machine learning for health care [2019] https://www.nature.com/articles/s41591-019-0548-6#Sec9

# RL

## Courses

- DeepMind x UCL RL Lecture Series [2021] https://www.youtube.com/watch?v=TCCjZe0y4Qc&list=PLqYmG7hTraZDVH599EItlEWsUOsJbAodm

## Textbooks

- Sutton & Barto 2nd Ed [2018] http://incompleteideas.net/book/the-book-2nd.html

## Learning optimal policies

- Learning-to-defer for sequential medical decision-making under uncertainty [2022] https://arxiv.org/abs/2109.06312
- Provable Benefits of Actor-Critic Methods for Offline Reinforcement Learning [2021] https://arxiv.org/abs/2108.08812
- Overcoming Model Bias for Robust Offline Deep Reinforcement Learning [2021] https://arxiv.org/abs/2008.05533
- The Difficulty of Passive Learning in Deep Reinforcement Learning [2021] https://arxiv.org/abs/2110.14020
- Is Deep Reinforcement Learning Ready for Practical Applications in Healthcare? A Sensitivity Analysis of Duel-DDQN for Hemodynamic Management in Sepsis Patients [2021] https://pubmed.ncbi.nlm.nih.gov/33936452/
- Deep reinforcement learning from human preferences [2017] https://arxiv.org/abs/1706.03741
- High Confidence Policy Improvement [2015] https://proceedings.mlr.press/v37/thomas15.html 

## State representation

- Learning Markov State Abstractions for Deep Reinforcement Learning [2021] https://arxiv.org/abs/2106.04379
- SOM-VAE: Interpretable Discrete Representation Learning on Time Series [2019] https://arxiv.org/abs/1806.02199

## OPE

- Reliable Off-Policy Learning for Dosage Combinations [2023] https://arxiv.org/abs/2305.19742
- Universal Off-Policy Evaluation [2021] https://arxiv.org/abs/2104.12820
- Off-Policy Deep Reinforcement Learning without Exploration [2018] https://arxiv.org/abs/1812.02900
- HCOPE [2015] https://ojs.aaai.org/index.php/AAAI/article/view/9541

## XRL (and XAI in general)

- Interpretable ML textbook [update 2023] https://christophm.github.io/interpretable-ml-book/
- Explainable Reinforcement Learning via Model Transforms [2022] https://arxiv.org/abs/2209.12006
- Counterfactual Explanations and Algorithmic Recourses for Machine Learning: A Review [2022] https://arxiv.org/abs/2010.10596
- Policy Optimization with Sparse Global Contrastive Explanations [2022] https://arxiv.org/abs/2207.06269
- Counterfactuals with Reinforcement Learning [2022] https://docs.seldon.io/projects/alibi/en/latest/methods/CFRL.html
- Model-agnostic and Scalable Counterfactual Explanations via Reinforcement Learning [2021] https://arxiv.org/abs/2106.02597
- XRL review [2020] https://towardsdatascience.com/xrl-explainable-reinforcement-learning-4cd065cdec9a
- Explainable Reinforcement Learning via Reward Decomposition [2019] https://finale.seas.harvard.edu/publications/explainable-reinforcement-learning-reward-decomposition

# RL in SEPSIS

- Towards more efficient and robust evaluation of sepsis treatment with deep reinforcement learning [2023] https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9979564/
- A value-based deep reinforcement learning model with human expertise in optimal treatment of sepsis [2023] https://www.nature.com/articles/s41746-023-00755-5
- The treatment of sepsis: an episodic memory-assisted deep reinforcement learning approach [2023] https://link.springer.com/article/10.1007/s10489-022-04099-7
- Delphic Offline Reinforcement Learning under Nonidentifiable Hidden Confounding [2023] https://arxiv.org/abs/2306.01157
- Uniformly Conservative Exploration in Reinforcement Learning [2023] https://proceedings.mlr.press/v206/xu23j.html
- Deep Offline Reinforcement Learning for Real-world Treatment Optimization Applications [2023] https://arxiv.org/abs/2302.07549
- A dosing strategy model of deep deterministic policy gradient algorithm for sepsis patients [2023] https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-023-02175-7
- Adversarial reinforcement learning for dynamic treatment regimes [2023] https://www.sciencedirect.com/science/article/pii/S1532046422002490
- Reinforcement Learning For Sepsis Treatment: A Continuous Action Space Solution [2022] https://proceedings.mlr.press/v182/huang22a.html
- Establishment and Implementation of Potential Fluid Therapy Balance Strategies for ICU Sepsis Patients Based on Reinforcement Learning [2022] https://pubmed.ncbi.nlm.nih.gov/35492326/
- A Conservative Q-Learning approach for handling distribution shift in sepsis treatment strategies [2022] https://arxiv.org/abs/2203.13884
- Leveraging Factored Action Spaces for Efficient Offline Reinforcement Learning in Healthcare [2022] https://proceedings.neurips.cc/paper_files/paper/2022/hash/dda7f9378a210c25e470e19304cce85d-Abstract-Conference.html
- Data-Efficient Pipeline for Offline Reinforcement Learning with Limited Data [2022] https://proceedings.neurips.cc/paper_files/paper/2022/hash/5ee7ed60a7e8169012224dec5fe0d27f-Abstract-Conference.html
- Federated Offline Reinforcement Learning [2022] https://arxiv.org/abs/2206.05581
- Unifying cardiovascular modelling with deep reinforcement learning for uncertainty aware control of sepsis treatment [2022] https://journals.plos.org/digitalhealth/article?id=10.1371/journal.pdig.0000012
- Superhuman performance on sepsis MIMIC-III data by distributional reinforcement learning [2022] https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0275358
- Establishment and Implementation of Potential Fluid Therapy Balance Strategies for ICU Sepsis Patients Based on Reinforcement Learning [2022] https://www.frontiersin.org/articles/10.3389/fmed.2022.766447/full
- Safe RL for sepsis treatment [2022] http://d-scholarship.pitt.edu/42914/
- Learning Optimal Treatment Strategies for Sepsis Using Offline Reinforcement Learning in Continuous Space [2022] https://link.springer.com/chapter/10.1007/978-3-031-20627-6_11
- Medical Dead-ends and Learning to Identify High-Risk States and Treatments [2021] https://proceedings.neurips.cc/paper/2021/hash/26405399c51ad7b13b504e74eb7c696c-Abstract.html
- Combining Model-Based and Model-Free Reinforcement Learning Policies for More Efficient Sepsis Treatment [2021] https://www.springerprofessional.de/en/combining-model-based-and-model-free-reinforcement-learning-poli/19877428
- Transatlantic transferability of a new reinforcement learning model for optimizing haemodynamic treatment for critically ill patients with sepsis [2021] https://pubmed.ncbi.nlm.nih.gov/33581824/
- Safety-driven design of machine learning for sepsis treatment [2021] https://www.sciencedirect.com/science/article/pii/S1532046421000915 
- Individualized fluid administration for critically ill patients with sepsis with an interpretable dynamic treatment regimen model [2020] https://www.nature.com/articles/s41598-020-74906-z
- Combining Reinforcement Learning with Supervised Learning for Sepsis Treatment [2020] https://dl.acm.org/doi/10.1145/3426020.3426077
- Deep Inverse Reinforcement Learning for Sepsis Treatment [2019] https://www.computer.org/csdl/proceedings-article/ichi/2019/08904645/1f8N9kBhTgY
- Improving Sepsis Treatment Strategies by Combining Deep and Kernel-Based Reinforcement Learning [2019] https://arxiv.org/abs/1901.04670

# RL in the ICU outside of sepsis

- Optimized glycemic control of type 2 diabetes with reinforcement learning: a proof-of-concept trial [2023] https://www.nature.com/articles/s41591-023-02552-9 
- Development of a Reinforcement Learning Algorithm to Optimize Corticosteroid Therapy in Critically Ill Patients with Sepsis [2023] https://www.mdpi.com/2077-0383/12/4/1513
- Clinical Knowledge-Guided Deep Reinforcement Learning for Sepsis Antibiotic Dosing Recommendations [2023] https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4481970
- Continuous action deep reinforcement learning for propofol dosing during general anesthesia [2022] https://pubmed.ncbi.nlm.nih.gov/34998516/
- Development and validation of a reinforcement learning algorithm to dynamically optimize mechanical ventilation in critical care [2021] https://pubmed.ncbi.nlm.nih.gov/33608661/
- Reinforcement learning for clinical decision support in critical care: comprehensive review [2020] https://www.jmir.org/2020/7/e18477/
- A Reinforcement Learning Approach to Weaning of Mechanical Ventilation in Intensive Care Units [2017] https://arxiv.org/abs/1704.06300


# SIMULATORS

- The Health Gym: synthetic health-related datasets for the development of reinforcement learning algorithms [2022] https://www.nature.com/articles/s41597-022-01784-7
- [Synthea] Simulation of a machine learning enabled learning health system for risk prediction using synthetic patient data [2022] https://www.nature.com/articles/s41598-022-23011-4
- Towards Effective Patient Simulators [2021] https://www.frontiersin.org/articles/10.3389/frai.2021.798659/full
- [GYMIC] Sepsis World Model: A MIMIC-based OpenAI Gym "World Model" Simulator for Sepsis Treatment [2019] https://arxiv.org/abs/1912.07127 + https://github.com/akiani/rlsepsis234
- World Models [2018] https://arxiv.org/abs/1803.10122

# FOUNDATION MODELS

- Towards Generalist Biomedical AI [2023] https://arxiv.org/abs/2307.14334
- On the Opportunities and Risks of Foundation Models [2021] https://arxiv.org/abs/2108.07258

# BENCHMARK DATASETS

- HiRID-ICU-Benchmark -- A Comprehensive Machine Learning Benchmark on High-resolution ICU Data [2021] https://arxiv.org/abs/2111.08536

# LIBRARIES

- ID3QNE: A value-based deep reinforcement learning model with human expertise in optimal treatment of sepsis [2023] https://github.com/CaryLi666/ID3QNE-algorithm
- d3rlpy: An Offline Deep Reinforcement Learning Library [2021] https://arxiv.org/abs/2111.03788
- GYMIC: An OpenAI Gym Environment for Simulating Sepsis Treatment for ICU Patients [2019] https://github.com/akiani/gym-sepsis

# SAFETY

- Preventing undesirable behavior of intelligent machines [2019] https://www.science.org/doi/10.1126/science.aag3311
- Artificial intelligence, bias and clinical safety [2018] https://qualitysafety.bmj.com/content/28/3/231

# MEDICAL IMAGING

- CXR Foundation [2022] https://ai.googleblog.com/2022/07/simplified-transfer-learning-for-chest.html

# REGULATIONS / GUIDELINES

- Crafting an intended purpose in the context of Software as a Medical Device (SaMD) [2023] https://www.gov.uk/government/publications/crafting-an-intended-purpose-in-the-context-of-software-as-a-medical-device-samd
- Regulatory Horizons Council: The regulation of Artificial Intelligence as a Medical Device [2022] https://www.gov.uk/government/publications/regulatory-horizons-council-the-regulation-of-artificial-intelligence-as-a-medical-device
- (Goldacre review) Better, broader, safer: using health data for research and analysis [2022] https://www.gov.uk/government/publications/better-broader-safer-using-health-data-for-research-and-analysis
- FDA/Health Canada/MHRA Good Machine Learning Practice for Medical Device Development: Guiding Principles [2021] https://www.gov.uk/government/publications/good-machine-learning-practice-for-medical-device-development-guiding-principles
- Guidance: A guide to good practice for digital and data-driven health technologies [2021] https://www.gov.uk/government/publications/code-of-conduct-for-data-driven-health-and-care-technology/initial-code-of-conduct-for-data-driven-health-and-care-technology#clinical-safety


