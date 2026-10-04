# A two-floor wired and wireless network

**Type:** Design study

A documented connection plan for twenty endpoints across two floors and a conference area.

## Requirements

The lower floor has five rooms with two endpoints each. The upper floor has four rooms with two endpoints each plus two conference-table endpoints: twenty endpoints in total.

## Proposed implementation

The report describes CAT6 links, a rack, patch panel, switch, server-based DHCP, and access points on both floors. It includes configuration screenshots and a schematic showing the intended wired and wireless arrangement.

## Design reasoning

Endpoint counts are only the starting point for switch sizing. Router, server, access-point and inter-switch links also consume ports. A port schedule and cable-route plan would make the design easier to review and maintain.

## Evidence boundary

The supplied PDF records a classroom configuration exercise. It does not include an editable simulator file, a hardware deployment record, or measured throughput and coverage results.

## Next version

Preserve the twenty-endpoint requirement, add an address table and port map, then capture DHCP leases, cross-floor connectivity tests, and guest-to-staff isolation results in a repeatable lab.

## Source submission

- `پیکربندی.pdf`

Original filenames are provenance records. This repository publishes edited English notes rather than the original slide artwork.

[All study notes](../README.md)
