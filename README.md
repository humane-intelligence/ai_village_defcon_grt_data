# AI Village Defcon Dataset

In this respository is the dataset from the AI Village red teaming competition, held at [DEFCON 31](https://aivillage.org/defcon31/). In the .zip containing the data is a json file. 

**To read the .json file into a python notebook, please use this code snippet:**

```python

import pandas as pd 
import numpy as np

data = pd.read_json("/ <insert your file path here> /anonymised_AIV.json")

```

This dataset is also available on Hugging Face at: [`humane-intelligence/defcon34-ai-village-redteam`](https://huggingface.co/datasets/humane-intelligence/defcon34-ai-village-redteam).

## **Data Description:**

| Column | dtype | total count | unique count |
|---------|---------|---------| ---------|
| category_name    | object   | 17309   | 6 |
| challenges_name    | object   | 17309   | 21   |
| contestant_message    | object   | 17309   | 21 |
| conversation   | object   | 17309   | 17246 |
| submission_message    | object   | 17309   | 1 |
| user_justification   | object   | 17309   | 17246 |
| submission_grade   | object   | 17309   | 3 |
| conversation_length    | int64   | 17309  | N/A |
