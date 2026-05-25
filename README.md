# Media Rights Licensing Suite

Wave:
- Portfolio next-20 completion batch

Source candidates represented:
- `AIMediaRightsLicensingAssistant`
- `AIMediaRightsLicensingOperations`
- `AIMediaRightsLicensingAnalytics`
- `AIMediaRightsLicensingWorkflow`

This suite is a runnable merged app with one login, one dashboard, one feature-first sidebar, PostgreSQL-backed records/documents/notifications/audit, role behavior, and smoke coverage.

## Local Run

```bash
cd /Users/erolakarsu/projects/merged/media-rights-licensing-suite
./start.sh
```

Local URL:
- `http://127.0.0.1:5790`

Seeded users:
- `admin@media-rights-licensing.local / admin123`
- `manager@media-rights-licensing.local / manager123`
- `analyst@media-rights-licensing.local / analyst123`

## Validation

```bash
cd /Users/erolakarsu/projects/merged/media-rights-licensing-suite/frontend
npm run typecheck
SMOKE_BASE_URL=http://127.0.0.1:5790 npm run smoke
```
