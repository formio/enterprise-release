# December 18th, 2020 Release
## 3.0.0-rc.31
### Includes
 - formio.js@4.12.4-rc.2
 - formio/pdf@2.0.1-rc.1
 - formio-viewer@2.50.2-rc.1
 - premium@1.15.3-rc.1
### Changed
 - FIO-993: Rewrote the Dockerfile from node:14-alpine3.12 to the raw alpine:latest. Reworked the pdf2htmlEX installation. Changed the path for the pdfunits

# December 11th, 2020 Release
## 3.0.0-rc.30
### Includes
 - formio.js@4.12.4-rc.2
 - formio/pdf@2.0.1-rc.1
 - formio-viewer@2.50.2-rc.1
 - premium@1.15.3-rc.1
 
### Added
 - PDF-232: Add pdf page layout setting

### Fixed
 - FIO-619: Changes the Dockerfile. Removes unnecessary packages, upgrades packages with vulnerabilities to the latest available versions.

### Changed
 - formiojs@4.12.4-rc.2
 - formio-viewer@2.50.2-rc.1
 - @formio/pdf@2.0.1-rc.1
 - @formio/premium@1.15.3-rc.1
 - Upgrade uuid@8.3.2, aws-sdk@2.808.0

# December 6th, 2020 Release
## 3.0.0-rc.29
### Fixed
 - Issue with jose exports.

## 3.0.0-rc.28
### Fixed
 - Replace disable with delete on utilization delete
 - Fixes the pdfunite path. And changes the path for pdf2htmlEX git to the formio.
 - PDF 234: Add fonts to support different languages

### Changed
 - Upgrade formio-viewer@2.50.1
 - Upgrade formiojs@4.12.2
 - Upgrade formio-pdf@2.0.0
 - Upgrade premium@1.15.2

# November 28th, 2020 Release
## 3.0.0-rc.27
### Fixed
 - Issues with the pdf2html conversions.

### Changed
 - Upgrade formio-viewer@2.50.1-rc.1
 - Upgrade formiojs@4.12.2-rc.5
 - Upgrade formio-pdf@2.0.0-rc.31
 - Upgrade premium@1.15.2-rc.2
 
# November 24th, 2020 Release
## 3.0.0-rc.26
### Changed
 - Changed from Debian build to Alpine to resolve some CVE errors with build.
 - Upgraded aws-sdk@2.798.0, core-js@3.7.0, debug@4.3.1, eslint@7.14.0, puppeteer@5.5.0, javascript-obfuscator@2.9.4, jose@3.1.2, webpack@5.6.0, webpack-obfuscator@3.1.0

## 2.76.0
*Changed*

* Upgrade formio-files-core@2.93.0
* Upgrade formio-pdf@1.73.0
* Fixed remove signature clearing

# May 4th, 2020 Release
## 2.76.0
*Changed*

* Upgrade formio-files-core@2.93.0
* Upgrade formio-pdf@1.73.0
* Fixed remove signature clearing

# April 19th, 2020 Release
## 2.75.0
*Changed*

* Upgrade formio-files-core@2.92.0
* Upgrade formio-viewer@2.43.0
* Upgrade formiojs@4.9.20

## 2.74.0
* Upgrade formio-files-core@2.91.0
* Reverted puppeteer to v2.x

# April 18th, 2020 Release
## 2.73.0
*Changed*

* Upgrade formio-files-core@2.90.0
* Upgrade formiojs@4.9.20-rc.3, formio-viewer@2.42.0
* Upgrade @formio/premium@1.12.5
* Upgrade formio-pdf@1.72.0
* Double submit issue.
* Problem where Select dropdowns would not show values.

# April 8th, 2020 Release
## 2.71.0
*Changed*

* Upgrade formio-files-core@2.88.0
* Upgrade formiojs@4.9.16, formio-viewer@2.40.0
* Upgrade formio-pdf@1.71.0
* custom pdf labels support
* Fixed form validations disappearance

# April 2nd, 2020 Release
## 2.70.0
*Changed*

