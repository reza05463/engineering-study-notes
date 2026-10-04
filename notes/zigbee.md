# Zigbee and low-power sensor networks

**Type:** Study note

A protocol study focused on device roles, mesh routing, power use, and careful technology comparisons.

## Scope

The presentation studies coordinator, router, and end-device roles, the relationship to IEEE 802.15.4, low-power operation, mesh networking, and smart-home applications.

## Device roles

Routing capability must be distinguished from end-device behaviour. Sleepy end devices save energy by limiting activity; they should not be described as if every sensor forwards traffic for the mesh.

## A fair comparison

The original slides make blanket claims about Wi-Fi device counts and Bluetooth being limited to point-to-point links. These statements are removed. Bluetooth has a mesh specification, and capacity and power use depend on the protocol variant, implementation, and workload.

## Security and measurement

Encryption alone does not establish that a deployment is secure. Provisioning, key handling, device updates, and configuration need their own analysis. Range and battery-life figures should be labelled with test conditions rather than promised universally.

## Evidence

This is a classroom protocol review. It includes no deployed mesh, firmware, packet captures, or measured power data. A practical extension would document join behaviour and packet delivery in a small sensor lab.

## Source submission

- `رضا رنجبر zigbee protocol.pptx`

Original filenames are provenance records. This repository publishes edited English notes rather than the original slide artwork.

## References

- [Connectivity Standards Alliance: Zigbee](https://csa-iot.org/all-solutions/zigbee/)
- [Bluetooth Mesh specification](https://www.bluetooth.com/specifications/specs/mesh-profile-1-0/)

[All study notes](../README.md)
