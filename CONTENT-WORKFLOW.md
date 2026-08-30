# Pedals & Paradoxes — Content Workflow

You do NOT need to edit HTML.

For a new piece, send ChatGPT:
1. The writing (rough is fine).
2. Date.
3. Location.
4. Any photographs.
5. GPX track if you have one.
6. Anything that should link to the piece.

ChatGPT can then:
- edit the piece while preserving the voice
- create the content file
- add/order photos
- add the journal entry to the index
- connect it to the journey/map
- update the Now section when appropriate
- test links and mobile layout
- return an updated deployable site

## Content folders

`content/journal/` — written pieces
`content/photos/` — photo metadata/links
`content/journey/` — GPX and journey data
`content/about/` — about page text
`content/gear/` — bike and gear text
`content/now.md` — current state

## Deployment

The site is intended to be hosted on Netlify and connected to a Git repository later.

For the first deployment, upload/publish the site as a static site. Once the Git workflow is connected, future approved changes can be deployed from the repository.

## Important

Never put private tracking credentials, Garmin account passwords, API keys, or other secrets into this repository.
