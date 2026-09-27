NOCI STYLING — deployable site
================================
Everything here is static. No build step, no server, no dependencies.

FASTEST WAY LIVE (about 5 minutes, free)
1. Go to app.netlify.com/drop
2. Drag this whole folder onto the page
3. You get a live URL immediately, e.g. noci-styling.netlify.app
4. Site settings > Domain management > add styling.shopnoci.com
   Netlify shows you one CNAME record to add at your DNS provider

BEFORE YOU SEND TRAFFIC
- Buttons currently go to https://intheb.ag — change if the quiz moves
- Add your Meta + TikTok pixels where the comment says PIXELS in index.html
- Add favicon.ico to this folder
- /privacy and /terms in the footer are not written yet. You need a real
  privacy policy before collecting photos.
- Replace styling.shopnoci.com in the meta tags with your real domain,
  or link previews will point at the wrong place.

FILES
  index.html   the whole page, self-contained
  img/         13 photographs + og.jpg (link preview card)
