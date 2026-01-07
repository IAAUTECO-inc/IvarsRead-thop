# Contributing to Ivarsread

As an institutional-grade server for critical data, Ivarsread requires the highest standards of code quality and security.

## 1. Developer Certificate of Origin (DCO)
To maintain legal transparency, all contributions must be signed-off. By including a `Signed-off-by` line in your commit messages, you certify that you have the right to submit the code under the project's license.
*Command:* `git commit -s -m "Brief description of changes"`

## 2. Technical Standards
* **Backend:** Python 3.10+ (PEP 8 compliant) or C++17 (for performance-critical modules).
* **Database:** Migrations must be documented and tested for PostgreSQL/TimescaleDB.
* **Security:** No external network dependencies in the core analysis engine. All APIs must be authenticated via mTLS or the AI Password protocol (v2+).

## 3. Pull Request Process
1. Fork the repository and create a feature branch.
2. Ensure 100% pass rate on existing unit tests.
3. Submit a PR with a detailed description of the analytical model or infrastructure change.
4. Every PR requires approval from two core maintainers.

## 4. Documentation
All new features must include Doxygen or Sphinx-compliant documentation and a security impact assessment.
