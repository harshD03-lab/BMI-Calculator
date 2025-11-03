# BMI-Calculator

# 🧮 BMI Calculator

A simple yet elegant **Body Mass Index (BMI) Calculator** built using **Python** and **Streamlit**.  
This web application allows users to calculate their BMI quickly and understand their health category based on standard BMI ranges.

---

## 🚀 Features

- ✅ User-friendly interface built with **Streamlit**
- ⚖️ Supports multiple height units — **Centimeters, Meters, and Feet**
- 🧍‍♂️ Calculates BMI instantly with just one click
- 📊 Provides clear interpretation of BMI results:
  - Extremely Underweight
  - Underweight
  - Healthy
  - Overweight
  - Extremely Overweight
- 🔒 Error handling for invalid or zero values

---

## 🛠️ Tech Stack

| Component | Description |
|------------|-------------|
| **Language** | Python 🐍 |
| **Framework** | Streamlit |
| **Editor Used** | Visual Studio Code |
| **Platform** | Web Application |

---

## 🧠 How It Works

1. The user enters their **weight (in kilograms)**.  
2. The user selects their **height unit** — Centimeters, Meters, or Feet.  
3. The app automatically converts the height to meters.  
4. The BMI is calculated using the standard formula:  
   \[
   BMI = \frac{weight(kg)}{height(m)^2}
   \]
5. Based on the calculated BMI, the app displays a **health category** message.



📸 Preview

<img width="1148" height="731" alt="Screenshot 2025-11-01 031736" src="https://github.com/user-attachments/assets/4974e883-5eee-4112-86c2-86ea55abd0c4" />



<img width="950" height="734" alt="Screenshot 2025-11-01 031819" src="https://github.com/user-attachments/assets/7ea66029-7bc8-4c95-9196-e9435bc27153" />







## 💻 Installation & Usage

Follow these simple steps to run the BMI Calculator locally on your system:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/harshD03/BMI-Calculator.git

2️⃣ Navigate to the Project Folder
cd BMI-Calculator

3️⃣ Install Required Dependencies
pip install -r requirements.txt

4️⃣ Run the Streamlit App
streamlit run app.py


⚡ The app will open automatically in your default web browser at http://localhost:8501.
