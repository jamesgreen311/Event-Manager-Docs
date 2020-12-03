---
layout: page
title: Event Counts
permalink: /event-counts/
---

# Event Counts

Each event registration will display the total number of participants signed up. This count is provided as helpful feedback to the attendee let them know how many have already signed up to attend this event. 

In addition to the total signed up count, if a **Max** for the event was set, the attendee will also see a **Seating Limit** and what is calculated as the number of **Seats Available**.

Seating Limit is the value set for Max.

Seats Available is calculated as the Max minus Total Signed Up. If Total Signed Up meets or exceeds Max, no one will be prevented from registering.

## Event Registration Counts
To determine the number of participants signed up per event, a pivot table is used. This pivot table is in the Event Registration Counts sheet. It uses the email entered on the registration form to identify an attendee. Each email captured per event will only be counted once. If someone accidentally registers more than once, as long as the same email address was used, they will only be counted one time.