# PerfKit Benchmarker Tutorials README

This is a place for landing PerfKitBenchmarker __tutorials__.  These tutorials
exist to help quickly demonstrate curated walk-throughs. The intent here is show
commonly used patterns of benchmarks, tests, and argument combinations to aid
rapid ramp-up for new users. Oftentimes, new users get stuck on which benchmarks
to run and/or which arguments to pass.

Lightweight conventions for organizing the tutorials:

*   Create a __directory__ for each tutorial. The directory name should clearly
    indicate the biases of the tutorial. For example, the first tutorial I
    created was in `networking_intro.gcp`.
*   The tutorial instructions/steps should be part of a __README&#46;md__ in the
    created directory.
*   __Images__ used in the README instructions should reside in a `img`
    directory under the tutorial directory.
*   __Static__ data used in the README instructions should reside in a `data`
    directory under the tutorial directory.
*   A demo script, named `demo.sh`, for easily running the tutorial can be
    placed alongside the README&#46;md.

Given all this, a sample structure for a tutorial might be:

```
PerfKitBenchmarker/
    tutorials/
        networking_intro.gcp/
            data/
            img/
            README.me
            demo.sh
```

---

## Tutorials Index

 Tutorial                    |  Created | Purpose
 --------------------------- | -------- | -------------------------------------
 [networking_intro.gcp][1]   | Jan 2020 | Show simple networking experiments on GCP for new users.
 xx.yy                | Jan 2020 | TBD

[1]: ./networking_intro.gcp

