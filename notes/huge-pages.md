# Understanding Linux huge pages

**Type:** Collaborative study

A collaborative report on virtual memory, translation overhead, and the trade-offs of larger pages.

## Attribution

The report and presentation credit Reza Ranjbar and Mohammadreza Omidian. Individual responsibilities are not specified in the supplied files, so this portfolio presents the work as collaborative.

## The core idea

Larger memory pages can cover more memory per address-translation entry. Their usefulness depends on the workload, allocation behaviour, hardware, and operating-system configuration.

## Two mechanisms

Explicit HugeTLB pages and Transparent Huge Pages are different Linux mechanisms. Their allocation, reservation, and reclaim behaviour should not be merged into one universal description. Consult the documentation for the kernel and application being used.

## Corrections to the original

The slides cite 10–30% improvement and a fourfold reduction in TLB misses without accompanying measurements. Those figures are not presented as project results. A page-table walk is not required on every memory access, and large pages do not eliminate every page fault.

## A reproducible follow-up

In an isolated lab, record the kernel, CPU, workload, memory size, and page policy. Compare repeated baseline and experimental runs using elapsed time, latency, and translation-related counters. Preserve raw results and report variability before making a performance claim.

## Source submission

- `رضا رنجبر محمدرضا امیدیان.zip/تحقیق کارگاه سیستم عامل.docx`
- `رضا رنجبر محمدرضا امیدیان.zip/تحقیق کارگاه سیستم عامل.pptx`

Original filenames are provenance records. This repository publishes edited English notes rather than the original slide artwork.

## References

- [Linux HugeTLB documentation](https://docs.kernel.org/admin-guide/mm/hugetlbpage.html)
- [Linux Transparent Hugepage documentation](https://docs.kernel.org/admin-guide/mm/transhuge.html)

[All study notes](../README.md)
