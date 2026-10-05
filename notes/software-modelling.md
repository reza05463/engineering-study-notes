# Three views of a software system

[**English**](software-modelling.md) · [**فارسی**](software-modelling.fa.md)

**Type:** Study note

I brought together my notes on ERD, DFD, and state diagrams to explain three ways of looking at a software system.

## Scope

Two overlapping presentations explain entity-relationship diagrams, data-flow diagrams, and state-transition diagrams. This consolidated note gives each technique a distinct purpose.

## Data: ERD

An ERD describes entities, attributes, keys, and relationships. Applied to the story library, a user owns stories and each story may refer to one category. Cardinality and optional relationships should be explicit.

## Flow: DFD

A DFD follows data between external actors, processes, and stores. For a story submission, the author supplies content, a process validates it, and the accepted story is written to storage. A DFD does not specify the execution order of every program statement.

## Behaviour: state transitions

A state diagram describes events and permitted changes. A proposed story workflow could use Draft, Published, and Hidden. Draft is a suggested extension; the supplied library schema only implements its status flag.

## Putting the views together

Use the same entity names and business rules in all three views. The library example is an editorial application of the presentation concepts, not evidence that these diagrams were originally delivered with the library application.

## Source submission

- `1_18576242756 (1).pptx`
- `mdlsazy_systmhay_nrmafzary_ERD_DFD_w_STD_dr_chrkhh_hyat_twsah.pptx`

These are the original filenames from my coursework. I have shared the notes here in English and Persian; the original slides and artwork are kept separately.

[All study notes](../README.en.md)
