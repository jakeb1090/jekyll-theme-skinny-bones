---
layout: post
title: Jupyter notebooks
---

Next you can update your site name, avatar and other options using the _config.yml file in the root of your repository (shown below).

![_config.yml]({{ site.baseurl }}/images/config.png)

```df = pd.read_csv('../input/officer-involved-shooting-incidents_officer-involved-shooting-incidents-2017-forward_ois1.csv')
from datetime import datetime
#datetime.strptime('04-APR-18','%d,%b,%y')
df.sample(7)```