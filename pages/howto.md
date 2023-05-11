---
title: Directions for Using Digital Dramaturgy
layout: setup
permalink: /setup/directions.html
custom-foot: js/setup-js.html
---

# {{page.title}}

_Digital Dramaturgy_ enables the publication of an annotated and/or edited playscript that can be used as a collaborative educational activity in a classroom or as a dramaturgical aid and preservation measure for dramatic presentations. 

The tool is built on top of the [CollectionBuilder](https://collectionbuilder.github.io/), a digital exhibit framework that's in use around the world. As such, the tool also allows for the publishing of interpretive essays, interactive visualizations (maps, word clouds, etc.), production timelines, and other features. This also allows for the (robust!) documentation from CollectionBuilder to be repurposed or referenced for many features of the tool. 

## How it Works

### A Broad Overview

_Digital Dramaturgy_ offers a scaffolded framework that allows users to start building their annotated playscript and then test that script by publishing it as a Google Sheet on our main digital dramaturgy site. 

After testing, a user can create their own website by making a copy of the GitHub repository on which this website is built and then replacing the base information collected with their own. 

Finally, after developing that site (following the directions) and finalizing their annotated playscript spreadsheet. See the [CollectionBuilder documentation on deployment](https://collectionbuilder.github.io/cb-docs/docs/deploy/) of a site for more information on possible publishing options. 

### Preparing a Script

At minimum, one can set up and publish a _Digital Dramaturgy_ with a published google sheet. We have starter sheets prepared for all of Shakespeare's plays that anyone can use simply by making a copy of them. 

{% include startershakespeare.html %}

One can also prepare their own script by using our [Starter Template with notes and Examples](https://docs.google.com/spreadsheets/d/1poB0eUjzNKAul30uNSSTJWgduVcUKohb8CH2fKxypK8/copy) or our [Blank Starter Template](https://docs.google.com/spreadsheets/d/1OD4D9xQe59fCAxJN0Aag30BkbKDPHXbM5J_m_hvhTAk/copy). We've included the first couple lines of Measure for Measure and notes about the fields in the former sheet. Delete these rows when ready to publish!

### Publishing your Script Using Google Sheets

The simplest way to publish your script spreadsheet/CSV on Digital Dramaturgy is by publishing it via Google Sheets. To do so, 

- On your Google Sheet, click "File" and select "Publish to the Web".
- On the popup modal, use the dropdowns in "Link" tab to select the sheet name of your metadata (usually "Sheet 1") and "Comma-separated values (.csv)" options, then click "Publish" button.
- Copy the link that is provided.
- Paste the link into form below and click Submit 

or
 
- Add your link as a paremeter after the digital dramaturgy website like so: https://thecdil.github.io/?play="{YOUR GOOGLE SHEET LINK HERE}
    - This enables you to send this option as a link to others you might want to share the site with. 

{% include setup-forms/sheets.html %}

You can also 




## How to Download Your Google Sheet as CSV

- On your Google Sheet, click "File" and select “Download as Comma-separated values”
- The file should download to your computer's Downloads folder
- Click in the "Choose file" box in the form above and navigate in your file explorer to select the downloaded CSV.