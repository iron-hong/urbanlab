---
title:  "How export my data using Stata"
categories: post
---


U can type:
```
sysuse auto, clear
```

Export varible make, price mpg and rep78 from 1 to 5
```
dataex make price mpg rep78 in 1/5
```

Copy these code and done
```
[CODE]
* Example generated by -dataex-. To install: ssc install dataex
clear
input str18 make int(price mpg rep78)
"AMC Concord"   4099 22 3
"AMC Pacer"     4749 17 3
"AMC Spirit"    3799 22 .
"Buick Century" 4816 20 3
"Buick Electra" 7827 15 4
end
[/CODE]
```


