# 📘 Probability Analysis Using Student Dataset

---

## 📌 Project Title
**Probability Analysis and Visualization using Student Performance Dataset**

---

## 📂 Dataset Description
The dataset contains information about students with the following attributes:

- Study Hours  
- Attendance Percentage  
- Group Discussion Participation (Yes/No)  
- Final Exam Result (Pass/Fail)  

---

## 🎯 Objective
The main objectives of this project are:

- To understand basic probability concepts  
- To calculate empirical probabilities from real data  
- To analyze relationships between different variables  
- To visualize data using Venn diagrams  
- To apply conditional probability and Bayes theorem  

---

## 🛠️ Tools and Libraries Used

- Python  
- Pandas  
- Matplotlib  
- Matplotlib-venn  

---

## ⚙️ Steps Performed

### 1️⃣ Data Loading
- Loaded dataset using Pandas  
- Displayed first few records using `.head()`  
- Checked data structure using `.info()`  

---

### 2️⃣ Probability Calculation
- Probability of students passing the exam  
- Probability of attendance greater than 80%  
- Probability of participation in group discussions  

---

### 3️⃣ Random Variable and Distribution
- Defined a random variable for number of students passing  
- Applied Binomial distribution to calculate probabilities  

---

### 4️⃣ Venn Diagram Analysis
- Created two sets:
  - Students with study hours > 10  
  - Students with attendance > 80%  
- Visualized overlap between both sets using Venn diagram  

---

### 5️⃣ Contingency Table
- Created a table between:
  - Group Discussion  
  - Final Exam Result  

---

### 6️⃣ Probability Types
- Joint Probability  
- Marginal Probability  
- Conditional Probability  

---

### 7️⃣ Bayes Theorem
- Calculated probability of passing given high attendance  
- Applied Bayes theorem formula  

---

## 📊 Key Insights

- Students with higher attendance have a higher probability of passing  
- Participation in group discussions improves performance  
- Study hours and attendance are positively related  

---

## ▶️ How to Run the Code

### Step 1: Install Required Libraries
```bash
pip install pandas matplotlib matplotlib-venn
