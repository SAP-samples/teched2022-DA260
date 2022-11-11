# Chapter 3 - Consolidation of business partner master data

Estimated time: 30 minutes

## Objective

A single source of truth for master data is essential. SAP Master Data Governance lets you integrate data from SAP and non-SAP systems or other sources to reach this goal. In this chapter, you will learn the basics for working with the consolidation capabilities of SAP Master Data Governance. You will start with the import of source data in spreadsheet format and the creation of a consolidation process. Then you will examine the results of each process step. Furthermore, you will learn how to use the match review to understand the result of matching and how to work with match groups and the result of the best record calculation.

Another feature that is highlighted in this chapter, is the derivation of master data as part of the process that can be used, for example to create ERP customer data.

## Exercise Description

This exercise is split in 7 parts. It is required to perform each step after the other. Please note that besides the short exercise description there is also a detailed [step-by-step description](../supplements/DA260_Exercises_Solutions.pdf) provided.

### Exercise 3.1 – Import business partners from spreadsheet file

You have some customer data with addresses, and phone numbers, and more in a spreadsheet file. This file is available for download: [DA260.xlsx](./DA260.xlsx). You can upload this file using the app Import Data for Consolidation (Business Partners).

Important: Download the spreadsheet [DA260.xlsx](./DA260.xlsx) to use it in this exercise.

### Exercise 3.2 - Create and start consolidation process

After having imported the data from the file, you start a consolidation process.

### Exercise 3.3 - Validate imported data

After an initial check you review the uploaded data and can make manual changes.

### Exercise 3.4 - Enhance and standardize addresses

In this exercise, you use the address standardization functionality of SAP Data Quality Management that is integrated in SAP Master Data Governance to validate and correct the addresses in the uploaded data.

Note: SAP Data Quality Management requires an additional license besides SAP Master Data Governance. For legal reasons, the system that is used in this workshop is only set up for a very limited range of addresses.

### Exercise 3.5 - Find duplicates

The consolidation process that you run uses features of SAP HANA that are integrated in SAP Master Data Governance for searching and matching. These features are applied to the uploaded data to detect duplicates in the uploaded data and to identify corresponding data that is already in the system. This results in match groups of identical, or at least similar records.

### Exercise 3.6 - Merge duplicates with best record calculation

After the match review and your decision on match groups in status open, the best record calculation will merge the data of each match group.

### Exercise 3.7 – Automated creation of ERP customer data

To demonstrate capabilities of derivation rules for automating master data processes, the consolidation process of this exercise uses the step Derivation to enhance the business partners for using them as customers in ERP processes. In this example, business partner grouping, roles, and general customer data are added. Furthermore, example data on company code-level is derived.

### Exercise 3.7 - Finalize consolidation process

Eventually, the validation and activation steps will bring the loaded data into the system. After finalizing the process, you can check all actions inside this process using the audit trail functionality. Of course you can also use the app Manage Customer to review the created and updated business partners.

## Step-by-Step Description

Follow [DA260_Exercises_Solutions.pdf](../supplements/DA260_Exercises_Solutions.pdf) to perform this exercise.

## Summary

You have completed chapter 3. You have learned:

- how you can upload data for import and consolidation in MDG.
- possibilities for validation and address enrichment, as well as for matching and merging of imported data.
- to know some of the capabilities for automating master data processes with derivation rules.

You've now completed all exercises that we prepared for you.

Thank you for joining!
