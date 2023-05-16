---
title: Site Configuration
layout: setup
permalink: /setup/
custom-foot: js/setup-js.html
---

# Set up the play for this site

This is the main site for Digital Dramaturgy, which is currently in an early development phase.  

The site is currently configured to feature **<span id="play_title_check"></span>** via the following spreadsheet:
- ***<span id="current-metadata" class="small"></span>***

Use one of the below forms to change the playscript featured. Note that configurations are stored in your browser's session storage, so any changes will disappear after you quit your browser session! If you'd like to make your changes permanent, go through our [How To directions](directions.html).

{% include setup-forms/sheets.html %}

{% include setup-forms/local-csv.html %}

{% include setup-forms/shakesselect.html %}

## How to Publish Your Google Sheet

- On your Google Sheet, click "File" and select "Publish to the Web".
- On the popup modal, use the dropdowns in "Link" tab to select the sheet name of your metadata (usually "Sheet 1") and "Comma-separated values (.csv)" options, then click "Publish" button.
- Copy the link that is provided.
- Paste the link into form above and click Submit.

For example, our first annotated play for this project, *A Midsummer Night's Dream*, looks like:

`https://docs.google.com/spreadsheets/d/e/2PACX-1vT4-hSjZe4pN0R2-fzmNyc_yrE355W1RgOBmYJ4PF-Lsyo1bKpWVKgwYqGOxGnMvvV41__J66Yjyxa1/pub?output=csv`

If you'd like to test it out, go ahead and enter the link into the form above. 

## How to Download Your Google Sheet as CSV

- On your Google Sheet, click "File" and select “Download as Comma-separated values”
- The file should download to your computer's Downloads folder
- Click in the "Choose file" box in the form above and navigate in your file explorer to select the downloaded CSV.