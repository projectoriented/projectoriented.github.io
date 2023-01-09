---
title: "Partisan Clustering of Categories in Enacted Bills"
date: 2023-01-08T12:48:11-08:00
tags:
    - bipartisan
    - bills
    - enacted
categories:
    - politics
keywords:
    - democrat
    - republican
---

## Of all the enacted bills in congress 113 - 117, which party is the original sponsor and in what category?
![Enacted bills](/images/Figure_1.png)

Data is fetched from the ProPublica API.

At first glance, the curvature of the horizontal bars indicate that the Republican party had greater influence in enacting bills to their favor in Congress 114 and 115. It is largely due to the fact that they controlled both chambers of Congress. Therefore, we can see similar counts of enacted bills where there is overlap of interests between the two parties of those years.

| Congress | Date | Senate Majority | Senate President | House Majority | House Speaker |
| -- | -- | -- | -- | -- | -- |
| 113 | 2013-01-03 to 2014-12-06 | D | Joe Biden (D) | R | Joe Boehner (R) |
| 114 | 2015-01-06 to 2017-01-03 | R | Joe Biden (D) | R | Paul Ryan (R) |
| 115 | 2017-01-03 to 2019-01-03 | R | Mike Pence (R) | R | Paul Ryan (R) |
| 116 | 2019-01-03 to 2021-01-03 | R | Mike Pence (R) | D | Nancy Pelosi (D) |
| 117 | 2021-01-03 to 2023-01-03 | D | Kamala Harris (D) | D | Nancy Pelosi (D) |

Notes:
1. Use the max value of co-sponsors for a bill as the sole delegate vs. using the sole sponsor. Could be interesting to see which major party supports the bill vs. the person who drafted it.