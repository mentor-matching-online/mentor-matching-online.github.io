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

### Install the software

To install the software, follow the [instructions in the software documentation](https://github.com/mentor-matching-online/mentor-match/blob/main/docs/_docs/getting-started.md).

### Running the software

To run the software locally, in the Command Line (Windows) or Terminal (MacOS) applications, navigate to the folder where you stored the software package, then run:

```
docker-compose up
```

You, in your browser, navigate to:

```
http://localhost:5001
```

You should see the software load on screen. Follow the prompts to complete the matching process. 

The process should take around 5 to 30 minutes, depending on the size of your dataset and how much memory you computer is able to allocate to the task. Leave the window open whilst the matching is taking place. 

{:.warning-text}
> **The software deletes the outputs after 10 minutes.** Make sure you check regularly whether the outputs are ready, so that you don't have to repeat the process.