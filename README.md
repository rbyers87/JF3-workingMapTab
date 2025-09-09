TX-JF
Texas - Jurisdiction Finder

Can take current location from cell phone to locate when law enforcement jurisdiciton you are in to report a crime.  

Uses TxDot gis website info for both county and city jurisdiciton boundaries.

County - https://gis-txdot.opendata.arcgis.com/datasets/TXDOT::texas-county-boundaries/about

City - https://gis-txdot.opendata.arcgis.com/datasets/TXDOT::texas-cities/about

Trying to mimic how 9-1-1 decides jurisdiciton.  App provides a non-emergency phone number, address, and website if one is available.


npm install --legacy-peer-deps

expo start -c

to upload/update your folder to github:
1. git add .
2. git commit -m "added github instructions to readme"
3. git push origin main


EXPO instructions:
eas build --platform android --profile preview

To push update from github to local folder:

cd path/to/your/project

git pull origin main

Here’s a one-line command that completely resets your folder to match the GitHub repo, discarding all local changes:

git fetch origin && git reset --hard origin/main && git clean -fd

