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
