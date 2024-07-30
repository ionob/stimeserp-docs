# Demand Request Allocation

## Overview
The Demand Request Allocation feature is designed to facilitate the allocation of employees to fulfill demand requests. This module allows users to efficiently assign employees based on their current status, trade, and other relevant criteria to meet the requirements of various projects.

<div>
    <img src="../../images/Demand Request List.png" alt="Demand Request List" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
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

<strong>Sale Rate:</strong>
The rate given in the project master for the designation mentioned in Trade Change. 

   >	The latest rate will be shown **Business Development** **->** **Basic** **->** **Project** **->** **Approved Rates**.

<div>
    <img src="../../images/sale rate.png" alt="sale rate" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">
</div>

<strong>Purchase Rate:</strong>
The rate given for the employee on the date of allocation for the trade mentioned in Trade Change.

### Rate Considerations

<strong>Own Staff/Site Staff:</strong>
Purchase rate is taken from the designation master. If a known trade is given for the designation, that rate will be shown.

<strong>Supplier Labour:</strong>
Purchase rate is taken from the Supplier or Supplier Labour master based on settings 

   >	**Procurement** **->** **Settings** **->** **Use Rate in Supplier Labour as purchase rate is enabled, otherwise from supplier master**.

<strong>Project Rate:</strong>
If project rate is selected in demand request allocation, the rate with the specified rate type will be shown.

<strong>Employee Rate Type:</strong>
If any rate type is given for an employee in the Supplier Labour master 

   >	**Job Details** **->** **Rate Type**, only the rate with that rate type will be considered.

<strong>Demand Request Rate:</strong>
If the employee has a rate for the designation and project mentioned in the demand request, it will be shown. If not, the latest rate with the effective date for this trade will be shown.

<strong>Rate Input:</strong>

   >	If Purchase rate is taken from Supplier Labour, a new rate can be added from demand request allocation **Enable Operation** **->** **Settings** **->** **Enable Rate Input in Demand Request**.

### Related Topics

* [How to Setup Approved Rate ?](../../Business%20Development/Basic/Project.md)
