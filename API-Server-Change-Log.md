# October 29th, 2021 Release
## API Server Version 7.2.0
## PDF Server Version 3.3.0

### Included Correlated Libraries:
 - portal@7.2.9
 - formviewpro@1.97.9
 - formmanager@1.97.9
 - formiojs@4.13.8
 - premium@1.17.0
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
- FIO-3934 PRE | Regression | Sketchpad: Rendered form: Changing the circle size, the circles cannot be placed onto the image
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
- FIO-3681 PRE | When using DataTable component and conditional to show it related to the value of another component on the form gives the error "Cannot set property 'disabled' of undefined"
- FIO-3659 FVP | Data from previous submission showing in new submission
- FIO-3655 PDF | 3.1.6 Regression | Columns display one below the other instead of displaying next to each other on PDF download
- FIO-3652 PRE | Data Table | Clicking the Filter button in the column filter causes our onSubmit method to be called
- FIO-3650 API, SEC | Resolve vulnerabilities
- FIO-3624 API | Investigate why x-token is no longer working and receiving message "No authentication token provided"
- FIO-3597 APP | Field Based Resource Access: Resources and Roles added to the Create Permission are automatically added to the Read Permission
- FIO-3593 APP, VUE | Review Sample Vue Form Embed Code and Resolve Issues
- FIO-3589 API | Review and Resolve Formio's Weekly Report by Snyk
- FIO-3584 APP | Teams: When adding a new member to a team, the INVITATION PENDING status does not display below the user email
- FIO-3552 PRE | Data Table: Page spin button: Focus is lost upon pressing Up or Down arrow buttons
- FIO-3551 PRE | Regression 1.17.0 | Data Table: Component Settings: Display tab: Last setting states: 'Unknown component: undefined'
- FIO-3549 PRE | Data Table: When Unique validation for some components inside Data Table is not met, no errors display in the Error list
- FIO-3548 PRE | Data Table: Remove Unique validation
- FIO-3536 PRE | Data Table: Error list does not display in the Data Table modal window when errors occur
- FIO-3535 PRE | Data Table: When no columns display in the Data Table, after adding a row and clicking edit button, I get errors in a console
- FIO-3500 FJS, PDF | FieldSet in a form longer than 1 pdf page will auto page break to page 2
- FIO-3447 PDF | Signature | Hide gray box next to PDF signatures
- FIO-3432 PDF | Text Area: Number of rows being displayed does not correspond to the number of rows configured to be displayed in settings
- FIO-3409 PRE | Data Table, Data Grid, Data Source: Data shows as empty when I click the edit button of a row created via the Data Source inside a Data Grid
- FIO-3403 API | Project Export/Import is causing a false admin role to be added to role assignment action
- FIO-3369 API | Custom Collections not working on latest 7x (7.1.6)
- FIO-3329 APP | Teams - The Ability to make team emails case sensitive
- FIO-3302 API | Project settings not returned when queried by API key
- FIO-3286 PRE | Investigate Datagrid not updating while datasource fetch data successfully
- FIO-3241 PRE | Data Table: When there is a component in a Modal View inside the Data Table, the Data Table Modal window does not close on 'X' button
- FIO-3238 PRE | Data Table: Adding a new data entry after 'All items per page' has been selected, the 1st data entry created moves to the next page and the new one is being added to the current
- FIO-3236 PRE | Data Table: Pressing Reset button doesn't close Data Table row modal window
- FIO-3208 ACC | USWDS | Enter Data | Description and Character Counter are showing not in one line
- FIO-3206 ACC | USWDS | Regression | Enter Data, Component settings | A big gap between Label of Input field and Asterisk or Tooltip in modal windows
- FIO-3198 API | Investigate why all access is removed when you update the project via api key or x-admin-key using a PUT request.
- FIO-3191 ACC | Container: Red background of component with error in Container in modal window remains when error is fixed
- FIO-3146 ACC | Radio, Select Boxes: 'Invalid entry' is still announced even when all errors are fixed
- FIO-3098 PRE | Data Table: In Table View, the grid renders wrong value for Select field in certain situations
- FIO-3091 API | Ensure 7x server is compatible with Engine Version 4.0.0 of AWS Deployment
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
- FIO-3057 PRE | Chrome, Edge, Safari | Data Table: Mobile horizontal scroll on a desktop version of the website
- FIO-3056 PRE | Firefox, Safari | Data Table: Clicking on 3-dots menu button in the Data table and then anywhere out to close the menu, it does not get closed causing errors in a console
- FIO-3051 PRE | Data Table: ,"survey":{} is at the end of the survey section on the Data Table
- FIO-3049 PRE | Data Table: Address is showing up as [Complex Data] in the Table
- FIO-3048 PRE | Data Table: When saving a form with an unused select box, the form does not show in the Data Table and unable to create new form
- FIO-3045 PRE | Data Table: When selecting to show 'All' items, the word 'All' disappears
- FIO-3044 PRE | Data Table: Unable to make an update when I edit a submission
- FIO-3023 PRE | Dynamic Wizard: 'Minimum Length' and 'Maximum Length' settings do not work. You can reduce/surpass the minimum/maximum number of allowed data entries
- FIO-3010 PRE | Dynamic Wizard: Remove Unique validation
- FIO-3008 PRE | Dynamic Wizard: When you are on the wizard page with DW in edit mode, and you click on the error in the Error list that is on a different wizard page, no components display on the page
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
- FIO-3629 PRE | Data Table: Enable Inline Editing
- FIO-3628 PRE | Data Table: Enable Row labels
- FIO-3575 API | Force CORS restrictions to ONLY allow “localhost” applications to connect to it
- FIO-3436 API | Ability to set reply-to email field header to allow quick response from received emails.
- FIO-3224 PRE | Data Table: Enable ability to raise events from the grid by adding buttons to the data table which will render as buttons in the grid
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
