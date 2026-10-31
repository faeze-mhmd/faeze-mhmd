# Hi, I'm Faeze Mohammadi 👋

**Computer Engineering Student at the University of Tehran | Machine Learning · Deep Learning · Computer Vision · Cryptography**

I am a Computer Engineering undergraduate pursuing research in artificial intelligence, machine learning, and deep learning. I work with Dr. Ahmad Kalhor in the Machine Learning Laboratory on evaluating data and representations with the Separation Index, and with Malihe Khatami in Dr. Siamak Mohammadi's Dependable System Design Laboratory on neural networks for side-channel analysis.

My projects include a Separation Index representation audit, Persian poetry attribution and retrieval, blood-cell classification, reinforcement learning, and evolutionary and adversarial search. I develop and evaluate models through experiments, baseline comparisons, and analysis of their behavior and limitations.

**Open to undergraduate research collaborations and internships in AI, machine learning, and related fields.**

## Education and academic highlights

- **University of Tehran — BSc in Computer Engineering** (Sep 2024 – present; expected Jul 2028)
- **GPA: 19.68/20.00**
- **Academic rank: 1st of ~120** in the Computer Engineering entering cohort, based on the first two years of study
- **Selected course grades (20/20):** Probability and Statistics; Discrete Mathematics; Artificial Intelligence; Data Structures; Advanced Programming; Formal Languages and Automata; Engineering Mathematics; Calculus II; Differential Equations
- **Selected current coursework (Fall 2026):** Machine Learning; Signals and Systems
- Six years of secondary education in schools of the **National Organization for Development of Exceptional Talents**, 2018–2024; **Diploma GPA: 19.86/20.00**
- **Second-round qualifier, Iranian National Olympiads:** Mathematics, Informatics, and Economics & Management

## Current research

### Data and Representation Evaluation with SI and SmI

**Machine Learning Laboratory, University of Tehran | Supervisor: Dr. Ahmad Kalhor | Oct 2026 – present**

- Studying how the Separation Index (SI) and Smoothness Index (SmI) can assess data difficulty and diversity, track how representations evolve across layers during training, and guide feature or layer reduction without loss of accuracy; the project is in its first phase.
- Exploratory first phase: compared sample-selection methods on MNIST, Fashion-MNIST, CIFAR-10, and CIFAR-100 using accuracy, SI, geometric coverage, and density, with separate training and validation sets.
- Now extending to the mean and variance of SI across data subsets as a diversity criterion, followed by SmI and the layer-wise analysis.

### Neural Network-Based Side-Channel Attack Analysis for Cryptographic Algorithms

