# ratecard-terms-frontend-static

This is a frontend which pulls content from https://cockpit.jerseypost.com which is an Open Source CMS.

See https://jerseypost.atlassian.net/wiki/spaces/ADT/pages/2177990667/Rate+Card+Terms+Server for full details

## Developent

To modify, I recommend using a GitHub Codespace. This provides a full web based IDE integrated with GitHub and our Azure deployemnt GitHub Actions/ Once in the Codespace, choose 'files' icon and create a new branch by clicking on `main` in the footer bar.

Committing to the branch and pushing to origin will *not* deploy to production.
You will need to merge you branch to `main` in order to automatically deploy to the Azure static web app.
See confluence link above for details.