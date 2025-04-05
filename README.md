# practical-machine-learning-project
Course project for Practical Machine Learning on Coursera

# Practical Machine Learning - Course Project

This repository contains my submission for the Course Project in the **Practical Machine Learning** course on Coursera, part of the Data Science Specialization by Johns Hopkins University.

## 📊 Project Goal

Using sensor data collected from accelerometers on the belt, forearm, arm, and dumbbell of 6 individuals, the goal is to predict the manner in which the participant performed a barbell lift. The target variable is `classe`.

## 🧠 Methods Used

- Data Cleaning (NA removal, column filtering)
- Feature Selection
- **Random Forest** model trained using the `caret` package
- 3-fold cross-validation (`trainControl`)
- Final prediction made on 20 unknown test cases

## 📁 Files Included

- `course-project.Rmd`: R Markdown file with full code and explanations
- `course-project.html`: Rendered HTML report (viewable in browser)

## ✅ Results

The model achieved nearly 100% accuracy on the training data and predicted all 20 test cases successfully. See the report for full details.

## 📌 Submission

- This project is submitted as part of the Coursera peer review system.
- The final predictions from this repo were submitted to the [Course Project Prediction Quiz](https://www.coursera.org/learn/practical-machine-learning/home/week/4)

---

🎯 Thank you for viewing!
