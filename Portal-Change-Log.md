# February 5th, 2021 Release
## 7.1.19
### Changed
 - Upgrade formiojs@4.12.7
 - Upgrade @formio/premium#1.15.4
 - Upgrade formmanager#1.96.5
 - Upgrade ng-formio@4.17.4
### Updated
 - Upgrade @formio/premium@1.15.4
 - Upgrade formmanager@1.96.5
 - Upgrade formiojs@4.12.7
 
# January 29, 2021 Release
## 7.1.17-rc.48
### Changed
 - Upgrade formiojs@4.12.7-rc.1
 - Upgrade @formio/premium#1.15.4-rc.2
 - Upgrade formmanager#1.96.5-rc.3
 - Upgrade ng-formio@4.17.4

### Changed
  - Upgrade formmanager@1.96.5-rc.3

# December 18th, 2020 Release
## 7.1.17-rc.35
### Changed
 - No changes on rc.34

## 7.1.17-rc.34
### Fixed
 - FIO-991: APP | Public Plan / FRB | Form Settings -> PDF Settings -> Settings Tab not saving

### Changed
 - Upgrade formmanager@1.96.1-rc.7

# December 15th, 2020 Release
## 7.1.17-rc.33
### Added
 - PDF-232: Add pdf page layout setting
 
### Fixed
 - FOR-2876-2877: fixed an issue where JSON checkbox is unchecked after page reloading and bool values are disappeared from dataGrid when adding new public configuration

### Changed
 - Upgrade formiojs@4.12.4-rc.2
 - Upgrade @formio/premium@1.15.3-rc.1
 - Upgrade formmanager@1.96.1-rc.6
 - Upgrade ng-formio@4.17.3-rc.4

# December 6th, 2020 Release
## 7.1.17.rc.32
### Changed
 - Upgrade formiojs@4.12.2
 - Upgrade @formio/premium@1.15.2
 - Upgrade formmanager@1.96.1-rc.5
 - Upgrade ng-formio@4.17.2

# December 4th, 2020 Release
## 7.1.17-rc.31
### Changed
 - Upgrade formiojs@4.12.2-rc.8
 - Upgrade @formio/premium#v1.15.2-rc.4
 - Upgrade formmanager#v1.96.1-rc.4
 - Upgrade ng-formio@4.17.2-rc.5


# December 1st, 2020 Release
## 7.1.17-rc.30
### Changed
 - Upgrade formiojs@4.12.2-rc.6
 - Upgrade @formio/premium#v1.15.2-rc.3
 - Upgrade formmanager#v1.96.1-rc.3
 - Upgrade ng-formio@4.17.2-rc.4

# November 27th, 2020 Release
## 7.1.17-rc.29
### Fixed
 - FOR-2806: Stages not showing up on Stages section for Tenants
 - FOR-2803: Stages on Tenants do not show up on the License Management section
 - Fixed form settings change in builder.

### Changed
 - Upgrade formiojs@4.12.2-rc.5
 - Upgrade @formio/premium#v1.15.2-rc.2
 - Upgrade formmanager#v1.96.1-rc.2
 - Upgrade ng-formio@4.17.2-rc.3
 
# November 20th, 2020 Release
## 7.1.17-rc.28
### Changed
- Upgrade formiojs@4.12.2-rc.3
 - Upgrade @formio/premium#v1.15.2-rc.1
 - Upgrade formio-tenant@1.14.1-rc
 - Upgrade formmanager#v1.96.1-rc.1
 - Upgrade ng-formio@4.17.2-rc.1

# September 29th, 2020 Release
## Portal 7.0.41
*Changed*
- Upgrade "@formio/premium": "github:formio/premium#v1.15.1-rc.1",
- Upgrade "formiojs": "^4.12.1-rc.4"
- Upgrade "formmanager": "github:formio/formmanager#v1.95.0-rc.11"
- Upgrade "ng-formio": "^4.17.1-rc.1"
- Upgrade "formio-tenant": "^1.14.0-rc.11"

*Fixed*
- FJS-1169: Add reset flag for on premise env
- FOR-2713: Error appears after saving webhook
- FJS-1013: fix width for 'Delete project' button
- FJS-1071: Set initial access

*Added*
-FOR-2717: Added the rolesDelimiter option to configure how roles should be split if a customer uses some extraordinary saml provider.
-Add check for forgot password button for deployed apps


