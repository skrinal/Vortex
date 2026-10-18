# Media to capture

Shoot all at the same window width, dark mode. Replace the slots referenced in `../README.md`.

| File | What to capture (route in VortexDashboard) | Type |
|---|---|---|
| `hero.png` | done - overview cockpit (currently the xx12x capture) | PNG |
| `dashboard.png` | `/dashboard/overview` cockpit | PNG |
| `instances.png` | `/dashboard/instances` list | PNG |
| `metrics.png` | `/dashboard/metrics` ApexCharts | PNG |
| `admin.png` | `/dashboard/admin` panel | PNG |
| `realtime.gif` | live status flip online/offline OR command palette | GIF |

GIF: keep ONE, < 5 MB, < 15 s, ~1000px wide.
Convert: `ffmpeg -i in.mp4 -vf "fps=12,scale=1000:-1" realtime.gif`
If > 10 MB, upload the mp4 to a GitHub release/issue and embed that asset URL instead of committing it.
