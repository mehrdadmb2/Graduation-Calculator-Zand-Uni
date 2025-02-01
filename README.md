# Graduation Calculator for Zand University Students 🎓💻

![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fmehrdadmb2%2FGraduation-Calculator-Zand-Uni&count_bg=%2379C83D&title_bg=%23555555&icon=github.svg&icon_color=%23E7E7E7&title=visits&edge_flat=false)
![GitHub license](https://img.shields.io/github/license/mehrdadmb2/Graduation-Calculator-Zand-Uni)
![GitHub stars](https://img.shields.io/github/stars/mehrdadmb2/Graduation-Calculator-Zand-Uni?style=social)
![GitHub forks](https://img.shields.io/github/forks/mehrdadmb2/Graduation-Calculator-Zand-Uni?style=social)
![GitHub issues](https://img.shields.io/github/issues/mehrdadmb2/Graduation-Calculator-Zand-Uni)
![GitHub contributors](https://img.shields.io/github/contributors/mehrdadmb2/Graduation-Calculator-Zand-Uni)
![GitHub last commit](https://img.shields.io/github/last-commit/mehrdadmb2/Graduation-Calculator-Zand-Uni)
![GitHub repo size](https://img.shields.io/github/repo-size/mehrdadmb2/Graduation-Calculator-Zand-Uni)

---

## 📜 Introduction

This Excel-based tool is tailored specifically for **Computer Engineering students at Zand University** (entry before 1403) to help them track their graduation progress. It calculates:

- 📚 Total passed courses and credits.
- 🎯 Passed courses and credits categorized by type (e.g., general, specialized, elective).
- 📊 Comparison of completed credits with the minimum required for graduation.
- ⏳ Remaining credits and courses to meet graduation requirements.

---

## 🛠️ Features

- **Easy Data Entry**: Input course details (name, credits, type) in a user-friendly Excel sheet.
- **Automated Calculations**: Instantly calculate passed courses and credits with visualized results.
- **Conditional Formatting**: Highlight key information for better readability.
- **Data Validation**: Prevent incorrect data entry with custom alerts and guidance.

---

## 📂 File Structure

### **Sheet 1: Summary**
- **B:** Course Name.
- **C:** Credits.
- **D:** Course Type (e.g., General, Specialized, Elective).
- **H:** Unique Course Types.
- **I:** Total Courses per Type.
- **J:** Total Credits per Type.
- **M:** Minimum Credits Required per Type.

### **Sheet 2: Details**
- **B:** Course Name.
- **C:** Credits.
- **D:** Course Type.
- **E:** Status (0 = Not Passed, 1 = Passed).
- **F:** Additional Notes.

---

## 📝 Usage Guide

1. **Open the File**:
   Download and open the Excel file in Microsoft Excel.

2. **Input Data**:
   - Enter course details in **Sheet 2**.
   - Ensure that "Status" is set to `0` or `1` for each course.

3. **View Results**:
   - Navigate to **Sheet 1** to view automatically calculated totals.
   - Check the remaining courses and credits required for graduation.

4. **Validate Data**:
   - Ensure all entries in "Status" are either `0` or `1`.
   - Incorrect entries will trigger a validation error with guidance.

---

## 🌟 Key Metrics

- **Total Passed Courses:** Automatically calculated in Sheet 1.
- **Total Passed Credits:** Summed up for all passed courses.
- **Remaining Courses/Credits:** Compared with minimum graduation requirements.
- **Type-specific Progress:** Track progress for each course type individually.

---

## 📈 Example

| Course Name      | Credits | Type        | Status | Notes         |
|------------------|---------|-------------|--------|---------------|
| Data Structures  | 3       | Specialized | 1      | Passed        |
| Mathematics      | 4       | General     | 0      | Not Attempted |
| Programming I    | 3       | Core        | 1      | Passed        |

### Summary:
- **Passed Courses:** 2.
- **Passed Credits:** 6.
- **Remaining:** Calculated automatically.

---

## ⚠️ Notes

- This tool is designed for students enrolled **before 1403**.
- Ensure the minimum credits required per type are updated in **Column M, Sheet 1**.
- Do not modify formulas unless necessary.

---

## 📄 License

This project is licensed under the **MIT License**. Feel free to use, modify, and share it for educational purposes.

---

## 🚀 Contributing

Contributions are welcome! If you encounter issues or have suggestions, please open an issue or submit a pull request.

---

## 🌐 Links

- [GitHub Repository](https://github.com/mehrdadmb2/Graduation-Calculator-Zand-Uni)
- [Documentation](https://github.com/mehrdadmb2/Graduation-Calculator-Zand-Uni#readme)

---

![Keep Learning](https://img.shields.io/badge/Keep-Learning-blue?style=for-the-badge)

