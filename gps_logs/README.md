# GPS LOGS

```
import pandas as pd

column_names = ["vid","route","ts","lat","lon","speed"]

csv_path = "https://github.com/uic-kmitl/GPS101/blob/main/gps_logs/b_2022-10-20.csv?raw=true"

df = pd.read_csv(csv_path, names = column_names)
```
