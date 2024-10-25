# Employee Payments

## Overview

You can create a new Employee Payment by clicking the New Payment button. This will open a form where you can select payment details based on the payment type and mode.

<div>
    <img src="../../images/employee payments.png" alt="employee payments" style="border-radius: 10px; width: 70%; height: 70%;border: 0.5px solid #333;">
</div>

### Step 1: Select Payment Type

First, choose the type of payment from the following options:

<div style="text-align:left;">
    <ul>
        <li><strong>Labour Salary</strong></li>
        <li><strong>Staff Salary</strong></li>
        <li><strong>Loan Advance</strong></li>
        <li><strong>Final Settlement</strong></li>
    </ul>
</div>

### Step 2: Select Payment Mode

Next, choose the payment mode:

<div style="text-align:left;">
    <ul>
        <li><strong>Cash</strong></li>
        <li><strong>Bank</strong></li>
        <li><strong>PDC (Post-Dated Cheque)</strong></li>
    </ul>
</div>

## Payment Forms Based on Type and Mode

Each selection combination will have specific fields to fill out. Here’s a breakdown:

### If You Select Cash Payment Mode:

<div style="text-align:left;">
    <ul>
        <h3>Labour Salary or Staff Salary</h3>
            <li><strong>Doc No:</strong> Auto-generated</li>
            <li><strong>Date</strong></li>
            <li><strong>Cash Document:</strong> select a cash document, the account will auto-fill and be disabled</li>
            <li><strong>Specific Fields:</strong> Labour Salary / Staff Salary</li>
                <ol>Salary Month: Select the relevant month. The system will display Invoice Details.</ol>
                <ol>Invoice Details:Month, Employee Name, Account, Cash/Credit, Amount, and Paying Amount.</ol>
            <li><strong>Document Upload</strong></li>
            <li><strong>Narration</strong></li>
            <li><strong>Grand Total:</strong> Total amount for the payment</li>
            <li><strong>Status:</strong> Choose Open, Approve, or Reject</li>
    </ul>
</div>

<div>
    <img src="../../images/labour salary cash.png" alt="labour salary cash" style="border-radius: 10px; width: 70%; height: 70%;border: 0.5px solid #333;">
</div>

<div style="text-align:left;">
    <ul>
        <h3>Loan Advance or Final Settlement</h3>
            <li><strong>Doc No:</strong> Auto-generated</li>
            <li><strong>Date</strong></li>
            <li><strong>Cash Document:</strong> select a cash document, the account will auto-fill and be disabled</li>
            <li><strong>Request</strong></li>
            <li><strong>Specific Fields:</strong> Loan Advance</li>
                <ol>Request: Choose a request. Invoice Details will show the linked invoice details.</ol>
                <ol>Invoice Details:Month, Employee Name, Account, Cash/Credit, Amount, and Paying Amount.</ol>
            <li><strong>Specific Fields:</strong> Final Settlement</li>
                <ol>Request: Choose the relevant request.</ol>
                <ol>Invoice Details:Month, Employee Name, Account, Cash/Credit, Amount, and Paying Amount.</ol>
            <li><strong>Document Upload</strong></li>
            <li><strong>Narration</strong></li>
            <li><strong>Grand Total:</strong> Total amount for the payment</li>
            <li><strong>Status:</strong> Choose Open, Approve, or Reject</li>
    </ul>
</div>

<div>
    <img src="../../images/loan advance cash.png" alt="loan advance cash" style="border-radius: 10px; width: 70%; height: 70%;border: 0.5px solid #333;">
</div>

### If You Select Bank Payment Mode:

<div style="text-align:left;">
    <ul>
        <h3><strong>Labour Salary or Staff Salary</strong></h3>
            <li><strong>Doc No:</strong> Auto-generated</li>
            <li><strong>Date</strong></li>
            <li><strong>Bank Document:</strong> select a bank document, the account will auto-fill and be disabled</li>
            <li><strong>Cheque No:</strong> Enter the cheque number</li>
            <li><strong>Cheque Date:</strong> Date of the cheque</li>
            <li><strong>Specific Fields:</strong> Labour Salary / Staff Salary</li>
                    <ol>Salary Month: Select the month, and the Invoice Details will display</ol>
                    <ol>Month, Employee Name, Account, Cash/Credit, Amount, and Paying Amount.</ol>
            <li><strong>Document Upload</strong></li>
            <li><strong>Narration</strong></li>
            <li><strong>Grand Total:</strong> Total amount for the payment</li>
            <li><strong>Status:</strong> Choose Open, Approve, or Reject</li>
    </ul>
