# Hi, I'm Faeze Mohammadi 👋

**Computer Engineering Student at the University of Tehran | Artificial Intelligence and Machine Learning | Computer Vision · NLP · Reinforcement Learning**

I am a Computer Engineering undergraduate pursuing research in artificial intelligence, machine learning, and deep learning. I work with Dr. Ahmad Kalhor on data and representation evaluation, and with Dr. Khatami under Dr. Siamak Mohammadi on neural networks for side-channel analysis.

My projects include a Separation Index representation audit, Persian poetry attribution and retrieval, blood-cell classification, reinforcement learning, and evolutionary and adversarial search. I develop and evaluate models through experiments, baseline comparisons, and analysis of their behavior and limitations.

**Open to undergraduate research collaborations and internships in AI, machine learning, and related fields.**

## Education and academic highlights

- **University of Tehran — BSc student in Computer Engineering**
- **GPA: 19.68/20.00**
- **Academic rank: 1st** in the Computer Engineering entering cohort, based on the first two years of study
- **Selected course grades (20/20):** Probability and Statistics; Discrete Mathematics; Artificial Intelligence; Data Structures; Advanced Programming; Formal Languages and Automata; Engineering Mathematics; Calculus II; Differential Equations
- Six years of secondary education in schools of the **National Organization for Development of Exceptional Talents (NODET; SAMPAD)**, 2018–2024; **Diploma GPA: 19.86/20.00**
- **National Olympiad Round 2 qualifier:** Mathematics, Computer Science, and Economics & Management

## Current research

### Data and Representation Evaluation with SI and SmI

**University of Tehran | Faculty-guided research with Dr. Ahmad Kalhor | In progress**

- Working on an ongoing research project involving Separation Index (SI) and Smoothness Index (SmI) for evaluating data and neural representations.
- The research covers data difficulty, quantity, diversity, and coverage; changes in network representations during training; and feature or layer removal while maintaining accuracy. Current SI benchmarking uses MNIST, Fashion-MNIST, CIFAR-10, and CIFAR-100 with controlled comparisons and separate training and validation sets.
- These studies form the foundation of a broader research project that continues to develop under Dr. Kalhor's guidance.

### Neural Networks for Profiling Side-Channel Analysis

**University of Tehran | Guided by Dr. Khatami under Dr. Siamak Mohammadi | In progress**

- Evaluating MLP, CNN, LSTM, and a CNN with a linear-attention adapter on ASCAD, using 50,000 profiling traces and 10,000 attack traces to study recovery of a single AES key byte.
- Analyzing key-rank curves across seeds, checkpoint replay, and ablations. CNN/MLP and hybrid experiments recovered the target byte across three seeds; recurrent follow-ups also include unsuccessful results.
- Examining attention ablations and seed variability; the hybrid showed mixed recovery efficiency relative to matched CNN controls in the exploratory experiments.

## Teaching experience

### Teaching Assistant / TA Supervisor — Discrete Mathematics

**University of Tehran | Instructor: Dr. Siamak Mohammadi**

Serving a third term as a teaching assistant, with TA supervisor responsibilities this term. Supporting students in mathematical logic, proof techniques and induction, recurrence relations, counting, and graph theory.

### Teaching Assistant — Formal Languages and Automata

**University of Tehran | Instructor: Dr. Hossein Hojjat**

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

**Programming:** Python · C++ · C · R · Verilog

**Machine Learning and Data Analysis:** PyTorch · TensorFlow/Keras · scikit-learn · OpenCV · NumPy · pandas

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

[View or download my academic and research resume](./certificates/Faeze-Mohammadi-Academic-Research-Resume.pdf)

## Connect

- [LinkedIn](https://www.linkedin.com/in/faeze-mohammadi-533330435/)
- [Kaggle](https://www.kaggle.com/itsfafa84)
- Email: [faezemhmd2005@gmail.com](mailto:faezemhmd2005@gmail.com)

