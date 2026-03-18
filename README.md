# CDN

This repository serves as a Content Delivery Network (CDN) for the InfoTools Chrome Extension. It hosts all static assets (images, icons, JSON data) required by the extension.

## Structure

The `assets/` directory contains all the media files used by the extension.

## Usage

The InfoTools Chrome Extension fetches its configuration and assets from this CDN using the `links.json` file as the primary manifest.

## Updating Assets

To update an asset:
1.  Add or edit the image in the `assets/` directory.
2.  Ensure the filename matches the name used in `links.json`.
3.  Commit and push the changes to this repository.
4.  The extension will automatically pick up the new assets on the next load or update cycle.