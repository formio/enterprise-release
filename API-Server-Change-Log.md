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


### Others tickets

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
