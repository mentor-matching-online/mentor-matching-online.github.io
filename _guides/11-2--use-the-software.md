---
layout: post
title: "Use the mentor matching software"
excerpt: "Install and run the mentor matching software."
step: 11.2
order: 34
---

Once your data is in [the correct format]({% link _guides/11-1--format-the-data.md %}), you can use our software package to do the matching process in just a few minutes. 

This software is provided free-of-charge under an open source license and you can run the software locally on your own device. 

You do not have to use our software if you don’t want to, but it can save significant time and money. It takes minutes to match hundreds of participants using our software; the equivalent task could take a person up to a week of full-time, manual work.

{:.warning-text}
> At the moment, you need to be able to install software on your device to use our mentor matching software. We are currently working to put our matching software online so you can use it through a web browser from any device. This may come at a small cost. We will update our guidance documents to tell you how to use the software when it is available.

## Install the software

To install the software, follow the [instructions in the software documentation](https://github.com/mentor-matching-online/mentor-match/blob/main/docs/_docs/getting-started.md).

## Running the software

To run the software locally, in the Command Line (Windows) or Terminal (MacOS) applications, navigate to the folder where you stored the software package, then run:

```
docker-compose up
```

Once the software is running, in your browser, navigate to:

```
http://localhost:5001
```

You should see the software load on screen. Follow the prompts to complete the matching process. 

### Upload the data

You should have already [formatted your source data]({% link _guides/11-1--format-the-data.md %}) into two files – `mentees.csv` and `mentors.csv`. When prompted, upload both of these files into the system.

If you are running the software locally, all the data stays entirely on your device – you are *uploading* it to another part  your computer. 

### Matching options

#### Weightings

After you have input your two source files you will be asked to choose how mentors and mentees are matched. There are two options:

1. **Optimise for the best possible matches**. If you choose this option, the software will prioritise ensuring that the best mentors and mentees are matched, even if that means a some participants receive no matches at all.
2. **Optimise so that the most number of mentees receive a match**. If you choose this option, the software will prioritise ensuring as many participants as possible receive at least 1 match. Some participants might still not receive a match. Some participants will receive fewer matches than they would have under the other option.

### Start the matching process

After you have chosen your options, select the `Start matching` button. 

The matching process should take around 5 minutes, depending on the size of your dataset and how much memory you computer is able to allocate to the task. Very large datasets can take much longer; the largest dataset we've tested contained 1,250 participants and took around 20 minutes to complete.

Leave the window open whilst the matching is taking place. 

### Download the matches

After matching is complete, you will be prompted to download the matches. The download will be a ZIP file containing two CSV files:

- `mentees-list.csv` – which contains all of the mentees and their matches
- `mentors-list.csv` – which contains off of the mentors and their matches

These files will be used in the remaining stages of the programme delivery.

After you have downloaded the data, the input and output files stored by the software will be erased.

{:.warning-text}
> **The software automatically deletes its copy of the outputs after 10 minutes.** Make sure you check regularly whether the outputs are ready, so that you don't have to repeat the process.

## Keep the output files safe

You will need to use the output files multiple times throughout the remaining stages of the programme. Keep them safe and secure, and don't delete them until your programme is finished.

If you lose the outputs for some reason, and need to repeat the process, provided the input data is the same and you use the same settings, the outputs from the software should be identical each time.