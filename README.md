# YoutubePlaylistParser = first draft
Extract duration of each video in playlist and title so can compute time required to watch all videos

## What the project does?

This script aims to pull in the playlist tiles and times from Youtube API. It targets exclusively public playlists, so does not need login credentials to access these. However, it does need a user-specific API key to access Youtube's API.

### Related notes:
- Google API requires developer credentials == like logging on
- Akin to Bloomberg terminal, where must log on to access the methods
- Accessing PUBLIC information does NOT require user OAuth key
- If wanted to access private playlist/ acocunt details, would need permission from the user in the form of an authentication key.
    - 2 keys would be needed: key to use API, key to access user data

## Why this project is useful?

USE CASE:
- Need to learn thematerial in a playlist to familiarise oneself with a topic
- Want to see average length of videos and time properties of playlist to come up with effecitve strategy for covering the content

## Navigating the Jupyter Notebook

The section "Youtube API" is where the script that successfully extracts the playlist data is implemented. There are large text outputs that display the large JSON objects returned by the Youtube API

## Contents page

### Using Youtube API in python 
  - Requesting JSON objects from youtube API

### Extract relevant info from JSON
  - Testing how to extract relevant info from JSON
  - Wanted to get: description, duration and URL data
  -
### Deconstructing the URL
  -  Trying to extract the video ID part of the URL

### Now get URLs
