---
layout: post
title: "Format the data"
excerpt: "Ensure your data is in the required format for our software."
step: 11.1
order: 33
---

You should have [collected]({% link _guides/7-2--open-registrations.md %}) and [validated]( {% link _guides/9-1--validate-the-registration-data.md %}) you participant data, and – if you've decided to – [established a baseline for your evaluation]({% link _guides/10-0--evaluate-the-programme.md %}). Now you can match mentors and mentees. You can do this manually or using our software package; this guide will focus on using our software package.

## Make sure your data is in the correct format

Whatever tool you use to [collect your data during registration]({% link _guides/5-1--build-the-registration-forms.md %}), you must ensure that your registration tools can output your participant data in a standardised format using the `.CSV` file format.

Our software requires that the data contains specific, case-sensitive, column headings. You may need to transform the data you have collected into the correct format – either manually or using appropriate formulae in a spreadsheet.

Our software also requires that mentors and mentees are loaded into the system as two, separate files called `mentors.csv` and `mentees.csv`.

The example files below contain the correct format and headings for the data; you can import this into most spreadsheet software to transform and prepare your own data.

{:.template}
> ## Example
> ### Output data
> 
> These files demonstrate the required format for data you input to our mentor matching software. The files must be named `mentors.csv` and `mentees.csv` respectively.
> 
> <a href="/assets/documents/example-output-data.zip" title="Download an example data files" class="button button--no-margin">Download the example files (.ZIP containing .CSV files)</a>

This example file includes a set of dummy source data and, on separate tabs, the data in the required output format. This example is provided to demonstrate how formulae can be used to transform raw registration data into the correct format.

{:.template}
> ## Example
> ### Dummy data and outputs
> 
> These files demonstrate how formulae can be used to transform raw registration data into the correct format.
> 
> <a href="/assets/documents/example-dummy-data-and-outputs.xlsx" title="Download the spreadsheet with dummy data and working formulae" class="button button--no-margin">Download this example (.XLSX)</a>

### Required fields

#### Mentors

The required columns and headings in the `mentors.csv` file are:

| Column         | Description                                 |
|----------------|---------------------------------------------|
| `first name`   | This is the mentor's first name, as they provided it when registering. |
| `last name`    | This is the mentor's last name, as they provided it when registering. |
| `email address`| This is the mentor's email address, as they provided it when registering. The email address must be unique. |
| `both mentor and mentee` | **This data must be provided as a `yes` or `no` value.** <br> This field indicates whether the participant has registered as both a mentor and a mentee. It is recommended that you complete this before submitting the data; it can be programmatically determined using a formulae in a spreadsheet. |
| `job title`   | This is the mentor's job title, as they provided it when registering. |
| `grade`   |  This is the mentor's grade (i.e. seniority), selected from a pre-defined list, as they provided it when registering. |
| `organisation`   |  This is the mentor's organisation, selected from a pre-defined list, as they provided it when registering. |
| `profession`   |  This is the mentor's profession (i.e. specialism), selected from a pre-defined list, as they provided it when registering. |
| `characteristics`   | **This field can be left blank.** <br> **This data must be provided as a comma-separated list.** <br>This is the mentor's arbitrary characteristics, selected from a pre-defined list, if they provided it when registering. |
| `biography`   |  **This field must, at a minimum, contain the participant's email address.** <br> This field is the core information sent out to matches during the matching process. You should construct the biography field using data collected during registration. The simplest biography would be to include the mentor's email address. You could also programmatically generate the biography based on a series of questions in the registration form and spreadsheet formulae. |

#### Mentees

The required columns and headings in the `mentees.csv` file are:

| Column         | Description                                 |
|----------------|---------------------------------------------|
| `first name`   | This is the mentee's first name, as they provided it when registering. |
| `last name`    | This is the mentee's last name, as they provided it when registering. |
| `email address`| This is the mentee's email address, as they provided it when registering. The email address must be unique. |
| `both mentor and mentee` | **This data must be provided as a `yes` or `no` value.** <br> This field indicates whether the participant has registered as both a mentor and a mentee. It is recommended that you complete this before submitting the data; it can be programmatically determined using a formulae in a spreadsheet. |
| `job title`   | This is the mentee's job title, as they provided it when registering. |
| `grade`   |  This is the mentee's grade (i.e. seniority), selected from a pre-defined list, as they provided it when registering. |
| `organisation`   |  This is the mentee's organisation, selected from a pre-defined list, as they provided it when registering. |
| `profession`   |  This is the mentee's profession (i.e. specialism), selected from a pre-defined list, as they provided it when registering. |
| `match with similar identity`   |  **This field cannot be left blank – if it is not needed, the default value is `no`.** <br> **This data must be provided as a `yes` or `no` value.** <br> This is the mentee's stated preference to be matched with someone with a similar abitrary characteristic as one they chose during registration. |
| `characteristics`   | **This field can be left blank.** <br> **This data must be one value from the same pre-defined list as used by mentors.** <br> This is the mentee's arbitrary characteristics, selected from a pre-defined list, if they provided it when registering. |
| `biography`   |  **This field must, at a minimum, contain the participant's email address.** <br> This field is the core information sent out to matches during the matching process. You should construct the biography field using data collected during registration. The simplest biography would be to include the mentee's email address. You could also programmatically generate the biography based on a series of questions in the registration form and spreadsheet formulae. |