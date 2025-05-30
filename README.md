# Coda Embed Test

This is a simple test page for embedding a Coda document in a GitHub Pages site.

## Setup Instructions

1. Fork this repository
2. Replace the Coda embed URL in `index.html`:
   - Find your Coda document's embed URL by:
     - Opening your Coda document
     - Click the "Share" button
     - Select "Embed"
     - Copy the provided URL
   - Replace `YOUR_DOC_ID/YOUR_PAGE_ID` in the iframe src with your actual Coda embed URL

3. Enable GitHub Pages:
   - Go to your repository settings
   - Scroll down to the "GitHub Pages" section
   - Select the main branch as the source
   - Click Save

Your page will be available at `https://[your-username].github.io/[repository-name]`

## Notes

- The embed is set to 800px height by default. You can adjust this in the CSS if needed.
- Make sure your Coda document is set to be publicly accessible for the embed to work. 