# Pittsburgh's Best Neighborhood

**Team:** Lucky Number Seven

**Members:**
- Goldium Wu — GOW4@pitt.edu
- Eden Brunner — EDB67@pitt.edu
- Helene Yao — helenemyao@gmail.com

> *A data-driven investigation into which Pittsburgh neighborhood deserves the title of "best," using [Western Pennsylvania Regional Data Center](https://data.wprdc.org/).*

> **What is the best neighborhood in Pittsburgh?**

"Best" is subjective, so the first thing our team had to do was define it. We decided the best neighborhood in Pittsburgh is a culmination that balances three factors:

1. **Quality of life** — is it a pleasant place to live?
2. **Safety** — can residents feel secure going about their day?
3. **Accessibility** — can people get around, get to work, and reach what they need?

Each of us analyzed a WPRDC dataset to measure it and produced a normalized score per geographic area. In the combined notebook, we average the three scores with equal weight to produce a single overall ranking.

## Data Sources

All data comes from the [Western Pennsylvania Regional Data Center (WPRDC)](https://data.wprdc.org/).

- [City of Pittsburgh Parks](https://data.wprdc.org/dataset/parks1)
-
- 
---

## The Result

🏆 **Best neighborhood in Pittsburgh:**

See `notebooks/combined_analysis.ipynb` for the full data-driven argument and visualizations.

---


## How to Run

1. Clone this repo:
   ```bash
   git clone [repo URL]
   cd [repo folder]
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the datasets from the WPRDC links in the table above and place the CSVs in the `data/` folder.
4. Open the notebooks in Jupyter:
   ```bash
   jupyter notebook
   ```
5. Run each individual sub-metric notebook first, then run `combined_analysis.ipynb` to see the final ranking.

---
