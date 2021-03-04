# Twitter Picture Data

Labelled Twitter profile picture data sets for experimental data science / machine learning purposes.

## About

These data sets were originally created for the purposes of training [Riley the Radiology Registrar](https://twitter.com/_JoshCase/status/1362653163338129409), a Twitter bot that writes radiology-style reports for Twitter profile pictures.

To create and train Riley, I manually labelled almost 2000 Twitter profile pictures scraped from the #MedTwitter community.

Unfortunately, Riley has been banned by Twitter, and they've refused to communicate regarding which policies if any have been violated. It's unclear if Riley will ever get allowed back onto the platform.

Consequently, I've decided to share these datasets openly to allow anyone to use them for side-projects that depend on labelled data.

## The datasets

To create somewhat realistic radiology reports, Riley tried to classify #MedTwitter profile pictures in the following ways:

1. How many human faces appeared in the picture?
    1. Classes: `0`, `1`, `2`, `3 or more`
    1. Folder: `/faces`
1. What attire is the main subject wearing?
    1. Classes: `Casual`, `Clinical`, `Professional`
    1. Folder: `/attire`
1. Is the main subject wearing any eyewear?
    1. Classes: `True`, `False`
    1. Folder: `/eyewear`
1. Is the main subject's hair long or short?
    1. Classes: `Long`, `Short`
    1. Folder: `/hairLength`
1. Is the main subject's hair light or dark?
    1. Classes: `Light`, `Dark`
    1. Folder: `/hairColour`
1. Is the main subject wearing a mask?
    1. Classes: `True`, `False`
    1. Folder: `/PPE`

And for profile pictures that contain no discernible human faces:
* Does the image contain alphanumeric characters? (i.e letters and numbers).
    1. Classes: `True`, `False`
    1. Folder: `/alphanumeric`
    
### Build something cool with this, and let me know when you do!
