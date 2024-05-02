## **INV-0002:** Inventory Testing - Edit Floor  

> **Summary:** Verify that admin user successfully modified and displayed a floor.  <br>

**Preconditions:** An admin user is logged in in the system.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Visit the web-app.    | Verify that login page is shown.  | 
 |  2 |  Log-in using your admin account.   | Verify that inventory page or inspection page is shown.   | 
 |  3 |  In the sidebar, click `Inventory` menu item.   | Verify that invetory page is shown.   |
 |  4 |  Click the `Edit` button on the floor you want to modifiy.   | Verify that you can type in the field for the new name.   |  
 |  5 |  Click the `Floor` textfield.   | Verify that you can type in the field.   |  
 |  6 | Click the `Save` button.   | Verify that the changes in the floor is saved in the database and displayed.   |  

**Post-conditions:**  

 - The floor is modified and displayed
