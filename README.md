# Federated-Learning-Conferences-Journals
Conferences and Journals Collection for Federated Learning from 2019 to 2021. For jounals, the impact factors on year 2019 are provided. For conferences, the number of accepted papers are provided.

## Conferences
- A-Level

|  Conference   | 2019 | 2020 | 2021 |
|  ----  | ----  | ----  | ----  |
| AAAI  | - | 6 |  |
| IJCAI  | 1 | 2 |  | 
| AISTATS | - | 3 |   | 
| ICLR | - | 4 |   | 
| KDD | - | 2 |   | 
| INFOCOM | 2 |7  |   | 
| ICML | 3 |  6|   | 
| MOBICOM | - | 1 |   | 
| NeurIPS | - | 17 |   | 
| CCS |  1 |  |   | 
| RTSS | 1 |  |   | 
| S&P | 2 |  |   | 

- B-Level

|  Conference   | 2019 | 2020 | 2021 |
|  ----  | ----  | ----  | ----  |
| CIKM | 1 | 1 |   | 
| ICDM | - |  1|   | 
| COLING  | - | 1 |  |
| ICDCS  | 3 | - |  | 
| EMNLP | - | 2 |   | 
| ECAI | - | 2 |   | 
| DASFAA | - | 4 |   | 
| CoNEXT | - |5  |   | 
| ICNP | - |  2 |   | 
| ICPP | - | 2 |   | 
| ICSOC | - |  2 |   | 
| ICWS | 2 | 2 |   | 
| AIES | - | 1 |   | 
| IPDPS |  - | 2 |   | 
| MIDDLEWARE | - | 3 |   | 
| DCC | 1 | - |   | 
| MOBISYS | 1 |  |   | 
| WSDM | 1 |  |   | 
| NDSS | - | 1 |   | 

- C-Level
	- CCGRID
	- BIGDATA
	- GlobalCom
	- ICC
	- ICASSP
	- ICCCN
	- ISCAS
	- LCN
	- NCA
	- NETWORKING
	- SMC
	- WCNC
	- AMIA
	- ICIP
	- IROS
	- ICPADS
	- MSN
	- IJCNN

## Journals

- Impact Factor > 5.0
	- Future Generation Computer Systems-5.6
	- IEEE Internet of Things-9.9
	- Information Science-5.9
	- IEEE Journal on Selected Areas in Communications-11.4
	- Knowledge-Based Systems-5.9
	- IEEE Transactions on Information Forensics and Security-6.0
	- IEEE Transactions on Industrial Informatics-9.1
	- IEEE Transactions on Signal Processing-5.0
	- IEEE Transactions on Wireless Communications-6.8
	- Communications of the ACM-7.0
	- IEEE Communications Magazine-11.1
	- IEEE Network-8.8
	- IEEE Transactions on Neural Networks and Learning Systems-8.8
	- IEEE Transactions on Vehicular Technology-5.4

- Others
	- IEEE Access
	- IEEE COMMUNICATIONS LETTERS
	- Journal of Parallel and Distributed Computing
	- Journal of Software
	- IEEE Open Journal of the Communications Society
	- Sensors
	- IEEE Transactions on Knowledge and Data Engineering
	- Computer Networks 
	- IEEE Intelligent Systems
	- Computers & Security
	- Mobile Networks and Applications

## Conference Hot Topics

|  Conference   | 2019 | 2020 | 2021 |
|  ----  | ----  | ----  | ----  |
| AAAI  | - | Optimization, NLP, Representation, CV, Privacy, Robustness |  |
| IJCAI  | Explanation | Incentive, Meta-Learning |  | 
| AISTATS | - | Privacy, Efficiency, Robustness |   | 
| ICLR | - | Aggregation, Robustness, Optimization |   | 
| KDD | - | Optimization, NLP |   | 
| INFOCOM | Privacy, Edge | Robustness,  Distribution, Edge, Optimization, Security |   | 
| ICML | Aggregation, Optimization, Robustness|  Distribution, Efficiency, Optimization |   | 
| MOBICOM | - | Efficiency, Privacy |   | 
| NeurIPS | - | Robustness, Optimization, Efficiency, Aggregation,  Personalization, Meta-Learning,  Split Learning|   | 
| CCS |  Security |  |   | 
| RTSS | Edge |  |   | 
| S&P | Privacy, Robustness|  |   | 




## Famous Groups

