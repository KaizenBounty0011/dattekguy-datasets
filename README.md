# dattekguy-datasets

Practice datasets for the **dattekguy** YouTube data-analysis series — realistic
(but 100% fake) company CSV files. Every video in the series analyzes one of
these companies as a workplace scenario.

▶️ Watch the series: [DatTekGuy on YouTube](https://www.youtube.com/@DatTekGuy-root)

## The companies

| Folder | Company | Industry |
|---|---|---|
| `payflow-fintech/` | PayFlow | Fintech / payments app |
| `trustbank/` | TrustBank | Retail bank (8 branches) |
| `deltaoil/` | DeltaOil | Oil company (6 rigs) |
| `ledgerpro-audit/` | LedgerPro | Audit / financial services firm |
| `smithgrey-lawfirm/` | Smith & Grey | Law firm |
| `citycare-hospital/` | CityCare | Hospital |
| `freshmart-retail/` | FreshMart | Supermarket chain (6 stores) |
| `govserve-agency/` | GovServe | Government agency |

## How to load a file (Python / Google Colab)

```python
import pandas as pd

url = "https://raw.githubusercontent.com/KaizenBounty0011/dattekguy-datasets/main/freshmart-retail/sales.csv"
df = pd.read_csv(url)
df.head()
```

Swap the folder/file for any dataset in the tables above — every video's
description links the exact files it uses.

## Notes

- All names, companies, accounts and amounts are **fictional**, generated with a
  seeded script. Any resemblance to real people or companies is coincidental.
- Amounts are in naira (₦); cities and states are Nigerian for local flavor.
- Some files contain deliberately planted anomalies for the fraud-detection
  episodes — finding them is the point. 🕵️
