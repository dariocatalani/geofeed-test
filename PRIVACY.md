# Privacy Policy for Hotwire Geolocation Checker

**Last updated:** 2025-10-04

## Who we are
This tool (“Hotwire Geolocation Checker”) is operated by [Hotwire / Dario Catalani].  
Contact: [email or issues link]

## What this tool does
When a user enters an IP or CIDR, the tool calls third-party geolocation APIs to return country/region/city and compares them with our official geofeed.

## Data we process
- **User input:** IP address or CIDR provided by the user.
- **Requests sent to providers:** The input IP and our API credentials are sent to:
  - **MaxMind GeoIP2 City** (`https://geoip.maxmind.com/geoip/v2.1/city/{ip}`)
  - **IP2Location.io** (`https://api.ip2location.io/?key=...&ip={ip}`)
  - **IPinfo** (`https://ipinfo.io/{ip}/json?token=...`)
- **Responses received:** Geolocation metadata (e.g., country, region, city).

## Purpose of processing
To verify geolocation for network administration and data quality checks against our geofeed (`https://github.com/hotwireipadmin/geofeed`).

## Legal basis / user expectations
Processing is performed at the user’s request to provide the service’s core functionality.

## Retention
- We do **not** store provider responses server-side.  
- Chat content may be retained in the user’s ChatGPT account per OpenAI’s terms.  
- Providers may keep request logs per their policies.

## Sharing with third parties
We share the input IP with:
- **MaxMind** (see MaxMind Privacy/Terms)
- **IP2Location.io** (see IP2Location Privacy/Terms)
- **IPinfo** (see IPinfo Privacy/Terms)

We do not sell personal data.

## Security
- API keys are configured as secrets in the GPT and are not shown to users.
- Transmission to providers uses HTTPS.

## User controls
- Do not use real personal IPs if you are concerned about privacy.
- You can request deletion of project issues or PRs in this repo via the contact above.

## Changes
We may update this policy and will revise the “Last updated” date above.

