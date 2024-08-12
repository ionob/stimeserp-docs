# Salary Structure

## Overview

The Salary Structure module in our ERP system allows users to define the structure of employee salaries. This includes setting up various salary heads, defining hourly rates, and categorizing components into basic/common and special types.

<div>
    <img src="../../images/Salary Structures.png" alt="Salary Structures" style="border-radius: 10px; width: 70%; height: 70%;border: 0.5px solid #333;">
</div>

### How to Creating a Salary Component

>	Go to **Payroll** **→** **Basic** **→** **Salary Structures**.

<h4>Add New Structure</h4>
Click on the <b>Create Structure</b> button. A form will appear to enter details about the new structure.

<div style="display: flex; gap: 10px;">
  <img src="../../images/create Salary Structures.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../../images/create structure.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

<h4>Salary Structure Field Exploration</h4>
<div style="text-align:left;">
    <ul>
        <li><strong>Document No:</strong> Input the document number for the salary structure listing. This is a unique identifier for each salary structure.</li>
        <li><strong>Name:</strong> Input the name of the salary structure, such as "Basic with Flat," "Basic with Overtime," etc. This name should clearly describe the structure for easy identification.</li>
        <li><strong>Salary Head:</strong> Static input from the software. Select the appropriate salary head based on the employee's salary details. There are four types of salary heads to choose from:</li>
            <ol><strong>Hourly with Overtime Rate:</strong> Allows manual input for rates.</ol>
            <ol><strong>Hourly with Flat Rate:</strong> The NOT, HOT, and WOT rates per hour are always set to 1.</ol>
            <ol><strong>Basic with Overtime Rate:</strong> Allows manual input for rates.</ol>
            <ol><strong>Basic with Flat Rate:</strong> The NOT, HOT, and WOT rates per hour are always set to 1.</ol>
        </ul>
</div>

<div>
    <img src="../../images/salary head.png" alt="salary head" style="border-radius: 10px; width: 70%; height: 70%;border: 0.5px solid #333;">
</div>

<div style="text-align:left;">
    <ul>
        <li><strong>Hour Rate Definition:</strong> This section appears based on the selected salary head. It defines how hourly rates are calculated.</li>
            <ol><strong>For Basic-related Salary Heads:</strong> Four fields are available</ol>
    </ul>
</div>
<div style="text-align:center;">
    <table>
        <tr>
            <td style="width: 20%;">Basic Rate Definition</td>
            <td style="text-align: left;"> Equation used for calculating the basic rate per hour.</td>
        </tr>
        <tr>
            <td style="width: 20%;">WOT Rate Per</td>
            <td style="text-align: left;">Manually input the WOT (Weekly Overtime) rate.</td>
        </tr>
        <tr>
            <td style="width: 20%;">HOT Rate Per</td>
            <td style="text-align: left;">Manually input the HOT (Holiday Overtime) rate.</td>
        </tr>
        <tr>
            <td style="width: 20%;">NOT Rate Per</td>
            <td style="text-align: left;">Manually input the NOT (Normal Overtime) rate.</td>
        </tr>
    </table>
</div>

<div>
    <img src="../../images/hour rate definition in basic.png" alt="hour rate definition in basic" style="border-radius: 10px; width: 70%; height: 70%;border: 0.5px solid #333;">
</div>

<div style="text-align:left;">
    <ul>
            <ol><strong>For Hourly-related Salary Heads:</strong> Three fields are available:</ol>
    </ul>
</div>
<div style="text-align:center;">
    <table>
        <tr>
            <td style="width: 20%;">NOT Rate Per</td>
            <td style="text-align: left;">Manually input the NOT rate.</td>
        </tr>
        <tr>
            <td style="width: 20%;">WOT Rate Per</td>
            <td style="text-align: left;">Manually input the WOT rate.</td>
        </tr>
        <tr>
            <td style="width: 20%;">HOT Rate Per</td>
            <td style="text-align: left;">Manually input the HOT rate.</td>
        </tr>
    </table>
</div>

<div>
    <img src="../../images/hour rate definition in hourly.png" alt="hour rate definition in hourly" style="border-radius: 10px; width: 70%; height: 70%;border: 0.5px solid #333;">
</div>

<div style="text-align:left;">
    <ul>
        <li><strong>Basic/Common Components:</strong> These are equation-oriented components that may include variable pay.</li>
        <li><strong>To create an equation:</strong></li>
            <ol>Select the component name in the equation field.</ol>
            <ol>Double-click in the equation column to open the equation form and input the necessary details.</ol>
        </ul>
</div>

<div style="display: flex; gap: 10px;">
  <img src="../../images/variable components.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../../images/variable components equation.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

<div style="text-align:left;">
    <ul>
        <li><strong>Special Components:</strong> These are used for fixed components that are not variable.</li>
    </ul>
</div>

<div>
    <img src="../../images/fixed component.png" alt="fixed component" style="border-radius: 10px; width: 70%; height: 70%;border: 0.5px solid #333;">
</div>

<div style="text-align:left;">
    <ul>
        <li><strong>Per Day Amount Definition (for Leave Settlement):</strong> An equation can be defined to calculate the per day amount used in leave settlements. This allows for accurate leave encashment based on specific criteria.</li>
    </ul>
</div>

<div>
    <img src="../../images/Per Day Amount Definition (for Leave Settlement).png" alt="Per Day Amount Definition (for Leave Settlement)" style="border-radius: 10px; width: 70%; height: 70%;border: 0.5px solid #333;">
</div>

<div style="text-align:left;">
    <ul>
        <li><strong>Gratuity Days Definition:</strong> The salary structure can include an equation to define gratuity days. This is used to calculate the gratuity amount based on the number of days eligible under company policy.</li>
    </ul>
</div>

<div>
    <img src="../../images/gratuity days definition.png" alt="gratuity days definition" style="border-radius: 10px; width: 70%; height: 70%;border: 0.5px solid #333;">
</div>

<div style="text-align:left;">
    <ul>
        <li><strong>Saving the Salary Structure: </strong> Once all fields are completed, click the <b>Save</b> button to create the salary structure.</li>
    </ul>
</div>