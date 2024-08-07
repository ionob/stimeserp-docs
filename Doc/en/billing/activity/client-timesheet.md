# Timesheet

## Overview
This documentation covers the process of managing timesheets within our system. There are two types of timesheets:

### Types of Timesheets

<div style="text-align:left;">
    <ul>
        <li><strong>Client Timesheet</strong></li>
        <li><strong>Manual Client Timesheet</strong></li>
    </ul>
</div>

### Creating a Timesheet
>	You can access and manage your timesheets through the following sections: **Billing** **→** **Activity** **→** **Client Timesheet** or **Manual Client Timesheet**

## Client Timesheet

Client timesheets are automatically generated based on the activities and tasks logged for a specific client. These timesheets are linked with client projects and billing.

<img src="../../images/client-timesheet.png" alt="Client Timesheet" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### Creating a Client Timesheet
The following fields are required to create a client timesheet:
<div style="text-align:left;">
    <ul>
        <li><strong>TimeSheet No:</strong> This field will be auto-generated.</li>
        <li><strong>Client:</strong> Search and select the client for whom the timesheet is being created.</li>
        <li><strong>Site:</strong> Specify the site associated with the client. You can create multiple sites under a single client. When generating a client timesheet, you must select at least one site or you can select multiple sites for the timesheet generation.</li>
    </ul>
</div>
<div>
    <img src="../../images/timesheet details.png" alt="Timesheet Details" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>
<div style="text-align:left;">
    <ul>
        <li><strong>Designation:</strong> Select the designation of the employee you want to generate client timesheet. You can create multiple designations. Designations will only appear in the client timesheet after employee mobilizing data has been added in project mobilizing data. This can be navigated using **Operation > Activity > Project Mobilization**, where site details and mobilized employees with their designations can be viewed.The designation will only show in the client timesheet after selecting the site.</li>
    </ul>
</div>
<div>
    <img src="../../images/Project mobilisation.png" alt="Project Mobilisation" style="border-radius: 10px; display: inline-block; width: 70%; height: 70%; border: 0.5px solid #333;">
    <img src="../../images/Designation.png" alt="Designation" style="border-radius: 10px; display: inline-block; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>
<div style="text-align:left;">
    <ul>
        <li><strong>Month:</strong> Select the month for which the timesheet is applicable.</li>
        <li><strong>From Date:</strong> Set the starting date for the timesheet period.</li>
        <li><strong>To Date:</strong> Set the ending date for the timesheet period.</li>
    </ul>
</div>
<div>
    <img src="../../images/date filter.png" alt="Date Filter" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>
<div style="text-align:left;">
    <ul>
        <li><strong>Official:</strong> Mark the timesheet as Official, Raw, or Missing.</li>
    </ul>
</div>
<div style="text-align:center;">
    <table>
        <tr>
            <td style="width: 20%;">Official</td>
            <td style="text-align: left;">A timesheet marked as official means an invoice can be created against it.</td>
        </tr>
        <tr>
            <td style="width: 20%;">Raw</td>
            <td style="text-align: left;">A timesheet marked as raw will only create a draft. At month-end, generate the client timesheet as raw to provide the employee's salary. After obtaining the employee mobilize data, edit the client timesheet and convert it from raw to official.</td>
        </tr>
        <tr>
            <td style="width: 20%;">Missing</td>
            <td style="text-align: left;">If exact employee data is not available, mark the timesheet as missing.</td>
        </tr>
    </table>
</div>
<div style="text-align:left;">
    <ul>
        <li><strong>Set Hours to 0:</strong> If data is unavailable, enable the checkbox to generate the timesheet with zero hours.</li>
        <li><strong>Status:</strong> Initially set to open. It can be edited to be approved or rejected.</li>
    </ul>
</div>
<div>
    <img src="../../images/status.png" alt="Status" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>

### Generating and Viewing Timesheets

After clicking "Generate," the timesheet will be created under the selected designation. If "Set Hours to 0" is checked, all dates will display the employee's hours as zero. The timesheet can be edited after it has been generated. Here’s an example of the Timesheet generation interface:

<div>
    <img src="../../images/view timesheet.png" alt="View Timesheet" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>

### Exporting Timesheets
The system provides options to export timesheets as PDF or Excel. This feature is only available after selecting the employee(s) for the timesheet.
<div>
    <img src="../../images/export option.png" alt="Export Options" style="border-radius: 10px;  width: 70%; height: 70%; border: 0.5px solid #333;">
</div>

<div style="text-align:left;">
    <h3>Export Options</h3>
    <ul>
        <li><strong>Show Client Id:</strong> Display the client ID in the export.</li>
        <li><strong>Show Previous Id:</strong> Display the previous ID in the export.</li>
        <li><strong>Show Rate And Amount:</strong> Include rate and amount details.</li>
        <li><strong>Show VAT:</strong> Include VAT information.</li>
        <li><strong>Include Logo:</strong> Add a logo to the export.</li>
        <li><strong>Show Approved By:</strong> Display the approver's details.</li>
        <li><strong>Show OT Details:</strong> Include overtime details.</li>
        <li><strong>Show Tradewise:</strong> Display trade-wise information.</li>
        <li><strong>Hour Format:</strong> Export in hour format.</li>
        <li><strong>Attendance Format:</strong> Export in attendance format.</li>
    </ul>
</div>

