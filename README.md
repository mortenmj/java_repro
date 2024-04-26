To reproduce:


```
bazel mod deps --lockfile_mode=update
bazel run @unpinned_maven//:pin
```
