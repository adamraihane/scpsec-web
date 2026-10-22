# SCPSEC website

Static public website for SCPSEC and FRTC, hosted on the SCPSEC VPS. Binary downloads are served from GitHub Releases and are not stored in this repository.

- `index.html`: Messenger downloads and guides.
- `wallet.html`: standalone wallet downloads and notices.
- `assits/`: styles, scripts, and platform logos.
- `ico/`: FRTC app icons.

Deploy static files to `/var/www/scpsec-site`. Keep `login.scpsec.cc` and `api.scpsec.cc` in their separate Nginx virtual hosts.