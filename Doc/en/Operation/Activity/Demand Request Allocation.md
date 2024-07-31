# Demand Request Allocation

## Overview
The Demand Request Allocation feature is designed to facilitate the allocation of employees to fulfill demand requests. This module allows users to efficiently assign employees based on their current status, trade, and other relevant criteria to meet the requirements of various projects.

<div>
    <img clss="popup-image" src="../../images/Demand Request List.png" alt="Demand Request List" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>

### Accessing Demand Request Allocation

**Steps to Access**

<strong>Navigate to Demand Request Allocation:</strong>
Go to the Demand Request Allocation section within the ERP system.

   >	The sequence can be defined in **Operation** **->** **Activity** **->** **Demand Request Allocation**.

<div>
    <img src="../../images/Demand Request Allocation.png" alt="Demand Request Allocation" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>

### Loading Employees

**Click on Load Employees**

<div>
    <img src="../../images/Load Employee.png" alt="Load Employee" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>

This will load all employees available for allocation.

<strong>Tabs:</strong>
Employees will be categorized into three tabs

<div style="text-align:center;">
    <table>
        <tr>
            <td style="width: 20%;">Idle</td>
            <td style="text-align: left;">Displays all idle employees with the designation matching the demand request.</td>
        </tr>
    </table>
</div>

<div>
    <img src="../../images/idle employees in demand allocation.png" alt="idle employees in demand allocation" style="border-radius: 10px; width: 50%; height: 50%; border: 0.5px solid #333;">
</div>

<div style="text-align:center;">
    <table>
        <tr>
            <td style="width: 20%;">Known Trade</td>
            <td style="text-align: left;">Shows employees who have the trade specified in the demand request.</td>
        </tr>
    </table>
</div>

<div>
    <img src="../../images/known trade.png" alt="known trade" style="border-radius: 10px; width: 50%; height: 50%; border: 0.5px solid #333;">
</div>

**Check related topic for How to add known trade for Site Staff**

<div style="text-align:center;">
    <table>
        <tr>
            <td style="width: 20%;">Other Employee</td>
            <td style="text-align: left;">Lists all employees currently in the company.</td>
        </tr>
    </table>
</div>

<div>
    <img src="../../images/other employee.png" alt="other employee" style="border-radius: 10px; width: 50%; height: 50%; border: 0.5px solid #333;">
</div>

### Employee Fields

<div>
    <img src="../../images/fields in demand request allocation of employee.png" alt="fields in demand request allocation of employee" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>

<strong>User ID:</strong>
Employee ID from the employee master (Staff/Site Staff/Supplier Labour).

<strong>Name:</strong>
Employee name from the employee master (Staff/Site Staff/Supplier Labour).

<strong>Previous ID:</strong>
Previous employee ID from the employee master (Staff/Site Staff/Supplier Labour).

<strong>Passport Number:</strong>
Passport number of the employee.

<strong>Nationality:</strong>
Nationality of the employee.

<strong>Trade:</strong>
Current trade of the employee as specified in Job Details of Employee master.

<strong>Trade Change:</strong>
Select the trade in which the employee is allocated, the same trade will be used for mobilization. (Painter can be mobilized as Accountant). Only trade mentioned in demand request can be selected. 

<div>
    <img src="../../images/trade change.png" alt="trade change" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>

<strong>Project Rate:</strong>
Select the rate type and rate for the employee's allocation 

   >	data is shown from the approved rates in the project master under **Business Development** **->** **Basic** **->** **Project** **->** **Approved Rates**.

<div>
    <img src="../../images/Project rate.png" alt="Project rate" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>

**Check related topic for creating project rate**

<strong>Camp:</strong>
Current camp of the employee.

<strong>Supplier:</strong>
Supplier name if the employee is supplier labour.

<strong>Check-In Issued Date:</strong>
(Shown only if Check-Paper is enabled)

   >	**Accommodation** **->** **Settings** **->** **Enable**: “Show CheckIn employees in Camp Allocation Queue”.

