## **INV-0005:** Inventory Testing - Edit Area  

> **Summary:** Verify that admin user successfully modified and displayed an area.  <br>

**Preconditions:** An admin user is logged in in the system.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Visit the web-app.    | Verify that login page is shown.  | 
 |  2 |  Log-in using your admin account.   | Verify that inventory page or inspection page is shown.   | 
 |  3 |  In the sidebar, click `Inventory` menu item.   | Verify that invetory page is shown.   |
 |  4 |  Click the `Floor` that you want to add area with.   | Verify that floor page  is shown shown.   |
 |  5 |  Click the `Edit` button on the area you want to modifiy.   | Verify that you can type in the field for the new name.   |  
 |  6 |  Click the `Area` textfield.   | Verify that you can type in the field.   |  
 |  7 | Click the `Save` button.   | Verify that the changes in the area is saved in the database and displayed.   |  

**Post-conditions:**  

 - The area is modified and displayed
