# eduaitorcpanel

Static builds for GoDaddy / cPanel shared hosting.

## Layout (maps 1:1 to `public_html`)

| Path in this repo | Upload / deploy to |
|-------------------|--------------------|
| `/` (root files) | `public_html/` → https://www.eduaitor.com |
| `/admin-dashboard/` | `public_html/admin-dashboard/` |
| `/admin/` | `public_html/admin/` (School ERP) |

## cPanel Git Version Control

1. Create repo in cPanel pointing at this GitHub URL.
2. Set deploy directory to `public_html` (or your domain docroot).
3. Pull / Update on deploy so root + `admin` + `admin-dashboard` land correctly.

## APIs (Render — not in this repo)

- Website CMS API: `eduaitor-website-backend.onrender.com`
- School ERP API: `eduaitor-api.onrender.com`

Built: 2026-08-25 13:08
