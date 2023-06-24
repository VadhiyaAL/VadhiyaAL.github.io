---
title: "Pandas"
date: 2023-06-04T18:01:49-04:00
draft: False
---

## Dataframe

* Read CSV <br>
{{< highlight text >}}
df = pd.read_csv("filename.csv")
{{< /highlight >}}
* head()
{{< highlight html >}}
df.head(10)  --> Show first 10 raws.
{{< /highlight >}}
* Series
  {{< highlight html >}}
Series = pd.Series(["BMW", "Toyota", "Honda"])
{{< /highlight >}}
* Anatomy of a DataFrame
  ![Anatomy of a Dataframe](/2023-06-07-21-21-07.png)
* Export to CSV
  {{< highlight html >}}
  data.to_csv("filename.csv") 
  {{< /highlight >}}
  --> create a csv from dataframe stored in "data". 
  PS Will include the index column
  {{< highlight html >}}
  data.to_csv("filename.csv", index=False)     --> No index
  {{< /highlight >}}

## Describe data
