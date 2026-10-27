# NEWS

## [2026-10-26] [GermaParl v3.0.0-rc4] [Sample]
- additional adjustments towards validation
  - addressed minor inconsistencies in `listOrg.xml` and `listPerson.xml`
  - moved `gap` nodes inside of `div` nodes
  - `ParlaMint-DE.ana.xml` now includes the correct `corpus component files`

## [2026-10-21] [GermaParl v3.0.0-rc3] [Sample]
- minor adjustments towards validation
  - added IDs to transcriber comments
  - added file name extensions to local taxonomy file paths
- minor corrections of typos in shared taxonomies
- removed affiliation information of guest speakers in listPerson
- added topic annotation on utterance level, topic prefix and appInfo for ParlaCAP
- added initial version of linguistically annotated variant in sample, including
sentiment annotation and entity linking
- added CoNLL-U representation of linguistically annotated variant

## [2026-05-13] [GermaParl v3.0.0-rc2]

- this minor release mainly addresses the following issues:
  - the flawed preparation of protocol 15/030 should be remedied, addressing issue 2
  - protocols are now properly split, addressing issue 3
  - minor improvements of speaker metadata (relevant for a single person) and
  organization metadata (relevant for a single organization)
  - additional steps of the technical validation towards ParlaMint, including
  fixing of missing namespaces, cleaning up of XML syntax and renaming of XML
  elements according to the ParlaMint encoding guidelines

- Note 1: Since protocol 01/021 is part of the sample but is also subject to issue 3,
different utterances are sampled (as the agenda item which was randomly sampled
before is not part of the protocol anymore)
- Note 2: the common taxonomies might appear different from the previous version
due to an adjustment of the mechanism which puts them into this repository.
Substantively, they are identical except for two minor adjustments / the correction 
of typos in the German translations in `ParlaMint-taxonomy-subcorpus.xml` and
`ParlaMint-taxonomy-politicalOrientation.xml`.

## [2026-03-26 / 2026-03-30] [GermaParl v3.0.0-rc1]

- initial commits of GermaParl v3.0.0-rc1 (first sample, then full corpus)