</div>

<div>
    <img src="../../images/staff salary bank.png" alt="staff salary bank" style="border-radius: 10px; width: 70%; height: 70%;border: 0.5px solid #333;">
</div>

<div style="text-align:left;">
    <ul>
        <h3><strong>Loan Advance or Final Settlement</strong></h3>
            <li><strong>Doc No:</strong> Auto-generated</li>
            <li><strong>Date</strong></li>
            <li><strong>Bank Document:</strong> select a bank document, the account will auto-fill and be disabled</li>
            <li><strong>Cheque No:</strong> Enter the cheque number</li>
            <li><strong>Cheque Date:</strong> Date of the cheque</li>
            <li><strong>Specific Fields:</strong> Loan Advance</li>
                <ol>Request: Select the request. Invoice Details will be shown for the selected request.</ol>
            <li><strong>Specific Fields:</strong> Final Settlement</li>
                <ol>Request: Choose the applicable request.</ol>
            <li>><strong>Document Upload</strong></li>
            <li><strong>Narration</strong></li>
            <li><strong>Grand Total:</strong> Total amount for the payment</li>
            <li><strong>Status:</strong> Choose Open, Approve, or Reject</li>
    </ul>
</div>

<div>
    <img src="../../images/final settlment bank.png" alt="final settlment bank" style="border-radius: 10px; width: 70%; height: 70%;border: 0.5px solid #333;">
</div>

### If You Select PDC (Post-Dated Cheque) Payment Mode:

<div style="text-align:left;">
    <ul>
        <h3><strong>Labour Salary or Staff Salary</strong></h3>
            <li><strong>Doc No:</strong> Auto-generated</li>
            <li><strong>Date</strong></li>
            <li><strong>Bank Document:</strong> select a bank document, the account will auto-fill and be disabled</li>
            <li><strong>Cheque No:</strong> Enter the cheque number</li>
            <li><strong>Cheque Date:</strong> Date of the cheque</li>
            <li><strong>Specific Fields:</strong> Labour Salary / Staff Salary</li>
                <ol>Salary Month: Choose the month, and relevant Invoice Details will appear.</ol>
            <li><strong>Document Upload</strong></li>
            <li><strong>Narration</strong></li>
            <li><strong>Grand Total:</strong> Total amount for the payment</li>
            <li><strong>Status:</strong> Choose Open, Approve, or Reject</li>
    </ul>
</div>

<div>
    <img src="../../images/labour salary pdc.png" alt="labour salary pdc" style="border-radius: 10px; width: 70%; height: 70%;border: 0.5px solid #333;">
</div>

<div style="text-align:left;">
    <ul>
        <h3><strong>Loan Advance or Final Settlement</strong></h3>
            <li><strong>Doc No:</strong> Auto-generated</li>
            <li><strong>Date</strong></li>
            <li><strong>Bank Document:</strong> select a bank document, the account will auto-fill and be disabled</li>
            <li><strong>Cheque No:</strong> Enter the cheque number</li>
            <li><strong>Cheque Date:</strong> Date of the cheque</li>
            <li><strong>Specific Fields:</strong> Loan Advance</li>
                <ol>Request: Select the request, and the system will display Invoice Details.</ol>
            <li><strong>Specific Fields:</strong> Final Settlement</li>
                <ol>Request: Select the relevant request.</ol>
            <li><strong>Document Upload</strong></li>
            <li><strong>Narration</strong></li>
            <li><strong>Grand Total:</strong> Total amount for the payment</li>
            <li><strong>Status:</strong> Choose Open, Approve, or Reject</li>
    </ul>
</div>

<div>
    <img src="../../images/final settlement pdc.png" alt="final settlement pdc" style="border-radius: 10px; width: 70%; height: 70%;border: 0.5px solid #333;">
</div>

## Saving and Editing

<div style="text-align:left;">
    <ul>
        <li>After filling out the fields, click Save to create the payment entry.</li>
        <li>The entry can be edited if the status is Open.</li>
        <li>If the payment is Approved, it cannot be edited.</li>
    </ul>
</div>

<div>
    <img src="../../images/status in employee payments.png" alt="status in employee payments" style="border-radius: 10px; width: 70%; height: 70%;border: 0.5px solid #333;">
</div>