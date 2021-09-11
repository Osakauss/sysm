# sysm

Building a kernel for a x86-64 system.

---

You should be able to read this guide from start to finish and get a good idea of the different concepts
needed to work on a kernel from absoltue scratch.

## index

1. [requirements](#requirements)
2. [introduction](#introduction)
3. [setting up the build environment](#buildenv)
4. [creating a testable system](#testing)
5. [full list of resources](#resources)

<a name="requirements"></a>
## requirements

This guide has absolutely zero focus on the programming aspect, one should have at least good knowledge
about working with C. Beign able to write or at least understand assembly for the x86 architecture is also
required.

<a name="introduction"></a>
## introduction

TODO

<a name="buildenv"></a>
## build environment

TODO

<a name="testing"></a>
## testing

TODO

<a name="resources"></a>
## resources <a res

The intel manuals for the 64 and I32 architecture are going to be the main source of information:
- [Basic Architecture][intel:basic_arch]
- [Instruction Set Reference][intel:reference]
- [System Programming Guide][intel:guide]
- [Model Specific Registers][intel:registers]
- [Combined Volumes][intel:combined]

Other useful links will be added in here as needed.

[intel:basic_arch]: https://software.intel.com/content/dam/develop/external/us/en/documents-tps/253665-sdm-vol-1.pdf "64 I32 Basic Architecture"
[intel:reference]: https://software.intel.com/content/dam/develop/external/us/en/documents-tps/325383-sdm-vol-2abcd.pdf "64 I32 Instruction Set Reference"
[intel:guide]: https://software.intel.com/content/dam/develop/external/us/en/documents-tps/325384-sdm-vol-3abcd.pdf "64 I32 System Programming Guide"
[intel:registers]: https://software.intel.com/content/dam/develop/external/us/en/documents-tps/335592-sdm-vol-4.pdf "64 I32 Model Specific Registers"
[intel:combined]: https://software.intel.com/content/dam/develop/external/us/en/documents-tps/325462-sdm-vol-1-2abcd-3abcd.pdf "64 I32 Combined Volumes"

