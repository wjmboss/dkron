---
title: Executors
weight: 2
---

## Executors

Executors plugins are the main mechanism of execution in Dkron. They implement different "types" of jobs in the sense that they que perform the most diverse actions on the target nodes.

For example, the built-in `shell` executor, will run the indicated command in the target node.

New plugins will be added, or you can create new ones, to perform different tasks, as HTTP requests, Docker runs, anything that you can imagine.

Refer to the API documentation for [params accepted by the `shell` executor](https://dkron.io/usage/api/#executor-shell).
