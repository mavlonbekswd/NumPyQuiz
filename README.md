
# NumPy Quiz Practice Pack
### 60 Real-World Questions — Easy · Medium · Hard

---

All files are **Jupyter notebooks (`.ipynb`)**. Each notebook has a
**markdown cell** (the scenario + tasks + expected output) and a **code cell**.

1. **Open a question notebook** from `Questions Only/` in Jupyter / VS Code.
2. **Read the scenario**, tasks, and expected output in the first (markdown) cell.
3. **Write your solution** in the code cell, under `# ── write your solution below ──`.
4. **Run the cell** (Shift+Enter) to verify your output.
5. **Compare with the solved notebook** in `Solved Answers/` — same name with `_solved` suffix.

> Tip: Try to solve each question fully before looking at the answer.
> Even if your output matches, read the `# ── WHY ──` notes for deeper understanding.

### Launching Jupyter
```bash
cd "NumPy Quiz"
jupyter notebook        # or: jupyter lab
```
On this machine the Python with NumPy/Pandas/Matplotlib/Seaborn is
`/opt/anaconda3/bin/python3`, so launch via `/opt/anaconda3/bin/jupyter notebook`
if `jupyter` is not on your PATH.

---

## Recommended Study Order

### Phase 1 — Foundation (Easy 01–10)
Start here if you are reviewing after finishing NumPy lessons.

| File | Topic | Theme |
|------|-------|-------|
| easy_01_arrays_call_center | Array creation, indexing | Call Centre |
| easy_02_indexing_hotel | 2-D slicing | Hotel |
| easy_03_shape_university | shape, ndim, size, dtype | University |
| easy_04_reshape_grocery | reshape, flatten | Grocery |
| easy_05_copy_view_wedding | copy vs view | Wedding |
| easy_06_arithmetic_restaurant | element-wise ops | Restaurant |
| easy_07_arange_linspace_taxi | arange, linspace, zeros, ones | Taxi |
| easy_08_slicing_ecommerce | 2-D axis slicing | E-commerce |
| easy_09_minmax_salary | min, max, sum, cumsum | Salaries |
| easy_10_mean_median_youtube | mean, median, outlier effect | YouTube |

### Phase 2 — Core Techniques (Easy 11–20)

| File | Topic | Theme |
|------|-------|-------|
| easy_11_boolean_mask_gym | Boolean masking | Gym |
| easy_12_filter_football | Compound filtering | Football |
| easy_13_stack_travel | hstack, vstack, concat | Travel |
| easy_14_random_support | randint, seed | Support |
| easy_15_sort_stock | sort, argmax, argmin | Stock |
| easy_16_where_university | np.where | University |
| easy_17_broadcast_grocery | broadcasting scalar + vector | Grocery |
| easy_18_argmax_callcenter | argmax, argmin (2-D) | Call Centre |
| easy_19_iter_restaurant | nditer, ndenumerate | Restaurant |
| easy_20_fancy_index_wedding | fancy indexing | Wedding |

### Phase 3 — Intermediate (Medium 01–10)

| File | Topic | Theme |
|------|-------|-------|
| medium_01_boolean_grocery | masking + stats pipeline | Grocery |
| medium_02_fancy_ecommerce | argsort + fancy indexing | E-commerce |
| medium_03_broadcast_hotel | broadcasting (2-D × 1-D) | Hotel |
| medium_04_reshape_callcenter | 3-D reshape + axis ops | Call Centre |
| medium_05_stack_employee | column_stack, vstack | Employee |
| medium_06_argsort_football | argsort, lexsort | Football |
| medium_07_random_taxi | choice, shuffle, permutation | Taxi |
| medium_08_normal_university | normal distribution | University |
| medium_09_std_restaurant | std, variance, CV | Restaurant |
| medium_10_percentile_salary | percentile, IQR, boxplot | Salary |

### Phase 4 — Advanced Analysis (Medium 11–20)

| File | Topic | Theme |
|------|-------|-------|
| medium_11_outlier_youtube | Z-score outlier detection | YouTube |
| medium_12_copy_view_gym | copy/view advanced | Gym |
| medium_13_iter_travel | nditer readwrite | Travel |
| medium_14_where_support | nested where, np.select | Support |
| medium_15_broadcast_sales | 3-D broadcasting + newaxis | Sales |
| medium_16_variance_stock | variance, daily % change | Stock |
| medium_17_uniform_booking | uniform distribution | Booking |
| medium_18_binomial_callcenter | binomial distribution | Call Centre |
| medium_19_poisson_restaurant | Poisson distribution | Restaurant |
| medium_20_searchsorted_catalog | searchsorted, tiered pricing | E-commerce |

### Phase 5 — Business Case Challenges (Hard 01–10)

