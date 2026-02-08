# PINN-ML-Learning

My 10-week structured learning path to master physics-informed neural networks 
for computational finance.

**Start Date:** February 3, 2026  
**Goal:** Be prepared to start independent research on barrier option pricing

## Learning Objectives

By the end of 10 weeks, I will be able to:
- [ ] Implement stochastic processes (Brownian motion, GBM)
- [ ] Derive and code Black-Scholes equation
- [ ] Build neural networks in PyTorch
- [ ] Compute second-order derivatives with autograd
- [ ] Implement physics-informed neural networks
- [ ] Price options using multiple methods (analytical, MC, PINN)

## Weekly Progress

### Week 1: Python Fundamentals + Probability ✓
- NumPy array operations
- Matplotlib visualization
- Normal and log-normal distributions
- Basic probability simulations

### Week 2: [In Progress / Not Started]
...

## Repository Structure

- `/weekX-topic/`: Jupyter notebooks and code for each week
- `/resources/`: Notes, formulas, reference materials
- `/images/`: Generated plots and visualizations

## Resources Used

**Video Courses:**
- Corey Schafer: Python, NumPy, Matplotlib
- ritvikmath: Probability and statistics
- QuantPy: Stochastic calculus and finance
- Sentdex: Neural networks from scratch
- Python Engineer: PyTorch tutorials

**Books:**
- (List as you use them)

## Contact

GitHub: @YOUR_USERNAME  
(Optional: Link to LinkedIn, personal website)
```

**Save this file.**

---

### **STEP 5: Create .gitignore (Important!)**

**Your repository should already have a .gitignore file. Open it and make sure it includes:**
```
# Jupyter Notebook checkpoints
.ipynb_checkpoints/
*/.ipynb_checkpoints/*

# Python cache
__pycache__/
*.py[cod]
*$py.class

# Virtual environments
venv/
env/
ENV/

# Large data files (don't upload large datasets)
*.csv
*.h5
*.pkl
data/
datasets/

# OS files
.DS_Store
Thumbs.db

# Large output files
*.mp4
*.mov

# Personal notes (if you want them private)
personal-notes.md
