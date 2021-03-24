# March 21st, 2021 Release
### Includes
 - portal@7.2.0-rc.7
 - formviewpro@1.97.0-rc.4
 - formmanager@1.97.0-rc.4
 - formiojs@4.13.0-rc.22
 - premium@1.16.0-rc.4
 - offline@3.1.0-rc.3
 - formio@2.1.0-rc.14
 - uswds@2.3.1
 - vpat@2.3.1

## 7.1.0-rc.9
### Changed
 - Upgrade formiojs@4.13.0-rc.22
 - Upgrade portal@7.2.0-rc.7

# March 19th, 2021 Release
### Includes
 - portal@7.2.0-rc.6
 - formviewpro@1.97.0-rc.3
 - formmanager@1.97.0-rc.3
 - formiojs@4.13.0-rc.20
 - premium@1.16.0-rc.4
 - offline@3.1.0-rc.2
 - formio@2.1.0-rc.14
 - uswds@2.11.1
 - vpat@2.11.1

## 7.1.0-rc.8
### Changed
 - Upgrade formiojs@4.13.0-rc.20
 - Upgrade portal@7.2.0-rc.6
 - Upgrade formio@2.1.0-rc.14
 - Upgrade premium@1.16.0-rc.4

# March 12th, 2021 Release
### Includes
 - portal@7.0.43-rc.1
 - formviewpro@1.96.1
 - formmanager@1.96.2
 - formiojs@4.12.7
 - premium@1.16.0-rc.4
 - offline@3.1.0-rc.3
 - formio@1.91.3-rc.3
 - uswds@2.0.2
 - vpat@2.0.9

## 6.11.6-rc.3
### Changed
 - Build process tweaks #792

# Febuary 26th, 2021 Release
### Includes
 - portal@7.1.20-rc.1
 - formviewpro@1.96.2
 - formmanager@1.96.5
 - formiojs@4.13.0-rc.11
 - premium@1.15.5-rc.1
 - offline@3.0.5
 - formio@2.0.1-rc.4
 - uswds@2.10.0
 - vpat@2.0.9

## 7.0.2
### Changed
 - official build

# Febuary 10th, 2021 Release
### Includes
 - portal@7.1.19
 - formviewpro@1.96.2
 - formmanager@1.96.5
 - formiojs@4.12.7
 - premium@1.15.4
 - offline@3.0.5
 - formio@2.0.0
 - uswds@2.0.2
 - vpat@2.0.9

## 7.0.0
### Changed
 - Upgrade portal@7.1.19
 - Upgrade formiojs@4.12.7
 - Upgrade @formio/premium@1.15.4
 - Upgrade formio@2.0.0

# Febuary 5th, 2021 Release
### Includes
 - portal@7.2.0-rc.2
 - formviewpro@1.96.2-rc.9
 - formmanager@1.96.5-rc.5
 - formiojs@4.12.7-rc.2
 - premium@1.15.4-rc.3
 - offline@3.0.5-rc.4
 - formio@2.0.0-rc.42
 - uswds@2.0.2
 - vpat@2.0.9

## 7.1.0-rc.2
### Added
 - FOR-2866: added hook for getting proper mongo collection
 - FIO-1196: Added SQLConector2 support.
 - FIO-841: Implements the Dev License.

### Fixed
 - FIO-1282: Fixes an issue when the server was crashing if doesn't reach manager index.html
 - FOR-2709: Makes changing 'tags', 'controller', 'properties' and 'settings' form's properties cause creating a new revision if allowed
 - FIO-1138: Fixed possibility to update teams in protected mode.
 - FIO-128: Fix saving custom properties in form revision.
 - FOR-2763: Changed the default template for creating new projects that include the only Administrator for Read All.

### Changed
 - FIO-920: Adding email support for Teams.
 - Upgrade formio@2.0.0-rc.43
 - Upgrade javascript-obfuscator@2.10.3, mongodb@3.6.4, passport-saml@2.0.5, twilio@3.55.1, sinon@9.2.4, aws-sdk@2.834.0, eslint@7.19.0

### Changed
 - Upgrade formiojs@4.12.7-rc.2
 - Upgrade portal@7.2.0-rc.2
 - Upgrade premium@1.15.4-rc.3

