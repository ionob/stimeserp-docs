# Project

## Overview
The Project Management module in our ERP system allows users to create and manage projects under clients. This module facilitates activities such as employee allocation, invoice generation, and timesheet management. The following guide outlines the steps to create a new project and manage its details effectively.

<div>
    <img src="../../images/Project list.png" alt="Project list" style="border-radius: 10px; width: 70%; height: 70%;border: 0.5px solid #333;">
</div>

### How to Create New Project

**Steps to Create a New Project**

Click on New Project: To create a new project, navigate to the Project section and click on the 'New Project' button.

<div>
    <img src="../../images/add new project.png" alt="add new project" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>

### Project Details

<div style="text-align:left;">

<strong>Project No:</strong>
This is a system-generated sequence number for the project.

   >	The sequence can be defined in **Administration** **->** **Basic** **->** **Document Sequence**.

<strong>Project Name:</strong>
Enter the name of the project.

<strong>Client Project Number:</strong>
The client may have a separate project number for their internal use.

<strong>Status:</strong>
Set the status of the project (Active/Inactive/Completed/Hold).

<strong>Job Type:</strong>
Define the type of the project (e.g., Construction, Cleaning, Security).

<strong>Main Contractor:</strong>
Enter details of the main contractor.

<strong>Payment Type:</strong>
Specify the expected payment date of the project (e.g., 30 days, 90 days).

   >	Payment schedules can be added from **HR** **->** **Basic** **->** **Payment Schedule**.

<strong>Client:</strong>
Select the client under which the project is created.

   >	Clients can be added from **Business Development** **->** **Basic** **->** **Client**. * [How to Create a Client ?](../Client.md)

<strong>LPO No:</strong>
Enter the Local Purchase Order Number. This will be shown in the client invoice print.

<strong>LPO Date:</strong>
Enter the Local Purchase Order Date. This will be shown in the client invoice print.

<strong>Sales Executive:</strong>
Select the sales executive from the company staff.

<strong>Project Coordinator:</strong>
Select the project coordinator from the company staff.

<strong>Start Date:</strong>
Enter the start date of the project.

<strong>End Date:</strong>
Enter the end date of the project.

<strong>Contact No:</strong>
Enter the contact number of the person related to this project.

<strong>Timesheet Collection Date:</strong>
Specify the expected timesheet collection date. If not provided, the task will default to the 10th of the month.

   >	An automatic timesheet collection task will be generated in **CRM** **->** **Activity** **->** **Task**.

<strong>Inter Transfer:</strong>
Used to change the sponsorship company of this project. The timesheet print will reflect the name of the transferred sponsorship company.

<strong>Closed LPO & LPO Amount Limit:</strong>
Used to manage the invoice amount. Confirmation is required if the invoice amount exceeds the defined LPO amount limit.

<strong>Trade Wise LPO:</strong>
Set amount limits for specific trades. LPO amount limits can be defined for each designation in the Approved Rates tab of the project.

<strong>Internal Use:</strong>
Used to create projects for internal use management and to manage overhead expenses. Petty cash under this project is calculated as overhead expense.

### Project Documents

Documents related to the project can be added here.

### Approved Rates

Define rates for various designations under this project

<div style="text-align:left;">
    <ul>
        <li><strong>Rate Type:</strong> Composition of rate (e.g., Food, Accommodation, Transportation, Kitchen).</li>
        <li><strong>Trade:</strong> Applicable trade.</li>
        <li><strong>Occurrence:</strong> Frequency of the rate (e.g., Hourly, Weekly, Monthly, Yearly).</li>
        <li><strong>Rate:</strong> Standard rate for the project.</li>
        <li><strong>NOT Rate:</strong> Normal overtime rate.</li>
        <li><strong>WOT Rate:</strong> Weekend overtime rate.</li>
        <li><strong>HOT Rate:</strong> Holiday overtime rate.</li>
        <li><strong>Acc Cost:</strong> Accommodation cost.</li>
        <li><strong>Tra Cost:</strong> Transportation cost.</li>
        <li><strong>Date:</strong> Effective date of the rate.</li>
        <li><strong>LPO Amount Limit:</strong> Trade-wise LPO amount limit.</li>
    </ul>
</div>

### Holiday Details

Update national holidays and other public holidays related to the project.

### Location Details

Update project location details with geographical coordinates.

### Other Details

General configuration details of the project.

### Site Supervisor

Select the site supervisor from the company staff.

### Normal Hours

Specify the expected normal hours for the project. Additional hours worked beyond this will be considered overtime if the overtime option is enabled.

### Accommodation Type and Transportation

Select the accommodation type and transportation type for the project.

### Allowable Absence

Define the allowable absence for the project, used in supplier timecard and supplier invoice absent calculation.

### Accommodation Emirates

Specify the emirates where accommodation is arranged for the project.

### Week Off Day

Select regular week off days for the project. Multiple week off days can be set.

### Flat & Overtime

Define flat rates and overtime rates for the project. If overtime is enabled, NOT Rate will be applied for overtime worked.

### Invoice Based on Attendance

Enable this option if timesheets and invoices should be generated based on attendance. Hours updated in the attendance register will be used. If disabled, timesheets will be generated with the normal hours specified in the project.

### Is Hourly Idle Project

Manage idle employees. If payment is to be given for idle days, mobilize those employees into this project to generate timesheets, invoices, and payroll using this data.

### Supplier Payment Settings

<div style="text-align:left;">
    <ul>
        <li><strong>Food Allowance for FAT Site (Monthly):</strong> Calculate mess deduction in the supplier invoice.</li>

   >	<strong>Formula:</strong> **Mess Deduction** **=** **(Monthly Food Allowance / No of days in the month)** * **(No of days worked on FAT Site)**.
<li><strong>Absent Deduction Per Day:</strong> Define custom absent deduction calculation for the project. If the number of absences exceeds the allowable absence, the amount will be deducted for each additional day.</li>
    </ul>
</div>

### Contact Person Details

Enter the name, designation, contact number, and GPS coordinates (X and Y) of the contact person.

### Related User

Assign the Business Development Manager (BDM), Business Development Executive (BDE), Operation Supervisor, and Site Coordinator for the project with effective dates.

