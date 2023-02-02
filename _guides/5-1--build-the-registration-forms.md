---
layout: post
title: "Build the registration forms"
excerpt: "How will you collect information from your participants?"
step: 5.1
order: 12
---

## Use a form or survey tool

We recommend using a form or survey tool to support your registration process. This will make it easy for you to gather data, minimising manual work like copy-and-pasting data, and minimising the risk of invalid or unhelpful data being collected. 

As we advised in our guidance on [tools you'll need to run a programme]({% link _guides/4-0--select-your-tools.md %}), tools like Microsoft Forms or Google Forms are usually a straight-forward choice; especially if you already have access to them in your organisation.

## Participant data to collect

You will need to collect data from both mentors and mentees to enable your matching process. 

Much of information requested below is required to enable [our matching software]({% link _guides/11-0--match-mentors-to-mentees.md %}) to work. In addition to the required information, you could collect additional data that can support your programme more widely. Any non-mandatory data you collect will not be actively used as part of the matching software's algorithm, but it can be used to generate more rich outputs.

Whilst you can collect this information in any way, the data will eventually need to be provided to the software in a standardised file format with specific column headings. [Learn more about the required data formats]({% link _guides/11-0--match-mentors-to-mentees.md %}).

### First and last name
#### Required

You should capture each participant's first and last name. This enables you to:

1. customise any correspondence with the participant
2. provide complete information about the participant to their matches

Our software requires that the first and last name are captured separately. 

This information is not considered in the matching algorithm.

### Job title or role
#### Optional

You could capture each participant's job title or role. This enables you to provide complete information about the participant to their matches.

Our software requires this field is represented in the structured data, but it could simply be left blank.

This information is not considered in the matching algorithm.

### Grade (seniority)
#### Required

You must capture each participant's grade – their level of seniority within the common structures of your organisation.

This information is considered in the matching algorithm.

The software uses a standardised grading structure to conduct each match. The default grades, from lowest to highest, are:

- AA
- AO
- EO
- HEO
- SEO
- Grade 7
- Grade 6
- SCS1
- SCS2
- SCS3
- SCS4

It is not currently possible to customise this structure, but future iterations of the software will allow you to define your own labels for each grade within your organisation.

We recommend providing a user-selectable list of grades in your registration form to enforce consistency of spelling, grammar and punctuation. Participants should only be able to pick one option.

### Profession (specialism)
#### Required

You must capture each participant's profession, specialism or area of expertise. 

A profession can be any string of alphanumeric characters, for example: `audit`, `tax`, `Human Resources`. 

This information is considered in the matching algorithm.

The software will compare whether the profession provided by a mentee is exactly the same as, or different from, the profession provided by a mentor and then determine whether or not to match those participants.

We recommend providing a user-selectable list of professions to enforce consistency of spelling, grammar and punctuation. Participants should only be able to pick one option.

### Organisation
#### Required

You must capture which organisation a participant works in. This could be an employer or a team within an employer. 

An organisation can be any string of alphanumeric characters, for example: `Cabinet Office`, `Finance team`, `Skills and Capability directorate`. 

This information is considered in the matching algorithm.

The software will compare whether the organisation provided by a mentee is exactly the same as, or different from, the organisation provided by a mentor and then determine whether or not to match those participants.

We recommend providing a user-selectable list of organisations to enforce consistency of spelling, grammar and punctuation. Participants should only be able to pick one option.

### Arbitrary or protected characteristics
#### Optional

If it is suitable for your programme, you could ask users to state a preference for a match who has a particular characteristic. The characteristic could be any characteristic set you want to use, but it was intended for matching people on the basis of a protected characteristic like ethnicity, sex or sexual orientation.

This information is considered in the matching algorithm.

A characteristic can be any string of alphanumeric characters, for example: `White` , `Female`, `Lesbian`, `Vegetarian`. 

The software will compare whether the characteristic selected by a mentee is matches one of the characteristics provided by a mentor and then determines whether or not to match those participants.

We recommend providing a user-selectable list of organisations to enforce consistency of spelling, grammar and punctuation. The software allows mentors to provide multiple characteristics – which could be facilitated with checkboxes on a form. Mentees can only select one characteristic – which could be facilitated with a dropdown list or a radio-button list.

### Biographical information
#### Optional

You could ask one or more questions of participants to construct a biography that is shared with a participant's matches. 

This information is not considered in the matching algorithm but it is used to generate the output files. Our software requires this field is represented in the structured data, but it could simply be left blank.

### Demographic monitoring
#### Optional

You could ask demographic questions of your participants, so you can use this as part of your evaluation and analysis of your programme.

This information is not considered in the matching algorithm and is discarded. We do not recommend collecting the data if you do not intend to use it for analysis.

{:.template}
> ## Example
> ### Registration form
> 
> This Google Form contains a template example you could use to collect your participant data. It is linked to a Google Sheet document that outputs the data in the format required by our matching software. You can freely re-use and adapt this form and spreadsheet to suit your needs.

## Make sure you have a data and privacy policy

Before you start collecting or processing any user data, make sure you have a [data and privacy policy]({% link _guides/5-2--create-a-data-and-privacy-policy.md %}) in place. The next step in our guidance covers this topic.