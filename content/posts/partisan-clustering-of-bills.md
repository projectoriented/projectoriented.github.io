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

## Which party is the original sponsor for enacted bills between congress 113 to 117?
![Enacted bills](/images/Figure_1.png)

Data is fetched from the ProPublica API.

At first glance, the counts of enacted bills from the Republican party are greater for most categories than for the Democratic party. This is especially clear in the 114th and 115th Congress which is no surprise at all because Republicans controlled both chambers of Congress in those years. Separately, we can see when both parties have overlapping interests, e.g. 'Armed Forces and National Security' or 'Government Operations and Politics', there is a push for bills to reach their mature age. It should be a good thing when there is agreement between the parties but in the example categories I mentioned, it might be concerning. I would like to see more activity in 'Transportation and Public Works' and 'Environmental Protection' and 'Housing and Community Development', and others pertaining to improving the livelihood, longevity, and convenience of residents in the US.

| Congress | Date | Senate Majority | Senate President | House Majority | House Speaker |
| -- | -- | -- | -- | -- | -- |
| 113 | 2013-01-03 to 2014-12-06 | D | Joe Biden (D) | R | Joe Boehner (R) |
| 114 | 2015-01-06 to 2017-01-03 | R | Joe Biden (D) | R | Paul Ryan (R) |
| 115 | 2017-01-03 to 2019-01-03 | R | Mike Pence (R) | R | Paul Ryan (R) |
| 116 | 2019-01-03 to 2021-01-03 | R | Mike Pence (R) | D | Nancy Pelosi (D) |
| 117 | 2021-01-03 to 2023-01-03 | D | Kamala Harris (D) | D | Nancy Pelosi (D) |

Notes:
1. Use the max value of co-sponsors for a bill as the sole delegate vs. using the sole sponsor. Could be interesting to see which major party supports the bill vs. the person who drafted it.

Ensuing questions:
1. What does a category entail? This includes: names of the committees, and title of the enacted bill.