---
layout: post
title: ChIP-Seq Analysis Pipeline
---

## Experimental Setup

## Mapping Strategy

## Peak Calling

## Quality assessment
In order to assess whether the ChIP worked at all, we can generate a so called ['Fingerprint plot'](https://deeptools.readthedocs.io/en/develop/content/tools/plotFingerprint.html) with [deepTools](https://github.com/deeptools/deepTools).
(Even though I think I understand the origin of plot's name, I think it is not suiting.)

```{sh}
plotFingerprint -b chip.bam input.bam -o chip.fingerprint.svg
```

![Example Fingerprint plots from the deepTools docs](https://deeptools.readthedocs.io/en/develop/_images/QC_fingerprint.png)
