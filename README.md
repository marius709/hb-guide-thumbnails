# HB Guide Thumbnails

Public CDN source for the Healthbridge Nova and Healthbridge Clinical guide
catalogue thumbnails. Served via jsDelivr in each guide project's Apps Script
deployment (Google Drive image hosting isn't a real CDN and was slow with
30+ images loading on one catalogue page).

Each guide project's own build.py generates these from its own guides/ or
Guides/ folder — this repo is a build output, not maintained by hand.
