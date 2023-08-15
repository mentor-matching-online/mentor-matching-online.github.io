---
layout: guide
title: "Notify participants of their matches"
excerpt: "What will you tell mentees and mentors about their matches and what to do next?"
step: 12.1
order: 36
---

You should now notify participants on your programme of their matches and the next steps they should take on the programme. The quickest and easiest way to do this is via email, using the output files you have generated earlier.

## Send personalised emails

Using the [email software you chose earlier]({% link _guides/4-0--select-your-tools.md %}), you should send a personalised email to each participant. 

### How to send personalised emails 

If you are using software like Outlook, you can achieve this using the built in [_Mail Merge_](https://support.microsoft.com/en-us/office/use-mail-merge-to-send-bulk-email-messages-0f123521-20ce-4aa8-8b62-ac211dedefa4#BulkMail=Windows) features. If you are a using a bulk email service like MailChimp or ZohoCampaigns, these services enable you to create templates in similar ways.

### What to tell people about their matches

The output files you generated earlier contain the following information:

| Column         | Description                                 |
|----------------|---------------------------------------------|
| `type`         | Whether someone is a mentor or mentee       |
| `first name`   | The participant's first name                |
| `last name`    | The participant's last name                 |
| `email address` | The participant's email address            |
| `number of matches` | How many matches the participant received. You could use this as part of your template to make it explicit how many matches a participant was given, or to create different emails for those who received different numbers of matches. |
| `mentor only`,<br> `mentee only`,<br> `both mentor and mentee` | These three columns contain either `yes` or `no` values; only one column contains a yes. This information could be used to tailor                your email. |
| `match X bio` | This is the biographical and contact information for each match. There are likely to be multiple columns in this format, where `X` is replaced by a number starting at 0. |
| `match details` | This column is a single output, combining all of the information from the `match X bio` columns. |

You can use all of these fields to construct your personalised emails. Examples of the emails you could send are provided below. The templates also include information about [what participants need to do for their speed mentoring]({% link _guides/12-2--tell-participants-what-to-do-for-speed-mentoring.md %}), which is covered in the next section of this guide.

{:.template}
> ## Example
> ### Notification email to mentors
> 
> This document contains a template you could use to send to **mentors**, notifying them of their mentees. Placeholders for template information are highlighted throughout the document; you'll need to amend these to suit your specific software.
> 
> <a href="/documents/example-mentor-notification-email.docx" title="Download an example mentor notification" class="button button--no-margin">Download this example (.DOCX)</a>

{:.template}
> ## Example
> ### Notification email to mentees
> 
> This document contains a template you could use to send to **mentees**, notifying them of their mentors. Placeholders for template information are highlighted throughout the document; you'll need to amend these to suit your specific software.
> 
> <a href="/documents/example-mentee-notification-email.docx" title="Download an example mentee notification" class="button button--no-margin">Download this example (.DOCX)</a>

