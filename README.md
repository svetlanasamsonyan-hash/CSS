# CSS

Custom UI overrides for iGaming sites. One folder per project.

## Structure
CSS/
  mrjindev/
    style.css      # uploaded into the backoffice CSS input
    script.js      # only when a change needs JS (loaded via jsDelivr)
    assets/        # icons / images, served via jsDelivr

## Workflow
1. Edit mrjindev/style.css.
2. Upload that file into the backoffice CSS input to apply it live.
3. Commit + push to keep history.
4. For JS or hosted images, push first, then reference with a pinned jsDelivr
   URL using the commit hash:
   https://cdn.jsdelivr.net/gh/<user>/CSS@<commit>/mrjindev/script.js
