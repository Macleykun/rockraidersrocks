# rockraiders.rocks
Git repo for the website rockraiders.rocks

## Validations
[HTML valid](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Frockraiders.rocks)
[CSS valid](https://jigsaw.w3.org/css-validator/validator?profile=css3svg&uri=https%3A%2F%2Frockraiders.rocks%2F&usermedium=all&vextwarning=&warning=1)
Pagespeed Desktop score:

![Alt text](./.github/.lighthouse/PSIRM.svg)

## Automations

[![GitHub Actions Workflow Critical CSS Status](https://img.shields.io/github/actions/workflow/status/Macleykun/rockraidersrocks/critical_css.yml?label=criticalCSS)](https://github.com/Macleykun/rockraidersrocks/actions/workflows/critical_css.yml)
[![GitHub Actions Workflow Generate Sitemap Status](https://img.shields.io/github/actions/workflow/status/Macleykun/rockraidersrocks/generate_sitemap.yml?label=Generate%20Sitemap)](https://github.com/Macleykun/rockraidersrocks/actions/workflows/generate_sitemap.yml)
[![GitHub Actions Workflow Generate AVIF Status](https://img.shields.io/github/actions/workflow/status/Macleykun/rockraidersrocks/generate_avif.yml?label=Generate%20AVIF)](https://github.com/Macleykun/rockraidersrocks/actions/workflows/generate_avif.yml)
[![GitHub Actions Workflow Lighthouse Benchmark Status](https://img.shields.io/github/actions/workflow/status/Macleykun/rockraidersrocks/lighthouse.yml?label=Lighthouse)](https://github.com/Macleykun/rockraidersrocks/actions/workflows/lighthouse.yml)
[![GitHub Actions Workflow Run Mozilla Observatory Report Status](https://img.shields.io/github/actions/workflow/status/Macleykun/rockraidersrocks/mozzila_observatory_report.yml?label=Mozilla%20Observatory%20Report)](https://github.com/Macleykun/rockraidersrocks/actions/workflows/mozzila_observatory_report.yml)
[![GitHub Actions Workflow Run Full OWASP Web Security Scan Status](https://img.shields.io/github/actions/workflow/status/Macleykun/rockraidersrocks/owasp_full_scan.yml?label=OWASP%20Web%20Security%20Full%20Scan)](https://github.com/Macleykun/rockraidersrocks/actions/workflows/owasp_full_scan.yml)
[![GitHub Actions Workflow Retrieve Pagespeed Results Status](https://img.shields.io/github/actions/workflow/status/Macleykun/rockraidersrocks/pagespeed.yml?label=Pagespeed)](https://github.com/Macleykun/rockraidersrocks/actions/workflows/pagespeed.yml)
[![GitHub Actions Workflow Minimize CSS Status](https://img.shields.io/github/actions/workflow/status/Macleykun/rockraidersrocks/purgecss.yml?label=Minifity%20CSS)](https://github.com/Macleykun/rockraidersrocks/actions/workflows/purgecss.yml)
[![GitHub Actions Workflow Dependabot Status](https://img.shields.io/github/actions/workflow/status/Macleykun/rockraidersrocks/dependabot.yml)](https://github.com/Macleykun/rockraidersrocks/actions/workflows/dependabot/dependabot-updates)

## Security Headers and you

This website is hosted fully on [CloudFlare JAM](https://www.cloudflare.com/learning/performance/what-is-jamstack/), so we don't have access to a webserver so configuring [HTTP Headers](https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Headers) is done using a [_headers](https://github.com/Macleykun/rockraidersrocks/blob/main/_headers) file. We try to configure these as tightly as possible and verify it using [securityheaders.com](https://securityheaders.com/?q=https%3A%2F%2Frockraiders.rocks%2F&followRedirects=on), at the time of writing this has the hightest score (A+).
