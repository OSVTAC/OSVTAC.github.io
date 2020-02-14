## VSAP Architecture and Certification Links

The new Los Angeles County voting system, VSAP, was recently tested and
certified by the California Secretary of State. The testing and certification
documents seem to be the only publicly provided documentation on the
software and system architecture. The testing reports also bring up some
issues found, and there is a response from the counties and analysis by the
Secretary of State Staff.

The certification documents for VSAP also illuminate the process of
certification, and reference the California Voting Standards Document. These
are relevant for any open source voting system to be used in California.


### Main Sites

* VSAP project home page: <https://vsap.lavote.net/>

* VSAP Certification documents: <https://www.sos.ca.gov/elections/ovsta/voting-technology-vendors/los-angeles-county-vsap/>

* CVSS (California Voting System Standards): <https://admin.cdn.sos.ca.gov/regulations/elections/california-voting-system-standards.pdf>

The standards document is a detailed specification of the requirements for
voting systems used in California. The reports of testing procedures
reference sections in this document.


### Significant Test Reports

The following certification documents are significant for understanding VSAP
architecture and the issues found in testing, and the testing process itself:

* Functional Test Report: <https://votingsystems.cdn.sos.ca.gov/vendors/LAC/vsap2-func.pdf>

  Describes the overall system architecture, the testing process, and issues
  related to the sections in the CVSS

* Software Test Report: <https://votingsystems.cdn.sos.ca.gov/vendors/LAC/vsap2-sw.pdf>

  Describes the system and software architeture, software components (e.g.
  open source libraries), testing and review process, and issues found
  referenced to the CVSS sections.

* Security and Telecommunications Test Report: <https://votingsystems.cdn.sos.ca.gov/vendors/LAC/vsap2-sec-tel.pdf>

  Describes the system architecture and testing for security vulnerabilty
  issues.

* County Response to Testing: <https://votingsystems.cdn.sos.ca.gov/vendors/LAC/la-cert-response.pdf>

  Contains the County and developers response to the issues found in the
  consultants testing reports.

* Staff Testing Report: <https://votingsystems.cdn.sos.ca.gov/vendors/LAC/vsap2-staff.pdf>

  Summarizes the testing and test results with issues raised, responses, and
  significance.

  - Addendum: <https://votingsystems.cdn.sos.ca.gov/vendors/LAC/vsap20-staff-add.pdf>

Other reports are of interest in understanding testing for usability,
accessible voting, and load testing as is relates to requirements:

* Accessibility Testing Report: <https://votingsystems.cdn.sos.ca.gov/vendors/LAC/vsap2-acc.pdf>

  Describes the testing process for usability for normal and special needs
  voters and results found. The attachments provide the details survey
  results for testers recruited from the public.

* Volume Testing Report: <https://votingsystems.cdn.sos.ca.gov/vendors/LAC/vsap2-vol-log.pdf>

  Describes the load and reliability testing process and results.

### Lawsuit on Usability

There is a lawsuit against LA County for a usability issue in VSAP-- the
candidate selection screen can only show 4 candidates, and the plaintiffs
claim people might not see and vote for candidates on subsequent pages.

* News article on the lawsuit: <https://laist.com/2020/01/23/beverly-hills-files-lawsuit-sues-la-county-over-ballot-design-skip-candidates.php>

  Contains a summary of the issue and complaint, the text of the lawsuit, and
  a response from the county.

* News article on the VSAP certification: <https://laist.com/2020/01/16/los-angeles-county-voting-system-uncertified.php>

  Contains a summary, written for the public at large, of the issues found in
  the certification documents listed above, the history and context of VSAP,
  though somewhat critical of VSAP.
