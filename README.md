# Rewind

Rewind finds the exact moment in archival audio from a plain-language description, and shows the source so you can verify it before it airs.

Built as the MVP for Product Lab (Week 4).

## Features
- **Plain-language search:** describe a clip the way you remember it; matching works by meaning, not exact keywords.
- **Jump to the moment:** each result shows the matching transcript line, its timestamp, and where it falls in the recording.
- **Source card:** speaker, mission, date, and a link to the original transcript with every result.

## Demo archive
The demo searches real NASA air-to-ground transcripts (US government works, public domain):
- Apollo 11 lunar landing
- Apollo 11 first moonwalk
- Apollo 13 "we've had a problem"

## Run it
It's a single `index.html` file with no build step. Open it in a browser, or deploy it on Vercel (framework: Other).
