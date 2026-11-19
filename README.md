# sca-vuln-python-flask

> **WARNING: Intentionally vulnerable.** Test fixture for Software Composition Analysis (SCA) tools.
> Do not deploy. Dependencies are pinned to versions with known CVEs.

**Ecosystem:** PyPI (pip / requirements.txt)

## Expected findings (non-exhaustive)
- Flask 0.12.2: CVE-2018-1000656, CVE-2019-1010083
- Jinja2 2.10: CVE-2019-10906, CVE-2020-28493
- requests 2.19.1: CVE-2018-18074
- urllib3 1.24.1: CVE-2019-11324, CVE-2020-26137
- PyYAML 5.3: CVE-2020-14343 (arbitrary code exec)
- Pillow 8.1.0: many (CVE-2021-25287, ...)
- cryptography 3.2: CVE-2020-36242
- paramiko 2.4.1: CVE-2018-1000805
