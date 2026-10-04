# Object-oriented design fundamentals

**Type:** Study note

Explaining objects, classes, encapsulation, inheritance, polymorphism, and abstraction without overstating their benefits.

## Objects and classes

An object combines state and behaviour. A class describes a family of objects and the operations they expose. Choosing useful boundaries matters more than merely arranging code into classes.

## Encapsulation and abstraction

Encapsulation controls access to representation. Abstraction presents the operations relevant to a caller while hiding unnecessary detail. The original Persian text labels abstraction as distribution; the correct concept here is abstraction (انتزاع).

## Inheritance and polymorphism

Inheritance can express a meaningful subtype relationship. Polymorphism lets callers use a shared interface with different implementations. Neither implies that inheritance is always the best tool for reuse; composition can keep unrelated responsibilities separate.

## Trade-offs

Clear interfaces can support maintainability and testing, but object orientation does not automatically isolate every change or make a system secure. Overly deep inheritance and unclear responsibilities can increase coupling.

## Evidence and next exercise

This artifact is a conceptual report. A useful follow-up would implement a small example with two interchangeable implementations and tests showing the same public contract.

## Source submission

- `برنامه نویسی شیء گرا-(رضا رنجبر).docx`

Original filenames are provenance records. This repository publishes edited English notes rather than the original slide artwork.

[All study notes](../README.md)
