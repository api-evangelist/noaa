# NOAA (noaa)

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
