# Soccer Run Clustering

This repository applyies **unsupervised clustering** to **soccer running data**
to identify common movement patterns across players and sessions.

The focus is on preprocessing running metrics, clustering observations based on movement
characteristics, and interpreting the resulting clusters in a soccer performance context.

## Goals
1. **Preprocess soccer running data** and select relevant movement variables.
2. **Apply clustering techniques** to group similar running profiles.
3. **Visualize cluster structure** using summary plots and feature comparisons.
4. **Interpret clusters** in terms of player movement demands and patterns.

## Data
- **Source:** Soccer run / tracking data
- **Unit of analysis:** Player-session or run-level observations
- **Typical variables:**  
  - Total distance  
  - High-speed running distance  
  - Sprint distance / count  
  - Acceleration or velocity metrics (as available)

If the dataset is not included, see `data/README.md` for instructions.

## Methods
- **Approach:** Unsupervised learning
- **Clustering methods:**  
  - Distance-based clustering (e.g., k-means or similar, as implemented)
- **Preprocessing:**  
  - Feature selection  
  - Scaling / normalization
- **Evaluation:**  
  - Cluster inspection and interpretability (not predictive accuracy)

## Outputs
- Cluster assignments for running profiles
- Visual summaries of cluster characteristics
- Interpretation of movement patterns represented by each cluster

## How to Run
1. Clone or download this repository.
2. Ensure the dataset is available at `data/run_data.csv`.
3. Open and run:
   - `notebooks/Soccer_Run_Clustering.ipynb`

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib / seaborn
- scikit-learn

## Notes
It explores **structure in running data**, not performance quality or tactical effectiveness.
Clusters represent **similar movement profiles**, not player ability.
