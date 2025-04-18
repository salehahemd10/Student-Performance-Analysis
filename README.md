📊 Student Performance Analysis Project
GitHub Repository: said-hahemd10/Student-Performance-Analysis

🔍 Overview
This project analyzes student performance data using Python (Pandas, NumPy, Matplotlib) in a Jupyter Notebook. It explores how factors like gender, parental education, lunch type, and test preparation affect math, reading, and writing scores.

📂 Repository Structure
Student-Performance-Analysis/  
├── StudentsPerformance.csv        # Dataset (1000 student records)  
├── student-performance.ipynb     # Jupyter Notebook (Full Analysis)  
├── student-performance-featured.webg  # Visualizations  
└── README.md                     # Project Documentation  
📊 Dataset Features
Column	Description
gender	Male / Female
race/ethnicity	Group A-E classification
parental level of education	Highest education of parents
lunch	Standard / Free or Reduced
test preparation course	None / Completed
math score	Score (0-100)
reading score	Score (0-100)
writing score	Score (0-100)
🔎 Key Findings
📌 Gender Differences
👩 Female students perform better in reading & writing.

👨 Male students slightly outperform in math.

📌 Parental Education Impact
Students with higher-educated parents score better.

Best performance: Parents with master's degrees.

📌 Other Factors
Standard lunch 🍎 → Higher scores than free/reduced.

Test prep 📚 → Significant score improvement.

🚀 How to Run
Clone the repo:

bash
git clone https://github.com/said-hahemd10/Student-Performance-Analysis.git
Install dependencies:

bash
pip install pandas numpy matplotlib jupyter
Open Jupyter Notebook:

bash
jupyter notebook student-performance.ipynb
📜 License
MIT License - Free to use and modify.