**[Dependable System Design Lab](https://dsdlab.ut.ac.ir), University of Tehran | Supervisor: Malihe Khatami (PhD candidate) | PI: Dr. Siamak Mohammadi | Oct 2026 – present**

- Part of the laboratory's project *Design and Implementation of Remote Side-Channel Attacks and Countermeasures*.
- Evaluating MLP, CNN, LSTM, and a CNN with a linear-attention adapter on ASCAD, using 50,000 profiling traces and 10,000 attack traces to study recovery of a single AES key byte.
- Analyzing key-rank curves across seeds, checkpoint replay, and ablations. CNN, MLP, and the hybrid model recovered the target byte across all three seeds; LSTM models did not, and these negative results are documented.
- Examining attention ablations and seed variability; the hybrid showed mixed recovery efficiency relative to matched CNN controls in the exploratory experiments.

## Teaching experience

### Teaching Assistant and TA Supervisor — Discrete Mathematics

**University of Tehran | Instructor: Dr. Siamak Mohammadi | Fall 2025 – present (3 terms)**

Serving a third term as a teaching assistant, with TA supervisor responsibilities this term, in a course of 90+ students. Supporting students in mathematical logic, proof techniques and induction, recurrence relations, counting, and graph theory.

### Teaching Assistant — Formal Languages and Automata

**University of Tehran | Instructor: Dr. Hossein Hojjat | Fall 2026 – present**

Supporting students in understanding formal languages, grammars, and finite automata, including the connections between language descriptions and computational models. Helping students reason through automata constructions, formal proofs, and course problems.

## Selected projects

| Project | Focus and evaluation | Language and main tools |
| --- | --- | --- |
| [Persian Poetry Attribution and Search](https://github.com/faeze-mhmd/persian-poetry-research) | Separate five-author attribution and known-item retrieval on 500 poems. Character TF-IDF with LinearSVC reached clean macro-F1 of 0.9502 on 100 held-out poems; a bounded OCR/ASR pilot supports a local demo. | Python · scikit-learn · Tesseract · Vosk |
| [Separation Index Representation Audit](https://github.com/faeze-mhmd/si-representation-audit) | Audits a published SI definition on Optdigits MLPs and Fashion-MNIST CNNs, with paired seeds, fixed baselines, deterministic neighbor rules, and explicit negative results. | Python · PyTorch · NumPy |
| [Blood Cell Classification with PyTorch](https://github.com/faeze-mhmd/blood-cell-classification-pytorch) | Compares MLP and CNN models for five-class classification under approximately matched parameter budgets; analyzes confusion matrices, feature maps, prediction confidence, spatial transformations, and occlusion. | Python · PyTorch · torchvision · NumPy |
| [MountainCar Reinforcement Learning with Q-Learning](https://github.com/faeze-mhmd/mountaincar-q-learning) | Implements tabular Q-learning from scratch; compares exploration schedules, state discretization, and reward shaping, including reward hacking assessed through goal-reaching success. | Python · NumPy · Gym |
| [Genetic Music Reconstruction and Minimax Checkers](https://github.com/faeze-mhmd/genetic-music-and-minimax-checkers) | Reconstructs melodies with genetic search on FFT-derived frequencies and implements Minimax/Alpha-Beta game agents; compares genetic settings and search-depth runtimes. | Python · NumPy · librosa · Pygame |
| [Supervised Learning from Scratch](https://github.com/faeze-mhmd/supervised-learning-from-scratch) | Implements decision trees and multiclass softmax regression; compares standard baselines and investigates feature engineering, class imbalance, and scaling with train-only preprocessing. | Python · NumPy · pandas · scikit-learn |

Additional projects include [Bayesian robot localization in R](https://github.com/faeze-mhmd/probability-and-robot-localization-r) with a discrete Bayes filter under sensor and motion uncertainty, [Naive Bayes spam classification in R](https://github.com/faeze-mhmd/probability-and-naive-bayes-r), and [pathfinding with BFS, DFS, IDS, A*, and Weighted A*](https://github.com/faeze-mhmd/snake-search-with-portals).

## Technical skills

**Programming:** Python · C++ · C · R

**Machine Learning and Data Analysis:** PyTorch · TensorFlow/Keras · scikit-learn · OpenCV · NumPy · pandas

**Languages:** Persian (native) · English (upper-intermediate, CEFR B2)

## Selected courses and certificates

| Course or credential | Provider | Certificate |
| --- | --- | --- |
| Machine Learning Specialization | DeepLearning.AI / Stanford Online via Coursera | [PDF](./certificates/machine-learning-specialization.pdf) |
| CS50's Introduction to Artificial Intelligence with Python | Harvard CS50 | [PDF](./certificates/CS50AI.pdf) |
| Cryptography I | Stanford Online via Coursera | [PDF](./certificates/Coursera%20Cryptography%2053U50G5ZY7VF.PDF) |
| Vision Language Models Bootcamp | OpenCV University | [PDF](./certificates/opencv-vlm-bootcamp.pdf) |
| PyTorch Bootcamp | OpenCV University | [PDF](./certificates/opencv-pytorch-bootcamp.pdf) |
| OpenCV Bootcamp | OpenCV University | [PDF](./certificates/opencv-opencv-bootcamp.pdf) |
| TensorFlow-Keras Bootcamp | OpenCV University | [PDF](./certificates/opencv-tensorflow-keras-bootcamp.pdf) |
| Writing in the Sciences | Stanford Online via Coursera | [PDF](./certificates/coursera-writing-in-the-sciences.pdf) |

<details>
<summary>Additional completed courses and certificates</summary>

| Course or credential | Provider | Certificate |
| --- | --- | --- |
| Supervised Machine Learning: Regression and Classification | Machine Learning Specialization — Course 1 | [PDF](./certificates/supervised-machine-learning.pdf) |
| Advanced Learning Algorithms | Machine Learning Specialization — Course 2 | [PDF](./certificates/advanced-learning-algorithms.pdf) |
| Unsupervised Learning, Recommenders, Reinforcement Learning | Machine Learning Specialization — Course 3 | [PDF](./certificates/unsupervised-learning-recommenders-reinforcement-learning.pdf) |
| Introduction to Statistics | Stanford Online via Coursera | [PDF](./certificates/coursera-introduction-to-statistics.pdf) |
| Python for Beginners | OpenCV University | [PDF](./certificates/opencv-python-for-beginners.pdf) |
| Deep Learning Fundamentals | DeepLearning.TV / Cognitive Class | [PDF](./certificates/DeepLearning.TV%20ML0115EN%20Certificate%20_%20Cognitive%20Class.pdf) |
| Data Analysis with Python | IBM / Cognitive Class | [PDF](./certificates/IBM%20DA0101EN%20Certificate%20_%20Cognitive%20Class.pdf) |
| Machine Learning with Python | IBM / Cognitive Class | [PDF](./certificates/IBM%20ML0101EN%20Certificate%20_%20Cognitive%20Class.pdf) |
| Deep Learning with TensorFlow | IBM / Cognitive Class | [PDF](./certificates/IBM%20ML0120EN%20Certificate%20_%20Cognitive%20Class.pdf) |

</details>


## Additional academic writing

**A Study of the Higgs Boson Particle** — Sole-authored literature review manuscript, available upon request. Synthesizes scientific literature into a structured technical review.

## Resume

[View or download my research CV](./Faeze-Mohammadi-Research-CV.pdf)

## Connect

- [LinkedIn](https://www.linkedin.com/in/faeze-mohammadi-533330435/)
- [Kaggle](https://www.kaggle.com/itsfafa84)
- Email: [faezemhmd2005@gmail.com](mailto:faezemhmd2005@gmail.com)

