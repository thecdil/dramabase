---
title: Directions for Using Digital Dramaturgy
layout: setup
permalink: /setup/directions.html
custom-foot: js/setup-js.html
---

# {{page.title}}

_Digital Dramaturgy_ enables the publication of an annotated and/or edited playscript that can be used as a collaborative educational activity in a classroom or as a dramaturgical aid and preservation measure for dramatic presentations. 

Currently, the tool is in early development stages, but the below should get you started if you'd like to check it out. 

## How it Works

### A Broad Overview

_Digital Dramaturgy_ offers a scaffolded framework that allows users to start building their annotated playscript and then test that script by publishing it as a Google Sheet on our main digital dramaturgy site. 

After testing, a user can create their own website by making a copy of the GitHub repository on which this website is built and then replacing the base information collected with their own. 

Finally, after developing that site (following the directions) and finalizing their annotated playscript spreadsheet. See the [CollectionBuilder documentation on deployment](https://collectionbuilder.github.io/cb-docs/docs/deploy/) of a site for more information on possible publishing options. 

### Step 1: Prepare your Script

At minimum, one can set up and publish a _Digital Dramaturgy_ with a published google sheet. We have two options to help you prepare a script.

#### Option A: Use a Prepared Shakespeare Play

 We have starter sheets prepared for all of Shakespeare's plays that anyone can use simply by making a copy of them. These are based on [a dataset found on Kaggle.com](https://www.kaggle.com/datasets/kingburrito666/shakespeare-plays); we are still investigating the provenance of the textual versions of these plays. 

{% include setup-forms/startershakespeare.html %}

#### Option B: Prepare Your Own Script

One can also prepare their own script by using one of our starter spreadsheets:

- [Starter Template with Notes and Examples](https://docs.google.com/spreadsheets/d/1poB0eUjzNKAul30uNSSTJWgduVcUKohb8CH2fKxypK8/copy) 
    - We've included some select lines from Measure for Measure and notes about the fields in this sheet. Delete these rows when ready to publish!
- [Blank Starter Template](https://docs.google.com/spreadsheets/d/1OD4D9xQe59fCAxJN0Aag30BkbKDPHXbM5J_m_hvhTAk/copy) 

In order for the spreadsheet to generate a Digital Dramaturgy site, it must include certain fields that correspond to the text ("playerline"), the speaker ("player"), the act, the scene, and the line number in the scene. Notes on these required fields are found in the Starter Template with Notes and Examples 

### Step 2: Make your Script Publicly Available Using Google Sheets

The simplest way to publish your playscript spreadsheet on Digital Dramaturgy is by publishing it via Google Sheets. To do so, 

- On your Google Sheet, click "File" and select "Publish to the Web".
- On the popup modal, use the dropdowns in "Link" tab to select the sheet name of your metadata (usually "Sheet 1") and "Comma-separated values (.csv)" options, then click "Publish" button.
- Copy the link that is provided.

### Step 3: View Your Playscript Spreadsheet on Digital Dramaturgy

- Paste the link you copied in Step 2 into the form below and click Submit 

{% include setup-forms/sheets.html %}
 
- Click around and check your play -- any edits you make to your Google Sheet will now update your site. 
- If you make edits to your spreadsheet, click the yellow "Refresh your Metadata" button on the pop out menu to refresh the website
- If you'd like to share a link to the site or, add your link as a parameter after the digital dramaturgy website like so: 
    - ***https://thecdil.github.io/dramabase/?play="{YOUR GOOGLE SHEET LINK HERE}***
    - This enables you to send this option as a link to others with whom you might want to share the site.

### Step 4: SetUp Your Own GitHub Repository to Publish Your Annotated Playscript 

_You will need a GitHub account to complete the next steps_

- Go to the [Digital Dramaturgy GitHub Repository](https://github.com/thecdil/dramabase)
- Click the green Use this template button and then the Create a new repository dropdown option.
- Leave the repository as Public. Enter a repository name (use a lowercase name without spaces or odd characters) and click Create repository from template.
- Open the `_config.yml` file and find the "play" variable towards the top of the file 
- Enter a Google sheets link, a relative link to a CSV file in the repository (e.g. /assets/data/play_example.csv), or a link to a CSV file stored somewhere accesible on the internet (i.e. https://example.com/play_example.csv)

### Step 5: Deploy Your Site via GitHub Pages

1. On your project repository's home page, click the "Settings" button (appears on the right along the tabs above the code area).
2. On "Settings" page: click "Pages" in the left side menu.
3. On the "Pages" page: under "Source" leave the dropdown button as "Deploy from a branch". Under "Branch" use the dropdown to change from "none" to "main" (leave the folder option as "/root"), then click the "Save" button. 
 
It will take a few minutes for the build to happen and your site to go live--so wait it out!
After a few minutes, refresh the "Pages" page. 
If the build is successful, an alert will appear near the top providing the URL to your live site.
The URL will follow the pattern: "https://username.github.io/repository-name"

### Further Steps and Future Development

Digital Dramaturgy is built on top of  [CollectionBuilder](https://collectionbuilder.github.io/), a digital exhibit framework that's in use around the world. As such, the tool also allows for the publishing of interpretive essays, interactive visualizations (maps, word clouds, etc.), production timelines, and other features. This also allows for the (robust!) documentation from CollectionBuilder to be repurposed or referenced for many features of the tool. 

We have not, however, well documented how to use these features. 