| File | Topic | Theme |
|------|-------|-------|
| hard_01_callcenter_full_analysis | Full stats pipeline | Call Centre |
| hard_02_ecommerce_analysis | Broadcasting + masking + argsort | E-commerce |
| hard_03_university_distribution | Normal + percentile + cohort | University |
| hard_04_gym_segmentation | Tiering + group stats | Gym |
| hard_05_restaurant_revenue | 3-D broadcasting + heatmap | Restaurant |
| hard_06_hotel_occupancy | Masking + stacked bars | Hotel |
| hard_07_youtube_analytics | Z-score + engagement + scatter | YouTube |
| hard_08_football_performance | Lexsort + composite scoring | Football |
| hard_09_grocery_optimization | 3-D profit broadcasting | Grocery |
| hard_10_travel_pipeline | Revenue + VPN analysis | Travel |

### Phase 6 — Capstone Challenges (Hard 11–20)

| File | Topic | Theme |
|------|-------|-------|
| hard_11_salary_outlier | IQR + Z-score + boxplot | Salary |
| hard_12_stock_simulation | Random walk + VaR + drawdown | Stock |
| hard_13_support_sla | SLA breach + agent KPIs | Support |
| hard_14_taxi_revenue | Surge pricing + profit margin | Taxi |
| hard_15_wedding_budget | Table analysis + stacked bar | Wedding |
| hard_16_callcenter_shifts | Poisson + overtime model | Call Centre |
| hard_17_ecommerce_returns | Binomial returns + audit | E-commerce |
| hard_18_university_cohort | 3-D multi-year analysis | University |
| hard_19_distribution_simulation | Poisson+Binomial+Normal | Restaurant |
| hard_20_full_distribution_analysis | **CAPSTONE — all topics** | HR/Salary |

---

## How to Check Your Answers

1. Run your code cell in `easy_01_arrays_call_center.ipynb` (Shift+Enter).
2. Compare output to the **EXPECTED OUTPUT** in the question notebook's markdown cell.
3. Open the corresponding `_solved.ipynb` for the full solution + explanation.
4. Read the `# ── WHY ──` notes in the solved code cell — this is where most learning happens.

---

## NumPy Topics Coverage

| Topic | Question Numbers |
|-------|-----------------|
| Array creation | E01, E07 |
| Indexing + slicing | E01, E02, E08 |
| Shape, ndim, size | E03 |
| Reshape | E04, M04 |
| Copy vs View | E05, M12 |
| Arithmetic ops | E06 |
| arange / linspace | E07 |
| min / max / sum / cumsum | E09 |
| Mean + Median | E10, M11 |
| Boolean masking | E11, M01 |
| Filtering (compound) | E12 |
| Stacking + joining | E13, M05 |
| Random randint | E14 |
| Sorting basics | E15 |
| np.where | E16, M14 |
| Broadcasting (1-D) | E17, M03 |
| argmax / argmin | E18 |
| nditer / ndenumerate | E19, M13 |
| Fancy indexing | E20, M02 |
| argsort | M02, M06, H08 |
| np.lexsort | M06, H08 |
| Random: choice/shuffle/permutation | M07 |
| Normal distribution | M08, H03 |
| Standard deviation + variance | M09, M16 |
| Percentile + quartiles | M10, H01 |
| Outlier detection (IQR + Z-score) | M10, M11, H11 |
| Binomial distribution | M18, H17, H19 |
| Poisson distribution | M19, H16, H19 |
| Uniform distribution | M17 |
| searchsorted | M20 |
| Advanced broadcasting (3-D) | M15, H05, H09 |
| 3-D arrays + multi-axis ops | M04, H01 |
| np.select | M14, H02 |
| np.corrcoef | H20 |
| Visualisation (histogram) | M08, M09, M18, M19 |
| Visualisation (boxplot) | M10, H11 |
| Visualisation (line chart) | M16, H12 |
| Visualisation (heatmap) | H05 |
| Visualisation (scatter) | H07, H20 |
| Visualisation (stacked bar) | H06, H15 |

---

## Preparing for Pandas After NumPy

After completing this quiz pack you will be well prepared for Pandas because:

- **Boolean masking** in NumPy → `df[df["col"] > x]` in Pandas
- **axis=0/1** behaviour is identical in Pandas DataFrames
- **groupby** in Pandas mirrors per-group masking you practised here
- **np.where / np.select** → `pd.cut`, `pd.qcut`, `np.where` used inside Pandas
- **argsort + fancy indexing** → `df.sort_values()` + `.iloc[]`
- **percentile / quartile** → `df.describe()` and `df.quantile()`
- **Broadcasting** prepares you for vectorised column operations in Pandas
- **Stack/join** → `pd.concat`, `pd.merge`
- **np.corrcoef** → `df.corr()`

---

*NumPy Quiz Practice Pack — 60 questions · 20 Easy · 20 Medium · 20 Hard*
*Themes: Call Centre · Hotel · University · Grocery · E-commerce · Gym · Restaurant · Taxi · YouTube · Football · Travel · Salary · Support · Stock*

