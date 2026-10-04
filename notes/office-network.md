# Network design for a 200 m² office

**Type:** Design study

Planning wired desks and conference-room wireless access around a small office’s physical requirements.

## Requirements

The assignment describes four rooms with two desks each, plus a central conference room. Eight fixed workstations use wired connections; laptops and mobile devices require wireless access in the conference room.

## Proposed topology

The report places a router, switch, and modem in a rack near the centre of the building and specifies CAT6 cabling. It proposes eight desk connections, one access point, and two spare outlets, with a 16-port switch.

## Capacity check

Eight desks plus one access point consume nine switch ports. A router uplink brings the count to ten; allowing two spare ports gives twelve. A 16-port switch leaves headroom for this stated scenario. Patch-panel outlets and active switch ports should be counted separately.

## Addressing clarification

192.168.1.1 is a host address, not a subnet. A portfolio revision can describe a proposed 192.168.1.0/24 subnet with .1 as its gateway, reserved management addresses, and a non-overlapping DHCP pool. This is a clarified proposal, not a recovered device configuration.

## Validation still needed

The report is a design exercise. No simulator project or connectivity logs were supplied. A stronger next version would add a labelled topology, DHCP and ping results, an access-point placement survey, and a guest-network isolation test.

## Source submission

- `پیکربندی فضای اداری 200متری.pdf`

Original filenames are provenance records. This repository publishes edited English notes rather than the original slide artwork.

[All study notes](../README.md)
