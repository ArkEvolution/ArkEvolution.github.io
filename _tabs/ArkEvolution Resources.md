---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
title: ArkEvolution Benchmark
permalink: /ArkEvolution-Resources/
nav_title: Benchmark
---

## Benchmark

> The benchmark captures the code change records for each version upgrade task.
> For each task, we analyzed the code change records between the starting version
> and the target version. Each upgrade task is formally defined as a 7-tuple:
> `Ui+j = <Vi, Vi+j, Vi', Vi+j', Delta1, Delta2, M>`, where `Vi` and `Vi'`
> represent the ArkTS and JS/TS software versions before evolution, respectively;
> `Vi+j` and `Vi+j'` represent the ArkTS and JS/TS software versions after
> evolution, respectively; `Delta1` denotes the code changes introduced by syntax
> adaptation between `Vi` and `Vi'`; `Delta2` denotes the evolutionary code
> changes between JS/TS versions `Vi` and `Vi+j` performed by developers; and `M`
> denotes the mapping relationships. Based on the code change entities identified
> in `Delta2`, including classes, functions, interfaces, and global variables,
> `M` defines which corresponding entities in the ArkTS version `Vi'` require
> synchronized evolution.
{: .prompt-tip }

[**Download the ArkEvolution benchmark**](/ArkEvolution/benchmark/benchmark.zip)
