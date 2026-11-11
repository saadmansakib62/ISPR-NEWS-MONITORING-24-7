# ISPR News Monitoring System

A responsive, single-page dashboard for monitoring public national and international news headlines. The site groups headlines into Bangladesh, Security & Defence, and International desks, with search, filters, source links, and periodic refresh.

## Run locally

Open `index.html` in a browser with an internet connection. Headlines are retrieved from Google News RSS through the public rss2json service, so loading the feeds requires access to those services.

## Deploy

The site is static and can be deployed from the repository root using GitHub Pages (`main` / `root`) or any static hosting provider. `manifest.json` enables install metadata for supported browsers.

## Important

This is an independent open-source news monitor, not an official ISPR website. Headlines are not verified by the dashboard; consult the original publisher for context and confirmation.