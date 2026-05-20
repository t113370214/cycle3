# Variable Coding and Assumptions Notes

## 1. Variable Recoding Rules
Variables were recoded as binary (1 = success/exposed, 0 = failure/comparison) prior to analysis. Missing values (NaN) were excluded.

**Group Variable: `SadOrHopeless`**
* 1 (Exposed Group): Original code 1 (Yes) -> Recoded as `1`.
* 0 (Comparison Group): Original code 2 (No) -> Recoded as `0`.

**Response Variable: `CurrentCigaretteUse`**
* 1 (Success): Original codes 2 to 7 (1 or more days) -> Recoded as `1`.
* 0 (Failure): Original code 1 (0 days) -> Recoded as `0`.

## 2. Statistical Assumptions
* **Independence:** The YRBS 2007 dataset is assumed to be a random sample.
* **Large Sample Size:** The sample sizes for both groups heavily exceed the minimum requirement, satisfying the normality condition for the two-proportion z-test.