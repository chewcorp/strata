---
type: correction
title: Stacked pull request merge base
description: A pull request merged into its parent branch after the parent landed never reaches main.
key: stacked-pr-merge-base
count: 2
status: stable
superseded_by: []
sources:
  - id: first-correction
    resource: "Correction during a stacked pull request merge."
  - id: repeat-correction
    resource: "The same correction repeated."
generated:
  by: process:strata-capture
  at: "2026-11-21T08:44:00Z"
verified:
  - by: human:fixture
    at: "2026-11-21T08:44:00Z"
---

A pull request merged into its parent branch after the parent landed never reaches main. Check the base before merging.[^first-correction][^repeat-correction]
