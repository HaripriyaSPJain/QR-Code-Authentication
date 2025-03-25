# QR Code Authentication: Detecting Original vs. Counterfeit Prints

## 📌 Overview
This project focuses on detecting counterfeit QR codes by distinguishing between:
- **First Prints (Original QR Codes)**
- **Second Prints (Counterfeit QR Codes)**

Using **Machine Learning (Random Forest)** and **Deep Learning (CNN)**, the system accurately classifies QR codes based on **copy detection patterns (CDPs)**. The dataset consists of images of **first prints (originals) and second prints (scanned & reprinted copies).**

---

## 📂 Dataset
The dataset contains:
- **First Print:** Original QR codes with embedded copy detection patterns.
- **Second Print:** Counterfeit versions created by scanning and reprinting the original QR codes.

🔗 **Dataset Link**: [Download Here](https://drive.google.com/drive/folders/1pPeWT1zntlKXnuY_yHmpI-ZzKl4nLgQS?usp=drive_link)

💡 **Note:** Ensure that the dataset is correctly placed in the project directory.

---

## Outputs
Output 1:

![image](https://github.com/user-attachments/assets/08392a8e-8767-44a4-b344-e678720bdacf)

Output 2:

![image](https://github.com/user-attachments/assets/a04c647f-0021-42b7-a648-d23de055ad0f)


## 🔧 Installation
To set up the environment, install the required dependencies:
```bash
pip install opencv-python numpy pandas scikit-learn tensorflow matplotlib seaborn joblib