|  Group   | Topic1 | Topic2 | Topic3 |
|  ----  | ----  | ----  | ----  |
| Qiang Yang | Distribution | Incentive | CV/NLP| 
| Vitaly Shmatikov | Robustness | Personalization |   | 
| Salman Avestimehr | Edge| Robustness | Aggregation |
| Bingsheng He| Privacy | Meta-Learning  |   | 
| Peter Richtárik |  Optimization | Personalization |  Efficiency | 
| Virginia Smith | Optimization | Distribution | Multi-Task | 
| Heng Huang | Optimization |  |   | 
|Choong Seon Hong | Edge| 
| H. Vincent Poor | Wireless| Security| Edge|
| Martin Jaggi| Optimization | Robustness|
| Nguyen H. Tran | Optimization| Personalization| Edge|
| Mehrdad Mahdavi | Optimization| Personalization| Efficiency| 
| Ananda Theertha Suresh | Optimization | Personalization | NLP  | 
| Yasaman Khazaeni | Aggregation | Personalization | NLP | 
| Seraphin B. Calo | Robustness | |   | 

## Related Works
### Incentives

[S1] [Explaining prediction models and individual predictions with feature contributions.](https://link.springer.com/article/10.1007/s10115-013-0679-x)

In order to save the exponential calculation of Shapley Value, This paper apply Monte Carlo sampling to get the approximation of Shapley Value by averaging marginal contribution with random order generation under probability.

[S2] [Polynomial calculation of the Shapley value based on sampling.](./Incentives/Polynomial_calculation_of_the_Shapley_value.pdf)

This paper approximates shapley value estimation at in polynomial time. Specifically, it is by their proposed sampling strategy of drawing a representative group of individuals or cases from a particular population. It is also appliable for any semivalue estimation.


[S3] [Bounding the estimation error of sampling-based Shapley value approximation.](./Incentives/Bounding_the_Estimation_Error.pdf)

Based on the hardness and typical tackling of SV calculation, this paper focus on the classical characteristic function representation, the only attempt to approximate SV for the general class of games which is asymptotic. They propose non-asymptotic bounds on the estimation error under the condition that the variance and range of the players’ marginal contributions is known.


[S4] [Efficient computation of the Shapley value for game-theoretic network centrality.](./Incentives/Efficient_Computation_of_the_Shapley_Value.pdf)

Monte Carlo simulations for SV are computationally expensive and not guaranteed to give an exact answer. Thus, this paper develops exact analytical formulae for SV-based centrality in both weighted and unweighted networks and develop efficient (polynomial) algorithms based on them. Targeted networks include social, organisational, biological and communication networks.


[S5] [Explaining individual predictions when features are dependent: More accurate approximations to Shapley values.](./Incentives/Explaining_individual_predictions_when_features.pdf)

Kernel SHAP is a computationally efficient approximation to Shapley values in higher dimensions which assumes the features are independent. Therefore, this paper extend the Kernel SHAP to handle dependent features by clustering SV corresponding to dependent features, improving the presentation of feature contribution for individual predictions.

[IN15]
[A_Multi-player_Game_for_Studying_Federated_Learnin](./Incentives/IN15_A_Multi-player_Game_for_Studying_Federated_Learnin.pdf)

IJCAI: Multi-party Game Demonstration

[IN16]
[An-incentive-scheme-for-federated-learning-in-the-sky](./Incentives/IN16-An-incentive-scheme-for-federated-learning-in-the-sky.pdf)

 Mobicom: Unmanned aerial vehicle


### Robustness


[P1] [Data Poisoning Attacks Against
Federated Learning Systems.](./Poison/P1_Data_Poisoning_Attacks_Against_Federated_Learning_Systems.pdf)

This paper studies targeted data poisoning attacks against FL systems in which a malicious subset of the participants aim to poison the
global model by sending model updates derived from mislabeled data.

[P2] [Local Model Poisoning Attacks to Byzantine-Robust Federated Learning.](./Poison/P2_Local_Model_Poisoning_Attacks_to_Byzantine_Robust_Federated_Learning.pdf)

It performs the first systematic study on local model poisoning attacks to federated learning under Byzantine-Robust FL. This paper formulates their attacks as optimization problems and apply our attacks to four recent Byzantine-robust federated learning methods.

[P3] [Learning to Detect Malicious Clients for Robust Federated Learning.](./Poison/P3_Learning_to_Detect_Malicious_Clients_for_Robust_Federated_Learning.pdf)

As the central server in the system cannot govern the behaviors of the clients, a rogue client may initiate an attack by sending malicious model updates to the server, so as to degrade the learning performance or enforce targeted model poisoning attacks (a.k.a. backdoor attacks). Therefore, timely detecting these malicious model updates and the underlying attackers becomes critically important. This work proposes a new framework for robust federated learning where the central server learns to detect and remove the malicious model updates using a powerful detection model, leading to targeted defense. 


[P4] [Targeted Backdoor Attacks on Deep Learning Systems Using Data Poisoning.](./Poison/P4_Targeted_Backdoor_Attacks_on_Deep_Learning_Systems_Using_Data_Poisoning.pdf)

It focus on backdoor data poisoning. In this paper, their studied poisoning strategies can apply under a very weak threat model: (1) the adversary has no knowledge of the model and the training set used by the victim system; (2) the attacker is allowed to inject only a small amount of poisoning samples; (3) the backdoor key is hard to notice even by human beings to achieve stealthiness. 

[P5] [Data Poisoning Attacks on Federated Machine
Learning.](./Poison/P5_Data_Poisoning_Attacks_on_Federated_Machine_Learning.pdf)

This paper focus on attacking a federated multi-task learning framework. They formulate the problem of computing optimal poisoning attacks on federated multi-task learning as a bilevel program that is adaptive to arbitrary choice of target nodes and source attacking nodes. Then it propose a systems-aware optimization method, ATTack, which is efficiency to derive the implicit gradients for poisoned data, and further compute optimal attack strategies in the federated machine learning. 

[P6] [Towards Poisoning of Deep Learning Algorithms with
Back-gradient Optimization.](./Poison/P6_Towards_Poisoning_of_Deep_Learning_Algorithms_with_Back-gradient_Optimization.pdf)

To date, data poisoning attacks have been devised only against a limited class of binary learning algorithms, due to the inherent complexity of the gradient-based procedure used to optimize the poisoning points (a.k.a. adversarial training examples). This work extend the definition of poisoning attacks to multiclass problems and propose a poisoning algorithm based on the idea of back-gradient optimization, i.e., to compute the gradient of interest through automatic differentiation, while also reversing the learning procedure to drastically reduce the attack complexity.

[P7] [A Flexible Poisoning Attack Against Machine
Learning.](./Poison/P7_A_Flexible_Poisoning_Attack_Against_Machine_Learning.pdf)

This article proposes an attack method in which the attacker makes the parameter value of the learning model close to his expected value and at the same time makes the model output wrong predictions for certain test samples. It considers the effect of attack and the concealment of attack. 


[P8] [How To Backdoor Federated Learning](./Poison/P8_How_To_Backdoor_Federated_Learning.pdf)

The paper proposes an input matrix manipulation to conduct targeted local model poisoning backdoor in federated learning. When the global is about to converge, the attacker could inject a malicious model based on the difference of the clean global one. And it proved to be efficient even when the attacker does not know the global learning rate. 

[P14] [Robust_Federated_Training_via_Collaborative_Machine_Teaching_using_Trusted_Instances](./Poison/p14_Robust_Federated_Training_via_Collaborative_Machine_Teaching_using_Trusted_Instances.pdf)

AAAI: partial corrupted local data + verification


[P15]
[dba_distributed_backdoor_attacks_against_federated_learning](./Poison/P15_dba_distributed_backdoor_attacks_against_federated_learning.pdf)

ICLR: distributed backdooring

[P16]
[Analyzing_Federated_Learning_through_an_Adversarial_Lens](./Poison/P16_Analyzing_Federated_Learning_through_an_Adversarial_Lens.pdf)

ICML: model poisoning attacks

[P17]
[robust-federated-learning-the-case-of-affine-distribution-shifts-Paper](./Poison/P17-robust-federated-learning-the-case-of-affine-distribution-shifts-Paper.pdf)

NIPS: defense for heterogenous data

[P18]
[attack-of-the-tails-yes-you-really-can-backdoor-federated-learning-Paper](./Posion/P18-attack-of-the-tails-yes-you-really-can-backdoor-federated-learning-Paper.pdf)

NIPS: Edge-case backdoor

[P19]
[Comprehensive-Privacy-Analysis-of-Deep-Learning-Passive-and-Active-White-box-Inference-Attacks-against-Centralized-and-Federated-Learning](./Posion/P19_Comprehensive-Privacy-Analysis-of-Deep-Learning-Passive-and-Active-White-box-Inference-Attacks-against-Centralized-and-Federated-Learning.pdf)

S&P: white-box inference attack


### Optimization_Distribution


[A8] [Self-Balancing Federated Learning With Global Imbalanced Data in Mobile Systems](./Optimization_Distribution/A8-Self-Balancing-Federated-Learning-With-Global-Imbalanced-Data-in-Mobile-Systems.pdf)

The Astraea framework counterweighs the training of FL with imbalanced datasets by two strategies. First, before training the model, Astraea performs data augmentation to alleviate global imbalance. Second, Astraea proposes to use some mediators to reschedule the training of clients according to the KLD between the mediators and the uniform distribution.

[ST1] [Client Selection for Federated Learning with
Heterogeneous Resources in Mobile Edge](./Optimization_Distribution/St1_Client_Selection_for_Federated_Learning_with_Heterogeneous_Resources_in_Mobile_Edge.pdf)

This paper propose a client selection strategy suitable for heterogeneous nodes in distributed systems. It gives a submission deadline in federated learning in order to reduce the impact of staggers. The deadline has been choosen by experience.

