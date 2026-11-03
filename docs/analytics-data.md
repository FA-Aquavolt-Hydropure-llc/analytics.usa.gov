# Analytics data

The dashboard's live data is published by the Digital Analytics Program at
<https://analytics.usa.gov/data>. Production and local development should use
that feed rather than treating committed files under `ga4-data/` as current.

The committed `ga4-data/` files are local fixtures/snapshots. Their `taken_at`
values show when each export was generated; do not present them as current data
or refresh their timestamps by hand. To use fresh local files, generate a new
export with the official [18F analytics-reporter](https://github.com/18F/analytics-reporter)
and configure `data_url` to the directory serving that export. The dashboard
notes that GA4 reports may be sampled; refer to the source report metadata when
interpreting the figures.
