# Sheet Site
## Goal
This website is an experiment to see if a complicated video gallery website can be created using google sheets as a configuration and resource database. With an added bonus of requiring little to no technical understanding of website design & hosting.

## Features
* Create a video gallery website as easy as copying and modifying a google sheet template - actual video/images should be hosted elsewhere (free sites is fine).
* Basic filtering, sorting and grouping using tags.
* Preview animation on videos
* Desktop and Mobile friendly - should scale well and not have too much blank space (modern browsers only).
* Obviously no ads or popups.

## How to use
Creating your own sheets site is as easy as:
1) Logging into google sheets using your google account.
2) Create a copy of [Nature Sheet available here](https://docs.google.com/spreadsheets/d/1LOIAjq90NeDJ3LEErShFGL7P7EC05KK-cV_IwZdnGPU/edit?usp=sharing) by navigating to File > Make a copy, this can be used as a template for your own website.
2.1) Modify Nature config sheet to style the website as you please.
2.2) Modify Nature resource and tag sheets to include the content you want.
2.3) Generate any resource previews ...
3) Publish your google sheet 
* Open your copied google sheet
* Navigate to "File > Publish to web"
* Click "Published content & Settings", click "Start Publishing"
4) Share your google sheet with public...
* Keep your google sheet open that you just publishde
* Click on "Share" (top right)
* Click "Get Sharable link"
* You will get a share URL that looks something like "https://docs.google.com/spreadsheets/d/1LOIAjq90NeDJ3LEErShFGL7P7EC05KK-cV_IwZdnGPU/edit?usp=sharing"
* Copy the Id part of the URL, you will need this in a moment, eg: "1LOIAjq90NeDJ3LEErShFGL7P7EC05KK-cV_IwZdnGPU"
5) Now you should be able to replace the #... on this website with your own. eg if your id was: 1LOIAjq90NeDJ3LEErShFGL7P7EC05KK-cV_IwZdnGPU then to view your own sheets site, you should visit https://sheetsite.github.io/#1LOIAjq90NeDJ3LEErShFGL7P7EC05KK-cV_IwZdnGPU

## Example
* This Google Document: https://docs.google.com/spreadsheets/d/1LOIAjq90NeDJ3LEErShFGL7P7EC05KK-cV_IwZdnGPU/edit?usp=sharing
* Will produce this result: https://sheetsite.github.io/#1LOIAjq90NeDJ3LEErShFGL7P7EC05KK-cV_IwZdnGPU

## Contributions
Pull requests are welcome, provided they are adhere to:
* Retain backwards compatibility with previously configured sheets
* Bug fixes welcome
* Additional features are welcome if they are minimalistic and generic
* Code should remain tidy and use the latest JS conventions.
* UglifyJS via https://skalman.github.io/UglifyJS-online/ is used for JS compression.