# January 29th, 2021 Release
### Includes
 - portal@7.1.17-rc.48
 - formviewpro@1.96.2-rc.4
 - formmanager@1.96.5-rc.3
 - formiojs@4.12.7-rc.1
 - premium@1.15.4-rc.2
 - offline@3.0.5-rc.2
 - formio@2.0.0-rc.42
 - uswds@2.0.2
 - vpat@2.0.9
 
 ## 7.0.0-rc.77
 ### Fixed
 - FIO-1214: Receiving Sketchpad must not be an array on submission fix


# December 18th, 2020 Release
### Includes
 - portal@7.1.17-rc.35
 - formviewpro@1.96.1-rc.9
 - formmanager@1.96.1-rc.7
 - formiojs@4.12.4-rc.3
 - premium@1.15.3-rc.1
 - offline@3.0.4-rc.1
 - formio@2.0.0-rc.36
 - uswds@2.0.2-rc.3
 - vpat@2.0.9-rc.1
 
## 7.0.0-rc.62
### Fixed
 - Issue where the server would crash if project=null was provided when saving the project settings.
 - Issue where the public project configurations would not get passed to formview pro and formmanager
 - FOR-2868: Adds the rejectUnauthorized flag to license utilization requests. 
 - FOR-2889: Everyone role is not saved on Access page
 - FIO-975: Added possibility to configure server config log.

### Changed
 - Upgrade portal@7.1.17-rc.35
 - Upgrade formio@2.0.0-rc.36

# December 15th, 2020 Release
### Includes
 - portal@7.1.17-rc.33
 - formviewpro@1.96.1-rc.5
 - formmanager@1.96.1-rc.6
 - formiojs@4.12.4-rc.2
 - premium@1.15.3-rc.1
 - offline@3.0.3-rc.4
 - formio@2.0.0-rc.35 
 - uswds@2.0.1-rc.3
 - vpat@2.0.8-rc.1

## 7.0.0-rc.61
### Changed
 - Upgrade portal@7.1.17-rc.33
 - Changed application variables.

## 7.0.0-rc.60
### Changed
 - FOR-2862: Rewrote Docker files from node:14-alpine3.12 to alpine:latest. Solved an issue with nghttp2 v1.40

# December 6th, 2020 Release
## 7.0.0-rc.59
### Includes
 - portal@7.1.17-rc.32
 - formviewpro@
 - formmanager@
 - formiojs@4.12.2
 - premium@1.15.2
 - offline@
 - formio@2.0.0-rc.35 
 - uswds@2.0.1
 - vpat@2.0.8

### Changed
 - Upgrade portal@7.1.17-rc.32
 - Upgrade formiojs@4.12.2
 - Upgrade premium@1.15.2
 - Upgrade formio@2.0.0-rc.35 
 - Upgrade semver@7.3.4, aws-sdk@2.804.0, twilio@3.53.0, eslint@7.15.0

# December 4th, 2020 Release
## 7.0.0-rc.58
### Changed
 - Upgrade portal@7.1.17-rc.31
 - Upgrade formiojs@4.12.2-rc.8
 - Upgrade premium@1.15.2-rc.4

# December 1st, 2020 Release
## 7.0.0-rc57
### Changed
 - Upgrade portal@7.1.17-rc.30
 - Upgrade formiojs@4.12.2-rc.6
 - Upgrade premium@1.15.2-rc.3

# November 27th, 2020 Release
## 7.0.0-rc56
### Added
 - FOR-2851: Adds an environment ID in the status endpoint
 
# November 25th, 2020 Release
## 7.0.0-rc.55
### Changed
- Upgrade portal@7.1.17-rc.28
 - Upgrade formio@2.0.0-rc.33
 - Upgrade formiojs@4.12.2-rc.3
 - Upgrade premium@1.15.2-rc.1
 
# September 30th, 2020 Release
## 6.11.0-patch.1
### Fixed
- Added email fallback system for sending emails with URL.


# August 26th, 2020 Release
## 6.11.0
### Changed 
- Upgrade portal to 7.0.40
- Upgrade formiojs@4.11.3

 ### Fixed
- Added email fallback system for sending emails with URL.

## 6.10.10
### Changed 
- Upgrade portal to 7.0.41-rc.5
- Upgrade formiojs@4.12.0-rc.19
- Upgrade formio@1.90.9
- Upgrade chance@1.1.7, formiojs@4.11.3, lodash@4.17.20, passport-saml@1.3.4, request-promise-native@1.0.9, resourcejs@2.3.1, sinon@9.0.3, aws-sdk@2.742.0, mongodb@3.6.0, twilio@3.49.0, uuid@8.3.0, eslint@7.7.0, mocha@8.1.3, webpack@4.44.1, webpack-obfuscator@1.12.0, universal-analytics@0.4.23


