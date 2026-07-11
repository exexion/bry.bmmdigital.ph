# bry.bmmdigital.ph

Static portfolio site snapshot from VM2.

- Live source captured from: `/var/www/bry-portfolio`
- VM: VM2 (`ubuntu@134.185.88.154`)
- Local full backup: `../_vm2_live_backup_20260711/bry-portfolio`
- This repository stores the clean deployable static site, excluding historical `index.html.bak-*` files kept only in the local backup.

## Current deployment note

As of the initial snapshot, no active Nginx `server_name bry.bmmdigital.ph`, systemd service, or PM2 app was found for this site on VM2. The folder exists on VM2, but the domain does not appear to be wired in the active web server configuration.
