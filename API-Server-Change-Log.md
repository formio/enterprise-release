# December 4, 2023 Release

## PDF Server Version 5.3.5

### Included Correlated Libraries
- formio-pdf@2.8.4
- premium@1.21.3
- formiojs@4.17.4
- formio-viewer@2.57.4

### Fixes
FIO-7561: PDF Server - Azure - ERROR: s3.putObject(): Expected uri parameter to have length >= 1, but found "" for params.Bucket

# November 29, 2023 Release

## API Server Version 8.3.5

### Changed
 - portal@8.3.4
 - formiojs@4.17.4
 - formio@3.3.5
 - premium@1.21.3
 - grid@1.4.0
 - formviewpro@1.104.3
 - formmanager@1.102.4
 - offline@4.5.4
 - uswds@2.5.0
 - vpat@2.5.1

### Breaking Change: Update to AWK SDK v3
  - To all customers currently using formio-enterprise@8.3.5 in conjunction with AWS S3 storage for file uploads, please be advised of a breaking change. In order to maintain the expected behavior of your file upload components, it is crucial to also update the front-end renderer of your application(s) to formiojs@4.17.4.

*Note: This update applies to customers utilizing portal.form.io to host their projects as well.*

### Fixes
- FIO-4405 Fix empty validation error when hidden radio has the Storage Type as String
- FIO-6771 Consolidate and float "Save Settings" buttons in Form Settings and Revisions contexts
- FIO-7043 Data Source Request Headers Values resolving when provided interpolated values
- FIO-7304 Select Component with Logic returns you to tab with select component
- FIO-7433 FormView Pro "return" key not redirecting after submission
- FIO-7460 502 Bad Gateway when project name has space or is duplicated
- FIO-7468 Export as a Project Template from Form includes Project Access settings
- FIO-7513 Remove “Drag and Drop a form component” when "fetch" enabled on data source component
- FIO-7528 Fix shouldSkipValidation function
- FIO-7530 Data Table | Rows with API key values remain in the grid after changing the resource
- FIO-7547 Container hidden with conditional logic still appears in submission
- FIO-7550 formio.full.css causes project compile error
- FIO-7564 Data Table component displays an error on Edit Form page in Form Manager when Fetch Source Type is Resource.


# November 1, 2023 Release

## API Server Version 8.3.4

### Changed
 - portal@8.3.3
 - formiojs@4.17.3
 - formio@3.3.4
 - premium@1.21.2
 - grid@1.4.0
 - formviewpro@1.104.3
 - formmanager@1.102.3
 - offline@4.5.3
 - uswds@2.5.0
 - vpat@2.5.1

### New Features
- FIO-7239 File Upload Component - S3 Multipart Upload API Support
- FIO-7261 Replace Text Area component in Settings>Authorization>SAML with ACE Editor
- FIO-7305 Change Fetch Tab to fetch from Resource and URL 
- FIO-7371 Enable the Form.io CLI tool clone command to allow the source of the migration to be an API endpoint

### Fixes
- FIO-7055 FMG | Data Table Component | Sometimes 'Add button' isn't displayed on Enter Data page, the user isn't able to populate the component. 
- FIO-7258 Account Settings | Username is copied instead of userID.
- FIO-7351 Wizard form: Data is not submitted for the Panel component if the conditionals are applied for Panel.
- FIO-7375 Typo in warning message on Form Manager page when Form Manager is disabled for a project.
- FIO-7444 Typo on Form API Page
- FIO-7472 Data Table | Error 401 (Unauthorized) occurs when a user enables the 'Fetch' checkbox in component settings
- FIO-7491 Data Table | Resource ID is not changed when importing project template or deploying stage version (for Data tables populated from resource)

### Changes
- FIO-7236 Deprecate random keygen
- FIO-7326 Changes on Project Plan page
- FIO-7328 Removed kickbox dependency
- FIO-7329 Removed nodemailer-sendgrid and mailgun
- FIO-7344 Remove "Static rendering is considered deprecated..." message from Email Action
- FIO-7372 Remove Jekyll/Gem files from the premium library
- FIO-7423 Payment Gateway for SaaS Portal


# November 1, 2023 Release

## PDF Server Version 5.3.4
(Version 5.3.3 was removed from docker and replaced with the 5.3.4 hotfix)

### Included Correlated Libraries
- formio-pdf@2.8.3
- premium@1.21.2
- formiojs@4.17.3
- formio-viewer@2.57.3

### Fixes
- FIO-7475 Pdf download does not convert with html format for FJS, FMG and FVP forms
- FIO-7107 Remove vm2 dependency from PDF server

# October 10, 2023 Release

## API Server Version 8.3.3

### Changed
 - portal@8.3.2
 - formiojs@4.17.2
 - formio@3.3.3
 - premium@1.21.1
 - grid@1.3.0
 - formviewpro@1.104.2
 - formmanager@1.102.2
 - offline@4.5.2
 - uswds@2.5.0
 - vpat@2.5.1

### Fixes
- FIO-5728 Check for unique email when adding a user to a team
- FIO-6156 Help links are pointing to the incorrect locations
- FIO-6197 Security Updates
- FIO-6578 Focus lost on Year field when Day component has advanced logic
- FIO-7201 Unable to see the last line of the Form Controller code block
- FIO-7246 Security Updates
- FIO-7257 Typo in 2FA tooltip
- FIO-7315 Typescript error when adding renderMode option in React
- FIO-7320 Removing /form from url on portal takes you to unexpected page
- FIO-7323 PDF Email Attachment doesn't work with Azure
- FIO-7349 Server crashes when you log into a user who belongs to a team that has been deleted
- FIO-7361 Add rel= "noreferer,noopener" to links in project settings template

### Changes
- FIO-7139 defaultProps deprecation for react
- FIO-7219 Remove Default Transport email type and Email Resources
- FIO-7327 Remove deprecated jira-connector

# October 10, 2023 Release

## PDF Server Version 5.3.2

### Included Correlated Libraries
- formio-pdf@2.8.2
- premium@1.21.1
- formiojs@4.17.2
- formio-viewer@2.57.2

### Fixes
 - FIO-7246 Security Updates
 - FIO-7202 Replace deprecated request-promise-native dependency

# September 19, 2023 Release

## API Server Version 8.3.2

### Changed
 - portal@8.3.1
 - formiojs@4.17.1
 - formio@3.3.1
 - premium@1.21.0
 - grid@1.3.0
 - formviewpro@1.104.1
 - formmanager@1.102.1
 - offline@4.5.1
 - uswds@2.5.0
 - vpat@2.5.1

### Bug Fixes
- FIO-7363 Uncaught Exception with email template
- FIO-4809 Wizard: When there are components outside the Wizard Panel, they display in all the wizard pages in a rendered form. When submitting data, they are empty in the submission
- FIO-6953 Add rel= "noreferer,noopener" to all links on portal.form.io
- FIO-7120 Investigate duplicate entries in licenses management in stages and tenants
- FIO-7173 Nested form | When the user nests a form with an initial focus set, the initial focus is triggered in the Nested form component settings
- FIO-7197 Increase size of data grid drop zone after first component dropped

## PDF Server Version 5.3.1

### Included Correlated Libraries
- formio-pdf@2.8.1
- premium@1.21.0
- formiojs@4.17.1
- formio-viewer@2.57.1
   
# September 12, 2023 Release

## API Server Version 8.3.0

### Changed
 - portal@8.3.0
 - formiojs@4.17.0
 - formio@3.3.0
 - premium@1.21.0
 - grid@1.3.0
 - formviewpro@1.104.0
 - formmanager@1.102.0
 - offline@4.5.0
 - uswds@2.5.0
 - vpat@2.5.1

### Enhancements & New Features
- FIO-6401 Add multiple row selection Data Tab in Form.io Apps
- FIO-6075 Add opt-in environment variables for SAML Passport keypaths
- FIO-3448 Allow PDF Signature modal to be the same proportion as the Signature overlay

### Bug Fixes
- FIO-4782 Ampersand (&) is not escaped in a query
- FIO-5042 OIDC logout is not working with FVP
- FIO-5731 isLastPage() function causing validation error on submission
- FIO-5967 Select (HTML5, Resource, Entire Object): Select data is not shown on View, Edit, and PDF download
- FIO-6785 Content Field formatting not showing indentation
- FIO-6807 Date/Time Component Date functionality does not work if it is disabled then enabled again
- FIO-6849 Form components cannot be edited because of legacy format of multi select default value multiple values
- FIO-6906 Data tab | Checkbox component | ‘is equal to’ filter applied incorrectly 
- FIO-6911 Data tab | Day component | ‘is equal to’ filter applied incorrectly
- FIO-6916 Data tab | Data table | When the filter has been applied to any component the filter form window is still displayed
- FIO-6919 Data tab | Signature component | ‘is equal to’ filter applied incorrectly
- FIO-6920 Data tab | File component | ‘is equal to’ filter applied incorrectly
- FIO-6923 Data Tab | remove irrelevant filter options from various components
- FIO-6925 Data tab | Select boxes component | ‘is equal to’ filter applied incorrectly
- FIO-6933 Unable to reach and save the form using basic keyboard accessibility.
- FIO-6967 Form Initialization Fails for form with Calendar Widget and Language Option
- FIO-6982 passport-saml-metadata dependency major version update
- FIO-7007 Select Boxes | URL Data Source | Submitted values are not presented on Data page.
- FIO-7036 Existing Resource Fields | Fields added to a Form from the Existing Resource Field list do NOT carry over all pre-configured settings
- FIO-7110 Nested Form: When 'Use Original Revision while Submissions Viewing' is enabled for the Nested Form, the Nested Form submission still displays in the current form revision
- FIO-7128 Drop-down selection issues
- FIO-7132 Submission Revisions | If the number component with the multiple values enabled is not filled, then an error occurs when loading the pdf submission (submission revisions and ‘Show Change Log’ are enabled)
- FIO-7149 Admin User Editing SAML Settings cannot see or save data
- FIO-7151 The 'Unauthorized' error message is displayed when the user changes the project plan
- FIO-7180 Print to PDF doesn't show uploaded images
- FIO-7217 The Select component is overlaid by the footer and continues to display below it
- FIO-7229 When creating a stage it does not inherit parent project plan
- FIO-7241 Server crashes on sending submission request when there is custom JS code calling method formatDate in utils library which is removed
- FIO-7248 Data tab | The ‘is equal to no’ filter is applied correctly for the Signature component but value in the filter isn't saved on UI
- FIO-7297 API Permission denied error when creating a stage with x-admin-key header provided
- FIO-7130 Migrate formio/grid from node-sass to sass


### Changes
- FIO-7123 Add Form Revisions to SAC package
- FIO-7124 Add Action Logs to SAC package

# September 12, 2023 Release

## PDF Server Version 5.3.0

### Included Correlated Libraries
- formio-pdf@2.8.0
- premium@1.21.0
- formiojs@4.17.0
- formio-viewer@2.57.0

# August 30, 2023 Release
## PDF Server Version 5.2.0

### Included Correlated Libraries
- formio-pdf@2.7.0
- premium@1.20.0
- formiojs@4.16.0
- formio-viewer@2.56.0

### Fixed
 - FIO-5303 PDF | Edit Grid Edit and Delete buttons show on PDF download
 - FIO-6149 File component not styled on PDF First form 
 - FIO-7174 Resolved 502 error introduced with base image migration

# August 23, 2023 Release
## API Server Version 8.2.1
### Fixed
 - Eliminate possibility of 502 error caused by PUT requests to nested date/time components with invalid values

# August 16, 2023 Release
## API Server Version 8.2.0

### Included Correlated Libraries
- portal@8.2.0
- formiojs@4.16.0
- formio@3.2.0
- premium@1.20.0
- formviewpro@1.103.0
- formmanager@1.101.0
- offline@4.4.0
- uswds@2.5.0
- vpat@2.5.0

### Fixed
- FIO-3345 FJS | Form builder: Cannot save form when there is a component in the Tagpad that has the same API key as the component outside the Tagpad
- FIO-3840 API |  Bug with Swagger spec definition showing incorrect type
- FIO-3987 API | Mailgun Emails are not attaching Azure blob files to the emails
- FIO-4301 React | "ref" prop has been removed
- FIO-4302 React |  Everytime the parent component change, the formio Instance is recreated and then destroyed immediately
- FIO-4495 FJS | Select (URL): When Storage Type is set to String, Boolean or Object, and the user selects a value in the dropdown, a new value = selectedValueID is created and displayed in the input field as well as the dropdown
- FIO-4550 USWDS | Data Grid: When label is taken from {{ row.flag }}, the field has an incorrect accessible name for the 2nd and the following data grid rows
- FIO-4809 FJS | Wizard: When there are components outside the Wizard Panel, they display in all the wizard pages in a rendered form. When submitting data, they are empty in the submission
- FIO-5299 Remove team invitation buttons and indicators when SSO teams are enabled
- FIO-5303 PDF | Edit Grid Edit and Delete buttons show
- FIO-5310 FJS | Date Time not showing correctly when Date Time is set to MMM and manually typing Month in all CAPS
- FIO-5384 'Actions' column and buttons migrate to pdf file.
- FIO-5566 Date deprecation warning error in FormIO when using REACT
- FIO-5690 FVP | Extra empty rows are displayed in the submission table after enabling the offline mode
- FIO-5730 Item Template is not used for printing PDF when the Data Source Type is API
- FIO-5857 MinDate using moment() is not keeping/saving after clicking out of the component
- FIO-6052 CLI tool using wrong destination path
- FIO-6086 Data is being removed after submitting a Wizard form with a Field Set component
- FIO-6129 FVP |  The footer is not displayed in FVP unless the user sets branding to true in the Public Configurations.
- FIO-6258 Quill Editor not displaying the value when set by the data object
- FIO-6343 FVP | New submission is not added to the table in the offline mode, and old submissions are not displayed
- FIO-6406 Data Table filters - Select Boxes, Select, Submitted/Updated
- FIO-6551 Add USWDS support for Data Table Component
- FIO-6574 Submission Revision | Wizard Changelog - All Components - Date/Time Component shows up in Submission Changelog when not changed
- FIO-6577 Tenants | Unable to create a new stage for tenants If the stage limit exceeded for parent project.
- FIO-6585 Data Tab | 'Import CSV' functionality doesn't work for the Radio Component
- FIO-6604 Content Component | Numbered List | Numbers are outside the border in Edit Page
- FIO-6611 Enable ability to delete archived projects
- FIO-6613 Submission Revisions | '0' value is not shown in the Submission Change Log
- FIO-6649 Teams cannot be created with Only_Primary_Write_Access enabled
- FIO-6669 Nested Form Component | UI | The 'Use Original Revision while Submissions Viewing' checkbox tooltip is cut off
- FIO-6682 Error with setLanguage function when date time component is added
- FIO-6688 Edit Grid | When Minimum Length validation is set up for Edit Grid all of rows components are shown inside the EG on Edit Mode
- FIO-6694 Team Membership UI Needs to be a Scrollable Container
- FIO-6733 Hidden Field not appearing in Data Tab
- FIO-6735 Data Source | The calculated values from the data source are not displayed on the View submission page
- FIO-6769 Blank Stage should still contain default forms
- FIO-6825 Data Tab Filters | Select component (ChoicesJS, HTML5) | Filter doesn't work when Data Source type is URL/JSON/Value-object.
- FIO-6950 DataGrid errors in the formio.js Mocha tests
- FIO-6963 Migrate formio-cli to not use formio-server and instead use node-fetch
- FIO-6980 Upgrade box-node-sdk to 3.x
- FIO-6981 Replace deprecated azure-storage dependency
- FIO-7002 Investigate Hide Components property in Angular Application
- FIO-7008 Data page | Help links are pointing to the wrong place in the help documentation
- FIO-7015 Resource page | Help link is pointing to the wrong place in the help documentation
- FIO-7022 Export single form | The 'export single form' functionality doesn't work for resources
- FIO-7035 Existing Resource Fields | Dragging the Layout component does NOT include the fields saved within that layout
- FIO-7056 UI | The wizard page buttons overlap with the stage creation window.
- FIO-7067 Patch Request Fails
- FIO-7069 DOC | Correct typo on Multi-Tenancy Page in portal when project is not enabled
- FIO-7084 error: {status: 400, message: "Index with name: XXX already exists with different options"}
- FIO-7087 Admin unable to "Edit" profile info
- FIO-7096 Unable to add components with drag and drop in the Microsoft Edge browser with Mac on portal.test
- FIO-7153 Schema 3.3.17 update hook crashing larger databases
- FIO-7161 Export CSV | Issues with export csv feature when the form has been created in old versions and has conditional logic
- FIO-7166 Document DB | Field 'collation' is currently not supported
- FIO-7175 Remove Usage Page > Email help Icon reference to Default email provider
- FIO-7178 Field Based Resource Access: Settings are not saved on the first attempt.
- FIO-7209 Radio, Select Boxes | Components don't work without Value Property set when data source = URL

### Enhancements & New Features
- FIO-3422 Project JSON Import includes all Resources by querying project by Resource ID, even when they are not explicitly included in the project JSON export
- FIO-3482 Add indication/progress bar when loading project JSON and disable the 'Import Project Template' button while upload is in progress
- FIO-4429 Implement PDF auto conversion functionality for the Form Manager app
- FIO-6729 Removed superfluous data from logs
- FIO-7040 Enable selectData for all List Based Components

### Changes
- FIO-6659 Deprecate Resource and Tree Component
- FIO-6988 Remove the ability to authenticate with credentials in formio-cli

# July 31, 2023 Release
## API Server Version 8.1.2
### Fixed
 - Perform update hooks in background so db is not locked 

# July 26, 2023 Release
## API Server Version 8.1.1 _(removed from Docker as of 7/27/23)_

### Included Correlated Libraries
- portal@8.1.1
- formiojs@4.15.1
- formio@3.1.1
- premium@1.19.1
- formviewpro@1.102.1
- formmanager@1.100.3
- offline@4.3.1
- uswds@2.4.8
- vpat@2.5.0

### Bug Fixes
- FIO-5527 The ACE, CKEditor and Quill text areas are not being cleared when the reset button is pressed and then when the user tries to submit the form a error is displayed.
- FIO-6066 Add CKEditor, Quill, and ACE to renderer dev dependencies
- FIO-6840 Registration process performance regression
- FIO-6876 Fix user onboarding process and tracking codes for hosted environment
- FIO-6885 0Auth (Premium) action | Warning in UI erroneously displaying when `oauth` button had been added.
- FIO-6889 PDF | Usage page | PDFs counter and PDF Downloads counter are not working
- FIO-6901 Custom headers not passed using File Component Storage type URL
- FIO-6947 Disable "Create Project" on deployed portal when project utilization has reached maximum
- FIO-6995 Import CSV on Data Tab stripping leading 0's on numbers imported to text fields
- FIO-6999 Review Page Component | Components nested inside Layout components are not displayed in the Review Page in the PDF files of submissions; Components nested inside Columns are not displayed in the Review Page on View and Edit submission pages
- FIO-7028 Import CSV | Errors occur when importing values with leading zeros for a number component
- FIO-7029 Create Project | The '400 - "Bad Token"' error message is displayed when creating a new project
- FIO-7030 Wizard form | All wizard pages are added in one line, there is no possibility to navigate between pages
- FIO-7049 Data Table | The user is not able to populate the data table component
- FIO-7051 When localhost is used licenseServer variable is overriden by localhost:3006.
- FIO-7054 Grid Wizard - breadcrumb type setting disappears
- FIO-7060 Email Action not emailing with attached submission
- FIO-7064 Invalid alias when no username on deployed environment
- FIO-7068 Onboarding Workflow using "Enter" key does not progress which page you are on
- FIO-7102 PDF | Nested form components are not displayed in the pdf file of submission of the parent form
- FIO-7103 Webhook action | The Webhook feature is stripping off parameters from the Request URL
- FIO-7122 x-admin-key returning 401 Unauthorized when used with PDF Server
- FIO-7136 PDF Management page | The user is not able to delete pdf file
- FIO-7137 PDF | PDF API collection | The user is not able to create PDF Form with Submission (error 404)

# July 26, 2023 Release
## PDF Server Version 5.1.0

### Included Correlated Libraries
- formio-pdf@2.6.0
- premium@1.19.1
- formiojs@4.15.1
- formio-viewer@2.55.0

### Fixes
- FIO-3447 PDF | Signature | Hide gray box next to PDF signatures
- FIO-4710 PDF | Old forms: Signature: Drawings are shifted, when the PDF form is zoomed in/out
- FIO-5073 PRE | API Driven Data Table: DT data submits as an array of empty objects, which causes a DT with empty rows displays when viewing a submission after page reload and on PDF download
- FIO-6135 PDF | Ensure that you are able to fully read Date Time in PDF Download regardless of size of overlay
- FIO-6185 PDF Conversion | Unable to upload non-fillable PDF files (FFR) if several instances behind the balancer.
- FIO-6202 Update decode-uri-component
- FIO-6212 PDF Management page doesn't work on hosted environment
- FIO-6519 Enable SSL between containers on remote-uswds environment
- FIO-6712 Update xml2js
- FIO-6855 Enable Env. Variables for SSL between containers to be set as a file path
- FIO-6856 Allow PDF Server to interact with S3 when only the bucket variable is set
- FIO-6883 Remove pm2 dependency from PDF Server
- FIO-6934 PDF no longer generates if using custom viewer with an older version of formio.js
- FIO-7052 Move PDF Server functionality to restricted mode when license fails to validate
  
# June 20, 2023 Release
## API Server Version 8.1.0

### Included Correlated Libraries
- portal@8.1.0
- formiojs@4.15.0
- formio@3.1.0
- premium@1.19.0
- formviewpro@1.102.0
- formmanager@1.100.2
- offline@4.3.0
- uswds@2.4.8
- vpat@2.5.0

### Enhancements & New Features
- FIO-3529 Export single form as Project JSON template
- FIO-4429 Implement PDF auto conversion functionality for the Form Manager app
- FIO-4444 Default cursor focus to Label/Title/Legend in settings window when adding a new component to form builder
- FIO-4794 Make the 'Clear Value When Hidden' field be shown when the 'Hidden' setting is enabled
- FIO-5026 Data Table: Add a configurable option to allow / deny the data from Data Table being submitted
- FIO-5235 Premium Component - Review Page
- FIO-5272 Use the URL data source type for Radio buttons and Select boxes
- FIO-5297 Upgrade to USWDS 3.0
- FIO-5302 Add a "Hide Input" configuration option
- FIO-5408 Ability to rearrange pages in Wizard by dragging the page icons
- FIO-5474 Simple Conditionals
- FIO-5985 Implement configurable OIDC logout solution into portal
- FIO-6104 Only show Language Dropdown UI in Developer Portal if SAC flag is set
- FIO-6231 Allow opt-in to full submission data to include base64 images in API calls for the submission endpoint
- FIO-6631 Allow S3 uploads to not require access key

