# OpenPOWER Foundation CAPI SNAP Enablement Documentation
This repository holds the source for the *Enable new FPGA Cards for CAPI2.0*
for OpenPOWER Foundation. 

To build this project, one must ensure that the Docs-Master project has
also been cloned at the same directory level as the Docs-Template project.
This can be accomplished with the following steps:

1. Clone the master documentation project (Docs-Master) using the following command:

  ```
  $ git clone https://github.com/OpenPOWERFoundation/Docs-Master.git
  ```
  
2. Clone this project (CAPI-SNAP-Doc) using the following command:

  ```
  $ git clone https://github.com/OpenPOWERFoundation/CAPI-SNAP-Doc.git
  ```
  
3. Build the project with these commands:
  ```
  $ cd CAPI-SNAP-Doc
  $ mvn clean generate-sources
  ```

For more information about with the document generation, please refer to [Documentation Development Guide](https://openpowerfoundation.org/?resource_lib=openpower-foundation-documentation-development-guide)

The online version of this document can be found in the OpenPOWER Foundation
Document library at [https://openpowerfoundation.org/?resource_lib=enable-new-fpga-cards-for-capi-2-0](https://openpowerfoundation.org/?resource_lib=enable-new-fpga-cards-for-capi-2-0) and also this github repository's release tab.   


## License
This project is licensed under the Apache V2 license.  More information
can be found in the LICENSE file or online at

  http://www.apache.org/licenses/LICENSE-2.0

## Community
To comment on, propose changes, and engage in community dialogue, you can open issues 
in the [Project Issues](https://github.com/OpenPOWERFoundation/CAPI-SNAP-Doc/issues), post to
the community mailing list \([capi-snap-doc@mailinglist.openpowerfoundation.org](mailto://capi-snap-doc@mailinglist.openpowerfoundation.org)\).

## Contributions
Contributions to this project should conform to the `Developer Certificate
of Origin` as defined at http://elinux.org/Developer_Certificate_Of_Origin.
Commits to this project need to contain the following line to indicate
the submitter accepts the DCO:
```
Signed-off-by: Your Name <your_email@domain.com>
```
By contributing in this way, you agree to the terms as follows:
```
Developer Certificate of Origin
Version 1.1

Copyright (C) 2004, 2006 The Linux Foundation and its contributors.
660 York Street, Suite 102,
San Francisco, CA 94110 USA

Everyone is permitted to copy and distribute verbatim copies of this
license document, but changing it is not allowed.


Developer's Certificate of Origin 1.1

By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I
    have the right to submit it under the open source license
    indicated in the file; or

(b) The contribution is based upon previous work that, to the best
    of my knowledge, is covered under an appropriate open source
    license and I have the right under that license to submit that
    work with modifications, whether created in whole or in part
    by me, under the same open source license (unless I am
    permitted to submit under a different license), as indicated
    in the file; or

(c) The contribution was provided directly to me by some other
    person who certified (a), (b) or (c) and I have not modified
    it.

(d) I understand and agree that this project and the contribution
    are public and that a record of the contribution (including all
    personal information I submit with it, including my sign-off) is
    maintained indefinitely and may be redistributed consistent with
    this project or the open source license(s) involved.
```

