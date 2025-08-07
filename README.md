# Text-To-Maths-Solver-Using-LLMMathChain
# 🧮 Text-to-Math Problem Solver

A smart assistant that converts natural language math problems into executable math expressions and provides step-by-step solutions. Built using **LangChain**, **Groq LLM**, and **Python math engines**, this tool helps solve word-based arithmetic, algebra, and other math problems via plain English input.

## 🚀 Features
- 🧠 Understands math problems in plain English
- 🔢 Converts text to equations using LLMs (Groq/OpenAI)
- 🧮 Executes and solves using Python or LangChain's `LLMMathChain`
- 📊 Supports arithmetic, algebra, percentages, age problems, and more
- 💡 Planned support for step-by-step explanations
💡 Example Usage
Input:
A bag contains 3 red balls and 5 blue balls. What is the probability of picking a red ball?

Output:
There are 3 red balls out of 8 total.
Probability = 3/8 = 0.375

Input:
What is 25% of 640?

Output:
25% of 640 is 160.

📁 File Structure
bash
Copy
Edit
.
├── app.py                  # Main Python/Streamlit app
├── solver.py               # Core logic for text-to-math solving
├── examples/               # Sample input-output problems
├── README.md               # This file

## 🧠 Tech Stack
| Component         | Description                          |
|------------------|--------------------------------------|
| LangChain        | LLM workflow framework               |
| ChatGroq         | Fast language model for reasoning    |
| LLMMathChain     | LangChain tool for math execution    |
| Python Math Libs | `eval()`, `sympy`, `numexpr`         |
| Streamlit        | Web UI for user interaction (optional) |

## 📦 Installation
```bash
git clone https://github.com/yourusername/text-to-math-solver.git
cd text-to-math-solver
pip install -r requirements.txt

