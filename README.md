# NIST Juliet 1.3 - Embedded Credentials

Sources:
* [NIST Juliet C# 1.3](https://samate.nist.gov/SARD/test-suites/110)
* [NIST Juliet Java 1.3](https://samate.nist.gov/SARD/test-suites/111)
* [NIST Juliet C/C++ 1.3](https://samate.nist.gov/SARD/test-suites/112)

## Description

A collection of test cases in the C#, Java, and C/C++ languages.

This project includes all the test cases for [Credentials Management Errors](https://cwe.mitre.org/data/definitions/255.html) relating to the storage of credentials/passwords at rest (e.g. hard-coded passwords):

* [CWE-256: Plaintext Storage of a Password](https://cwe.mitre.org/data/definitions/256.html)
* [CWE-260: Password in Configuration File](https://cwe.mitre.org/data/definitions/260.html)
* [CWE-257: Storing Passwords in a Recoverable Format](https://cwe.mitre.org/data/definitions/257.html)
* [CWE-259: Use of Hard-coded Password](https://cwe.mitre.org/data/definitions/259.html)
* [CWE-321: Use of Hard-coded Cryptographic Key](https://cwe.mitre.org/data/definitions/321.html)
* [CWE-798: Use of Hard-coded Credentials](https://cwe.mitre.org/data/definitions/798.html)

Although this is the criteria for the tests selected, there are not tests for all of the CWE's. Only CWE-256, CWE-259 and CWE-321 are available.

# Limitations

This project does not include the scripts to execute test cases, documents, or any additional support files. For those please download the full Juliet test suite:

* [NIST Juliet C# 1.3](https://github.com/0x736E/NIST-Juliet-CSharp-1.3)
* [CNIST Juliet Java 1.3](https://github.com/0x736E/NIST-Juliet-Java-1.3)
* [NIST Juliet C/C++ 1.3](https://github.com/0x736E/NIST-Juliet-C-CPP-1.3)

# License

This software is not subject to copyright protection and is in the public domain. NIST assumes no responsibility whatsoever for its use by other parties, and makes no guaranties, expressed or implied, about its quality, reliability, or any other characteristic.

Pursuant to 17 USC 105, Juliet Test Suite for C/C++ version 1.3 is not subject to copyright protection in the United States. To the extent NIST may claim Foreign Rights in Juliet Test Suite for C/C++ version 1.3, the Test Suite is being made available to you under the CC0 1.0 Public Domain License.
