---
title: "Jupyter"
date: 2023-06-04T13:35:17-04:00
draft: False
---
 Starting of project and launching Jupyter Notebook, Use following in `Anaconda Prompt`

{{< highlight text >}}
 cd working_dir
 mkdir project_folder
 conda create --prefix ./env pandas numpy matplotlib scikit-learn jupyter
 conda  activate ./env
 jupyter notebook
{{< /highlight >}}

# Jupyter CheetSheet

## Importing libraries

{{< highlight text >}}
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import sklearn
{{< /highlight >}}

## Cell Chnaging

* `Shift + Enter` to Run
* `Esc` to change from Edit to Command mode (Blue)
* `Enter` to get back to Edit mode (Green)

### Markdown

* `Esc + M` go to markdown mode.

### Code

* `Esc + Y` to change cell to code.
