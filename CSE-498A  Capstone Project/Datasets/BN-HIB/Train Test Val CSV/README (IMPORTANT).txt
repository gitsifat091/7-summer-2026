
Choice Column:

The Choice column functions as the Label column. Each value in this column represents the final categorical label assigned to an entry.

The following mappings apply:

Targeted → Hate

Harmless → Benign

Provocative → Inflammatory

These labels are authoritative and should be treated as the ground truth for classification tasks.



Class Column:

The Class column is not a label. Instead, it is used for analytical purposes.

Its primary function is to:

Determine the language distribution within each class

Enable breakdowns and comparisons of linguistic usage across different classes

The Class column should be used strictly for analysis and reporting, not for model supervision or labeling.