# August 18th, 2020 Release
## 6.10.9
### Changed 
- Upgrade formiojs@4.11.2
- Upgrade portal to 7.0.39-rc.3
- Change build process to delete node_modules
 
 ### Fixed
- Issues where the pdf attachments were not attaching.
- PDF Email Attachments so that they do not require Save Submission, and also made them more robust.

 
# August 5th, 2020 Release
## 6.10.8
### Changed 
 - Upgrade portal to 7.0.38
 - Upgrade formiojs@4.11.1
 - Change build process to delete node_modules

 ### Fixed
  - Passing project to pdf server to solve image displays.


# July 10th, 2020 Release
## 6.10.7-rc.1
### Changed 
 - Upgrade portal@7.0.38-rc.1
 - Upgrade formiojs@4.11.1-rc.1
 -Upgrade formio to 1.90.5 to fix mongo ssl connections.

### Fixed
 - Passing project to pdf server to solve image displays.

# July 9th, 2020 Release
## 6.10.6
### Changed 
 - Upgrade formio to 1.90.2 to fix email crash on large emails.

# July 8th, 2020 Release
## 6.10.5
### Changed 
 - Upgrade formio to 1.90.1 to upgrade resourcejs to 2.3.1 to fix issue with limit and sort.

# July 7th, 2020 Release
## 6.10.4
*Changed*
- Upgrade portal@7.0.36-rc.2
- Upgrade formiojs@4.11.0-rc.4
- Upgrade dependencies
- Upgrade portal@7.0.36-rc.1
- Upgrade formiojs@4.11.0-rc.2
- Upgrade formio@1.90.0

*Fixed*
- FOR-2682: Fixes an issue where x-jwt-token from SAML was too big
- fix: added next function calls

# July 2nd, 2020 Release
## 6.10.3
*Changed*
- Upgrade portal@7.0.35

# May 13th, 2020 Release
## 6.9.33
*Changed*
- Upgrade formio@1.78.0
- Upgrade formio-workers@1.14.4
- Upgrade minio@7.0.16, mongodb@3.5.7, mocha@7.1.2, aws-sdk@2.670.0, moment@2.25.3, twilio@3.43.0, webpack-obfuscator@0.28.0
- Remove adding project role to owners since it isn't needed.

# April 24th, 2020 Release
## 6.9.32
*Changed*
 - Upgrade formio@1.76.0
 - Upgrade formio-workers@1.15.0

# April 22nd, 2020 Release
## 6.9.31
*Changed*
* Upgrade portal to 7.0.3
* Upgrade formiojs@4.9.22

# April 21st, 2020 Release
## 6.9.30
*Changed*
* Upgrade portal to 7.0.2
* Upgrade formiojs@4.9.21
* Upgrade formio-app@7.0.2

# April 19th, 2020 Release
## 6.9.29
*Changed*
* Upgrade portal to 7.0.1

# April 16th, 2020 Release
## 6.9.28
*Changed*
* Upgrade portal to 7.0.0

# April 7th, 2020 Release
## API Server 6.9.24
## 6.9.27
*Changed*
 * Upgrade portal to 7.0.0-rc.87
 * Add config to interpolation for datasource on server side.

## 6.9.26
 * No changes:

# March 30th, 2020 Release
## API Server 6.9.24
*Changed*
 * Upgrade portal to 7.0.0-rc.84
 * Upgrade formiojs@4.9.10

# March 30th, 2020 Release
## API Server 6.9.24
*Changed*
* Upgrade portal to 7.0.0-rc.84
* Upgrade formiojs@4.9.10\

# March 28th, 2020 Release
## API Server 6.9.24
*Changes*
* Upgrade portal to 7.0.0-rc.83
* Upgrade formiojs@4.9.9

# March 27th, 2020 Release
## API Server 6.9.23
*Changed*
* Adding debug output for DataSource request headers.
* Upgrade portal to 7.0.0-rc.82
* Upgrade formiojs@4.9.8

## API Server 6.9.22
*Fixed*
* Ensure the DataSource header values are interpolated.

