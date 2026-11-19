# snip — YouTube Shorts editing planner

A responsive, browser-only prototype for turning moments from long-form YouTube videos into short-form clip plans.

## Run it

Open `index.html` in a browser, or serve this folder with any static file server. No build step or dependencies are required.

## What it does

- Loads a privacy-enhanced YouTube embed preview from a pasted video link.
- Lets you define clip titles, time ranges, output aspect ratios, and a captioning preference.
- Builds a clip list and exports a JSON edit plan with source timestamps.

## Important limitation

This prototype does not download, cut, or render video or generate captions. The exported JSON is timing metadata only. To produce finished Shorts, connect a media-processing backend and a rights-compliant source workflow, and only edit video you own or are authorized to use.
