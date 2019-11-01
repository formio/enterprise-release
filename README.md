This repository contains the changelog for the enterprise servers from form.io. No code is actually hosted in it. You can subscribe to this repository to be notified of the changes in each new release.

# Change Log
All notable changes to this project will be documented in this file

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

# October 31st 2019 Release
## Server 6.7.13
*Added*

* Ability to use the submission filter queries when exporting submissions as CSV.

*Changed*

* Upgrade all minor dependencies.

# October 16th 2019 Release
## Server 6.7.9 - 6.7.12
*Added*
* Print instructions for disabling Redis if using default settings

*Changed*
* Upgrade portal to version 6.8.6. Fixes stages per tenant.
* Upgrade Form Manager to v1.45.0 https://github.com/formio/formmanager/blob/master/CHANGELOG.md#1450
* Upgraded portal to version 6.8.5, which fixes project limit size.
* Upgraded portal to version 6.8.4, which introduces stages per tenant.
## Portal 6.8.4 - 6.8.6
*Added*
* Staging deployments for Tenants.

*Changed*
* Upgraded Form Managaer to v1.45.0 https://github.com/formio/formmanager/blob/master/CHANGELOG.md#1450
* Upgraded @babel/core@7.6.4, @babel/preset-env@7.6.3, @progress/kendo-ui@2019.3.1010, chance@1.1.3, dompurify@2.0.6, protractor-helpers@1.1.651, webpack@4.41.1, core-js@3.3.1, formiojs@4.3.3, swagger-ui@3.24.0, webdriverio@5.15.0
* Fix project limit to be a sane value so we don't overrun max_int on some systems.
* Upgraded ng-formio renderer that resolves bug with File component errors. https://github.com/formio/ngFormio/pull/650
* Added the renderer version and application version to the application.


