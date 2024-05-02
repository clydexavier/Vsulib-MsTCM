## **INS-0005:** Inspection Testing - Edit Equipment Status  

> **Summary:** Verify that admin user successfully modified and displayed equipment status.  <br>

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
 |  7 |  After parts inspection, click the dropdown button of the status of the equipment part.  | Verify that the status selection button will be shown.  |
 |  8 |  Select the status of the equipment part.  | Verify that the selected status is displayed. |
 |  9 |  Click the update button. | Verify that the equipment status is changed and displayed in the textbox. |

**Post-conditions:**  

The edited equipment status are saved in the database.
