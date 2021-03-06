# Why?

To test different languages and environments, how they handle creating ten million objects with one instance variable (string "tere").

OOP is beautiful and a software engineer should be able to create objects without being concerned about memory or CPU time issues.


# Confirming the results

```bash
  cd benchmarks && ruby run-tests.py
```


# Results

![seconds](https://github.com/mxrguspxrt/TenMillionObjects/raw/master/charts/seconds.png "Seconds")
![megabytes](https://github.com/mxrguspxrt/TenMillionObjects/raw/master/charts/mb.png "Megabytes")


```
  Go used 158MB and ran 1 seconds.
  Crystal used 429MB and ran 1 seconds.
  Ruby used 933MB and ran 6 seconds.
  Python3 used 1688MB and ran 14 seconds.
  Python2 used 3802MB and ran 22 seconds.
```

I do recommend to take a look at https://crystal-lang.org


# Contributing

Make a PR and I merge.
