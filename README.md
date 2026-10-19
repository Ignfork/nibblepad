# NibblePad Agent ($NIBBLE)

A single-file website. Upload `index.html` to GitHub Pages, Netlify, Vercel or any host, and it works as-is.

## Edit before launch
At the top of the `<script>` in index.html:

```js
var CONFIG = {
  xUrl:    'https://x.com/NibblePad',
  mint:    '',                        // optional: $NIBBLE mint, adds a $NIBBLE quick-search in Market Watch
  pumpUrl: 'https://pump.fun/create'  // where "Continue to Pump.fun" goes
};
```

## Features
- Colorful pixel title and a 3D voxel hamster (Nibs) that follows your mouse, blinks, and crunches seeds when clicked
- The Crew: six critter agents (hamster, bunny, squirrel, mouse, raccoon, beaver) with filters
- Agent Desk: pick a critter and chat. Browser-side tools write names, hooks, lore, posts, launch plans, color palettes, logo briefs, checklists, ticker checks and story scans
- Launch Pad: draft editor (template, name, ticker, story, X, image), live preview, save draft, download a launch kit (JSON + 1200×630 card), read-only Phantom connect, hand-off to Pump.fun
- Market Watch: live public Solana pair search via the DEX Screener API
- How it works, scrolling marquee, floating "Need a nibble?" button
