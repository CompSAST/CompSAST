# SAST scanners comparison

[![Semgrep][Semgrep]][Semgrep-url]
[![CodeQL][CodeQL]][CodeQL-url]
[![SonarQube][SonarQube]][SonarQube-url]
[![PVS-Studio][PVS-Studio]][PVS-Studio-url]
[![Opengrep][Opengrep]][Opengrep-url]
[![PMD][PMD]][PMD-url]
[![Joern][Joern]][Joern-url]

The following repository aimed to research what popular static analisys security testing (SAST) tools are best
in vulnerabilities finding. The experiment would take several SAST instruments that able to multi-language scan in application, therefore, tools like [Bandit](https://github.com/pycqa/bandit) or [Clang-analizer](https://clang-analyzer.llvm.org/) are not in the testing list.

#### SAST tools to compare:

- [Semgrep](https://semgrep.dev/)
- [CodeQL](https://codeql.github.com/)
- [SonarQube](https://www.sonarsource.com/products/sonarqube/advanced-security/)
- [PVS-Studio](https://pvs-studio.com/pvs-studio/?utm_source=website&utm_medium=github&utm_campaign=open_source)
- [Opengrep](https://www.opengrep.dev/)
- [PMD](https://pmd.github.io/)
- [Joern](https://joern.io/)

#### Benchmarks to test

- [IAMeter](github.com/POSIdev-community/) by Positive Technologies for Go, Java, Python
- [OWASP Benchmark](https://github.com/OWASP-Benchmark) for Java, Python
- [NIST Juliet](https://samate.nist.gov/SARD/test-suites) for Java, C/C++, C#

Additional testing on vulnerable by design applications that are not built as scanning tools benchmark:

- [OWASP JuiceShop](https://github.com/juice-shop/juice-shop) for JavaScript/TypeScript

<!-- badge links -->
[Semgrep]: https://img.shields.io/badge/Semgrep-1F7A8C?style=for-the-badge
[Semgrep-url]: https://semgrep.dev/
[CodeQL]: https://img.shields.io/badge/CodeQL-2F67B1?style=for-the-badge
[CodeQL-url]: https://codeql.github.com/
[SonarQube]: https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge
[SonarQube-url]: https://www.sonarsource.com/products/sonarqube/advanced-security/
[PVS-Studio]: https://img.shields.io/badge/PVS--Studio%20OSS-8A3FFC?style=for-the-badge
[PVS-Studio-url]: https://pvs-studio.com/pvs-studio/?utm_source=website&utm_medium=github&utm_campaign=open_source
[Opengrep]: https://img.shields.io/badge/Opengrep-0F172A?style=for-the-badge
[Opengrep-url]: https://www.opengrep.dev/
[PMD]: https://img.shields.io/badge/PMD-6B7280?style=for-the-badge
[PMD-url]: https://pmd.github.io/
[Joern]: https://img.shields.io/badge/Joern-B45309?style=for-the-badge
[Joern-url]: https://joern.io/
