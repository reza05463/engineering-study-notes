# Black-box and white-box testing

**Type:** Study note

Choosing tests from observable requirements and internal control flow, with a concrete boundary example.

## Black-box techniques

Black-box tests derive expected behaviour from requirements. Equivalence partitioning, boundary-value analysis, decision tables, and state-transition testing belong here. The original report repeats partitioning and boundary analysis under white-box techniques; this revision corrects that classification.

## White-box techniques

White-box tests use implementation structure, such as statement and branch coverage. Executing every statement does not necessarily exercise every branch. Full path coverage can be infeasible when loops create many possible paths.

## Worked example

For a hypothetical field accepting integer values from 1 to 100, test valid and invalid partitions and boundaries such as 0, 1, 2, 99, 100, and 101. Derive expected outcomes from the requirement; reject out-of-range values and accept the valid boundaries. This is a new explanatory example, not an executed test report.

## Applying it to the library

Test successful registration and invalid input as observable behaviours. Then inspect branches around authentication and owner/admin authorization. Combine both approaches: coverage alone does not establish that requirements are correct or complete.

## Evidence

The original artifact is a comparison report. No automated test suite, coverage report, or defect log accompanied it.

## Source submission

- `مقایسه_و_برسی_تست_های_جعبه_سیاه_و_جعبه_سفید.docx`

Original filenames are provenance records. This repository publishes edited English notes rather than the original slide artwork.

## References

- [ISTQB test-technique material](https://istqb.org/?download_id=5745&sdm_process_download=1)

[All study notes](../README.md)
