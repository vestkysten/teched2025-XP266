# Exercise 2 - Maintain your Feature in Cloud ALM

In this exercise, we will check whether the connection between SAP Cloud ALM and SAP Cloud Transport Managemeent service has been established properly. This will enable the usage of Features in SAP Cloud ALM to transport changes throghout your landscape. The Creation of the Feature will be part of the exercise.

## Exercise 2.0 - Check your Cloud ALM and cTMS configuration

1. Go to the BTP Cockpit of your SAP Cloud ALM subaccount.
2. Open the Destinations view (to be found in the Connectivity area in the navigation pane).
3. Search for destination CALM_FTR_CTMS_<Account_ID>
4. Click Check Connection. The result shall be "HTTP request to destination succeeded".
 
## Exercise 2.1 - Create a new Feature

1. Open SAP Cloud ALM.
2. Go to the Features application.
3. Select your project named ...
4. Click Create in the top right corner.
5. Add a meaningful name to your Feature.
6. Add a Description.
7. In the Additional Infromation section change the priority to "High" and select yourself as Responsible.
8. Click on Save and Close.
9. Your Feature is saved and shows up in the Features Overview list on the left hand side.

## Summary

You've now created the Feature for later usage in the deployment process.

Continue to - [Develop your pro-code application](../ex3/README.md)
