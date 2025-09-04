# OSPP 2025 @ Kmesh Community  
## Project Summary  
**Project:** *Kmesh eBPF Unit Test Framework Enhancement*

---

## My OSPP Journey

My OSPP journey began with exploring Kmesh, a high-performance, low-overhead service mesh data plane based on **eBPF** and the programmable Linux kernel.

When writing eBPF programs, validating their functionality typically requires compiling and then running black-box tests. This approach is inefficient and heavily dependent on the test author’s skill. Inspired by Cilium, we introduced a dedicated eBPF unit test framework for Kmesh.

At the current stage, the framework has been built. My main work focused on designing and implementing comprehensive unit tests for eBPF programs such as **sendMsg** and **cgroup**.

This process involved mastering networking fundamentals, understanding eBPF internals, and collaborating with the community to ensure the test framework is practical, reliable, and extensible.

I will also worked on integrating these unit tests into GitHub Actions, making them part of the CI pipeline with coverage reports, ensuring that every contribution to Kmesh is continuously validated.

---

## Contribution List (Pull Requests)

- [Unit tests for Kmesh eBPF sendMsg program](https://github.com/kmesh-net/kmesh/pull/1452)  
- [Unit tests for Kmesh eBPF cgroup_sock program](https://github.com/kmesh-net/kmesh/pull/1453)  
- [Unit tests for Kmesh eBPF cgroup_skb program](https://github.com/kmesh-net/kmesh/pull/1474)  
---

## Summary & Outlook

This OSPP experience has been a **valuable period of growth** for me. It was not just a technical exercise; it allowed me to deeply experience the **charm of open source**.

From my initial confusion when facing a large codebase to being able to independently design and contribute code, every step was made possible with the **community's help**. Open discussions, rigorous code reviews, and selfless knowledge sharing—these are the **cornerstones of open-source collaboration**. They've transformed me from a mere code user into a **contributor**.

Although OSPP is coming to an end, this is just the **beginning of my open-source journey**.