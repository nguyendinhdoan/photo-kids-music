# Photo Kids - Premium Music Library

Premium music tracks for the [Photo Kids](https://myphotokids.com) app.

## Structure

- `catalog.json` — Track metadata (version, track list with download URLs)
- `*.m4a` — Audio files (AAC 192k, attached to GitHub Release)

## Usage

The Photo Kids app fetches `catalog.json` from the latest GitHub Release to discover available premium tracks. Users can then download individual tracks on-demand.

## Adding Tracks

1. Add track files to a GitHub Release
2. Update `catalog.json` with track metadata
3. Upload updated `catalog.json` to the release
