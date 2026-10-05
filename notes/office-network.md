# Network design for a 200 m² office

[**English**](office-network.md) · [**فارسی**](office-network.fa.md)

**Type:** Design study

For this assignment, I planned wired desk connections and conference-room Wi-Fi for a 200 m² office.

## Requirements

The assignment describes four rooms with two desks each, plus a central conference room. Eight fixed workstations use wired connections; laptops and mobile devices require wireless access in the conference room.

## Proposed topology

In my design, I placed a router, switch, and modem in a rack near the centre of the building and specifies CAT6 cabling. I proposed eight desk connections, one access point, and two spare outlets, with a 16-port switch.

## Capacity check

Eight desks plus one access point consume nine switch ports. A router uplink brings the count to ten; allowing two spare ports gives twelve. A 16-port switch leaves headroom for this stated scenario. Patch-panel outlets and active switch ports should be counted separately.

## Addressing clarification

192.168.1.1 is a host address, not a subnet. For clarity, I use a proposed 192.168.1.0/24 subnet with .1 as its gateway, reserved management addresses, and a non-overlapping DHCP pool. This describes my proposed addressing scheme, rather than a configuration exported from a device.

## About this work

I completed this as a design exercise. I have not included a simulator project or connectivity logs. Possible additions are a labelled topology, DHCP and ping results, an access-point placement survey, and a guest-network isolation test.

## Source submission

- `پیکربندی فضای اداری 200متری.pdf`

These are the original filenames from my coursework. I have shared the notes here in English and Persian; the original slides and artwork are kept separately.

[All study notes](../README.en.md)
