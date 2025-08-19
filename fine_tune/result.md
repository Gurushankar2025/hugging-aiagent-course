# Results – Resume Screening Model

## 1. Evaluation Metrics

| Dataset     | Accuracy | Precision | Recall | F1-Score | Loss |
|------------|---------|----------|--------|----------|------|
| Evaluation | 1.0     | 1.0      | 1.0    | 1.0      | 0.0003 |
| Test       | 1.0     | 1.0      | 1.0    | 1.0      | 0.0006 |

> All metrics were calculated on evaluation and test sets. The model shows perfect scores due to the structured dataset (small/custom dataset).

---

## 2. Loss Curve (Training & Evaluation)

| steps         | 50    | 100    | 150    | 200    |     
|-----------------|------|------|------|------
| Training Loss   | 0.33 | 0.024 | 0.0043 | 0.0027 |
| Evaluation Loss | 0.06 | 0.0046 | 0.0022 | 0.0016 |

> The loss steadily decreases during training. Evaluation loss is very close to training loss. 

---

## 3. Evaluation Accuracy Curve

| steps             | 2    | 4    | 6    | 8    |     
|------------------|------|------|------|------|
| Evaluation Accuracy | 1.0  | 1.0  | 1.0  | 1.0  |


> The evaluation accuracy from the first epoch is already 1.0, forming a straight line throughout training.

#### (I have trained the model with this dataset multiple times, each time with a simple tweak like stratifying the data, shuffle etc, and the provided results are from one of the curves from multiple curves on multiple runs. To other curves(here lines graph check the assets folder) )
---

## Confusion Matrix

| Actual \ Predicted | Reject | Hire |
|------------------|--------|------|
| Reject            | 20     | 0    |
| Hire              | 0      | 105  |
This matches the numbers shown in the heatmap. using test data.

**Related images are presented in the assets folder**

