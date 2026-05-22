Auto Tagging Support Tickets Using LLM
An Auto Tagging Support Tickets built using **LLaMA3 via Groq API**.
This project automatically classifies customer support tickets into different categories using **Zero-Shot** and **Few-Shot Prompting** techniques.

---

## 📌 Project Overview

Customer support teams receive thousands of tickets daily.
Manually sorting them takes time and effort.

This project uses **Large Language Models (LLMs)** to automatically predict the most relevant support category for each ticket.

The system compares:

* **Zero-Shot Prompting** → AI predicts without examples
* **Few-Shot Prompting** → AI predicts after seeing examples

The project also evaluates model performance using:

* Accuracy Scores
* Classification Reports
* Confusion Matrices
* Visual Graphs

---

## ✨ Features

* AI-based support ticket classification
* Zero-Shot vs Few-Shot comparison
* Uses **LLaMA3 model** through the **Groq API**
* Performance evaluation and visualization
* Confusion matrix heatmaps
* Accuracy comparison charts
* Clean and beginner-friendly implementation

---

## 🛠 Technologies Used

* **Python**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Groq API**
* **LLaMA3**

---

## 📂 Ticket Categories

The model classifies tickets into categories like:

* Billing & Payments
* Technical Issue
* Account Access
* Shipping & Delivery
* Product Defect
* Feature Request
* Refund & Cancellation

---

## ⚙ How It Works

1. Dataset of support tickets is created
2. Prompts are sent to the LLaMA3 model using Groq API
3. Model predicts top 3 possible categories
4. Predictions are evaluated against true labels
5. Results are visualized using charts and heatmaps

---

## 📊 Evaluation Metrics

The project compares:

* **Top-1 Accuracy**
* **Top-3 Accuracy**
* Precision
* Recall
* F1-Score

---

## 📈 Visualizations

The notebook generates:

* Confusion Matrix Heatmaps
* Accuracy Comparison Bar Charts

These visualizations help compare the performance of:

* Zero-Shot Learning
* Few-Shot Learning

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
```

Install dependencies:

```bash
pip install groq pandas matplotlib seaborn scikit-learn
```

---

## 🔑 API Setup

This project uses the Groq API.

Set your API key before running:

```python
from groq import Groq
client = Groq(api_key="YOUR_API_KEY")
```

---

## ▶ Run the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run all notebook cells step by step.

---

## 📷 Sample Output

* Ticket category predictions
* Accuracy scores
* Confusion matrix graphs
* Comparison charts

---

## 🎯 Learning Outcomes

This project helps in understanding:

* Prompt Engineering
* Zero-Shot Learning
* Few-Shot Learning
* LLM-based Classification
* AI Evaluation Metrics
* Data Visualization

---

## 🤝 Contributing

Contributions are welcome.
Feel free to fork this repository and improve the project.

---

## 📜 License

This project is for educational and learning purposes.

---

## 👨‍💻 Author

Developed by **[Yahya Abbasi]**
