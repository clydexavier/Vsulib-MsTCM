## **INS-0004:** Inspection Testing - Display Parts  

> **Summary:** Verify that parts is saved and displayed succesfully.  <br>

**Preconditions:** Equipment parts are displayed in the database.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Visit the web-app.    | Verify that the logged in page is shown.   | 
 |  2 |  Log-in using your account.   | Verify that the inspection page is shown.   | 
 |  3 |  In the sidebar, click Inspection menu item.   | Verify that inspection floor page is shown.  | 
 |  4 |  Choose and click a floor entity.  | Verify that inspection floor Page is shown.  |
 |  5 |  Choose and click an area entity.  | Verify that the equipment that needs to be inspect under that area is shown.  |
 |  6 |  Click the parts button of the specific equipment.  | Verify that inspection parts page is shown which includes the list of all parts of the equipment.  |

**Post-conditions:**  None