### Bug Fixes
- FIO-1157 Default Forms and Resources do not show Title, Name, Path or Type in the manage section until an edit has been made
- FIO-1425 Submission object empty when using calculated values on the server
- FIO-2088 Date/time component not handle casing
- FIO-2809 Checkbox: When set to Radio input type, the radio button has an excessive left padding = 20px
- FIO-2855 Selected option in Select component with Resource Data Source Type and 'Entire Object' Value Property is showing twice in dropdown list
- FIO-3258 User has to click twice on edit page to change Radio select on initial change
- FIO-3268 'Submit Form' button in Wizard and 'Submit' button in PDF form are enabled when no permissions have been granted to any user role. When submit, it shows an Unauthorized error
- FIO-3295 Data Grid | Unable to minimize group by clicking the group header
- FIO-3442 Edit Grid | Deleting a row and editing a currency component opens two rows in edit mode and does not allow you save changes or cancel changes
- FIO-3623 Disable ‘Create an admin user’ when creating a new tenant from empty stage 
- FIO-3700 Tagpad: When Day value is not set inside the Tagpad, it shows as '00/00/0000' in submission for all the dots
- FIO-3707 Tagpad: Remove Unique validation
- FIO-4187 Receiving "You must assign this button to an OAuth Action before it will work"
- FIO-4189 Advanced Logic not working inside Nested Form
- FIO-4216 When using Submission Collection Receiving 404 errors: 'Resource not found' when performing a GET request against a form that has a Select Resource
- FIO-4230 Button Component | Button Label is still showing when unchecking Show Label in DataGrid in button component inside of DataGrid
- FIO-4232 Form controller not working inside wizard forms
- FIO-4301 React | "ref" prop has been removed
- FIO-4302 React | Everytime the parent component change, the formio Instance is recreated and then destroyed immediately
- FIO-4343 Datagrid automatically expand to utilize all the horizontal space available
- FIO-4345 Tag Pad | Tag Pad button(s) not showing on Mobile
- FIO-4352 Enable the form components sidebar scrollable separately from the form.
- FIO-4439 Form Builder: Cannot delete an uploaded PDF file to upload a new one. No "Delete" button next to the "Display as" dropdown
- FIO-4500 Tags: When 'Store as' is set to 'Array of Tags', the delimeter character set in the 'Delimeter' setting is not used
- FIO-4513 Data Table: Select (Resource) saved as a reference does not show values correctly in a submission
- FIO-4551 USWDS | Data Grid: IDs are not unique between the fields inside the Field Sets in the Data Grid rows
- FIO-4568 SSO Team | After switching a Regular team to an SSO Team, when Accept is clicked, the accept and reject buttons still show, and the team count increases.
- FIO-4664 Address: Conditional logic based Address data does not fire
- FIO-4672 When performing a PUT request using POSTMAN, the View tab does not show the data
- FIO-4752 Auto scroll of page while drag and drop of components
- FIO-4756 API server needs to have CORS restrictions for tenants
- FIO-4824 Data Grid: When there are lots of components inside the Data Grid, the page widens and the Data Grid displays out of the page. Values in most components are not seen
- FIO-4876 Regression | Nested Form: When 'Use Original Revision while Submissions Viewing' is enabled for the NF, the NF submission still displays in the current form revision
- FIO-4956 On View Submission tab long text values not split up by spaces in Text Area that is in Layout and Data components are displayed in one line
- FIO-5024 Unable to Sign in using OIDC SSO
- FIO-5041 OIDC login to FVP does not work with incognito for Chrome and Brave browser
- FIO-5042 OIDC logout is not working with FVP
- FIO-5048 Components Number and Currency with Modal Edit and Multiple Values checked are not rendered on the form
- FIO-5072 Data Table: Data Tables data in old forms does not submit, even though 'Submit Data to the Server' checkbox is checked
- FIO-5073 API Driven Data Table: DT data submits as an array of empty objects, which causes a DT with empty rows displays when viewing a submission after page reload and on PDF download
- FIO-5074 Data Table: When 'Submit Data to the Server' setting is disabled, 'Required' validation should be disabled and removed from the DT component settings
- FIO-5086 Date/Time: Server-side validation does not fire up when submitting an invalid value
- FIO-5101 Event handler is resetting the disabled state of the Submit button when anything changes
- FIO-5126 Investigate why PDF Server is crashing when unable to communicate to the CDN
- FIO-5246 Unique validation not firing when using PUT request to change submission that should trigger unique validation
- FIO-5262 Select | Search breaks after user scrolls to see more and goes back to seeing the original dropdown order
- FIO-5263 Add basic keyboard accessibility for formbuilder
- FIO-5288 Existing Resource not saving Property Name correctly.
- FIO-5318 When a radio button is unchecked, the "checked" attribute should be removed or set to false.
- FIO-5335 Trying to set the value of a component through logic while it is hidden, but until the user makes it show once, the logic doesn't work.
- FIO-5369 Сlicking on the tooltip enables the checkboxes on the component settings page.
- FIO-5374 The response is not being updated with the response from the webhook
- FIO-5398 Using periods in search query for select dropdowns is not URLencoding.
- FIO-5421 Unable to install Form Builder role and Admin Modification, error occurs in the console.
- FIO-5422 Form Manager UI modifications
- FIO-5460 Address and Select components are not firing the "blur" event.
- FIO-5540 It takes several seconds to logout and load API calls.
- FIO-5574 Console errors: "TypeError: Cannot read properties of undefined (reading 'pdf')"
- FIO-5613 Public configuration tokens are not interpolated within the execution of a webhook
- FIO-5631 Redirect to main page is occurred when refreshing pages
- FIO-5637 Ensure CORS restrictions are enforced for Tenants
- FIO-5658 FMG | Data tab | Scroll bar is not displayed when the data table is empty
- FIO-5685 Serialized Select when set Value Property as {Entire Object} to be set as a string.
- FIO-5709 Export CSV | If a user selects “No” in a radio button component, the response value in the CSV shows as blank.
- FIO-5785 Select Component (URL) | When 'Value Property' is _id, all the selected values display as id when viewing a submission
- FIO-5811 Wizard | Ensure screen scrolls to top of page on wizard form when validation errors occur with wizard buttons
- FIO-5870 Replace aggregate queries
- FIO-5904 Component data outside of Wizards are not saving
- FIO-5941 Unable to use x-token to GET stage version tags using POSTMAN
- FIO-5963 Select component is empty in the downloaded PDF if Data Source Type is URL.
- FIO-5979 Enable ability for browsers to cache CORS
- FIO-5986 File Component | It is possible to upload the same file multiple times on an unstable connection
- FIO-6009 When checkboxes set as radio buttons, conditional logic isn't triggered upon "deselect"
- FIO-6029 Update Choices-js
- FIO-6041 Webhook | The request becomes invalid and the "formId" is appended with a question mark, not an ampersand when the request URL has some params.
- FIO-6052 CLI tool using wrong destination path
- FIO-6069 DocumentDB limits the namespace names for new indexes
- FIO-6078 Hidden Select Boxes Component validation preventing submission
- FIO-6100 Issue while using metadata object in calculated fields
- FIO-6123 AttachedListeners array is not cleared after detach method call
- FIO-6156 Help links are pointing to the incorrect locations
- FIO-6179 API server crashes when PDF server is not configured
- FIO-6218 Take CDN url from public configuration of FMG
- FIO-6249 Legacy PDF Server URL settings no longer overraide env variable for pdf download
- FIO-6253 Apply PDF proxy updates to PDF upload and download
- FIO-6273 Update Portal CKEditor
- FIO-6274 Can not submit the Dynamic Wizard data Component Headers
- FIO-6275 Sketchpad component can not edit and save
- FIO-6277 When a user is assigned to a team, it can take up to 20 minutes for the user to see they have been invited to the team
- FIO-6301 The signature component is not marked as required and its elements are overlapped
- FIO-6307 Change form controller helper text: Instance - The current component instance
- FIO-6318 'Stage Settings' link redirects the user to Home page on Email action page.
- FIO-6323 When switching to Quill text editor, the data inside of the text area does not transfer over
- FIO-6345 Add rel=noopener to Portal Application Links to Docs / External Links
- FIO-6355 Enable counting of tenants with offline license
- FIO-6377 Project Plan page shouldn't be visible for team members who have 'Write/Read' project permissions.
- FIO-6406 Data Table filters - Select Boxes, Select, Submitted/Updated
- FIO-6407 Select component not storing expected value
- FIO-6419 fast-xml-parser dependency update
- FIO-6424 PDF Submission | Select Data is rendered incorrectly
- FIO-6446 Can't enable exists endpoint on access settings, can only do via API
- FIO-6447 FVP | Permissions | Authenticated role | Authenticated user with enterprise or team pro project plan is not able to log into FVP
- FIO-6453 Fix backend validation errors
- FIO-6466 Select Component not loading using custom datasource after upgrade from FJS and PRE
- FIO-6468 Custom validation on Day component confusing Day and Year
- FIO-6469 Double quotes (") turned to single quotes (') in placeholder text
- FIO-6470 FMG | Export CSV | Select Boxes Component values are displayed as [object Object] in the CSV file
- FIO-6474 Archived plan | An error message should be corrected when the user tries to delete a submission
- FIO-6475 Archived plan | An error message is not displayed when the user tries to add a new action
- FIO-6480 Data table | The data table displays the wrong number of rows after applying and removing the filters
- FIO-6509 Unauthorized error occurs on Usage page for PDF Utilization table for Trial level project.
- FIO-6513 Remote redirect causing infinite loops
- FIO-6526 USWDS date field missing "success" border
- FIO-6529 UI glitch in the Portal App when you access a project that is disabled
- FIO-6533 File upload hash causing delays in file uploads
- FIO-6554 Sign up page | Errors 404 occur when the user clicks on the 'Software Agreement' and 'Open Source License' links
- FIO-6555 Form Access Controls - consolidate save buttons
- FIO-6571 Submission Revision | Wizard Changelog - All Components - Quill text editor is not displaying data on submission
- FIO-6582 Data in older form not visible though still present in database
- FIO-6601 Add submission collection lookup when loading form submissions
- FIO-6614 Submission Revisions | Change the copy on the /revisions page
- FIO-6617 Field Based Resource Access: The user with Authenticated role doesn't have access to the submissions that have been assigned to them
- FIO-6618 Form Access: 'Allow access to EXISTS endpoint...' checkbox value is saved on backend but doesn't save on UI.
- FIO-6625 FVP | An error occurs when displaying the form preview on the Launch page
- FIO-6627 Remove case-sensitivity when adding emails to Teams
- FIO-6638 Remove IndexedDB as option in data source component source dropdown
- FIO-6654 Simple Conditions: UI issue with Checkbox condition.
- FIO-6661 Document how to translate Date/Time Component & Flatpickr
- FIO-6662 Session on login would not work if your database is using readSecondary for replica sets
- FIO-6663 Unable to use Import CSV on Data Tab, 'Migrate' button is disabled.
- FIO-6670 UI | Interface overlay occurs in the component settings (Ace editor and the 'Options Label Position' dropdown)
- FIO-6671 Teams | Change copy on the create/team page
- FIO-6675 React App - Selecting "Cancel" during remove confirmation dialog removes page
- FIO-6676 React - When form builder changes anything change event is not being fired
- FIO-6685 Review Page Component | The user is not able to drag and drop the Review Page component to the form when the form contains the Select Boxes Component
- FIO-6686 Recently created/updated forms/resources aren't displayed in the top position on the Forms page.
- FIO-6687 Data Tab | Text Area | The value is displayed in one line
- FIO-6691 Review Page Component | TypeError: 'Cannot read properties of undefined (reading 'forEach')' is shown when the Review Page is added as the first component of the form
- FIO-6711 FormIo-angular can't edit PDF form in Chrome
- FIO-6715 ACC | FMG | Data Table isn't displayed on View Data tab when 'vpat' is true.
- FIO-6760 Select Component (Resource, resource multiple values) | Data isn't rendered correctly.
- FIO-6766 Select Boxes, Radio, Select Components | Default Value is displayed as an input field after saving the settings. The user is not able to choose default value/s from the list
- FIO-6768 Data security update
- FIO-6774 Data security update
- FIO-6788 Enable pagination of projects to increase initial portal load performance
- FIO-6798 Nested Form: When 'Use Original Revision while Submissions Viewing' is enabled for the Nested Form, and specific form revision selected the PDF submission still displays in the current form revision
- FIO-6824 Fix performance issues on the home page and form and resource index pages
- FIO-6831 Form Revisions | When the user is viewing submitted data for revision X, submissions for all form revisions display in the Data Tab.
- FIO-6835 API server crashing with the pdf-proxy middleware
- FIO-6840 Registration process performance regression
- FIO-6858 Conditional Tab refreshes and clears select component value from UI on selection of a value, selection is still saved.
- FIO-6862 502 error when setting calculated values on edit grid with Calculate Values on Server
- FIO-6874 Fix TypeError: n.loadlanguage is not a function
- FIO-6875 Form Manager License updates
- FIO-6876 Fix user onboarding process and tracking codes for hosted environment
- FIO-6887 Investigate form manager license management
- FIO-6889 PDF | Usage page | PDFs counter and PDF Downloads counter are not working
- FIO-6898 On-premise environment | When the project connected to on-premise environment as a new stage - form/resources are not displayed.
- FIO-6912 Signature Component | Unique settings are missed (footer text, pen color, background color)
- FIO-6948 Forms page | The user is not able to copy a form (new and existing projects)

### Changes
- FIO-6082 Change the pagination and the place for select all in grid repository
- FIO-6124 Add eSign action to the Form Manager
- FIO-6137 Allow configuration of Box Sign component text
- FIO-6404 Update hook to modify all date/time component data to ISO date formats
- FIO-6541 Documentation for Logic Tab
- FIO-6729 Log data output modifications
- FIO-6761 Remove 'Storage Type' setting from the component settings for Radio, Checkbox, Select Boxes


# June 8, 2023 Release
## API Server Version 8.0.3

### Included Correlated Libraries
- portal@8.0.4
- formiojs@4.14.14
- formio@3.0.2
- premium@1.18.10
- formviewpro@1.101.1
- formmanager@1.100.1-patch.1
- offline@4.2.4
- uswds@2.4.8
- vpat@2.5.0

### Feature
 - Form manager license management UI

### Fixes
 - UI performance improvements

# May 19, 2023 Release
## API Server Version 8.0.2

### Included Correlated Libraries
- portal@8.0.2
- formiojs@4.14.14
- formio@3.0.2
- premium@1.18.10
- formviewpro@1.101.1
- formmanager@1.100.1-patch.1
- offline@4.2.4
- uswds@2.4.8
- vpat@2.5.0

### Bug Fixes
- FIO-6419 Update fast-xml-parser
- FIO-6627 Remove case-sensitivity when adding emails to Teams
- FIO-6647 FMG | Unable to Sign in using OIDC SSO
- FIO-6662 Session on login would not work if your database is using readSecondary for replica sets
- FIO-6670 UI | Interface overlay occurs in the component settings (Ace editor and the 'Options Label Position' dropdown)
- FIO-6841 Hidden Select Boxes Component validation preventing submission


# May 5th, 2023 Release
## PDF Server Version 5.0.2

### Included Correlated Libraries
- formio-pdf@2.5.2
- premium@1.18.9
- formiojs@4.14.13
- formio-viewer@2.54.2

### Changes
 - FIO-6650: Updates to SSL configuration
 - FIO-6640: Migration to new container image to fix dependency problems between chromium and pdf2htmlEX
 - FIO-6707: PDF submission evaluation context CDN no longer hardcoded to HTTP

# April 3rd, 2023 Release
## API Server Version 8.0.1

- portal@8.0.1
- formiojs@4.14.13
- formio@3.0.1
- premium@1.18.9
- formviewpro@1.101.0
- formmanager@1.100.1
- offline@4.2.3
- uswds@2.4.8
- vpat@2.5.0

### Bug Fixes
- FIO-2932 Select Dropdown is showing values twice
- FIO-3826 Protected mode: Settings: "Delete Stage" button is enabled. Using direct URL, user can open "Delete Stage" page as well
- FIO-3829 Settings > API Settings > API Keys > Add more space for "API Keys" column in the grid
- FIO-4263 Security Update
- FIO-4274 Teams: Make changes to the display of team members on all the related pages to maintain consistency
- FIO-4705 GET {{projectURL}}/current request returns with 400 Bad Request and an error in a console
- FIO-4828 Sign Up Email Template fixes
- FIO-4868 FormIO application server throws a CORS error
- FIO-5109 Calendar icon does not display on PDF download using USWDS Viewer
- FIO-5511 Validation not triggering using row in container components
- FIO-5534 Enable ability to retrieve PDF File via API & in PDF Management Page
- FIO-5571 Sketchpad Issues when using files other than SVG files
- FIO-5646 General License Issues
- FIO-5744 Update Field Based Resource Access settings so it shows correct Permissions
- FIO-5758 S&C License | Issue with retrieving encrypted data.
- FIO-5785 Select Component (URL) | When 'Value Property' is _id, all the selected values display as id when viewing a submission
- FIO-5819 Forms page doesn't update after stage importing.
- FIO-5866 Disable autosave on license management page
- FIO-5889 Change Limit counting on SaaS portal to use MongoDB instead of Redis
- FIO-5899 Change reset password in hosted environment to use reset password workflow
- FIO-5911 Email action will naively create an attachment PDF out of any response from PDF server generation
- FIO-5937 Panel with 'Collapsed' setting checked does not display validation error message after collapsing/expanding the panel
- FIO-5978 Initial user registration requires password reset to log in
- FIO-5991 Update node-saml dependency
- FIO-6076 Stage team permissions are wiped when upgrading the stage to a new version and the admin user can't change Stage Team settings
- FIO-6085 Fix wildcard CORS to return the correct value for Access-Control-Allow-Origin
- FIO-6095 Uncaught Exception using S&C
- FIO-6114 Box Sign | Signature components for signing are displayed in the order of creation, and not in the order set by the settings ("Signer Order" setting)
- FIO-6115 eSign action| Error 500 occurs when 'Approvers' and/or 'Final Signed Copy Recipients' are/is filled with an interpolated value
- FIO-6117 Box Sign | The form does NOT automatically redirect the user to Box Sign's website upon form submission
- FIO-6133 Form View Pro doesn't work at stages other than Live.
- FIO-6145 Address component inside edit grid displays dropdown behind modal
- FIO-6148 Box Sign | The user is NOT able to re-sign the wizard form submission with Box Sign Component (error 500) when editing the submission
- FIO-6154 Content type for {{pdfServer}}/pdf/{{projectId}}/file/{{pdfFileName}}.pdf endpoint is text/html instead of application/pdf.
- FIO-6162 Tenant Manager on initial load takes longer to load
- FIO-6167 When a new stage is created inside the Tenant it is displayed as a project on License Management page.
- FIO-6176 The 'Unauthorized' error occurs when trying to open a form in the FormView Pro
- FIO-6179 API server crashes when PDF server is not configured
- FIO-6180 API: Date/Time components are not being saved in ISO format in MongoDB
- FIO-6181 Update jsonwebtoken dependencies
- FIO-6189 Team admin member cannot see edit button
- FIO-6198 Unexpected behavior when adding members to the team: there is no 'Invitation pending' tag, unable to remove team members or make them admin.
- FIO-6215 Update knex dependency
- FIO-6216 Update resourcejs dependency
- FIO-6217 Take CDN url from public configuration of portal
- FIO-6218 Take CDN url from public configuration of FMG
- FIO-6219 Take CDN url from public configuration of FVP
- FIO-6220 CDN class improvements
- FIO-6227 When already authenticated, navigating directly to //auth endpoint does not properly redirect
- FIO-6228 Update xmldom dependency
- FIO-6229 Text field input adjustments
- FIO-6235 Change Basic to Archived for hosted project plans
- FIO-6237 Stage Settings don't save any configuration
- FIO-6238 Stage Settings | Stage Framework and Stage Path are not displayed (not always reproduced)
- FIO-6249 Remove PDF Server URL setting and deferring to env variable for pdf download
- FIO-6255 Security Update
- FIO-6261 FMG | Email action | The user is not able to change an email provider via FMG
- FIO-6270 SQL Connector Project Settings Don't Persist
- FIO-6273 Update Portal CKEditor
- FIO-6282 Remove twilio dependency
- FIO-6285 Auth-2FA page | An error message is displayed when the user taps the 'Log out' button
- FIO-6298 Radio button erroneously resetting value
- FIO-6303 Invalid alias error when reaching PDF proxy endpoints
- FIO-6304 Form.io is hard-coded in the settings for the stage path.
- FIO-6308 Form API tab | The "Resource Fields" table does not fit on the page and there is no scroll bar
- FIO-6320 CORS error for pdf management page on hosted.
- FIO-6321 The user cannot submit the form in the FVP when 'Make Public' option is activated
- FIO-6327 Browser freezing when moving between stages
- FIO-6329 Public configuration should override every other CDN url
- FIO-6332 Tenants UI fixes
- FIO-6333 Tenants | The 'NaN - NaN' value is displayed below the tenant list on the Tenant Main page when the list is empty
- FIO-6334 Email Action Warning in UI erroneously displaying when Email Transport has been configured
- FIO-6337 Teams tab | Teams list is cut off and there is no scroll bar
- FIO-6339 File Upload component updates
- FIO-6347 When creating a stage, it will inherit the parent's plan
- FIO-6371 UI issue | Data Table Component | The search filter form is cut off- FIO-6431 Quick Inline Embed | Data Table component | The component is NOT displayed and doesn't work correctly using Quick inline Embed Link
- FIO-6422 Resolve postgres-settings-knex-raw-error
- FIO-6436 Ensure we do not reject the server-to-server call from pdf to server
- FIO-6441 Submission Revisions | The user is not able to enable Submission Revisions in the deployed environment
- FIO-6462 SSO Teams option not available
- FIO-6463 PDF proxy removing content-type header
- FIO-6471 Data Tab | 'Import CSV' functionality doesn't work for the Select Boxes Component
- FIO-6489 CORS errors on portal-check endpoint
- FIO-6512 Cannot drag and drop components on to PDF first forms using Mac
- FIO-6523 Add stage limit for Offline License on portal.form.io
- FIO-6556 Synchronous form building not properly saving changes
- FIO-6579 Unable to export legacy projects
- FIO-6594 Field Based Resource Access: Permissions aren't saved in form JSON

# April 3rd, 2023 Release
## PDF Server Version 5.0.1

### Included Correlated Libraries
- formio-pdf@2.5.2
- premium@1.18.9
- formiojs@4.14.13
- formio-viewer@2.54.2

### Bug Fixes
- FIO-6037 The new offline license creator doesn't ask if you want to include API / PDF anymore automatically giving everyone PDF server
- FIO-6203 Update superagent dependency
- FIO-6204 Update vm2 dependency
- FIO-6368 Fix the PDF server so that any process.exit() calls should not cause a PM2 restart
- FIO-6464 PDF download for forms without settings property
- FIO-6465 addStyleTag function calls causing race condition
- FIO-6488 Fix unlink error
- FIO-6498 Improved auth middleware debugging
- FIO-6505 Cannot read properties of undefined (reading data) when trying to get project info on remote pdf server
- FIO-6365 Update puppeteer to latest

### New Feature
- FIO-6499 Add configurable file cache time


# January 17th, 2023 Release
## PDF Server Version 5.0.0

### Included Correlated Libraries
- formio-pdf@2.5.1
- premium@1.18.8
- formiojs@4.14.12
- formio-viewer@2.54.1

## Breaking Changes

### API Server compatibility alert!!!
- Use of PDF Server version 5.0.0 requires the use of API Server version 8.0.0 or later. Significant changes made to authorization functionality of the PDF Server were required for this latest release of the PDF server, breaking backwards compatibility with all versions of the API Server prior to the formio-enterprise:8.0.0 release.

- When tagging formio/formio-enterprise and formio/pdf-server, do not use the “latest” tag (formio/pdf-server:latest). Instead, tag the API and PDF Server versions to the version tag you intend to use (Example: formio/pdf-server: 5.0.0)_

- Custom PDF Viewers must be upgraded to use Formio.js Version 4.14.12 or higher.

## Major PDF Server Improvements:

Control how your PDFs look and feel
- Condensed PDF Print Mode: As you may know, our digital web forms are mobile responsive and look great on whatever device you are on.  Now you can print these forms to PDF using a compact view of the webform submission to PDF output without having to build your own viewer - This is a major time savings for PDF print outs!
- Configurable default font size for PDF Downloads
- Configurable option to display Radio Button and Checkbox backgrounds
- Option for Portrait or Landscape page layout in Form Settings for PDF Downloads

## Performance improvements
- PDF Generation speeds increased up to 5x when compared to 3.x PDF server
- Optimized fetching & storing of HTML files used during PDF Printout 
- Improved error handling middleware to log more verbose errors 
- Added native support of Azure uploads to the PDF server


## Enhancements & New Features
-  FIO-5959 Enable Box Sign as E-Sign Provider
-  FIO-6105 Improved debug info for add-formfields and convert middlewares
-  FIO-5751 Remove base64 file data from logs
-  FIO-5797 Make external libs urls configurable
-  FIO-5939 Add formfields recognition status endpoint

## Bug Fixes
- FIO-4357 Sketchpad component overlay image Absolute Positioning on Background Image causing pagebreak to not be respected
- FIO-4689 Text Area: Editors: When a font-size is set to editors through CSS, it does not override the global PDF font size on a rendered form
- FIO-4777 When File component has no layout box on PDF first form, gray overlay and spinner display where file component should be on PDF download
- FIO-4793 Date/Time: When default value is set to moment() and user does not click the input field to open a calendar widget, current date/time value in UTC time zone will be submitted which lead to the incorrect display on PDF download
- FIO-4825 Data Grid: When there are lots of components inside the Data Grid, not all of them display on PDF download
- FIO-5033 Cannot download as PDF, 'x-file-token is invalid' error is displayed
- FIO-5126 Resolve crashes due to CDN connection
- FIO-5233 Date/Time PDF download inconsistent with submission
- FIO-5280 Using mobile (touch events), signature component is not working on PDF form 
- FIO-5308 Large PDF not printing in customer environment
- FIO-5449 When file uploads do not pass file type or size validation, there is no possibility to remove that file and select another one
- FIO-5515 Data Source data not getting pulled into PDF Download
- FIO-5534 Enable ability to retrieve PDF File via API & in PDF Management Page
- FIO-5697 PDF is not showing borders in Data Grids larger than one column
- FIO-5806 Inaccurate error message in the response for GET request from anonymous user if x-jwt-token is absent.
- FIO-5882 Receiving "function not found findOne" when creating new PDFs
- FIO-6116 Data is not displayed when viewing submission of pdf form with Box Sign component
- FIO-6154 Content type for {{pdfServer}}/pdf/{{projectId}}/file/{{pdfFileName}}.pdf endpoint is text/html instead of application/pdf.
- FIO-6158 Add timeout to HTML gen child process


# January 6th, 2023 Release
## API Server Version 8.0.0

- portal@8.0.0
- formiojs@4.14.12
- formio@3.0.0
- premium@1.18.8
- formviewpro@1.100.0
- formmanager@1.100.0
- offline@4.2.0
- uswds@2.4.8
- vpat@2.5.0

## Enhancements & New Features
- FIO-800 Ability to delete the license utilization
- FIO-3042 Ability for users in deployed server to not be able create new projects
- FIO-3054 Enable ability to log in to the portal base project as an Admin
- FIO-3331 Show the full name of the Form/Resource while on the Edit tab
- FIO-3555 Implement Two-Factor Auth for the Form.io Authentication
- FIO-4075 Overview page rework
- FIO-4076 Project sidebar: UI changes
- FIO-4210 Add ability to specify path to 'email' property of user object in OAuth OpenID settings
- FIO-4212 Enable ability to log in to the portal base project as an Admin
- FIO-4213 Ability for users in deployed server to not be able create new projects via ONLY_PRIMARY_WRITE_ACCESS env variable
- FIO-4261 Enable Communication from portal to server to report domain on which the portal is running
- FIO-4264 Add option to choose Portrait or Landscape in Form Settings for PDF generation
- FIO-4327 Implement wizard header type selection
- FIO-4420 PDF conversion: Enable PDF auto conversion for the PDF files uploaded after switching the form type from web/wizard to PDF
- FIO-4430 Implement PDF auto conversion functionality for the Next Portal
- FIO-4448 Enable ability to upload CSV data directly to a Resource/Form through Developer Portal
- FIO-4481 Add a spinner for PDF upload and remove the Upload PDF button when the PDF file is processed
- FIO-4509 Allow for PDF migration to work with Project Import as well as Single form imports via Form Embed URL
- FIO-4713 Enable ability to turn off the sanitize method
- FIO-4717 Google Drive Integration
- FIO-4719 Configurable default font size for PDF Downloads
- FIO-4823 Box Sign Component
- FIO-4859 Field Based Resource Access not respecting PATCH request to dependent field
- FIO-4978 Enable Translation of Portal Application, part of S&C package
- FIO-5194 Create PDF configurable option for Radio button and Check Boxes so that the background is shown or not
- FIO-5476 Condensed PDF Print Mode for api 8.0.0
- FIO-5898 Deprecate reset password action


## Bug Fixes

- FIO-895 Project Framework type does not carry over from live to stage. Unable to update Stage framework
- FIO-1152 Receiving Not Found Error when submitting Credit Card
- FIO-1156 Billing Page | On Accounts that have Credit Card already added unable to upgrade or downgrade project. Receiving Bad Request Error.
- FIO-1314 Uploaded image in a File component does not display in a generated PDF file when 'Display as image\(s\)' setting is enabled
- FIO-1325 Update footer to include updated info
- FIO-2677 When creating submissions using POSTMAN, the PDF download does not always show the data
- FIO-2902 Project Plan: Remove Independent project plan
- FIO-3105 Remove ability to switch to on premise environment using hosted project plan
- FIO-3106 Staging: Connect Environment: 'On-Premise Environments Help' link leads to 6.x server instructions page
- FIO-3107 Project Name does not change correctly when connecting to On-Premise env and does not return when disconnecting from it
- FIO-3108 Staging: Connect Environment: Labels have no connection with input fields
- FIO-3123 Cannot create stages on Next. On Portal there is no such a problem
- FIO-3124 Staging: Export Template: Include Template Components table: 'Select/deselect all' link stops working after diselecting and then selecting the values. It also has no appropriate link styling
- FIO-3125 Staging: Import & Export Template pages: Remove 'Cancel' buttons from these pages since they do not match the design now
- FIO-3126 Staging: Export Template page: Clicking on 'select/diselect all' link in the Actions section when there are disabled checkboxes, all the Actions become selected and presented in the project JSON
- FIO-3132 Teams page: 'Add a team' should not look like a button
- FIO-3133 Teams page: Remove autosaving and add 'Save Team Settings' button
- FIO-3135 Footer: Unpin the footer from the bottom of the page. It's not a good design and the footer sometimes overlap content on various pages
- FIO-3136 Create a Team page: No 'SSO Team' checkbox
- FIO-3137 View a Team page: Clicking on the expand/collapse button in the sidebar, you are redirected to the Projects page
- FIO-3140 Staging pages: Warning banners that should restrict usage of some functionalities display incorrectly
- FIO-3141 Team permissions: I see Access and Staging links having Project Read or Write permission
- FIO-3142 View a Team page: Remove autosaving and add 'Save Team Settings' button
- FIO-3261 Form Module settings not saving
- FIO-3308 Email submission: Checkbox \(radio type\): Selected checkbox displays as empty
- FIO-3312 Team permissions: Users with Project Read or Write permissions can reach the Action Logs page in the Form builder
- FIO-3313 Team permissions: Users with Project Read or Write permissions can reach the Project Team page using direct URL
- FIO-3315 Stage Settings: Project Path field is enabled on Trial and Basic project plans
- FIO-3316 Stage Settings page and Project Settings page design flaws
- FIO-3368 PDF | File: When 'Display as Images' and 'Enable Webcam' settings are enabled, and the overlay box height ≈ 100px, the video module displays shifted to the right
- FIO-3404 Modal Edit/ Data Table | Modal Edit and Data Table is blocking part of the Navigation Bar when Navigation is showing in Use Tab
- FIO-3411 File Component - Receiving \[object ProgressEvent\] on file upload when changing Environment settings on Next instead of Production.
- FIO-3434 OIDC - After registering a new account using OpenID, I am sent to an email confirmation page, but I am a logged-in user and can access my portal
- FIO-3485 'Save' button should overlay fields and field settings icon in form builder
- FIO-3534 After deleting a form, I get back to the Edit form page and see the deleted form, as though it was not deleted. Adter page refresh the form does not load anymore.
- FIO-3554 Fix typo on Field Match Based Access
- FIO-3573 Launch tab: remove the 'Launch' form preview
- FIO-3585 Teams: Wrong number of users display in teams on the Projects page when users reject invitation
- FIO-3586 Teams: When clicking the 'Reject Invitation' button, I'm asked if I want to leave the team, even though I'm not in the team yet. Should be no confirmation window
- FIO-3587 Teams: Project Access permission does not display in the Project tab on the Edit Team page
- FIO-3607 Teams: When using search function on 'Member' or 'Invites' pages, results do not consider the pages filters \('only members' and 'only invites'\)
- FIO-3611 Profile: Hide the 'Edit' tab when logged in using SSO with OIDC. Otherwise, I get 'Not Found' error when open it
- FIO-3613 Forms & Resources: Access & Form Settings tabs: Incorrect links to docs
- FIO-3614 Import Resource: When importing a resource, it creates as a form and not a resource
- FIO-3635 Incorrect project limits on Portal comparing to Project Plan Limits documentation
- FIO-3636 Project Plan: Selecting Team Pro plan and increasing and then decreasing a number of PDFs by one step, I get 1000 / month PDF downloads instead of 10 / month. Switching to Enterprise after that, I see 1 PDF Form instead of 25
- FIO-3720 Form Builder: When you drag a component and try to scroll a form by MMB, it does not scroll, making it impossible to move the components out of the visible edges of the form
- FIO-3721 Settings: Authorization: Form.io Auth: 'Token Parse' section is missing
- FIO-3725 Action Logs: Submission filter shows all the available results when no matches found
- FIO-3726 Sidebar: It displays with UI issues on scale >150%, resolution: 1080p
- FIO-3727 PDF | Not able to upload a PDF file when the PDF server is not set up, it works fine on portal.form.io though
- FIO-3729 Form builder: Able to save components with non-unique API keys saving the form by clicking on the Use page button and confirming saving changes
- FIO-3730 Form builder: Confirmation window does not show up anymore after saving the form changes that cannot be saved \(e.g. in case of non-unique API keys\) and leaving the Edit tab
- FIO-3755 No error display when entering URL in an invalid format into the "Embed URL" field when importing a form. Get a "TypeError: s is null" error in a console
- FIO-3764 LIC | Tenants' stages and project stages are registering as projects when connecting to a remote environment.
- FIO-3787 LIC | When trying to Connect a Tenant to an On-Premise Environment, receiving a 400 Error
- FIO-3788 Form Builder: Cannot delete an uploaded PDF file to upload a new one. No "Delete" button next to the "Display as" dropdown
- FIO-3789 Form builder: Cursor is in "Text" mode instead of "Pointer" mode when hovering over the options in the "Display as" dropdown
- FIO-3790 I see "Please verify your email "Click here to verify"!" message with a button at the top of the website. Clicking on the button, nothing happens. No way to remove it
- FIO-3791 Form Settings: Saving the changes for the 2nd time, they are not saved, and the old values display
- FIO-3792 Form Builder: Move "Display as" dropdown to the Builder Sidebar, so that there is no blank area to the right of the "Display as" dropdown
- FIO-3793 Form Builder: Clicking the "Launch" tab button when the page is not fully loaded, I cannot reach FVP. Only when the page is fully loaded, redirection occurs. When on "Use" page, the "Launch" button stops working at all
- FIO-3794 New Form page: Cursor displays in "Deafult" mode instead of "Pointer" mode when hovering over the "PDF Form" image
- FIO-3795 New Form page: Make "API Web Form" and "PDF Form" options looks like clickable elements on the page
- FIO-3799 Protected mode: Resources, Forms, Data, Access pages: Resource and Form titles are disabled and hidden below the "More Info..." link. There is no way to open the form even to make a submission
- FIO-3800 Protected mode: Form & Resource pages: "Edit", "Actions", "Access", "Launch" navbar buttons look like enabled, they are disabled though
- FIO-3801 Protected mode: Form Builder: "Revisions", "Action Logs", "Form Settings", "Delete Form" navbar buttons are enabled, they should be disabled though. Users are not allowed to do any modifications to the form on those pages
- FIO-3803 Protected mode: Use page: "Launch this form" link is displayed. Should be hidden
- FIO-3805 Resources page: Use page: "If you would like other people to use this form, then you can Launch this form" message hides immediately after page load. Should display, since we are going to allow launch resources on next
- FIO-3807 Protected mode: Access page: Project Roles table: Users can access disabled pages using direct links. Should be redirected to the Home page instead
- FIO-3808 Protected mode: Form & Resource pages: Users can access disabled pages using direct links. Should be redirected to the Home page instead
- FIO-3810 Install Attribution Tracking on our portal in order to track registrations
- FIO-3814 Select registers for URL retrieval every time it is made hidden / visible
- FIO-3827 Project Teams: When Protected mode is enabled for the Live stage, switching the Project Teams permissions to Access and then to any other permission, the Access permission stays selected
- FIO-3828 Protected mode: Settings: Stage Settings: Title is disabled. Should be enabled
- FIO-3830 Settings: API Settings: API Keys & CORS sections: No help info
- FIO-3831 Settings: API Settings: API Keys: Cannot delete API Keys. When deleted and saved, they still display after page reload
- FIO-3832 Settings: API Settings: API Keys: Name values are not incremented on creation and display as "Key" for all the keys
- FIO-3833 Settings: API Settings: CORS: Entering anything into the "CORS" field and saving the settings, the stage does not load anymore because of the CORS policies. Portal loads on production though
- FIO-3834 Settings: API Settings: "CSP" page is missing
- FIO-3835 Settings: PDF Settings: "Global PDF Settings" section is missing
- FIO-3847 Settings: Public Configuration: "Add Public Configuration to Forms schema." checkbox and the Public Config data grid are not hidden when the "Enable Public Configurations" checkbox is not checked
- FIO-3848 Settings: Public Configuration: Public configuration endpoint displays as though it is hosted on localhost
- FIO-3849 Settings: Public Configuration: Warning message, "How to use Public Configurations" and "Form Manager Configurations" help sections are missing
- FIO-3850 Settings: Public Configuration: "JSON" checkbox is saved as unchecked, even when the value has a valid JSON format
- FIO-3851 Settings: Public Configuration: When saving a public config \(value not in a JSON format, "JSON" checkbox checked\), the settings are not saved, and there is Syntax error in a console. No indication of an invalid action on UI
- FIO-3863 Settings: Integration: Email Provider & File Storage: SMTP, Sendgrid, Mailgun, Custom, Amazon S3 / Minio: Remove the h4 headings from the pages to match the design of other similar pages
- FIO-3864 Settings: Change the names of some setting menus
- FIO-3866 Top region: Form Manager icon does not display at the top right when FMG is enabled for the stage
- FIO-3892 Cannot save settings. Receiving 'Uncaught \(in promise\) TypeError: o.settings.oauth is undefined' error on save
- FIO-3900 Environment Settings page is not loading. Error: Missing formId
- FIO-4003 Revision system where the revision ID's are not consistent when they are deployed into other stages
- FIO-4114 Project sidebar: Clicking the Resources or Forms, the page scrolls down a bit, so that the selected option in the sidebar is at the top
- FIO-4115 Project sidebar: Clicking the PDF link, the Settings link becomes highlighted as well
- FIO-4116 Form builder: Adding a component to the form, it takes a few seconds to do it accompanied by CPU utilization increasing
- FIO-4117 Settings: Public Configuration: Get lots of empty rows in Public Config after saving one key - value pair. After that I cannot save settings. Get 'T is undefined' on save
- FIO-4124 PDF icon disappears when view button is clicked
- FIO-4150 Form builder: Errors hide after saving the form with non-unique API keys, only the fields stay highlighted in red
- FIO-4151 Stage Name instead of the Project Name displays in project content when switching to any stage but Live
- FIO-4165 Button background isn't clickable, only button text is clickable
- FIO-4166 Teams navbar with All, Member, Invites tabs is too wide
- FIO-4173 Investigate 404 error with empty "project" parameter value provided in the URL
- FIO-4183 Embed Form for creation of Quick Inline Embed Code
- FIO-4206 Incorrect project limits on Portal and Next comparing to Pricing page
- FIO-4211 Teams: When adding a new member to a team, the INVITATION PENDING status does not display below the user email
- FIO-4220 Login Action | Role Assignment | OAuth | Resources not loading in Actions dropdown
- FIO-4253 PDF Management: When a new stage is copied from the stage that has PDF forms and PDF files, they do not display on PDF Management page, though they are returned in the response
- FIO-4254 Receiving error when clicking Tenants UI Button
- FIO-4255 Teams: When you are invited to a team, you no longer see the Reject Invitation button
- FIO-4256 Teams - The Ability to make team emails case sensitive
- FIO-4259 Revisions - When I have made a revision changing 'Form Settings', the 'Form Settings' configurations do not revert when I restore a previous form revision
- FIO-4265 Team Owner displays as a Team Admin
- FIO-4271 Unable to reclick “select/unselect all” on Export Template after initial click
- FIO-4274 Teams: Make changes to the display of team members on all the related pages to maintain consistency
- FIO-4329 Data table: When the Data Table component has 'Table View' setting disabled, and there are components inside it having it enabled, they will display in the Data grid table on the Data page
- FIO-4431 Unable to Create TEAMS. Receiving Unauthorized Error
- FIO-4433 Value does not recalculate on server when making a draft submission
- FIO-4465 iFrame Embed: src ="https://formview.io/...", the environment is outdated though
- FIO-4483 Display of the Tenants/Form Manager button is not constant when switching the stages
- FIO-4501 PDF, Overlay components on PDF are shifting after importing a form embed url or project import with PDF first form
- FIO-4502 “Save as Draft” functionality not working in order to pass saveDraft key using options object in Form component.
- FIO-4505 Resources, Forms, Access, Data pages: Forms are sorted by alphabetical order instead of being sorted by the last time they were updated
- FIO-4510 Unable to download PDF submission when migrated from another stage
- FIO-4511 Enable PDF files between environments with Stage Deployments
- FIO-4515 Investigate if the PORTAL\_SSO\_LOGOUT environment variable also sets the PORTAL\_SSO variable
- FIO-4516 When you re-import an updated parent form from a tenant to a stage, the linkage breaks
- FIO-4517 When creating a new stage or tenant, allow selecting which stage to copy from \(instead of only live\)
- FIO-4520 OIDC - After registering a new account using OpenID, I am sent to an email confirmation page, but I am a logged-in user and can access my portal
- FIO-4580 Date Time | Date is showing the date prior to the submitted date on Data Table.
- FIO-4588 Change the content of the modal window of a file migration process
- FIO-4696 Custom JavaScript pollution between stages of different projects
- FIO-4715 Revisions | When viewing data from initial version, it should show data as form and is instead being shown as wizard
- FIO-4721 A wrong message appears when try to save components when unique API key was match
- FIO-4722 Custom JavaScript pollution between stages
- FIO-4723 Resources, Forms, Access, Data pages: Forms are sorted by alphabetical order instead of being sorted by the last time they were updated
- FIO-4725 VUE | Form is not rendering TypeError: Cannot call a class as a function
- FIO-4727 PRE, Data Table: Columns of the components inside Container, Data Grid, Edit Grid, Tree display in the Data Table, though they are always empty
- FIO-4728 Receiving unauthorized error when deleting a stage connected to an onprem environment
- FIO-4729 FJS, PDF | Unable to open PDF overlay component settings after moving the component on PDF and saving
- FIO-4730 Kendo UI grid is not displaying data or fields
- FIO-4731 Unable to add a new stage to a project. The 'Add Stage' button is disabled when I enter a Stage Title
- FIO-4741 Bug Bounty: No length on password leading to denial Application level Dos on service
- FIO-4747 APP, Form Revisions: When there is a draft revision created and the user is restoring a form revision and saving it as a new draft, the changes do not preserve and the original draft displays after the page refresh
- FIO-4761 Kendo UI Grid: There is no horizontal scroll. All the columns are too narrow and display only first characters of the values
- FIO-4810 When there is / character that is followed by a anything else, the search results are not relevant
- FIO-4812 Action Logs: When switch from Trial or Enterprise to lower level project plans, the Action Logs are still eanbled and working. There is no way to disable/enable the feature
- FIO-4826 Nonfillable PDF Conversion: Cleared components appear again, after pressing Clear form button and then clicking Create form button
- FIO-4860 Add information about Cosmos only supporting document expiry indexes on the \_ts field
- FIO-4885 When license server goes down, license server crashes for all environments. Server should go into read only mode
- FIO-4888 Data Table: Tooltip with options Edit and Delete Row doesn’t appear or vertical scroll appears when tooltip is opened for the first row, when you move the mouse from different sides to hover over the 3-dot icon
- FIO-4911 LIC | Online License | Able to perform actions on a disabled project each time after the license error is thrown
- FIO-4917 DataGrid: Event for adding/deleting rows in DataGrid in angular-formio
- FIO-4929 PDF conversion: PDF conversion isn't enabled for the PDF files uploaded after switching the form type from wizard to PDF
- FIO-4971 LIC | Offline License | Read-only mode | Able to Import / Export project JSON to / from a stage. Able to create / deploy / delete tags
- FIO-4972 Project Template not saving after selecting Project JSON using Upload a Project Template button when creating a New Project
- FIO-4980 PDF | PDF Management Page not working on Stages when LIVE Stage \(Primary Project\) PDF Server URL isn’t set inside of Portal
- FIO-4982 Datasource - When the Datagrid is populated from API and another row is added, the new row doesn't appear on edit view
- FIO-5033 Cannot download as PDF, 'x-file-token is invalid' error is displayed
- FIO-5044 Remove Dropbox for Next Portal
- FIO-5050 Stage Versions: CORS domain is hard-coded to https://form.io
- FIO-5090 Add Form Revisions transfer for stage version deployment and export/import process
- FIO-5112 Two web forms with the same Name and API path can be created If users clicks 'Create Form' button twice in a row.
- FIO-5134 Submission Revisions: Error is showing when user submits the same data of submission
- FIO-5135 Tanslations: Language dropdown: Cursor style is incorrect
- FIO-5154 Remove Auto-Save and replace with Save Settings Button on Access Tab for Stage, Forms
- FIO-5163 Teams: New team members can be added without filling email, no error messages appear.
- FIO-5185 New 'Add Stage button' showing up on Stage Settings page
- FIO-5189 Customer env. | Actions: Save Submission: 'Save Submission to' field does not register correctly
- FIO-5190 Overlay components on PDF are shifting after importing a form embed url or project import with PDF first form
- FIO-5195 When Translation is enabled, Portal is causing open HTML and is not displaying text strings
- FIO-5205 PDF | Unable to upload PDF form on Form Creation page
- FIO-5240 Teams Invitation | All team members are automatically invited when one of them accepts the invitation.
- FIO-5255 Submission Revisions page: Incorrect text of Submission Revisions section
- FIO-5258 Create Team and Team pages: Old form.io logo is shown in left sidebar
- FIO-5261 Page Title is covered with menu button when left sidebar is hidden on all pages except Main and Project pages
- FIO-5268 Actions Tab is not showing in Teams with users set to Read or Write
- FIO-5271 Different right padding in the page header on different pages and different top padding on Project page unlike the others
- FIO-5273 Account Settings: Different icons are used for Account Settings
- FIO-5301 "Search Fields" in form builder is not localized
- FIO-5334 Typo in the email action, the BBC placeholder says "Send blink copy..." when it should be "Send blind copy..."
- FIO-5337 FMG, USWDS | Day component doesn't include the 'Month' tab in the form settings.
- FIO-5361 Fix session token issues
- FIO-5363 Email action doesn't validate transport field
- FIO-5407 Remove User guiding from Portal.
- FIO-5410 UI | Stage teams panel displays title as a key 'STAGE\_TEAMS\_INFO' on the Access tab
- FIO-5433 Snyk Security | formio/formio-enterprise:8.0.0-rc.6:/src/package.json - Prototype Pollution in mongoose
- FIO-5435 Exists endpoint does not work with Submission Collections
- FIO-5438 PDF | The download process of the pdf file is not stopped after shutting down the modal window
- FIO-5445 Simple Mappings setting not showing on Save Submission Action
- FIO-5467 Remove Email Validation from next branch
- FIO-5483 Teams are not showing what projects they are assigned to on Team View page.
- FIO-5484 Left-hand navigation side bar should stick as you scroll within a project.
- FIO-5498 Stage Name is empty in the settings when the stage was connected from 8.x to 7.x
- FIO-5506 Portal Test Missing Tenant Tab on hosted environment
- FIO-5524 Email address is stored in the PDF Server URL & Form Revisions Settings
- FIO-5530 PDF: Text fields are misaligned on PDF file after an Export/Import.
- FIO-5531 Webhook | The submission call of the form returns an empty payload and therefore only an unknown error is shown to the user inside the form.
- FIO-5539 Group permissions | Allow the Group Resource field in the action to select existing resource only.
- FIO-5593 PDF Management page content is not displayed- 8.x
- FIO-5616 Revert change that caused API calls to execute on PDF output - API 8.x
- FIO-5627 Date/Time | Unable to input manually the name of the month when Date Time format is MMMM yy
- FIO-5644 FMG, FVP | Unable to access Form Manager and FVP If the project was imported via Custom Project Template.
- FIO-5645 Change default pdf-server URL to /pdf
- FIO-5653 Formio-server test suite fails in clean environments
- FIO-5665 Unable to add teams to a project when logged in with SSO
- FIO-5666 The display of data in the data table is different in the portal and FMG\+FVP
- FIO-5674 Positioning of the Data table is broken on the submission page on Firefox browser.
- FIO-5695 Remove text from the Homepage
- FIO-5696 Remove auto saving in Submission Data Permissions for 'EXISTS endpoint' checkbox because of the previously added 'Save Settings' button.
- FIO-5703 Change Submission Revisions Tab Message when feature not enabled by license.
- FIO-5720 Log Out button doesn't work properly on Login page If 2FA set up for user
- FIO-5721 The form can be created twice with the same title when the server is slow.
- FIO-5747 Password hash is displayed on the PDF download page when Submission Changelog is enabled for the form.
- FIO-5758 S&C License | Issue with retrieving encrypted data.
- FIO-5759 PDF Management page doesn't display data on hosted environment.
- FIO-5761 'Clear all changes' button and 'Cancel' button work unclear when new form is created.
- FIO-5764 License Management Page is displayed on deployed environment.
- FIO-5768 A hidden wizard page with file component inside a datagrid causing email to fail to send
- FIO-5774 User is not displayed in the Revisions Tab with Submissions Collection.
- FIO-5775 Unable to view submission from Revisions table if Submissions Collection is enabled, 404 Not found error occurs in the console.
- FIO-5784 Allow Quick Inline Embed to pull in Premium Components from a deployed environment.
- FIO-5786 Selected values are not displayed on view submission page If the select resource use Group Resource.
- FIO-5792 Text Area: ACE editor: Caret position not working correctly
- FIO-5839 Introduce ability to use admin token with copy command in formio-cli
- FIO-5860 502 Bad Gateway Error when Importing Project Template
- FIO-5880 SAML user leaving SSO team crashes the API Server
- FIO-5881 Receiving "Token expired." when performing email authentication on deployed FVP
- FIO-5885 Login Form | Remove Email and Password labels and leave placeholder only.
- FIO-5900 Remove reset password form from portal base project
- FIO-5902 TagPad component not working correctly on mobile browser
- FIO-5950 Add PDF server proxy to the API server
- FIO-5956 Accepting/leaving a team crashes the API server when using LDAP as authentication for the portal base project - 8.x
- FIO-5965 Date / Time Component | The value rendered in the component DOESN’t match the value selected by the user
- FIO-5980 Replace all requests that are sent to pdf-server to api-server /pdf-proxy endpoint
- FIO-6084 Text field component using Calendar Picker widget is not formatting the data correctly
- FIO-6119 Change loading spinner icon to standard spinner icon
- FIO-6120 Save Form / Cancel buttons showing on top of component edit modals

## Task

-  FIO-2857 Update angular starter kit
-  FIO-3907 Import project settings form into a hosted project so other Form.io team members can actively update the form
-  FIO-4422 Clear form button for nonfillable conversion
-  FIO-4683 Servers should print out version in logs at boot
-  FIO-4718 Make "Sanitize" a configurable option, except for data that is being submitted
-  FIO-4757 SEC | Remove SQL action
-  FIO-4758 SEC | fast-json-patch - version upgrade 
-  FIO-5000 Investigate our headers to see if they are assigning the FULL header object to the submission metadata
-  FIO-5067 DOC | Box Sign documentation
-  FIO-5097 DOC | Field Based Resource Access: Update the docs with the latest interface for FBRA
-  FIO-5136 Update Encryption tests to co-operate with S&C license
-  FIO-5175 Add New Logo to Portal, FormviewPro, Form Manager App
-  FIO-5201 Add S&C features and add visual indication to Portal for Features only included in Security and Compliance Package
-  FIO-5208 Move encrypted fields and submission collection for S\+C license only
-  FIO-5391 Eliminate Stage Type from License Server & Management UI
-  FIO-5493 Remove auto saving in Revisions and add 'Save settings' button instead.
-  FIO-5921 DOC | Create PDF configurable option for Radio button and Check Boxes so that the background is shown or not
-  FIO-5923 DOC | DataTable: Send the component instance attached to the Event object that is passed to the event handler
-  FIO-5924 DOC | Add option to choose Portrait or Landscape in Form Settings for PDF generation
-  FIO-5925 DOC | PDF conversion: Enable PDF auto conversion for the PDF files uploaded after switching the form type from web/wizard to PDF
-  FIO-5929 DOC | Enable ability to log in to the portal base project as an Admin
-  FIO-5932 DOC | Enable ability to turn off the sanitize method
-  FIO-5972 DOC | Update Webhook Docs
-  FIO-6096 DOC | Select Resource Documentation
-  FIO-6097 Verify behavior of update hook when upgrading a deployment from 7.x to 8.x

# December 27th, 2022 Release
## API Server Version 7.5.0

- portal@7.5.0
- formiojs@4.14.11
- formio@2.5.4
- premium@1.18.7-patch.2
- formviewpro@1.99.3
- formmanager@1.99.3
- offline@4.2.0
- uswds@2.4.8
- vpat@2.5.0

## New Feature
-  FIO-5850 Enable webhook to allow for self-signed certificates

## Bug Fixes
-  FIO-5218 Users assigned to the same groups with the same roles see different sets of submissions.
-  FIO-5298 When SSO team member has Admin Access, they do not have the ability to add new users
-  FIO-5348 Clean up database index behavior
-  FIO-5513 Resolve webhook response issues
-  FIO-5529 Include uid and uidNumber as parameters for LDAP action
-  FIO-5536 Accepting/leaving a team crashes the API server when using LDAP as authentication for the portal base project
-  FIO-5750 Email Actions | SMTP Provider | Date/Time is always displayed in UTC format in Email
-  FIO-5862 Upgrade to node 18
-  FIO-5908 PDF: Text fields are misaligned on PDF file after an Export/Import.
-  FIO-5982 Allow Quick Inline Embed to pull in Premium Components from a deployed environment.
-  FIO-5999 Date/Time Component | Date/Time picker is not displayed
-  FIO-6005 PDF | Customer running into issues with Timezone 
-  FIO-6023 Signature field does not appear after submission
-  FIO-6032 API: Date/Time components are not being saved in ISO format in MongoDB
-  FIO-6087 Investigate Webhook Failed with Error : "SELF\_SIGNED\_CERT\_IN\_CHAIN", code: "SELF\_SIGNED\_IN\_CHAIN." Fetch Error
-  FIO-6088 Incorrect dates are displayed on the view submission page for Text Fields Using Calendar Picker Widget


# December 19, 2022 Release
## PDF Server Version 3.4.0

### Included Correlated Libraries
- formio-pdf@2.5.0
- premium@1.18.7-patch.1
- formiojs@4.14.11-rc.15
- formio-viewer@2.54.0

## Bug Fixes

- FIO-4629 PDF | Mobile Chrome & Firefox | PDF form: Signature: Cannot leave a Signature
- FIO-5121 PDF | Form Module is not supporting PDF First Form validation translations
- FIO-5280 PDF | Signature component is not working on PDF form while use in mobile (touch events)
- FIO-5617 Revert change that caused API calls to execute on PDF output - PDF 3.x
- FIO-5680 Disable frame sameorigin
- FIO-5995 Date/Time Component | PDF submission is NOT downloaded when 'Display in Timezone' setting <> UTC 
- FIO-6002 PRE | Sketchpad component overlay image Absolute Positioning on Background Image causing pagebreak to not be respected - PDF 3.4.x
- FIO-6003 PDF | When there is a File component that has no layout box on a PDF first form, a gray overlay and a spinner display where file component should be on PDF download - PDF 3.4.x
- FIO-6004 PDF | DG | PDF is not showing borders in Data Grids larger than one column - PDF 3.4.x
- FIO-6005 PDF | Customer running into issues with Timezone on Production - PDF 3.4.x
- FIO-6006 Date/Time: When default value is set to moment\(\) and user does not click the input field to open a calendar widget, current date/time value in UTC time zone will be submitted which lead to the incorrect display on PDF download - PDF 3.4.x
- FIO-6023 Signature | signature field does not appear after submission

# November 3rd, 2022 Release
## API Server Version 7.4.2

### Included Correlated Libraries:
- portal@7.4.2
- formiojs@4.14.10
- formio@2.5.3
- premium@1.18.7
- formviewpro@1.99.2
- formmanager@1.99.2
- offline@4.2.0
- uswds@2.4.8
- vpat@2.5.0

### Bug Fixes
- FIO-4194 'Submit Form' button in Wizard and 'Submit' button in PDF form are enabled when no permissions have been granted to any user role. When submit, it shows that 1 offline task is added
- FIO-5418 Keys of the elements in data tables
- FIO-5430 Date/ Time not showing correct language on second Date Time component 
- FIO-5444 Webhook action not showing Response in Request Payload
- FIO-5494 No recipient to the email causes thrashing of the container
- FIO-5495 Interpolation on a submission that no longer exists causing uncaught exception
- FIO-5787 Fixes for API-driven data table filtering

# October 14th, 2022 Release
## PDF Server Version 4.0.0 

### Included Correlated Libraries
- formio-pdf@2.4.0
- premium@1.18.6
- formiojs@4.14.9
- formio-viewer@2.53.0

### Tickets Include

### New Features
- FIO-1245 PDF Auto Conversion
- FIO-5278 DataTable: Send the component instance attached to the Event object that is passed to the event handler
- FIO-5193 Submission Revisions Logs
- FIO-5082 Condensed PDF Print Mode
- FIO-4800 Add native support of Azure uploads for a PDF server
- FIO-4456 Enable Box Sign as E-Sign Provider
- FIO-4349 PDF conversion: Enable PDF auto conversion for the PDF files uploaded after switching the form type from web/wizard to PDF
- FIO-4203 Create PDF configurable option for Radio button and Check Boxes so that the background is shown or not
- FIO-4167 Ability for an event to emit once a Data Source request fails
- FIO-3455 Non-fillable pdf conversion

### Bug Fixes

- FIO-5733 Include helmet library for PDF 4.x for header configurations for HTML downloads (HTML embed)
- FIO-5676 PDF First forms not rendering
- FIO-5659 API Server is not including the x-license-key header for PDF communication
- FIO-5634 Ensure PDF is not loading timezones when generating PDFs
- FIO-5624 Revisions | Original PDF still shows if replaced with new PDF after Publishing or Saving as Draft
- FIO-5610 Revert change that caused API calls to execute on PDF output - PDF 4.x
- FIO-5603 Investigate certain PDF First Forms not producing output file
- FIO-5602 Fix unlink to not crash server
- FIO-5583 Hotfix for middleware not working
- FIO-5581 Different MD5 implementations producing different result if input contains language specific characters
- FIO-5563 SEC | Update pdf-libs dependency: poppler
- FIO-5556 SEC | formio/pdf-server:4.0.0-rc.29:/src/package.json - Sandbox Bypass in vm2
- FIO-5523 Add logging to assist with resolving customer issues
- FIO-5512 Fix offline license on PDF Server
- FIO-5473 Digit Keys issue for non-fillable conversion
- FIO-5462 Refactoring check PDF basic middleware
- FIO-5436 Signature component added short and cant sign
- FIO-5420 Fix error for obfuscated code
- FIO-5418 Keys of the elements in data tables
- FIO-5417 When multiple calendars present in form, clicking on multiple calendar icon, multiple windows opened.
- FIO-5386 Columns not being respected when Portrait Setting set for PDF page layout in settings.
- FIO-5385 Mount Viewer Fonts at PDF Server Route
- FIO-5371 Settings not properly saving any configuration
- FIO-5322 PDF files do not load and the error appears
- FIO-5305 Edit Grid Settings | PDF download shows extra-large divider lines and takes two paragraphs.
- FIO-5300 ENOENT: no such file or directory, unlink pdf error when sending multiple pdf generation requests
- FIO-5266 Calendar control is not reflecting the localization changes
- FIO-5234 Identify any instances where we are requiring communication to cdn.form.io to load libraries.
- FIO-5156 PDF Auto-Conversion - Resolve empty API keys on fields from fillable forms
- FIO-5149 Custom component not showing the right data structure
- FIO-5107 Fix button loader icon removal at an unexpected event
- FIO-5036 Sketchpad: Sketchpad preview drawing does not display on submission open / edit
- FIO-5002 CVE - formio/pdf-server:4.0.0-rc.10:/usr/src/pdf-libs/package.json - User Interface (UI) Misrepresentation of Critical Information in swagger-ui-dist
- FIO-4989 Non-fillable PDF Conversion | Form Fields Recognition: Slow loading of forms often resulting in 504 error
- FIO-4988 Non-fillable PDF Conversion | Form Fields Recognition: Components remain on the form after pressing Clear form and Clear Fields buttons. After creating and saving the form, components disappear
- FIO-4928 PDF conversion isn't enabled for the PDF files uploaded after switching the form type from wizard to PDF
- FIO-4920 Table: The signature in layouts is cut off on PDF download and view tab
- FIO-4908 Non-fillable PDF conversion: Non-fillable conversion turns off after uploading big non-fillable form
- FIO-4897 PDF server is launching multiple excessive chrome processes that increase cpu utilization
- FIO-4896 Non-fillable PDF Conversion: There is infinite loader after pressing Clear form button
- FIO-4886 Nested Form: Calculated Value does not display in a component inside the nested form on parent form load
- FIO-4880 API, PDF | Regression | There is no access to any project and 400 error is showing. 502 error on PDF server
- FIO-4864 PDF | Investigate slow PDF generation
- FIO-4851 FJS | Select (Resource): When 'Multiple Values' setting is enabled, all the selected values display as the last one selected when viewing a submission
- FIO-4764 FJS, PDF | Regression | Date/Time & Textfield Calendar: When Time is disabled, the date in the PDF download will be one day off the selected date
- FIO-4709 PDF | Regression | Non-fillable PDF conversion: Empty PDF files are not uploading
- FIO-4705 API, PDF | GET {{projectURL}}/current request returns with 400 Bad Request and an error in a console
- FIO-4704 FJS, CAD | VUE - Form builder: When using component search, the custom group does not expand any longer
- FIO-4684 PDF | Regression | PDF redraws when making an edit to a PDF form
- FIO-4681 PDF | Submission Revisions: Changelog: Long values not split by spaces render in one line and go off the edge of the PDF file on PDF download
- FIO-4669 PDF | Fillable PDF Conversion: Components have the same Property Name (API key) and API key isn't incremented when components have the same labels and numbers and underscores at the end
- FIO-4666 PDF | PDF Conversion: PDF forms are not uploaded after some time
- FIO-4652 APP | Nonfillable PDF Conversion: Cleared components appear again, after pressing Clear form button and then clicking Create form button
- FIO-4651 PDF | PDF Conversion: Clear form button appears in Usual PDFs, in PDFs when Non-fillable conversion is turned off
- FIO-4629 FJS, PDF | Regression | Mobile Chrome & Firefox | PDF form: Signature: Cannot leave a Signature
- FIO-4583 PRE | Regression | Data Table: Hidden controls inside layout controls display in the Data Table grid
- FIO-4575 PDF | Non-fillable PDF conversion: Text Data in the Table rows is converted into Text Field components
- FIO-4564 PDF| Fillable PDF Conversion: Components with the same Label in lower, upper, capitalized, title, sentence case, have the same Property Name (API key) and API key isn't incremented
- FIO-4562 PDF | File: When selected file does not pass file type or file size validation, there is no possibility to remove that file and select another one
- FIO-4549 PDF | Fllable PDF conversion: PDF Chekbox and Radio Export Values are not exported from pdf-to-json and don't fill Radio Value of form.io Checkboxes
- FIO-4545 PDF | Fllable PDF conversion: PDF Checkboxes which behave as Radio are converted as Checkboxes with Input Type Checkbox. Should be converted with Input Type Radio
- FIO-4526 APP | Replaces all instances of 'https://unpkg.com/formiojs@latest' with 'https://cdn.form.io/formiojs/formio.embed.min.js'
- FIO-4521 PDF | Fllable PDF conversion: Tooltip of component in fillable pdf is written as Label of component on portal after conversion
- FIO-4512 PDF | Nonfillable PDF conversion: Nonfillable conversion turns off after some time after the start of environment
- FIO-4503 PDF | Fllable PDF conversion: PDF converter fails to convert  form with combo box or select box (select component)
- FIO-4416 PDF | Regression | When uploading a PDF file that contains only text without graphics, the renderer crashes
- FIO-4395 FJS | Typo in Tool Tip for Default Value for All Components
- FIO-4392 FJS | Help links are pointing to incorrect locations
- FIO-4287 PDF | Non-fillable PDF conversion: Layout box size is in % format, which leads to the wrong size of the boxes on the rendered form
- FIO-4283 PDF | Fllable PDF conversion: PDF button is converted as a form.io button. Should be omitted in the transferring process
- FIO-4282 PDF | Non-fillable PDF conversion: Uploading an empty PDF file, I get a PDF form with Text Fields all over the document
- FIO-4225 NFP, FJS | Date/Time: Last selected/entered value from multiple values is highlighted as error value, when Date/Time is required
- FIO-4218 FJS | Error message isn't showing in modal window
- FIO-4194 FVP | 'Submit Form' button in Wizard and 'Submit' button in PDF form are enabled when no permissions have been granted to any user role. When submit, it shows that 1 offline task is added
- FIO-4153 FJS | Text Field Calendar widget locale setting not saving
- FIO-3763 When projects do not have anonymous access turned on and we are still able to hit a form with a GET request as an anonymous user.
- FIO-3435 API, FJS | Form definition download taking a long time to call
- FIO-3343 FJS | Form builder: HTML Element, Content, Hidden, Data Source components have no bottom margins
- FIO-3160 ACC, FJS | Select Boxes: Select Boxes options are announced as 'radio button'
- FIO-3055 NFP | IE11 | Next portal does not load, causing several syntax errors in a console
- FIO-3000 ACC, FJS | Web form: Submit button is referenced by [aria-labelledby] with [id=l-eiqbap-submit] not found
- FIO-2987 ACC, FJS | Panel: When clicking on the collapsible panel in the Modal window, the Modal window closes
- FIO-2985 ACC, FJS | File: When no file formats are specified, quite a long message displays in the component and announced
- FIO-2984 ACC | File: Change the 'Use Camera,' link to 'use camera'
- FIO-2981 ACC, FJS | Firefox | File: Video player is in a tabulation order
- FIO-2979 ACC, FJS | File: Clicking on browse link or dragging and dropping files into the drag&drop area, explorer does not open / file is not uploaded causing 'Uncaught TypeError: uploadingProcess is null' error in a console
- FIO-2977 ACC, FJS | File: Browse link has no accessible name that contains File label, description and information about allowed file types
- FIO-2971 FJS | Table: Tooltip text of 'Clone Row Components' option isn't fully visible in Component Settings
- FIO-2963 ACC, FJS | Bootstrap | Modal View: Change focus order of Cancel and Save buttons
- FIO-2962 ACC, FJS | Bootstrap | Well: No bottom margin
- FIO-2917 ACC, FJS | Radio: No radio label, radio description, radio required announcements
- FIO-2890 ACC, FJS | Bootsrtap | Modal dialog window: Change buttons order
- FIO-2870 ACC, FJS | Bootstrap | Component Settings | Focus outline of Save, Cancel, Remove buttons is not fully visible in Components Settings window of Content component, when user focuses with Tab key
- FIO-2794 ACC, FJS | Enter Data | Modal Edit: There is no announcement 'Modal window has been opened' when some components modal windows have opened
- FIO-2791 ACC, FJS | Bootsrtap | Date/Time: The input field does not take the entire page width
- FIO-2782 ACC | Bootsrtap | Change the initial focus element to the Close button in the Modal window on its opening
- FIO-2779 ACC, FJS | Bootsrtap | Change OnHover cursor style to the Hand pointer for the errors in the Error list
- FIO-2777 ACC, FJS | Bootstrap | Insufficient color contrast of the components errors
- FIO-2773 ACC, FJS | Tooltips of component action buttons are too far from the buttons
- FIO-2770 ACC, FJS | Bootstrap | Modal and Confirmation windows | Text overlaps the Close buttons in both windows
- FIO-2769 ACC, FJS | Bootstrap | Modal and Confirmation windows | Contrast issues
- FIO-2768 ACC, FJS | Bootstrap | Pressing Wizard breadcrumbs buttons by Enter key, the page does not open
- FIO-2757 ACC, FJS | 'Press Ctrl + Alt + X to go back to the error list.' announcement is missing when focusing on a component with an error when form validation is not met
- FIO-2756 ACC, FJS | Error list: 'Press Ctrl + Alt + X to go back to the error list.' tooltip does not display
- FIO-2755 ACC | Modal and Confirmation windows issues
- FIO-2734 ACC | Enter Data/Component Settings | Tooltips not focusing with keyboard
- FIO-2729 ACC | Enter Data/Component Settings | Panel: Collapsible Panel component doesn't collapse and expand
- FIO-2541 ACC | Enter Data | Character counter covers border of Checkbox with tile
- FIO-2540 ACC | Enter Data | The Field Set, Columns, Well components resize when they are below the component with character counter.
- FIO-1946 ACC, FJS | Bootstrap ui framework accessibility support - Bootstrap templates
- FIO-268 FJS - 1294 Text Area - When Text area is empty but has a default row greater than 1 , text row shows as one line when submission is viewed
- FIO-3456 Pdf-autoconversion branches integration
- FIO-5722 Remove submission deep cloning to increase pdf generation speed
- FIO-5253 Change pdf loading spinner color to green
- FIO-5127 Rename pdf-libs endpoints
- FIO-5118 DOC | PDF Conversion Documentation
- FIO-5069 Fetch tab for Data Table Component to enable API driven data tables
- FIO-4949 Disable auto fill in browser
- FIO-4901 PDF Conversion: Remove timeout when recognizing formfields
- FIO-4755 Merge pdf-converter into pdf-server
- FIO-4663  Ensure upload/download endpoints are proxied through the server, and that it is protected via x-license-key
- FIO-4530 PDF | PDF Nonfillable Conversion: Add environment variable for disabling nonfillable conversion
- FIO-4409 PDF | Need to split server licensing for and PDF Plus
- FIO-4336 APP, PDF | Clear form button for nonfillable conversion
- FIO-4267 Update /pdf endpoint on formio-server to return used version of pdf-autoconversion services
- FIO-3998 Auto adjusting rows count in textareas
- FIO-3997 Ordering fields when displaying PDF form as Web form
- FIO-3939 FJS | Full Native Solution  to translate Content and HTML component
- FIO-2648 ACC, FJS | Bootstrap ui framework accessibility support - VPAT and Bootstrap compatibility

# October 7th, 2022 Release
## API Server Version 7.4.1

### Included Correlated Libraries:
- portal@7.4.1
- formviewpro@1.99.1
- formmanager@1.99.1
- formiojs@4.14.9
- premium@1.18.6
- offline@4.2.0
- formio@2.5.2
- uswds@2.4.8-rc.1
- vpat@2.4.3-rc.1

### Tickets Included

### New Features
 - FIO-5237 Data Table | Ability to organize Data Table in Ascending and Descending order ignoring capitalizations
 - FIO-5161 Add Events to Data Table for Added / Edited / Deleted
 - FIO-4943 Content: Add a 'CKEditor Content' placeholder when the component is empty, so that it display a proper layout
 - FIO-4814 Implement a way for form.io to use session storage over local storage for tokens

### Bug Fixes

 - FIO-5719 Unable to access project as member of team \(Project Read \+ Stage Read\). Error accessing project: "Cannot read properties of undefined \(reading 'appOrigin'\)"
 - FIO-5718 Unable to access stage as member of project \(Project Access \+ Stage Read\). Error accessing project: "Cannot read properties of undefined \(reading 'appOrigin'\)"
 - FIO-5682 Tenant Page not loading. Showing Unauthorized error.
 - FIO-5680 Disable frame sameorigin
 - FIO-5643 When new PDF form is created on Form Manager all added components are not saved.
 - FIO-5636 Unable to access project as member of project. Error accessing project: "Cannot read properties of undefined \(reading 'appOrigin'\)"
 - FIO-5605 UI issues - 7.x
 - FIO-5599 Error accessing project: Project limit reached \(remote.form.io, remote-dev.form.io, latest.test-form.io, etc.\)
 - FIO-5591 Delete 'Disable sorting and filtering in Data Table' checkbox from Data Table settings \(Display Tab\).
 - FIO-5580 Unable to connect remote.form.io \(7.4.1-rc.10\) to remote-dev.form.io \(8.0.0-rc.9\)
 - FIO-5579 Components are not saving on inital save on PDF
 - FIO-5578 Components are not saving on inital save on Wizard
 - FIO-5572 Save Submission is not showing a mapping option when a resource is selected.
 - FIO-5568 Stage Versions: CORS domain is hard-coded to https://form.io
 - FIO-5564 Loader is not showing for API-driven dataTables
 - FIO-5544 Form components should stick when building forms
 - FIO-5517 Revert advanced header changes
 - FIO-5478 Unable to create Wizard and PDF forms.
 - FIO-5457 PDF Management page content is not displayed
 - FIO-5455 DateTime: Disabling dates with custom function doesn't work when referring data
 - FIO-5436 Signature component added short and cant sign
 - FIO-5431 Losing text area data after checking source view and going back to the text view.
 - FIO-5418 Keys of the elements in data tables
 - FIO-5417 When multiple calendars present in form, clicking on multiple calendar icon, multiple windows opened.
 - FIO-5401 Number| Number Component is stripping out the scientific notation of the number
 - FIO-5400 Remove Email Validation from API 7.4.1
 - FIO-5399 Fix form.io flatpickr cdn to use https://cdn.test-form.io for non production builds.
 - FIO-5381 Formview pro application exceeds size
 - FIO-5379 formio/formio-enterprise:7.4.1-rc.5:/src/package.json - Denial of Service \(DoS\) in dicer
 - FIO-5378 formio-enterprise:7.4.1-rc.10:/src/package.json - Regular Expression Denial of Service \(ReDoS\) in moment
 - FIO-5377 Unable to connect to On-Premise Environment when Creating New Stage, Using 7x server to connect to 7x/8x server.
 - FIO-5357 PDF download not working on specific form with self signed certificates
 - FIO-5346 Add the correct header type to this file when it is returned.
 - FIO-5296 Double declaration of variables in Data Table
 - FIO-5266 Calendar control is not reflecting the localization changes
 - FIO-5234 Identify any instances where we are requiring communication to cdn.form.io to load libraries.
 - FIO-5199 Provide user information in POST request to show who submitted any given submission
 - FIO-5178 Emit an event from the HTML component when it is clicked in Angular App
 - FIO-5172 Required validation is being triggered on form load using FMG or FVP with Angular 5.2.3-rc.3
 - FIO-5168 Change with Signature Pad import is breaking other customer libraries that import the formiojs renderer.
 - FIO-5157 Change text for Submission Revisions to be available  only in Security & Compliance Level Subscription
 - FIO-5155 Data Grid - Components Form | Nested form component values are not displayed on PDF download
 - FIO-5152 Edit Grid Settings | PDF download shows extra-large divider lines and takes two paragraphs.
 - FIO-5149 Custom component not showing the right data structure
 - FIO-5130 formio/formio-enterprise:7.4.0-rc.24:/src/package.json - Improper Verification of Cryptographic Signature in node-forge
 - FIO-5057 Data Table: When there is Select inside Columns inside DT, it fails to render when adding new DT rows
 - FIO-4983 Data Table: When the components inside DT have 'Property Name' with dots, the sorting / filtering features don't work throwing errors in a console
 - FIO-4892 Submission Revisions: Submission Change Log with initial submission is empty, when it is opened the second and next times
 - FIO-4878 Button: Save in State: SiS does not change when editing submission in FVP
 - FIO-4820 Radio component in form builder resets custom API Property Name
 - FIO-4764 Date/Time & Textfield Calendar: When Time is disabled, the date in the PDF download will be one day off the selected date
 - FIO-4736 License management: Projects tab: Stages display depends on the page user has come from
 - FIO-4629 Mobile Chrome & Firefox | PDF form: Signature: Cannot leave a Signature
 - FIO-4603 File: When selected file does not pass file type or file size validation, there is no possibility to upload another one
 - FIO-4153 Text Field Calendar widget locale setting not saving
 - FIO-3020 Data table: When the Dynamic Wizard, Edit Grid, Data Grid, Container, Tree components have 'Table View' setting disabled, and there are components inside them having it enabled, they will display in the Data table
 - FIO-2971 Table: Tooltip text of 'Clone Row Components' option isn't fully visible in Component Settings
 - FIO-987  Allow Refresh of application while offline
 - FIO-5406 Performance Improvements 7.4.x
 - FIO-5221 Implement in-memory cache for the Project JSON
 - FIO-5120 DOC | API Driven DataTable Documentation
 - FIO-5119 DOC | Localization of the Form.io Developer Portal Documentation
 - FIO-5589 DOC | Implement a way for form.io to use session storage over local storage for tokens

# August 10th, 2022 Release
## API Server Version 7.2.7

### Included Correlated Libraries:
- portal@7.2.16
- formviewpro@1.97.16
- formmanager@1.97.16
- formiojs@4.13.13
- premium@1.17.2-rc.1
- offline@3.2.0
- formio@2.3.3
- uswds@2.4.6
- vpat@2.4.2

### Tickets Included

- FIO-5221 API | Implement in-memory cache for the Project JSON
- FIO-5286 BUI | API 7.2.7


# July 14th, 2022 Release
## API Server Version 7.1.14

### Included Correlated Libraries:
- portal@7.2.15
- formviewpro@1.97.15
- formmanager@1.97.15
- formiojs@4.13.13
- premium@1.17.0
- offline@3.2.0
- formio@2.2.7
- uswds@2.4.6
- vpat@2.4.2

### Tickets Included

- FIO-4405 FJS | When hidden radio has the Storage Type as String, we are receiving empty validation error
- FIO-4743 FJS | Regression | Actions: Action Conditionals: 'Trigger this action only if field' select: All form components display as 'undefined'
- FIO-4763 FJS | Regression | Select in Dynamic Wizard/ Data/Edit Grid/TagPad: Cannot make a submission. Get 'Could not connect to API server (key editGrid[0].select must not contain '.')' error
- FIO-5132 7.1.14 Build - Customer specific Request
- FIO-5218 Users assigned to the same groups with the same roles see different sets of submissions.
- FIO-5259 API | Updating Package JSON for Formio/formio and FormioServer
- FIO-5289 FJS | Select Resource not saving Multiple Value data correctly

### New Feature

- FIO-5117 Revert PR #4049 which caused empty number fields to be an empty string rather than null


# June 14th, 2022 Release
## API Server Version 7.4.0
## PDF Server Version 3.3.9

### Included Correlated Libraries:
 - portal@7.4.0
 - formviewpro@1.99.0
 - formmanager@1.99.0
 - formiojs@4.14.8
 - premium@1.18.4
 - offline@4.2.0 
 - formio@2.5.0
 - uswds@2.4.6
 - vpat@2.4.2

### Tickets Included

### API

- FIO-4673	API | Submission Revisions: The field paths are only showing the value of the last field not the entire file path on PDF download				
- FIO-4707	API | When form revisions are enbaled	 the form URL appends an invalid revision endpoint			
- FIO-4738	API | Original Form Revisions: Swapped arguments in a function. Appended '&' as a query separator in URL				
- FIO-4783	API | Submission Revisions: Submission Revision Change Log doesn't contain info about Select Boxes changes. There is no Delta Symbol next to Select Boxes that is signifying changes				
- FIO-4785	API | Submission Revisions: When changes are made in 2 or more components	 previous revisions aren't shown in Submission Revision Change Log			
- FIO-4811	API | Submission Revisions: Submissions created before the feature is enabled	 do not display in the table after enabling the Submission Revisions			
- FIO-4837	API | Submission Revisions | Nested Form: The form that contains Nested Form has no revisions	  empty Submission Change Log and doesn't have Delta Symbol that is signifying changes in any form components			
- FIO-4849	API | Submission Revisions | Tagpad: After editing submitted Tagpad	 no new changes are shown in Submission Change Log. Tagpad doesn't have Delta Symbol that is signifying changes in Tagpad component			
- FIO-4923	API | Email Action issues on Remote environments with Email Override enabeld				
- FIO-4941	API | Resolve node-saml CVE with dependency version bump				
- FIO-4985	API | Project Level Access - Read All Anonymous permission is opening up READ Access for form submissions				
- FIO-5011	API | Language Resource needs to be included in the Portal Base project				
- FIO-5021	API | Translations: Language resource: Language and Language key components are non-required				
- FIO-5052	API | "Regression | Unauthorized errors as ""Language"" resource doesn't have the correct permissions to view all submissions."				
- FIO-5075	API | Submission Revisions: Submitted data of Select with Resource Data Source Type isn't showing on Submission Change Log section				
- FIO-5077	API | Submission Revisions: Select with URL	 Raw JSON Data Source Type has several Field Paths Submission Changelog section			
- FIO-5095	API | Regression | Submission Revisions: Submission Revision Change Log doesn't contain info about changes in Date/Time with checked Multiple Values. There is no Delta Symbol next to Date/Time that is signifying changes				

### APP

- FIO-4853	APP | Project Template not saving after selecting Project JSON using Upload a Project Template button when creating a New Project				
- FIO-4950	APP | Customer env. | Actions: Save Submission: 'Save Submission to' field does not register correctly				
- FIO-4952	APP | Regression | Connect to On-Premise Environment Form not loading				
- FIO-4958	APP | Regression | Walkthrough page: Almost all the elements display as {{ ... | translate }}				
- FIO-4959	APP | Regression | Project Stage: The 'Delete Project' button and the section it is in are missing				
- FIO-4961	APP | Regression | Submission Revisions: There is no access for enabling Submission Revisions				
- FIO-4967	APP | New 'Add Stage button' showing up on Stage Settings page				
- FIO-4987	APP | Regression | Some pages don't open from Welcome banner and Walkthrough page. Errors are showing				
- FIO-4993	APP | Regression | Walkthrough page: 'Create an Admin User account!' text on the Welcome page instead of 'Welcome to Your New Project!' text		- FIO-5009	APP | Regression | Stage Settings: On-Premise Environment: Typo in a 'Continue' button				
- FIO-5013	APP | Indication of what language is currently set in the Language Dropdown for Portal				
- FIO-5015	APP | Placeholder text not translating				
- FIO-5016	APP | List of Translations that did not work				
- FIO-5020	APP | Tanslations: Language dropdown: Cursor style is incorrect				
- FIO-5051	APP | Regression | Teams: Typo in a 'New Team' header				
- FIO-5078	APP | Unable to reclick “select/unselect all” on Export Template after initial click				
- FIO-5103	APP | Submission Revisions: Error is showing when user submits the same data of submission				
- FIO-5111	APP | Regression | Teams: Member shows as Admin on a View Team page				
- FIO-5138	APP | Regression | Create a new project: All elements display as {{... | translate}}	 a project can't be created.			
- FIO-5140	APP | PDF | Unable to upload PDF form on Form Creation page				
- FIO-5141	APP | Translations: Current language is not saved for app after the page is refreshed.				
- FIO-5145	APP | When Translation is enabled	 Portal is causing open HTML and is not displaying text strings			
- FIO-5146	APP | Regression | 'Save form' button is changed when the user scroll down the edit form page.				
- FIO-5169	APP | Regression | Translations : Text is displayed with underscores on Login page				

### FJS

- FIO-2505	FJS | Regression | Data Grid: Signatures on different rows are not consistent in size				
- FIO-2645	FJS | Container | Allow Container required messages in AlertBox to redirect to Container.				
- FIO-3973	FJS | Edit Grid: Wrong error displays for the 1st component in EG. 'Invalid row. Please correct it or delete.' error displays even when all the errors are fixed in EG				
- FIO-4037	FJS | Values should not modify once the component has been saved.				
- FIO-4362	FJS | Regression | Checkbox: Radio input type: Checked radio buttons display as unchecked on Edit and View Submission pages				
- FIO-4398	FJS | Data Grid | When Text Field Input Format setting is set to HTML	 the data is not displayed in the Text Field			
- FIO-4558	FJS | Regression | HTML: 	code> tag displays as 'field is not defined' in a preview and a rendered PDF form			
- FIO-4559	FJS | Textbox/Textarea with show/hide condition in datagrid cause infinite loop on a particular form				
- FIO-4567	FJS | Regression | Signature is disabled on form load				
- FIO-4571	FJS | Regression | Form builder: Component settings: Tooltips don't show up on mouse hover				
- FIO-4573	FJS | Regression | Examples page: Submission Hosting page: Form does not load. Get 400 Bad Request Invalid alias error				
- FIO-4579	FJS | Regression | Select Resource - Data is not returned when item template is set but value property field is empty in Select settings				
- FIO-4615	FJS | Regression | Date/Time	 Text Field - Calendar widget: Value is not consistent in submission and PDF download for different timezone cases			
- FIO-4628	FJS | File: Multiple Upload: When files are selected one by one	 they replace each other in the upload process			
- FIO-4631	FJS | Regression | Tooltip box has small width which makes long hints display vertically				
- FIO-4632	FJS | Regression | Date/Time: When date format is changed to dd-MM-yyyy and Time input is disabled	 the wrong date displays on View Submission	 PDF download and Kendo UI grid		
- FIO-4641	FJS | Upgrade Signature Pad to the latest version				
- FIO-4690	FJS | Regression | Customer nested form crashes server when submitted				
- FIO-4691	FJS | Regression | Calculated Values: When Allow Manual Override of Calculated Value setting is enabled	 the value does not get recalculated		- FIO-4698	FJS | Regression | Tags are not applied to the text in tooltips and render with the text				
- FIO-4743	FJS | Regression | Actions: Action Conditionals: 'Trigger this action only if field' select: All form components display as 'undefined'				
- FIO-4750	FJS | Custom buttons do not work on 1st click	but the 2nd			
- FIO-4788	FJS | Advanced Conditional based on a numeric value does not work correctly				
- FIO-4799	FJS | Select: Property Value is not set by default and causes the values to show as ‘undefined’ in dropdown				
- FIO-4815	FJS | Tabs: Cannot make a submission with a Tabs component. Get 400 Bad Request error				
- FIO-4858	FJS | When open a form that has a Select Resource	the request is sent that contains a query parameter 'limit=4294967295'			
- FIO-4861	FJS | Submission Revisions: After Restoring old Revision	 new Revision has Note of old revision	 since nothing has been entered into Note field of new Revision		
- FIO-4942	FJS | Regression | Email submission: Custom PDF File Name is not respected and defaulted to {{ form.name }}-{{ submission._id }}				
- FIO-4947	FJS | Regression | API Driven Data Table: The up and down arrows do not display correctly when the 'Sort Ascending' and the 'Sort Descending' filters are applied				
- FIO-4953	FJS | Regression | Signature is deleted when saving and validation is not passing after validation has passed or saving after submission and is not saved on the modal view				
- FIO-4970	FJS | Oversize limit query size causes existing resource fields to not display correctly in the FormBuilder (existing resource fields)				
- FIO-4976	FJS | Resource Select data not showing on View or PDF download				
- FIO-4995	FJS | Regression | Examples page: Signature on example form is disabled				
- FIO-4997	FJS | Regression | Cannot make a submission with a Tabs component inside the Nested component				
- FIO-5003	FJS | Radio: Radio with 'false' value does not display in different templates				
- FIO-5006	FJS | Regression | API Driven Data Table: Filtering in DT crashes the server where the data is fetched from				
- FIO-5053	FJS | URL Select data with HTML 5 Widget Type not showing on View or PDF download				
- FIO-5122	FJS | Select: Templates for Select component no longer using full interpolation				
- FIO-5142	FJS | Regression | Resource Select data not showing on View Submission page and PDF download when Select component has checked Lazy Load Data				
### FVP

- FIO-4342	FVP | Regression | Offline mode: No submissions display in Submissions UI grid in offline mode				
- FIO-4925	FVP | Wizard | Submission values display only for several pages. The rest of the form is empty when Everyone role is set for Create/Read				

### PDF

- FIO-4416	PDF | Regression | When uploading a PDF file that contains only text without graphics	 the renderer crashes			
- FIO-4635	PDF | PDF form with hidden select component - download is not working. 502 Bad Gateway is shown				
- FIO-4781	PDF | When 'Attach Submission PDF' setting is enabled	 emails are not sent			
- FIO-4897	PDF | PDF server is launching multiple excessive chrome processes that increase cpu utilization				
- FIO-4948	PDF | Regression | Unable to upload PDFs: Error connect ECONNREFUSED 127.0.0.1:8080.				
- FIO-5008	PDF | Submission Revisions: In PDF Changelog Delta symbol is shown only for the last change that was made				
- FIO-5170	PDF | Select: Submitted data of Select component with Resource and URL Data Source Types shows as ‘undefined’ in PDF download				
- FIO-5071	PRE | Regression | Sketchpad: When Sketchpad has Image Image Type	 Sketchpad preview drawing does not display on submission open / edit			


### Other Tickets

- FIO-4353	API,LIC | Offline License fails to validate when upgrading from existing 7.x license							
- FIO-4654	API,PDF | Enable the upload of images to our ECR registry as part of the CircleCI process.				
- FIO-4681	API,PDF | Submission Revisions: Changelog: Long values not split by spaces render in one line and go off the edge of the PDF file on PDF download				
- FIO-4772	API,LIC | Offline License | Issue with On-Premise on API 7.3.1 using Offline License			
- FIO-4797	APP,PDF | Submission Revisions: Address isn't showing in Submission Change Log and doesn't have Delta Symbol that is signifying changes. In some cases Field Path of Address is incorrect in Submission Revision Change Log				
- FIO-4843	API,APP | Submissions Revisions: Investigate Submission Revisions with Save as Draft			
- FIO-4880	API,PDF | Regression | There is no access to any project and 400 error is showing. 502 error on PDF server				
- FIO-4890	API,APP,LIC | Offline License | Read-only mode | Able to Import / Export project JSON to / from a stage. Able to create / deploy / delete tags	- FIO-4899	API,LIC | Offline License | When project limit is reached	 I cannot create new stages / tenants		
- FIO-4905	API,LIC | Offline License | In a read-only mode I can create/update form/resource actions			
- FIO-4996	APP,PDF | Regression | Submission Revisions: Submission Revision Change Log isn't showing in PDF download after enabling it				
- FIO-5025	API,APP | Translations: When there is an HTML tag inside the portal translation tag	 the last is split into smaller tags to maintain the layout		
- FIO-5076	API,FVP | After editing forms with nested form	I am unable to submit form. 404 Error		
- FIO-5081	API,LIC | Regression | Offline License: When in a Restricted mode	 the form.io does not work correctly throwing the 'License not found' errors		
- FIO-5176	API,LIC | Regression | Offline License | In a read-only mode I can't update projects/project stages/tenants			
- FIO-4595	FJS,PDF | Regression | Signature: Edit Submission page: Signature value does not clear
- FIO-4787	FJS,PDF | Submission Revisions: Submission Revision Change Log doesn't contain info about changes in components with checked Multiple Values. There is no Delta Symbol next to components that is signifying changes				
- FIO-4792	FJS,PDF | Submission Revisions: Submission Revision Change Log shows a Delta Symbol next to every field if a form is filled out the first time. And shows a Delta Symbol next to every field when an empty form is submitted the first time				
- FIO-4798	FJS,PDF | Submission Revisions: The wrong Date/Time format displays on Submission Change Log section				
- FIO-4805	FJS,PDF | Submission Revisions: In Currency component Currency	 Thousands Separators	 Decimal Places aren't showing on Submission Change Log section		
- FIO-4808	FJS,PDF | Submission Revisions: Survey component isn't showing in Submission Change Log and doesn't have Delta Symbol that is signifying changes				
- FIO-4830	FJS,PDF | Submission Revisions | Data Grid	 Edit Grid: After deleting Row Submission Change Log section is empty and component doesn't have Delta Symbol that is signifying changes			
- FIO-4832	FJS,PDF | Submission Revisions | Radio	 Select	 Select Boxes: Submission Change Log section shows the Value data instead of the Label data of option		
- FIO-4836	FJS,PDF | Submission Revisions: File component isn't showing in Submission Change Log and doesn't have Delta Symbol that is signifying changes				
- FIO-4838	FJS,PDF | Submission Revisions: Sketchpad component isn't showing in Submission Change Log and doesn't have Delta Symbol that is signifying changes				
- FIO-4842	FJS,PDF | Submission Revisions: The wrong Time format displays on Submission Change Log section				
- FIO-4846	FJS,PDF | Submission Revisions | Nested Form: When Parent and Child form contain the same components	 component in Child Form has name of component from Parent form. The same components are shown twice in Submission Change Log			
- FIO-4850	FJS,PDF | Submission Revisions | Data Table: Revision that contains info about deleting row isn't shown in Submission Change Log section				
- FIO-4854	FJS,PDF | Submission Revisions: In Wizard forms Revisions aren't showing in Submission Revision Change Log and there is no Delta symbol next to changed components				
- FIO-4891	FJS,PDF | Submission Revisions | Survey	 Address: Some long path	 not label	 is shown in Field Path column for Survey	 Address components in Submission Change Log section
- FIO-4969	FJS,PRE | Regression | Data Table: DT fails to render correctly				
- FIO-5139	FJS,API | Validation isn't working for Select component with URL	 Raw JSON Data Source Types. And the form can be submitted without these required fields		
- FIO-4065	PDF,APP | Overlay components on PDF are shifting after importing a form embed url or project import with PDF first form			
- FIO-4364	PDF,FJS | Select: When default value is set	 it will display on the View Submission page as well as PDF download regardless of the value that was actually selected		


### New Feature

- FIO-2815  FMG | Adding Email action to FMG and edit actions on an existing form inside of form manager
- FIO-3967  APP, PDF, FJS | Create PDF configurable option for Radio button and Check Boxes so that the background is shown or not
- FIO-4359  API, APP, FJS | Submission Revisions Logs
- FIO-4397  APP | Enable Translation of Portal Application
- FIO-5128  Allow support for Data Table row-based events for angular formio component


# May 25th, 2022 Release
## API Server Version 7.3.3
## PDF Server Version 3.3.8

### Included Correlated Libraries:
 - portal@7.3.3
 - formviewpro@1.98.6
 - formmanager@1.98.6
 - formiojs@4.14.7-patch.4
 - premium@1.18.3
 - offline@4.2.0 
 - formio@2.4.2
 - uswds@2.4.6
 - vpat@2.4.2

### Tickets Included

- FIO-4628	FJS | File: Multiple Upload: When files are selected one by one, they replace each other in the upload process
- FIO-4772	API | Offline License | Issue with On-Premise on API 7.3.1 using Offline License
- FIO-4897	PDF | PDF server is launching multiple excessive chrome processes that increase cpu utilization
- FIO-4942	FJS | Regression | Email submission: Custom PDF File Name is not respected and defaulted to {{ form.name }}-{{ submission._id }}
- FIO-4953	FJS | Regression | Signature is deleted when saving and validation is not passing after validation has passed or saving after submission and is not saved on the modal view
- FIO-4985	API | Project Level Access - Read All Anonymous permission is opening up READ Access for form submissions
- FIO-4995	FJS | Regression | Examples page: Signature on example form is disabled
- FIO-5081	API, LIC | Regression | Offline License: When in a Restricted mode, the form.io does not work correcty throwing the 'License not found' errors




# May 25th, 2022 Release
## API Server Version 7.2.6
## PDF Server Version 3.3.8

### Included Correlated Libraries:
 - portal@7.2.14
 - formviewpro@1.97.14
 - formmanager@1.97.14
 - formiojs@4.13.2
 - premium@1.16.4
 - offline@3.2.0 
 - formio@2.3.3
 - uswds@2.4.4
 - vpat@2.4.1



### Tickets Included

- FIO-4985	API | Project Level Access - Read All Anonymous permission is opening up READ Access for form submissions



# April 5th, 2022 Release
## API Server Version 6.12.4
## PDF Server Version 3.3.8

### Included Correlated Libraries:
 - portal@7.0.50
 - formviewpro@1.98.5
 - formmanager@1.98.5
 - formiojs@4.14.7
 - premium@1.18.2
 - offline@4.2.0 
 - formio@1.91.12
 - uswds@2.4.6
 - vpat@2.4.2



### Tickets Included

- FIO-5036 FJS, PRE | Regression | Sketchpad: Sketchpad preview drawing does not display on submission open / edit
- FIO-4942 FJS | Regression | Email submission: Custom PDF File Name is not respected and defaulted to {{ form.name }}-{{ submission._id }}
- FIO-4766 FJS | Update submission data is deleting all information when using a specific project JSON file
- FIO-4897 PDF | PDF server is launching multiple excessive chrome processes that increase cpu utilization



# April 14th, 2022 Release
## API Server Version 7.3.2
## PDF Server Version 3.3.7

### Included Correlated Libraries:
 - portal@7.3.2
 - formviewpro@1.98.4
 - formmanager@1.98.4
 - formiojs@4.14.6
 - premium@1.18.1
 - offline@4.2.0 
 - formio@2.4.1
 - uswds@2.4.6
 - vpat@2.4.2

### New Feature
- Offline License

### Tickets Included

- FIO-4941 Resolve node-saml CVE with dependency version bump
- FIO-4905 LIC | Offline License | In a read-only mode I can create/update form/resource actions
- FIO-4899 LIC | Offline License | When project limit is reached, I cannot create new stages / tenants
- FIO-4890 LIC | Offline License | Read-only mode | Able to Import / Export project JSON to / from a stage. Able to create / deploy / delete tags 
- FIO-4887 LIC | Offline license is counting portal base against the project limits
- FIO-4853 API | Project Template not saving after selecting Project JSON using Upload a Project Template button when creating a New Project
- FIO-4815 API, FJS | Tabs: Cannot make a submission with a Tabs component. Get 400 Bad Request error
- FIO-4789 API | PDF | SUB | Review Vulnerabilities in latest versions
- FIO-4778 FJS | Regression | Select: When Form contains Edit/Data Grids with Selects with Resource Data Source Type and HTML 5 / ChoicesJS Widget Types, options in Selects aren't showing
- FIO-4772 API | Offline License | Issue with On-Premise on API 7.3.1 using Offline License
- FIO-4763 FJS | Regression | Select in Dynamic Wizard/ Data/Edit Grid/TagPad: Cannot make a submission. Get 'Could not connect to API server (key editGrid[0].select must not contain '.')' error
- FIO-4654 API |  Enable the upload of images to our ECR registry as part of the CircleCI process.
- FIO-4642 LIC | License remote: Able to create more than 3 new projects. No longer able to use that license when making a new deployment. Get Exceeded the allowed number of projects. Max number of your projects is 3. You have 10 projects.
- FIO-4353 API, LIC | Offline License fails to validate when upgrading from existing 7.x license
- FIO-4300 PDF |  Get PDF server to work with offline license
- FIO-3924 FJS | Remove Datagrid setting Enable "Equal column width" as it's causing additional columns
 

# March 25th, 2022 Release
## API Server Version 6.12.3
## PDF Server Version 3.3.5

### Included Correlated Libraries:
 - portal@7.0.48
 - formviewpro@1.98.2
 - formmanager@1.98.2
 - formiojs@4.14.3
 - premium@1.18.0
 - offline@4.2.0 
 - formio@1.91.10
 - uswds@2.4.5
 - vpat@2.4.2

### Tickets Included

- FIO-4781 PDF | When 'Attach Submission PDF' setting is enabled, emails are not sent


# March 23th, 2022 Release
## PDF Server Version 3.3.5

### Tickets Included

- FIO-4779 PDF | When there is a Text Area component that has no layout box on a PDF first form, none of the components values that follow the Text Area in the rendering order display on PDF download
- FIO-4784 PDF | Investigate why  PDF server does not process "widget": null, correctly any longer.


# March 14th, 2022 Release
## API Server Version 6.12.1
## PDF Server Version 3.3.4

### Included Correlated Libraries:
 - portal@7.0.48
 - formviewpro@1.98.2
 - formmanager@1.98.2
 - formiojs@4.14.3
 - premium@1.18.0
 - offline@4.2.0 
 - formio@1.91.10
 - uswds@2.4.5
 - vpat@2.4.2

### Tickets Included

### FJS

 - FIO-4398	FJS | Data Grid | When Text Field Input Format setting is set to HTML, the data is not displayed in the Text Field
 - FIO-4632	FJS | Regression | Date/Time: When date format is changed to dd-MM-yyyy and Time input is disabled, the wrong date displays on View Submission, PDF download and Kendo UI grid 
 - FIO-4763	FJS | Regression | Select in Dynamic Wizard/ Data/Edit Grid/TagPad: Cannot make a submission. Get 'Could not connect to API server (key editGrid[0].select must not contain '.')' error
 - FIO-4775	FJS | Table view form | When editing a signature component submission, the data disappears
 - FIO-4778	FJS | Regression | Select: When Form contains Edit/Data Grids with Selects with Resource Data Source Type and HTML 5 / ChoicesJS Widget Types, options in Selects aren't showing 


# March 1st, 2022 Release
## API Server Version 6.12.0
## PDF Server Version 3.3.3

### Included Correlated Libraries:
 - portal@7.0.47
 - formviewpro@1.98.1
 - formmanager@1.98.1
 - formiojs@4.14.2
 - premium@1.18.0
 - offline@4.2.0 
 - formio@1.91.9
 - uswds@2.4.5
 - vpat@2.4.2
 
### Tickets Included

### APP

- FIO-4464 APP | iFrame Embed: src ="https://formview.io/...", the environment is outdated though
- FIO-4526 APP | Replaces all instances of 'https://unpkg.com/formiojs@latest' with 'https://cdn.form.io/formiojs/formio.embed.min.js'

### API

- FIO-4386 API | Regression | Cannot make PDF download. Get "Failed to load resource: the server responded with a status of 504" in a console

### FJS

- FIO-2645 FJS | Container | Allow Container required messages in AlertBox to redirect to Container.
- FIO-2681 FJS | Allow Type labels inside the File Component to be localized
- FIO-3320 FJS | Text Area: Value displays inside the input field when viewed as a plain text
- FIO-3321 FJS | Day: Day value displays three times when viewed as a plain text
- FIO-3533 FJS |  Signature Modal when the user tries edit the modal didn't open
- FIO-3715 FJS | Receiving Validation Errors when rendering a form with a submission in draft-state
- FIO-3758 FJS | If multiple Edit Grids are open, then the Radios inside of Edit Grid #2 are not getting set correctly.
- FIO-4037 FJS | Values should not modify once the component has been saved.
- FIO-4355 FJS | Regression | Unable to Download Datasource data via CSV
- FIO-4362 FJS | Regression | Checkbox: Radio input type: Checked radio buttons display as unchecked on Edit and View Submission pages
- FIO-4412 FJS | Checkbox: Checkbox value does not return when the checkbox is shown conditionally, and it is inside the nested form that has "Save as reference" checkbox disabled
- FIO-4442 FJS | Date Time | Date is showing the date prior to submitted date on View Tab and Data Table.
- FIO-4466 FJS | Regression | Select (Resource): Save as Reference setting does not save the value as a reference but the regular value
- FIO-4478 FJS | Regression | Unable to upload a PDF file
- FIO-4538 FJS | Regression | Form Builder: Component menu buttons have inappropriate styling
- FIO-4567 FJS | Regression | Signature is disabled on form load
- FIO-4571 FJS | Regression | Form builder: Component settings: Tooltips don't show up on mouse hover
- FIO-4572 FJS | Regression | Resource: When Resource component is configured correctly, I get 'No Choices to choose from' on search request, though I get the values in a response
- FIO-4615 FJS | Regression | Date/Time, Text Field - Calendar widget: Value is not consistent in submission and PDF download for different timezone cases
- FIO-4631 FJS | Regression | Tooltip box has small width which makes long hints display vertically
- FIO-4632 FJS | Regression | Date/Time: When date format is changed to dd-MM-yyyy and Time input is disabled, the wrong date displays on View Submission, PDF download and Kendo UI grid
- FIO-4690 FJS | Regression | Customer nested form crashes server when submitted
- FIO-4691 FJS | Regression | Calculated Values: When Allow Manual Override of Calculated Value setting is enabled, the value does not get recalculated
- FIO-4693 FJS | Select Resource - Front end validation is not being removed from field when validation is honored
- FIO-4698 FJS | Regression | Tags are not applied to the text in tooltips and render with the text

### FMG

- FIO-2842 FMG | Regression | Custom components do not display in the form builder sidebar
- FIO-4441 FMG | Regression | There is incorrect view of Search Forms field on main page

### FVP

- FIO-4342 FVP | Regression | Offline mode: No submissions display in Submissions UI grid in offline mode

### PDF

- FIO-556 PDF | Signature: When the PDF is zoomed in/out, what is being drawn by the user is shifted to the left/right
- FIO-599 PDF | Nested Form: When nested form is PDF, PDF download shows as webform and the data inside the PDF show blank
- FIO-1343 PDF | Regression | HTML Attributes setting not working
- FIO-4181 PDF | Regression | Unable to add a signature drawing to PDF overlay signature component
- FIO-4391 PDF | Regression | Firefox | Signature: Signature drawing moves to the top left corner after each movement
- FIO-4450 PDF | Regression | Files that cannot be parsed as PDFs process too long, and server throws 504 Bad Gateway error at the end
- FIO-4451 PDF | Regression | Cannot open component settings of the PDF components on the PDF form after saving any changes
- FIO-4614 PDF | Regression | PDF files intermittently don't load on different pages. See the infinite spinner with no errors
- FIO-4635 PDF | PDF form with hidden select component - download is not working. 502 Bad Gateway is shown
- FIO-4661 PDF | Regression | Cannot make a PDF download. Get 504 Gateway Time-out error

### PRE

- FIO-4539 PRE | Regression | IE11 | Portal does not load. Getting errors in a console

### Other Tickets

- FIO-3018 APP, FJS | Custom JavaScript pollution between stages
- FIO-3317 APP, API | Incorrect project limits on Portal and Next comparing to Pricing page
- FIO-3435 API, FJS | Form definition download taking a long time to call
- FIO-3811 APP, API | Gartner Capterra Conversion Tracking Instructions
- FIO-3952 API, FMG | Regression | Cannot make a PDF download on a newly created project. Get Unauthorized error when make a call
- FIO-4363 FJS, PDF | Regression | PDF download: Checkbox: Radio input type: Only the 1st row of checked radio buttons display as checked on PDF download, all the others display as unchecked
- FIO-4377 API, APP | Regression | Portal does not load. Error "Failed to instantiate module formioApp due to:Error: State 'project.env.integrations.signrequest' is already defined"                               
- FIO-4443 FJS, PDF | Regression | Signature is not visible when generating a PDF from webform
- FIO-4579 FJS | Regression | Select Resource - Data is not returned when item template is set but value property field is empty in Select settings
- FIO-4595 FJS, PDF | Regression | Signature: Edit Submission page: Signature value does not clear
- FIO-4658 Incorrect Value for Select Dropdown fed by a Resource
- FIO-4660 6x | Regression | API | Project Limits not updating for Form Requests, Submission Requests  and Emails
- FIO-4671 APP, FJS, PDF | Regression | Unable to open PDF overlay component settings after moving the component on PDF and saving
- FIO-4692 API | CSP errors in console when dragging dropping components in form builder
- FIO-4706 API, PDF | Regression | Cannot make a PDF download from a stage other than live. Recieve 401 Unathorized and 'x-file-token is invalid' error
- FIO-4716 6x | API | Revisions | After Submission, receiving "Could not connect to API server ([object Object])" on View or Edit Tab of Submissions  when 'Use Original Version' is configured for revisions
- FIO-4743 API, APP, FJS | Regression | Actions: Action Conditionals: 'Trigger this action only if field' select: All form components display as 'undefined'
        
### New Feature

### FJS

- FIO-2960 FJS | Add debounce to reCaptcha calls
- FIO-3227 FJS | Custom Select to allow our logic to handle asynchronous custom functions


# February 18th, 2022 Release
## API Server Version 7.3.1
## PDF Server Version 3.3.2

### Included Correlated Libraries:
 - portal@7.3.1
 - formviewpro@1.98.0
 - formmanager@1.98.0
 - formiojs@4.14.1
 - premium@1.18.0
 - offline@4.2.0 
 - formio@2.4.0
 - uswds@2.4.5
 - vpat@2.4.2
 
### Tickets Included


### API

- FIO-1140	API | When deploying the Version from the "Dev" Stage to the "QA" Stage form.io is reintroducing the formRevision tags
- FIO-1159	API | On-Premise | Unable to connect to Remote environment using Remote Portal. Receiving 'Error importing environment - 400 - : [object Object]'
- FIO-3468	API | Webhook - When 'Transform Payload' is added to Webhook action, the submission data is not shown in webhook response
- FIO-3489	API |  GET /health returns HTTP 200 and "ok" instead of detailed diagnostic info.
- FIO-3594	API | Investigate PUT request receiving 404 Error: Resource not found
- FIO-3853	API | The Export JSON function breaks when creating a submission (via the API) that references a Resource submission that does not exist.
- FIO-3969	API | Lodash is still executing functions when protected eval is being used
- FIO-4043	API | Custom Components not loading on Forms
- FIO-4143	API | Error causing server crash - TypeError: req.submissionFieldMatchAccess[accessKey].some is not a function
- FIO-4234	API | s3 Files with Policy Expiration field set above 15 min (900 seconds) are getting AccessDenied error prior to what the policy expiration field is set to
- FIO-4368	API | Unable to connect to MongoDB using API Server 7.3.0
- FIO-4473	API | SSO - error when using SSO authentication with SAML. 
- FIO-4537	API | Regression | Date/Time component is not opening calendar widget for existing forms and component is removed from form when creating a new form
- FIO-4552	API | Various tasks in  portal returning error - Receiving Failed to load resource: net::ERR_BLOCKED_BY_RESPONSE.NotSameOriginAfterDefaultedToSameOriginByCoep
- FIO-4569	API | Regression | Tenant manager page does not open, receiving ' remote-dev.form.io refused to connect.' error in browser
- FIO-4596	API |  SAML using login.gov not working with API 7.3.0 and API 7.3.1.
- FIO-4598	API | Local Deployment: formio-server v7.3.1-rc-4: Portal does not load correctly
- FIO-4692	API | CSP errors in console when dragging dropping components in form builder


### APP
- FIO-3030	APP | Fix UI Issue that shows any invite UI when using SAML (SSO) as team member 
- FIO-3816	APP | Regression | Profile: Username does not display on View page. On Edit page it is the 1st field instead of being the 2nd, and it's not reqired
- FIO-3925	APP | Regression | Kendo UI grid is not displaying data or fields
- FIO-4182	APP | Regression | Unable to add a new stage to a project. The 'Add Stage' button is disabled when I enter a Stage Title
- FIO-4246	APP | IE11 | Upload request fails, and I receive 'fetch is undefined' error when deploying a stage and migrating PDF files
- FIO-4292	APP | Regression | Resources, Forms, Access, Data pages: Forms are sorted by alphabetical order instead of being sorted by the last time they were updated
- FIO-4401	APP | Revisions | When viewing data from initial version, it should show data as form and is instead being shown as wizard 
- FIO-4470	APP | A wrong message appears when try to save components when unique API key was match 

### FJS

- FIO-560	FJS | Text Area: CKEditor not showing inserted media on View Submission tab
- FIO-2645	FJS | Container | Allow Container required messages in AlertBox to redirect to Container.
- FIO-2718	FJS | Move the location of the minDate and maxDate off of the Date tab and to the Validation tab to avoid confusion
- FIO-2864	FJS | Tooltip not showing text after running into double quotes
- FIO-2991	FJS | Regression | PDF submission 'created' time not showing on PDF download when set via content component
- FIO-3038	FJS | Password: Excessive 'Hide Input' setting
- FIO-3199	FJS | When validation is triggered on a time component, the form can still be submitted
- FIO-3239	FJS | Initial component with default value that is breaking validation is not showing after changes to other components
- FIO-3320	FJS | Text Area: Value displays inside the input field when viewed as a plain text
- FIO-3321	FJS | Day: Day value displays three times when viewed as a plain text
- FIO-3502	FJS | Radio , Select Boxes, Select | Value being overwritten when editing Label
- FIO-3533	FJS |  Signature Modal when the user tries edit the modal didn't open
- FIO-3627	FJS | Nested Form | Modal | Validation Errors not redirecting to Component
- FIO-3715	FJS | Receiving Validation Errors when rendering a form with a submission in draft-state
- FIO-3756	FJS | Resource: Get Unauthorized error when unfolding the "Resource" select on the "Display" tab. No resources display until I load them through the Select (Resource) component and get back to the Resource component
- FIO-3825	FJS | Conditional component not re-showing if you change a component value to make it untrue and then change the value again to make it true”
- FIO-3860	FJS | Existing Resource Field showing Different Property Name from PDF and webforms
- FIO-3884	FJS | Conditionally required fields inside datagrids are displaying required red asterisk inside the field and not the label
- FIO-3948	FJS |  Edit Grid | Saving two items in an edit grid with the second created saved first, then editing the second created one, the data is overwritten to the first created
- FIO-3973	FJS | Edit Grid: Wrong error displays for the 1st component in EG. 'Invalid row. Please correct it or delete.' error displays even when all the errors are fixed in EG
- FIO-3974	FJS | Regression | Different color or component errors: #BF2231 instead of #dc3545
- FIO-3975	FJS | Conditionally hidden modal buttons still display on the form. They are empty when opened
- FIO-3976	FJS | Regression | Sketchpad: When any logic is configured for the Sketchpad, the component breaks down
- FIO-4002	FJS | Data Grid: Signature column is changing the size when the form is rendered or new row is added
- FIO-4037	FJS | Values should not modify once the component has been saved. 
- FIO-4055	FJS | Calendar Widget is not showing correct date on PDF submission
- FIO-4070	FJS | Edit Grid | Text field with <b> and </b> causes textfield to render incorrectly
- FIO-4299	FJS | Data Source Component not passing POST request
- FIO-4305	FJS | Add the flags to the setForm method for PDF
- FIO-4337	FJS | Regression | After selecting 'Password Strength' addon, there are no settings for that addon show up
- FIO-4351	FJS | React |  Replace tooltip functionality 
- FIO-4362	FJS | Regression | Checkbox: Radio input type: Checked radio buttons display as unchecked on Edit and View Submission pages
- FIO-4374	FJS | DataTable | Knowing what data table raised the row clicked event if multiple data tables are on a form
- FIO-4398	FJS | Data Grid | When Text Field Input Format setting is set to HTML, the data is not displayed in the Text Field
- FIO-4405	FJS | When hidden radio has the Storage Type as String, we are receiving empty validation error
- FIO-4412	FJS | Checkbox: Checkbox value does not return when the checkbox is shown conditionally, and it is inside the nested form that has "Save as reference" checkbox disabled
- FIO-4419	FJS | iOS Safari | Time: When trying to select time and submit it, form.io validation is failing. When marking the time component as not mandatory, in submission json time will be blank
- FIO-4442	FJS | Date Time | Date is showing the date prior to submitted date on View Tab and Data Table.
- FIO-4446	FJS | Regression | Select fields configured with Resource/URL as data source and 'Lazy Load' setting enabled are not displaying values when validation has been triggered
- FIO-4466	FJS | Regression | Select (Resource): Save as Reference setting does not save the value as a reference but the regular value
- FIO-4468	FJS, PDF | Select boxes look overlapped on PDF download view.
- FIO-4478	FJS | Regression | Unable to upload a PDF file
- FIO-4496	FJS | Regression | Select (Resource): When more than one object is in the Item Template, returned results from the response do not display in the dropdown
- FIO-4538	FJS | Regression | Form Builder: Component menu buttons have inappropriate styling
- FIO-4567	FJS | Regression | Signature is disabled on form load
- FIO-4571	FJS | Regression | Form builder: Component settings: Tooltips don't show up on mouse hover
- FIO-4572	FJS | Regression | Resource: When Resource component is configured correctly, I get 'No Choices to choose from' on search request, though I get the values in a response
- FIO-4573	FJS | Regression | Examples page: Submission Hosting page: Form does not load. Get 400 Bad Request Invalid alias error
- FIO-4579	FJS | Regression | Select Resource - Data is not returned when item template is set but value property field is empty in Select settings
- FIO-4615	FJS | Regression | Date/Time, Text Field - Calendar widget: Value is not consistent in submission and PDF download for different timezone cases
- FIO-4631	FJS | Regression | Tooltip box has small width which makes long hints display vertically
- FIO-4690	FJS | Regression | Customer nested form crashes server when submitted
- FIO-4691	FJS | Regression | Calculated Values: When Allow Manual Override of Calculated Value setting is enabled, the value does not get recalculated
- FIO-4693	FJS | Select Resource - Front end validation is not being removed from field when validation is honored
- FIO-4698	FJS | Regression | Tags are not applied to the text in tooltips and render with the text

### FMG

- FIO-1320	FMG | User is redirected to Edit page after clicking on No button in a Delete a form page regardless where you come from
- FIO-1355	FMG | Forms page: Close button overlaps a text in the Search bar
- FIO-2842	FMG | Regression | Custom components do not display in the form builder sidebar
- FIO-3952	FMG | Regression | Cannot make a PDF download on a newly created project. Get Unauthorized error when make a call
- FIO-4441	FMG | Regression | There is incorrect view of Search Forms field on main page
- FIO-4656	FMG | Regression | Tooltip box has small width which makes long hints display vertically

### FVP

- FIO-3595	FVP | Unable to submit form in offline mode. Error is showing or Submit button is just spinning.
- FIO-4042	FVP | Mobile View | Title of Form does not wrap to next line. 
- FIO-4236	FVP | Regression | IE browser: Submission cannot be done by a user with Authenticated role and error appears for user with Anonymous role
- FIO-4453	FVP | Regression |  There is no color coordinated section based on operations to show Green - added, Orange - changed and Red - deleted submissions while in offline mode

### LIC

- FIO-3762	LIC | Empty stage is being reported as project in license utilization page when a stage is connected to a remote environment
- FIO-3773	LIC | When stage connected to an OnPrem environment, the stage is reporting as a 'project' in License Utilization
- FIO-4197	LIC | Regression | When TENANT limit has been reached, no error message appears. Tenant does not show in Tenant manager as disabled.

### PDF

- FIO-556	PDF | Signature: When the PDF is zoomed in/out, what is being drawn by the user is shifted to the left/right
- FIO-599	PDF | Nested Form: When nested form is PDF, PDF download shows as webform and the data inside the PDF show blank
- FIO-1200	PDF | PDF themes do not apply when select them in PDF Theme dropdown in PDF Settings
- FIO-1343	PDF | Regression | HTML Attributes setting not working 
- FIO-1521	PDF | Conditional Number not showing if conditional is selecting all and deleting. Working if using backspace/delete key.
- FIO-3120	PDF | PDF download: When a component with a value does not fully fit on a PDF page, it moves to the following page, becomes separated by the pages and creates an excessive page break above
- FIO-3366	PDF | Date/Time: When Time is disabled, the date in the PDF download will be one day off the selected date
- FIO-4181	PDF | Regression | Unable to add a signature drawing to PDF overlay signature component
- FIO-4249	PDF | Moving PDF components not moving to correct location when using external monitors and resolution size is changed
- FIO-4391	PDF | Regression | Firefox | Signature: Signature drawing moves to the top left corner after each movement
- FIO-4402	PDF | Regression | IE11 | PDF forms are not loading
- FIO-4450	PDF | Regression | Files that cannot be parsed as PDFs process too long, and server throws 504 Bad Gateway error at the end
- FIO-4451	PDF | Regression | Cannot open component settings of the PDF components on the PDF form after saving any changes
- FIO-4536	PDF | Regression | PDF forms don't load
- FIO-4614	PDF | Regression | PDF files intermittently don't load on different pages. See the infinite spinner with no errors
- FIO-4635	PDF | PDF form with hidden select component - download is not working. 502 Bad Gateway is shown 
- FIO-4671	PDF | Regression | Unable to open PDF overlay component settings after moving the component on PDF and saving
- FIO-4685	PDF | File: S3: Images display as broken links on PDF form

### PRE

- FIO-3069	PRE | Data Table: The components in the Data Table display blank in the PDF
- FIO-3675	PRE | Data Table: When minimum and maximum length is set in the component settings, the 'Delete All' button does not show up
- FIO-3983	PRE | Data Table | Scrollbar is causing column value to not show the full value
- FIO-3995	PRE | Data Table | Investigate Add Button missing
- FIO-3999	PRE | IE11 | Data Table does not load
- FIO-4001	PRE | Regression | Data Table: Edit row and Delete row buttons display one below the other partially overlapping the next row buttons
- FIO-4385	PRE | When a data table has a Date / Time field and the user uses the date picker/calendar in the column heading Filter option, the filter fields disappear.
- FIO-4393	PRE | Resolve Typos in Filtering Dropdown of Data Table Component
- FIO-4400	PRE | Data Table | When Filtering the table, the filters-applied class modifier should be added to the 3 dots in the column
- FIO-4414	PRE | Data Table: When no data entries are added yet, no component headers display
- FIO-4415	PRE | Data Table: Controls in a layout control does not show in table view
- FIO-4539	PRE | Regression | IE11 | Portal does not load. Getting errors in a console

### SUB

- FIO-4296	SUB | Submission Server "Data" tab does not paginate correctly

### USWDS

- FIO-4314	USWDS | USWDS-viewer where format=html is not replacing the libs with compressed code. It just returns "Form.io Viewer" in the rendered html.


### Other Tickets

- FIO-1453	API, APP | 7x/6x | When you re-import an updated parent form from a tenant to a stage, the linkage breaks
- FIO-2649	ACC, FMG | All br/sr | Extra 'main' landmark is showing in landmarks list in NVDA and JAWS, 'banner' and 'search' landmarks are missing in the landmarks list in NVDA 
- FIO-2841	ACC, FMG | When focusing a Search bar with a keyboard, a new search request is automatically sent to the server
- FIO-3018	APP, FJS | Custom JavaScript pollution between stages
- FIO-3233	PRE, APP | Data Table: Columns of the components inside Container, Data Grid, Edit Grid, Tree display in the Data Table, though they are always empty
- FIO-3435	API, FJS | Form definition download taking a long time to call
- FIO-3508	ACC, VPAT | Disable Data Table component, since it does not have accessibility support
- FIO-3519	ACC, FJS | USWDS | Scroll up on page opening not scrolling to the step indicator/progress bar
- FIO-3677	FJS, PRE | Nested Form: Logic that makes a Nested Form disabled does not work, and the components inside the Nested Form stay active
- FIO-3737	API, FJS | ReCAPTCHA: ReCAPTCHA does not protect submission endpoints.
- FIO-3775	API, APP | Receiving unauthorized error when deleting a stage connected to an onprem environment
- FIO-3782	ACC, USWDS | PDF download: Select (ChoicesJS): No field outlines display on PDF download
- FIO-3842	APP, VUE | Form is not rendering TypeError: Cannot call a class as a function
- FIO-4081	ACC, FJS, USWDS | Regression | File: When file pattern is configured, I get the next message when the form is rendered: 'Allowed file types: undefined'
- FIO-4084	ACC, FMG | Regression | 'Skip to Content' button is missing
- FIO-4353	API, LIC | Offline License fails to validate when upgrading from existing 7.x license
- FIO-4363	FJS, PDF | Regression | PDF download: Checkbox: Radio input type: Only the 1st row of checked radio buttons display as checked on PDF download, all the others display as unchecked
- FIO-4367	Resolves PDF Server Vulnerabilities
- FIO-4443	FJS, PDF | Regression | Signature is not visible when generating a PDF from webform
- FIO-4460	API, PDF | Regression | When uploading one of the test project JSON files with PDF migration, the server crashes
- FIO-4487	API, FJS | Server crashes returning 502 Bad Gateway error on patch request to a non-existing submission
- FIO-4489	FVP | IE11 | Cannot open a form. Get the next error: 'SCRIPT5002: Function.prototype.toString: 'this' is not a Function object'
- FIO-4533	FMG, FVP | Regression | FMG/FVP does not load. Get errors in a console
- FIO-4542	FJS, PDF | Regression | HTML Element, Content,Text Area: ACE, CKEditor and Quill do not display the input area
- FIO-4546	FJS, PDF | Regression | DataTable is not showing on Use Tab.
- FIO-4565	API, FJS | Regression | Required validaiton does not fire for empty protected fields when editting a submission
- FIO-4582	API, APP | Regression | Additional CSP restriction issues
- FIO-4595	FJS, PDF | Regression | Signature: Edit Submission page: Signature value does not clear
- FIO-4599	VPAT, FMG | Regression | Form Builder: Components are added without Labels and Property Names, and there is no possibility to add them and save the component with them. Components are shown as unknown
- FIO-4600	FJS, USWDS | Regression | Survey: Radio buttons inside the table display between the rows overlapping the borders
- FIO-4601	VPAT, FMG | Regression | Enter Data: File can't be uploaded into File component that contains Tooltip
- FIO-4602	PDF, USWDS | Regression | Get Socket Hang Up error when generating a downloadable PDF from a test regression form
- FIO-4606	Error: 'Cannot read property 'map' of undefined' causing server crash
- FIO-4608	VPAT, FMG, FVP | Regression | Enter Data, Edit Submission: If Wizard form contain component with tooltip, there is no switching to Next page. If Web form contain component with tooltip, there is no switching to View Data page.
- FIO-4632	FJS, PDF | Regression | Date/Time: When date format is changed to dd-MM-yyyy and Time input is disabled, the wrong date displays on View Submission, PDF download and Kendo UI grid
- FIO-4658	Incorrect Value for Select Dropdown fed by a Resource 

### New Features

### APP

- FIO-2939	APP | Create Debounce Timeout for DataSource
- FIO-3770	APP | Allow for PDF migration work with Project Import as well as Single form imports via Form Embed URL
- FIO-4480	APP | Add a spinner for PDF upload and remove the Upload PDF button when the PDF file is processed


### FJS
- FIO-2960	FJS | Add debounce to reCaptcha calls
- FIO-3227	FJS | Custom Select to allow our logic to handle asynchronous custom functions
- FIO-3880	FJS | Add deferRender option to form renderer
- FIO-4311	FJS | Wizard | Wizard theme that supports right hand navigation 

### FVP

- FIO-663	FVP | Ability for URL params to auto-populate the forms
- FIO-3338	FVP | Ability for Application message Translations to work in FVP 
- FIO-3956	FVP |  Direct Anonymous User to specific submission URL / redirect to login, back to URL after authentication

### PDF

- FIO-2646	APP, FJS | Enable ability to turn off the sanitize method
- FIO-2996	PDF | Text size has decreased on PDF download from 2.96x to 3.1.1
- FIO-3130	PDF, APP | Ability to set the font size of PDF overview
- FIO-3131	API, APP, FJS | Google Drive Integration 


# January 14th, 2022 Release
## API Server Version 7.1.13
## PDF Server Version 3.3.1

### Included Correlated Libraries:
 - portal@7.2.14
 - formviewpro@1.97.14
 - formmanager@1.97.14
 - formiojs@4.13.12
 - premium@1.16.4
 - offline@3.2.0 
 - formio@2.2.7-rc.1
 - uswds@2.4.4
 - vpat@2.4.1
 
### Tickets Included

- FIO-4455 API | Issue with calculation on conditionally shown field
- FIO-4314 USWDS | USWDS-viewer where format=html is not replacing the libs with compressed code. It just returns "Form.io Viewer" in the rendered html
- FIO-4313 Date fields not formatted as MM/dd/yyyy are dropping for the form and not appearing on the pdf
- FIO-3990 ACC, USWDS | Checkboxes inside of Data Grid with more than 1 row are only checking/ unchecking the first-row Checkbox regardless of which rows checkbox you click


# January 14th, 2022 Release
## API Server Version 7.2.5
## PDF Server Version 3.3.1

### Included Correlated Libraries:
 - portal@7.2.14
 - formviewpro@1.97.14
 - formmanager@1.97.14
 - formiojs@4.13.12
 - premium@1.16.4
 - offline@3.2.0
 - formio@2.3.3
 - uswds@2.4.4
 - vpat@2.4.1
 
### Tickets Included

- FIO-4441 FMG | Regression | There is incorrect view of Search Forms field on main page
- FIO-4412 FJS | Checkbox: Checkbox value does not return when the checkbox is shown conditionally, and it is inside the nested form that has "Save as reference" checkbox disabled


# December 17th, 2021 Release
## API Server Version 7.2.4
## PDF Server Version 3.3.1

### Included Correlated Libraries:
 - portal@7.2.13
 - formviewpro@1.97.13
 - formmanager@1.97.13
 - formiojs@4.13.11
 - premium@1.16.4
 - offline@3.2.0
 - formio@2.3.2
 - uswds@2.4.3
 - vpat@2.4.1
 
### Tickets Included

- FIO-4355 FJS | Regression | Unable to Download Datasource data via CSV
- FIO-4324 FJS | Templating Code executes on API/PDF Server
- FIO-4292 APP | Regression | Resources, Forms, Access, Data pages: Forms are sorted by alphabetical order instead of being sorted by the last time they were updated
- FIO-4228 API | After updating MongoDB dependencies, it no longer supports the "mongos" option.
- FIO-4088 API | PATCH is not supported on Draft Submissions
- FIO-3489 API |  GET /health returns HTTP 200 and "ok" instead of detailed diagnostic info.



# December 1st, 2021 Release
## API Server Version 7.3.0
## PDF Server Version 3.3.1

### Included Correlated Libraries:
 - portal@7.3.0
 - formviewpro@1.97.12
 - formmanager@1.97.12
 - formiojs@4.14.0
 - premium@1.17.1
 - offline@3.2.0
 - formio@2.3.1
 - uswds@2.4.2
 - vpat@2.4.1
 
### Tickets Included

- FIO-4313 Date fields not formatted as MM/dd/yyyy are dropping for the form and not appearing on the pdf
- FIO-4306 API, FJS, PRE | Investigate why SignRequest component is not showing in builder on the 7.3.0 build and fix various sign request bugs
- FIO-4270 LIC | Deleted Stages still showing on License Management Page
- FIO-4250 API | Regression | At times, I receive 'This is project has been disabled with the following message: Cannot read property 'terms' of undefined. Please correct the problem before continuing.' error when using a project
- FIO-4241 FJS | Calculation Validation not showing until submission when numbers are inside a data grid
- FIO-4200 LIC | 7.2.1 Regression | Stage limit is not being honored allowing two additional stage to be created against the license limit
- FIO-4196 API | 7.2.1 Regression| Server is crashing after trying to access a stage that has been disabled via license utilization
- FIO-4185 FJS | 7.2.1 Regression | Focus moves to the top of form after entering values, when error list is showing
- FIO-4174 FJS | Regression | Examples page: Radio buttons appear too far left
- FIO-4120 FJS | Edit Grid | The row variable is changing in the Edit grid between editing the row and viewing the row.
- FIO-4085 FJS | Modal Edit | Data is being saved instead of being cleared when clicking outside the modal and confirming to clear data or clicking the x
- FIO-4072 FJS | Number | "-" is not triggering 'is not a number' validation when that is the only character on the field
- FIO-4045 FVP, FJS | Offline Mode not loading existing online submissions and receiving 'unable to submit the form' message. Offline submissions do not load correctly as well
- FIO-4000 PRE | IE11, Firefox, Safari | Data Table: Moving components out of the Layout components inside the Data Table, a browser stops responding
- FIO-3996 FJS | 4.14.0 Regression | IE11 | Examples pages: None of the pages load in IE11. Errors in a console
- FIO-3990 ACC | USWDS | Checkboxes inside of Data Grid with more than 1 row are only checking/ unchecking the first-row Checkbox regardless of which rows checkbox you click.
- FIO-3984 FJS | 4.14.0 Regression | Date/Time: First click on a desired date does not select it, and the current one is selected instead. The 2nd click selects the desired date
- FIO-3970 FJS | 4.14.0 Regression | Edit Grid: When 'Open First Row when Empty' setting is enabled, no table headers display
- FIO-3966 FJS | 4.14.0 Regression | Text Area: Text Area has a default value upon creation
- FIO-3944 FJS | 4.14.0 Regression | Spacing between certain settings when the component setting page is opened
- FIO-3940 PRE | Tagpad: When there are more than one Tagpad in a webform, only the last one will work. All the other won't
- FIO-3934 PRE | Regression | Sketchpad: Rendered form: Changing the circle size, the circles cannot be placed onto the image
- FIO-3913 FJS | DateTime inside DataGrid flickers a lot.
- FIO-3912 FJS | Can we disable the auto populate field key based on Label property of a component?
- FIO-3911 FJS | Date/Time: Calendar control is not reflecting the localization changes
- FIO-3875 FJS | Validation not triggering until form is submitted on a calculated value in number component
- FIO-3865 NFP | Settings: Settings sidebars should not change their width on selecting different options
- FIO-3838 FJS | Tabs | Tabs Keys go back to default key after making a change and adding more tabs
- FIO-3836 FJS | Validate { required : true } added to Panel Component causes API Server timeout
- FIO-3760 FJS | Custom Component | TypeError: ctx.component.fields is undefined
- FIO-3753 FJS | Value set into the Edit Grid with "Open First Row when Empty" setting enabled that is inside the Container which is conditionally shown, does not save. After submit, I get " "0" must be an object " error
- FIO-3752 FJS | Clicking the button with a custom action inside the Edit Grid lvl1, the value is not set into the Edit Grid lvl2 inside the Panel inside the Edit Grid lvl1 on the 1st click but the 2nd
- FIO-3744 FJS | Resource: Unique validation is not honored on submit
- FIO-3743 FJS | Date/Time: When Date is disabled, the Hours value does not save on 1st change but the 2nd
- FIO-3713 FJS | Investigate 504 GATEWAY_TIMEOUT Error on Patch request with file upload component
- FIO-3681 PRE | When using DataTable component and conditional to show it related to the value of another component on the form gives the error "Cannot set property 'disabled' of undefined"
- FIO-3674 FJS, PDF | PDF form: Conditionally shown field does not show up when the logic is met on a customer form
- FIO-3657 FJS | Fields do not appear to be calculating in the client, though the calculation seem to happen on the server and the calculated values display in submission
- FIO-3653 PRE | Data Table | The filter option does not show a textbox into which to enter a filter value.
- FIO-3652 PRE | Data Table | Clicking the Filter button in the column filter causes our onSubmit method to be called
- FIO-3651 PRE | Data Table | When adding a button to the grid, the event raise for the button only has the button itself as part of the event data.
- FIO-3631 FJS | Red asterisk doesn't display when the modal view is enabled
- FIO-3599 PDF | Investigate Performance Improvements for Custom  PDF Viewer
- FIO-3571 FJS | HTML code is rendered in textfield and textarea components event when input format is set to PLAIN.
- FIO-3561 FJS | 4.13.5 Regression | Data Grid | Filled required field is showing as invalid and form can't be submitted
- FIO-3552 PRE | Data Table: Page spin button: Focus is lost upon pressing Up or Down arrow buttons
- FIO-3551 PRE | Regression 1.17.0 | Data Table: Component Settings: Display tab: Last setting states: 'Unknown component: undefined'
- FIO-3549 PRE | Data Table: When Unique validation for some components inside Data Table is not met, no errors display in the Error list
- FIO-3548 PRE | Data Table: Remove Unique validation
- FIO-3537 FJS | Data Table: Cannot save the form with several Data Tables with unique API keys that have several components inside of them with the same API keys
- FIO-3536 PRE | Data Table: Error list does not display in the Data Table modal window when errors occur
- FIO-3535 PRE | Data Table: When no columns display in the Data Table, after adding a row and clicking edit button, I get errors in a console
- FIO-3521 PRE | Modify Tag Pad template so it works with columns inside of the tag pad
- FIO-3518 FJS | Scroll up on page opening not scrolling to the Breadcrumb only to top of the form
- FIO-3500 FJS, PDF | FieldSet in a form longer than 1 pdf page will auto page break to page 2
- FIO-3488 FJS | Caluclated fields not triggering on form load properly when submission JSON is set
- FIO-3465 FJS | Errors embedding FJS 4.14.0-rc.13 inside application
- FIO-3447 PDF | Signature | Hide gray box next to PDF signatures
- FIO-3428 APP | Portal incorrectly sends /project/available request to on-premise environment instead of hub
- FIO-3418 FJS | Investigate issue with cursor jumping back after hitting the space bar
- FIO-3409 PRE | Data Table, Data Grid, Data Source: Data shows as empty when I click the edit button of a row created via the Data Source inside a Data Grid
- FIO-3381 FJS | Edit Grid: 'Inline Editing' setting has an incomplete tooltip text
- FIO-3362 FJS | Reconfigure PR so that it does not cause spacing issues in Data Grids
- FIO-3346 FJS | Date/Time: Value that is typed in manually does not persist on submit. An extra character can be added at the end of the value
- FIO-3344 FJS | Form builder: Hidden, Data Source, Form components: Errors display over the overlay bottom border
- FIO-3326 FJS | Nested Form with Clear value on hidden with conditional logic is clearing on the 2nd change and not the inital
- FIO-3322 FJS | Survey: When viewed as a Plain Text, it renders as an incomplete table without values
- FIO-3319 FJS | Select Boxes: Values don't display when viewed as a plain text
- FIO-3305 FJS | File: When File pattern is configured and more than 1 file extension is defined, I can only upload files of the 1st file extension
- FIO-3286 PRE | Investigate Datagrid not updating while datasource fetch data successfully
- FIO-3280 FJS | 4.13.3 Regression | Address: Modal View: Confirmation dialog shows one extra time after a new value has been added
- FIO-3279 FJS | 4.13.3 Regression | File: Modal View: When confirming removing the uploaded file, it is removed but visually still displays
- FIO-3247 FJS | Please check the form and correct all errors before submitting. not redirecting to error box at the top of the page
- FIO-3243 FJS | Select Boxes | Label Position Top and Options Label Left causes Box to block Label name
- FIO-3241 PRE | Data Table: When there is a component in a Modal View inside the Data Table, the Data Table Modal window does not close on 'X' button
- FIO-3238 PRE | Data Table: Adding a new data entry after 'All items per page' has been selected, the 1st data entry created moves to the next page and the new one is being added to the current
- FIO-3236 PRE | Data Table: Pressing Reset button doesn't close Data Table row modal window
- FIO-3165 FJS | Signature: Signature value persists in the Modal View when the changes are rejected
- FIO-3160 ACC, FJS | Select Boxes: Select Boxes options are announced as 'radio button'
- FIO-3098 PRE | Data Table: In Table View, the grid renders wrong value for Select field in certain situations
- FIO-3092 FJS | Investigate issue with Customer data not showing up on View Tab
- FIO-3082 DataTable | Unable to submit form with a required field, even if the field has passed validation
- FIO-3080 PRE | Data Table: 'Minimum Length' and 'Maximum Length' settings do not work. You can reduce/surpass the minimum/maximum number of allowed data entries
- FIO-3079 PRE | Data Table: Page spin button has no limit in values
- FIO-3078 PRE | Data Table: Total number of pages does not display
- FIO-3077 PRE | Data Table: Disable component controls according to the data presented in the Data Table
- FIO-3076 PRE | Data Table: Property name is 'datatable'. Should be 'dataTable'
- FIO-3075 PRE | Data Table: Empty data entry rows shrink in size. 'Edit row' and 'Delete row' buttons overlap each other
- FIO-3068 PRE | Data Table: Property name not incrementing when component type is in a Data Grid/Edit Grid as well as a Data Table
- FIO-3066 PRE | Wizard: Data Table: When the Data Table is not on the last wizard page, and you get to the last page through the page the Data Table is on, you won't be able to submit the form. Error 'Cannot set property 'value' of undefined' occurs
- FIO-3065 PRE | Data table: Data Table does not work correctly in the Modal View
- FIO-3063 PRE | Data table: When Data Table is disabled, you can edit data, submit them and the edited values persist
- FIO-3061 PRE | Data table: Data Table does not get initial focus initially when 'Initial Focus' setting is enabled
- FIO-3060 PRE | Data table: When the Data table is hidden, there are 2 errors in a console when rendering the form, viewing or editing its submission
- FIO-3059 APP, PRE | Data table: When the Data Table component has 'Table View' setting disabled, and there are components inside it having it enabled, they will display in the Data grid table on the Data page
- FIO-3058 FJS | Data Table: Selecting Right label position, the Data table partially renders outside the Preview section in the component settings and the Webform when rendered on the Use page
- FIO-3057 PRE | Chrome, Edge, Safari | Data Table: Mobile horizontal scroll on a desktop version of the website
- FIO-3056 PRE | Firefox, Safari | Data Table: Clicking on 3-dots menu button in the Data table and then anywhere out to close the menu, it does not get closed causing errors in a console
- FIO-3051 PRE | Data Table: ,"survey":{} is at the end of the survey section on the Data Table
- FIO-3050 Data Table | No error message under submit if required fields are not met, nor error box on the top of the form that provides redirect to the form
- FIO-3049 PRE | Data Table: Address is showing up as [Complex Data] in the Table
- FIO-3048 PRE | Data Table: When saving a form with an unused select box, the form does not show in the Data Table and unable to create new form
- FIO-3045 PRE | Data Table: When selecting to show 'All' items, the word 'All' disappears
- FIO-3044 PRE | Data Table: Unable to make an update when I edit a submission
- FIO-3023 PRE | Dynamic Wizard: 'Minimum Length' and 'Maximum Length' settings do not work. You can reduce/surpass the minimum/maximum number of allowed data entries
- FIO-3011 FJS | Select (HTML5, Resource, Entire Object): Only '{' character is send and returned to/from the server
- FIO-3010 PRE | Dynamic Wizard: Remove Unique validation
- FIO-3008 PRE | Dynamic Wizard: When you are on the wizard page with DW in edit mode, and you click on the error in the Error list that is on a different wizard page, no components display on the page
- FIO-3002 FJS | Remove Extra small size option for Buttons
- FIO-3000 ACC, FJS | Web form: Submit button is referenced by [aria-labelledby] with [id=l-eiqbap-submit] not found
- FIO-2989 API, FJS | OpenID receiving 404 - Couldn't connect to API
- FIO-2987 ACC, FJS | Panel: When clicking on the collapsible panel in the Modal window, the Modal window closes
- FIO-2985 ACC, FJS | File: When no file formats are specified, quite a long message displays in the component and announced
- FIO-2984 ACC | File: Change the 'Use Camera,' link to 'use camera'
- FIO-2981 ACC, FJS | Firefox | File: Video player is in a tabulation order
- FIO-2979 ACC, FJS | File: Clicking on browse link or dragging and dropping files into the drag&drop area, explorer does not open / file is not uploaded causing 'Uncaught TypeError: uploadingProcess is null' error in a console
- FIO-2977 ACC, FJS | File: Browse link has no accessible name that contains File label, description and information about allowed file types
- FIO-2963 ACC, FJS | Bootstrap | Modal View: Change focus order of Cancel and Save buttons
- FIO-2962 ACC, FJS | Bootstrap | Well: No bottom margin
- FIO-2959 FJS | Required component with Label hidden will show bigger asterisk than original and moved to far right of screen
- FIO-2955 FJS | Validation error on nested Wizard
- FIO-2946 FJS | Validation not triggered when change "required" option in Logic tab
- FIO-2943 ACC | Regression | Bootstrap | Enter Data | Wizard Form: Cancel button is announced as Previous
- FIO-2927 FJS | 4.13.1 Regression | Tooltip: HTML Attributes in the tags break the tooltip rendering
- FIO-2917 ACC, FJS | Radio: No radio label, radio description, radio required announcements
- FIO-2903 FVP, FJS | Base and Project URLs are not being saved correctly on FVP.
- FIO-2890 ACC, FJS | Bootsrtap | Modal dialog window: Change buttons order
- FIO-2870 ACC, FJS | Bootstrap | Component Settings | Focus outline of Save, Cancel, Remove buttons is not fully visible in Components Settings window of Content component, when user focuses with Tab key
- FIO-2848 FJS | Display as Modal is causing required components inside of the edit grid to flicker when validating fields
- FIO-2831 FJS | 4.13.1 Regression | Edit Grid: When valid data is entered, the error disappears from error list, but Field in Edit Grid is still bordered red as invalid. When all errors of Edit Grid 1 are fixed, the errors of Edit Grid 2 are not showing
- FIO-2822 FJS | 4.13.1 Regression | Dynamic Wizard: Can put one DW inside another one when there is a DW on another wizard page
- FIO-2821 FJS | 4.13.1 Regression | Examples page: Submission View page: Customer and HTML5 Select field values do not display when rendered in HTML mode
- FIO-2819 FJS | Edit Grid: When 'Open First Row when Empty' setting is enabled, all the EG rows are deleted in the rendered form and I submit it, I'm getting no visual error but a 'ValidationError' in a console
- FIO-2811 FJS | 4.x Regression | Button: Button Custom logic does not work
- FIO-2810 FJS | Checkbox: When set to Radio input type, cannot unselect an option
- FIO-2794 ACC, FJS | Enter Data | Modal Edit: There is no announcement 'Modal window has been opened' when some components modal windows have opened
- FIO-2791 ACC, FJS | Bootsrtap | Date/Time: The input field does not take the entire page width
- FIO-2784 FJS | HTML tags in Label showing shows Error Message : Click to navigate to the field with following error." ref = "errorRef" tabIndex = "0", style = "cursor:pointer;" >
- FIO-2782 ACC | Bootsrtap | Change the initial focus element to the Close button in the Modal window on its opening
- FIO-2779 ACC, FJS | Bootsrtap | Change OnHover cursor style to the Hand pointer for the errors in the Error list
- FIO-2778 FJS | URL: Redundant 'Minimum Word Length' and 'Maximum Word Length' settings
- FIO-2777 ACC, FJS | Bootstrap | Insufficient color contrast of the components errors
- FIO-2773 ACC, FJS | Tooltips of component action buttons are too far from the buttons
- FIO-2770 ACC, FJS | Bootstrap | Modal and Confirmation windows | Text overlaps the Close buttons in both windows
- FIO-2769 ACC, FJS | Bootstrap | Modal and Confirmation windows | Contrast issues
- FIO-2768 ACC, FJS | Bootstrap | Pressing Wizard breadcrumbs buttons by Enter key, the page does not open
- FIO-2764 API, FJS | 7x | Ability to have the submission contain only data that you submitted via POSTMAN
- FIO-2757 ACC, FJS | 'Press Ctrl + Alt + X to go back to the error list.' announcement is missing when focusing on a component with an error when form validation is not met
- FIO-2756 ACC, FJS | Error list: 'Press Ctrl + Alt + X to go back to the error list.' tooltip does not display
- FIO-2755 ACC | Modal and Confirmation windows issues
- FIO-2753 ACC, FJS | Component Settings | Tabulation issues
- FIO-2752 FJS | Nested Form | Data Clearing inside of Data Grid when hitting the Add Another Button
- FIO-2734 ACC | Enter Data/Component Settings | Tooltips not focusing with keyboard
- FIO-2731 FJS | Unable to Disable Multiple Values on Number component
- FIO-2729 ACC | Enter Data/Component Settings | Panel: Collapsible Panel component doesn't collapse and expand
- FIO-2726 FJS | Date Time: Localization of the Calendar widget not working when logic is applied
- FIO-2721 FJS |  When there is data prepopulated in the nested Data Grid, it isn’t visible until the “Add Another” button is clicked.
- FIO-2681 FJS | Allow Type labels inside the File Component to be localized
- FIO-2676 FJS  | Conditionally showing columns are not auto-adjusting when auto adjust column is set to true
- FIO-2625 FJS | Data Grid: Get an infinite loop when changing the default values of the Data Grid components in the Data Grid. Fields are flickering
- FIO-2580 FJS | Examples page | Multi-Language Forms page: Español & 中文: Success message says 'complete' on submit
- FIO-2575 FJS | Examples page | Kitchen Sink: Address component has no red outline when there is an error
- FIO-2570 FJS | Examples page | Submission View: Select component: Value instead of a Label displays when the form renders as Plain Text
- FIO-2561 FJS | 4.13.0 Regression | Address: Address that has Modal Edit checked is not shown in error list. Error message doesn't disappear in modal window
- FIO-2554 FJS | Add the "Perform Server Validation" component property to the default schema and verify the default value is correct
- FIO-2541 ACC | Enter Data | Character counter covers border of Checkbox with tile
- FIO-2540 ACC | Enter Data | The Field Set, Columns, Well components resize when they are below the component with character counter.
- FIO-2534 FJS | Tree: Data of a Tree component inside another Tree component display as a JSON object. Should display as [Complex Data] instead
- FIO-2533 FJS | Tree: Data of all the components inside the Tree component displays in the Tree column in the Data table. Should be [Complex Data] instead
- FIO-2532 FJS | Tree: Edit submission: Click Edit button of the root data entry and then Cancel and you'll get an empty Tree component instead of changes have been cancelled
- FIO-2505 FJS | Data Grid: Signatures on different rows are not consistent in size
- FIO-2504 FJS | Panel component: Redundant settings for a non-wizard Panel component in a Wizard form
- FIO-2494 FJS | When the Logic to Hide is applied to a Wizard page, it does not work correctly, making the content of such a page be hidden but displaying the wizard page itself
- FIO-2492 FJS | When there is a component in one wizard page that has the same API key as the one on another wizard page where validation isn't met for some reasons, there will be misredirection from such an error in the Error list
- FIO-1946 ACC, FJS | Bootstrap ui framework accessibility support - Bootstrap templates
- FIO-1562 FJS | Radio button selection not persisting and is deselected on click
- FIO-1543 FJS | RenderMode: html is showing a - or blank when data is present.
- FIO-1537 FJS | Wizard | "Button click" does not work for wizards for the recaptcha component. Receiving an unauthorized Error on submit
- FIO-1525 FJS | Data Map: Empty value is displayed in the Submission data table for the Data Map with a 'Table View' setting enabled
- FIO-1513 FJS | Data Grid: Error message is shown only for the 1st row of components in Data Grid when custom validation is set up
- FIO-1500 FJS | Add Another | UX issue with validation messages triggering across all items, not just on empty/incomplete
- FIO-1488 FJS, PDF | Text Area: Quill: Unordered list renders as Ordered list in a PDF submission
- FIO-1434 FJS | Tree: Default value and Multiple values settings do not work
- FIO-1433 FJS | Checkbox: Custom default value set up via JavaScript does not work
- FIO-1405 FJS | Investigate why CheckValidity call when a series of dependent fields are on the page is not working
- FIO-1372 FJS | beforeNext hook not fired when form is rendered with readOnly flag
- FIO-1310 FJS | Exact Search option not always showing all available options in dropdown.
- FIO-1288 FJS | Height of Prefix and Suffix hasn't resized when height of Text Field, Text Area, Password fields has resized and Word/Character Counter is shown
- FIO-1224 FJS | Form Controller using instance.options.language = 'ar-SA' clearing existing form and receiving Uncaught (in promise) TypeError: Cannot read property '1' of null on edit tab
- FIO-1212 FJS | Equitable Life | Date/ Time using IE11 - The initial click into the Date Time or Calendar widget does not choose the date. The second click does.
- FIO-390 FJS | Tags- Placeholder text not showing up
- FIO-346 FJS | Firefox | Multiple Select fields/Tags showing ... after label. Example, if value is A, it shows as A...
- FIO-320 FJS | File component issues
- FIO-290 FJS | Ability to add tooltips for each survey row/column
- FIO-249 FJS | Tabs - Able to save tabs with identical API keys
- FIO-222 FJS | Upgrade react-formio 3.0.0 so that it uses json-logic-js 2.x version
- FIO-196 FJS | Limit and skip are not working for select components with URL Data source not loading by Default. Disable limiting checkbox might be not working
- FIO-175 FJS | Phone number field without formatting (1234567890) shows value correctly in the phone field, but validation fails until a character is changed
- FIO-124 FJS | Edit Grid: Data in the table shifts to the right when one of the components has a really long value (like a Text Area)

### New Features

- FIO-4295 Introduce Data Table to deployed Form Builder
- FIO-4239 Disable rendering child components when they are inside a hidden parent
- FIO-3649 FJS | Select component - debounce option for server side filtering
- FIO-3629 PRE | Data Table: Enable Inline Editing
- FIO-3628 PRE | Data Table: Enable Row labels
- FIO-3415 FJS | reCAPTCHA - Change 'Button Key' field to a select dropdown where user can select available buttons on form
- FIO-3227 FJS | Custom Select to allow our logic to handle asynchronous custom functions
- FIO-3224 PRE | Data Table: Enable ability to raise events from the grid by adding buttons to the data table which will render as buttons in the grid
- FIO-2860 Form.io/Signrequest Integration
- FIO-1422 FJS | Wizard: Add new setting 'Save On Enter' to wizard "Next" button
- FIO-1239 APP, FJS | Implement wizard header type selection
- FIO-1112 FJS | Tabs: Add 'Vertical' layout option for Tabs component


# November 19th, 2021 Release
## API Server Version 7.1.12
## PDF Server Version 3.3.1

### Included Correlated Libraries:
 - portal@7.2.12 
 - formviewpro@1.97.11
 - formmanager@1.97.11
 - formiojs@4.13.10
 - premium@1.17.0
 - offline@3.2.0
 - formio@2.2.6
 - uswds@2.4.1
 - vpat@2.4.1
 
### Tickets Included

- FIO-4250 API, APP, LIC | Regression | At times, I receive 'This is project has been disabled with the following message: Cannot read property 'terms' of undefined. Please correct the problem before continuing.' error when using a project
- FIO-4214 API | Fix roles interpolation within the SAML authentication
- FIO-4184 LIC | Investigate License receiving "Server is in Restricted Method Mode" Error
- FIO-4052 FJS | Investigate Custom component errors that derive from the "grid" components. The current way that this is handled is through our server side module system
- FIO-3798 FJS | Investigate issues with Customer's form when upgrading from 3x to 4x
- FIO-3590 React | “Save as Draft” functionality not working in order to pass saveDraft key using options object in Form component.
- FIO-3466 FMG | Access - Form Manager application where it is not reading the access controls correctly when the user is authenticated via SSO
- FIO-2958 FVP | Reorder Data Grid showing moving row below the submit button

### New Feature

- FIO-3786 FMG | Users mapped to “Authenticated” Submission Data Permissions are not being applied. “Update Own Submissions” and “Delete Own Submissions” are not shown on submission.
- FIO-3334 FJS | Ability to use the Number field with EU separators


# November 16th, 2021 Release
## API Server Version 7.2.3
## PDF Server Version 3.3.1

### Included Correlated Libraries:
 - portal@7.2.11 
 - formviewpro@1.97.10
 - formmanager@1.97.10
 - formiojs@4.13.9
 - premium@1.17.0
 - offline@3.2.0
 - formio@2.3.0
 - uswds@2.4.1
 - vpat@2.4.1
 
### Tickets Included

- FIO-4281 API | Regression | Cannot assign roles to form permissions
- FIO-4272 API | 7.2.3 Regression | General performance regression on 7.2.3
- FIO-4250 API, APP, LIC | Regression | At times, I receive 'This is project has been disabled with the following message: Cannot read property 'terms' of undefined. Please correct the problem before continuing.' error when using a project


# November 9th, 2021 Release
## API Server Version 7.2.2
## PDF Server Version 3.3.1

### Included Correlated Libraries:
 - portal@7.2.11 
 - formviewpro@1.97.10
 - formmanager@1.97.10
 - formiojs@4.13.9
 - premium@1.16.4
 - offline@3.2.0
 - formio@2.3.0
 - uswds@2.4.1
 - vpat@2.4.1
 
 **Update package json for the app 
 
### Tickets Included

- FIO-3971 API, SEC | Investigate and resolve Cross Site Scripting with SAML ACS



# November 8th, 2021 Release
## API Server Version 7.1.11
## PDF Server Version 3.3.1

### Included Correlated Libraries:
 - portal@7.2.11 
 - formviewpro@1.97.10
 - formmanager@1.97.10
 - formiojs@4.13.9
 - premium@1.16.4 
 - offline@3.2.0
 - formio@2.2.6
 - uswds@2.4.1
 - vpat@2.4.1
 
 **Update package json for the app 
 
### Tickets Included

- FIO-4137 API | When revisions were not enabled, the forms are now pointing to the “_fvid” #1 instead of the latest version
- FIO-4126 PDF | Regression | IE11 | Imported project: After uploading a new PDF file for a PDF form, the form does not load, throwing an error in a console: 'SCRIPT438: Object doesn't support property or method 'endsWith''
- FIO-4119 FJS | EditGrid | Fix Display as Modal as it is not working correctly
- FIO-4087 FJS | File | Multiple Value check makes Validation error show up twice
- FIO-4065 PDF, APP | Overlay components on PDF are shifting after importing a form embed url or project import with PDF first form
- FIO-3568 FJS | Uploading multiple files for single-value-file-component
- FIO-4106 API | Refactored so that any email address can be set as Reply-To
- FIO-3967 APP, PDF, FJS | Create PDF configurable option for Radio button and Check Boxes so that the background is shown or not


# October 30th, 2021 Release
## API Server Version 7.2.1
## PDF Server Version 3.3.0

### Included Correlated Libraries:
 - portal@7.2.10
 - formviewpro@1.97.9
 - formmanager@1.97.9
 - formiojs@4.13.8
 - premium@1.16.4
 - offline@3.2.0
 - formio@2.3.0
 - uswds@2.4.1
 - vpat@2.4.0
 
 
### Tickets Included

- Fixed issues with portal not working with portal subdomains.


# October 29th, 2021 Release
## API Server Version 7.2.0
## PDF Server Version 3.3.0

### Included Correlated Libraries:
 - portal@7.2.9
 - formviewpro@1.97.9
 - formmanager@1.97.9
 - formiojs@4.13.8
 - premium@1.16.4
 - offline@3.2.0
 - formio@2.3.0
 - uswds@2.4.1
 - vpat@2.4.0
 
 
### Tickets Included

- FIO-4191 APP | Regression | Form Settings button is missing and isn't clickable
- FIO-4172 PDF | Regression 3.3.0 | PDF download has incorrect view
- FIO-4137 API | When revisions were not enabled, the forms are now pointing to the “_fvid” #1 instead of the latest version
- FIO-4105 API | Tenant Manager | Unable to create Tenants
- FIO-4098 ACC | USWDS | Modal Edit: Error message isn't announced in Component modal window
- FIO-4095 APP | 7.2.0 Regression | Submission Collection - Collection Name is disabled.
- FIO-4082 ACC, FJS | USWDS| Checkbox renders incorrectly
- FIO-4065 PDF, APP | Overlay components on PDF are shifting after importing a form embed url or project import with PDF first form
- FIO-4041 API | Form not loading stylesheet and script
- FIO-4039 API | Regression | Address Component is not showing Search dropdown
- FIO-3994 APP | Regression | Unable to remove PDF using the x button on the builder
- FIO-3971 API, SEC | Investigate and resolve Cross Site Scripting with SAML ACS
- FIO-3958 SUB | GET all submissions within a form does not work with query parameters
- FIO-3953 API | Regression | Custom logo does not display in the header due to CSP settings
- FIO-3950 API | 7.2.0 Regression | Export JSON/CSV doesn't work on General Settings and Specific Component Settings
- FIO-3947 ACC | USWDS | Word count not showing remaining words
- FIO-3945 API | 7.2.0 Regression | Adding Teams to Projects are not saving
- FIO-3919 FVP | 1.98.0 Regression | GET https://remote-dev.form.io/ request is automatically sent every second when any form is loaded
- FIO-3914 API | Change the OAuth and SAML logins to minify the email so that team lookups work correctly
- FIO-3910 FJS | PDF overlay not showing up on Builder after upload
- FIO-3909 FJS | Unable to Drop components onto form builder
- FIO-3896 LIC | 7x License enable/disable issue
- FIO-3891 API | SQL Connector crashes when submitting a form
- FIO-3890 FJS | Row is not being referenced when fields are inside a Container inside EditGrid
- FIO-3885 API, LIC | License Utilization is counting a project against the license limit when a bogus project endpoint is entered in url
- FIO-3854 LIC, API, PDF | Customer system should never be affected within a 12 hour window of our services being down.
- FIO-3818 APP | PDF Management: When a new stage is copied from the stage that has PDF forms and PDF files, they do not display on PDF Management page, though they are returned in the response
- FIO-3783 API | Investigate Customer Email Template to see why component not showing inside of Template
- FIO-3780 SEC | No Rate limit on Password Reset Function
- FIO-3771 APP |  Receiving error when clicking Tenants UI Button
- FIO-3762 LIC | Empty stage is being reported on license utilization page when a stage is connected to a remote environment
- FIO-3708 APP | See Comments | Teams: When you are invited to a team, you no longer see the Reject Invitation button
- FIO-3659 FVP | Data from previous submission showing in new submission
- FIO-3655 PDF | 3.1.6 Regression | Columns display one below the other instead of displaying next to each other on PDF download
- FIO-3650 API, SEC | Resolve vulnerabilities
- FIO-3624 API | Investigate why x-token is no longer working and receiving message "No authentication token provided"
- FIO-3597 APP | Field Based Resource Access: Resources and Roles added to the Create Permission are automatically added to the Read Permission
- FIO-3593 APP, VUE | Review Sample Vue Form Embed Code and Resolve Issues
- FIO-3589 API | Review and Resolve Formio's Weekly Report by Snyk
- FIO-3584 APP | Teams: When adding a new member to a team, the INVITATION PENDING status does not display below the user email
- FIO-3500 FJS, PDF | FieldSet in a form longer than 1 pdf page will auto page break to page 2
- FIO-3447 PDF | Signature | Hide gray box next to PDF signatures
- FIO-3432 PDF | Text Area: Number of rows being displayed does not correspond to the number of rows configured to be displayed in settings
- FIO-3403 API | Project Export/Import is causing a false admin role to be added to role assignment action
- FIO-3369 API | Custom Collections not working on latest 7x (7.1.6)
- FIO-3329 APP | Teams - The Ability to make team emails case sensitive
- FIO-3302 API | Project settings not returned when queried by API key
- FIO-3208 ACC | USWDS | Enter Data | Description and Character Counter are showing not in one line
- FIO-3206 ACC | USWDS | Regression | Enter Data, Component settings | A big gap between Label of Input field and Asterisk or Tooltip in modal windows
- FIO-3198 API | Investigate why all access is removed when you update the project via api key or x-admin-key using a PUT request.
- FIO-3191 ACC | Container: Red background of component with error in Container in modal window remains when error is fixed
- FIO-3146 ACC | Radio, Select Boxes: 'Invalid entry' is still announced even when all errors are fixed
- FIO-3091 API | Ensure 7x server is compatible with Engine Version 4.0.0 of AWS Deployment
- FIO-3006 API | JavaScript heap out of memory
- FIO-2999 ACC | Radio: An error, an 'Invalid entry' message and a 'Press Ctrl+Alt+X to go back to the error list.' message are announced as a part of each radio option
- FIO-2961 ACC | Date/Time: 'Unhandled Promise rejection: calendar_1.calendarContainer is undefined' error in a console when saving a form with a Date/Time component inside
- FIO-2948 API | Investigate if responses to requests using API keys do not include the settings property stop working in 7x Server
- FIO-2921 LIC, API, PDF | Ensuring that a misconnection with the license server allows both the PDF server and API Server to continue to function without them.
- FIO-2897 ACC | Bootsrtap | Button: uswds button themes display in the Theme dropdown
- FIO-2894 ACC | Chrome/Jaws | Date/Time: Date/Time widget closing announcement is not read after selecting a value
- FIO-2893 ACC | Bootsrtap | IE11/Jaws | Date/Time: Date/Time widget closing announcement is read as an opening announcement when open a widget using Enter button
- FIO-2892 ACC | Bootstrap | All browsers/srs | Date/Time: Date/Time widget opening announcement is not read when open a widget using Enter button
- FIO-2833 APP | 7.1.3 Regression | Changing Form Access settings, a form JSON file becomes unminified
- FIO-2793 ACC | Bootsrtap | Date/Time: Grid of dates displays days with lots of excessive information
- FIO-2792 ACC | Bootsrtap | Date/Time: Date/Time title automatically changes on Calendar widget opening
- FIO-2772 ACC | Exclude the Dynamic Wizard from available components in the vpat since it hasn't been worked on to be accessible yet
- FIO-2758 ACC | Component Settings | Missing/excessive settings
- FIO-2715 FVP | When server (unique) validation is not met on submit, an [Object object] status message shows up
- FIO-2685 FJS | Wizard: Previously selected radio component not showing “radio-selected” on elements log after going back to it
- FIO-2662 PRE | Data Source | Fetch Tab Remove the Put, Patch and Delete Options from the Method dropdown
- FIO-2660 React | When using formio/react inside a component, every time the parent component change, formio/react is destroyed and recreated.
- FIO-2652 API | Remove Authoring Mode
- FIO-2598 FMG, FVP | Regression | Table component does not render correctly. Horizontal scroll displays all the time. First column components are cut off
- FIO-2565 FJS | Wizard | First Page Tooltip data is not showing initially.
- FIO-2563 API | Role Assignment Action not working
- FIO-2546 ACC | Component Settings | Focus outline of Save, Cancel, Remove buttons is not fully visible in Components Settings window of Content component, when user focuses with Tab key
- FIO-2544 ACC | Component Settings, Enter Data | On a big scale suffixes and prefixes moves under and over the input correspondingly
- FIO-2535 ACC | Enter Data | When component has Modal edit view, part of buttons Save and Cancel are outside of modal window
- FIO-2523 ACC | Firefox | Enter Data | Inappropriate focus outline when Checkbox, Select boxes, Radio components are in focus
- FIO-1565 API | Revisions: Making changes to a Form with Revisions enabled, the user is displayed as "anonymous". Want to show email of the user from FMG that made the change
- FIO-1536 API | Allow endpoint on API server to provide submission JSON to generate PDF
- FIO-1528 API | Deployment | Change default 'from' email address domain to use 'example' instead of 'form.io' in the deployment environment variable
- FIO-1475 API | 7.1.0 Regression | Teams: Unable to add Teams to a project I own that were created prior to 7.1.0 build
FIO-1474 APP | Revisions - When I have made a revision changing 'Form Settings', the 'Form Settings' configurations do not revert when I restore a previous form revision
- FIO-1416 APP | 7.1.0 Regression | Created Team using 7.1.0 | When you search for the team inside of the teams tab in Project you should see the amount of members in the team. You do not.
- FIO-1310 FJS | Exact Search option not always showing all available options in dropdown.
- FIO-1246 API | 7.0.0 Regression | On-Premise Environment | After submitting an editted web or PDF form with a new value of a password field, network request fails. Could not connect to API server for several minutes after that
- FIO-1227 FJS | Link inside Component to redirect to help section of that component is broken
- FIO-889 API | QQL form.io Solution Penetration Test Report Issue #4-R8:  Implement HTTP Strict-Transport-Security
- FIO-885 API | Ensure we place queries within a "try catch" block to make sure the server does not crash when the Database throws an error.
- FIO-841 API, LIC | 7x License Server | Implement Dev License
- FIO-805 API, SEC | Read ALL permission should not include actions (including Read All permission on project level)
- FIO-790 API | CSV Checkbox set as Radio showing blank on CSV downloads
- FIO-761 FOR-2888 | (Github) Server throws 'Error: cyclic dependency detected' when calling Webhook action
- FIO-716 FMG | After saving any changes to the PDF form, a new GET files.form.io API call is sent to the server and the PDF form is reloaded
- FIO-510 PDF | HTML is coming out as code rather than viewable. format=html on PDF is not outputting the viewer
- FIO-468 APP | Improve Action Logs
- FIO-285 APP | No confirmation pop-up shows up when deleting a submission from the Data table
- FIO-223 API | File Component inside of an Edit Grid does not show up correctly on Email Action and does not show up as attached.
- FIO-222 FJS | Upgrade react-formio 3.0.0 so that it uses json-logic-js 2.x version
- FIO-168 FJS | IE11 | Select Preview is not working
- FIO-3841 API | Ability to interpolate the project, form, _id, and any other fields from a submission into a web hook URL
- FIO-3678 APP, API | Add ability to specify path to 'email' property of user object in OAuth OpenID settings
- FIO-3575 API | Force CORS restrictions to ONLY allow “localhost” applications to connect to it
- FIO-3436 API | Ability to set reply-to email field header to allow quick response from received emails.
- FIO-3145 ACC, FMG | Add the possibility to switch between bootstrap and uswds templates in public configurations
- FIO-1368 APP, API | Enable Communication from portal to server to report domain on which the portal is running
- FIO-919 API | Health Check Endpoint
- FIO-899 API | Unable to remove roles assigned from a group using PUT request
- FIO-665 FVP | Add ability to set auto process of offline queue when reconnected
- FIO-569 PDF | Add option to choose Portrait or Landscape in Form Settings for PDF generation
- FIO-4137 API | When revisions were not enabled, the forms are now pointing to the “_fvid” #1 instead of the latest version
- FIO-4065 PDF, APP | Overlay components on PDF are shifting after importing a form embed url or project import with PDF first form

# October 18th, 2021 Release
## API Server Version 7.1.10
## PDF Server Version 3.2.3

### Included Correlated Libraries:
 - portal@7.2.8
 - formviewpro@1.97.8
 - formmanager@1.97.8
 - formiojs@4.13.8
 - premium@1.16.4
 - offline@3.2.0
 - formio@2.2.5
 - uswds@2.4.0
 - vpat@2.4.0
 
 
### Tickets Included

- FIO-4061 FVP | 1.97.8 Regression | Offline mode: Going offline and than back online, the connection indicator stays orange indicating the FVP is offline
- FIO-4058 PDF | 3.2.3 Regression | Importing a PDF test stage and changing the PDF file for PDF forms, all the components' layouts shrink in size, the form does not fully load, and I get an error in a console
- FIO-4045 FVP  | Offline Mode not loading existing online submissions and receiving 'unable to submit the form' message. Offline submissions do not load correctly as well
- FIO-4034 FJS | Calculated values are triggering before conditionally displayed fields preventing data calculation
- FIO-3990 USWDS | Checkboxes inside of Data Grid with more than 1 row are only checking/ unchecking the first-row Checkbox regardless of which rows checkbox you click.
- FIO-3971 SEC | Investigate and resolve Cross Site Scripting with SAML ACS
- FIO-3952 FMG | 1.97.7, 1.98.0 Regression | Cannot make a PDF download on a newly created project. Get Unauthorized error when make a call
- FIO-3950 API | 7.2.0 Regression | Export JSON/CSV doesn't work on General Settings and Specific Component Settings
- FIO-3948 FJS |  Edit Grid | Saving two items in an edit grid with the second created saved first, then editing the second created one, the data is overwritten to the first created
- FIO-3919 FVP | 1.98.0 Regression | GET request is automatically sent every second when any form is loaded
- FIO-3893 API | Investigate API Server crash when using SQL Connector
- FIO-3837 FJS | Conditionally showing components are going back to the default values on submission
- FIO-3778 ACC, PDF | PDF download: Sketchpad: Sketchpad drawings display on each page of PDF download. They don't display in the correct place where the Skethpad is
- FIO-3772 PDF | When columns component has the auto adjust columns setting set to true, components inside of the columns do not show up on PDF.
- FIO-3758 FJS | If multiple Edit Grids are open, then the Radios inside of Edit Grid #2 are not getting set correctly.
- FIO-3674 FJS, PDF | PDF form: Conditionally shown field does not show up when the logic is met on a customer form
- FIO-3670 FJS | Select: Selects flickers between label and value when typing in other fields. I get 'TypeError: data.minMax is undefined' error in a console
- FIO-3659 FVP | Data from previous submission showing in new submission
- FIO-3657 FJS | Fields do not appear to be calculating in the client, though the calculation seem to happen on the server and the calculated values display in submission
- FIO-3656 ACC | Columns are not auto collapsing when components inside of them are hidden
- FIO-3645 FJS | 'Textfield' calendar widget to lose focus when tabbing/clicking into field
- FIO-3488 FJS | Caluclated fields not triggering on form load properly when submission JSON is set
- FIO-2989 API, FJS | OpenID receiving 404 - Couldn't connect to API
- FIO-2880 PDF | 3.2.2 Regression | Text Field: Calendar widget: value is not consistent in submission and PDF download for different timezone cases
- FIO-2867 PDF | Overlay text from initial PDF download into project not saving
- FIO-1310 FJS | Exact Search option not always showing all available options in dropdown.

### New Feature

- FIO-3770 PDF | Allow for PDF migration work with Project Import as well as Single form imports via Form Embed URL
- FIO-3678 API | Add ability to specify path to 'email' property of user object in OAuth OpenID settings
- FIO-3436 APP, API | Ability to set reply-to email field header to allow quick response from received emails.
- FIO-665 FVP | Add ability to set auto process of offline queue when reconnected


# September 29th, 2021 Release
## API Server Version 6.11.11
## PDF Server Version 3.2.2

### Included Correlated Libraries:
 - portal@7.0.46
 - formviewpro@1.97.7
 - formmanager@1.97.7
 - formiojs@4.13.7
 - premium@1.16.4
 - offline@3.1.1
 - formio@1.91.8
 
 
### Tickets Included
- FIO-4029 API | Unable to Create TEAMS. Receiving Unauthorized Error
- FIO-3980 API | Receiving Bad Request on Exporting CSV data with Select Component
- FIO-3978 PDF | PDF download are not downloading correctly. Showing code instead of Values.
- FIO-3950 API | 7.2.0 Regression | Export JSON/CSV doesn't work on General Settings and Specific Component Settings
- FIO-3935 FJS | Day | When Month is set to Select and data is inserted and then removed, the data still persists on submit
- FIO-3724 API | Email | Mailgun Emails are not attaching PDFs.
- FIO-3595 FVP | Unable to submit form in offline mode. Error is showing or Submit button is just spinning.
- FIO-2880 PDF | 3.2.2 Regression | Text Field: Calendar widget: value is not consistent in submission and PDF download for different timezone cases
- FIO-510 PDF | HTML is coming out as code rather than viewable. format=html on PDF is not outputting the viewer




# September 17th, 2021 Release
## API Server Version 6.11.10
## PDF Server Version 3.2.1

### Included Correlated Libraries:
 - portal@7.0.40
 - formviewpro@1.97.6
 - formmanager@1.97.6
 - formiojs@4.13.6
 - premium@1.16.4
 - offline@3.1.1
 - formio@1.91.7
 
 
### Tickets Included
- FIO-3881 PDF, API | 3.2.1 Regression | I can surpass the Submission PDFs limit and make more than 1000 PDF downloads
- FIO-3877 PDF, API | 3.2.1 Regression | I can surpass the PDF Forms limit and create more than 25 PDF Forms
- FIO-3874 PDF | 3.2.1 Regression | Unable to download PDFs when I have 10 available PDF downloads on any project plan
- FIO-3824 PDF | PDF 2x renderer is missing text
- FIO-3823 FJS | Receiving ReCaptcha: Response token not found on submission.
- FIO-3736 PDF | 3.2.0 Regression | Get 'PDF file not found' when trying to make a PDF download of a web or wizard form. Works fine with a PDF form
- FIO-3727 NFP, PDF | Not able to upload a PDF file when the PDF server is not set up, it works fine on portal.form.io though
- FIO-3663 FJS | Unable to drag and drop components into a data grid with a certain combination
- FIO-3662 PDF | Investigate EROFS: read-only file system, open '/tmp/3fc1ac34d3f234109aadd808e724fcd' error when trying to upload a PDF file for form creation or downloading PDF file
- FIO-3641 PDF | Fixing issues where the pdf server could crash on evaluate exception
- FIO-3601 PDF | 2.97.5 Regression | Uploading a PDF file or checking PDF server version, I get '503 Service Unavailable: Back-end server is at capacity` error
- FIO-3562 PDF | 3.1.5 Regression | Inconsistency with Components loading on PDF download
- FIO-3561 FJS | 4.13.5 Regression | Data Grid | Filled required field is showing as invalid and form can't be submitted
- FIO-3538 PDF |  3.1.5 Regression | Text field data that contains letters isn't showing and data that contains digits is showing as Date in PDF download
- FIO-3414 FJS | Edit Grid | Investigate why Add Another Repaired Inspection button stopped working. The section gets removed immediately after the user adds it.
- FIO-3413 FJS | Investigate why Data is immediately clearing after insert
- FIO-3250 PDF | Disabled PDF checkbox is displayed when using form
- FIO-3213 API | Need to create choices.js patch to fix the problem on Windows Server 2016 using IE11
- FIO-3116 API | File components are not being attached to emails when file component is inside Container and are being shown as undefined once clicked on using the email link
- FIO-3083 FJS | Conditional component not re-showing if you change a component value to make it untrue and then change the value again to make it true
- FIO-3032 API | Investigate issue with API Server 6.11.0 TypeError: "Cannot read property 'name' of undefined"
- FIO-2998 PDF | Unsigned Signatures should show blank and not "Click to sign" on PDF download
- FIO-2907 ACC | Sketchpad component: Accessibility issues
- FIO-2906 ACC | Data Grid: Accessibility issues
- FIO-2905 ACC | Ability to add hidden label for the html input
- FIO-2880 FJS | 3.1.6 Regression | Text Field: Calendar widget: value is not consistent in submission and PDF download for different timezone cases
- FIO-2759 ACC | Bootstrap | Wizard | Change the button order of wizard buttons
- FIO-2104 FJS | Initially Collapsed Panel component isn't focusable with Tab key
- FIO-1462 PDF | 3.0.0, 3.1.0 Regression | PDF settings: When Landscape mode is selected, the form still renders in a Portrait mode
- FIO-898 API | Form.io does not provide post headers (X-Forwarded-For) for user IP from browser submission
- FIO-565 PDF | PDF Server not rendering PDF correctly. Sections of PDF are not being seen due to overlapping issues.
- FIO-254 FJS | Add the ability to interpolate the address URL
- FIO-3109 ACC | Set the focus to the new row when adding a new row in a Datagrid
- FIO-569 PDF | Add option to choose Portrait or Landscape in Form Settings for PDF generation






# September 16th, 2021 Release
## API Server Version 7.1.9
## PDF Server Version 3.1.6

### Included Correlated Libraries:
 - portal@7.2.7 
 - formviewpro@1.97.6
 - formmanager@1.97.6
 - formiojs@4.13.6
 - premium@1.16.4
 - offline@3.1.1
 - formio@2.2.4
 - uswds@2.3.8
 - vpat@2.3.4

### Tickets Included
- FIO-3213 API | Need to create choices.js patch to fix the problem on Windows Server 2016 using IE11


# September 2nd, 2021 Release
## API Server Version 7.1.8
## PDF Server Version 3.1.6

### Included Correlated Libraries:
 - portal@7.2.6
 - formviewpro@1.97.6
 - formmanager@1.97.5
 - formiojs@4.13.5
 - premium@1.16.4
 - offline@3.1.1
 - formio@2.2.4
 - uswds@2.3.8
 - vpat@2.3.4


### Tickets Included
- FIO-3691 APP | Regression 7.1.8 | After Deploying a new version onto a stage, the page does not redirect and update the version
- FIO-3689 PDF | Unable to download PDF submission when migrated from another stage
- FIO-3676 PDF | 7.1.8 Regression | Uploaded PDFs are not shown in PDF management page
- FIO-3632 FJS | Unable to submit customer form, receiving an empty validation message upon submission
- FIO-3624 API | Investigate why x-token is no longer working and receiving message "No authentication token provided"
- FIO-3500 PDF | FieldSet in a form longer than 1 pdf page will auto page break to page 2
- FIO-584 PDF | Enable PDF files between environments with Stage Deployments
- FIO-3692 PDF | Enable SSL Layer on top of Docker Container
- FIO-2736 API | Enable SSL Layer on top of Docker Container



# August 31th, 2021 Release
## PDF Server Version 3.1.6


### Tickets Included
- FIO-3784 PDF | Unable to upload PDFs on 3.1.6-rc.5 (0x50c48f is not a constructor)
- FIO-3655 PDF | 3.1.6 Regression | Columns display one below the other instead of displaying next to each other on PDF download
- FIO-3641 PDF | Fixing issues where the pdf server could crash on evaluate exception
- FIO-3500 PDF | FieldSet in a form longer than 1 pdf page will auto page break to page 2
- FIO-2880 FJS | 3.1.6 Regression | Text Field: Calendar widget: value is not consistent in submission and PDF download for different timezone cases
- FIO-634 PDF | Regression 3.0.0 | File: When 'Display as Image' is enabled and a file is selected, the 'Remove' button does not display on a PDF form
- FIO-506 PDF | 3.1.6 Regression | PDF download: Date/Time is 6-7 hours off


# August 6th, 2021 Release
## API Server Version 7.1.7
## PDF Server Version 3.1.5

### Included Correlated Libraries:
 - portal@7.2.5
 - formviewpro@1.97.5
 - formmanager@1.97.5
 - formiojs@4.13.5
 - premium@1.16.4
 - offline@3.1.1
 - formio@2.2.3
 - uswds@2.3.8
 - vpat@2.3.2.4


### Tickets Included

- FIO-3617 API, FJS, PDF | 7.1.7 Regression | When I make a PDF download of the form with Select Resource or Resource component, and the form has the 'View as Plain Text' setting enabled, the server crashes
- FIO-3602 PDF | 3.1.5 Regression | Unable to upload a PDF or check PDF status endpoint
- FIO-3600 API | 7.1.7 Regression | '502 Bad Gateway' when loading portal
- FIO-3598 ACC, FMG, FVP | Checkbox: Checkbox doesn't have focus outline and marked checkbox isn't visible in FMG and FVP with VPAT module. Checkbox, Select Boxes, Radio components have white background in Component Settings
- FIO-3596 PDF Server fails to launch if it connected to a fresh DB in Multicontainer Deployments
- FIO-3570 FJS | 4.13.5 Regression | Edit Grid: Form cannot be submitted and empty error is showing if Edit Grid has Open First Row when Empty checked
- FIO-3565 FJS | 4.13.5 Regression | Tree: Form with Tree component cannot be submitted
- FIO-3562 PDF | 3.1.5 Regression | Inconsistency with Components loading on PDF download
- FIO-3561 FJS | 4.13.5 Regression | Data Grid | Filled required field is showing as invalid and form can't be submitted
- FIO-3545 PDF | Page Breaks using Tabs
- FIO-3538 PDF |  3.1.5 Regression | Text field data that contains letters isn't showing and data that contains digits is showing as Date in PDF download
- FIO-3478 API | 7.1.7-rc.3 Unable to drag and drop fields in builder mode
- FIO-3476 FJS | Unable to drop components in builder mode with a combination of certain layout components
- FIO-3471 SEC | Ensure that the queries include all indexes to speed up performance.
- FIO-3462 SEC | Fix server vulnerabilities with maillgun
- FIO-3441 SEC | Resolve vulnerabilities
- FIO-3414 FJS | Edit Grid | Investigate why Add Another Repaired Inspection button stopped working. The section gets removed immediately after the user adds it.
- FIO-3413 FJS | Investigate why Data is immediately clearing after insert
- FIO-3405 ACC | FVP | Validation Error Messages still show after validation is met. Submission still works.
- FIO-3400 LIC | Investigate issues with running remote license against 7.1.5 version
- FIO-3370 API | Oauth Registration is causing server crashes when submitted
- FIO-3367 FJS, PDF | 4.13.3, 3.1.4 Regression | Resource Select: When default value has been changed and submitted, it still displays in the PDF download though
- FIO-3284 API | Investigate if the PORTAL_SSO_LOGOUT environment variable also sets the PORTAL_SSO variable
- FIO-3264 API | Remove the following error from the console
- FIO-3259 API | Investigate LDAP functionality on 7.1.4.
- FIO-3251 FJS | Issue with calculation on conditionally hidden field
- FIO-3250 PDF | Disabled PDF checkbox is displayed when using form
- FIO-3242 FJS | Logic causing infinite loop
- FIO-3210 ACC | Issue with the button display - styles being applied to both div and button
- FIO-3119 PDF | PDF download: When a form is rendered through the uswds-viewer, a 'powered by <form.io>' text displays twice at the end of the PDF, even though the 'branding' is set to false
- FIO-3116 API | File components are not being attached to emails when file component is inside Container and are being shown as undefined once clicked on using the email link
- FIO-3083 FJS | Conditional component not re-showing if you change a component value to make it untrue and then change the value again to make it true
- FIO-3026 ACC | Required field message showing up even after field is no longer required based on logic
- FIO-2998 PDF | Unsigned Signatures should show blank and not "Click to sign" on PDF download
- FIO-2997 PDF | Unchecked Checkboxes show on PDF download
- FIO-2907 ACC | Sketchpad component: Accessibility issues
- FIO-2906 ACC | Data Grid: Accessibility issues
- FIO-2905 ACC | Ability to add hidden label for the html input
- FIO-2885 Deploying to AKS currently requires root level access which causes security concerns.
- FIO-2880 FJS | Text Field: Calendar widget: value is not consistent in submission and PDF download for different timezone cases
- FIO-2834 (github issue) CSV Export - When exporting CSV submissions, uploaded files are displaying as "" in export
- FIO-2759 ACC | Bootstrap | Wizard | Change the button order of wizard buttons
- FIO-2104 FJS | Initially Collapsed Panel component isn't focusable with Tab key
- FIO-1627 ACC | Wizard: Wizard panel-pages do not render tooltips
- FIO-1462 PDF | 3.0.0, 3.1.0 Regression | PDF settings: When Landscape mode is selected, the form still renders in a Portrait mode
- FIO-1371 API, LIC | Investigate issue with Failing License
- FIO-1310 FJS | Exact Search option not always showing all available options in dropdown.
- FIO-1026 FOR-2444 | API | When creating a new stage or tenant, allow selecting which stage to copy from (instead of only live)
- FIO-898 API | Form.io does not provide post headers (X-Forwarded-For) for user IP from browser submission
- FIO-586 PDF-193 | Regression 3.0.0 | Error text does not fully display under the field for all the components
- FIO-3109 ACC | Set the focus to the new row when adding a new row in a Datagrid
- FIO-3099 API | Implement Oauth provider
- FIO-2914 Read Comments API | Allow custom component validation to work on API Server
- FIO-2557 PDF  | Automatically configure the base url of submissions generated with the pdf viewer
- FIO-1566 PDF | ECB | Ability to create global headers and footers


# July 16th, 2021 Release
## API Server Version 6.11.9
## PDF Server Version 2.97.4

### Included Correlated Libraries:
 - portal@7.0.44
 - formviewpro@1.97.4
 - formmanager@1.97.3
 - formiojs@4.13.3
 - premium@1.16.3
 - offline@3.1.1
 - formio@1.91.6 
 
### Tickets Included
- No tickets included



# July 14th, 2021 Release
## API Server Version 6.11.8
## PDF Server Version 2.97.4

### Included Correlated Libraries:
 - portal@7.0.38
 - formviewpro@1.97.4 
 - formmanager@1.97.3
 - formiojs@4.13.3 
 - premium@1.16.3
 - offline@3.1.1
 - formio@1.91.5

### Tickets Included
- FIO-3471 SEC | Ensure that the queries include all indexes to speed up performance.
- FIO-3089 FJS | Receiving Validation error on Number component with no validations
- FIO-644 7x/6x PDF 16 | Teams - PDF - Unable to upload/create PDF form as a WRITE team member.



# July 13th, 2021 2nd Release
## API Server Version 7.1.6-patch.2
## PDF Server Version 3.1.4

### Included Correlated Libraries:
 - portal@7.2.4-patch.1
 - formviewpro@1.97.4
 - formmanager@1.97.4
 - formiojs@4.13.4
 - premium@1.16.3
 - offline@3.1.1
 - formio@2.2.2
 - uswds@2.3.4 
 - vpat@2.3.3


### Tickets Included
- FIO-3477 API | Legacy SSO teams are not showing up for users on portal
- FIO-3213 API | Need to create choices.js patch to fix the problem on Windows Server 2016 using IE11



# July 12th, 2021 Release
## API Server Version 6.11.7
## PDF Server Version 2.97.4

### Included Correlated Libraries:
 - portal@7.0.44
 - formviewpro@1.97.4
 - formmanager@1.97.3
 - formiojs@4.13.3
 - premium@1.16.3
 - offline@3.1.1
 - formio@1.91.4 
 
 

### Tickets Included

- FIO-3429 PDF | API | Date Time data not showing on PDF download using Webform, Wizard or PDF
- FIO-3425 PDF | Resource Selects are not showing on webform PDF download
- FIO-3423 PDF | 3.1.4 Regression | When the form is submitted with a Date/Time component that has a default value, there will be a spinner and the '<form.io> Form Viewer' text instead of the form title in the PDF download
- FIO-3421 PDF | 3.1.4 Regression | When conditional logic to hide and then show components is met, the components do not show up after being hidden
- FIO-3420 PDF | 3.1.4 Regression | Checkbox (Radio type): Selected checkbox (radio button) does not show up in a PDF download
- FIO-3407 PDF | When there is no HTML Element in the PDF form, all the other components except Signature and File display empty values in the PDF download
- FIO-3389 PDF | Signature | Have the signature component render the signature in the exact proportions as it was captured
- FIO-3371 PDF | 3.1.4 Regression | Resource: Cannot make a PDF download when there is a Resource component in the form
- FIO-3352 PDF | 3.1.4 Regression | When no theme is applied, some components are too wide in PDF download
- FIO-3351 PDF | 3.1.4 Regression | Tagpad: Cannot make a PDF download of a form with a Tagpad component
- FIO-3342 FJS | 4.13.3 Regression | Date/Time: When 'Multiple Values' setting is enabled, values display as '0NaN-aN-aN 12:aN AM' in a View a Submission page
- FIO-3323 FJS | 4.13.3 Regression | Data Grid: The width of column with Remove button is quite wide
- FIO-3318 PDF | 3.1.4-rc.1 Regression | Select - Unable to download webform PDF when I have a Select Resource on form
- FIO-3285 API | Investigate lodash.cloneDeep having very very long response time , which is causing "The user aborted a request" Issue
- FIO-3256 PDF | Warning message for a checkbox now show vertically; previously (last week) it was showing horizontally.
- FIO-3254 FJS | 4.13.2 Regression | Select, Select Boxes, Radio, Survey: Changes made to option values do not persist on component save
- FIO-3248 PDF | Gray overlay box is transparent when PDF overlay field is focused
- FIO-3246 PDF | Overlay validation messages are displayed behind other overlay fields
- FIO-3244 PDF | Signature overlay is expanding size when saving Signature data
- FIO-3229 FJS | PDF | Checkbox | When View as Plain Text is set to True on PDF settings, Checkbox shows as FALSE even when TRUE.
- FIO-3187 FJS, PDF | 3.1.3, 2.97.0 Regression | Date/Time: At times values don't display in submission and/or PDF download
- FIO-3090 FJS | When clicking on the name of the radio in a conditionally showing data grid, it is not targeting the second instance of the radio component, and is instead targeting the first instance of the radio component
- FIO-3006 API | JavaScript heap out of memory
- FIO-2922 API | Investigate production server crashes
- FIO-2888 API | ReCaptcha: Token is not specified in submission
- FIO-1453 7x/6x API | PHSA | When you re-import an updated parent form from a tenant to a stage, the linkage breaks








# July 1st, 2021 Release
## API Server Version 7.1.6
## PDF Server Version 3.1.4

### Included Correlated Libraries:
 - portal@7.2.4
 - formviewpro@1.97.3
 - formmanager@1.97.3
 - formiojs@4.13.3  
 - premium@1.16.3 
 - offline@3.1.1
 - formio@2.2.2 
 - uswds@2.3.3 
 - vpat@2.3.2


### Tickets Included

- FIO-3429 PDF | API | Date Time data not showing on PDF download using Webform, Wizard or PDF
- FIO-3425 PDF | Resource Selects are not showing on webform PDF download
- FIO-3423 PDF | 3.1.4 Regression | When the form is submitted with a Date/Time component that has a default value, there will be a spinner and the '<form.io> Form Viewer' text instead of the form title in the PDF download
- FIO-3421 PDF | 3.1.4 Regression | When conditional logic to hide and then show components is met, the components do not show up after being hidden
- FIO-3420 PDF | 3.1.4 Regression | Checkbox (Radio type): Selected checkbox (radio button) does not show up in a PDF download
- FIO-3407 PDF | When there is no HTML Element in the PDF form, all the other components except Signature and File display empty values in the PDF download
- FIO-3389 PDF | Signature | Have the signature component render the signature in the exact proportions as it was captured
- FIO-3371 PDF | 3.1.4 Regression | Resource: Cannot make a PDF download when there is a Resource component in the form
- FIO-3369 API | Custom Collections not working on latest 7x (7.1.6)
- FIO-3352 PDF | 3.1.4 Regression | When no theme is applied, some components are too wide in PDF download
- FIO-3351 PDF | 3.1.4 Regression | Tagpad: Cannot make a PDF download of a form with a Tagpad component
- FIO-3342 FJS | 4.13.3 Regression | Date/Time: When 'Multiple Values' setting is enabled, values display as '0NaN-aN-aN 12:aN AM' in a View a Submission page
- FIO-3337 FVP | TypeError: Failed to register a ServiceWorker for scope ('https://epmform.olmapps.com/') with script ('https://epmform.olmapps.com/ngsw-worker.js'): A bad HTTP response code (401) was received when fetching the script.
- FIO-3328 FMG | SAML login issue with not redirecting to Form Manager App
- FIO-3323 FJS | 4.13.3 Regression | Data Grid: The width of column with Remove button is quite wide
- FIO-3318 PDF | 3.1.4-rc.1 Regression | Select - Unable to download webform PDF when I have a Select Resource on form
- FIO-3309 FJS | Unable to get property 'contains' of undefined or null reference when using the CalendarWidget using IE11
- FIO-3303 FJS, PDF | Text Area: CKEditor: Table does not render correctly when vieweing submission and in PDF download
- FIO-3285 API | Investigate lodash.cloneDeep having very very long response time , which is causing "The user aborted a request" Issue
- FIO-3283 FJS | Edit Grid, Dynamic Wizard: No error message about non-unique API keys display below the components in the form
- FIO-3275 API | Patch the Nunjucks template execution vulnerability
- FIO-3256 PDF | Warning message for a checkbox now show vertically; previously (last week) it was showing horizontally.
- FIO-3254 FJS | 4.13.2 Regression | Select, Select Boxes, Radio, Survey: Changes made to option values do not persist on component save
- FIO-3248 PDF | Gray overlay box is transparent when PDF overlay field is focused
- FIO-3246 PDF | Overlay validation messages are displayed behind other overlay fields
- FIO-3244 PDF | Signature overlay is expanding size when saving Signature data
- FIO-3237 PDF | Images on PDF not showing on PDF downloads
- FIO-3229 FJS | PDF | Checkbox | When View as Plain Text is set to True on PDF settings, Checkbox shows as FALSE even when TRUE.
- FIO-3225 FMG | SAML login issue with Form Manager App
- FIO-3212 API | Fixing the OpenID access token for Active Directory. #844
- FIO-3192 API | Remove UI window when deploying stage versions with PDF
- FIO-3187 FJS, PDF | 3.1.3, 2.97.0 Regression | Date/Time: At times values don't display in submission and/or PDF download
- FIO-3139 API | Teams: When Administrator User removes himself from the Team by clicking on 'Remove from team' button, and then it gets invited again, there will be no invitation, and the User will be automatically invited
- FIO-3114 FJS | Property name not adding numbers to components when the component is inside of a column, which is inside of a field set, inside of a DG, inside a panel
- FIO-3104 PDF | CSS-classes of USA buttons display in a submission rendered as a PDF through the uswds-viewer
- FIO-3095 SEC | Abusing in-built functionality leading to complete victim account takeover.
- FIO-3090 FJS | When clicking on the name of the radio in a conditionally showing data grid, it is not targeting the second instance of the radio component, and is instead targeting the first instance of the radio component
- FIO-3088 FJS | DataSource when using a DataGrid is not showing data when the form is nested
- FIO-3081 API | Receiving Error "The user aborted a request" when calling form definition
- FIO-3040 API | Handle the Webhook error and respond instead of spinning forever.
- FIO-2997 PDF | Unchecked Checkboxes show on PDF download
- FIO-2922 API | Investigate production server crashes
- FIO-2888 API | ReCaptcha: Token is not specified in submission
- FIO-2869 FVP | Custom components not showing up on FVP
- FIO-2844 API | Token Swap being called twice
- FIO-2824 FJS | Number | Remove Spellcheck setting for Number Component
- FIO-2710 FJS | Sketchpad: Height and width settings do not reflect on the form. Setting up any values, you’ll get the same result on the rendered form
- FIO-2675 PDF| S3/Azure | File Component | Files that have the display as image set to true are not being shown on PDF download
- FIO-3113 PDF | Make the PDF server throw an error if the PDF is not loading instead of generating a pdf with just a loader
- FIO-3087 FJS | Prevent user from dragging and dropping disabled components while PDF is loading in builder mode
- FIO-3041 APP | Allow the user name in portal to be changed with SSO.



# June 2nd, 2021 Release
## API Server Version 7.1.5
## PDF Server Version 3.1.3

### Included Correlated Libraries:
 - portal@7.2.3
 - formviewpro@1.97.2
 - formmanager@1.97.2
 - formiojs@4.13.2
 - premium@1.16.2
 - offline@3.1.1
 - formio@2.2.1
 - uswds@2.3.2
 - vpat@2.3.2

### Tickets Included
- FIO-3117 PDF | Manual Page Break is causing components outside of panels to minimize in size
- FIO-3006 API | JavaScript heap out of memory
- FIO-2989 API | OpenID receiving 404 - Couldn't connect to API


# May 27th, 2021 Release
## API Server Version 7.1.4
## PDF Server Version 3.1.2

### Included Correlated Libraries:
 - portal@7.2.3
 - formviewpro@1.97.2
 - formmanager@1.97.2
 - formiojs@4.13.2
 - premium@1.16.2
 - offline@3.1.1
 - formio@2.2.1
 - uswds@2.3.2
 - vpat@2.3.2

### Tickets Included
- FIO-3086 FJS | 4.13.2 Regression | Total value isn't recalculated when the form is edited
- FIO-3084 FMG | FormManager not loading using 7.1.4-rc.2
- FIO-3012 PDF | Excess page breaks when generating a PDF file through uswds-viewer
- FIO-2992 PDF | Manual Page Break not causing page break, and is causing Panels to mimimize in size
- FIO-2936 FJS | Receiving .finally is not a function
- FIO-2882 PDF | 3.1.1 Regression | Sketchpad: Image overlaps other fieds on PDF download
- FIO-2849 PDF | Interpolation of submission data in the pdf header/footer does not work
- FIO-2846 API | Investigate TypeError : Cannot read property '_id' of null
- FIO-2823 API | Custom mongodb collection on a resource breaks the resource and the submission data cannot be accessed
- FIO-2786 FJS | Nested Wizard in Modal Edit | Initial click on page1's next button does not work
- FIO-2765 PDF , ACC | PDF Download where page breaks, instead of the field moving to next page, field is cut in half by page
- FIO-2730 ACC | Webforms are showing the Form.io logo when using Quick Inline Embed configuration
- FIO-2687 FJS | Receiving [Object, object]  in Select with Custom Data Source
- FIO-2686 ANG  | Date Time is not attaching timezone metadata to the submission
- FIO-2678 PDF  | Selected Radio buttons need to be darker on PDF download
- FIO-2672 API | If the "unique" validation is attached to an "index" field, then all lookups should only include that field in the query for lookup.
- FIO-2622 FJS | When you have a Nested Form component with clearOnHide set, the data becomes detached from the subForm component when the value is reset when cleared.
- FIO-2618 PDF | FJS | Rework Mechanism to indicate once the PDF has completely Loaded as it has caused Regressions with how the loaders with PDF work.
- FIO-2617 FJS | File component - When setting "Display as Image" to true, the Use Camera button shows without setting "Enable web camera" to True.
- FIO-2567 FJS | Calculated Data in DataSource in Edit Mode is not working
- FIO-2459 PDF  | Increase timeout for PDF-server response to allow upload of larger PDF files
- FIO-1470 FJS |  Radio buttons not receiving i18n translations
- FIO-1429 FJS | Mobile Phone Number does show number keypad but is using regular keypad.
- FIO-1146 PDF |  Text area: ACE editor: Caret position does not set correctly when entering characters into the field
- FIO-658 FVP | Ability to replace the name of the title
- FIO-654 FVP | Safari - When a logo hasn't been defined for a project through the Public Configuration, a standard <form.io> logo will display in the header for the 1st time when the form is opened in the FVP
- FIO-633 PDF | Multiple Masks error covers up the text field, making it impossible to read what you are typing
- FIO-2986 FJS | Inherit default (en) translations (validations, buttons) for custom languages
- FIO-1409 FJS | Button - Add new setting 'Save On Enter' to button component. Setting should only be an option when 'Submit' is selected for Action
- FIO-977 API | Download Permission - Allow anonymous PDF download via API key
- FIO-800 API | Ability to delete the license utilizations


# May 4th, 2021 Release
## API Server Version 7.1.3
## PDF Server Version 3.1.1

### Included Correlated Libraries:
 - portal@7.2.2
 - formviewpro@1.97.1
 - formmanager@1.97.1
 - formiojs@4.13.1
 - premium@1.16.1
 - offline@3.1.0
 - formio@2.2.0
 - uswds@2.3.2
 - vpat@2.3.2

### Tickets Included
 - FIO-2913 FJS | Dynamic Wizard - Unable to add/save a new Dynamic Wizard to builder
 - FIO-2911 FJS | Dynamic Wizard - Problem with poor separation of EditMode and other modes in normal projects
 - FIO-2908 FJS | 4.13.1 Regression | Dynamic Wizard & Edit Grid: When the components have Sketchpad component inside, cannot submit the form. Cannot read property 'offsetWidth' of undefined error is thrown
 - FIO-2832 Receiving 400 bad request when using OpenID
 - FIO-2808 API | 7.1.3 Regression | '400 Bad Request' error for a portal-check and 'Invalid alias' error in a console each time I open a project, render a form or reload a page
 - FIO-2807 PDF | 3.1.1 Regression | PDF server is responding with a '400 Bad Reqest' error on PDF download on remote-dev.form.io
 - FIO-2790 API | Investigate why SAML authentication does not work with teams using Email Field configuration.
 - FIO-2767 API | User Profile Permissions - Logging in as a user to a freshly installed deployed portal, I am unable to edit my username information
 - FIO-2738 FJS | 4.13.0 Regression | Dynamic Wizard: Clicking on the error in the Error list related to DW when the wizard page with it is already open, outside components appear and display with the DW
 - FIO-2701 FJS | 4.13.0 Regression | Dynamic Wizard - Logic form: Reset action crashes Dynamic Wizard
 - FIO-2692 FJS | 4.13.0 Regression | Dynamic Wizard - Data form: Error in a console after making a data entry on the Component Headers page
 - FIO-2661 API Server | The inline embedding for deployed server seems to not be working anymore. We need to refactor the offline embed script to use new lazy loading embedding method.
 - FIO-2623 API | Receiving 401 Unauthorized error when performing a simple GET request on a new stage
 - FIO-2605 API | Using the x-token for a parent project, you can use the JWT token received from that response to gain access to other sibling projects.
 - FIO-135 FJS-1417: Data table: Text formatting of the Text Areas with editors persists in the Data table
 - FIO-2788 FMG | OAuth process being redirected back to Portal instead of FMG


# April 26th, 2021 Release
## API Server Version  7.1.2
## PDF Server Version 3.1.0

### Tickets Included:
 - FIO-2766 API | Form Definition Permission - Read Form Definition Permissions are not preventing unauthorized users from viewing form definition
 - FIO-2531 API | Including _id’s of conflicting records when unique validation is triggered on server
### New Features
 - FIO-2484 API | Implement 'Split Roles' PR for Group Permission for the 7x server


# April 16th, 2021 Release
## API Server Version  7.1.1
## PDF Server Version 3.1.0

### Included Correlated Libraries:
 - portal@7.2.0
 - formviewpro@1.97.0
 - formmanager@1.97.0
 - formiojs@4.13.0
 - premium@1.16.0
 - offline@3.1.0
 - formio@2.1.1
 - uswds@2.3.2
 - vpat@2.3.2

### Tickets Included
 - FIO-2796 API | Deployment issues using 7.1.0 with CosmosDB

# April 13th, 2021 Release
## API Server Version 7.1.0
## PDF Server Version 3.1.0

### Included Correlated Libraries:
 - portal@7.2.0
 - formviewpro@1.97.0
 - formmanager@1.97.0
 - formiojs@4.13.0
 - premium@1.16.0
 - offline@3.1.0
 - formio@2.1.0
 - uswds@2.3.2
 - vpat@2.3.2

### Tickets Included
 - FIO-2702 FJS | 4.13.0 Regression | Dynamic Wizard: Form does not work correctly when the DW has no components inside
 - FIO-2699 FJS | 4.13.0 Regression | Dynamic Wizard - Logic form: DW is hidden and disabled by logic. After it's become visible and enabled, it renders with the components outside the DW
 - FIO-2698 FJS | 4.13.0 Regression | Dynamic Wizard - Logic form: 'Uncaught InternalError: too much recursion' error on changing the value set by logic. DW stops working correctly after that
 - FIO-2690 FJS | 4.13.0 Regression | Dynamic Wizard: DW does not work correctly and there are errors in a console when redirecting to the Wizard pages with DWs by clicking the errors in the Error list
 - FIO-2679 API | GET Request is being shown twice in Network Tab
 - FIO-2653 APP, FJS | 4.13.0 Regression | Data page: Submission table does not load causing 'The Kendo UI directives require jQuery to be available before AngularJS' error in a console
 - FIO-2634 FJS | 4.13.0 Regression | Nested Form: Signature data does not display in submission
 - FIO-2518 SEC | Remove any broken symlinks, if any.
 - FIO-2517 SEC | Check for calls out of the dockerfile to download software externally
 - FIO-2516 SEC | Remove suid & sgid files to enforce simple permission sets.
 - FIO-2515 SEC | Remove kernal tunable items since they are not needed.
 - FIO-2514 SEC | Remove base init scripts since they are not needed.
 - FIO-2513 SEC | Ensure the base image contains no cron jobs.
 - FIO-2512 SEC | Remove fstab from Docker image
 - FIO-2500 API | Deleting a project doesn't recursively delete all live stages
 - FIO-2478 FJS-1380 | API Put Request is updating data with values that are not part of the select and radio components.
 - FIO-1565 API | FMG | Revisions | Making changes to a Form with Revisions enabled the user is displayed as "anonymous". Want to show email of the user from FMG that made the change.
 - FIO-1559 APP | 7.2.0-rc.4 Regression | Team data on Home Page not updating until refresh
 - FIO-1550 API | 7.1.0-rc.5 Regression | Oauth - Resources are not being shown on Oauth Action when Action is set to Login Existing Resource
 - FIO-1546 API | When you type into License Key and then clear it and save the settings. You are redirected to the overview page with Error. Unable to delete.
 - FIO-1544 FJS | Dynamic Wizard: After filling out a form, then resetting it, filling out again and submitting it, Dynamic Wizard data does not fully save
 - FIO-1536 API | Allow endpoint on API server to provide submission JSON to generate PDF
 - FIO-1535 API / APP | Regression | Updating Username is not updating on Submit. Not updating on the View Page either.
 - FIO-1497 API | API Stage Request - Refactor the GET query to show all ACTIVE stages per project and remove DISABLED stages from the displayed request response
 - FIO-1452 API | Investigate Google Oauth 2.0 and Open ID Connect 
 - FIO-1410 API | 7.1.0 Regression | Receiving 'Unauthorized' when logging in to remote accounts
 - FIO-1365 API | Authoring Stage Issues
 - FIO-1349 API | DataSource server validation logic not handling a situation where the datasrc returns: Uncaught (in promise): [object String].
 - FIO-1309 API | 'Calculate On Server' is not recalculating when user changes calculation values in the API request
 - FIO-1269 FJS | Minified JSON format | Dynamic Wizard JSON is not minifying the template
 - FIO-1215 FVP | Offline Mode - Deleted submissions are not displayed or highlighted in red when viewing Offline activity table but instead are removed
 - FIO-1191 API | 7.0.0 Regression | When a project is connected to an on-premise env, PDF forms do not load in PDF Management page. Error in a console
 - FIO-1171 PDF | 3.0.0 Regression | Select (Resource): 'Cannot read property 'widget' of undefined' error is thrown when trying to submit the form with an empty value
 - FIO-1163 API | Regression 7.0.0-rc.69 | Columns | When Column component shares the same API key as a component inside it, the data is not showing up
 - FIO-1140 API | When deploying the Version from the "Dev" Stage to the "QA" Stage form.io is reintroducing the formRevision tags.
 - FIO-1138 API | Teams - Protected flag is preventing user to remove teams or update team permission
 - FIO-1090 FOR-2866 API | Submission Collection - Fails to get a single submission when using different collection for form.
 - FIO-1000 API | File Export is being returned with Error {} | Need to ensure that the current project is loaded in cache before an import is made
 - FIO-911 When project import fails, entire project JSON is dumped into the server logs. Need a better way to log the failure
 - FIO-644 7x/6x PDF 16 | Teams - PDF - Unable to upload/create PDF form as a WRITE team member.
 - FIO-755 SEC-35 | Deployed Server - Remote Code Execution via SSTI
 - FIO-476 FJS-954: Sketch Pad does not show data on CSV export 

# Febuary 24th, 2021 Release
## API Server Version 7.0.2
## PDF Server Version 3.0.0
### Included Correlated Libraries:
 - portal@7.1.19
 - formviewpro@1.96.2
 - formmanager@1.96.5
 - formiojs@4.12.7
 - premium@1.15.4
 - offline@3.0.5
 - formio@2.0.0
 - uswds@2.0.2
 - vpat@2.0.9


# Febuary 9th, 2021 Release
## API Server Version 7.0.0
## PDF Server Version 3.0.0
### Changed
 - Upgrade portal@7.1.19
 - Upgrade formiojs@4.12.7
 - Upgrade @formio/premium@1.15.4
 - Upgrade formio@2.0.0

### Tickets Included
 - FIO-1282 API | 7.0.0-rc75 Regression | Quickly changing 'Public/Private' settings on launch page is causing 502 gateway error / Accessing formmanager is causing 502 gateway error
 - FIO-1262 API | SAML profile getting stripped and apps that depend on data from the profile would stop working
 - FIO-1244 FMG / API | Blocker 7.0.0-rc.73 | Unable to load FormManager for projects that have FormManager enabled via license
 - FIO-1235 API | 7.0.0 Regression | Changes on pages like Forms Revisions, Form Settings and Launch cannot be saved after hard refresh. 'Cannot convert undefined or null to object' error in a console
 - FIO-1221 API | SAML provider is not working with private encryption
 - FIO-1214 API | Sketchpad | Receiving Sketchpad must not be an array on submission
 - FIO-1213 APP | Form JSON is saving the entire JSON and not the minified schema causing large JSON size
 - FIO-1180 APP | Actions | Login action shows resource number instead of name and reset password is not showing resources
 - FIO-1179 API | Token Swap - Receiving error "cannot read property 'models' of undefined" when "/current" api endpoint is used in headers to perform a token swap
 - FIO-1139 APP | Regression on 7.1.17-rc.42 | Action Log is not updating with actions.
 - FIO-1135 API | 7.0.0-rc.68 Regression | Select - Unable to download a CSV report when Select component is part of form JSON
 - FIO-1129 API | 7.0.0-rc.68 Regression | When hitting the refresh button on the browser or by using the quick key, you are redirected to the login page
 - FIO-1123 APP | 7.1.17-rc40 Regression | Environment Settings page is showing as blank.
 - FIO-1081 FJS | Dynamic Wizard - When Logic is used for components inside a Dynamic Wizard to merge schema and dynamically add values, form gets into an infinite  loop and logic is not executed
 - FIO-1061 API | 7.0.0-rc.64 Regression | Unable to retrieve a specific form submission (see description and attachment)
 - FIO-1060 API | 7.0.0-rc.64 Regression | Significant slowdown on form submission
 - FIO-1043 FMG | Unable to use form manager on Remote. Travis to investigate
 - FIO-1035 API | 7x Server | Nested form inside Nested Form - Receiving "Too many recursive requests." on submit
 - FIO-1027 FOR-2152 | API | EXISTS permission can also be exploited as a way to check whether a user is registered or not.
 - FIO-1025 FOR-2477 | APP | Public Config Settings - UI of checkbox not displaying 'true' for public config settings when 'JSON' option is checked
 - FIO-991 APP | Form Settings -> PDF Settings -> Settings Tab not saving
 - FIO-983 FVP | Data Source after submission on Refresh | Data source shows as Unknown component: datasource
 - FIO-980 API | (7x Server Blocker Regression) - Group Permissions - Receiving 'Unauthorized' for valid group users when tying to GET a submission request
 - FIO-975 SEC | Mongo string is being presented in plain text inside of the config logs
 - FIO-951 API | 7x License - When a license is enabled for multiple projects, the information for some projects doesn’t register on the license UI (status and type are missing)
 - FIO-949 API | Project Request Issues | Investigation
 - FIO-931 FOR-2892 | 7x Server Regression | Revisions- Save Draft and Publish not saving changes to form
 - FIO-905 FOR-2845 Set the correct username when making revisions if they are authenticated into Portal using SAML
 - FIO-902 FOR-2889 | Access page: 'Stage Level Access Permissions' table: 'Everyone' role is not saved after is it selected for any of the permissions
 - FIO-853 FOR-2891 7x Server | Permission | Form definition (JSON) can still be accessed anonymously when 'Read Form Definition' permission has 'Anonymous' role removed from form access settings
 - FIO-850 FOR-2878 Project Settings: Users with Read and Write team permissions are able to get to different Project Settings pages using direct URLs
 - FIO-849 FOR-2877 | Portal | Public Config - Adding a 2nd public config row wipes value of 1st config row
 - FIO-848 FOR-2876 | Portal | Public Config - Refreshing the page after checking the 'JSON' configuration in public configs removes the ‘Check’ UI for JSON checkbox
 - FIO-847 FOR-2872 | Posting submission data where any datagrid or editgrid are "null" or an empty string, causes the crash
 - FIO-845 FOR-2868 | Add "ignore TLS errors" flag to license check to the server
 - FIO-843 FOR-2858 | The default limit for resources is too large for Cosmos DB and throws errors.
 - FIO-842 API | FOR-2856 | (7x Server) Newly created projects are not created with default stages 'Production' and 'Authoring'. I only see 'Live' stage
 - FIO-840 FOR-2837 | Revisions- Validation errors still fire if you are using an older version of the form that does not have that component
 - FIO-836 FOR-2770 | Team Permission | Remove the ability for Team Write / Read members to access the 'Access' section of project
 - FIO-835 FOR-2769 | Teams: Read Permission: When you have Read only permissions and try to drag over the component, you click onto a different tab and a "Do you want to save" popup appears and when you click "Yes" it shows message that Form Saved.
 - FIO-830 FOR-2843 | API | TerraQuest | Invalid Alias Error on submitting the form after Edit.
 - FIO-829 FOR-2839 | Invalid Alias Issue
 - FIO-827 SQL Connector Issue
 - FIO-826 | Webhook action: Displays “externalId is not defined”.
 - FIO-825 FOR-2828 | Save to Resource action does not allow you to pick DataGrid, EditGrid
 - FIO-824 | Tenant/Stages- PDF Download not calculating on Project Limits on Tenants. Counting against Live Project and not the Tenant
 - FIO-823 FOR-2798 | APP | Unable to connect to Remote Server using Stages other than Live. Error importing environment - 400 - Bad Request: [object Object]
 - FIO-822 FOR-2786 | New Projects should only have 2 stages on initial creation and they should be Live and Authoring.
 - FIO-821 FOR-2764 | Form.io api gives "401 Unauthorized" error despite sending valid API key in the request
 - FIO-820 FOR-2760 | if a project has a “parent” project defined, but that project does not exist in the database, PDF downloads fail
 - FIO-818 FOR-2739 | 7x Server Self Access Permissions- Self Access checkbox not saving
 - FIO-816 FOR-2722 | Webhook- Delete is not firing and not populating request with the submission data.
 - FIO-815 FOR-2721 | Fixes an issue related to externalIds in Webhooks. #639
 - FIO-808 FOR-2669 | Importing a form with Form Controller, the settings do not save onto the new Project
 - FIO-804 FOR-2862 | Upgrade nghttp2 to v1.41.0
 - FIO-803 FOR-2851 | API | Expose Environment ID in the status endpoint
 - FIO-802 FOR-2831 | Enterprise "Revisions" Feature is setting the version I had before making this attempt instead of Restoring to selected Version
 - FIO-801 FOR - 2787 | Receiving console errors ' TypeError: Cannot read property 'read' of undefined ' when viewing 'Access' page
 - FIO-796 FOR-2874 | Recaptcha - Server validation is not fired when a POST request is made for a form with recaptcha enabled
 - FIO-794 FOR-2797 | Unable to create PDFs. Receiving Unauthorized.
 - FIO-792 FOR-2788 | When linking your account to Github, you will not see Link with GitHub Your account is linked with GitHub! on the Edit Page on User Settings until you log back in.
 - FIO-791 FOR-2741 | Investigate inconsistency with emails sending using form.io default email provider
 - FIO-787 FOR-2795 | Clicking on the name of the Team button that is assigned to a Project should redirect you to that Team View Page. It does for a split second, then redirects to the project
 - FIO-785 FOR-2855 | Creating a 3rd+ stage is causing an 'Internal Server Error' and the project gets in a bad state
 - FIO-784 FOR-8205 | Wizard- Conditional pages not saving data.
 - FIO-783 FOR-2850 | API | Oauth is failing after Oauth button is clicked - action is not executed
 - FIO-782 FOR-2820 | API 7x | Tenant- Stage Versions not showing up after you hit deploy button. It says "No versions exist."
 - FIO-781 FOR-2818 | API 7x | Tenant- No Notification that Tenant is Disabled inside Tenant Manager or when you open the tenant.
 - FIO-780 FOR-2817 | API 7x | Tenant- When you have surpassed the number of tenants, the newly created tenants show as Disabled in the License Management page but you are able to use the tenants and create forms,etc.
 - FIO-779 FOR-2802 | Need the ability to either search or sort (alpha) forms/resources on Form Management page
 - FIO-778 FOR-2792 | Stages- When you have hit your limit on stages, and you disable a stage, the Add New Stage button does not show.
 - FIO-777 FOR-2784 | Upgrading the project inside of the Form.io Project upgrades the limits but still shows as old project level.
 - FIO-775 FOR-2840 | Team permissions: Write: Able to reach the Export Template page and export a JSON project template. Also, able to create a new version of the stage
 - FIO-774 FOR-2747 | Investigate if there is a way to disable Google ID set or if we need to stop it from being loaded on-premise.
 - FIO-773 FOR-2812 | Login Page- Redirects links to Terms of Service and Privacy Policy pages are just redirecting to the form.io home page
 - FIO-770 FOR-2864 | APP | Form Versioning - Newly added fields are removed from form builder after publishing a new version of a form. Revision is not saved
 - FIO-769 FOR-2821 | Tenant- After clicking the button to delete a stage that is not the live stage, the delete will redirect to the Parent Project and not redirect to the Tenant.
 - FIO-767 FOR-2803 | Stages on Tenants do not show up on the License Management section like the Main Project's Stages
 - FIO-766 FOR-2885 | In portal, when you want to enable a project for licenses, it is not adding the “projectId” and therefore fails to enable the license for that project.
 - FIO-765 FOR-2863 | API / APP | Deleted project are still showing up after deleting.
 - FIO-764 FOR-2857 | API | Stages registering as projects on license
 - FIO-763 FOR-2893 | API |  Form builder: Form Access page: When selecting any role in the Access page, lots of 'TypeError: t.form.fieldMatchAccess is undefined' errors are thrown in a Console
 - FIO-762 FOR-2785 | API | Forms and Resources Utilizations: Title, Name, Path, and Type do not show information until you add a component. You are also not able to Disable a form if until you add a component.
 - FIO-589 APP | PDF Management page: Users with Read and Write team permissions are able to get to the PDF Management page and delete PDFs there. The page might not load for the 1st time
 - FIO-431 FJS-1434: Tagpad - Receive ' Tagpad: "height" is not allowed' error when trying to submit tagpad
 - FIO-400 FJS-1344 | Cannot change the same API key to another one after adding two components with the same API keys to the form itself (one of such components inside a Panel, a Well, a Container, a Data Grid or an Edit Grid is automatically rem...
 - FIO-332 FJS-1129 | Unique Validation message is not using the Custom Error Message
 - FIO-217 FJS-1443 | Dynamic Wizard on submit receiving "dynamicWizard" must be an object
 - FIO-212 FJS-1351 | Dynamic Wizard: If any component in a Dynamic Wizard has a 'required' validation, the user won't be able to submit it even if they filled it out with valid data
 - FIO-176 FJS-1447: Tagpad | Component values display under the component labels instead of displaying next to them in the submission and PDF download
 - FIO-174 FJS-1446 | Sketchpad: Submitted data does not persist in the submission and the PDF download
 - FIO-119 FJS 1221 | Nested Form-When changing child data on the parent form, the data does not save
 - FIO-114 FJS-1402 | Tagpad: Sometimes values are not saved and sometimes validation does not allow to submit the form even though all the required fields are filled in with valid data (see the video attached)
 - FIO-1188 API | Remove Twilio SMS Action from 7x Server
 - FIO-990 API | Remove the formio-services dependency.




 
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
