# NOAA (noaa)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

National Oceanic and Atmospheric Administration (NOAA) provides a suite of publicly accessible REST APIs delivering weather observations, forecasts, alerts, climate data, ocean conditions, and historical environmental records from the US federal government. The National Weather Service API offers real-time forecasts, active alerts, radar, and station observations across the continental United States and territories. NOAA also publishes the Climate Data Online API for historical climate datasets, the CO-OPS Tides and Currents API for water level and oceanographic data, and the Aviation Weather API for aeronautical weather products. All NOAA APIs are free to use as open government data with no licensing restrictions.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/noaa/refs/heads/main/apis.yml

**Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=noaa-api-evangelist&utm_content=repo

---

## Tags

Weather, Climate, Forecast, Alerts, Ocean, Tides, Aviation Weather, Government, Open Data, Environmental

---

## APIs

| Name | Base URL | Documentation |
|------|----------|---------------|
| National Weather Service API | https://api.weather.gov | https://www.weather.gov/documentation/services-web-api |
| Climate Data Online (CDO) API | https://www.ncdc.noaa.gov/cdo-web/api/v2 | https://www.ncdc.noaa.gov/cdo-web/webservices/v2 |
| CO-OPS Tides and Currents API | https://api.tidesandcurrents.noaa.gov/api/prod | https://tidesandcurrents.noaa.gov/api/ |
| Aviation Weather API | https://aviationweather.gov/api/data | https://aviationweather.gov/data/api/ |

---

## Plans, Rate Limits, and FinOps

| Resource | File |
|----------|------|
| Plans and Pricing | [plans/noaa-plans-pricing.yml](plans/noaa-plans-pricing.yml) |
| Rate Limits | [rate-limits/noaa-rate-limits.yml](rate-limits/noaa-rate-limits.yml) |
| FinOps | [finops/noaa-finops.yml](finops/noaa-finops.yml) |

All NOAA APIs are free public government services with no subscription fees or usage charges. The CDO API requires a free email-registered token with a limit of 5 requests/second and 10,000 requests/day. The Aviation Weather API is capped at 100 requests/minute.

---

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

---

## Common

| Type | URL |
|------|-----|
| Website | https://www.noaa.gov |
| Documentation | https://www.weather.gov/documentation |
| GitHub Org | https://github.com/NOAAGov |
| GitHub Org | https://github.com/weather-gov |
| LinkedIn | https://www.linkedin.com/company/noaa |
| Blog | https://www.noaa.gov/news |
| Status Page | https://www.weather.gov/im/tecnews |
| X | https://x.com/NWS |

---

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
