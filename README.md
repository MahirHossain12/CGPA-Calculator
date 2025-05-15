Here’s a full project description you can use for your GitHub repository:

---

# 🎓 CGPA Calculator for University Students (4.0 Scale)

This is a simple **terminal-based CGPA calculator** built in Python. It helps students calculate their overall CGPA and last 2 years' CGPA (typically semesters 5–8) based on the grades and credit hours of individual courses. This tool is particularly useful for **University of Dhaka CSE students**, but it can be adapted to any university that uses a **4.00 GPA scale**.

---

## 📌 Features

* Menu-driven interface with simple options for grades and credit hours.
* Supports all 8 semesters and allows skipping any semester.
* Calculates:

  * **Overall CGPA**
  * **CGPA of the last 2 years (Semesters 5–8)**
* Saves the final result in a file named `cgpa_results.txt`.
* Easy to understand, beginner-friendly code — ideal for learning.

---

## 🎯 How It Works

1. The user is asked to enter the number of courses for each semester (1 to 10).
2. For each course, the user selects:

   * The **grade** (from options like A+, A, B+, etc.)
   * The **credit hours** (from a list of standard university values)
3. The program multiplies the grade point by credit hours to calculate weighted points.
4. It adds up all points and credit hours across semesters.
5. It calculates:

   * The overall CGPA (all semesters combined)
   * The last 2 years’ CGPA (based on semesters 5–8 only)
6. The results are displayed and saved to a text file.

---

## 🧮 Grade Point Mapping (4.0 Scale)

| Grade | Point |
| ----- | ----- |
| A+    | 4.00  |
| A     | 3.75  |
| A-    | 3.50  |
| B+    | 3.25  |
| B     | 3.00  |
| B-    | 2.75  |
| C+    | 2.50  |
| C     | 2.25  |
| D     | 2.00  |
| F     | 0.00  |

---

## 🛠 Requirements

* Python 3.x
* No external libraries needed — just run the script in any terminal or command prompt.

---

## 🚀 Getting Started

1. Clone the repository:

```bash
git clone https://github.com/your-username/cgpa-calculator.git
cd cgpa-calculator
```

2. Run the script:

```bash
python cgpa_calculator.py
```

3. Follow the on-screen instructions.

---

## 📂 Output Example

```text
=== Results ===
Overall CGPA: 3.48
Last 2 Years CGPA (Sem 5–8): 3.65
Saved to cgpa_results.txt
```

---

## 📘 Notes

* You can press `Ctrl + C` anytime to stop the program.
* Make sure to enter at least one valid grade and credit to get a CGPA.
* The credit hour values range from 0 to 4 (with intermediate values like 0.5, 1.5, etc.).

---

## 💡 Ideal Use Cases

* Students tracking academic progress
* University departments providing GPA calculators
* Developers learning how to write menu-driven Python programs

---

## 📄 License

This project is open-source and free to use under the MIT License.

---

Let me know if you want this description converted into a `README.md` file with Markdown formatting.