### Editing Official Status
You can change the official status using the "Is Official" edit button. When clicked, a popup will appear allowing you to select the status as Official, Raw, or Missing. After editing, you can update the status. If the client timesheet was initially generated as raw, you can update it to official once the data is correctly included.

<div>
    <img src="../../images/editing official status.png" alt="editing official status" style="border-radius: 10px;  width: 70%; height: 70%; border: 0.5px solid #333;">
</div>


## Manual Client Timesheet

Manual client timesheets are created manually for instances where automated timesheets are not feasible. This could include ad-hoc tasks or special projects that require manual entry.

<div>
    <img src="../../images/manual client timesheet.png" alt="manual client timesheet" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>

### Creating a Client Timesheet
The following fields are required to create a client timesheet:
<div style="text-align:left;">
    <ul>
        <li><strong>TimeSheet No:</strong> This field will be auto-generated.</li>
        <li><strong>Client:</strong> Search and select the client for whom the timesheet is being created.</li>
        <li><strong>Site:</strong> Specify the site associated with the client. You can create multiple sites under a single client. When generating a client timesheet, you must select at least one site or you can select multiple sites for the timesheet generation.</li>
    </ul>
</div>

<div>
    <img src="../../images/client in manual.png" alt="client in manual" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>

<div style="text-align:left;">
    <ul>
        <li><strong>Designation:</strong> Select the designation of the employee you want to generate client timesheet. You can create multiple designations. Designations will only appear in the client timesheet after employee mobilizing data has been added in project mobilizing data. This can be navigated using **Operation > Activity > Project Mobilization**, where site details and mobilized employees with their designations can be viewed.The designation will only show in the client timesheet after selecting the site.</li>
    </ul>
</div>
<div>
    <img src="../../images/Project mobilisation.png" alt="Project Mobilisation" style="border-radius: 10px; display: inline-block; width: 70%; height: 70%; border: 0.5px solid #333;">
    <img src="../../images/Designation.png" alt="Designation" style="border-radius: 10px; display: inline-block; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>
<div style="text-align:left;">
    <ul>
        <li><strong>Month:</strong> Select the month for which the timesheet is applicable.</li>
        <li><strong>From Date:</strong> Set the starting date for the timesheet period.</li>
        <li><strong>To Date:</strong> Set the ending date for the timesheet period.</li>
        <li><strong>Prepared by:</strong> This field will display the user who is currently logged in and preparing the timesheet.</li>
    </ul>
</div>

<div>
    <img src="../../images/prepared by.png" alt="prepared by" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>

<div style="text-align:left;">
    <ul>
        <li><strong>Checked by:</strong> Search and select the user who checked the timesheet. </li>
    </ul>
</div>

<div>
    <img src="../../images/checked by.png" alt="Checked by" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>

>	You can add checked-by users through **HR** → **Basic** → **Staff** .Adding a staff member will not automatically show them as a checked-by user. To make a staff member available as a checked-by user, create a user in **Administration** → **Activity** → **User** and select the previously added staff member.

<div style="text-align:left;">
    <ul>
        <li><strong>Approved by:</strong> Search and select the user who approved the timesheet.</li>
        <li><strong>Remarks:</strong> Add any relevant remarks or notes.</li>
            <ol><strong>Official:</strong> Timesheet marked as official means an invoice can be created against it.</ol>
            <ol><strong>Raw:</strong> Timesheet marked as raw will only create a draft. At month-end, generate the client timesheet as raw to provide the employee's salary. After obtaining the employee mobilize data, edit the client timesheet and convert it from raw to official.</ol>
            <ol><strong>Missing:</strong> If exact employee data is not available, mark the timesheet as missing.</ol>
            <ol><strong>Discrepancy:</strong> Used when our client's timesheet and our timesheet data mismatch. Generate the user timesheet with a discrepancy to indicate the inconsistency.</ol>
        <li><strong>Official Status:</strong> Mark the timesheet as Official, Raw, Missing, or Discrepancy</li>
        <li><strong>Set Hours to 0:</strong> If data is unavailable, enable the checkbox to generate the timesheet with zero hours.</li>
    </ul>
</div>

#### Entering Employee Details

After entering the necessary details in the manual client timesheet, click the "Load Employee Details" button. This will take you to the timesheet where you can select the employees and add the hours they worked.

<div>
    <img src="../../images/load employee data.png" alt="load employee data" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>
<div>
    <img src="../../images/Entering Employee Details.png" alt="Entering Employee Details" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>

#### Uploading Client Timesheet

In the manual client timesheet, you can download the template for the header format needed for the employee timesheet by clicking the "Download Template" button. You can then upload the client timesheet using the "Choose File" button to import all the data.

<div>
    <img src="../../images/Uploading Client Timesheet.png" alt="Uploading Client Timesheet" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>

#### Finalizing and Saving the Timesheet

Enable the "Is Final" button in the timesheet and click save. If the timesheet is generated as official, it will show in the client invoice section.

<div>
    <img src="../../images/Finalizing and Saving the Timesheet.png" alt="Finalizing and Saving the Timesheet" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>

### Related Topics

* [How to Create a Client ?](../Client.md)
* [How to Create a Site ?](../site.md)
* [How to Create a Designation ?](../designation.md)
* [How to Generate a Client Invoice ?](../clientinvoice.md)
* [How to Create a Checked-by Users ?](../staff.md)
* [How to Create a User ?](../user.md)