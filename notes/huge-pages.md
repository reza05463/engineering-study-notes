# Understanding Linux huge pages

[**English**](huge-pages.md) · [**فارسی**](huge-pages.fa.md)

**Type:** Collaborative study

Mohammadreza Omidian and I prepared this report on virtual memory, address translation, and the trade-offs of larger memory pages.

## Attribution

I worked on this report and presentation with Mohammadreza Omidian. We credited the work jointly; the original files do not list separate responsibilities.

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

These are the original filenames from my coursework. I have shared the notes here in English and Persian; the original slides and artwork are kept separately.

## References

- [Linux HugeTLB documentation](https://docs.kernel.org/admin-guide/mm/hugetlbpage.html)
- [Linux Transparent Hugepage documentation](https://docs.kernel.org/admin-guide/mm/transhuge.html)

[All study notes](../README.en.md)
