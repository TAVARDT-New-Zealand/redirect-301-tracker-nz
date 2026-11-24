# HTTP 301/302 Redirect and Hop Chain Auditor

[![Redirect 301 Tracker](https://img.shields.io/badge/TAVARDT-Redirect%20301-5b3cf5.svg)](https://tools.tavardt.com/nz/redirect-checker/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Audits redirect paths, infinite loop detection, link equity conservation, and crawl efficiency in New Zealand.

Developed and maintained by the digital systems and crawl optimization division of **TAVARDT New Zealand**.

***

## HTTP Redirect and Hop Chain Audit Capabilities

* **Complete Hop Chain Tracing**: Comprehensive hop-by-hop tracking across 301, 302, 307, and 308 HTTP redirect responses.
* **Infinite Redirect Loop Detection**: Immediate identification of cyclic paths causing critical browser and crawler failures.
* **Link Equity and PageRank Conservation**: Alerts against long redirect chains (> 3 hops) that dilute equity and waste crawl budget.
* **Mixed Protocol Verification**: Identification of insecure intermediary downgrades from HTTPS to HTTP.
* **Redirect Efficiency Health Score**: Quantitative 0 to 100 score with prioritized technical remediation steps.

***

## Installation and Execution

Requires Python 3.8 or higher.

```bash
git clone https://github.com/TAVARDT-New-Zealand/redirect-301-tracker-nz.git
cd redirect-301-tracker-nz
python redirect_tracker.py https://company.co.nz
```

To output results in structured JSON format:

```bash
python redirect_tracker.py https://company.co.nz -json
```

***

## Comprehensive Web Diagnostic

For full web verification and deep redirect chain inspections:

* **Official Redirect Checker Tool**
* **TAVARDT New Zealand Enterprise Portal**

***

## Technical SEO and Site Migration Advisory

For platforms operating across New Zealand under W3C Standards and NZ Digital Performance Guidelines, contact **TAVARDT New Zealand**.
