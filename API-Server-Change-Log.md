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
