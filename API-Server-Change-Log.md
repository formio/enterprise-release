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