# August 26th, 2020 Release
## Portal 7.0.40
*Changed*
- Upgrade "@formio/premium": "github:formio/premium#v1.14.3-rc.2",
- Upgrade "formiojs": "^4.11.3-rc.3"
- Upgrade "formmanager": "github:formio/formmanager#v1.94.9-rc.2"
- Upgrade "ng-formio": "^4.15.3-rc.2"
- Upgrade "formio-tenant": "^1.13.18-rc.2"

# August 16th, 2020 Release
## Portal 7.0.39
*Changed*
- Upgrade "@formio/premium": "github:formio/premium#v1.14.2",
- Upgrade "formiojs": "^4.11.2"
- Upgrade "formmanager": "github:formio/formmanager#v1.94.8"
- Upgrade "ng-formio": "^4.15.2"
- Upgrade "formio-tenant": "^1.13.17"
- Adding group permission levels.
- Reverted group permissions since that is in the 7.1.x build of portal.

# August 5th, 2020 Release
## Portal 7.0.38
*Changed*
- Upgrade dependencies to include formiojs@4.11.1
- Change to build process, deleting node-modules
- Upgrade "@formio/premium": "github:formio/premium#v1.14.1-rc.4",
- Upgrade "formmanager": "github:formio/formmanager#v1.94.7-rc.6"
- Upgrade "formmanager": "github:formio/formmanager#v1.94.7-rc.6"
- Upgrade "formio-tenant": "^1.13.16-rc.5"

*Fixed*
- Build problem where latest formmanager was not getting pulled in.
- FJS-1068: Fix  Error when viewing submission data in portal
- FOR-2670: Fixes an issue where existed teams for stages were being deleted after the page refresh.



# July 9th, 2020 Release
## Portal 7.0.37
*Changed*
- Upgrade formiojs@4.11.0
- Upgrade formmanager@1.94.6

# July 7th, 2020 Release
## Portal 7.0.36
*Changed*
- Upgrade formiojs@4.11.0-rc.2
- Upgrade formmanager@1.94.6-rc.2

*Fixed*
- Removed the duplicate Kickbox settings.

# July 2nd, 2020 Release
## Portal 7.0.35
- Push 'Next' portal to production portal
- Upgrade "formmanager": "github:formio/formmanager#v1.94.5"
- Upgrade "formio-tenant": "^1.13.14"

# February 21st, 2020 Release
## Portal 6.9.6 - 6.8.7
*Fixed* 
* Credit card processing form to show the Month and Year in dropdowns.
* Crash in the pdf display functions

*Changed*
* Upgrade form manager to 1.59.0
* Upgrade form view pro to 1.57.0

*Added*
* Team Invitation UI


# October 16th 2019 Release

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




# August 20th 2019 Release:
## Portal 6.6.5
* Hubspot stylesheet
* Force google analytic scripts to load from https for security reasons.
* Fix headers on remote environment requests.
* Fix various templates loading.
* The configuration that adds the Public Configurations to forms to instead be added to the project level for performance reasons.
* A configuration to the form settings to add the project public configuration to the form JSON.
* Upgraded @babel/core@7.5.5, @babel/preset-env@7.5.5, @progress/kendo-ui@2019.2.724, lodash@4.17.15, protractor-helpers@1.1.589, webdriverio@5.11.10, copy-webpack-plugin@5.0.4, formiojs@3.24.0, mocha@6.2.0, webpack@4.38.0
* Added ActionItem log view to portal.
* On index, only return if a file is uploaded for base64 files.
* Fix some issues with protecting password fields.

# July 11th 2019 Release:
## Portal 6.5.3
* Fixed issues regarding the tenant manager with pagination and also introduced searching.
* Upgraded formiojs@3.22.15, protractor-helpers@1.1.568, webpack@4.35.2, ckeditor@4.12.1, swagger-ui@3.23.0
* FormView Pro 1.38.0
* Fixed offline issues
* Updated renderer


# June 22nd 2019 Release:

## Portal 6.4.9
*Fixed*
* Issue where the Form Manager button would show up when it shouldn't.
*Changed*
* Upgraded dependencies.
* Upgraded formmanager and dependencies.
*Added*
* Direct SAML passport configuration options.


# June 7th 2019 Release 

## Portal 6.4.6
*Changed*
* Upgraded Form Manager + Form View Pro to latest version
* Upgraded @babel/core@7.4.5, @babel/preset-env@7.4.5, babel-loader@8.0.6, protractor-helpers@1.1.538, swagger-ui@3.22.2, @progress/kendo-ui@2019.2.529, express@4.17.1, formiojs@3.21.2, webdriverio@5.9.4, webpack@4.32.2, webpack-dev-server@3.4.1, chartist@0.11.2, mini-css-extract-plugin@0.7.0

*Fixed*
* Fix on premise check for collections setting.