## API Server 6.9.21
*Fixed*
* Issue where DataSource was not populating before validations occur.
* Ensure form is loaded with public configurations when interpolating data source component.
* Problem with Validate endpoint where only admins could use it.
* Issue where the datasource component would hang up the request if it failed.
* Issues where datasource checks would fail for any SSL errors that would occur.
*Added*
* Debug messaging to the data source component.

## API Server 6.9.20
*Changed*
* Upgrade portal to 7.0.0-rc.80
* Upgrade formiojs@4.9.6
* Upgrade aws-sdk@2.644.0

## API Server 6.9.19
*Changed*
* Upgrade portal to 7.0.0-rc.79
* Upgrade formiojs@4.9.5

## API Server 6.9.18
*Changed*
* Upgrade portal to 7.0.0-rc.79
* Upgrade formiojs@4.9.5

## API Server 6.9.17
*Changed*
* Upgrade portal to 7.0.0-rc.77
* Upgrade formiojs@4.9.3

## API Server 6.9.16
*Changed*
* Upgrade portal to 7.0.0-rc.76
* Upgrade formiojs@4.9.2

## API Server 6.9.15
*Changed*
* UPgrade portal to 7.0.0-rc.74

## API Server 6.9.14
*Changed*
* Upgrade portal to 7.0.0-rc.73

## API Server 6.9.13
*Changed*
* Upgrade portal to 7.0.0-rc.72
*Fixed*
* Issues with encrypted fields not working when persistent flag isn't set on a component.
* CSV download issues when DateTime components are added.

## API Server 6.9.12
*Changed*
* Upgrade portal to 7.0.0-rc.71

## API Server 6.9.11
*Changed*
* Upgrade portal to 7.0.0-rc.70

*Fixed*
* Validate endpoint to work with aliases
* Adding config and modules to form revision endpoints.
* Data Source component to always trigger when validate endpoint is called.

## API Server 6.9.10
*Changed*
* Upgrade portal to 7.0.0-rc.68

## API Server 6.9.7
*Changed*
* Fixed deployed portal to resolve Exising Resources
* Fixed issue with deployed portal erasing spaces in TextAreas.

## API Server 6.9.6
*Changed*
* Build process to change from pkg to alpine-node.

## API Server 6.9.6
*Added*
* Validate endpoint for forms to allow them to perform a validation only against a form.

# February 24th, 2020 Release
## API Server 6.9.4
*Changed*
* Fixed deployed portal to work better in situations where "access" is granted to primary and "read" is granted to stage.
* Upgrade formio@4.9.0-rc.2
* Upgrade portal@7.0.0-rc.64

## API Server 6.9.3
*Changed*
* Upgrade portal to fix form manager loading issues.

## API Server 6.9.2
*Added*
* Ability to use tokens in the evaluation context.

# February 21st, 2020 Release
## API Server 6.9.1
*Fixed*
* Update hooks to work when no primary project is found.

## API Server 6.9.0
*Fixed*
* Update hook to work with deployments where there isn't a primary project.


## API Server 6.9.0-rc2

*Fixed*
* Permissions issues with team resources.

*Changed*
* Upgrade portal to 7.0.0-rc.62

## API Server 6.9.0-rc1

*Fixed*
* Issues with leaving teams.

*Changed*
* Upgrade twilio@3.39.5, aws-sdk@2.623.0
* Upgrade portal to 7.0.0-rc.61
* Upgrade formiojs@4.9.0-rc.1

# February 13th, 2020 Release

## API Server 6.7.40

*Fixed*
* Fix saving payeezy requests to db.

## API Server 6.7.39

*Fixed*
* Stricter limits on payeezy integration.


# February 7th, 2020 Release

## API Server 6.7.38

*Fixed*
* Crash when trying to log projects.

*Changed*
* Upgrade formio@1.63.11

## API Server 6.7.37

*Fixed* 
* Problem where un-linking files that do not exist could make server crash.

*Changed* 
* Upgrade formio@1.63.10
* Upgrade formiojs@4.8.1, twilio@3.39.3, aws-sdk@2.611.0

# January 24th, 2020 Release

## API Server 6.7.36
* Fixed issues with the email BCC and CC actions.

## API Server 6.7.35
* Fixed - Validations for file components.
* Added - BCC and CC support for Email Actions.
* Changed - Upgrade aws-sdk@2.608.0, mongodb@3.5.2, uuid@3.4.0

# January 13th, 2020 Release

## Server 6.7.34-.29
* Fixed issues with payeezy integration
* Form Controller Property
# December 31st, 2019 Release

