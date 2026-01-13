
# Teaching-Learning-Based Optimization (TLBO) Project

This project implements the **Teaching-Learning-Based Optimization (TLBO)** algorithm for solving engineering optimization problems.  
It is written in Python and designed to be **modular, easy-to-run, and reproducible**.

---

## Project Features
- Implements **Teacher Phase** & **Learner Phase**
- Population initialization and fitness evaluation
- Convergence curve plotting (linear and log scale)
- Example objective function: Sphere function (minimize f(x, y) = x² + y²)
- Clean, modular Python code with detailed comments
- Optional advanced features: Hybrid TLBO with PSO/GA, Multi-objective TLBO

---

## Installation

1. Clone this repository:

```bash
git clone https://github.com/elbob28/TLBO-Project.git
cd TLBO-Project
```

2. Install required Python packages:

```bash
pip install -r requirements.txt
```

**Dependencies:**
- numpy>=1.21.0
- pandas>=1.3.0
- scikit-learn>=0.24.0
- matplotlib>=3.4.0
- scipy>=1.7.0

---

## How to Run

1. Run the main script:

```bash
python main.py
```

2. Output:
- **Console:** Best solution found and its fitness value
- **Plot:** Convergence curve saved as `convergence_plot.png`

3. Example expected output (for Sphere function with 2 variables):

```
Best Solution Found: [~0.0, ~0.0]
Best Fitness Value: ~0.0
```

- Convergence plot shows how TLBO approaches the optimal solution over iterations.

---

## Visualization

Here’s an example of the convergence curve generated:

![Convergence Curve](convergence_plot.png)

---

## Advanced Features (Optional)

- **Hybrid TLBO with PSO or GA:** Combines TLBO with Particle Swarm Optimization or Genetic Algorithms to improve convergence on complex problems.
- **Multi-objective TLBO:** Handles multiple conflicting objectives simultaneously, useful for engineering design trade-offs.

For more details, see `advanced_features.md`.

---

## AI Assistance

This project was enhanced using **AI-powered tools**:

- **GitHub Copilot**: Code generation and modularization
- **DALL·E / MidJourney**: Image generation for presentation
- **ChatGPT**: Writing README and documentation, slide explanations
- **Other AI tools**: Video editing and slide enhancement

---

## Author

**Mohamed Ayoub Ben Ayed**

---

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
