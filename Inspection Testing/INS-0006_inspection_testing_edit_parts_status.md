## **INS-0006:** Inspection Testing - Edit Parts Status  

> **Summary:** Verify that admin user successfully modified and displayed parts status.  <br>

**Preconditions:** _None_  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Visit the web-app.    | Verify that the logged in page is shown.   | 
 |  2 |  Log-in using your account.   | Verify that the inspection page is shown.   | 
 |  3 |  In the sidebar, click Inspection menu item.   | Verify that inspection floor page is shown.  | 
 |  4 |  Choose and click a floor entity.  | Verify that inspection floor Page is shown.  |
 |  5 |  Choose and click an area entity.  | Verify that the equipment that needs to be inspect under that area is shown.  |
 |  6 |  Click the parts button of the specific equipment.  | Verify that inspection parts page is shown.  |
 |  7 |  Click the edit button of the specific displayed equipment parts.  | Verify that the dropdown button is shown.  |
 |  8 |  Click and select the status of the equipment parts.  | Verify that the selected status is displayed. |
 |  9 |  Click the save button. | Verify that the equipment part status is changed and the status counter is displayed. |
 
**Post-conditions:**  

The edited equipment parts status are saved in the database.
