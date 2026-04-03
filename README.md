# Codtech-Task-4---Optimization-Model
This project applies linear programming using Python and PuLP to solve a business optimization problem. It determines the optimal production quantities of products to maximize profit under resource constraints. The notebook demonstrates problem formulation, solution, and key insights for decision-making.

# 📌 Optimization Model using Linear Programming

## 📖 Overview

This project demonstrates how to solve a real-world business problem using Linear Programming in Python. The goal is to determine the optimal production plan that maximizes profit while satisfying resource constraints.

## 🎯 Objective

* Maximize total profit from two products
* Use limited resources efficiently (labor and materials)
* Apply optimization techniques using Python

## 🛠️ Technologies Used

* Python
* PuLP (Linear Programming Library)
* Google Colab

## 📊 Problem Statement

A company produces two products:

* Product A (Profit = 40 per unit)
* Product B (Profit = 30 per unit)

### Constraints:

* Labor: 2A + B ≤ 100
* Material: A + B ≤ 80

The objective is to find the optimal values of A and B that maximize profit.

## ⚙️ Implementation Steps

1. Define the optimization problem
2. Create decision variables
3. Formulate the objective function
4. Add constraints
5. Solve using PuLP
6. Display optimal results

## 📈 Results

* Optimal number of Product A and Product B is calculated
* Maximum profit is achieved under given constraints
* Resources are utilized efficiently

## 💡 Insights

* Product A contributes more to profit, so it is prioritized
* Both constraints are fully utilized in the optimal solution
* Linear programming helps in efficient decision-making

## 🚀 How to Run

1. Open Google Colab
2. Install PuLP using:

   ```
   !pip install pulp
   ```
3. Run all cells in the notebook
4. View results and insights

## 📂 Project Structure

Optimization-Model/
│── optimization_model.ipynb
│── README.md

## 📌 Conclusion

This project shows how optimization techniques can be used to solve business problems effectively and improve decision-making using limited resources.

Author

Chandan M
