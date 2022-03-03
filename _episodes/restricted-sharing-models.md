---
title: Restricted sharing models
teaching: 10
exercises: null
duration: null
summary: Considering options for if you cannot publish your data openly.
questions:
  - What do I do if I am not allowed to share my data openly?
objectives:
  - Understand controlled access sharing.
  - Understand publishing metadata
keypoints:
is-break: null
ukrn_wb_rules: []
day: 1
order: 600000
missingDependencies: []
dependencies: []
originalRepository: UKRN-Open-Research/ukrn-wb-lesson-templates

---

## Overview

In some cases, data cannot be shared. 
There can be several reasons for this: it may be impractical to anonymise them sufficiently, 
they may be commercially sensitive, or they may be deemed too risky to share.
In these cases, you can usually still publish metadata, and place your data somewhere where
authorised people can access them.

## Publishing metadata

Metadata are data that describe datasets.
These include things like the name, size, and date of the dataset, 
but they also usually include some details about the structure of the data.

Metadata that include structural information are often called a 
[data dictionary](https://help.osf.io/hc/en-us/articles/360019739054-How-to-Make-a-Data-Dictionary).
They allow others to understand the variables.

Here is a small example of a data dictionary for an online psychology experiment:

| Variable | Name | Type | Description |
|----------|------|------|-------------|
| participant_id | Participant Id | string | A 15-character alphanumeric identifier for the participant |
| trial_type | Trial type | string | jsPsych plugin type |
| trial_index | Trial index | integer | jsPsych trial index |
| time_elapsed | Time since experiment start | integer | Milliseconds elapsed since the start of the experiment script |
| rt | Response time | double | Response time reported by the trial function in milliseconds |
| stimulus | Trial stimulus | string | Stimulus parameter for the trial function |
| response | Trial response | string | Response recorded by the trial function |
| task | Trial task | string | Friendly name for the trial_type |
| correct_response | Expected response | string | Response required for a correct response |
| correct | Correct response supplied? | boolean | Whether the response matched the correct_response |

These kinds of data dictionaries are usually saved as .csv files, and should accompany published datasets.
They provide useful information in and of themselves, however, so 
**you can and should publish your data dictionaries even if you can't publish the underlying data.**

## Controlled access

When you cannot share your data openly, you can often share it with certain people.
In this model, rather than putting your data out there for anyone to access, 
you place your data in an environment where authorised users can provide code to be executed with the data.
Usually, the code will be checked by experts to ensure that it complies with the terms of access.
If the code is judged to be okay, it is run with the data and the results are sent back to the user. 

If controlled access sharing might be an option for you, you will need to find a provider who will manage the access.
Many universities will have policies and providers in place for this because it is common in medical and rich demographic datasets.
