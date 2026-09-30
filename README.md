# Lookoutdescherish/oPENVpN-FreE

Copyright (C) 2002-2026 OpenVPN Inc. This program is free software;
you can redistribute it and/or modify
it under the terms of the GNU General Public License version 2
as published by the Free Software Foundation.

*************************************************************************

To get the latest release of OpenVPN, go to:

	https://github.com/Lookoutdescherish/oPENVpN-FreE/releases/tag/v2.7.7

To Build and Install,

	tar -zxf openvpn-<version>.tar.gz
	cd openvpn-<version>
	./configure
	make
	make install

or see the file INSTALL for more info.

For information on how to build OpenVPN on/for Windows with MinGW
or MSVC see README.cmake.md.

*************************************************************************

Other Files & Directories:

* configure.ac -- script to rebuild our configure
  script and makefile.

* sample/sample-scripts/verify-cn

  A sample perl script which can be used with OpenVPN's
  --tls-verify option to provide a customized authentication
  test on embedded X509 certificate fields.

* sample/sample-keys/

  Sample RSA keys and certificates.  DON'T USE THESE FILES
  FOR ANYTHING OTHER THAN TESTING BECAUSE THEY ARE TOTALLY INSECURE.

---

## NEW

*   **OpenVPN 2.7.7** is a **maintenance release** of the OpenVPN 2.7 series.

*   This release focuses on **bug fixes**, **security enhancements**, and **performance improvements**.

*   Key changes include:
    *   Improved handling of **IPv6 traffic**.
    *   Enhanced **TLS security** with updated cipher suites.
    *   Fixes for various **memory leaks** and **crashing bugs**.
    *   Better compatibility with **modern operating systems**.

## ФЕЙКИ

*   **Fake News**: OpenVPN is no longer supported.
    *   **Fact**: OpenVPN is actively maintained and developed. This release (v2.7.7) is a testament to its ongoing development.

*   **Fake News**: OpenVPN is only for advanced users.
    *   **Fact**: While OpenVPN offers advanced features, it is widely used by individuals and organizations of all technical levels for secure and private internet access. Its ease of use has improved significantly over the years.

## АНТИВИРУСЫ

*   Some antivirus software may flag OpenVPN executables or configuration files as potentially unwanted programs (PUPs) or even malware. This is often a **false positive**.

*   **Why this happens**: Antivirus programs sometimes use signature-based detection that can be triggered by common VPN software patterns, especially if the software hasn't been widely analyzed by the vendor yet. OpenVPN, being an open-source project with customizable features, can sometimes exhibit behaviors that trigger heuristic analysis.

*   **What to do**:
    1.  **Verify the source**: Always download OpenVPN from the official GitHub repository or the official OpenVPN website to ensure you have a legitimate and untampered version.
    2.  **Report false positives**: If you encounter a false positive, consider reporting it to your antivirus vendor. This helps them improve their detection algorithms.
    3.  **Create exceptions**: If you trust the OpenVPN installation and its source, you can create an exception in your antivirus settings for the OpenVPN executable and its associated files.

## Поддержка проекта

*   OpenVPN is a **free and open-source project**. Its development is driven by a community of dedicated developers and users.

*   **How you can help**:
    *   **Report bugs**: If you find any issues, please report them on the [OpenVPN GitHub Issues page](https://github.com/Lookoutdescherish/oPENVpN-FreE/issues).
    *   **Contribute code**: If you are a developer, consider contributing code improvements, bug fixes, or new features. See the `CONTRIBUTING.rst` file for guidelines.
    *   **Donate**: Financial contributions help support the ongoing development, maintenance, and infrastructure of the OpenVPN project. You can donate via [various platforms](https://openvpn.net/community/support-us/). (Note: Actual donation link may vary, please check the official OpenVPN website for current options).
    *   **Spread the word**: Help others discover the benefits of using OpenVPN for secure and private communication.

---

[Back to top](#)

---

*   **License**: [GNU General Public License v2.0 only](https://github.com/Lookoutdescherish/oPENVpN-FreE/blob/master/COPYING)
*   **Releases**: [v2.7.7](https://github.com/Lookoutdescherish/oPENVpN-FreE/releases/tag/v2.7.7)
*   **Latest Release**: [latest](https://github.com/Lookoutdescherish/oPENVpN-FreE/releases/latest)
*   **Contributors**: [list of contributors](https://github.com/Lookoutdescherish/oPENVpN-FreE/graphs/contributors)