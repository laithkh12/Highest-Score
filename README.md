# 🎓 Student Score Analyzer

This project provides an example of calculating total and maximum exam scores from a list of student scores. It demonstrates different approaches for each task, including using built-in Python functions and manual looping techniques.

---

## 📋 Features

- **Total Score Calculation**: Two approaches to calculate the total of all student scores.
- **Maximum Score Calculation**: Two options to determine the highest score in the list.
- **Simple and Efficient**: Demonstrates both quick and more detailed looping methods.

---

## 🔍 Code Overview

The following code demonstrates two different ways to perform each task:

1. **Calculate the Total Exam Score**:
   - **Option 1**: Uses `sum()` for a quick and efficient total.
   - **Option 2**: Uses a `for` loop to manually add each score.

2. **Find the Maximum Score**:
   - **Option 1**: Uses `max()` for a straightforward maximum value.
   - **Option 2**: Uses a `for` loop to track the highest score manually.

### Code Snippet

```python
student_score = [150, 142, 185, 120, 171, 184, 149, 24, 59, 68, 199, 78, 65, 89, 86]

# Calculate Total Exam Score

# Option 1: Using sum()
# totalExamScore = sum(student_score)
# print(f'The sum is {totalExamScore}')

# Option 2: Using a for loop
# total_sum = 0
# for score in student_score:
#     total_sum += score
# print(total_sum)

# ---------------------------------------------------------------------------------------

# Calculate Maximum Score

# Option 1: Using max()
# print(max(student_score))

# Option 2: Using a for loop
# max_score = 0
# for score in student_score:
#     if score > max_score:
#         max_score = score
# print(max_score)
```

## 🧮 Usage Instructions
1. Clone the Repository:
```bash
   git clone https://github.com/your-username/student-score-analyzer
   cd student-score-analyzer
```
2. Run the Code: Execute the script in a Python environment to see the total and maximum scores:
```bash
python student_score_analyzer.py
```
3. Experiment with Options:
  Uncomment either Option 1 or Option 2 for each task to try different approaches.

## 📈 Example Output
```bash
The sum of all student scores is: 1769
The highest score among students is: 199
```

## ⚙️ Customization
  Feel free to modify the student_score list with other scores for testing different datasets or to implement additional score analysis methods!

## 📜 License
  This project is licensed under the MIT License. See the LICENSE file for details.

Happy analyzing! 📊✨

