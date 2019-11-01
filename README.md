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

# September 17th 2019 Release
## Server 6.7.4-6.7.5
*Fixed*
* Fix issue where field logic value settings were forced to a string
* Fix issue with files in submission index endpoint when URL is undefined

*Added*
* Ability to set ‘Attach File’ setting within an email action to cooperate with all file storage providers
* Added configurable access endpoint configurations so that it can be turned off per-project or per-deployment.
* Added configurable access endpoints.
* Added empty subsubmission data check before updating.

*Changed*
* Upgraded aws-sdk@2.524.0, twilio@3.34.0

# September 4th 2019 Release
## Server 6.7.3

* Fixed issues with the query parameters for "null", "true", and "false" to allow the filtering of properties with these values.

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

## Server 6.7.0
* Upgrade formio to 1.50.0 which adds token schema and other bug fixes
* Temp tokens now use mongo instead of redis.
* New temp tokens auto-expire
* Default to pdf format in pdf download.
* Add own filter to count query
* Fix issue where row is not defined on custom conditional
* Email Action - 'Attach Submission Files' is not attaching file uploads to email email

# August 13th 2019 Release:
## PDF Server 2.55.0
* Added -  font-size scaling for datetime inputs
* Fixed performance problems with pdf generation by removing superfoulous timeouts.
* Added check for existence of this.formio before invoking to resolve some PDF form crashes.
* Upgraded formio.js from 3.23.3 to 3.24.3

# August 2nd 2019 Release:
## API Server 6.6.5 - 6.63
* Fixed- Compile issues that would create an invalid utils object and was causing crashing.
* Changed - The configuration to add public configurations to form json schemas to be at the project level instead of per-* form. This improves performance for projects without this feature.
* Changed - Updated formio to 1.49.0 https://github.com/formio/formio/blob/master/Changelog.md#1490
* Changed - Updated dependencies.
* Changed - Upgrade formio-app to 6.6.2 which includes includeConfig form configuration.
* Changed - Adding "cdn", "alpha", and "gamma" to list of reserved project names.

# July 22nd 2019 Release:
## PDF 2.67.0
* Add support for PDF overrides on component schemas
* Add z-index and opacity to PDF errors
* Improved font scaling logic for overlay components

# July 11th 2019 Release:
## Portal 6.5.3

* Fixed issues regarding the tenant manager with pagination and also introduced searching.
* Upgraded formiojs@3.22.15, protractor-helpers@1.1.568, webpack@4.35.2, ckeditor@4.12.1, swagger-ui@3.23.0
* FormView Pro 1.38.0
* Fixed offline issues
* Updated renderer

## Form Manager 1.38.0
* Updated renderer

## PDF Server 2.66.0

* Upgraded formiojs@3.22.15, aws-sdk@2.487.0, formio-viewer@2.22.0
* Set file component to image mode by default when added via PDF builder
* Increase default size of file component PDF overlay
* Fix CSS rule for white-space:pre-wrap


# June 22nd 2019 Release:

## API Server 6.5.23 - 6.5.25
*Changed*
* Upgraded minio@7.0.10, aws-sdk@2.478.0, formiojs@3.22.8, jira-connector@2.14.0, squel@5.13.0, twilio@3.32.0, webpack@4.34.0
* Upgraded deployed portal to 6.4.9
* Upgraded mongodb@3.2.7, aws-sdk@2.471.0, jira-connector@2.13.0, webpack@4.33.0


*Fixed*
* Problem where invalid SAML configurations could make the server crash.

*Added*
* Ability to configure SAML using passport settings.

## Portal 6.4.9
*Fixed*
* Issue where the Form Manager button would show up when it shouldn't.

*Changed*
* Upgraded dependencies.
* Upgraded formmanager and dependencies.

*Added*
* Direct SAML passport configuration options.

## PDF Server 2.62.0
*Changed*
* Upgraded minio@7.0.10, aws-sdk@2.478.0, formiojs@3.22.7, async@3.0.1, core-js@3.1.4

*Added*
* FOR-2357: The file component to the pdf builder which defaults to image mode.

*Fixed*
* FOR-2347: Ensure the browser context is closed when any failures occur during pdf generation.


## FormView Pro 1.34.0
*Added*
* A way to refresh the app when you are done submitting.

*Changed*
* Upgrade to Angular 8
* Upgrade core renderer to 3.22.7
* Upgrade core dependencies.
* The SSO init will now only trigger when you go to the Login page, OR if you provide a query parameter of "?sso=saml" to the url of the application.
* When an anonymous user submits the form, it will now just display a submission complete message and show refresh button.

*Fixed*
* Fixed issues where if admin updates a record, it could change ownership of record.
* Fixes problem when an anonymous form submits, it navigates to the submission view page, but you don't see the submission.
* Issues with refreshing the application changes the domain and then makes it so you are unauthorized.

## Form Manager 1.34.0
*Update*
* Updated dependencies.


# June 7th 2019 Release - API Server / Portal
## Server 6.5.18 - 6.5.22

*Fixed*
* Issue where the SAML relay was not adding the correct query separator.
* Fix issue where fields were not getting decrypted for pdfs.
* Project template exports to include the "properties" on each form component.
* Problems with the PDF download which includes forms with nested form components assigned to specific form revisions.


*Changed*
Upgraded portal, form manager, and formview pro.
* Upgraded all dependencies.
* Upgraded deployed portal to 6.4.6
* Upgraded formiojs@3.20.14, minio@7.0.8, mongodb@3.2.4, twilio@3.30.3, aws-sdk@2.455.0, formio@1.46.0, passport-saml@1.1.0, webpack@4.31.0
* Upgraded deployed portal to 6.4.4
* Always mount the form manager.

## Portal 6.4.6
*Changed*
* Upgraded Form Manager + Form View Pro to latest version
* Upgraded @babel/core@7.4.5, @babel/preset-env@7.4.5, babel-loader@8.0.6, protractor-helpers@1.1.538, swagger-ui@3.22.2, @progress/kendo-ui@2019.2.529, express@4.17.1, formiojs@3.21.2, webdriverio@5.9.4, webpack@4.32.2, webpack-dev-server@3.4.1, chartist@0.11.2, mini-css-extract-plugin@0.7.0

*Fixed*
* Fix on premise check for collections setting.