<div>
    <img src="../../images/Check-In Issued Date enabling.png" alt="Check-In Issued Date enabling" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>

<strong>Sale Rate:</strong>
The rate given in the project master for the designation mentioned in Trade Change. 

   >	The latest rate will be shown **Business Development** **->** **Basic** **->** **Project** **->** **Approved Rates**.

<div>
    <img src="../../images/sale rate.png" alt="sale rate" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>

### Purchase Rate
The rate given for the employee on the date of allocation for the trade mentioned in Trade Change.

 #### ***Rate Considerations***

<strong>Own Staff/Site Staff:</strong>
Purchase rate is taken from the designation master. If a known trade is given for the designation, that rate will be shown.

<div style="display: flex; gap: 10px;">
  <img src="../../images/salary seeting using designation.png" style="width: 100%; ">
  <img src="../../images/known trading adding for specific employee.png" style="width: 100%; ">
</div>

<strong>Supplier Labour:</strong>
Purchase rate is taken from the Supplier or Supplier Labour master based on settings 

   >	**Procurement** **->** **Settings** **->** **Use Rate in Supplier Labour as purchase rate is enabled, otherwise from supplier master**.

<div>
    <img src="../../images/use rate in supplier labour as purchase rate.png" alt="use rate in supplier labour as purchase rate" style="border-radius: 10px; width: 50%; height: 50%; border: 0.5px solid #333;">
</div>

<div style="text-align:left;">
    <ul>
        <li>If project rate is selected in demand request allocation, the rate with the specified rate type will be shown.</li>
        <li>If the any rate type is given for employee in supplier labour master (Job Details -> Rate type) then only the rate with that rate type will be considered. </li>
        <li>If the employee has a rate for the designation and project mentioned in the demand request, it will be shown.</li>
        <li>If not, the latest rate with the effective date for this trade will be shown.</li>
    </ul>
</div>

<strong>Rate Input:</strong>

   >	If Purchase rate is taken from Supplier Labour, a new rate can be added from demand request allocation **Enable Operation** **->** **Settings** **->** **Enable Rate Input in Demand Request**.

<div>
    <img src="../../images/enable rate input in demand request.png" alt="enable rate input in demand request" style="border-radius: 10px; width: 50%; height: 50%; border: 0.5px solid #333;">
</div>

<br>

<div style="text-align:left;">
    <ul>
        <li>Once the settings is enabled then select any supplier labour and change their purchase rate and click allocate. </li>
        <li>Then a rate update request form will be shown.  </li>
    </ul>
</div>

<br>

<div style="display: flex; gap: 10px;">
  <img src="../../images/rate update in demand request allocation.png" style="width: 100%; ">
  <img src="../../images/rate update  new rate.png" style="width: 100%; ">
</div>

<br>

<div style="text-align:left;">
    <ul>
        <li>Supplier labour who has new rate there will new rate label and if new rate is not given then it will show existing. </li>
    </ul>
</div>

<br>

<div style="display: flex; gap: 10px;">
  <img src="../../images/rate update request.png" style="width: 100%; ">
  <img src="../../images/rate update request form.png" style="width: 100%; ">
</div>

<br>

<div style="text-align:left;">
    <ul>
        <li>Click on approve and save then new rate will be updated in supplier labour master. (Only employees with new rate will have rate update in supplier labor master). </li>
        <li>If workflow is define then there will be an approval form for request. </li>
    </ul>
</div>

<br>

<div>
    <img src="../../images/new added supplier labour rate.png" alt="new added supplier labour rate" style="border-radius: 10px; width: 50%; height: 50%; border: 0.5px solid #333;">
</div>

<br>

Once the allocation is done then click on fully allocated checkbox and save the request to create noc. 

### Related Topics

* [How to Setup Approved Rate ?](../../Business%20Development/Basic/Project.md)
* [How to add known trade for staff ?](../../hr/basic-Setup/Site-Staff.md)
