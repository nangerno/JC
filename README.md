# How to use parquet

```python
import pandas as pd

df = pd.read_parquet("test-00000-of-00001.parquet")
df.to_json("test.jsonl", orient="records", lines=True)
```
