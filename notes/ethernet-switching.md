# Ethernet forwarding trade-offs

**Type:** Study note

Comparing store-and-forward, cut-through, and fragment-free forwarding through latency and error-handling trade-offs.

## Store-and-forward

A switch receives the complete frame before forwarding it, allowing frame-check validation first. This creates a different latency/error-handling trade-off from forwarding that begins before full reception.

## Cut-through and fragment-free

Cut-through begins forwarding after sufficient header information arrives, before the complete frame-check result is available. Fragment-free waits for the first 64 bytes; it should not be described as a full integrity check.

## Corrections

The original slides use the phrase 100% reliability for store-and-forward. This revision removes that guarantee. CRC checking does not prove that a network is fault-free or that every possible corruption will be detected.

## Operational scope

The deck includes example configuration commands for several vendors. They are not reproduced as universal commands: availability and syntax must be verified against the exact switch model, hardware, and software release.

## Evidence

This is a comparative presentation, with no switch configuration export, traffic capture, or measured forwarding-latency experiment. A lab extension should preserve the device version and traffic conditions alongside its observations.

## Source submission

- `switches.pptx`

Original filenames are provenance records. This repository publishes edited English notes rather than the original slide artwork.

[All study notes](../README.md)
