# Exploring Knot Theory and Its Application to DNA Topology

## Overview

This repository is dedicated to exploring the intersection of **mathematics** and **biology** through the lens of **knot theory**. By leveraging mathematical tools such as the **Homfly polynomial**, **Dowker notation**, and **tangle diagrams**, this project provides insights into **DNA topology**, including phenomena like supercoiling, recombination, and enzyme mechanisms.

### Key Highlights:
- Implementation of algorithms to compute the **Homfly polynomial** using Dowker notation.
- Exploration of **tangle theory** and its relevance to DNA behavior.
- Mathematical modeling of DNA topological changes driven by enzymes.

---

## Objectives

- **Mathematical:** Develop and implement algorithms to calculate knot invariants such as the Homfly polynomial for a variety of knots and links.
- **Biological:** Apply knot theory concepts to analyze and model DNA topology, focusing on supercoiling and recombination.
- **Computational:** Create efficient and scalable computational methods for studying complex knots and tangles.

## Features

### 1. **Homfly Polynomial Calculator**
- A recursive algorithm for computing the Homfly polynomial for any given knot or link.
- Inputs include Dowker notation and crossing orientations.
- Results validated against manual calculations and known examples.

### 2. **Tangle Theory Exploration**
- Definition and manipulation of tangles, including:
  - (0,0)-type tangles
  - Rational tangles
  - Exceptional tangles
- Analysis of tangles as components of knots and links.

### 3. **Biological Applications**
- Modeling DNA recombination and supercoiling using knot and tangle theory.
- Understanding the role of topoisomerases and recombinases in modifying DNA topology.

## Usage

### **1. Computing the Homfly Polynomial**
Run the `homfly_calculator.py` script:
```bash
python scripts/algorithms/homfly_calculator.py --input examples/trefoil.txt
```

### **2. Visualizing Knot Structures**
Generate a visualization for a knot or tangle diagram:
```bash
python scripts/visualization/plot_knot.py --input examples/figure8_knot.txt
```

### **3. Tangle Analysis**
Perform an analysis of tangle properties:
```bash
python scripts/algorithms/tangle_analysis.py --tangle example_tangle.json
```



## Future Work

- Extend the Homfly polynomial algorithm to handle larger and more complex knots.
- Explore additional biological applications, including chromatin organization and knot-like structures in proteins.
- Incorporate machine learning methods to predict knot properties from diagram inputs.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## Contact
For any questions or contributions please contact: s-mohammed.elboghdadi@zewailcity.edu.eg 
