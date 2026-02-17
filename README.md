#  Artificial Neural Networks (ANN) Labs  
### F23 AI – Green | Spring 2026

> **Student**: Ibadullah Hayat (Reg No: B23F0001AI010)  
> **Instructor**: Dr. Usama Ahmed Khan  
> **University**: Pak-Austria Fachhochschule Institute of Applied Science and Technology 
> **Course**: Artificial Neural Networks 

In this repository i will published all the  hands-on labs for the **Artificial Neural Networks** course, implemented in **Python using TensorFlow/Keras**. Each lab builds foundational understanding—from perceptrons to deep networks—with real-world datasets and best practices in model design, regularization, and evaluation.

All notebooks are self-contained, well-documented, and ready to run in **Google Colab**.

---


## 📁 Repository Structure
ann-labs/
├── Lab02_Basic_NN _and_Back_prop.ipynb
├── Lab03_MLP_Binary_Classification.ipynb
├── Lab04_Hyperparameters_Heart_Disease.ipynb
└── README.md

---

>  **Datasets**:  
> - **Lab 03**: Synthetic 2D dataset (`make_classification`)  
> - **Lab 04**: UCI Heart Disease dataset (loaded via public URL)

---

##  How to Run

### Option 1: Google Colab (Recommended)
1. Open any `.ipynb` file in this repo
2. Click **"Open in Colab"**
3. Run all cells — **TensorFlow is pre-installed in Colab!**

### Option 2: Local Setup
```bash
# Clone the repo
git clone https://github.com/Ibad-Hayat14/ANN-Labs.git
cd ANN_Labs

# Install dependencies
pip install tensorflow pandas scikit-learn matplotlib seaborn

# Launch Jupyter
jupyter notebook
