# qnap-store-mirror

Mirror of [pdulvp/qnap-store](https://github.com/pdulvp/qnap-store) with a one-line fix to the XML declaration (`<? xml ... ?>` → `<?xml ... ?>`) so QNAP's App Center can parse it.

GitHub Actions re-syncs upstream every 6 hours.

Use the raw URLs in QTS → App Center → App Repository:
- Pre-releases: `https://raw.githubusercontent.com/<your-user>/qnap-store-mirror/main/repos-prereleases.xml`
- Stable: `https://raw.githubusercontent.com/<your-user>/qnap-store-mirror/main/repos.xml`
