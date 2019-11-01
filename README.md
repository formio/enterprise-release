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

# September 27th 2019 Release
## Server 6.7.6-6.7.8
*Added*
* Option to specify authorization method for OpenID.

*Changed*
* Upgraded Deployed portal to 6.8.3
* Upgraded Deployed Form Manager to 1.43.0
* Upgraded Deployed Form View Pro to 1.42.0
* Upgraded Deployed Tenant Manager to 1.3.0
* Upgraded formio@1.60.1 to fix Email action crashing
* Upgraded aws-sdk@2.537.0, webpack@4.41.0, adal-node@0.2.1
* Upgraded portal to 6.8.2 which upgrades form manager to 1.42.0
* Upgraded portal, which includes new formview pro, form manager, and tenant manager for deployed servers.
* Upgraded formio/formio which includes batch email processing.
* Upgraded formio/formio-workers to 1.14.0 which solves some email templating issues.

*Fixed*
* Crash with the Google Sheets action when using PATCH method.
* Crash with the Login Action when no settings are provided to the action.

## Portal 6.8.3
*Added*
* Added possibility to specify authorization method for OpenID.

*Changed*
* Upgraded Form Manager @ 1.43.0, Form View Pro @ 1.42.0, and Tenant Manager @ 1.3.0
* Upgraded dompurify@2.0.3, formiojs@4.2.4, protractor-helpers@1.1.636, webdriverio@5.13.2, webpack@4.41.0, angular-swagger-ui@0.6.2
* Upgrade form manager to resolve issues with defining project object.
* Upgraded Tenant Manager dependencies for latest angular.
* Upgraded Form Manager for latest angular and formio.js@4.2.0-rc.7
* Upgraded FormView Pro for latest angular and formio.js@4.2.0-rc.7
* Upgraded @babel/core@7.6.2, @babel/preset-env@7.6.2
* Upgraded depdendencies.
* Upgraded ng-formio fronm 2.37.4 to 2.38.1: See https://github.com/formio/ngFormio/blob/2.x/Changelog.md
* Upgraded ngFormBuilder from 2.37.6 to 2.38.0: See https://github.com/formio/ngFormBuilder/blob/master/Changelog.md

*Fixed*
* Tenant manager where you could only see 10 forms in the settings configurations.
* SAML redirect to not reset back to the homepage.



