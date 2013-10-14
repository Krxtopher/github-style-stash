## Overview

This Google Chrome extension adds cosmetic improvements to Markdown rendering in Stash. Note that the extension only applies itself to Markdown documents at `stash.resource.com`. If you'd like to use this extension for other Stash installations you'll need to download the source code and modify the `content_scripts.matches` property in the `manifest.json` file.

Also note that the extension does *not* enable Github-flavored Markdown syntax, so you'll still want to constrain yourself to the official Markdown syntax while working with Stash.

## Installation

1. Download the pre-built Chrome estension `distribution/GoogleStyleStash.crx`.
2. In Google Chrome, select **Window > Extensions** to open the Extensions tab.
3. Drag the `GoogleStyleStash.crx` extension into the Extensions tab area.

That's it! Any Markdown files you view at stash.resource.com will be automatically styled to match Github's style.

## Bugs?

This extension has only been lightly tested. If you find cases where it doesn't display some bit of Markdown as you would expect please open an issue!