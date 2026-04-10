# ATLS Retired Hosts

Redirect-only Netlify site for retired `*.abovethelinesafety.com` dashboard hostnames.

Source of truth:
- `C:\Utils\atls-weather-dashboard\config\deployments.json`

Generated artifact:
- `_redirects`

Update flow:
1. Regenerate from `atls-weather-dashboard`
2. Commit the new `_redirects`
3. Let Netlify publish the redirect-only site
