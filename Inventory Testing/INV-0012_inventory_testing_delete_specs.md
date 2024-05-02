## **INV-0012:** Inventory Testing - Delete Specs  

> **Summary:** Verify that admin user successfully deleted a specs.  <br>

**Preconditions:** An admin user is logged in in the system.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Visit the web-app.    | Verify that login page is shown.  | 
 |  2 |  Log-in using your admin account.   | Verify that inventory page or inspection page is shown.   | 
 |  3 |  In the sidebar, click `Inventory` menu item.   | Verify that invetory page is shown.   |
 |  4 |  Click the `Floor` that you want to delete specs with.   | Verify that floor page  is  shown.   |  
 |  5 |  Click the `Area` that you want to delete specs with.   | Verify that area page  is  shown.   |
 |  6 |  Click the `Equipement` that you want to delete specs with.   | Verify that specs page  is  shown.   |
 |  7 |  Click the `Delete ` button to the specs that you want to modify.   | Verify that the confirmation modal is shown.   |  
 |  8 |  Click the `OK` button.   | Verify that the specs is deleted in the database and is no longer displayed.   |  
 
**Post-conditions:**  

 -  - The specs is deleted and no longer displayed
