# 🧠 Machine Learning for Chemical Engineers

**Instructor**: Antonio del Rio Chanona  

Welcome to the *Machine Learning for Chemical Engineers* course! This course is designed for final-year undergraduate and master's students interested in applying data-driven and AI-based techniques to engineering problems (with an emphasis on chemical engineering).

---

## 🎯 Course Objectives

- Teach both fundamental and advanced machine learning (ML) and AI concepts.
- Highlight practical applications in chemical engineering.
- Intuitive explanations behind the algorithms and applications.
- Develop an understanding of what ML/AI can and cannot do.

---

## Lecture 1a: Introduction to ML
- 🎥 [Watch Video](https://www.youtube.com/watch?v=DaSwgTO-BqQ&t=3s)
- 📑 [Slides](slides/lecture01a_ML4CE_course_overview.pdf)

## Lecture 1b: Linear regression
- 🎥 [Watch Video](#) [coming soon!]
- 📑 [Slides](slides/lecture01b_ML4CE_linear_regression.pdf)
- 📓 [Notebook: ML Models with sklearn](notebooks/notebook01_ML4CE_ml_models.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1NViNm2MUy8FgV1tEEoxd2_NoSYzghEOw?usp=sharing)

## Lecture 1c: Maximum likelihood estimation
- 🎥 [Watch Video](#) [coming soon!]
- 📑 [Slides](slides/lecture01c_ML4CE_maximum_likelihood.pdf)

## Lecture 2a: Neural networks
- 🎥 [Watch Video](#) [coming soon!]
- 📑 [Slides](slides/lecture02a_ML4CE_neural_networks.pdf)

## Lecture 2b: Optimization algorithms for deep learning (e.g., SGD, Adam)
- 🎥 [Watch Video](#) [coming soon!]
- 📑 [Slides](slides/lecture02b_ML4CE_optimization.pdf)
- 📓 [Notebook: Optimization algorithms for deep learning](notebooks/notebook02b_ML4CE_optimization.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1CaSIIeGtrwQ-dC3bc3_oQY9x-wr7-HTC?usp=sharing)

## Lecture 2c: Optimization in deep learning
- 🎥 [Watch Video](#) [coming soon!]
- 📑 [Slides](slides/lecture02b_ML4CE_optimization.pdf)

---

## 🗂️ Course Structure

The course consists of video lectures, slides, Jupyter notebooks, and hackathon-style coursework where you can build your own algorithm and benchmark against existing one. Each lecture includes code examples.

### 📚 Curriculum Highlights

1. **Introduction to Machine Learning**
   - What is machine learning
   - Modern ML vs expert systems ML
   - Examples of ML in engineering

2. **Machine Learning Models**
   - Linear regression, neural networks, decision trees
   - Gaussian processes
   - Supervised learning principles

3. **Anomaly Detection**
   - Probabilistic models
   - Dimensionality reduction (PCA, autoencoders)
   - Clustering methods

4. **Data-Driven Optimisation**
   - Bayesian optimisation
   - Derivative-free optimisation (model-based vs direct)
   - Evolutionary algorithms
   - Design of experiments & simulations

5. **Data-Driven Control**
   - Reinforcement learning
   - Data-driven model predictive control

6. **Large Language Models (LLMs)**
   - Transformers, transfer learning, self-supervised learning
   - Vocabulary and LLM pipeline
   - How does ChatGPT work?

---

## 🧪 Build your own algorithm

This course uses **hackathon-style coursework**:

There are generally 3 types of coursework mirroring ML applications for engineering:

- **Data-driven optimisation**: Build ML algorithms for controller tuning, design of experiments, real-time optimisation, etc.
- **Unsupervised learning**: Anomaly detection in the Tennessee Eastman plant.
- **Data-driven control**: Build a data-driven model-predictive or reinforcement learning algorithm to control chemical reactors or supply chains.

📚 [All courseworks can be found here](https://github.com/OptiMaL-PSE-Lab/Imperial-ML4CE-Course)

---

## 📁 Repository Structure

```plaintext
.
├── README.md                # This file
├── syllabus.md              # (Optional) Full course syllabus
├── environment.yml          # Reproducible conda environment
├── slides/                  # PDF slides per lecture
├── notebooks/               # Jupyter notebooks per lecture/topic
│   └── lecture01_intro/
│       ├── 01_data_overview.ipynb
│       └── 02_visualization_basics.ipynb
├── data/                    # Example datasets (optional)
└── resources/               # Extra papers, readings, links
