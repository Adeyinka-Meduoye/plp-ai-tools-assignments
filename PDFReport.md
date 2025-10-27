### **PART 1: Theoretical Understanding (40%)**

#### **Q1: TensorFlow vs. PyTorch**

**Answer Outline:**

* **TensorFlow:**

  * Developed by Google.
  * Uses computational graphs; ideal for production and deployment (e.g., TensorFlow Serving, TensorFlow Lite).
  * Better suited for **large-scale production** and **cross-platform deployment**.

* **PyTorch:**

  * Developed by Meta (Facebook).
  * Uses dynamic computation graphs (“define-by-run”)—better for research, flexibility, and debugging.
  * Ideal for **research and rapid prototyping**.

**When to choose:**

* Choose **TensorFlow** for large, deployable models (mobile/web apps, APIs).
* Choose **PyTorch** for experimental research, rapid iteration, and academic settings.


#### **Q2: Two Use Cases for Jupyter Notebooks**

1. **Interactive Experimentation:**
   Run step-by-step model training, tweak hyperparameters, and visualize outputs inline.
2. **Data Visualization & Reporting:**
   Combine code, graphs (Matplotlib/Seaborn), and markdown commentary for transparent AI reporting.


#### **Q3: How spaCy Enhances NLP**

* spaCy provides **pre-trained pipelines**, **efficient tokenization**, and **NER (Named Entity Recognition)**—far more advanced than basic Python `string` methods.
* Supports **POS tagging**, **dependency parsing**, and **text categorization**, all optimized for **speed and scalability**.


#### **Comparative Analysis: Scikit-learn vs. TensorFlow**

| Criteria                | **Scikit-learn**                               | **TensorFlow**                                |
| ----------------------- | ---------------------------------------------- | --------------------------------------------- |
| **Target Applications** | Classical ML (SVM, Decision Trees, Regression) | Deep Learning (CNNs, RNNs, Transformers)      |
| **Ease of Use**         | Easier for beginners, simpler syntax           | Steeper learning curve                        |
| **Community Support**   | Strong for traditional ML                      | Massive community for DL and deployment tools |


### **PART 3: Ethics & Optimization (10%)**

#### **Ethical Considerations**

* **Bias Examples:**

  * MNIST: potential bias in digit representation (poor for handwritten digits outside standard Latin numerals).
  * Amazon Reviews: bias in sentiment terms (“cheap” could mean good or bad depending on culture).

**Mitigation Tools:**

* **TensorFlow Fairness Indicators:** measure fairness across groups.
* **spaCy Rule-Based Systems:** allow bias-aware text rules (e.g., adjusting lexicons to be neutral).
