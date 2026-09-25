SURVEY MARK EXPLORER - SOUTH AFRICA

To open the website: double-click index.html in this folder.
(Needs an internet connection for the background map and place search.
The beacon data itself is stored locally in the data folder.)

Folder contents
  index.html  the ready-to-open website
  data\       beacon data (.geojson) plus .js copies used when opened from disk
  source\     the source code, for editing. See source\README.md for how to
              run the developer server, change map/search providers, and add
              or replace beacon data. After editing, run "npm run build" in
              source\ and copy source\dist\index.html and source\dist\data\
              here.

Do not open source\index.html directly. It is a development template and
shows an unstyled page outside the developer server.
