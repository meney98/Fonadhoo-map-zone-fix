FONADHOO MAP - GitHub files

Upload ALL files in this ZIP to the same GitHub repository folder:
index.html
data.js
script.js
map.svg
houses.json
blocks.json
zones.json

ZONE FIX
- PH, SS01, SS02, SS03, SS04, SS05, SS06 and SS07 buttons support zones.json lists.
- A zones.json item can be a stable block ID such as BLOCK-1630 OR a current editable block/house name.
- Renaming a block in blocks.json does not break a zone that uses its BLOCK-#### ID.
- You can also set "area": "PH" (or SS01 ... SS07) in blocks.json or houses.json. The zone button will include it automatically, so you do not need to duplicate the name in zones.json.

IMPORTANT
The uploaded zones.json has empty house lists for all 8 zones. This package does not invent missing zone memberships. Add memberships to zones.json, or set the area field in houses.json/blocks.json.