## API Server 6.7.28
*Fixed*
* Update to not crash if no project is found.

## API Server 6.7.27
*Fixed*
* Hosted platform to not allow many cc auth checks.

## API Server 6.7.25
*Fixed*
* Jira connector basic auth change
* Added correct handling of tenant project plan.
* Allow form settings to be loaded as part of revisions.

*Changed*
* Upgrade Portal to 6.8.7
* Upgrade mongodb@3.4.1, webpack@4.41.4, aws-sdk@2.594.0, twilio@3.39.1

# December 12th, 2019 Release

## API Server 6.7.24
*Fixed*
* Swagger IO interfaces from not returning any elements.

## API Server 6.7.23
*Changed*
* Upgrade formio@1.63.4.
* Resolved issues with server crashing due to Swagger io calls.

# December 11th, 2019 Release

## API Server 6.7.22
*Changed*
* Reverted the sort by modified within CSV exports.

## API Server 6.7.21
*Changed*
* Upgrade formio@1.63.2 to resolve CSV export issue with wizards.

## API Server 6.7.20
*Fixed*
* Upgraded formio@1.63.0 which resolves CSV export issue with wizards.
* Build issues where pkg@4.4.1 broke our server.

## API Server 6.7.19

*Changed*
* Upgrade formio.js@4.8.0-rc.1
* Upgrade formio/formio@1.62.0

*Fixed* 
* Fix datasource field action to work with new system.
* Issue with Docker Secrets where it would fault on certain VM's due to accessing a directory outside the bounds of the container.

# December 6th, 2019 Release
## API Server 6.7.18

*Added*
* Support for Docker Secrets.
* Adding ability to forward headers with data source component.
* Upgrade formio/formio@1.61.0

## API Server 6.7.17

*Fixed*
* Adding ignoreTLS for SMTP configurations so that certain SMTP servers can be configured.

# November 11th, 2019 Release
## API Server 6.7.16

*Fixed*
* Fixed issue where empty DateTime fields are getting saved as January 1, 1970.

# November 6th, 2019 Release
## Server 6.7.15

*Fixed*
* Issues with OpenID authentication.

*Changed*
* Upgrade formio@1.60.6
* Upgrade request-promise-native@1.0.8, aws-sdk@2.564.0, formiojs@4.7.2, twilio@3.37.0

## API Server 6.7.14
*Added*
* filesServer to pdf upload response.

*Fixed*
* Fixed OpenID attribute mapping.

# October 31st 2019 Release
## API Server 6.7.13
*Added*

* Ability to use the submission filter queries when exporting submissions as CSV.

*Changed*

* Upgrade all minor dependencies.

# October 16th 2019 Release
## API Server 6.7.9 - 6.7.12
*Added*
* Print instructions for disabling Redis if using default settings

*Changed*
* Upgrade portal to version 6.8.6. Fixes stages per tenant.
* Upgrade Form Manager to v1.45.0 https://github.com/formio/formmanager/blob/master/CHANGELOG.md#1450
* Upgraded portal to version 6.8.5, which fixes project limit size.
* Upgraded portal to version 6.8.4, which introduces stages per tenant.

# September 27th 2019 Release
## API Server 6.7.6-6.7.8
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

# September 17th 2019 Release
## API Server 6.7.4-6.7.5
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
## Server 6.7.0
* Upgrade formio to 1.50.0 which adds token schema and other bug fixes
* Temp tokens now use mongo instead of redis.
* New temp tokens auto-expire
* Default to pdf format in pdf download.
* Add own filter to count query
* Fix issue where row is not defined on custom conditional
* Email Action - 'Attach Submission Files' is not attaching file uploads to email email

# August 2nd 2019 Release:
## API Server 6.6.5 - 6.63
* Fixed- Compile issues that would create an invalid utils object and was causing crashing.
* Changed - The configuration to add public configurations to form json schemas to be at the project level instead of per-* form. This improves performance for projects without this feature.
* Changed - Updated formio to 1.49.0 https://github.com/formio/formio/blob/master/Changelog.md#1490
* Changed - Updated dependencies.
* Changed - Upgrade formio-app to 6.6.2 which includes includeConfig form configuration.
* Changed - Adding "cdn", "alpha", and "gamma" to list of reserved project names.

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

# June 7th 2019 Release
## API Server 6.5.18 - 6.5.22

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
