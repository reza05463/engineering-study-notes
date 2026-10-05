# Ethernet forwarding trade-offs

[**English**](ethernet-switching.md) · [**فارسی**](ethernet-switching.fa.md)

**Type:** Study note

I compared store-and-forward, cut-through, and fragment-free switching, focusing on latency and error handling.

## Store-and-forward

A switch receives the complete frame before forwarding it, allowing frame-check validation first. This creates a different latency/error-handling trade-off from forwarding that begins before full reception.

## Cut-through and fragment-free

Cut-through begins forwarding after sufficient header information arrives, before the complete frame-check result is available. Fragment-free waits for the first 64 bytes; it should not be described as a full integrity check.

## Corrections

The original slides use the phrase 100% reliability for store-and-forward. This revision removes that guarantee. CRC checking does not prove that a network is fault-free or that every possible corruption will be detected.

## Operational scope

The deck includes example configuration commands for several vendors. They are not reproduced as universal commands: availability and syntax must be verified against the exact switch model, hardware, and software release.

## About this work

My work here is a comparison of forwarding methods. I have not included switch configuration output, packet captures, or latency measurements. A lab extension would need to record the device version and traffic conditions.

## Source submission

- `switches.pptx`

These are the original filenames from my coursework. I have shared the notes here in English and Persian; the original slides and artwork are kept separately.

[All study notes](../README.en.md)
