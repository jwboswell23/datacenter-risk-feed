# Data-Center Risk Feed (VA · OH · GA · TX)

Machine-readable outputs of the daily/weekly data-center project, moratorium and regulatory risk research. Consumed by an Excel dashboard via `WEBSERVICE()` / `FILTERXML()` using raw URLs of the form
`https://raw.githubusercontent.com/jwboswell23/datacenter-risk-feed/main/<name>.xml`.

Feeds: meta, states, gdp, top, catalysts, rhetoric, politicians, news, events (each as .xml / .csv / .json; XML kept under 30,000 characters for Excel). Full tables: `projects_full.csv`, `events_full.csv`, `rhetoric_full.csv`, `news_full.csv`.

Updated automatically — daily ~7:00 AM ET, weekly sweep Monday ~6:30 AM ET. Research outputs only; no personal data.
