# DA260 - Hands-On Experience with SAP Master Data Governance

## Description

This repository contains the material for the SAP TechEd 2022 session called DA260 - Hands-On Experience with SAP Master Data Governance.  

## Overview

This session gives you a hands-on introduction into selected topics of SAP Master Data Governance. Please visit the [SAP Master Data Governance community](https://www.sap.com/community/topics/master-data-governance.html) on sap.com for a comprehensive description on the product.

Due to time constraints of a 2 hours session, we selected the following functional areas for exercises:

### Chapter 1: Central Master Data Governance

Estimated Duration: 30 minutes

As a business user, you will request the creation of a new product. Then an expert will add additional product information and an approver will complete the processing of the request until the final creation of the product.

### Chapter 2: Master Data Quality Management

Estimated Duration: 30 minutes

You will analyze the data quality situation in the system using rules that were defined in the system's data quality rule repository. You will drill down from the data quality dashboard to the erroneous product master data and start the correction from there. (During this exercise, we will ask you to pause for the presenter to do some settings in the system that will change the system behavior. It is hence important that all participants start exercise together at the same time.)

### Chapter 3: Master Data Consolidation

Estimated Duration: 20 minutes

You will import business partner master data from an Excel spreadsheet, cleanse & enrich the data, match the business partners with existing data in the system, until having consolidated master data in your master data hub.

## Requirements

The system used in this session is based on _SAP Master Data Governance on SAP S/4HANA OP 2021 (Feature Pack 2)_. Please note that even though SAP MDG is delivered together with SAP S/4HANA, additional licenses on top of SAP S/4HANA are required to use SAP Master Data Governance. For more information see the [SAP Master Data Governance community](https://www.sap.com/community/topics/master-data-governance.html) on sap.com.

In this session we will solely use the SAP Fiori Launchpad to access the SAP MDG system. We will not use SAP Logon nor the NetWeaver Business Client environment to access the system.

Each participant in the workshop has their participant number, which you find at your table. This number will be used to distinguish the user ID with which you will log on to the system and the objects that you will handle in the system. During the exercise, you might also see objects belonging to other groups. Make sure to work only with your dedicated user ID and with your own objects, not to disturb the work of your peer groups. Your participant number is written on the sign at your table.

Your user ID to log on is: _DA260-##_ - ## represents your participant number. For example enter DA260-04 or DA260-23

Your password is: _will only be shared on-site_

Launchpad URL: [https://teched.mdg.cloud.sap:44301/sap/bc/ui2/flp](https://teched.mdg.cloud.sap:44301/sap/bc/ui2/flp)

## Exercises

- [Chapter 1 – Request & Approve Material Creation](exercises/ex1/)
  - [Exercise 1.1 – Logon, search and then request a new material](exercises/ex1#ex1.1)
  - [Exercise 1.2 – Process and enhance the material request](exercises/ex1#ex1.2)
  - [Exercise 1.3 - Approve the request and activate the new material](exercises/ex1#ex1.3)
- [Chapter 2 – Validation rules for master data quality management](exercises/ex2/)
  - [Exercise 2.1 – Submit request for new customer](exercises/ex2/)
  - [Exercise 2.2 – Management and definition of validation rules](exercises/ex2/)
  - [Exercise 2.3 – Re-check requested customer](exercises/ex2/)
  - [Exercise 2.4 – Find and fix errors in existing data](exercises/ex2/)
- [Chapter 3 – Consolidation of business partner master data](exercises/ex3/)
  - [Exercise 3.1 – Import business partners from spreadsheet file](exercises/ex3/)
  - [Exercise 3.2 - Create and start consolidation process](exercises/ex3/)
  - [Exercise 3.3 - Validate imported data](exercises/ex3/)
  - [Exercise 3.4 - Enhance and standardize addresses](exercises/ex3/)
  - [Exercise 3.5 - Find duplicates](exercises/ex3/)
  - [Exercise 3.6 - Merge duplicates with best record calculation](exercises/ex3/)
  - [Exercise 3.5 - Finalize consolidation process](exercises/ex3/)

## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License

Copyright (c) 2022 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
