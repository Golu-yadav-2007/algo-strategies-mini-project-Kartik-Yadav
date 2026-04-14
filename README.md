
# Algorithmic Strategies for Logistics Optimization
**Course:** Analysis and Design of Algorithms (ADA)
**Project:** Lab Experiment - 1
**Developer:** Kartik Yadav

## 📌 Problem Context
In real-world logistics, decision-making and optimization are vital for efficient delivery systems. This project implements various algorithmic paradigms to solve problems like sorting tracking IDs, maximizing truck capacity, and optimizing delivery routes.

## 🧠 Algorithmic Strategies
* **Divide and Conquer:** Applied via QuickSort to handle large-scale tracking ID data processing.
* **Greedy Algorithms:** Used for Fractional Knapsack to maximize truck load profit where locally optimal choices lead to efficient solutions.
* **Dynamic Programming:** Essential for 0/1 Knapsack (Warehouse Storage) and Shortest Path computations (Route Optimization) involving overlapping subproblems.

## 🛠️ Setup & Usage
### Technical Requirements
* **Python:** ≥ 3.10 with venv
* **Libraries:** `matplotlib`, `numpy`, `time`, `memory_profiler`

### Setup Instructions
1. Initialize environment: `python -m venv .venv`
2. Activate: `.venv\Scripts\activate` (Windows) or `source .venv/bin/activate` (Mac/Linux)
3. Install: `pip install matplotlib numpy memory_profiler jupyterlab`

### Usage
Open `notebooks/algo_strategies_notebook.ipynb` in Jupyter or Google Colab to run the simulations and view performance plots.

## 📊 Summary Comparison
| Task | Strategy | Complexity | Practical Application |
| :--- | :--- | :--- | :--- |
| Sorting IDs | Divide & Conquer | $O(n \log n)$ | Logistics Data Sorting |
| Truck Load | Greedy | $O(n \log n)$ | Resource Allocation |
| Storage | Dynamic Programming | $O(n \cdot W)$ | Inventory Management |
| Routing | Dynamic Programming | $O(m \cdot n)$ | Shortest Path computations |

