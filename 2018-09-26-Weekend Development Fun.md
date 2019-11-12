---
published: true
title: Weekend Development Fun
description: I've just spent the better part of this weekend having fun with a new app called Automate
---

I've just spent the better part of this weekend having fun with a new app called ["Automate" for Android](https://play.google.com/store/apps/details?id=com.llamalab.automate). 

If you've ever had the experience of linking apps through IFTTT or Tasker, then you may just understand how useful they can be.

Here's a quick excerpt from my exploits of the weekend:

## [📈 Track HR alongside Google Fit](https://llamalab.com/automate/community/flows/23922)
Want heart rate (HR) tracking, but not all the time? This flow waits until you start an activity in Google Fit and pow! 💢 Heart rate tracking begins.

The moment you stop the activity tracking, so does the HR tracking... Simples.

### Requires
 - Mi Band Tools (only works with Xiaomi Mi Bands)
 - Google Fit

### How to use
 - Download the flow
 - Ensure you have the required apps installed and setup
 - Click "Run"
   It will now be waiting for Google Fit notifications in the background.
 - Start tracking an activity in Google Fit
   This flow will keep continuous heart rate tracking on until you stop the activity... and then all goes back to sleep until the next activity you track.

## [📖 Save for Later](https://llamalab.com/automate/community/flows/23925)
Do you like favourites, but don't like them split among all your apps? Me too... but I don't want an extra app again, the sales slogans tend to remind me of Lord Of The Rings:

> One ring to rule them all, and in the darkness bind them!

Personally, I'm happy to save it to a folder. That's what this app does, it allows you to share any content whatsoever, and have it saved where you like.

### Requires
 - Permission to modify SD card (only to save what you share, in a location you choose)

### Recommended setup
 - Use Syncthing to sync the folder between devices

### How To Use
 - Download the flow
 - Click "Run"
 - Find something worthy of saving, then just Share... to Automate & then select "Save for Later"
 - Smile with glee (stroking phone while whispering "my precious" optional)

## [📑 Shrink Logs](https://llamalab.com/automate/community/flows/23924)

Ever find logs useful? Don't want to delete it but still find yourself scrolling through endless pages of INFO entries?

I may just have the tool for you. Rather than clear the entire log, this tool reads each line of the log checks if it's a discardable INFO log, and keeps the rest.

### Requires
 - Permission to read and modify SD card (purely just for the logs)

### How To Use
 - Download the flow
 - ...and whenever you need easier logs to read
 - Click "Run"
 - ...and if that's not enough, you can even geek out to saved space stats in the log - phewee.

