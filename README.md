# MODELLING_SPREAD_OF_MENTAL_HEALTH_DISEASES
This is a project that builds upon existing model frameworks to model the spread of anxiety in a closed social network. 

# ABSTRATCT
Emotional contagion is the phenomenon by which individuals’ emotional states influence an spread to others, and plays a critical role in shaping mental health dynamics within social networks. This paper explores the interplay between emotional contagion and mental health awareness through the lens of evolutionary game theory. By extending the classical SIR framework to a SIRA (Susceptible–Infected–Recovered–Active) model, we simulate how emotional states and awareness behaviors propagate in both fully connected and network-constrained populations. Our model incorporates differential equations and a discrete network-based simulation modeling roles of peer support, natural recovery, and susceptibility to distress. Through over 300 simulations, we analyze how key parameters, including support effectiveness, self-recovery, and network structure influence emotional outcomes. Findings suggest that strong recovery and support mechanisms significantly buffer against emotional contagion, even when exposure is high, whereas weak support structures lead to persistent emotional distress and systemic strain. This research offers a useful framework for understanding the spread of emotional states in social systems and provides actionable insights for designing interventions that promote emotional resilience, mental health awareness, and sustainable support networks.

# FILE STRUCTURE 
1. Graphs- Contain a sample of graphs 
2. Final Paper- Final draft of the paper submitted for the class
3. Code - Jupyter notebook containing the main simulation code. 

# Running the code

1.**Clone the repo:**
```bash
git clone https://github.com/arses-ui/Netwroks.git
cd Netwroks
```
2. **Create and activate a virtual environment 
2. **Install required packages:**
```bash
pip install -r requirements.txt
```
3. **Open the Notebook and run the simulation:**
```bash
jupyter notebook NETWORKS.ipynb
```
# Dependencies

1. Python 3.8+
2. NumPy
3. Matplotlib
4. NetworkX

# Authors and Contributions 
**Arses Prasai** - Modeling, Simulatioon Development, Report Writing 
**Marcos Cebrian** - Modeling, Simulatioon Development
**Licheng Wang** - Literature Analysis, Report Writing

**Course:** Evolutionary Game Theory (MATH 30.04), Spring 2025 
