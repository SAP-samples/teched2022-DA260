# Chapter 2 - Validation rules for master data quality management

Estimated time: 30 minutes

## Objective

Learn about the key capabilities of master data quality management in SAP MDG, such as validation rules, data quality evaluation and analysis of the results, and how to efficiently correct erroneous master data. Furthermore, you will see other capabilities related to data quality, namely duplicate prevention and address validation and enrichment.

## Exercise Description

This exercise is split in 4 parts. It is required to perform each step after the other. Please note that besides the short exercise description there is also a detailed [step-by-step description](../supplements/DA260_Exercises_Solutions.pdf) provided.

### Exercise 2.1 – Submit request for new customer

In this exercise, you will be a business user requesting a new customer. You will again send an SAP MDG Change Request which shall be further processed by other users in your company. You will see how MDG helps you to prevent the creation of duplicate master data records. Furthermore, you will use address validation and enrichment to achieve high quality master data.

### Exercise 2.2 – Management and definition of validation rules

This exercise is a demonstration provided by your instructor in the workshop. You will watch while changes are executed to the system that are explaining the system behavior and that will be important for the next exercise. Using you own system user you can display and examine all changes done by the presenter. However, your user does not have authorization to change anything. Only after these changes have been done centrally for all users of the system, you can continue with the next exercise.

In this demonstration, you will watch the instructor in the role of a master data steward. A new SAP MDG validation rule will be created that introduces a new check to all business partner data representing persons. Only after these changes have been done centrally for all users of the system, you can continue with the next exercise.

### Exercise 2.3 – Re-check requested customer

_Important_: This exercise can only start after the instructor has changed the system settings as outlined in the exercise 2.2 above. Please wait until you are asked to begin this exercise.

In this exercise, you will use the change request that you created in Exercise 2.1 and just re-check the same data. As you will notice, the system will now act differently since a new validation rule has been introduced. After the issue has been detected, you will use the workflow and collaboration features in SAP MDG to correct the data issue.

### Exercise 2.4 – Find and fix errors in existing data

In this exercise, you will investigate the results of the system-driven regular evaluation of the master data quality. You will analyze the results and then execute some improvements of the quality by changing the erroneous master data records. For example, there might be some records that had been created before the new rule on titles for persons had been activated. These records hence now need to be found and corrected.

Note: as other users work in parallel and might change data, the figures displayed on the screenshot of this exercise might vary, except where explicitly noted.

## Step-by-Step Description

Follow [DA260_Exercises_Solutions.pdf](../supplements/DA260_Exercises_Solutions.pdf) to perform this exercise.

## Summary

You have completed chapter 2. You have learned:

- how you can introduce new master data validation rules based on business needs
- the capabilities for data quality evaluation and analysis of the result
- which possibilities are offered to efficiently correct data – directly from the evaluation analysis

Continue to - [Exercise 3](../ex3/README.md)
