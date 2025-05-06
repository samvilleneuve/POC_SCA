# POC_SCA

Vulnerable examples to allow findings detection on Checkmarx (or other Application Security tools) related to vulnerable packages

## Usefull links
The Bootstrap Blog: https://blog.getbootstrap.com/
XSS affecting bootstrap package: https://security.snyk.io/vuln/SNYK-JS-BOOTSTRAP-7444580
Bootstrap XSS: https://gist.github.com/BlackFan/e968b5209637952cca1580dc8ffdfde6
XSS in bootstrap data-target attribute: https://chawdamrunal.medium.com/xss-in-bootstrap-data-target-attribute-5f0c534a87a3
CVE-2024-6531 https://www.herodevs.com/vulnerability-directory/cve-2024-6531?bootstrap-nes

## Checkmarx One Results
No SAST findings (despite the case in bootstrap_Local_3.3.7.html)
Some SCA findings on Bootstrap vulnerable packages stored locally.

## Improvement
Build a more sophisticated case to induce a SAST finding