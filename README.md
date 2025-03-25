# AVL-analysis

# Music Data Structures Performance Comparison

## Overview

This project compares the performance of a **Binary Search Tree (BST)** and an **AVL Tree** when inserting and searching over a dataset of classic hit songs. Using a CSV file with over 15,000 records, it measures insertion time, search time, and tree height across varying dataset sizes.

## Repository Structure

- ClassicHit.csv 
- Dataset of music metadata main.py 
- Script implementing BST, AVL, performance tests, and report generation desempenho_arvores.png 
- Performance comparison charts musicas_por_ano.png # Chart of songs released every 3 years performance_report.txt 
- Text summary of dataset statistics Relatório Arvores.pdf 



# This file


## Getting Started

### Prerequisites

- Python 3.10+
- pip

### Installation

```
git clone https://github.com/yourusername/music-tree-performance.git
cd music-tree-performance
pip install pandas matplotlib
```

# Usage
Run the main script to perform all tests and generate outputs:

``` python main.py ```


# Outputs
File	Description
desempenho_arvores.png - Comparative plots for insertion time, tree height, and search time
musicas_por_ano.png	- Bar chart showing number of songs released every 3 years
performance_report.txt	- Dataset statistics: genre distribution, average popularity, correlations


# Results Summary
Insertion Performance: BST inserts faster (no balancing), but height grows quickly.

Tree Height: AVL maintains a much smaller height, ensuring balance.

Search Performance: AVL provides faster searches due to shallower structure.

# Customization
Change the key attribute in main.py by updating key_attribute in time_operations() and time_search_operations().

Adjust dataset sizes via the subset_sizes list.

# Authors
Daniel Mangabeira Correia


# 📄 License
This project is licensed under the MIT License.

#  Acknowledgements
Dataset courtesy of ClassicHit music metadata.
