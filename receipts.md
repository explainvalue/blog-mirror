# Wayback Machine capture receipts
Appended by the nightly archive job. Each line links a live URL to its dated snapshot.

## 2026-08-07T17:37:28Z
- https://explainvalue.ai/ — skipped: submit failed: 401 Client Error: UNAUTHORIZED for url: https://web.archive.org/save
- https://explainvalue.ai/blog — skipped: submit failed: 401 Client Error: UNAUTHORIZED for url: https://web.archive.org/save
- https://explainvalue.ai/learn — skipped: submit failed: 401 Client Error: UNAUTHORIZED for url: https://web.archive.org/save
- https://explainvalue.ai/blog/portfolio — skipped: submit failed: 401 Client Error: UNAUTHORIZED for url: https://web.archive.org/save
- https://explainvalue.ai/terms — skipped: submit failed: 401 Client Error: UNAUTHORIZED for url: https://web.archive.org/save
- https://explainvalue.ai/privacy — skipped: submit failed: 401 Client Error: UNAUTHORIZED for url: https://web.archive.org/save
- https://explainvalue.ai/blog/gs-ms-priced-forever-july-2026 — skipped: submit failed: 401 Client Error: UNAUTHORIZED for url: https://web.archive.org/save
- https://explainvalue.ai/blog/gpor-ep-sotp-july-2026 — skipped: submit failed: 401 Client Error: UNAUTHORIZED for url: https://web.archive.org/save
- https://explainvalue.ai/blog/bank-cost-of-equity-correction-june-2026 — skipped: submit failed: 401 Client Error: UNAUTHORIZED for url: https://web.archive.org/save
- https://explainvalue.ai/blog/structural-fcf-breaks-may-2026 — skipped: submit failed: 401 Client Error: UNAUTHORIZED for url: https://web.archive.org/save
- https://explainvalue.ai/blog/fslr-policy-trade-may-2026 — skipped: submit failed: 401 Client Error: UNAUTHORIZED for url: https://web.archive.org/save
- https://explainvalue.ai/blog/hban-near-book-may-2026 — skipped: submit failed: 401 Client Error: UNAUTHORIZED for url: https://web.archive.org/save
- https://explainvalue.ai/blog/bank-regulatory-tiers-may-2026 — skipped: submit failed: 401 Client Error: UNAUTHORIZED for url: https://web.archive.org/save
- https://explainvalue.ai/blog/usb-franchise-discount-may-2026 — skipped: submit failed: 401 Client Error: UNAUTHORIZED for url: https://web.archive.org/save
- https://explainvalue.ai/blog/bmy-pharma-sotp-april-2026 — skipped: submit failed: 401 Client Error: UNAUTHORIZED for url: https://web.archive.org/save
- https://explainvalue.ai/blog/pharma-platform-rho-april-2026 — skipped: submit failed: 401 Client Error: UNAUTHORIZED for url: https://web.archive.org/save
- https://explainvalue.ai/blog/unh-sotp-april-2026 — skipped: submit failed: 401 Client Error: UNAUTHORIZED for url: https://web.archive.org/save
- https://explainvalue.ai/learn/what-is-a-dcf-apple — skipped: submit failed: 401 Client Error: UNAUTHORIZED for url: https://web.archive.org/save
- https://explainvalue.ai/static/briefings/financials_sector_20260516.pdf — skipped: submit failed: 401 Client Error: UNAUTHORIZED for url: https://web.archive.org/save
- https://explainvalue.ai/static/briefings/financials_sector_20260725.pdf — skipped: submit failed: 401 Client Error: UNAUTHORIZED for url: https://web.archive.org/save
- https://explainvalue.ai/static/briefings/healthcare_sector_20260419.pdf — skipped: submit failed: HTTPSConnectionPool(host='web.archive.org', port=443): Max retries exceeded with url: /save (Caused by NewConnectionError('<urllib3.connection.HTTPSConnection object at 0x7fa8e65cf9d0>: Failed to establish a new connection: [Errno 111] Connection refused'))
- https://explainvalue.ai/static/briefings/healthcare_sector_20260425.pdf — skipped: submit failed: HTTPSConnectionPool(host='web.archive.org', port=443): Max retries exceeded with url: /save (Caused by NewConnectionError('<urllib3.connection.HTTPSConnection object at 0x7fa8e65cfc50>: Failed to establish a new connection: [Errno 111] Connection refused'))
- https://explainvalue.ai/sitemap.xml — skipped: submit failed: HTTPSConnectionPool(host='web.archive.org', port=443): Max retries exceeded with url: /save (Caused by NewConnectionError('<urllib3.connection.HTTPSConnection object at 0x7fa8e65cf750>: Failed to establish a new connection: [Errno 111] Connection refused'))
- https://github.com/explainvalue/blog-mirror/commits/main — skipped: submit failed: HTTPSConnectionPool(host='web.archive.org', port=443): Max retries exceeded with url: /save (Caused by NewConnectionError('<urllib3.connection.HTTPSConnection object at 0x7fa8e64ac410>: Failed to establish a new connection: [Errno 111] Connection refused'))

## 2026-08-07T19:05:00Z — manual reconciliation
The 18:47 UTC sweep submitted all 24 URLs; roughly the first six
captures completed before archive.org's rate protection re-engaged,
and the polling step failed before receipts could be recorded.
Verified via Wayback lookup (third-party fetch):
- https://explainvalue.ai/ -> https://web.archive.org/web/20260807184801/https://explainvalue.ai/
- https://explainvalue.ai/blog/portfolio -> https://web.archive.org/web/20260807184825/https://explainvalue.ai/blog/portfolio
Remaining URLs (blog posts, learn, PDFs, sitemap, mirror commits) will
be captured by the next nightly run.

## 2026-08-07T21:31:30Z — single-capture canary
- https://explainvalue.ai/blog/unh-sotp-april-2026 -> https://web.archive.org/web/20260807213101/https://explainvalue.ai/blog/unh-sotp-april-2026
