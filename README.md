# Pittsburgh's Best Neighborhood

**Team:** Lucky Number Seven
**Canvas Group Number:** Group 7

**Members:**
- Goldium Wu — GOW4@pitt.edu
- Eden Brunner — EDB67@pitt.edu
- Helene Yao — helenemyao@gmail.com (hmy8@pitt.edu)

> *A data analysis of which Pittsburgh neighborhood is the "best," using [Western Pennsylvania Regional Data Center](https://data.wprdc.org/).*

**What is the best neighborhood in Pittsburgh?**

"Best" is subjective, so we decided the best neighborhood in Pittsburgh is a culmination that balances three factors:

1. **Quality of life** — is it a pleasant place to live? Represented by green space per neighborhood division.
2. **Safety** — can residents feel secure going about their day? Counted by the frequently of crime that occurs in a neighborhood on a daily basis.
3. **Accessibility** — can people get around, get to work, and reach what they need?

## Sub-metric Data Sources

- [City of Pittsburgh Parks](https://data.wprdc.org/dataset/parks1)
- [Pittsburgh Regional Transit Stops](https://data.wprdc.org/dataset/prt-of-allegheny-county-transit-stops)
- [Pittsburgh Police Arrests](https://data.wprdc.org/dataset/pbp_arrest_data_2024_2025)
---

## Results:
`notebooks/combined_analysis.ipynb` 

---

## How to Run

1. Clone this repo:
   ```bash
   git clone [repo URL]
   cd [repo folder]
   ```
2. Install dependencies:
   ```bash
   pip install pandas matplotlib openpyxl numpy
   ```
3. Download the datasets from the WPRDC links in the table above and place the CSVs in the `data/` folder.
4. Open the notebooks in Jupyter:
   ```bash
   jupyter notebook
   ```
5. Run each individual sub-metric notebook first, then run `combined_analysis.ipynb` to see the final ranking.

---
