---
title: Error codes | Gengo API
---

# Error codes

Code values let you map your own localized message, and msg values are just sample error messages.

* 1000
: Authentication failed

* 1100
: api_sig is a required field

* 1150
: api_key is a required field

* 1200
: ts is a required field

* 1201
: ts must be numeric

* 1250
: data is a required field

* 1251
: JSON data cannot be decoded

* 1300
: type is a required field

* 1301
: job_type is not supported

* 1350
: body_src is a required field

* 1351
: Invalid body text

* 1400
: lc_src is a required field

* 1450
: lc_tgt is a required field

* 1500
: tier is a required field

* 1551
: language service is not supported

* 1601
: callback_url must be a valid URL

* 1651
: auto_approve must be 0 or 1

* 1701
: use_preferred must be 0 or 1

* 1751
: "custom_data" is over maximum storage limit (1kb)

* 1800
: jobs is a required field

* 1851
: as_group must be 0 or 1

* 1901
: process must be 0 or 1

* 1950
: These jobs cannot be grouped (they have different tiers, source or target languages)

* 1951
: You cannot group a single job

* 1952
: Ultra jobs cannot be grouped

* 2000
: body is a required field

* 2050
: job_id is a required field

* 2100
: Unauthorized job access

* 2150
: revision_id is a required field

* 2200
: Unauthorized revision access

* 2250
: Job is not reviewable

* 2251
: Job cannot be purchased (incorrect state)

* 2252
: Job cannot be cancelled (incorrect state)

* 2300
: comment is a required field

* 2350
: reason is a required field

* 2400
: captcha is a required field

* 2401
: Invalid captcha challenge

* 2450
: Invalid follow-up value

* 2500
: rating is a required field

* 2501
: services_api_error_codes_rating_restriction

* 2502
: services_api_error_codes_rating_restriction

* 2550
: Jobs' group id is missing

* 2600
: Unauthorized job group access

* 2650
: Invalid job status

* 2700
: Not enough credits - please top up

* 2750
: Unauthorized order access

* 2800
: API temporarily unavailable