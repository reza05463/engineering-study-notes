# Zigbee and low-power sensor networks

[**English**](zigbee.md) · [**فارسی**](zigbee.fa.md)

**Type:** Study note

My notes on Zigbee device roles, mesh routing, power use, and comparisons with other wireless technologies.

## Scope

The presentation studies coordinator, router, and end-device roles, the relationship to IEEE 802.15.4, low-power operation, mesh networking, and smart-home applications.

## Device roles

Routing capability must be distinguished from end-device behaviour. Sleepy end devices save energy by limiting activity; they should not be described as if every sensor forwards traffic for the mesh.

## A fair comparison

The original slides make blanket claims about Wi-Fi device counts and Bluetooth being limited to point-to-point links. These statements are removed. Bluetooth has a mesh specification, and capacity and power use depend on the protocol variant, implementation, and workload.

## Security and measurement

Encryption alone does not establish that a deployment is secure. Provisioning, key handling, device updates, and configuration need their own analysis. Range and battery-life figures should be labelled with test conditions rather than promised universally.

## About this work

I prepared this as a classroom protocol review. I have not included a deployed mesh, firmware, packet captures, or power measurements. A possible follow-up is a small sensor lab to observe device joining and packet delivery.

## Source submission

- `رضا رنجبر zigbee protocol.pptx`

These are the original filenames from my coursework. I have shared the notes here in English and Persian; the original slides and artwork are kept separately.

## References

- [Connectivity Standards Alliance: Zigbee](https://csa-iot.org/all-solutions/zigbee/)
- [Bluetooth Mesh specification](https://www.bluetooth.com/specifications/specs/mesh-profile-1-0/)

[All study notes](../README.en.md)