* Upgrade formio-files-core@2.87.0
* Upgraded formiojs@4.9.13, uuid@7.0.3, aws-sdk@2.652.0, formio-viewer@2.39.0
* Premium component styles to formio-viewer.
* PDF header/footer: added date interpolation by the provided date format
* Upgrade formio-pdf@1.70.0
* Issues with IE in signature block.

# March 27th, 2020 Release
## PDF Server 2.69.0
*Changed*
* Upgrade formio-files-core@2.86.0
* Upgrade formio-viewer to use formiojs@4.9.5
* Upgrade formiojs@4.9.5

# March 22nd, 2020 Release
## PDF Server 2.67.0
*Changed*
* Upgrade formio-files-core@2.83.0

# March 20th, 2020 Release
## PDF Server 2.66.0
*Changed*
* Upgrade formio-files-core@2.83.0
* Upgrade formio-viewer to use formiojs@4.9.3
* Upgrade formiojs@4.9.3
* Upgrade formio-pdf to fix Signature overlays.

## PDF Server 2.65.0
*Changed*
* Upgrade formio-files-core@2.82.0

# March 18th, 2020 Release
## PDF Server 2.64.0
*Changed*
* Upgrade formio-files-core@2.80.0
* Only set the PROXY environment variable if the HTTP_PROXY is not set.

## PDF Server 2.63.0
*Changed*
* Upgrade formio-files-core@2.79.0
* Upgrade formio-viewer to include 4.9.0-rc.11 renderer.
* Fixed issues with Signature positioning.
* Added a change event for subforms in pdf building.

# February 12th, 2020 Release
## PDF Server 2.61.0
*Changed*
* Upgrade formio-files-core@2.77.0
* Upgrade formio-pdf@1.66.0
* Upgrade formiojs@4.8.1, js-base64@2.5.2, puppeteer@2.1.1, request@2.88.2, aws-sdk@2.617.0

*Changed*
* Upgrade formio-pdf@1.66.0
* Ability to parse params from either ? or # for local pdf loading.
* getErrors method
* Upgrade formio.js@3.29.9
* Upgrade @babel/core@7.8.4, @babel/preset-env@7.8.4, mocha@7.0.1, webpack@4.41.6, webpack-cli@3.3.11

# January 28th, 2020 Release
## PDF Server 2.60.0
*Changed*
* Renderer version to 4.8.0
* Upgrade formio-viewer to use 4.8.0 renderer.

*Fixed*
* Potential issues where the PDF generation could get hung up on waiting for images to load.

*Added*
* Page size capabilities.

# January 24th, 2020 Release

## PDF Server 2.59.0
* Fixed issues related to disabled signatures when viewing them in read-only mode.
* Upgrade formio-files-core@2.75.0
* Upgrade formio-pdf@1.65.0

# January 8th, 2020 Release
## PDF Server 2.56.0
* Added headers and footers feature for PDF files.
* Added ability to change theme of PDF
* Added ability to configure PDF margins (helpful when setting header and footer)
* Added ability to turn off the Title bar
* Added ability to render PDF as plain text view (html mode)

# August 13th 2019 Release:
## PDF Server 2.55.0
* Added -  font-size scaling for datetime inputs
* Fixed performance problems with pdf generation by removing superfoulous timeouts.
* Added check for existence of this.formio before invoking to resolve some PDF form crashes.
* Upgraded formio.js from 3.23.3 to 3.24.3

# July 22nd 2019 Release:
## PDF Server 2.67.0
* Add support for PDF overrides on component schemas
* Add z-index and opacity to PDF errors
* Improved font scaling logic for overlay components

# July 11th 2019 Release:
## PDF Server 2.66.0

* Upgraded formiojs@3.22.15, aws-sdk@2.487.0, formio-viewer@2.22.0
* Set file component to image mode by default when added via PDF builder
* Increase default size of file component PDF overlay
* Fix CSS rule for white-space:pre-wrap

# June 22nd 2019 Release:
## PDF Server 2.62.0
*Changed*
* Upgraded minio@7.0.10, aws-sdk@2.478.0, formiojs@3.22.7, async@3.0.1, core-js@3.1.4

*Added*
* FOR-2357: The file component to the pdf builder which defaults to image mode.

*Fixed*
* FOR-2347: Ensure the browser context is closed when any failures occur during pdf generation.
